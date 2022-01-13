<template>
  <header>
      <div class="nav">
          <ul>
              <li class="left">
                  <a href="#">dfgdf</a>
                  <a href="#">dfgg</a>
                  <a href="#">dfg</a>
              </li>
              <li class="titolo">
               <img src="../assets/foto/avada-spa-logo-retina-new-400x46.png" alt="">
              </li>
              <li class="right">
                  <a href="#">dfg</a>
                  <a href="#">fgsdfg</a>
                  <a href="#">dgdg</a>
                  <a href="#">+</a>
              </li>
          </ul>
      </div>

      <div class="jumbo">
          <img src="../assets/foto/avada-spa-slider-image-1-new.jpg" alt="">

          <div class="cubo-info">
              <div class="cubo-uno">
                  <img src="" alt="">
                  <h5>Demos</h5>
              </div>

              <div class="cubo-due">
                  <h3>£39</h3>
                  <h4>On Sale</h4>
              </div>
          </div>

          <div class="info">
              <h4>Give Yuorself permission</h4>
              <h2>Relax, Revive & Rejuvenate</h2>
              <button>EXPLORE TREATMENTS</button>
          </div>
      </div>
  </header>
</template>

<script>
export default {
    name: 'Header'
}
</script>

<style lang='scss' scoped>

    .nav{
        height: 80px;
        width: 100%;
        background-color: greenyellow;

        ul{
            display: flex;
            justify-content: center;
            line-height: 80px;

            li{                
                list-style: none;
                margin: 0 30px;

                a{
                    margin: 20px;
                }

                img{
                    vertical-align: middle;
                   height: 30px;
                }
            }
        }
    }

    .jumbo{
        height: 850px;
        width: 100%;
        position: relative;
        background-color: bisque;

        img{
            height: 100%;
            width: 100%;
        }

        .cubo-uno{
            position: absolute;
            top: 40px;
            right: 10px;
            height: 80px;
            width: 80px;
            border-radius: 10px;
            background-color: pink;
            text-align: center;
        }

        .cubo-due{
            position: absolute;
            top: 140px;
            right: 10px;
            height: 80px;
            width: 80px;
            border-radius: 10px;
            background-color: pink;
            text-align: center;
        }

        .info{
            position: absolute;
            text-align: center;
            color: white;
            top: 40%;
            left: 50%;
            transform: translate(-50%, -40%);

            h4{
                font-size: 30px;
            }

            h2{
                font-size: 70px;
            }

            button{
                margin: 30px;
                padding: 10px 20px;
                border: none;
                border-radius: 15px;
                color: white;
                font-weight: bold;
                background-color: rgb(206, 203, 203);
            }
        }
    }

</style>