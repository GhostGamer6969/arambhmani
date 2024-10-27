<script lang="ts">
  import { page } from "$app/stores";
</script>

<header>
  <nav class="navbar">
    <div class="nav-links">
      <li
        class="noBullet"
        aria-current={$page.url.pathname === "/" ? "page" : undefined}
      >
        <a href="/"><strong>Home</strong></a>
      </li>
      <li
        class="noBullet"
        aria-current={$page.url.pathname === "/projects" ? "page" : undefined}
      >
        <a href="/projects"><strong>Projects</strong></a>
      </li>
      <li
        class="noBullet"
        aria-current={$page.url.pathname === "/blog" ? "page" : undefined}
      >
        <a href="/blog"><strong>Blog</strong></a>
      </li>
    </div>
  </nav>
</header>

<style>
  .navbar {
    background-color: transparent;
    padding: 20px 0;
    display: flex;
    justify-content: center; /* Center the navigation items */
    align-items: center;
    max-width: 900px;
    margin: 0 auto;
  }

  .noBullet {
    list-style-type: none;
  }

  .nav-links {
    display: flex;
    flex-wrap: nowrap; /* Ensure items stay in a single line */
  }

  .nav-links a {
    color: #e0e0e0;
    text-decoration: none;
    margin: 0 15px;
    font-size: 1.2em;
    font-weight: 500;
  }

  .nav-links a:hover {
    color: #ffffff;
    text-shadow: 0 0 8px rgba(255, 255, 255, 0.8);
  }

  /* Media query for small screens */
  @media (max-width: 768px) {
    .nav-links a {
      margin: 0 10px;
      font-size: 1.1em;
    }
  }

  /* Media query for phones */
  @media (max-width: 480px) {
    .navbar {
      flex-direction: column; /* Stack items vertically */
      align-items: center; /* Center items */
    }

    .nav-links {
      display: flex;
      justify-content: center; /* Center navigation links */
      width: 100%; /* Ensure it spans the full width */
    }

    .nav-links a {
      margin: 0 5px;
      font-size: 1em;
    }
  }
</style>
