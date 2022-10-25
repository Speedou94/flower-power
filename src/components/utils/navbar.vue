<template>
  <nav class="navbar" role="navigation" aria-label="main navigation">
    <div class="navbar-brand">
      <button class="button">Se connecter</button>
      <button class="button">S'inscrire</button>
      <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
      </a>
    </div>


    <div class="navbar-end">
      <div class="navbar-item">
        <button class="button">Eshop</button>
      </div>
    </div>

  </nav>
</template>

<script>
export default {
  name: "navbar"
};
</script>

<style scoped>
.navbar {
  display: flex;
  flex-direction: row-reverse;
  align-items: flex-end;
  background: linear-gradient(violet, yellow);
}

.button {
  margin: 3px;
}


</style>