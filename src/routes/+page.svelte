<main>
  <section id="card-titulos">
    <div class="container">
      <div class="row">
        <div class="card col-6" style="width:32rem">
          <div class="card-body">
            <h4 class="card-title">Curso de Especialización. Desarrollo de Videojuegos y Realizad Virtual</h4>
            <img class="card-img-top" id="imgjuego" src="img/pexels-garrett-johnson-3800795.jpg" alt="imagen-des-videojuegos">
            <div class="boton">
              <a href="/videojuegos" class="btn btn-primary">Más información</a>
            </div>
          </div>
        </div>
        <div class="card col-6" style="width:32rem">
          <div class="card-body">
            <h4 class="card-title">Curso de Especialización. Ciberseguridad en Entornos de las Tecnologías de la Información</h4>
            <img class="card-img-top" id="imgseguridad" src="img/cyber-security-g780a90f3b_1920.jpg" alt="imagen-ciberseguridad">
            <div class="boton">
              <a href="/ciberseguridad" class="btn btn-primary">Más información</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</main>

<style lang="sass">
  section
    padding-top: 1rem
  .card
    height:35rem
    margin-left: 3rem
    margin-bottom: 10rem
    border: 0.2rem solid #009CDE
    animation: rosauwu 2s
    animation-direction: normal
    animation-fill-mode: forwards
    animation-duration: alternate
    animation-timing-function: linear

    .card-title
      padding-top: 1rem
      color: #005D9D

    #imgjuego
      padding-top: 4rem
      width: 28rem
      height: 23rem

    #imgseguridad
      padding-top: 2rem
      height: 21rem

    .boton
      align-items: center
      padding-top: 2rem

  @keyframes rosauwu 
    0% 
      transform: translateY(-200%)
      opacity: 0%
  
  @media screen and (max-width: 1200px)
    .row
      display: flex
      flex-direction: column
      align-items: center
      
</style>


