<template>
    <section class="hero  is-fullheight-with-navbar">
        <div class="hero-body">
            <div class="container">
                <div class="contenedor_texto">
                    <h1>Te estamos rederigiendo a</h1>
                    <h2>Notorious.cl</h2>
                    <h3>En <strong>3</strong> segundos</h3>
                    <b-button type="is-dark"
                        inverted
                        outlined
                        class="cancelar"
                        >
                        Cancelar redirección
                    </b-button>
                    <h4>¿Te gustaria saber más?</h4>
                    <b-button type="is-dark"
                        inverted
                        class="blog"
                        >
                        <span>Visita nuestro blog</span>
                    </b-button>
                </div>
                <div class="contenedor_imagen">
                    
                </div>
                
            </div>
        </div>
    </section>
</template>
<script>
export default {
    name: "Hero"
}
</script>
<style lang="scss" scoped>
    .container{
        display: grid;
        grid-template-columns: repeat(2,1fr);
                background-image: url('../assets/img/mari.png');
        background-size: cover;
        background-position: center top;
    }
    .contenedor_texto{
        width: 40vw;
        h1{
            font-size: 2.5vw;
            width: 100%;
        }
        h2{
            font-size: 2vw;
        }
        h3{
            font-size: 1.5vw;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif !important;;
            strong{
                color: white;
            }
            margin-bottom: 1%;
        }
        .cancelar{
            padding: 0 2%;
            margin-bottom: 5%;
        }
        h4{
            font-size: 1.5vw;
        }
        .blog{
            font-size: 1vw;
            padding: 0.2vw 1.5vw 1.5vw 1.5VW;
            margin: 2% 0;
            span{
                font-weight: 800;
                
            }
        }
    }
    .contenedor_imagen{


    }

</style>