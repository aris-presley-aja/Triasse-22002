<template>
<!--  -->

<!--  -->
  <div class="hero is-medium is-bold">
                <a role="button" class="navbar-burger burger" @click="isMenuOpen = !isMenuOpen" aria-label="menu" aria-expanded="false">
                  <span aria-hidden="true"></span>
                  <span aria-hidden="true"></span>
                  <span aria-hidden="true"></span>
                </a>
      <div class="hero-body">

        <div class="container">

          <div  class="navbar-end">
<div class="hero-foot">
    <nav class="tabs is-boxed is-fullwidth">
      <div class="container">
        <ul>
          <li class="">
                                              <span>      <nuxt-link :to="{ name: 'index' }" class="navbar-item">
                                    <h3 class="title is-3 is-flex-mobile"></h3>
                                            </nuxt-link> </span>
          </li>
          <li>
            <a>Paket Tes Darah</a>
          </li>
          <li>
            <a>laboratorium</a>
          </li>
          <li>
            <a>artikel</a>
          </li>
          <li>
            <a>

                                   <!-- For mobile and tablet -->
                       <div v-show="isMenuOpen" class="navbar-end">

                        <VmMenu></VmMenu>
                      </div>

            </a>
          </li>
          <li>
            <a>

                                    <!-- For desktop -->
                      <div class="navbar-end is-hidden-mobile">

                        <VmMenu></VmMenu>
                      </div>

            </a>
          </li>
        </ul>
      </div>
    </nav>
  </div>
<!--  -->



          </div>
                          <div class="img" width="100%">
                                <!-- <b-img src="../../static/img-big-banner@3x.jpg" width="120%"> -->
                                <!-- <b-img src="../../static/img-big-banner@3x.jpg" fluid alt="Responsive image"></b-img> -->
                              <img src="../../static/img-big-banner@3x.jpg">
                          </div>
                        <!--  -->

                        <!--  -->
                                      <div class="card" style="
                                                  width:80%;
                                                  position: absolute;
                                                    left: 10%;
                                                    top: 85%;
                                                    z-index: 1;">
                                        <div class="">
                                                          <div class="pilih-jenis">
                                                  <i>Pilih Jenis Pemeriksaaan</i>
                                                      </div>
                                        </div>
                                        <div class="card-content">
                                          <div class="media">
                                            <div class="media-left">

                                            </div>
                                            <div class="media-content">

                                            </div>
                                          </div>
                                                      <table class="table" width="100%">
                                                                  <thead>
                                                                      <tr>

                                                                        <td width="33%">Pilih Provinsi </td>

                                                                                              <td width="33%">Pilih kota / Kabupaten</td>

                                                                                                                    <td width="33%">Pilih Jenis Pemeriksaan</td>
                                                                      </tr>
                                                                  </thead>
                                                                      <tfoot>
                                                                                <tr>
                                                                                                    <td width="33%">
                                                                                                                                <div class="dropdown is-active">

                                                                                                  <div class="dropdown-trigger">


                                                                                                    <button class="button" aria-haspopup="true" aria-controls="dropdown-menu">
                                                                                                    <i class="fas fa-map-marker-alt" style="font-size:1.4em;color:blue"></i>
                                                                                                      <span>Provinsi</span>
                                                                                                      <span class="icon is-small">
                                                                                                        <i class="fas fa-angle-down" aria-hidden="true"></i>
                                                                                                      </span>
                                                                                                    </button>
                                                                                                  </div>
                                                                                                  <div class="dropdown-menu" id="dropdown-menu" role="menu">

                                                                                                </div>


                                                                                      </div>
                                                                                                      </td>
                                                                                            <td width="33%">
                                                                                                <div class="class=control">

                                                                                                  <div class="">
                                                                                                    <button>
                                                                                                      <i class="fas fa-map-marked-alt" style="font-size:1.4em;color:blue"></i>
                                                                                                      <span>Kota / Kabupaten</span>
                                                                                                      <span class="icon is-small">
                                                                                                        <i class="fas fa-angle-down" aria-hidden="true"></i>
                                                                                                      </span>
                                                                                                    </button>
                                                                                                  </div>
                                                                                                  <!-- <div class="dropdown-menu" id="dropdown-menu" role="menu">

                                                                                                    </div> -->


                                                                                      </div>
                                                                                            </td>
                                                                                        <td width="33%">
                                                                                                                      <div class="control">

                                                                                                  <div class="">
                                                                                                    <button class="button" aria-haspopup="false" aria-controls="dropdown-menu">
                                                                                                      <i class="fas fa-stethoscope" style="font-size:1.4em;color:blue"></i>
                                                                                                      <span>Pilih Jenis Pemeriksaan</span>
                                                                                                      <span class="icon is-small">
                                                                                                        <i class="" aria-hidden="true"></i>
                                                                                                      </span>
                                                                                                    </button>
                                                                                                  </div>



                                                                                      </div>
                                                                                        </td>
                                                                                </tr>
                                                                                <tr>

                                                                                                        <td width="33%"
                                                                                                        style="

                                                                                                            position: absolute;
                                                                                                              left: 70%;
                                                                                                              top: 85%;
                                                                                                              ">

                                                                                            <button class="button2"> Cari lab</button>
                                                                                  </td>
                                                                                </tr>
                                                                          </tfoot>
                                                      </table>
                                  <!-- top column -->

                                  <!-- /top column -->


                                          <!--  -->

                                            </div>
                                      </div>
                          <!--  -->

      </div>
    </div>
                    <div align="center"   style="background-color: #daf0fff8;">
                            <h1><b>Mengapa harus Triasse ?</b></h1>
                      <p></p>
                      <h2> Proin Egestas eu dui vestibulum. Suspendisse sit amet sem non nunc tempor tincidunt.</h2>

<!--  -->


                                                                    <div class="card-content">
                                                                      <div class="">
                                                                        <figure class="">
                                                                          <img  width="38%" height="38%" left="50%" align="left" src="https://bulma.io/images/placeholders/96x96.png" alt="Placeholder image">
                                                                        </figure>
                                                                      </div>
                                                                    </div>
                          <div class="card-content">

                            <div class="content">

                              <b class="ratakiri">Jaminan harga terbaik</b>


                                  <p class="ratakiribawah">
                                                             <img src="https://bulma.io/images/placeholders/48x48.png">
                                harga kompetitif di laboratorium terbesar dan terpercaya di indonesia seperti Prodia, <br>Kimia Farma, Parahita, GS Lab & Biotest
                                    </p>

                            </div>

                            <div class="content">

                              <b class="ratakiri">layanan home service</b>


                                  <p class="ratakiribawah">
                                                             <img src="https://bulma.io/images/placeholders/48x48.png">
                                harga kompetitif di laboratorium terbesar dan terpercaya di indonesia seperti Prodia, Kimia Farma, Parahita, GS Lab & Biotest
                                    </p>

                            </div>
                            <div class="content">
                              <img src="https://bulma.io/images/placeholders/48x48.png">
                              Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                              Phasellus nec iaculis mauris. <a>@bulmaio</a>.
                              <a href="#">#css</a> <a href="#">#responsive</a>
                              <br>
                              <time datetime="2016-1-1">11:09 PM - 1 Jan 2016</time>
                            </div>
                            <div class="content">
                              <img src="https://bulma.io/images/placeholders/48x48.png">
                              Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                              Phasellus nec iaculis mauris. <a>@bulmaio</a>.
                              <a href="#">#css</a> <a href="#">#responsive</a>
                              <br>
                              <time datetime="2016-1-1">11:09 PM - 1 Jan 2016</time>
                            </div>
                          </div>

                        </div>
                                  <!--  -->

                    <!--  -->



                      <table class="table"></table>
                    <!--  -->
<!--  -->
<div class="columns is-centered">
  <div class="column is-half">

    <!-- Your card code: -->
    <div class="card">
      <div class="card-image">
        <figure class="image is-4by3">
          <img src="../../static/480x480.png" alt="Placeholder image">
        </figure>
      </div>
      <div class="card-content">
        <div class="content">
            texte ici
            <br>
        </div>
      </div>
    </div>

  </div>
</div>
<!--  -->
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
    .pilih-jenis {
    background-color: #daf0fff8;
    background-position: -100% 0%;
    // align-content: center;
    // vertical-align: top;
         width:100%;
    // margin-left:50%;
    // transform:translate(-50%, -50%);

  }
.card .card-image,
.card .card-image .image img {
  height: 50%;
  width: 50%;
}
    .card-header-title {
      font-size: 20px;
    }
  .card-atas {
    width:70%;
 position: absolute;
  left: 20%;
  top: 90%;
  z-index: 1;
}
      .pilih-jenis2 {
      background: rgb(255, 255, 255);
    background-position: -100% 0%;
    align-content: center;
    // vertical-align: top;
    top: 50%;
         width:80%;
    margin-left:50%;
    transform:translate(-50%);

  }
    .title {

    background: url('../../static/img-brand-logo.png') no-repeat;
    background-position: 100% 15%;
    align-content: center;
    vertical-align: center;
    width: 100px;
    height: 100px;

  }
  //   .ngelink {
  //   left: 50%;
  //   top: -25%;
  //   width: 200px;
  //   height: 10px;

  // }
  //   .bottomline {

  //   background-position: 50% 50%;


  // }
    .hero {
      background: rgb(255, 255, 255);
    }
.ratakiri {

    margin-left:-30%;
    font-size: 1rem;
}
.ratakiribawah {
    top: 30%;
    margin-left:-20%;
    font-size: 1rem;
        transform:translate(0%, -30%);
}
.keterangan-sisi {

    margin-left:-35%;
    font-size: 1rem;
}
.img {
     width:100vw;
    margin-left:50%;
    transform:translate(-50%);
}
 .navigasi-hero {
  width: 100px;
  margin: 40px;
  text-align: center;
  line-height: 75px;
  font-size: 1.2em;
}
.button2 {background-color: #ff7b00;} /* Blue */
     .ngelink {
    left: 50%;
    top: -25%;
    width: 200px;
    height: 10px;

  }
    h3, h4 {
        justify-content: right;
      // background-position: 0% -25%;
        //  left: 50%;
    // top: -25%;
    width: 200px;
    height: 10px;
      color: rgb(0, 0, 0);
    }
</style>
