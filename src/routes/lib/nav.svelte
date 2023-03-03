<main>
    <div class="navegacion">
        <div class="row">
            <div class="col-md-4">
                <div class="logo">
                    <img src="/img/logoazarquiel.png" alt="" />
                </div>
            </div>
            
            <div class="col-md-6 align-middle">
                <div class="botones ">
                    <div class="row ">
                        <p class="col-md-2">INICIO</p>
    
                        <p class="col-md-2">CENTRO</p>
    
                        <p class="col-md-2" >AL DIA </p>
    
                        <p class="col-md-2">INICIO</p>
    
                        <p class="col-md-2">INICIO</p>
                        <div class="col-md-2">
                            <button class="btn btn-primary" type="button" data-bs-toggle="offcanvas" data-bs-target="#demo">
                                <i class="fa-solid fa-bars"></i>
                              </button>

                        </div>
                        

                        <div class="offcanvas offcanvas-end f-flex flex-direction colum" id="demo">
                            <div class="offcanvas-header">
                              <h1 class="offcanvas-title">Search</h1>
                              <button type="button" class="btn-close" data-bs-dismiss="offcanvas"></button>
                              <div>
                                <input name="searchword" id="mod-search-searchword" maxlength="200" class="inputbox search-query" type="text" size="20" placeholder="Search ...">
                              </div>
                            </div>
                            <div class="offcanvas-body">
                              <ul>
                                <li>Inicio </li>
                                <li>Al dia  </li>
                                <li>El loro </li>
                                <li>El centro </li>
                                <li>Secretaria </li>
                                <li>familias </li>
                                <li>Bolsa </li>

                              </ul>
                              

                              <button class="btn btn-secondary justify-content" type="button">A Button</button>
                            </div>
                          </div>
                          
                          <div class="container-fluid mt-3">
                           
                            
                            
                        </div>
                    </div>
                </div>
            </div>
        </div>
     

        
    </div>
    
</main>

<style lang="sass">

    img
       width: 15rem
       height: 5rem
       padding-left: 3rem
       padding-top: 3rem
       vertical-align: middle
    .botones 
        padding-top: 3rem
        margin-bottom: 0rem
    @media only screen and (max-width: 768px) 
        .botones
            display: none

    
    .btn 
        color: black
        background-color: transparent
        border-color: transparent
        padding-bottom: 1rem
        font: normal normal normal 14px/1 FontAwesome
    .offcanvas
        background-color: gray
    .offcanvas
        li,h1
            color: white
            font-family: Arial, Helvetica, sans-serif
   
    
       
        
    


</style>
