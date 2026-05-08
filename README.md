# TravelBlog_level2
:root {
  --brown-dark: #2c2416;
  --brown-mid: #5a3e28;
  --brown-light: #3a2c1e;
  --gold: #c9a96e;
  --gold-muted: #a08c6e;
  --cream: #f5f0e8;
  --cream-card: #ede5d4;
  --border: #d4c4a8;
  --text-cream: #e8d9b8;
}

/* BODY */
body {
  margin: 0;
  background: var(--cream);
  font-family: 'DM Sans', sans-serif;
  color: var(--brown-dark);
}

/* NAVBAR */
.navbar-custom {
  background: var(--brown-dark);
  padding: 15px 30px;
}

.navbar-brand {
  font-family: 'Playfair Display', serif;
  color: var(--text-cream) !important;
  font-size: 1.4rem;
}

.nav-link {
  color: var(--gold-muted) !important;
  text-transform: uppercase;
  font-size: 0.75rem;
  letter-spacing: 1px;
}

.nav-link.active {
  color: white !important;
  border-bottom: 1px solid var(--gold);
}

/* HERO */
.hero-wrap {
  position: relative;
  height: 520px;
  overflow: hidden;
}

.hero-wrap img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  filter: brightness(0.6);
}

.hero-content {
  position: absolute;
  bottom: 0;
  padding: 60px;
}

.badge-category {
  background: var(--gold);
  color: white;
  padding: 5px 12px;
  text-transform: uppercase;
  font-size: 0.7rem;
  letter-spacing: 2px;
}

.hero-title {
  color: white;
  font-size: 3rem;
  font-family: 'Playfair Display', serif;
  margin: 20px 0;
  max-width: 650px;
}

.hero-meta {
  color: var(--text-cream);
  font-size: 0.9rem;
}

/* ARTICLE */
.lead-italic {
  font-family: 'Lora', serif;
  font-style: italic;
  font-size: 1.2rem;
  line-height: 1.8;
  color: var(--brown-mid);
}

.article-body {
  font-family: 'Lora', serif;
  line-height: 1.9;
  color: var(--brown-light);
}

.section-heading {
  font-family: 'Playfair Display', serif;
  border-left: 4px solid var(--gold);
  padding-left: 15px;
  margin: 40px 0 20px;
}

.pull-quote {
  background: var(--cream-card);
  border-left: 4px solid var(--gold);
  padding: 25px;
  margin: 40px 0;
  font-size: 1.3rem;
  font-style: italic;
  font-family: 'Playfair Display', serif;
}

/* QUICK FACTS */
.quick-facts {
  background: var(--brown-dark);
  padding: 30px;
  border-radius: 4px;
}

.fact-label {
  color: var(--gold);
  text-transform: uppercase;
  font-size: 0.7rem;
}

.fact-value {
  color: var(--text-cream);
  font-family: 'Lora', serif;
}

/* COMMENT SECTION */
.comment-section {
  margin-top: 60px;
  border-top: 1px solid var(--border);
  padding-top: 30px;
}

.comment-section h3 {
  font-family: 'Playfair Display', serif;
  margin-bottom: 20px;
}

.form-control {
  border: 1px solid var(--border);
  border-radius: 3px;
}

.btn-post {
  background: var(--brown-dark);
  color: white;
  border: none;
  padding: 12px 30px;
  text-transform: uppercase;
  letter-spacing: 1px;
}

.btn-post:hover {
  background: var(--brown-mid);
}

/* SIDEBAR */
.sidebar-card {
  background: white;
  border: 1px solid var(--border);
  padding: 30px;
  border-radius: 4px;
}

.author-img {
  width: 72px;
  height: 72px;
  border-radius: 50%;
  object-fit: cover;
  margin-bottom: 15px;
}

.author-role {
  color: var(--gold);
  text-transform: uppercase;
  font-size: 0.75rem;
}

.author-bio {
  color: var(--brown-mid);
  line-height: 1.7;
}

.related-thumb {
  width: 100%;
  height: 110px;
  object-fit: cover;
  border-radius: 4px;
}

.related-cat {
  color: var(--gold);
  text-transform: uppercase;
  font-size: 0.7rem;
  margin-top: 10px;
}

.related-title {
  font-family: 'Playfair Display', serif;
}

/* FOOTER */
footer {
  background: var(--brown-dark);
  color: var(--gold-muted);
  text-align: center;
  padding: 25px;
  margin-top: 50px;
}
/* COMMENT AVATAR */
.comment-avatar {
  width: 45px;
  height: 45px;
  border-radius: 50%;
  background: #c9a96e;
  color: white;
  display: flex;
  align-items: center;
  justify-content: center;
  font-weight: bold;
  flex-shrink: 0;
}

/* COMMENT TEXT */
.comment-text {
  font-family: 'Lora', serif;
  line-height: 1.6;
  color: #5a3e28;
}
/* RESPONSIVE */
@media (max-width: 768px) {

  .hero-content {
    padding: 30px;
  }

  .hero-title {
    font-size: 2rem;
  }

}
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Lost in Kyoto — Travel Blog</title>

  <!-- External CSS -->
  <link rel="stylesheet" href="explea.css">

  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

  <!-- Bootstrap Icons -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css" rel="stylesheet">

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Lora:ital@0;1&family=DM+Sans:wght@400;500&display=swap" rel="stylesheet">
</head>

<body>

<!-- NAVBAR -->
<nav class="navbar navbar-expand-lg navbar-custom">
  <div class="container-fluid">

    <a class="navbar-brand" href="#">Wanderlust</a>

    <div class="navbar-nav ms-auto d-flex flex-row gap-3">
      <a class="nav-link" href="#Asia">Asia</a>
      <a class="nav-link" href="#Europe">Europe</a>
      <a class="nav-link" href="#America">Americas</a>
      <a class="nav-link active" href="#About">About</a>
    </div>

  </div>
</nav>

<!-- HERO -->
<div class="hero-wrap">

  <img
    src="https://images.unsplash.com/photo-1528360983277-13d401cdc186?w=1400&q=80"
    alt="Kyoto Temple"
  >

  <div class="hero-content">

    <span class="badge-category">Japan · Asia</span>

    <h1 class="hero-title">
      Lost in Kyoto's Ancient Streets at Dawn
    </h1>

    <div class="hero-meta">
      By <strong>Meera Nair</strong> · March 28, 2025 · 8 min read
    </div>

  </div>
</div>

<!-- MAIN CONTENT -->
<div class="container-lg py-5">

  <div class="row g-5">

    <!-- ARTICLE -->
    <div class="col-lg-8">

      <p class="lead-italic">
        There is a version of Kyoto that exists only before sunrise — a quiet, fog-wrapped world where stone lanterns glow amber.
      </p>

      <p class="article-body">
        I arrived at Fushimi Inari at 5:15 in the morning, before the crowds appeared. The peaceful atmosphere made the entire place feel magical.
      </p>

      <h2 class="section-heading">
        The Rhythm of the Old City
      </h2>

      <p class="article-body">
        Kyoto does not ask to be rushed. Every street, temple, and pathway encourages slow exploration and quiet appreciation.
      </p>

      <blockquote class="pull-quote">
        "In Kyoto, the past is not preserved — it breathes."
      </blockquote>

      <h2 class="section-heading">
        What to Eat, Where to Wander
      </h2>

      <p class="article-body">
        Visit Nishiki Market for authentic local food, warm dumplings, and fresh matcha desserts.
      </p>

      <!-- QUICK FACTS -->
      <div class="quick-facts mt-4">

        <div class="row g-3">

          <div class="col-6">
            <p class="fact-label">Best time to visit</p>
            <p class="fact-value">March–May · Oct–Nov</p>
          </div>

          <div class="col-6">
            <p class="fact-label">Getting there</p>
            <p class="fact-value">Shinkansen from Tokyo</p>
          </div>

          <div class="col-6">
            <p class="fact-label">Don't miss</p>
            <p class="fact-value">Fushimi Inari at sunrise</p>
          </div>

          <div class="col-6">
            <p class="fact-label">Budget</p>
            <p class="fact-value">¥8,000–12,000 / day</p>
          </div>

        </div>

      </div>

      <!-- COMMENT SECTION -->
      <section class="comment-section">

        <h3>Leave a Comment</h3>

        <div class="row g-3 mb-3">

          <div class="col-md-6">
            <input type="text" class="form-control" placeholder="Your Name">
          </div>

          <div class="col-md-6">
            <input type="email" class="form-control" placeholder="Email Address">
          </div>

        </div>

        <textarea class="form-control mb-3" rows="5" placeholder="Write your comment"></textarea>

        <button class="btn-post">
          Post Comment
        </button>

      </section>

    </div>

    <!-- SIDEBAR -->
    <div class="col-lg-4">

      <div class="sidebar-card mb-4">

        <img
          src="https://images.unsplash.com/photo-1529626455594-4ff0802cfb7e?w=200&q=80"
          alt="Author"
          class="author-img"
        >

        <h4>Achal Tambe</h4>

        <p class="author-role">
          Contributing Editor
        </p>

        <p class="author-bio">
          Solo traveller, slow food enthusiast, and passionate storyteller.
        </p>

      </div>

      <div class="sidebar-card">

        <h4>Related Posts</h4>

        <img
          src="https://images.unsplash.com/photo-1513415277900-a62401e19be4?w=400&q=80"
          alt="Tokyo"
          class="related-thumb"
        >

        <p class="related-cat">
          Japan
        </p>

        <p class="related-title">
          48 Hours in Tokyo's Hidden Neighborhoods
        </p>

      </div>

    </div>

  </div>

</div>

<!-- FOOTER -->
<footer>
  <p>© 2025 Wanderlust Magazine · All rights reserved</p>
</footer>
</body>
</html>
