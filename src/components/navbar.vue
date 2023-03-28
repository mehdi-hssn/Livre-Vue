<template>
    <div>
        <nav class="navbar navbar-expand-md navbar-dark fixed-top bg-dark">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">Librairie M</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarCollapse"
          aria-controls="navbarCollapse" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarCollapse">
          <ul class="navbar-nav mr-auto mb-2 mb-md-0">
            <li class="nav-item active">
              <a class="nav-link" aria-current="page" href="#">Accueil</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"><RouterLink to="/card"> livres</RouterLink></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Commandes</a>
            </li>
          </ul>

          <form class="d-flex">
            <input class="form-control mr-2" type="search" placeholder="Livre/catégorie" aria-label="Search">
            <button class="btn btn-outline-success" type="submit">Rechercher</button>
          </form>
        </div>
      </div>
    </nav>
    </div>
</template>

<script>
 export default {
    name: "navbar"
 }
</script>

<style scoped>
#bodyApp{
  padding: 0px;
}
.navbar .container-fluid .collapse .navbar-nav .nav-item .nav-link a{
 text-decoration: none;
 color: white;
}
</style>
