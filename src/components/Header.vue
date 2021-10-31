<template>
  <header>
    <nav>
      <div>
      <h1>Mentor Search</h1>
      </div>
      <div>
      <button>Mentores</button>
      <button>Alunos</button>
      </div>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'Header',
}
</script>

<style scoped>
header {
    width: 100%;
    height: 80px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    box-shadow: 0px 2px 4px rgba(30, 60,90, 0.1);
}

nav {
  display: flex;
  justify-content: space-between;
  width: 100%;
  padding: 20px;
}
</style>
