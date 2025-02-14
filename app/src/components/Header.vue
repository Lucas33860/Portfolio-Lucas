<template>
  <header>
    <h1>Mon Portfolio</h1>
    <nav>
      <ul>
        <li><a href="#about">À propos</a></li>
        <li><a href="#projects">Projets</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: "AppHeader.vue",
};
</script>

<style scoped>
header {
  background-color: #333;
  color: white;
  padding: 1rem;
  text-align: center;
}
nav ul {
  display: flex;
  justify-content: center;
  gap: 1rem;
}
nav ul li {
  list-style: none;
}
nav ul li a {
  color: white;
  text-decoration: none;
}
</style>
