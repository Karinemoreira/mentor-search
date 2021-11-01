<template>
  <div class='search-container'> 
    <input type="text" name="query" placeholder="Buscar" />
    <button class="btn-search">Busca</button>
  </div>
</template>

<script>
  export default {
    name: "SearchBar",
  };
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.search-container {
  margin: 20px;
}

input {
  border: none;
  border: 2px solid #8257e7;
  color: black;
  padding: 10px;
  font-weight: bold;
  outline: 0
}

.btn-search {
  border: 2px solid #8257e7;
  background: #8257e7;
  color: #fff;
/*   border-radius: 12px; */
  padding: 10px;
  cursor: pointer;
  font-weight: bold;
}

.btn-search:hover {
  border: 2px solid #6f39ee;
  background: #6f39ee;
  color: #fff;
}
</style>
