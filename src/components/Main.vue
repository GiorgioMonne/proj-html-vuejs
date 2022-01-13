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

      <div class="disegni">
          <div class="scard uno">
              <i id="emo" class="fas fa-hands-wash"></i>
              <h3>Massages</h3>
          </div>
          <div class="scard due">
              <i id="emo" class="far fa-smile"></i>
                <h3>Therapy</h3>
          </div>
          <div class="scard uno">
              <i id="emo" class="fas fa-heart"></i>
              <h3>Relaxing</h3>
          </div>
          <div class="scard due">
              <i id="emo" class="far fa-moon"></i>
              <h3>Meditation</h3>
          </div>
          <div class="scard uno">
              <i id="emo" class="fas fa-bahai"></i>
              <h3>Natural Beauty</h3>
          </div>
      </div>
  </main>
</template>

<script>
export default {
    name: 'Main'
}
</script>

<style lang="scss" scoped>

.scriptum{
    width: 800px;
    text-align: center;
    margin: 40px auto;

    .titolo{
        font-size: 60px;
        margin: 20px;
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

    .approach{
        padding: 10px 25px;
        border-radius: 20px;
        border: 2px solid rgb(181, 180, 180);
        background-color: white;
        color: rgb(181, 180, 180);
        font-weight: bold;
    }
}

.disegni{
        height: 150px;
        width: 1200px;
        margin:50px auto;
        display: flex;
        // background-color: red;

        .scard{
            height: 60%;
            width: calc(100% / 5);
            align-items: center;
            flex-direction: column;
            display: flex;
            color: rgb(187, 185, 185);
        }

        .due{
           align-self: flex-end;
        }

        #emo{
            font-size: 50px;
            margin: 10px;
        }
}

</style>