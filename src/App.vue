<template>
  <div id="app">
    <img src="./assets/logo.svg" class="logo" />
    
    <nav class="menu">
      <a href="#info" class="menu__link color--three">Min filosofi</a>
      <a href="#pricing" class="menu__link color--two">Priser</a>
      <a href="#contact" class="menu__link color--one">Kontakt</a>
    </nav>



    <section class="section color--three" id="info">
      <h2 class="section__heading">Min filosofi</h2>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
        quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
        consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
        cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
        proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
      </p>
    </section>

    <section class="section color--two" id="pricing">
      <h2 class="section__heading">Priser</h2>
      <p>Första träffen är gratis!!!</p>
      <p>1 träff 500 kr</p>
      <p>5 träffar 2000 kr</p>
      <p>10 träffar 3000 kr</p>
    </section>

    <section class="section color--one" id="contact">
      <h2 class="section__heading">Kontakt</h2>
      
      <a href="workout@joyful.se">workout@joyful.se</a>
      
    </section>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>

body {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  margin: 0;
  min-width: 18rem;
}

html {
  font-size: 18px;
}
@media (min-width: 44rem) {
  html {
    font-size: 20px;
    margin: 0 2rem;
  }
}

a {
  color: #fff;
}

.logo {
  width: 100%;
  display: block;
  padding: 3rem;
  box-sizing: border-box;
  max-width: 500px;
  margin: 0 auto;
}

.menu {
  display: flex;
}
.menu__link {
  padding: 1rem 0.5rem;
  text-decoration: none;
  background-color: hsl(300, 35%, 86%);
  flex: 1 1 auto;
  color: black;
  text-align: center;
  white-space: nowrap;
}
.menu__link:hover {
  background-color: hsl(300, 35%, 56%);
}
@media (min-width: 44rem) {
  .menu__link {
    margin: 0.5rem;
    border-radius: 0.4rem;
    flex: 0 0 auto;
    padding: 1rem 2rem;
    font-size: 1.2rem;
  }
  .menu {
    justify-content: center;
    margin-bottom: 1rem;
  }
}



.section {
  padding: 2rem;
  max-width: 40rem;
  margin: 0 auto;
}
@media (min-width: 44rem) {
  .section {
    margin-bottom: 2rem;
    border-radius: 0.4rem;
  }
}

.color--one {
  background-color: hsl(300, 35%, 66%);
  color: white;
}
.color--two {
  background-color: hsl(300, 35%, 56%);
  color: white;
}
.color--three {
  background-color: hsl(300, 35%, 46%);
  color: white;
}

.section__heading {
  margin-top: 0;
  text-align: center;
}

</style>
