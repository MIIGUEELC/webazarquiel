<main>
    <div class="container d-flex justify-content-center">
        <h1>Contenido de los cursos</h1>

    </div>
    <div class=" tarjetas d-flex justify-content-center">
        <div id="carouselExampleFade" class="carousel " data-bs-ride="carousel">
        
            <div class="carousel-inner">
                
                    <div class="carousel-item active">
                    
                        <div class="card" style="width: 40rem;">
                            <img class="card-img-top" src="/img/videojuegoss-png.jpg" alt="">
                            <div class="card-body">
                              <h5 class="card-title">VIDEOJUEGOS</h5>
                              <p class="  card-text">Aprende todo lo relacionado sobre el desarrollo de videojuegos.</p>
                              <a href="/videojuegos" class="btn btn-primary">Informacion</a>
                            </div>
                        </div>
                    </div>    
               
                    <div class="carousel-item ">
                 
                        <div class="card" style="width: 40rem;">
                            <img class="card-img-top" src="/img/ciberseguridad.png" alt>
                            <div class="card-body">
                                 <h5 class="card-title">CIBERSEGURIDAD</h5>
                                <p class="card-text">Conviertete en experto en seguridad de sistemas</p>
                                <a href="/ciberseguridad" class="btn btn-primary">Informacion</a>
                            </div>
                        </div>
                    </div>    
                   
             
            </div>

        
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleFade" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleFade" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
    </div>

    </div>

    <img src="" alt="">
   
      
    

</main>
<style lang="sass">

    .tarjetas
        margin-bottom: 2rem
        border-color: black
    .card
         box-shadow:  5px 10px 18px blue
        
    .carousel-control-prev, .carousel-control-next
        height: 8rem
        position: absolute 
        top: 30%
    main
       
        background-image: url('/img/azarquielfondo.png')
        background-size: cover
        background-repeat: no-repeat
        backdrop-blur: 10px
        

</style>