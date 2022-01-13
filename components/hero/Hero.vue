<template>
<!--  -->

<!--  -->
  <div class="hero is-small is-bold">
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
                                    <h3 class="titles is-3 is-flex-mobile"></h3>
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
                       <b><i>Pilih Jenis Pemeriksaaan</i></b>

                                                      </div>
                                                       <div class="pilih-jeniskanan">

                                                        <figure class="image is-128x128">
                        <img width="10%" height="auto" src="../../static/img-doctor.svg" alt="Placeholder image">
                      </figure>
                                                      </div>
                                        </div>
                                        <div class="card-content">
                                          <div class="media">
                                            <div class="media-left">

                                            </div>
                                            <div class="media-content">

                                            </div>
                                          </div>
                                                      <table class="naik" width="100%">
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
                                                                                                <div class="class=control">

                                                                                                  <div class="">
                                                                                                    <button>
                                                                                                      <i class="fa fa-map-marker" style="font-size:1.4em;color:blue"></i>
                                                                                                      <span>Provinsi</span>
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
                                                                                                    <i class="fas fa-stethoscope" style="font-size:1.4em;color:blue"></i>
                                                                                                    </div> -->


                                                                                                </div>
                                                                                            </td>
                                                                                            <td width="33%">
                                                                                                <div class="class=control">

                                                                                                  <div class="">
                                                                                                    <button>
                                                                                                          <i class="fas fa-stethoscope" style="font-size:1.4em;color:blue"></i>
                                                                                                      <span>Kota / Kabupaten</span>
                                                                                                      <span class="icon is-small">
                                                                                                        <i class="fas fa-angle-down" aria-hidden="true"></i>
                                                                                                      </span>
                                                                                                    </button>
                                                                                                  </div>
                                                                                                  <!-- <div class="dropdown-menu" id="dropdown-menu" role="menu">
                                                                                                    <i class="fas fa-stethoscope" style="font-size:1.4em;color:blue"></i>
                                                                                                    </div> -->


                                                                                                </div>
                                                                                            </td>
                                                                                </tr>
                                                                                <tr>

                                                                                                        <td width="33%"
                                                                                                        style="

                                                                                                            position: absolute;
                                                                                                              left: 70%;
                                                                                                              top: 110%;
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
                    <div align="center" class="turun"  style="background-color: #daf0fff8;">
                            <h1><b>Mengapa harus Triasse ?</b></h1>
                      <p></p>
                      <h2> Proin Egestas eu dui vestibulum. Suspendisse sit amet sem non nunc tempor tincidunt.</h2>

                                    <!--  -->
                                  <!--  -->

                                  <!--  -->
                        <div class="card-content">
                                                                      <div class="">
                                                                        <figure class="">
                                                                          <img  width="38%" height="38%" left="50%" align="left" src="https://bulma.io/images/placeholders/96x96.png" alt="Placeholder image">
                                                                        </figure>
                                                                      </div>
                                                                    </div>
                        <div class="cards">
                          <div width="38%" height="38%" left="50%" align="center" class="card-contents">

                                                                                  <div class="columns is-mobile is-left">
                                                        <div class="columns is-narrow">
                                                          <img class="imgratakiri" height="25em" src="https://bulma.io/images/placeholders/96x96.png" alt="">
                                                        </div>
                                                        <div class="ratakiri column has-text-left">
                                                          <span class="title">Jaminan harga terbaik</span><br>
                                                          <span class=""><h2>harga kompetitif di laboratorium terbesar dan terpercaya di indonesia seperti Prodia, Kimia Farma, Parahita, GS Lab & Biotest</h2></span>
                                                        </div>
                                                      </div>


                                                                                  <div class="columns is-mobile is-left">
                                                        <div class="columns">
                                                          <img class="imgratakiri" top="-50%"  src="https://bulma.io/images/placeholders/96x96.png" alt="">
                                                        </div>
                                                        <div class="ratakiri column has-text-left">
                                                          <span class="title">Layanan home service</span><br>
                                                          <span class="subtitle">Pemeriksaan bisa dilakukan dari rumah sendiri dengan layanan Home Service, petugas datang untuk<br> melakukan pengecekan dan tes</span>
                                                        </div>
                                                      </div>


                                                                                  <div class="columns is-mobile is-left">
                                                        <div class="columns">
                                                           <img class="imgratakiri" top="-50%" height="25em" src="https://bulma.io/images/placeholders/96x96.png" alt="">
                                                        </div>
                                                        <div class="ratakiri column has-text-left">
                                                          <span class="title">Cicilan 4x dengan bunga 0%</span><br>
                                                          <span class="subtitle">Pembayaran paket pemeriksaan lebih ringan karena dap[at dicicil sampai dengan empat kali, dan tanpa bunga tambahan</span>
                                                        </div>
                                                      </div>


                                                                                  <div class="columns is-mobile is-left mb-4">
                                                        <div class="columns">
                                                          <img class="imgratakiri" top="-50%" height="25em" src="https://bulma.io/images/placeholders/96x96.png" alt="">
                                                        </div>
                                                        <div class="ratakiri column has-text-left">
                                                          <span class="title">Jaminan harga terbaik</span><br>
                                                          <span class="subtitle">harga kompetitif di laboratorium terbesar dan terpercaya di indonesia seperti Prodia, Kimia Farma, Parahita, GS Lab & Biotest</span>
                                                        </div>
                                                      </div>

                            <!--  -->

                            <!--  -->
                          </div>

                      </div>
                  </div>
                                  <!--  -->

                    <!--  -->


<!--
                      <table class="table"></table> -->
                    <!--  -->
<!--  -->


    <!-- Your card code: -->
    <div class="container-cards turun2">
      <div class="title">
        <center>
        <p>Lorem Ipsum Dolor Sit Amet</p>
        <h2>Proin egestas eu dui in vestibulum. Suspendisse sit amet sem non nunc tincidunt.</h2>
        </center>
      </div>


        <div class="subtitle">
                  <!-- konten kartu 6
            <br> -->
            <center>
                                                    <div class="section">
                                                      <!-- mulai -->
                                                      <div class="barisan-kartu">
                                                        <!-- separator kartu -->
                                                        <div class="six-card is-centered">
                                                          <div class="card is-centered">
                                                            <div class="card-image">
                                                              <img class="imgratakirienam" top="-20%" height="10em" src="https://bulma.io/images/placeholders/96x96.png" alt="">
                                                            </div>
                                                            <div class="card-content ">
                                                              <div class="media">
                                                                <!-- <div class="media-left">
                                                                  <figure class="image is-48x48">
                                                                    <img src="https://bulma.io/images/placeholders/96x96.png" alt="Placeholder image">
                                                                  </figure>
                                                                </div> -->
                                                                <div class="media-contents">
                                                                  <p class="title is-4"><b>Paket Medical Check-up Basic</b></p>
                                                                  <!-- <p class="subtitle is-6">@johnsmith</p> -->
                                                                </div>
                                                              </div>

                                                              <div class="contents">
                                                                  <p> harga mulai dari</p>
                                                                    <p class="harga-diskon"> Rp 4116.000</p>
                                                                    <p style="color:blue">Rp 364.001</p>

                                                              </div>
                                                            </div>
                                                          </div>
                                                      </div>
                                                          <!-- kartu 2 -->
                                                        <div class="six-card">
                                                          <div class="card">
                                                            <div class="card-image">
                                                    <img class="imgratakirienam" top="-50%" height="10em" src="https://bulma.io/images/placeholders/96x96.png" alt="">
                                                            </div>
                                                            <div class="card-content">
                                                              <div class="media">
                                                                <!-- <div class="media-left">
                                                                  <figure class="image is-48x48">
                                                                    <img src="https://bulma.io/images/placeholders/96x96.png" alt="Placeholder image">
                                                                  </figure>
                                                                </div> -->
                                                                <div class="media-contents">
                                                                  <p class="title is-4"><b>Paket Medical Check-up Silver</b></p>
                                                                  <!-- <p class="subtitle is-6">@johnsmith</p> -->
                                                                </div>
                                                              </div>

                                                              <div class="contents">
                                                                  <p> harga mulai dari</p>
                                                                    <p class="harga-diskon"> Rp 600.000</p>
                                                                    <p style="color:blue">Rp 573.000</p>

                                                              </div>
                                                            </div>
                                                          </div>
                                                      </div>
                                                          <!-- kartu 3 -->
                                                        <div class="six-card">
                                                          <div class="card">
                                                            <div class="card-image">
                                                     <img class="imgratakirienam" top="-20%" height="10em" src="https://bulma.io/images/placeholders/96x96.png" alt="">
                                                            </div>
                                                            <div class="card-content">
                                                              <div class="media">
                                                                <!-- <div class="media-left">
                                                                  <figure class="image is-48x48">
                                                                    <img src="https://bulma.io/images/placeholders/96x96.png" alt="Placeholder image">
                                                                  </figure>
                                                                </div> -->
                                                                <div class="media-contents">
                                                                  <p class="title is-4"><b>Paket Medical Check-up Gold</b></p>
                                                                  <!-- <p class="subtitle is-6">@johnsmith</p> -->
                                                                </div>
                                                              </div>

                                                              <div class="contents">
                                                                  <p> harga mulai dari</p>
                                                                    <p class="harga-diskon"> Rp 1.228.000</p>
                                                                    <p style="color:blue">Rp 1.127.000</p>

                                                              </div>
                                                            </div>
                                                          </div>
                                                      </div>
                                                          <!-- kartu 4 -->
                                                        <div class="six-card">
                                                          <div class="card">
                                                            <div class="card-image">
                                                    <img class="imgratakirienam" top="-50%" height="10em" src="https://bulma.io/images/placeholders/96x96.png" alt="">
                                                            </div>
                                                            <div height="100%" class="card-content">
                                                              <div class="media">
                                                                <!-- <div class="media-left">
                                                                  <figure class="image is-48x48">
                                                                    <img src="https://bulma.io/images/placeholders/96x96.png" alt="Placeholder image">
                                                                  </figure>
                                                                </div> -->
                                                                <div class="media-contents">
                                                                  <p class="title is-4"><b>Paket Skrining Diabetes Melitus</b></p>
                                                                  <!-- <p class="subtitle is-6">@johnsmith</p> -->
                                                                </div>
                                                              </div>

                                                              <div class="contents">
                                                                  <p> harga mulai dari</p>
                                                                    <p class="harga-diskon"> Rp 261.265</p>
                                                                    <p style="color:blue">Rp 249.375</p>

                                                              </div>
                                                            </div>
                                                          </div>
                                                      </div>
                                                          <!-- kartu 5 -->
                                                        <div height="100%" class="six-card">
                                                          <div class="card">
                                                            <div class="card-image">
                                                          <img class="imgratakirienam" top="-50%" height="10em" src="https://bulma.io/images/placeholders/96x96.png" alt="">
                                                            </div>
                                                            <div class="card-content">
                                                              <div class="media">
                                                                <!-- <div class="media-left">
                                                                  <figure class="image is-48x48">
                                                                    <img src="https://bulma.io/images/placeholders/96x96.png" alt="Placeholder image">
                                                                  </figure>
                                                                </div> -->
                                                                <div class="media-contents">
                                                                  <p class="title is-4"><b>Paket resiko penyakit jantung</b></p>
                                                                  <!-- <p class="subtitle is-6">@johnsmith</p> -->
                                                                </div>
                                                              </div>
                                                                    <br>
                                                              <div class="contents">
                                                                  <p> harga mulai dari</p>
                                                                    <p class="harga-diskon"> Rp 1.162.000</p>
                                                                    <p style="color:blue">Rp 1.016.7250</p>

                                                              </div>
                                                            </div>
                                                          </div>
                                                      </div>
                                                          <!-- kartu 6 -->
                                                      <div class="six-card">
                                                          <div class="card">
                                                            <div class="card-image">
                                                               <img class="imgratakirienam" top="-50%" height="10em" src="https://bulma.io/images/placeholders/96x96.png" alt="">
                                                            </div>
                                                            <div class="card-content">
                                                              <div class="media">
                                                                <!-- <div class="media-left">
                                                                  <figure class="image is-48x48">
                                                                    <img src="https://bulma.io/images/placeholders/96x96.png" alt="Placeholder image">
                                                                  </figure>
                                                                </div> -->
                                                                <div class="media-contents">
                                                                  <p class="title is-4"><b>Paket TORCH</b></p>
                                                                  <!-- <p class="subtitle is-6">@johnsmith</p> -->
                                                                </div>
                                                              </div>
                                                                <br><br>
                                                              <div class="contents">
                                                                  <p> harga mulai dari</p>
                                                                    <p class="harga-diskon"> Rp 2.480.000</p>
                                                                    <p style="color:blue">Rp 2.417.000</p>

                                                              </div>
                                                            </div>
                                                          </div>
                                                      </div>
                  <!-- separator kartu -->
              </div>
            <!-- end -->
          </div>
        <!-- kartu 2 -->
                    </center>
            <!-- konten 6 kartu -->
      </div>
                  <table align="center" width="100%">
                                              <tr align="center">
                          <th colspan = "2"><img align="right" class="" width="50%" height="auto" top=" 0%" src="../../static/img-banner2-1.jpg" alt=""></th>
                          <th colspan = "2"><img left= "0%" class="duagambar" width="50%" height="auto" top=" 0%" src="../../static/img-banner2-2.jpg" alt=""></th>
                          </tr>
                  </table>
    </div>
<br><br><br>
  <br><br><br>
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
        .pilih-jeniskanan {
    // background-color: #daf0fff8;
    // background-position: 0% -50%;
     align-content: center;
    // vertical-align: top;
            height: 20px;
         width:100%;
         margin-top:-4%;
     margin-left:80%;
    // transform:translate(-50%, -50%);

  }
    .pilih-jenis {
    background-color: #daf0fff8;
    background-position: 0% 0%;
    // align-content: center;
    // vertical-align: top;
        height: 50px;
         width:100%;

     margin-left:0%;
    //  transform:translate( 0%, 20%);

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
    .duagambar{
          transform:translate(-40%);
    }

    .titles {

    background: url('../../static/img-brand-logo.png') no-repeat;
        transform:translate(-80%);
    background-position: 100% 15%;
    align-content: center;
    vertical-align: center;
    width: 400px;
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
.imgratakiri {
        // transform:translate(0%, 0%);
          margin-bottom: 10px;
        width: 100%;
    height: 70%;
    margin-left: 45%;
    font-size: 1rem;
}
.imgratakirienam {
        // transform:translate(0%, 0%);
          margin-bottom: 10px;
        width: 120px;
    height: 120px;
    margin-left: 0%;
    font-size: 1rem;
}
.barisan-kartu {
	display: grid;
	grid-template-columns: repeat(auto-fill, minmax(175px,1fr));
	grid-gap: 0.5em;
}

.card{
	height: max-content;
}
.ratakiri {
        transform:translate(0%, -20%);
    margin-left: 15%;
      margin-bottom: 10px;
    font-size: 1rem;
}
.imgratakiribawah {
    top: 20%;
    margin-left:2%;
    // font-size: 1rem;
    //     transform:translate(0%, -30%);
}
.ratakiribawah {
    top: 30%;
    margin-left:-10%;
    font-size: 1rem;
        transform:translate(0%, -80%);
}
.ratakiribawahlagi {
    top: 90%;
    margin-left: 7.7%;
    font-size: 1rem;
        transform:translate(0%, 40%);
}
.keterangan-sisi {

    margin-left:-35%;
    font-size: 1rem;
}
.turun {
    transform:translate(0%, 10%);
}
.turun2 {
    transform:translate(0%, 25%);
}
.naik {

    // margin-left:50%;
    transform:translate(0%, -30%);
}
.naik-dua-gambar {

    // margin-left:50%;
    transform:translate(0%, -50%);
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
  .harga-diskon{
  text-decoration: line-through;
}
</style>
