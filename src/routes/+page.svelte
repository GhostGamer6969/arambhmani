<div class="page-container">
  <div class="home-container">
    <h1 class="greeting">Ahoy there 👋</h1>
    <p class="intro">
      Hey, I’m Arambh Mani, your resident blockchain adventurer! I juggle
      fintech projects, dive into blockchain mysteries, and occasionally
      convince myself that I know what I'm doing. Right now, my passion project
      is Celeriz—think of it as global payments without the paperwork maze or
      the headache. I bounce between Berlin and Delhi because, really, why limit
      myself to one timezone of chaos?
    </p>

    <p class="intro">
      When I’m not neck-deep in tech wizardry, you’ll find me geeking out over
      crypto, teaching my laptop to do new tricks (aka coding), or trying to
      explain to my friends why blockchain isn’t just for buying pizza with
      Bitcoin. These days, I’m on a mission to make sending money across borders
      as easy as sending a text—less drama over fees, more “ding!” and your cash
      is on its way!
    </p>

    <section class="projects-preview">
      <h2>Featured Projects</h2>
      <div class="projects-list">
        <div class="project-card">
          <h3>CeleriZ</h3>
          <p>
            A global payment app simplifying cross-border transactions with
            Stellar Blockchain.
          </p>
          <a href="/projects">View More</a>
        </div>
        <div class="project-card">
          <h3>DDos Protection Tool</h3>
          <p>
            Developed a tool that can detect and block DDoS attacks, ensuring
            your web server is protected from DDos.
          </p>
          <a href="/projects">View More</a>
        </div>
      </div>
    </section>

    <section class="blogs-preview">
      <h2>Recent Blogs</h2>
      <div class="blogs-list">
        <div class="blog-card">
          <h3>Why I am building CeleriZ</h3>
          <p>How blockchain can simplify cross-border payments.</p>
          <a href="/blog">Read More</a>
        </div>
        <div class="blog-card">
          <h3>How Web3 is Changing Finance</h3>
          <p>
            An exploration of decentralized finance and its impact on fintech.
          </p>
          <a href="/blog">Read More</a>
        </div>
      </div>
    </section>
  </div>
</div>

<style>
  .home-container {
    background-color: #121212;
    color: #e0e0e0;
    max-width: 900px;
    /* margin: 40px auto; */
    text-align: left;
  }

  /* Center the entire white box */
  .page-container {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh; /* Full viewport height */
    background-color: #f4f4f4; /* Light grey background */
  }

  .greeting {
    font-size: 3.2em;
    color: #ffffff;
    margin-bottom: 20px;
  }

  .intro {
    font-size: 1.4em;
    color: #e0e0e0;
    line-height: 1.8;
    margin-bottom: 40px;
  }

  /* Projects Section */
  .projects-preview,
  .blogs-preview {
    margin-top: 50px;
  }

  .projects-preview h2,
  .blogs-preview h2 {
    font-size: 2em;
    color: #ffffff;
    margin-bottom: 30px;
  }

  .projects-list,
  .blogs-list {
    display: flex;
    gap: 20px;
  }

  .project-card,
  .blog-card {
    background-color: #1e1e1e;
    color: #e0e0e0;
    border-radius: 10px;
    padding: 20px;
    max-width: 300px;
    text-align: left;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
  }

  .project-card h3,
  .blog-card h3 {
    font-size: 1.5em;
    color: #e0e0e0;
  }

  .project-card p,
  .blog-card p {
    font-size: 1.1em;
    color: #555;
    margin-bottom: 15px;
  }

  .project-card a,
  .blog-card a {
    text-decoration: none;
    color: #007bff;
    font-weight: 500;
  }

  .project-card a:hover,
  .blog-card a:hover {
    color: #0056b3;
  }

  /* Social Links */
  .social-links {
    margin-top: 50px;
  }

  .social-links a {
    margin: 0 15px;
    text-decoration: none;
    color: #333;
    font-size: 1.3em;
  }

  .social-links a:hover {
    color: #007bff;
  }

  /* Responsive Styles */
  @media (max-width: 768px) {
    .projects-list,
    .blogs-list {
      flex-direction: column;
    }

    .project-card,
    .blog-card {
      max-width: 100%;
      margin-bottom: 20px;
    }

    .greeting {
      font-size: 2.5em;
    }

    .intro {
      font-size: 1.3em;
    }

    /* Add padding for mobile view */
    .home-container {
      padding: 20px; /* Add padding on mobile */
    }

    .project-card,
    .blog-card {
      padding: 15px; /* Slightly reduce padding on smaller screens */
    }
  }
</style>
