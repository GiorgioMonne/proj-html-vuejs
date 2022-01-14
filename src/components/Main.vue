<template>
  <main>
      <div class="scriptum">
          <h2 class="titolo">Luxury Spa Experiences</h2>
          <span class="foglia"><i class="fab fa-envira"></i></span>
          <h3 class="morbi">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Tenetur est ratione exercitationem dicta. Sed vitae sequi quas quo itaque similique. Exceptu</h3>
          <hr>
          <h3 class="vestibulum">Lorem ipsum dolor sit amet consectetur adipisicing elit. Reprehenderit ipsum adipisci officiis eos aut quasi quisquam atque odio porro sequi repudiandae, possimus qui ea excepturi cupiditate dolorum ut harum aperiam.lorem Lorem ipsum dolor, sit amet consectetur adipisicing elit. Officiis id hic quia rem odio, velit nemo ipsam! Dolor omn</h3>
          <button class="approach">OUR APPROACH</button>
      </div>

        <Disegni/>

      <div class="appointment">
          <div class="foto">
              <img src="../assets/foto/jacuzzi.jpg" alt="">
          </div>

          <div class="info-foto">
              <div class="contenuto">
                  <h2>Face & Body Treatments</h2>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sed maxime nisi placeat repellat voluptates cumque ullam accusantium in illum.</p>


                <div class="comparsa">
                  <div class="oil-mass">
                      <div class="normal active">
                          <i class="fas fa-plus-square"></i> <h4>Oil Massage</h4>
                      </div>

                      <div class="click">
                        <i class="fas fa-minus-square"></i> <h4>Oil Massage</h4>
                        <h5>$62 For 2 Hours - Lorem ipsum dolor sit amet</h5>
                      </div>
                  </div>

                  <div class="manicure">
                       <div class="normal active">
                          <i class="fas fa-plus-square"></i> <h4>Manicure</h4>
                      </div>

                      <div class="click">
                        <i class="fas fa-minus-square"></i> <h4>Manicure</h4>
                        <h5>$62 For 2 Hours - Lorem ipsum dolor sit amet</h5>
                      </div>

                  </div>

                  <div class="aromatherapy">
                       <div class="normal active">
                          <i class="fas fa-plus-square"></i> <h4>Aromatherapy</h4>
                      </div>

                      <div class="click">
                        <i class="fas fa-minus-square"></i> <h4>Aromatherapy</h4>
                        <h5>$62 For 2 Hours - Lorem ipsum dolor sit amet</h5>
                      </div>

                  </div>
                </div>

                    <button id="info-btn" class="approach">BOOK AN APPOINTMENT</button>

                </div>
              
            </div>
        </div>

        <div class="lista-trattamenti">
          <div class="top">
              <h2>OUR TREATMENTS</h2>
          </div>

        <Card/>

        </div>

        <div class="secondo-jumbo">
          <img class="saponi" src="../assets/foto/belli.jpg" alt="">

            <div class="cont">
                <p>"Lorem ipsum dolor sit amet consectetur adipisicing elit. Et in molestiae distinctio, omnis corporis ex maiores cumque consectetur aperiam consequuntur alias nobis laboriosam earum ab placeat impedit repellat quibusdam iusto..."</p>
                <h4>FRIEDA FRIEDSON,MASSEUSE</h4>
            </div>

        </div>

      <div class="sconto">
          <div class="rimpicc">
              <div class="blocco">
              <h2>25%</h2>
              <span>SPECIAL OFFER</span>
          </div>

          <div class="centro">

            <h2>Take some time. Treat yourself. You deserve it.</h2>
            <h3>Book a treatment this month and receive a 25% on all futher treatments</h3>

          </div>

          <div class="btn">
              <button>BOOK NOW</button>
          </div>
          </div>
      </div>
  </main>
</template>

<script>

import Card from '../assets/sections/Card.vue';
import Disegni from '../assets/sections/Disegni.vue';

export default {
    name: 'Main',
    components: {
        Card,
        Disegni
    }
}
</script>

<style lang="scss" scoped>

.scriptum{
    width: 800px;
    text-align: center;
    margin: 40px auto;
    color: lightgray;

    .titolo{
        font-size: 60px;
        margin: 20px;
        color:  rgb(142, 142, 170);
    }

    .foglia{
        font-size: 27px;
        margin:20px 0;
    }

    .morbi{
        margin: 30px 0;
    }

    hr{
        width: 60px;
        margin: auto;
    }

    .vestibulum{
        margin: 30px;
    }
}

.approach{
        padding: 10px 25px;
        border-radius: 20px;
        border: 2px solid rgb(181, 180, 180);
        background-color: white;
        color: rgb(181, 180, 180);
        font-weight: bold;
        cursor: pointer;
}

.appointment{
    width: 1000px;
    padding: 100px auto;
    margin: 150px auto;
    display: flex;
    

    .foto{
        width: 50%;
        background-color: aquamarine;  
        box-shadow: 4px 4px 3px 3px rgb(192, 192, 192); 
        margin:0 20px;   

        img{
            height: 100%;
            width: 100%;
            border: 20px solid white;
            
        }
    }

    .info-foto{
        width: 50%;
        margin: auto;

        .contenuto{
            width: 60%;
            margin: auto;

            h2{
            font-size: 45px;
            }

            p{
            margin:30px 0;
            }

            .comparsa{
                // background-color: bisque;

                .oil-mass{
                    border: 1px solid rgb(226, 226, 226);
                    padding: 10px;

                }

                .manicure{
                    border: 1px solid rgb(226, 226, 226);
                    padding: 10px;
                    margin: 5px 0;
                }

                .aromatherapy{
                    border: 1px solid rgb(226, 226, 226);
                    padding: 10px;
                }

                i{
                    margin: 0 10px 0px 0;
                    color: grey;
                }

                .click{
                    display: flex;
                    flex-wrap: wrap;
                    display: none;
                    

                    h5{
                       padding-right: 50px;
                       margin: 20px 5px;
                       color: grey;
                    }
                }

                .active{
                    display: inline;
                }

                .normal{
                    display: flex;
                    color: rgb(177, 176, 176);
                }
            }

            #info-btn{
                margin: 30px 0;
                cursor: pointer;
            }
        }

        
    }

    
}

.lista-trattamenti{
        width: 100%;
        // background-color: aquamarine;

        .top{
            height: 150px;
            text-align: center;
            line-height: 150px;
            color: white;
            background-image: url('../assets/foto/disegnobello.jpg');
        }        
}

.secondo-jumbo{
            height: 600px;
            width: 100%;
            position: relative;

            img{
                height: 100%;
                width: 100%;  
            }

            .cont{
                width: 30%;
                position: absolute;
                text-align: center;
                color: rgba(19, 3, 18, 0.87);
                top: 50%;
                left: 50%;
                transform: translate(-50% , -50%);
                font-weight: bold;
                

                p{
                    font-size: 18px;
                }

                h4{
                    font-size: 20px;
                    padding: 10px 0;
                }
            }
 }

.sconto{
    background-image: url('../assets/foto/disegnobello.jpg');
    // opacity: 0.2;
    display: flex;
    color: white;
    padding: 130px;

    .rimpicc{
        display: flex;
        margin:auto;

        .blocco{
            display: flex;
            flex-direction: column;
            height: 100px;
            width: 100px;
            border: 1px solid lightgrey;
            align-items: center;
            justify-content: center;
            

            h2{
                font-size: 40px;
            }

            span{
                font-size: 10px;
                
            }
        }

        .centro{
            margin:0 140px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            color: black;  
            
            h2{
                margin: 10px;
            }
        }

        .btn{
            display: flex;
            align-items: center;

            button{
                padding: 8px 25px;
                border-radius: 20px;
                background-color: lightgrey;
                color: white;
                font-weight: bold;
                cursor: pointer;
            }
        }

    }
}

</style>

