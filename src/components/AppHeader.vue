<template>
    <header>
    <img alt="Vue Logo" src="../assets/logo.png" height="50" />
    <p> My Vuejs App</p>
    <nav>
    <ul>
    <li><router-link to="/">Home</router-link></li>
    <li><router-link to="about">About</router-link></li>
    <li><router-link to="projects">Projects</router-link></li>

    </ul>
    </nav>
    </header>
</template>

<style lang="scss">
  header {
    display: flex;
    border-bottom: 1px solid #ccc;
    padding: .5rem 1rem;

    p {
      margin-left: 1rem;
    }
  }

  nav {
    margin-left: auto;

    ul {
      list-style: none;
    }

    ul li {
      display: inline-flex;
      margin-left: 1rem;
    }
  }
</style>
