<template>
  <Header />
  <main>
      <router-view />
  </main>
  <Footer />
</template>

<script>
  import Header from "./components/Header.vue";
    import Footer from "./components/Footer.vue";


  export default {
    name: "App",
    components: {
      Header, Footer
    },
  };
</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+Mono:wght@300;400;700&display=swap');
    * {
      padding: 0;
      margin: 0;
    }

    #app {
      font-family: 'Noto Sans Mono', sans-serif;
      font-weight: normal;
      display: flex;
      flex-direction: column;
      min-height: 100vh;
      text-align: center;
    }

    main {
      flex: 1;
    }
</style>
