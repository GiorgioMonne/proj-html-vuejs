<template>
    <div class="card-list">
        <div class="carta">
            <img src="../foto/donna-acqua.jpg"  alt="">
            <h2>Hydrotherapy</h2>
            <hr>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iure veniam voluptates, adipisci explicabo qsdgsgsdgdfasdadqcsa</p>
        </div>

        <div class="carta">
            <img src="../foto/massaggino.jpg" alt="">
            <h2>Hydrotherapy</h2>
            <hr>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iure veniam voluptates, adipisci explicabo qsdgsgsdgdfasdadqcsa</p>
        </div>

        <div class="carta">
            <img src="../foto/cose.jpg" alt="">
            <h2>Hydrotherapy</h2>
            <hr>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iure veniam voluptates, adipisci explicabo qsdgsgsdgdfasdadqcsa</p>
        </div>

        <div class="carta">
            <img src="../foto/centro-benessere.jpg" alt="">
            <h2>Hydrotherapy</h2>
            <hr>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iure veniam voluptates, adipisci explicabo qsdgsgsdgdfasdadqcsa</p>
        </div>

        <div class="carta">
            <img src="../foto/skincare-pelle-grassa.webp" alt="">
            <h2>Hydrotherapy</h2>
            <hr>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iure veniam voluptates, adipisci explicabo qsdgsgsdgdfasdadqcsa</p>
        </div>

        <div class="carta">
            <img src="../foto/healthy_porridge_bowl-d434804.jpg" alt="">
            <h2>Hydrotherapy</h2>
            <hr>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iure veniam voluptates, adipisci explicabo qsdgsgsdgdfasdadqcsa</p>
        </div>

        <div class="carta">
            <img src="../foto/treatments.jpg" alt="">
            <h2>Hydrotherapy</h2>
            <hr>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iure veniam voluptates, adipisci explicabo qsdgsgsdgdfasdadqcsa</p>
        </div>

        <div class="carta">
            <img src="../foto/bagno.jpg" alt="">
            <h2>Hydrotherapy</h2>
            <hr>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iure veniam voluptates, adipisci explicabo qsdgsgsdgdfasdadqcsa</p>
        </div>
        
    </div>

</template>

<script>
export default {
    name: 'Card',
    components:{

    }
}
</script>

<style lang="scss" scoped>

    .card-list{
            display: flex;
            flex-wrap: wrap;
    }

    .carta{
            height: 600px;
            width: calc(100% / 4);
            border: 1px solid rgb(241, 241, 241);
            color: grey;
            cursor: pointer;

            img{
                height: 70%;
                width: 100%;
                
            }

            hr{
                width: 90%;
                margin:15px auto;
                color: lightgray;
            }

            h2{
                margin:15px 20px;
            }

            p{
                margin:15px 20px;
            }
     }

</style>