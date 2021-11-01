<template>
  <header>
    <nav>
      <div>
      <h1>Mentor Search</h1>
      </div>
      <div class="btn-container">
      <button class="btn-header">Mentores</button>
      <button class="btn-header">Alunos</button>
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

h1 {
  color: #8257e7;
}

nav {
  display: flex;
  justify-content: space-between;
  width: 100%;
  padding: 20px;
}

.btn-header {
  border: 2px solid #8257e7;
  background: #8257e7;
  color: #fff;
  border-radius: 12px;
  padding: 10px;
  cursor: pointer;
  font-weight: bold;
}

.btn-header:hover {
  border: 2px solid #6f39ee;
  background: #6f39ee;
  color: #fff;
}

.btn-container {
  display: flex;
  justify-content: space-between;
  width: 160px;
}
</style>
