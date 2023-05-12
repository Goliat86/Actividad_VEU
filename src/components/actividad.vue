<template>
    <div>
        <div class="container">
            <div class="row">
                <div class="col-12 col-sm-12 col-md-12 col-lg-12 col-xl-12 ">

        <nav class="navbar navbar-expand-lg navbar-light " style="background: #5897fb !important;">
            <div class="container-fluid">
                <form class="d-flex">
                    
                        <input class="form-control me-2" type="search" placeholder="Busca por cargo, salario, ubicación o empresa" aria-label="Search">
                        <svg xmlns="http://www.w3.org/2000/svg" class="input-icon" fill="none" viewBox="0 0 24 24" strokeWidth={1.5} stroke="currentColor" className="w-6 h-6">
                        <path strokeLinecap="round" strokeLinejoin="round" d="M21 21l-5.197-5.197m0 0A7.5 7.5 0 105.196 5.196a7.5 7.5 0 0010.607 10.607z" />
                        </svg>
                </form>
                
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                    data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false"
                    aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarSupportedContent" >
                    <ul class="navbar-nav me-auto mb-2 mb-lg-0 " >
                        
                        <li class="nav-item dropdown" style="margin-left: 8rem;">
                            <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown">
                                Area
                            </a>
                            
                                
                            
                        </li>

                        <li class="nav-item dropdown" >
                            <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" >
                                Cargo
                            </a>
                            
                                
                            
                        </li > 
                        
                        <li class="nav-item dropdown" >
                            <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" >
                                Salario
                            </a>
                            
                                
                            
                        </li>
                        
                        <li class="nav-item dropdown" >
                            <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" >
                                Ubicación
                            </a>
                            
                                
                            
                        </li>
                        
                    </ul>
                    
                </div>
        </div>
    </nav>
</div>
</div>
</div>
</div>
</template>

<script >
export default {
    name: 'actividadPeaku',
    props: {
        msg: String
    },
    data(){
        return{
            texto: "Hola soy Omar"
        }
    }
}
</script>

<style>
.d-flex{
    
    position: relative;
    margin-left: 5rem;
    padding-right: 3rem;
}

.form-control{
    padding-left: 3rem !important;
    margin-top: 1rem !important;
    margin-bottom: 1rem !important;
    border-radius: 5px;
    width: 30rem !important;
    
}
.input-icon {
   color: #191919;
   position: absolute;
   width: 20px;
   height: 20px;
   left: 12px;
   top: 50%;
   transform: translateY(-50%);
   
  
}

.nav-link{
    
    color: white !important;
    border-radius: 15px;
    border: solid 1px white;
    padding: .2rem !important;
    margin: .1rem;
}

.nav-item{
    padding-right: .8rem;
    
}
</style>