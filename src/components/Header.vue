<template>
  <header>
    <div class="header-in">
      <div class="title">
        <div class="logo">
          <img src="../assets/isaralogo.png" alt="iSara">
        </div>
        <div class="subtitle txtxs">
          <p>バンコクのノマドエンジニア育成講座</p>
        </div>
        <div class="headcontact">
          <div class="contactpc startpoint">
            <p class="txtxs">お問い合わせ / 資料請求はこちら</p>
          </div>
          <div class="contactsp startpoint">
            <img src="../assets/form.png">
            <a href="">資料請求</a>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<style scoped>

body {
  letter-spacing: 1.5px;
}

body, p, h1, h2, h3, h4, h5, h6 {
  text-rendering: optimizeLegibility;
  background: rgba(0, 0, 0, 0);
  -webkit-font-smooting: antialiased;
}

p {
  margin: 0 0 10px;
  display: block;
  margin-block-start: 1rem;
  margin-block-end: 1rem;
  margin-inline-start: 0px;
  margin-inline-end: 0px;
}

header {
  position: fixed;
  z-index: 10;
  background-color: #fff;
  width: 100%;
}

.header-in {
  display: block;
}

.title {
  width: 1170px;
  max-width: calc(100% - 20px);
  margin: 0 auto;
  position: relative;
  padding: 20px 0;
  height: 75px;
}

.title .logo, .subtitle {
  display: inline-block;
}

.logo {
  margin-top: -6px;
}

.logo img {
  width: 128px;
}

img {
  width: auto;
  height: auto;
  max-width: 100%;
  max-height: 100%;
  vertical-align: middle;
  border: 0;
}

.subtitle {
  position: relative;
  bottom: -10px;
}

.txtxs {
  font-size: 14px;
  font-weight: 300;
}

.subtitle p {
  font-weight: 600;
  margin-bottom: 0;
}

.contactpc {
  cursor: pointer;
  position: absolute;
  right: 0px;
  top: 16px;
  color: #fff;
  padding: 11px 40px;
  background-color: #da6b64;
  border-radius: 25px;
}

.contactpc p {
  margin: 0;
}

.contactsp {
  display: none;
}

a {
  color: #337ab7;
  text-decoration: none;
  background-color: transparent;
}

</style>