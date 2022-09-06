<template>
  <nav class="navbar bg-green navbar-expand-lg navbar-light">
    <div class="container-fluid">
          <a class="navbar-brand"><img class = "cimg" src = "../assets/ctmac.png" ></a>
          <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse position" id="navbarNavDropdown">
          <ul class="navbar-nav">
            <li class="nav-item active">
              <a class="nav-link" href="/">Home <span class="sr-only"></span></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="/#cardapio">Alterar dados</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="/peçaonline">Conta</a>
            </li>
    
          </ul>
        </div>
    </div>
  </nav>

</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #ffffff;
}
</style>
