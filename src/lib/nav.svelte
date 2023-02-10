<main>
  <section id="barra-nav">
    <div class="container">
      <div class="row">
        <div id="nav-imagen" class="col-4">
          <img src="img/logoiesazarquiel.png" alt="logo-azarquiel"/>
        </div>
        <div id="nav-menu" class="col-8">
          <div>
            <ul class="menu">
              <li class="datosmenu"><a href="#top">INICIO</a></li>
              <li class="datosmenu"><a href="#top">AL DÍA</a><i class="fa-solid fa-angle-down"></i></li>
              <li class="datosmenu"><a href="#top">AL LORO</a></li>
              <li class="datosmenu"><a href="#top">EL CENTRO</a><i class="fa-solid fa-angle-down"></i></li>
              <li class="datosmenu"><a href="#top">SECRETARÍAS</a><i class="fa-solid fa-angle-down"></i></li>
              <li class="datosmenu"><a href="#top">FAMILIAS</a><i class="fa-solid fa-angle-down"></i></li>
              <li class="datosmenu"><a href="#top">BOLSA</a></li>
              <i class="fa-solid fa-bars" id="barrasmenu" data-bs-toggle="offcanvas" data-bs-target="#demo"></i>
            </ul>
          </div>
        </div>
        <div class="offcanvas offcanvas-end" id="demo">
          <div class="offcanvas-header">
            <h1 class="offcanvas-title">SEARCH</h1>
            <button type="button" class="btn-close text-reset" data-bs-dismiss="offcanvas"></button>
          </div>
          <div class="offcanvas-body">
            <input type="text" placeholder="Search ..." size="40rem">
            <ul class="menu-desplegable">
              <li><i class="fa-solid fa-angle-right"></i><a href="#top" class="cont-list">INICIO</a></li>
              <li><i class="fa-solid fa-angle-right"></i><a href="#top" class="cont-list">AL DÍA</a><i class="fa-solid fa-angle-down" id="mascontenido"></i></li>
              <li><i class="fa-solid fa-angle-right"></i><a href="#top" class="cont-list">AL LORO</a></li>
              <li><i class="fa-solid fa-angle-right"></i><a href="#top" class="cont-list">EL CENTRO</a><i class="fa-solid fa-angle-down" id="mascontenido"></i></li>
              <li><i class="fa-solid fa-angle-right"></i><a href="#top" class="cont-list">SECRETARÍAS</a><i class="fa-solid fa-angle-down" id="mascontenido"></i></li>
              <li><i class="fa-solid fa-angle-right"></i><a href="#top" class="cont-list">FAMILIAS</a><i class="fa-solid fa-angle-down" id="mascontenido"></i></li>
              <li><i class="fa-solid fa-angle-right"></i><a href="#top" class="cont-list">BOLSA</a></li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </section>
</main>

<style lang="sass">
  section
    padding-top: 2rem
    padding-bottom: 2rem

    img
      width: 16rem
      height: 3rem

    .menu
      display: flex
      font-size: 13px
      column-gap: 1rem
      list-style: none
      text-decoration: none
      padding-top: 0.3rem
      padding-left: 3rem
      color: black

      a:link
        text-decoration: none
        color: black

    .fa-solid:hover
      cursor: pointer

    #demo
      background-color: #3D3D3D

      h1
        color: white
          
    .menu-desplegable
      display: flex
      flex-direction: column
      row-gap: 1rem
      list-style: none
      padding-top: 6rem

      a:link
        text-decoration: none
        color: white

      .cont-list
        padding-left: 1rem

      .fa-solid
        color: white

  @media screen and (max-width: 1000px)      
    .datosmenu
      display: none     

    #barrasmenu
      padding-left: 22rem
      
</style>
