<template>
  <div class="container">
    <AppHeader />
    <nuxt />
  </div>
</template>

<script>
import AppHeader from "../components/AppHeader";
export default {
  components:{
    AppHeader
  }
}
</script>

<style>


*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

a{
  color: #666;
  text-decoration: none;
}

ul{
  list-style: none;
}

.container{
  max-width: 800px;
  margin: 2rem auto;
  overflow: hidden;
  padding: 1rem 2rem;
  background: #ffff;
}
</style>
