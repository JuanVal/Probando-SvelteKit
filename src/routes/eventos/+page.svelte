<h1>DESCUBRE Y PARTICIPA EN NUESTROS EVENTOS DESDE DEL INICIO</h1>

<section class="container-events">
<div class="item">
  <h3>Item</h3>
  <img src="https://firebasestorage.googleapis.com/v0/b/appgoldeoro.appspot.com/o/eventos%2Fportadas%2Ftryout_imagen.jpg?alt=media&token=74c55421-9c3c-4e7c-b427-44fdfbd70bd7" alt="">
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Adipisci dolores maxime expedita eos eligendi nobis sit alias ab autem. Totam?</p>
</div>
<div class="item">
  <h3>Item</h3>
  <img src="https://firebasestorage.googleapis.com/v0/b/appgoldeoro.appspot.com/o/eventos%2Fportadas%2Ftorneos_patrocinados.jpg?alt=media&token=013ca3ee-4b84-4ecc-8210-e835ab5a592e" alt="">
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Adipisci dolores maxime expedita eos eligendi nobis sit alias ab autem. Totam?</p>
</div>
<div class="item">
  <h3>Item</h3>
  <img src="https://firebasestorage.googleapis.com/v0/b/appgoldeoro.appspot.com/o/eventos%2Fportadas%2Fformacion.jpg?alt=media&token=c6214afa-0f48-4cd7-8382-62ff5f725feb" alt="">
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Adipisci dolores maxime expedita eos eligendi nobis sit alias ab autem. Totam?</p>
</div>
<div class="item">
  <h3>Item</h3>
  <img src="https://media.discordapp.net/attachments/1016294469668180029/1038396570787381288/torneos_clubes_y_privados.webp?width=729&height=557" alt="">
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Adipisci dolores maxime expedita eos eligendi nobis sit alias ab autem. Totam?</p>
</div>
</section>


<style>
.container-events{
  display: grid;
  grid-template-columns: repeat(2, calc(50% - .5rem));
  grid-auto-rows: 500px;
  gap: 1rem;
  padding: 1rem;
  width: 900px;
  height: 500px;
  background: indigo;
  overflow: hidden scroll;
}
.item{
  background: gray;
  display: flex;
  flex-direction: column;
}
img{
  width: 100%;
  height:100%;
  object-fit: cover;
}
h3{
  text-align: center;

}
p{
  padding: 1rem;
}
</style>