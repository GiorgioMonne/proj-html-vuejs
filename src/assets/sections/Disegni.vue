<template>

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
  
</template>

<script>
export default {
    name: 'Disegni'
}
</script>

<style lang="scss" scoped>

.disegni{
        height: 150px;
        width: 1100px;
        margin:100px auto;
        display: flex;
        // background-color: red;

        .scard{
            height: 60%;
            width: calc(100% / 5);
            align-items: center;
            flex-direction: column;
            display: flex;
            color: rgb(187, 185, 185);
            cursor: pointer;
            
        }

        .due{
           align-self: flex-end;
        }

        #emo{
            font-size: 40px;
            margin: 10px;
        }
}

</style>