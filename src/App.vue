<template>
  <div id="app">
    <header>
      <h3>/louishouston.github.io/my-web-portfolio/</h3>
    </header>
    <main>
      <section id="about">
        <h2>About Me</h2>
        <p>Welcome to my portfolio!</p>
      </section>
      <section id="projects">
        <h2>Projects</h2>
        <ul>
          <li>Project 1</li>
          <li>Projecft 2</li>
        </ul>
      </section>
    </main>
  </div>
</template>

<script>
export default {
  name: 'App',
};
</script>

<style>
#app {
  font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
  text-align: center;

}

body{ 
  background-color: #6188de;
}

h3 {
  color: #a3a6b5;
}
</style>