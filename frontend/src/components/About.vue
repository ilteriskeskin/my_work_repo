<template>
  <div id="app" class="main">
    <div class="container">

      <img src="../assets/img/ninja_ilto.jpg" class="ppImg">

      <h2 class="aboutH2">
        Kim bu İlteriş Keskin?
      </h2>

      <span>
        Ali İlteriş Keskin benim. <a href="https://heybooster.ai" class="about-a" target="_blank"><u>Heybooster</u></a>'da
        yazılım geliştirici olarak çalışıyorum. Boş vakitlerimde ise yeni şeyler öğrenmek için ve özgür yazılımlar
        geliştirmek için vakit harcıyorum. Elimden geldiğince özgür yazılımlar kullanmaya çalışıyorum.
      </span>
      <hr class="aboutHr">
      <ul>
        <li>
          5 yıldır GNU/Linux dağıtımları (şu an Ubuntu 20.04) kullanıyorum.
        </li>
        <li>
          5 yıldır Windows'a elimi sürmedim. (Bunun haklı gururunu yaşıyorum.)
        </li>
        <li>
          Para kazanmak için Python, Django, Flask ile hobi olarak C++ ile ilgileniyorum.
        </li>
        <li>
          Okulun bana bir şey katmadığını sadece diploma için okuduğumu düşünüyorum.
        </li>
        <li>
          Yeni şeyler öğrenmek kurcalamak çok keyif veriyor.
        </li>
        <li>
          Özgür yazılım felsefesini destekliyor ve benimsiyorum.
        </li>
        <li>
          Şimdilerde frontend tarafındaki bilgilerimi güçlendiriyorum. Vue.js öğrenmeye başladım.
        </li>
      </ul>
      <p class="aboutP">
        <a href="https://github.com/ilteriskeskin" target="_blank" class="about-a"><u>GitHub</u></a> ve <a
        href="https://gitlab.com/ilteriskeskin" target="_blank" class="about-a"><u>GitLab</u></a>
        hesaplarımdan paylaştığım projelere bakabilirsiniz.
      </p>
    </div>
  </div>
</template>

<script>
  export default {
    name: "About"
  }
</script>

<style scoped>
  img {
    width: 100%;
    max-width: 300px;
    height: 100%;
    max-height: 300px;
  }

  li, span {
    color: #d1cec9;
  }

  .main {
    margin-bottom: calc(15% + 10px);
  }

  .aboutH2 {
    font-weight: 900;
    margin-bottom: 20px;
    color: #f2f2f2;
  }

  .aboutP {
    color: #d1cec9;
  }

  .aboutHr {
    border: 1px solid #d1cec9;;
  }

  .ppImg {
    display: block;
    margin-left: auto;
    margin-right: auto;
    margin-bottom: 20px;
    border-radius: 35%;
  }
</style>
