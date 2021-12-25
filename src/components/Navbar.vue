
<template>
  <div id="nav">
  <nav class="container navbar navbar-expand-lg navbar-light bg-light">
    <a class="navbar-brand" href="#">
        <img src="../assets/pp.jpeg" alt="" style="height:30px; width:30px;">
    </a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <div class="navbar-nav mr-auto">
            <router-link to="/" class="nav-item nav-link">Home</router-link>
            <router-link to="/about" class="nav-item nav-link">About</router-link>
            <router-link to="/services" class="nav-link">Services</router-link>
            <router-link to="/contact" class="nav-link">Contact</router-link>
        </div>
        
    </div>
</nav>
 </div>
  <router-view/>
</template>



<style scoped>
    
    nav{
    
    display: flex;
    justify-content: space-between;
    }
    #nav a {
    font-weight: bold;
    color: black;
    }

    #nav a.router-link-exact-active {
    color: black;
    background: crimson;
    border-radius: .5rem;
}
</style>
