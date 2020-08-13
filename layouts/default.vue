<template>
  <div>
    <header class="l-header fixed-top bg-white" height="56px">
      <div class="align-items-center"><!-- あとでd-flex追加 -->
        <a href="">
          <img class="d-block mx-auto " src="../imges/sakehundred.svg" alt="sake hundred" width="252" height="24px" >
        </a>
      </div>
    </header>
      <!-- <div class="l-header__row d-flex align-items-center justify-content-between">
        <div class="l-header__menu">
          <button class="navbar-toggler" type="button" data-toggle="collapse">
          </button>
          
        </div>
      </div> -->
    <Nuxt />
    <footer role="contentinfo" class="l-footer pt-50 pb-30 pb-md-50 mt-105">
      <div class="row justify-content-md-between">
        <div class="col-md-3 d-md-flex flex-row">
          <p class="text-13 text-md-12 text-muted">ガイド</p>
          <ul class="list-unstyled d-flex flex-wrap d-md-block ">
            <li class="w-50 w-md-100 mt-30 mt-md-20">text</li>
            <li class="w-50 w-md-100 mt-30 mt-md-20">text</li>
            <li class="w-50 w-md-100 mt-30 mt-md-20">text</li>
            <li class="w-50 w-md-100 mt-30 mt-md-20">text</li>
            <li class="w-50 w-md-100 mt-30 mt-md-20">text</li>
            <li class="w-50 w-md-100 mt-30 mt-md-20">text</li>
          </ul>
        </div>

        <div class="col-md-3 d-md-flex flex-row">
          <p class="text-13 text-md-12 text-muted">リーガル</p>
          <ul class="list-unstyled d-flex flex-wrap d-md-block">
            <li class="w-50 w-md-100 mt-30 mt-md-20">text</li>
            <li class="w-50 w-md-100 mt-30 mt-md-20">text</li>
            <li class="w-50 w-md-100 mt-30 mt-md-20">text</li>
            <li class="w-50 w-md-100 mt-30 mt-md-20">text</li>
            <li class="w-50 w-md-100 mt-30 mt-md-20">text</li>
            <li class="w-50 w-md-100 mt-30 mt-md-20">text</li>
          </ul>
        </div>

        <div class="col-md-3 d-md-flex flex-row">
          <p class="text-13 text-md-12 text-muted">サービス</p>
          <ul class="list-unstyled d-flex flex-wrap d-md-block">
            <li class="w-50 w-md-100 mt-30 mt-md-20">text</li>
            <li class="w-50 w-md-100 mt-30 mt-md-20">text</li>
            <li class="w-50 w-md-100 mt-30 mt-md-20">text</li>
            <li class="w-50 w-md-100 mt-30 mt-md-20">text</li>
            <li class="w-50 w-md-100 mt-30 mt-md-20">text</li>
            <li class="w-50 w-md-100 mt-30 mt-md-20">text</li>
          </ul>
        </div>
      </div>
      <p class="mt-80 text-center">
        <img src="../imges/sake-handred.svg" width="384" height="130">
      </p>
      <p1>
        <p class="mt-30 mt-md-40 text-center text-muted mb-0">
          <small>©︎ 2020 Clear Inc.</small>
        </p>
      </p1>
    </footer>
  </div>
</template>

<script>
export default {}
</script>

<style>
header {
  height: 56px;
}

.img {
  vertical-align: middle;
}

.l-footer {
  background-color: #111;
  color: #fff;
  line-height: 1.3333;
}
footer {
  margin-bottom: 0;
  padding-bottom: 0;
}

/* html {
  font-family:
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3b8070;
  color: #3b8070;
  text-decoration: none;
  padding: 10px 30px;
}

.button--green:hover {
  color: #fff;
  background-color: #3b8070;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
} */
</style>
