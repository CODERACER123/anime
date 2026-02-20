<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>AniPicker — Anime Explorer</title>
  <link rel="stylesheet" href="styles.css" />
  <script defer src="app.js"></script>
</head>

<body>
  <header class="site-header">
    <div class="brand">
      <div class="logo" aria-hidden="true">AP</div>
      <div class="brand-text">
        <h1>AniPicker</h1>
        <p class="tagline">Pick an anime. Get pics, facts, and vibes.</p>
      </div>
    </div>

    <div class="header-actions">
      <label class="search">
        <span class="sr-only">Search anime</span>
        <input id="searchInput" type="search" placeholder="Search (e.g., Naruto, One Piece)..." />
      </label>

      <label class="select">
        <span class="sr-only">Choose anime</span>
        <select id="animeSelect"></select>
      </label>

      <button id="randomBtn" class="btn" type="button">Random</button>
      <button id="themeBtn" class="btn btn-ghost" type="button" aria-pressed="false">Toggle theme</button>
    </div>
  </header>

  <main class="container">
    <section class="hero">
      <div class="hero-card">
        <h2>Explore your next favorite anime</h2>
        <p>
          Choose an anime from the list to reveal a short summary, a gallery, and some cool facts.
          Everything here is editable—add your own titles, images, and trivia.
        </p>
        <div class="hero-hints">
          <span class="pill">Fast</span>
          <span class="pill">No frameworks</span>
          <span class="pill">Easy to customize</span>
        </div>
      </div>
      <div class="hero-glow" aria-hidden="true"></div>
    </section>

    <section id="animeSection" class="anime hidden" aria-live="polite">
      <div class="anime-top">
        <div>
          <h2 id="animeTitle">Anime Title</h2>
          <p id="animeSummary" class="summary">Summary goes here.</p>

          <div class="meta">
            <div class="meta-item">
              <span class="meta-label">Genre</span>
              <span id="animeGenre" class="meta-value">—</span>
            </div>
            <div class="meta-item">
              <span class="meta-label">Studio</span>
              <span id="animeStudio" class="meta-value">—</span>
            </div>
            <div class="meta-item">
              <span class="meta-label">First Aired</span>
              <span id="animeAired" class="meta-value">—</span>
            </div>
          </div>

          <div class="cta-row">
            <a id="animeLink" class="btn btn-primary" href="#" target="_blank" rel="noreferrer">Learn more</a>
            <button id="favoriteBtn" class="btn" type="button" title="Save to favorites">☆ Favorite</button>
          </div>
        </div>

        <figure class="poster">
          <img id="animePoster" alt="Selected anime poster" />
          <figcaption id="animeQuote" class="quote"></figcaption>
        </figure>
      </div>

      <section class="panel">
        <h3>Picture Gallery</h3>
        <div id="gallery" class="gallery"></div>
        <p class="hint">Tip: Replace the image URLs in <code>app.js</code> with your own.</p>
      </section>

      <section class="panel">
        <h3>Cool Facts</h3>
        <ul id="facts" class="facts"></ul>
      </section>
    </section>

    <section class="panel">
      <h3>Your Favorites</h3>
      <div id="favorites" class="favorites">
        <p class="muted">No favorites yet. Pick an anime and press “Favorite”.</p>
      </div>
    </section>
  </main>

  <footer class="site-footer">
    <p>
      Built with plain HTML/CSS/JS. Images are hotlinked placeholders—swap them for your own or host locally.
    </p>
  </footer>
</body>
</html>
