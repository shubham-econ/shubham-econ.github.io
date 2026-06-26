---
title: Home
---

<style>
  @import url('https://fonts.googleapis.com/css2?family=EB+Garamond:ital,wght@0,400;0,500;1,400&family=Inter:wght@400;500&display=swap');

  .home-root {
    font-family: 'Inter', sans-serif;
    max-width: 680px;
    padding: 3rem 0 4rem;
  }

  .home-top {
    display: flex;
    gap: 2.5rem;
    align-items: flex-start;
    margin-bottom: 3.5rem;
  }

  .home-img-wrap {
    flex-shrink: 0;
  }

  .home-img {
    width: 108px;
    height: 108px;
    border-radius: 50%;
    object-fit: cover;
    display: block;
    border: 1px solid #e0e0e0;
  }

  .home-img-fallback {
    width: 108px;
    height: 108px;
    border-radius: 50%;
    background: #e8f0fb;
    display: none;
    align-items: center;
    justify-content: center;
    font-family: 'EB Garamond', serif;
    font-size: 32px;
    color: #2a5cbf;
    border: 1px solid #b5d4f4;
  }

  .home-identity {
    padding-top: 0.25rem;
  }

  .home-name {
    font-family: 'EB Garamond', serif;
    font-size: 32px;
    font-weight: 500;
    line-height: 1.15;
    margin: 0 0 0.4rem;
    letter-spacing: -0.3px;
  }

  .home-role {
    font-size: 14px;
    color: #555;
    margin: 0 0 0.2rem;
    line-height: 1.5;
  }

  .home-edu {
    font-size: 13px;
    color: #888;
    margin: 0;
    line-height: 1.5;
  }

  .home-divider {
    border: none;
    border-top: 1px solid #e8e8e8;
    margin: 0 0 2.5rem;
  }

  .home-bio {
    margin-bottom: 2.5rem;
  }

  .home-bio p {
    font-family: 'EB Garamond', serif;
    font-size: 19px;
    line-height: 1.75;
    color: #1a1a1a;
    margin: 0 0 1.1rem;
  }

  .home-bio p:last-child {
    margin-bottom: 0;
  }

  .home-interests {
    margin-bottom: 2.5rem;
  }

  .home-interests-label {
    font-size: 11px;
    font-weight: 500;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    color: #999;
    margin-bottom: 0.75rem;
  }

  .home-tags {
    display: flex;
    flex-wrap: wrap;
    gap: 6px;
  }

  .home-tag {
    font-size: 13px;
    color: #1a4fa0;
    background: #e8f0fb;
    border: 1px solid #b5d4f4;
    border-radius: 100px;
    padding: 4px 12px;
    white-space: nowrap;
    font-family: 'Inter', sans-serif;
  }

  .home-links {
    display: flex;
    gap: 1.5rem;
    align-items: center;
  }

  .home-link {
    font-size: 14px;
    font-weight: 500;
    color: #1a1a1a;
    text-decoration: none;
    border-bottom: 1px solid #ccc;
    padding-bottom: 1px;
    transition: color 0.15s, border-color 0.15s;
  }

  .home-link:hover {
    color: #1a4fa0;
    border-color: #1a4fa0;
  }

  .home-link-sep {
    width: 1px;
    height: 14px;
    background: #ddd;
  }

  @media (max-width: 500px) {
    .home-top {
      flex-direction: column;
      gap: 1.25rem;
    }
  }
</style>

<div class="home-root">

  <div class="home-top">
    <div class="home-img-wrap">
      <img
        src="assets/images/1000854640.jpg"
        alt="Shubham Bhandare"
        class="home-img"
        onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';"
      >
      <div class="home-img-fallback">SB</div>
    </div>
    <div class="home-identity">
      <h1 class="home-name">Shubham Bhandare</h1>
      <p class="home-role">Research Assistant · Centre for Policy Research</p>
      <p class="home-edu">M.A. Economics, Azim Premji University</p>
    </div>
  </div>

  <hr class="home-divider">

  <div class="home-bio">
    <p>
      I work with Rahul Verma on projects related to political parties, elections, and public opinion.
    </p>
    <p>
      My research sits at the intersection of political economy, caste politics, electoral behaviour, and public policy — with a focus on how institutions, political processes, and historical contexts shape socio-economic outcomes.
    </p>
    <p>
      Current projects span caste representation in elections, dominant party systems, electoral geography, constituency delimitation, and the political determinants of public goods provision.
    </p>
  </div>

  <div class="home-interests">
    <div class="home-interests-label">Research themes</div>
    <div class="home-tags">
      <span class="home-tag">Political economy</span>
      <span class="home-tag">Caste politics</span>
      <span class="home-tag">Electoral behaviour</span>
      <span class="home-tag">Public policy</span>
      <span class="home-tag">Political representation</span>
      <span class="home-tag">Electoral geography</span>
      <span class="home-tag">Public goods provision</span>
    </div>
  </div>

  <div class="home-links">
    <a href="cv" class="home-link">CV</a>
    <div class="home-link-sep"></div>
    <a href="research" class="home-link">Research</a>
    <div class="home-link-sep"></div>
    <a href="writing" class="home-link">Writing</a>
  </div>

</div>
