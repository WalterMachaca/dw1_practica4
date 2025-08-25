<template>
  <div>
    <h1>Home Page</h1>
    <p>Bienvenido a la página principal home page!</p>
    <router-link class="btn" to="/about">Ir a About</router-link>
  </div>
</template>

<script>
export default {
  name: 'Home',
};
</script>

<style scoped>
.page {
  background: var(--color-light);
  padding: 2rem;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(243, 246, 245, 0.1);
}

.btn {
  display: inline-block;
  background: var(--color-secondary);
  color: var(--color-light);
  padding: 10px 15px;
  border-radius: 6px;
  text-decoration: none;
  margin-top: 1rem;
  transition: background 0.3s;
}

.btn:hover {
  background: #38c68fff; 
}
</style>