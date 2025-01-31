<template>
  <div id="app">
    <header>
      <h3>louishouston.github.io</h3>
    </header>
    <main>
      <section id="about">
        <h2>About Me</h2>
        <h5><a href="https://x.com/LouisRAHouston/"> X </a>  | Github | LinkedIn </h5>
        <p>Hello, my name is Louis Houston. I am currently an aspiring full-stack software engineer. Although what I lack in experience I make up for in personal curiousity, motivation and projects. Thank you for taking the time to look over my portfolio!</p>
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
  font-family: 'Helvetica', sans-serif;
  text-align: center;
  font-size: min(4vw, 2rem); 
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  height: 20%;
}

a {
  color: #616474;
}

h5 {
  font-size: 1rem;
}

#about {
  border: rgb(64, 64, 64) .143rem solid;
  border-radius: .4rem;
  margin-top: 3vw;
  padding: 1rem;
  display: grid;
  max-width: 600px;
  width: 100%;
  word-wrap: break-word;
  box-sizing: border-box;
}




body{ 
  background-color: #E9F5F3;
  text-shadow: #616474;
  padding-top:.005rem;
  padding-bottom: .005rem;
}


h3 {
  color: #616474;
}
</style>