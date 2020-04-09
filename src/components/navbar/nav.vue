<template>
  <div class="nav">
      <ul class="menu-items">
          <li id="logo-link">
              <img src="../../assets/portfolio.png" alt="" id="logo">
          </li>
          <li id="title-link">
            <span id="title">Alex<span id="title-end">.dev</span></span>
          </li>
      </ul>
  </div>
</template>

<script>
export default {
  name: 'Navbar'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    .nav {
        position: fixed;
        color: #1a1a1d;
        width: 100%;
        height: 3rem;
        background-color: #fcfcfc;
        border-bottom: 1px solid #924BD8;
        z-index: 999;
    }

    #logo-link {
        display: flex;
        align-items: center;
        height: 100%;
        margin-right: 1rem;
    }

    #title-link {
        display: flex;
        align-items: center;
        height: 100%;
    }

    #logo {
        width: 2.2rem;
    }

    .menu-items {
        margin: 0;
        height: 100%;
        display: flex;
        align-items: center;
        list-style: none;
    }

    #title {
        font-weight: 400;
        font-size: 1.5rem;
    }

    #title-end {
        color: #924BD8;
    }
</style>
