<template>
  <div>
    <h1>About Page</h1>
    <p>Esta es la página about page.</p>
    <router-link class="btn" to="/">Ir a Home</router-link>
  </div>
</template>

<script>
export default {
  name: 'About',
};
</script>

<style scoped>
.page {
  background: var(--color-light);
  padding: 2rem;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

.btn {
  display: inline-block;
  background: var(--color-primary);
  color: var(--color-light);
  padding: 10px 15px;
  border-radius: 6px;
  text-decoration: none;
  margin-top: 1rem;
  transition: background 0.3s;
}

.btn:hover {
  background: #1b781fff; /* Verde más oscuro */
}
</style>