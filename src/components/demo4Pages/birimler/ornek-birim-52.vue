<template>
  <div>
    <div id="page-loading" class="kl-pageLoading--yes">
      <div class="preloader-pulsating-circle border-custom"></div>
    </div>
    <div id="page_wrapper">
      <Header />
      <div
        id="page_header"
        style="padding-top:10px;"
        class="page-subheader page-subheader--auto page-subheader--inherit-hp uh_zn_def_header_style  psubhead-stheader--absolute sh-tcolor--dark"
      >
        <div class="bgback"></div>
        <div class="th-sparkles"></div>

        <div class="ph-content-wrap">
          <div class="ph-content-v-center">
            <div>
              <div class="container">
                <div class="row" style="padding-top:15px;">
                  <div class="col-sm-6">
                    <ul
                      vocab="http://schema.org/"
                      typeof="BreadcrumbList"
                      class="breadcrumbs fixclear bread-style--minimal"
                    >
                      <li property="itemListElement" typeof="ListItem">
                        <a property="item" typeof="WebPage" href="/"
                          ><span property="name">Anasayfa</span></a
                        >
                        <meta property="position" content="1" />
                      </li>
                      <li>&#214;rnek Birim</li>
                    </ul>
                    <div class="clearfix"></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="zn_header_bottom_style"></div>
      </div>
      <section id="content" class="site-content">
        <div class="container">
          <div class="row">
            <div
              class="right_sidebar col-sm-12 col-md-9 "
              role="main"
              itemprop="mainContentOfPage"
            >
              <div id="th-content-post">
                <div
                  id="post-107"
                  class="kl-single-layout--modern post-107 post type-post status-publish format-standard has-post-thumbnail hentry category-uncategorized prodpage-style2"
                >
                  <div
                    class="itemView clearfix eBlog kl-blog kl-blog-list-wrapper kl-blog--style-light "
                  >
                    <div
                      class="kl-blog-post"
                      itemscope="itemscope"
                      itemtype="https://schema.org/Blog"
                    >
                      <div class="kl-blog-single-head-wrapper">
                        <img
                          src="../../../../public/admin.togdem.com/AdminPanel_Assets/img/birimler/32/birim-yetkili-1.png"
                          style="width:70%; margin-left:15%;"
                        />
                      </div>

                      <h1
                        class="page-title kl-blog-post-title entry-title"
                        itemprop="headline"
                      >
                        Birim Yetkili 1
                      </h1>
                      <h3>&#214;rnek Birim M&#252;d&#252;r&#252;</h3>

                      <div class="itemBody kl-blog-post-body" itemprop="text">
                        <p>
                          Lorem Ipsum, dizgi ve baski end&#252;strisinde
                          kullanilan migir metinlerdir. Lorem Ipsum, adi
                          bilinmeyen bir matbaacinin bir hurufat numune kitabi
                          olusturmak &#252;zere bir yazi galerisini alarak
                          karistirdigi 1500lerden beri end&#252;stri standardi
                          sahte metinler olarak kullanilmistir. Besy&#252;z yil
                          boyunca varligini s&#252;rd&#252;rmekle kalmamis, ayni
                          zamanda pek degismeden elektronik dizgiye de
                          si&#231;ramistir. 1960larda Lorem Ipsum pasajlari da
                          i&#231;eren Letraset yapraklarinin yayinlanmasi ile ve
                          yakin zamanda Aldus PageMaker gibi Lorem Ipsum
                          s&#252;r&#252;mleri i&#231;eren masa&#252;st&#252;
                          yayincilik yazilimlari ile pop&#252;ler olmustur.
                        </p>
                        <i class="fas fa-phone"></i
                        ><a href="tel:+90 555 555 5555">: +90 555 555 5555</a
                        ><br />
                        <i class="fas fa-envelope"></i
                        ><a href="tel:ornek@email.com">: ornek@email.com</a
                        ><br />
                      </div>

                      <div class="clearfix"></div>
                      <div class="row blog-sg-footer">
                        <div class="col-sm-6"></div>
                        <div class="col-sm-6"></div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <Aside />
          </div>
        </div>
      </section>

      <Footer />
    </div>

    <div id="modal" style="display:none;">
      <i onclick="modalkapat()" class="fas fa-window-close fa-3x"></i>
    </div>
    <div id="modal2" style="display:none;">
      <h3 class="text-center">Online Sipariş Formu</h3>
      <form method="post">
        <div class="form-group">
          <label class="control-label">Ürün Adı</label>
          <input
            type="text"
            id="urunAdi"
            required
            name="urunAdi"
            readonly
            class="form-control"
          />
        </div>
        <div class="form-group">
          <label class="control-label">Adedi</label>
          <input
            type="number"
            id="adedi"
            required
            name="adedi"
            readonly
            class="form-control"
          />
        </div>
        <div class="form-group">
          <label class="control-label">Ad Soyad/Firma Adı</label>
          <input
            type="text"
            id="isim"
            required
            name="isim"
            class="form-control"
          />
        </div>
        <div class="form-group">
          <label class="control-label">E-Mail</label>
          <input
            type="email"
            id="email"
            required
            name="email"
            class="form-control"
          />
        </div>
        <div class="form-group">
          <label class="control-label">Telefon</label>
          <input
            type="tel"
            id="telefon"
            required
            name="telefon"
            class="form-control"
          />
        </div>
        <div class="form-group">
          <label class="control-label">Adres</label>
          <input
            type="tel"
            id="adres"
            required
            name="adres"
            class="form-control"
          />
        </div>
        <div class="form-group">
          <label class="control-label">Mesaj</label>
          <input
            type="tel"
            id="mesaj"
            required
            name="mesaj"
            class="form-control"
          />
        </div>
        <div class="form-group">
          <input
            type="submit"
            value="Gönder"
            name="gonder"
            class="btn btn-primary"
          />
          <input
            type="button"
            value="İptal"
            id="iptal"
            class="btn btn-danger"
          />
        </div>
      </form>
    </div>

    <a
      href="#"
      id="totop"
      class="u-trans-all-2s js-scroll-event"
      data-forch="300"
      data-visibleclass="on--totop"
      >Yukarı</a
    >
  </div>
</template>
<script>
import Header from "../../MasterPageComponent/Header";
import Footer from "../../MasterPageComponent/Footer";
import Aside from "../../MasterPageComponent/Aside";

export default {
  components: {
    Header,
    Footer,
    Aside,
  },
};
</script>
<style scoped>
.kayityok {
  text-align: center;
  background: #cd2122;
  width: 100%;
  padding-top: 30px;
}

.kayityok h3 {
  color: white;
  height: 80px;
}

.dahafazla {
  height: 270px;
  padding-top: 90px;
  text-align: center;
  background: #cd2122;
}

.dahafazla h3 {
  color: white;
  margin-top: 0;
}

.gosterslayt .slick-prev,
.gosterslayt .slick-next,
#rezerveSlayt .slick-next,
#rezerveSlayt .slick-prev {
  background: #00355a;
  height: 130px;
  color: white;
  border: none;
  font-weight: bolder;
  font-size: 30px;
  position: absolute;
  width: 40px;
  top: 40%;
  opacity: 0.6;
  z-index: 50;
}

#hizmetSlayt .slick-prev,
#hizmetSlayt .slick-next {
  transition: all 0.5s;
  position: absolute;
  width: 40px;
  top: calc(50% - 25px);
  height: 40px;
  opacity: 0.6;
  z-index: 50;
  left: 10px;
  border-radius: 20px;
  border: none;
  outline: none;
}

#hizmetSlayt .slick-next {
  left: calc(100% - 50px);
}

#hizmetSlayt .slick-prev:hover,
#hizmetSlayt .slick-next:hover {
  transition: all 0.5s;
  opacity: 1;
}

.gosterslayt .slick-next,
#rezerveSlayt .slick-next {
  left: calc(100% - 40px);
}

#modal {
  top: 0;
  left: 0;
  width: 100vw;
  height: 100vh;
  position: fixed;
  background: #00355a50;
  z-index: 100;
}

#modal i {
  float: right;
  color: red;
  cursor: pointer;
  margin: 20px;
}

#modal iframe {
  width: 100%;
  height: 100%;
}

#modal2 {
  padding: 20px;
  box-shadow: 0px 0px 1000px 1000px rgba(0, 0, 0, 0.5);
  width: 500px;
  height: 90vh;
  overflow-y: scroll;
  left: calc(50vw - 250px);
  top: 5vh;
  position: fixed;
  background: #dcdcdc;
  z-index: 100;
}

#instadiv {
  overflow-y: scroll;
  height: 500px;
}

.instagramul li {
  list-style: none;
}

#eluid08822604 span.grid-ibx__icon img,
#eluid089b28a9 span.grid-ibx__icon img {
  height: 70px;
  width: 70px;
}

#baskanmenu {
  width: 100%;
  padding-left: 5px;
}

#baskanmenu li {
  padding: 10px 10px 10px 0;
  font-weight: bold;
  list-style: none;
}

#baskanmenu li:hover {
  background: lightgray;
}

img.wp-smiley,
img.emoji {
  display: inline !important;
  border: none !important;
  box-shadow: none !important;
  height: 1em !important;
  width: 1em !important;
  margin: 0 0.07em !important;
  vertical-align: -0.1em !important;
  background: none !important;
  padding: 0 !important;
}

#slayt {
  margin-top: 100px;
  padding: 50px;
}

#slayt img {
  width: 80%;
}

#anasayfaslayt .slick-prev,
#anasayfaslayt .slick-next {
  position: absolute;
  height: 50px;
  width: 50px;
  border-radius: 50px;
  border: none;
  z-index: 10;
  color: #e5e4e3;
  background: #999;
  font-size: 40px;
  font-weight: bolder;
  opacity: 0.5;
  padding-top: 3px;
  outline: none;
}

#anasayfaslayt .slick-prev {
  top: 40%;
  left: 10px;
}

#anasayfaslayt .slick-next {
  top: 40%;
  left: calc(100% - 60px);
}

.haber .hedslayt img,
.etkinlik .hedslayt img {
  width: 100%;
  height: 450px;
  object-fit: cover;
}

.hedslayt .slick-next,
.hedslayt .slick-prev {
  position: absolute;
  width: 70px;
  height: 50px;
  top: 513px;
  background: white;
  left: 15px;
  border: none;
  outline: none;
}

.hedslayt .slick-next {
  left: calc(100% - 85px);
}

.haber .hedslayt h3,
.etkinlik .hedslayt h3 {
  position: absolute;
  z-index: 2;
  overflow: hidden;
  background: rgba(255, 255, 255, 0.5);
  top: calc(100% - 100px);
  padding: 20px 5px;
  width: 100%;
}

.duyuru img {
  height: 70px;
  margin-bottom: 20px;
}

.hedslayt .slick-dots {
  text-align: center;
  background: white;
  padding-top: 10px;
  margin-left: 2%;
  height: 51px;
  width: 96%;
}

.hedslayt .slick-dots li {
  width: 70px;
  height: 50px;
  margin-top: -10px;
  border-left: 0.5px solid lightgray;
  border-right: 0.5px solid lightgray;
}

.hedslayt .slick-dots .slick-active {
  background: #00355a;
  font-size: 15px;
  font-weight: bold;
}

#tumhaberler {
  height: 50px;
  position: absolute;
  top: 514px;
  z-index: 1000;
  width: 70px;
  border-right: 0.5px solid lightgray;
  left: calc(100% - 150px);
  color: #00355a;
  line-height: 50px;
}

.etkinlik .fw-bold,
.haber .fw-bold,
.duyuru .fw-bold {
  background: #00355a90;
  position: absolute;
  top: calc(100% - 60px);
  height: 60px;
  margin: 0;
  width: calc(100% - 30px);
}

.hedslayt .slick-dots li button {
  border: none;
  outline: none;
  padding: 0 10px;
  border-radius: unset;
  opacity: 1;
  background: white;
  color: #00355a;
  width: 100%;
  height: 100%;
  box-sizing: border-box;
  text-indent: 0;
}

.ortakslayt .slick-prev,
.ortakslayt .slick-next {
  position: absolute;
  height: 30px;
  width: 30px;
  border-radius: 30px;
  border: none;
  text-align: center;
  z-index: 10;
  color: #d6eaf8;
  background: #00355a;
  font-size: 20px;
  font-weight: bolder;
  opacity: 0.5;
  outline: none;
}

.urunSlayt .slick-next,
.urunSlayt .slick-prev {
  transition: all 0.5s;
  position: absolute;
  width: 30px;
  height: 30px;
  border: none;
  background: #dcdcdc;
  outline: none;
  opacity: 0.5;
}

.hedaltslayt .slick-prev,
.urunSlayt .slick-prev {
  top: 40%;
  left: 15px;
  z-index: 1000;
}

.hedaltslayt .slick-next,
.urunSlayt .slick-next {
  top: 40%;
  left: calc(100% - 45px);
  padding-top: 3.5px;
}

.ortakslayt .slick-prev {
  top: 35%;
  left: 15px;
}

.ortakslayt .slick-next {
  top: 35%;
  left: calc(100% - 45px);
  padding-top: 3.5px;
}

.hedaltslayt .slick-active,
.hedaltslayt .slick-slide {
  text-align: center;
}

.hedaltslayt .slick-active h3,
.hedaltslayt .slick-slide h3 {
  margin: 15px 10px 0 10px;
}

.hedaltslayt .slick-active h3,
.hedaltslayt .slick-slide h3 {
  background: #fafafa;
  height: 80px;
  padding-top: 20px;
  font-weight: bolder;
  color: #003458;
}

.hedaltslayt .slick-center,
.hedaltslayt .slick-current {
  text-align: center;
  background: none;
  height: 100px;
}

.hedaltslayt .slick-center h3,
.hedaltslayt .slick-current h3 {
  margin: 10px;
  height: 100%;
  font-weight: bolder;
  padding-top: 30px;
  background: #003458;
  color: #fafafa;
}

.hedaltslayt .slick-prev:hover,
.hedaltslayt .slick-next:hover,
#anasayfaslayt .slick-prev:hover,
#anasayfaslayt .slick-next:hover,
.ortakslayt .slick-prev:hover,
.ortakslayt .slick-next:hover,
.urunSlayt .slick-next:hover,
.urunSlayt .slick-prev:hover,
#rezerveSlayt .slick-next:hover,
#rezerveSlayt .slick-prev:hover {
  transition: all 0.5s;
  opacity: 1;
}

#logo img {
  width: 100%;
  height: 100%;
  object-fit: contain;
}

.acilirkutu {
  height: 250px;
  overflow-y: hidden;
}

.acilirkutu .kaydir {
  transition: all 0.6s;
  position: absolute;
  width: 100%;
  height: 250px;
  top: 200px;
  background: #00355a;
}

.kaydir h3 {
  font-size: 18px;
  font-weight: bold;
  color: white;
  position: center;
  border-bottom: 1px solid white;
  margin: 0 auto;
  padding: 0 5px;
  height: 50px;
  line-height: 50px;
}
.nav-mm--dark.main-nav ul ul.sub-menu .menu-item a {
  color: #fafafa;
}

.eluid0399322e .kl-iconbox__inner .kl-iconbox__icon,
.eluidca297d5e .kl-iconbox__inner .kl-iconbox__icon {
  color: #fafafa;
}

.element-scheme--light a {
  color: #00355a;
}

.menuli {
  padding: 10px 20px;
  color: #00355a;
  float: right;
  list-style: none;
  color: #00355a;
  border-right: 1px solid lightgray;
}

.menuli a {
  font-weight: bold;
  color: #00355a;
}

.menuli a:hover {
  color: #00355a;
}

.menuli:nth-last-of-type(1) {
  border-left: 1px solid lightgray;
}

.sol {
  border-left: 1px solid lightgray;
  float: left;
  margin-left: -50px;
  width: 40%;
  padding: 13px 10px 0 10px;
}

.nav-mm--dark.main-nav .zn_mega_container .menu-item a {
  color: #fafafa;
}

.site-header.style14 .site-header-top-wrapper {
  background: #fafafa;
}

.tabs_style3.tabs--light > ul.nav > li > a {
  background: #fafafa;
}

.tabs_style3.tabs--light > ul.nav > li > a:hover,
.zn_section.eluidadf0d8f7 {
  background: #00355a;
}

.listele {
  text-align: center;
}

.sayfanumarasi {
  font-weight: bold;
  padding: 0 20px;
  font-size: 20px;
  color: black;
}

.latest_posts-wgt {
  position: initial;
}

.product-list-item {
  box-shadow: #cdcdcd 0px 0px 10px;
}

.woocommerce
  ul.products
  li.product
  .product-list-item.prod-layout-classic
  .kw-details-title {
  font-weight: 500;
}
#eluid494d325b > li > a,
#eluid2e8167eb > li > a,
#eluid2cac18d7 > li > a,
#eluid0312a0f0 > li > a {
  color: #fafafa;
}

.nlbox--style-normal .elm-nlbox__submit,
.elm-social-icons.sc--normal .elm-sc-icon {
  color: #00355a;
  background: #fafafa;
}

.nlbox--style-normal .elm-nlbox__submit:hover {
  color: #fafafa;
  background: #00355a;
  border: #fafafa 1px solid;
}

.eluid9e3fee1d.zn_separator--icon-no {
  border-color: #fafafa;
}

.element-scheme--light a {
  color: white;
}
.galeriSlayt {
  width: 100vw;
  height: 100vh;
  top: 0;
  left: 0;
  background: rgba(0, 53, 90, 0.65);
}
.photo-gallery {
  color: #313437;
  background-color: #fff;
}

.photo-gallery p {
  color: #7d8285;
}

.photo-gallery h2 {
  font-weight: bold;
  margin-bottom: 40px;
  padding-top: 40px;
  color: inherit;
}

@media (max-width: 767px) {
  .photo-gallery h2 {
    margin-bottom: 25px;
    padding-top: 25px;
    font-size: 24px;
  }
}

.photo-gallery .intro {
  font-size: 16px;
  max-width: 500px;
  margin: 0 auto 40px;
}

.photo-gallery .intro p {
  margin-bottom: 0;
}

.photo-gallery .photos {
  padding-bottom: 20px;
}

.photo-gallery .item {
  padding-bottom: 30px;
}
</style>
