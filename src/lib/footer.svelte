<main>
  <section id="footer">
    <div class="container">
      <div class="row">
        <div id="sitios" class="col-3">
          <div class="titulo">
            <h3>Otros Sitios</h3>
          </div>
          <div class="elementos">
            <p><a href="#top">Portal de Educación</a></p>
            <p><a href="#top">Programa Papas</a></p>
            <p><a href="#top">Intranet</a></p>
            <p><a href="#top">Delphos</a></p>
            <p><img src="img/fseu.png" alt="union-europea"></p>
          </div>
        </div>
        <div id="contacto" class="col-3">
          <div class="titulo">
            <h3>Contacto</h3>
          </div>
          <div class="elementos">
            <p>I.E.S. Azarquiel</p>
            <p>Paseo de San Augenio, 21</p>
            <p>45003 - Toledo</p>
            <p><i class="fa fa-phone"></i>: 925284043</p>
            <p><i class="fa fa-fax"></i>: desde el 20/01/2020 No Operativo</p>
            <p><i class="fa fa-envelope"></i>CENTRO: <a href="#top">45003875.ies@edu.jccm.es</a></p>
            <p><i class="fa fa-envelope"></i>AMPA: <a href="#top">azarquiel.ampa@gmail.com</a></p>
            <p><i class="fa fa-envelope"></i>PAPAS: <a href="#top">azarquiel.papas@gmail.com</a></p>
          </div>
        </div>
        <div id="localizacion" class="col-6">
          <div class="titulo">
            <h3>Localización</h3>
          </div>
          <div class="elementos">
            <!-- svelte-ignore a11y-missing-attribute -->
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3062.1442480633414!2d-4.025172850152187!3d39.87100669647257!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0xd6a0a53483a57e7%3A0xc7f7d4815179b44b!2sIES%20Azarquiel!5e0!3m2!1ses!2ses!4v1675194746190!5m2!1ses!2ses" width="550" height="300" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
          </div>
      </div>
    </div>
  </section>
  <footer>
    <div id="footer-copy" class="col-12">
      <div class="container">
        <h1>© 2022 IES Azarquiel.</h1>
      </div>
    </div>
  </footer>    
</main>

<style lang="sass">
  section
    background-color: #009cde
    color: white
    padding-top: 1rem

    .elementos
      font-size: 14px

      a:link
        text-decoration: none
        color: white

    img
      width: 16rem

  footer
    background-color: #009cde
    padding-top: 1rem
    height: 4rem

    h1 
      font-size: 17px
      color: white
      text-align: center
      font-weight: bold

  @media screen and (max-width: 1130px)
    .row
      display: flex
      flex-direction: column


</style>
