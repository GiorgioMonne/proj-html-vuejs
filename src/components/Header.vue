<template>
  <header>
        <div class="nav">
            <div class="left">

                <div class="navali">
                    <i id="blue" class="fas fa-home"></i>  
                </div>

                <div class="navali">
                    <i class="fab fa-pagelines"></i>
                    <h4>TREATMENT</h4>
                    <h5>Face & body</h5>    
                </div>
                <div class="navali">
                    <i class="fas fa-male"></i>
                    <h4>ABOUT</h4>
                    <h5>Our Team</h5>    
                </div>
            </div>

            <div class="mid">

              <img id="logotop" src="../assets/foto/avada-spa-logo-retina-new-200x23.png" alt="">

            </div>

            <div class="navali">
                <i class="fas fa-heart"></i>
                <h4>JOURNAL</h4>  
                <h5>Tips & Tricks</h5>  
            </div>
            <div class="navali">
                <i class="fas fa-bookmark"></i>
                <h4>TREATMENT</h4>
                <h5>Special Offers</h5>    
            </div>    
            <div class="navali">
                   <i class="fas fa-plus"></i>
            </div>  

        </div>

        <div class="jumbo">
          <img src="../assets/foto/avada-spa-slider-image-1-new.jpg" alt="">

          <div class="cubo-info">
              <div class="cubo-uno">
                  <i class="fas fa-folder-open"></i>
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
        width: 100%;
        height: 100px;
        display: flex;
        justify-content: center;
        align-items: center;

        .left{
            display: flex;

            #blue{
                color: rgb(85, 175, 226);
            }

        }

        .navali{
            margin: 0 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            color: grey;
            cursor: pointer;
            
            h5{
                color: lightgray;
            }
        }

        .mid{
            margin: 0 50px;
        
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
            height: 60px;
            width: 60px;
            border-radius: 10px;
            background-color: pink;
            text-align: center;
            cursor: pointer;

            i{
                padding-top: 5px;
                font-size: 25px;
            }
        }

        .cubo-due{
            position: absolute;
            top: 140px;
            right: 10px;
            height: 60px;
            width: 60px;
            border-radius: 10px;
            background-color: pink;
            text-align: center;
            padding-top: 5px;
            cursor: pointer;
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
                cursor: pointer;
            }
        }
    }

</style>