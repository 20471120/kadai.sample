<template>
  <main class="all">
    <div >
      <img class="card-img" src="../imges/water.jpeg" width="100%" height="562px" >
      <div>
        <p class="text-21 text-md-30 text-serif">そのすべてが満ちていく。</p>
        <router-link to="/about" class="btn btn-md btn-ooutline-white">詳しく</router-link>
      </div>
    </div>

    <section role="latest-news">
      <div>
        <p class="text-center">最新のお知らせ</p>
      </div>
      <div class="text-left">
        <a href="">text</a><hr>
        <a href="">text</a><hr>
        <a href="">text</a><hr>
      </div>
    </section>

    <section role="product" class="py-70 py-90">
      <div>
        <p>製品<br>比類なき、最高峰の日本酒を。</p>
      </div>

      <div class="col-12 mt-50 text-md-30 text-serif">
        <img src="../imges/byakkou1.jpeg" width="100%">
        <p>百行｜BYAKKO<br>"上質"を極める、至高の1本</p>
        <a href="">詳しく</a>   <a href="">購入</a>
      </div>

      <div class="row">  <!-- md以上が２列  -->
        <div class="col-12 col-md-6 mt-50 mt-md-55">
          <img src="../imges/amairo1.jpeg" width="100%">
          <p>天彩｜AMAIRO<br>濃密にとろける、日本酒というデザート</p>
          <a href="">詳しく</a>  <a href="">購入</a>
        </div>
        <div class="col-12 col-md-6 mt-50 mt-md-55">
          <img src="../imges/shirin1.jpeg" width="100%">
          <p>思凛｜SHIRIN<br>密やかにたたずむ、森のエレガンス</p>
          <a href="">詳しく</a>  <a href="">購入</a>
        </div>
      </div>

      <div>
        <img src="../imges/gengai1.jpeg" width="100%">
        <p>現外｜GENGAI<br>二度と再現できない、奇跡のヴィンテージ</p>
        <a href="">詳しく</a>  <a href="">購入</a>
      </div>
    </section>

    <section  role="collection" class="u-white py-70 pt-md-95 pb-md-105">
      <h class="text-18 text-md-30 text-serif text-center">コレクション</h>
      <div class="p-lineup mt-60 mt-md-75">
        <div class="carousel -type-swiper1 js-swiper swiper-container swiper-container-initialized swiper-container-horizontal swiper-container-ios -current-slide-0 -current-slide-2">
          <div class="p-lineup__row swiper-wrapper d-md-flex flex-row">
            <a href="" class="p-lineup__item py-md-40 swiper-slide js-gtm-product-click swiper-slide-duplicate" data-position="3" data-swiper-slide-index="2" style="width: 187.5px">
              <p class="text-14 text-center ">思凛｜SHIRIN</p>
              <figure>
                <img src="../imges/shirin.png" class="w-100">
              </figure>
              <p class="text-serif text-center">密やかにたたずむ、森のエレガンス</p>
            </a>
            <a href="" class="p-lineup__item py-md-40 swiper-slide js-gtm-product-click swiper-slide-duplicate swiper-slide-prev" data-position="4" tata-swiper-slide-index="3" style="width: 187.5px">
              <p class="text-14 text-center">現外｜GENGAI</p>
              <figure>
                <img src="../imges/gengai.png" class="w-100">
              </figure>
              <p class="text-serif text-center">二度と再現できない、奇跡のヴィンテージ</p>
              </a>
              <a href="" class="p-lineup__item py-md-40 swiper-slide js-gtm-product-click swiper-slide-active" data-position="1" data-swiper-slide-index="0" style="width: 187.5px">
              <p class="text-14 text-center">百光｜BYAKKO</p>
              <figure>
                <img src="../imges/byakkou.png" class="w-100" >  
              </figure>
              <p class="text-serif text-center">"上質"を極める至高の1本</p>
              </a>
              <a href="" class="p-lineup__item py-md-40 swiper-slide js-gtm-product-click swiper-slide-next" data-position="2" data-swiper-slide-index="1" style="width: 187.5px">
                <p class="text-14 text-center">天彩｜AMAIRO</p>
                <figure>
                  <img src="../imges/amairo.png" class="w-100"> 
                </figure>
                <p class="text-serif text-center">濃密にとろける、日本酒というデザート</p>
              </a>
          </div> 
        </div>

      </div>
    </section>
  
    <section role="story">
      <div class="container-fluid py-80 py-md-105 ">
        <h class=" text-md-30 text-serif ">ストーリー</h>
        <div class="p-storylist">
          <div class="p-storylist__row d-md-flex flex-row">
            <div class="p-storylist__item col-md-3 ">
              <div class="p-storycard">
                <figure>
                  <img src="../imges/str1.png" class="w-100">  
                </figure>
                <div class="d-flex mt-20 mt-md-30 text-md-13 text-muted">
                  <p>
                    <span class="p-storycard__tag d-block">INTERWVIEW</span>
                  </p>
                  <time class="p-storycard__date ml-20 pl-20 border-left">20??/??/??</time>
                </div>
                <p1>
                  <p class="p-storycard__title d-block mt-md-20 text-13 text-md-21 text-serif">ブランドにおけるクリエイティブ--象徴性と思想の表現</p>
                </p1>
              </div>
            </div>

            <div class="p-storylist__item col-md-3 ">
              <div class="p-storycard">
                <figure>
                  <img src="../imges/str2.png" class="w-100">  
                </figure>
                <div class="d-flex mt-20 mt-md-30 text-md-13 text-muted">
                  <p>
                    <span class="p-storycard__tag d-block">INTERWVIEW</span>
                  </p>
                  <time class="p-storycard__date ml-20 pl-20 border-left">20??/??/??</time>
                </div>
                <p1>
                  <p class="p-storycard__title d-block mt-md-20  text-serif">プレミアムからラグジュアイリーへ-2年間の歩みと新たな決意</p>
                </p1>
              </div>
            </div>

            <div class="p-storylist__item col-md-3">
              <div class="p-storycard">
                <figure>
                  <img src="../imges/str3.png" class="w-100">  
                </figure>
                <div class="d-flex mt-20 mt-md-30 text-10 text-md-13 text-muted">
                  <p>
                    <span class="p-storycard__tag d-block">INTERWVIEW</span>
                  </p>
                  <time class="p-storycard__date ml-20 pl-20 border-left">20??/??/??</time>
                </div>
                <p1>
                  <p class="p-storycard__title d-block mt-md-20 text-13 text-md-21 text-serif">SAKE HUNDRED そのすべてが満ちていく。</p>
                </p1>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <a href="">もっと見る</a>
    <section role="glass">
      <div class="glass d-md-flex flex-row">
        <div>
          <img src="../imges/cup.jpeg" width="50%">
        </div>
        <div>
          <img src="../imges/white-bg.gif" width="50%">  
          <p>そのすべてが満ちていく
            <br><button class="bg-primary text-white">私たちについて</button>
          </p>
          
        </div>
      </div>
    </section>
    
    <section role="brands-news">
      <div>
        <h>ブランドからのお知らせ</h><br><br>
        <a href="">text</a><hr>
        <a href="">text</a><hr>
        <a href="">text</a><hr>
      </div>

    </section>
  
    <section class="mt-90 p-newsletter">
      <div class="py-55 py-md-90 px-md-0 p-newsletter__wrapper">
        <div class="justify-content-md-center">
          <div class="col-md-8">
            <h2 class="text-18 text-md-30 text-serif text-center">
              ニュースレターに
              <br class="d-md-none">登録しませんか
            </h2>
          </div>
          <p class="mt-30 text-center">
            SAKE HUNDREDからの最新ニュースや商品情報、
            <br class="d-md-none">イベントのご案内などをお送りする
            <br class="d-md-none">ニュースレターです。
            <br>配信をご希望の方は
            <br class="d-md-none">下記フォームよりご登録ください。
          </p>
          <div class="form-row"> 
            <div class="col-12 col-md-6">
              <div class="mt-40 mt-md-60 d-md-flex flex-row ">
                <input type="text" class="form-control" placeholder="お名前" required="required">
                <input type="text" class="form-control" placeholder="メールアドレス" required="required">
              </div>
            </div>
          </div>
        </div>

        <div class="row justify-content-md-center">
          <div class="col-md-5">
            <div class="mt-50 mt-md-55">
              <div class="custom-control custom-checkbox custom-control-inline text-13 -lene">
                <input type="checkbox" class="custom-control-input">
                <label for="form-checkbox-01" class="custom-control-label">利用規約、プライバシーポリシーに同意</label>
              </div>
              <div class="mt-30 custom-control custom-checkbox custom-control-inline text-13 -line">
                <input type="checkbox" class="custom-control-input">
                <label for="form-checkbox-02" class="custom-control-label">20歳以上であることを確認する</label>
              </div>
              <br class="d-md-none">
              <span class="ml-40 ml-md-0 text-muted">※未成年者の飲酒は法律で禁止されています。</span> 
              <div>
                <button class="g-recaptcha btn btn-primary">登録する</button>
                <p class="mt-50 mt-md-55 text-muted">
                  This site is protected by reCAPTCHA and the Google<br>
                  <a href="">Privacy Policy</a> and
                  <a href="">Terms of Service</a> apply.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

  </main>
      

  
</template>

<script>
export default {}
</script>

<style>
.all {
text-align: center;
}

.btn-outline-white {
    color: #fff;
    border-color: #fff;
}

.btn {
    display: inline-block;
    font-weight: 400;
    color: #212529;
    text-align: center;
    vertical-align: middle;
    cursor: pointer;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
    background-color: transparent;
    border: 1px solid transparent;
    padding: .375rem 1.375rem;
    font-size: .875rem;
    line-height: 1;
    border-radius: 0;
}

.container-fluid {
  max-width: 1516px;
  width: 100%;
  padding-right: 38px;
  padding-left: 38px;
  margin-right: auto;
  margin-left: auto;
}

.swiper-wrapper {
  position: relative;
  width: 100%;
  height: 100%;
  z-index: 1;
  transition-property: transform;
  box-sizing: content-box
}



.p-storylist__item {
  margin:0 auto;
 }

 .form-row {
   display: flex;
   flex-wrap: wrap;
   margin-right: -5px;
   margin-left: -5px;
 }

 .form-control {
   width: 100%;
 }

.custom-control {
  position: relative;
  display: block;
}
 .custom-control-inline {
   display: inline-flex;
 }

 .custom-control-input {
   position: absolute;
   left: 0;
 }
/* .container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
} */
</style>