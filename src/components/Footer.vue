<template>
  <footer>
      <div class="fine">
        <div class="logo">
          <img src="../assets/foto/avada-spa-logo-new.png" alt="">
        </div>

        <div class="link">
            <h4>@COPYRIGHT 2012-2020 | AVADA THEME BY THEMFUSION | ALL RIGHTS RESERVED | POWERED BY WORDPRESS</h4>
        </div>

        <div class="social">
            <div class="soc">
              <i class="fab fa-facebook-f"></i>
            </div>
            <div class="soc">
              <i class="fab fa-twitter-square"></i>
            </div>
            <div class="soc">
              <i class="fab fa-instagram"></i>
            </div>
            <div class="soc">
              <i class="fab fa-youtube"></i>
            </div>
           
        </div>
      </div>
  </footer>
</template>

<script>
export default {
    name: 'Footer'
}
</script>

<style lang="scss" scoped>

.fine{
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 20px 30px;

    .logo{
      width: 33%;
    }

  .link{
    width: 33%;
    text-align: center;
    font-size: 10px;
  }

  .social{
    width: 33%;
    display: flex;
    justify-content: flex-end;
    align-items: center;

    .soc{
      height: 40px;
      width: 40px;
      background-color: lightgray;
      text-align: center;
      line-height: 40px;
      margin: 5px;
      cursor: pointer;
    }

  }
    
}

</style>