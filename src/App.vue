<template>
  <div id="app">
    <header>
      <h3>louishouston.github.io</h3>
    </header>
    <main class="content">
      <section id="about">
        <h2>Louis Houston</h2>
        <h4>Software Engineer</h4>

        <p id="about-body">Hello, my name is Louis Houston.<br> While I'm early in my career, I am dedicated to learning and
          growing through personal projects.</p>
          <h5><a href="https://x.com/LouisRAHouston" target="_blank">X</a> | <a href="https://github.com/LouisHouston"
            target="_blank">Github</a> | <a href="https://www.linkedin.com/in/louisrahouston/" target="_blank">LinkedIn</a> </h5>
      </section>


      <section id="projects-container">
        <h2></h2>

        <a href="https://youtu.be/o3_EqOKpjfw" target="_blank" class="project-link">
        <div class="project-box">
            <div class="project-header">
                <img src="../public/bingoProjectLogo.png" class="project-icon" alt="Bingo Game Icon">
                <h3 class="project-title">Multiplayer Bingo</h3>
            </div>
            <img src="../public/bingoProjectWebsite.png" class="project-image" alt="Screenshot of login page of Bingo Game">
            <p class="project-description">A real-time multiplayer bingo game with live chat, secure login, and instant game updates. Uses WebSockets for real-time gameplay, bcrypt encryption for authentication, and honeypotting to block bots. Includes separate lobby & global chat for an interactive social experience.</p>
        </div>
        </a>
        
        <a href="https://youtu.be/suC9moqP8Hc" target="_blank" class="project-link">
        <div class="project-box">
            <div class="project-header">
                <img src="../public/youtube-likLogo.png" class="project-icon" alt="YouTube-Like Icon">
                <h3 class="project-title">Youtube-Like</h3>
            </div>
            <img src="../public/youtube-likeWebsite.png" class="project-image" alt="Picture of database and next to video playing">
            <p class="project-description">YouTube-like video-sharing platform with secure authentication and optimized storage. Uses SQL, JavaScript, and EJS to manage users and store videos as blobs, while bcrypt encryption ensures secure login. Designed for scalability and efficiency, this project demonstrates full-stack development, database management, and authentication best practices.</p></div>
        </a>


        <a href="https://github.com/LouisHouston/ProjectOlympia" target="_blank" class="project-link">
          <div class="project-box">
            <div class="project-header">
                <img src="../public/ProjectOlympiaLogo.png" class="project-icon" alt="Project Olympia logo used">
                <h3 class="project-title">Project Olympia</h3>
            </div>
            <img src="../public/ProjectOlympia.png" class="project-image" alt="ProjectOlympia Login Page">
            <p class="project-description">This Paralympic athlete research tool lets users search for athlete stats using a SQL database and a built-in search feature. It uses the Google API for tracking views, clicks, and university geolocation. The project was previously deployed on AWS and offers an interactive way to explore Paralympic data.</p>
        </div>
        </a>

        <a href="https://youtu.be/4WSXSQeF9A4" target="_blank" class="project-link">
          <div class="project-box">
            <div class="project-header">
                <img src="../public/CamBoard.png" class="project-icon" alt="YouTube-Like Icon">
                <h3 class="project-title">CamBoard</h3>
            </div>
            <img src="../public/CamBoard.png" class="project-image" alt="Screenshot of a user commenting on a video">
            <p class="project-description">A facial expression recognition system using OpenCV and machine learning, which triggers audio responses based on detected emotions, providing an interactive and dynamic user experience.</p>
        </div>
        </a>

        
        <a href="" target="_blank" class="project-link">
          <div class="project-box empty-box">
            <div class="project-header">
                <h3 class="project-title"></h3>
            </div>
            <p class="project-description"></p>
        </div>
        </a>

        <a href="" target="_blank" class="project-link">
          <div class="project-box empty-box">
            <div class="project-header">
                <h3 class="project-title"></h3>
            </div>
            <p class="project-description"></p>
        </div>
        </a>
      
        


      </section>


      <section id="Experience">
        <h2>Experience</h2>
        <h4>Qualtrics - Software Apprentice</h4>
        <p id="experience-desc"> Actively participated in coding teams, collaborating with a group of mentors, who assigned and supervised tasks related to mock-up web application development and tracking user interaction and data collection
<br> Participated in technical interview training and completed hands-on coding challenges under the guidance and assistance of a mentor.
 </p>
      </section>
    </main>
    <footer>
      <p>©2025 louis ra houston </p>
    </footer>
  </div>
</template>
/* ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ */
/* ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ */
/* ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ */
/* ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ */
/* ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ */
/* ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ */
<script>
export default {
  name: 'App',
};
</script>

<style>
html,
body {
  height: 100%;
  margin: 0;
}

body {
  display: flex;
  flex-direction: column;
  background-color: #E9F5F3;
  text-shadow: #616474;
  padding-top: 0.005rem;
  padding-bottom: 0.005rem;
  height: 100%;
}

#app {
  font-family: 'Helvetica', sans-serif;
  text-align: center;
  font-size: min(4vw, 2rem);
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  flex: 1;
}

a {
  color: #616474;
  
}

h5 {
  font-size: 1rem;
}

#about {
  border: rgb(64, 64, 64) 1px solid;
  border-radius: 0.4rem;
  margin-top: 2vw;
  padding: 0;
  display: grid;
  max-width: 600px;
  width: 95%;
  word-wrap: break-word;
  box-sizing: border-box;
}

#about-body {
  font-size: 1.2rem;
  margin-left: 1.3rem;
  margin-right: 1.3rem;
}

.content {
  flex: 1;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 0;
}

footer {
  color: rgb(179, 179, 179);
  text-align: center;
  padding: 0.98%;
  font-size: .92rem;
}

h3 {
  color: #618a83;
  font-size: min(4vw,.92rem);
}

h4 {
  color: #2e303a;
}

#salute {
  font-size: 2rem;
}

#projects-container h2 {
  text-align: center;
  width: 100%;
  margin-bottom: 20px;
  justify-content: center;
}

.project-box {
  flex: 1 1 30%;
  min-width: 350px;
    min-height: 100%;
  background-color: #e5eee5;
  border: rgb(64, 64, 64) 1px solid;
  color: rgb(143, 9, 9);
  padding: 1%;
  text-align: center;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  display: flex;
  flex-direction: column;
  align-items: center;
}

#projects-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
  max-width: 1200px;
  width: 90%;
  margin: 0 auto;
}

.project-header {
    display: flex;
    align-items: center; 
    justify-content: center; 
    gap: 10px; 
    font-size: min(4vw, 2rem);

}

.project-icon {
    width: 24px; 
    height: 24px;
    border-radius: 8px;
}

.project-title {
    font-size: 1.5rem;
    font-weight: bold;
    margin: 0; 
}

.project-image {
    width: 90%;
    aspect-ratio: 16 / 9;
    max-height: 200px;
    object-fit: cover;
    border-radius: 3px;
    margin-top: 1rem;
    margin-left: 1%;
    margin-bottom:1.43%;
}

@media (hover: hover) {
  .project-link:hover .project-box {
    transform: scale(1.05);
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
    text-decoration: none;
  }
}

.project-link {
    text-decoration: none;
    color: inherit; 
    display: inline-block; 
    flex: 1 1 30%;
    
}

.project-description {
  font-size: 1rem;
  margin-top: 3%;
  padding: 0 3%;
  text-align: center;
}

.empty-box {
  opacity: 0; 
  pointer-events: none;
}


@media (max-width: 768px) {
  .project-box {
    flex: 1 1 45%;
  }
}

@media (max-width: 480px) {
  .project-box {
    flex: 1 1 100%;
  }
}

#experience-desc {
  font-size: 1.43rem;
  margin-left: 1.3rem;
  margin-right: 1.3rem;
}
</style>