<template>
  <div class="home">
    <h1 id="main-title">Welcome to my <span id="portfolio">Portfolio</span></h1>
  </div>
</template>

<script>
export default {
  name: 'Home'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.home {
  margin: auto;
  height: 100%;
  width: 50vw;
}

#main-title {
  font-weight: 400;
}

#portfolio {
  font-weight: 300;
  color: #924BD8;
}

</style>
