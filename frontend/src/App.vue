<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <!-- <header>


    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="You did it!" />
    </div>
  </header>

  <main>
    <TheWelcome />
  </main> -->
  
  <div class="fila">
    <div class="ficha primeira"><p>VC001</p><p>Guichê 02</p></div>
    <div class="ficha">VC002<p>Guichê 02</p></div>
    <div class="ficha">VC003<p>Guichê 04</p></div>
    <div class="ficha">VC004<p>Guichê 08</p></div>
    <div class="ficha">VC005<p>Guichê 06</p></div>
    <div class="ficha">VC006<p>Guichê 01</p></div>
  </div>

  <div class="tv">
    TV
  </div>

</template>

<style scoped>

.ficha {
  background-color: rgb(41, 41, 41);
  height: 260px;
  width: 210px;
  padding: 8px;
  margin: 5px;
  border-radius: 2px;
  box-shadow: 2px 2px rgb(17, 17, 17);
}

.tv {
  background-color: rgb(41, 41, 41);
  height: 420px;
  width: 780px;
  padding: 8px;
  margin: 5px;
  border-radius: 2px;
  box-shadow: 2px 2px rgb(17, 17, 17);
}


header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
