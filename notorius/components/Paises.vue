<template>
      <section class="container">
            <div class="banderas">
                  <span class="has-text-centered">
                        <img src="../assets/img/chile.png" alt="chile">
                        <h1>chile</h1>
                  </span>
                  <span class="has-text-centered"> 
                        <img src="../assets/img/argentina.png" alt="argentina">
                        <h1>argentina</h1>
                  </span>
                  
            </div>
            <hr>
            <div class="has-text-centered">
                  <p>¿Necesitas más ayuda?</p>
                  <p>Haz click en cualquiera de los iconos para comunicarte con nosotros</p>
            </div>
            <div class="iconos has-text-centered">
                  <b-icon
                        class="icono"
                        icon="whatsapp"
                        size="is-small">
                  </b-icon>
                  <b-icon
                        class="icono"
                        icon="instagram"
                        size="is-small">
                  </b-icon>
                  <b-icon
                        class="icono"
                        icon="facebook"
                        size="is-small">
                  </b-icon>
                  <b-icon
                        class="icono"
                        icon="email"
                        size="is-small">
                  </b-icon>
                  <b-icon
                        class="icono"
                        icon="phone"
                        size="is-small">
                  </b-icon>
            </div>
      </section>
</template>
<script>
export default {
      name:'Paises'
}
</script>
<style lang="scss" scoped>
      .container{
            background-image: url('../assets/img/anna.png');
            background-size: cover;
            background-position: center top;
      }
      hr{
            opacity: 0.5;
      }
      .banderas{

            display: grid;
            grid-template-columns: repeat(2,1fr);
            span{
                  margin: 20% 10%;
                  img{
                        width: 15vw;
                        margin: 10% 0
                  }
                  h1{
                        font-size: 2vw
                  }
            }
      }
      .has-text-centered{
            margin-top: 8%;
            p{
                  font-size: 1.5vw;
                  margin: 2vw 0
            }
      }
      .iconos{
            margin: 5% 0;
            padding-bottom: 5%;
            .icono{
                  color: white;
                  font-size: 3vw;
                  margin: 5% 3%
            }
      }
</style>