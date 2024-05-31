<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Shohara Afrin Bika - Web Developer</title>
  <link rel="stylesheet" href="style.css"> </head>
<body>
  <header class="intro">
    <h1>Hi , I'm Shohara Afrin Bika</h1>
    <h3>A passionate Web Developer from Bangladesh</h3>
  </header>
  <main class="about-me">
    <p>I'm a programmer with experience in languages like C++, C#, Java, and JavaScript. I'm also familiar with frameworks like React and ASP.NET, and databases like MSSQL. I've built APIs using RESTful principles.  In addition to my professional skills, I'm passionate about competitive programming and have created personal projects using these technologies to keep my skills sharp!</p>
    <h3>Languages and Tools:</h3>
    <ul class="skills">
      <li><a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/></a></li>
      <li><a href="https://www.w3schools.com/cs/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="csharp" width="40" height="40"/></a></li>
      <li><a href="https://reactjs.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/></a></li>
    </ul>
  </main>
  <aside class="stats">
    <img src="https://github-readme-stats.vercel.app/api?username=BikaAfrin&theme=catppuccin_latte&show_icons=true" alt="Bika's GitHub stats">
    <a href="https://github.com/anuraghazra/github-readme-stats" target="_blank" rel="noreferrer">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=BikaAfrin&layout=compact" alt="Top Languages">
    </a>
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=bikaafrin&" alt="bikaafrin">
  </aside>
</body>
</html>

body {
  font-family: sans-serif;
  margin: 0;
  padding: 2rem;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.intro {
  text-align: center;
  margin-bottom: 2rem;
}

h1 {
  font-size: 2rem;
  margin-bottom: 0.5rem;
}

h3 {
  font-size: 1.2rem;
  color: #888;
}

.about-me p {
  line-height: 1.5;
  margin-bottom: 1rem;
}

.skills {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  list-style: none;
  margin: 0;
  padding: 0;
}

.skills li {
  margin: 0.5rem;
}

.stats img {
  width: 100%;
  margin-bottom: 1rem;
}

@media (min-width: 768px) {
  .main, .stats {
    flex: 1;
  }
  .stats {
    margin-left: 2rem;
  }
