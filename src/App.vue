<script setup>
// import HelloWorld from './components/HelloWorld.vue'
// import TheWelcome from './components/TheWelcome.vue'
import mynev from './components/MyNev.vue'
import mycard from './components/mycard.vue'
import mytest from './components/test.json'
</script>

<template>
  <!-- <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="You did it!" />
    </div>
  </header> -->

  <main>
    <mynev /> 
    <div className="grid-container">
    <mycard v-bind="mytest[0] "/>
    <mycard v-bind="mytest[1] "/>
    <mycard v-bind="mytest[2] "/>
    <mycard v-bind="mytest[3] "/>
    <mycard v-bind="mytest[4] "/>
    <mycard v-bind="mytest[5] "/>
    <mycard v-bind="mytest[6] "/>
    <mycard v-bind="mytest[7] "/>
    <mycard v-bind="mytest[8] "/>
    <mycard v-bind="mytest[9] "/>
    <mycard v-bind="mytest[10] "/>
    <mycard v-bind="mytest[11] "/>
 

  </div>
  </main>
  
  


</template>

<style scoped>
body {
  background-color: aqua;
}
/* header {
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
} */
</style>
