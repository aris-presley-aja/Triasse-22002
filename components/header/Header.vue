<template>
  <div class="kepala">
    <nav class="navbar" role="navigation" aria-label="main navigation">
      <!-- <div class="navbar-brand">
                        <nuxt-link :to="{ name: 'index' }" class="navbar-item">
         <h3 class="title is-3 is-flex-mobile"></h3>
                </nuxt-link>

        <a role="button" class="navbar-burger burger" @click="isMenuOpen = !isMenuOpen" aria-label="menu" aria-expanded="false">
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
        </a>
      </div> -->

      <div class="navbar-menu is-active">
        <div class="navbar-start">
          <!-- <div class="navbar-item field">
            <VmSearch></VmSearch>
          </div> -->
        </div>
                  <div class="navbar-item social">
                    <div class="flex-container">
                        <b-nav class="navigasi">
                        <b-nav-item class="flex-item-left">
                          <i class="fas fa-calendar-week" style="font-size:1.4em;color:green"/>
                                <i class="ngelink is-3 is-flex-mobile">senin-jumat ( 09:00 - 18:00 W.I.B )</i>

                        </b-nav-item>
                        <b-nav-item class="flex-item-center">
                            <i class="far fa-comments" style="font-size:1.4em;color:blue"/>
                                                  <i class="ngelink is-3 is-flex-mobile">+62811 1122 015</i>
                        </b-nav-item>
                        <b-nav-item class="flex-item-right">
                                <i class="far fa-envelope" style="font-size:1.4em;color:red"/>
                                                  <i class="ngelink is-3 is-flex-mobile">cs@triasse.com</i>
                        </b-nav-item>

                      </b-nav>
                   </div>
                </div>

                              <div class="navbar-end">

                             </div>
          <!-- <div class="navbar-item shopping-cart" @click="showCheckoutModal">
            <span class="icon">
              <i class="fa fa-shopping-cart"></i>
            </span>
            <span :class="[numProductsAdded > 0 ? 'tag is-info' : '']">{{ numProductsAdded }}</span>
          </div> -->

      </div>

      <!-- For mobile and tablet -->
      <!-- <div v-show="isMenuOpen" class="navbar-end">
        <VmMenu></VmMenu>
      </div> -->

      <!-- For desktop -->
      <!-- <div class="navbar-end is-hidden-mobile">
        <VmMenu></VmMenu>
      </div> -->
              <div class="navbar-end">
          <!-- <div class="navbar-item field">
            <VmSearch></VmSearch>
          </div> -->

        </div>
    </nav>
  </div>
</template>

<script>
  import VmMenu from '../menu/Menu';
  import VmSearch from '../search/Search';

  export default {
    name: 'VmHeader',

    data () {
      return {
        linkedinTooltip: 'Follow us on Linkedin',
        facebookTooltip: 'Follow us on Facebook',
        twitterTooltip: 'Follow us on Twitter',
        instagramTooltip: 'Follow us on Instagram',
        isCheckoutActive: false,
        isMenuOpen: false
      }
    },

    components: {
      VmSearch,
      VmMenu
    },

    computed: {
      numProductsAdded () {
        return this.$store.getters.productsAdded.length;
      }
    },

    methods: {
      showCheckoutModal () {
        this.$store.commit('showCheckoutModal', true);
      }
    }
  };
</script>

<style lang="scss" scoped>
  // .title {
  //   background: url('../../static/img-brand-logo.png') no-repeat;
  //   background-position: 0% -25%;
  //   // background-size: 165px;
  //   width: 200px;
  //   height: 100px;
  // }
  * {
  box-sizing: border-box;
    background-color: #daf0fff8;
}
.kepala {
  background-color: #daf0fff8;
}
.flex-container {

  justify-content: right;
  font-size: 12px;
  text-align: center;
}

.flex-item-left {
  // background-color: #f1f1f1;
    justify-content: right;
  padding: 10px;
  flex: 50%;
}
.flex-item-center {
  // background-color: dodgerblue;
    justify-content: right;
  padding: 10px;
  flex: 50%;
}
.flex-item-right {
  // background-color: dodgerblue;
    justify-content: right;
  padding: 10px;
  flex: 50%;
}

/* Responsive layout - makes a one column-layout instead of a two-column layout */
@media (max-width: 800px) {
  .flex-item-right, .flex-item-left {
    flex: 100%;
  }
}
  .shopping-cart {
    cursor: pointer;

  }

  .navigasi {



  width: 100px;
  margin: 40px;
  text-align: center;
  line-height: 75px;
  font-size: 1.2em;
}
  a {
    color: grey;
  }
</style>
