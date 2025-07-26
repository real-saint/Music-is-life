<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Music Journey</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <style>
    * {
      box-sizing: border-box;
    }
    body {
      margin: 0;
      font-family: 'Roboto', sans-serif;
      font-size: 14px;
      background: url('https://images.unsplash.com/photo-1507874457470-272b3c8d8ee2?auto=format&fit=crop&w=1600&q=80') no-repeat center center fixed;
      background-size: cover;
      color: #fff;
      padding: 1.5rem;
      scroll-behavior: smooth;
    }
    .container {
      max-width: 1000px;
      margin: 0 auto;
      background: rgba(0, 0, 0, 0.7);
      border-radius: 10px;
      padding: 1.5rem;
    }
    h1, h2 {
      color: #fbbf24;
    }
    .section {
      margin-bottom: 2rem;
      padding: 1rem;
      background: rgba(34, 34, 34, 0.85);
      border-radius: 12px;
      box-shadow: 0 0 10px rgba(255, 255, 255, 0.05);
      opacity: 0;
      transform: translateY(20px);
      animation: fadeInUp 1s forwards;
    }
    .section:nth-of-type(1) { animation-delay: 0.3s; }
    .section:nth-of-type(2) { animation-delay: 0.6s; }
    .section:nth-of-type(3) { animation-delay: 0.9s; }
    .section:nth-of-type(4) { animation-delay: 1.2s; }
    .section:nth-of-type(5) { animation-delay: 1.5s; }@keyframes fadeInUp {
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

.lyrics {
  font-style: italic;
  border-left: 4px solid #fbbf24;
  padding-left: 1rem;
  margin-top: 1rem;
  color: #ccc;
}
.timeline {
  list-style: none;
  padding: 0;
}
.timeline li {
  display: flex;
  justify-content: space-between;
  border-bottom: 1px solid #444;
  padding: 0.5rem 0;
}
.timeline li span:first-child {
  color: #888;
  font-family: monospace;
}
.visuals p {
  margin-bottom: 1rem;
}
strong {
  color: #fff;
}
.social-icons {
  text-align: center;
  margin-top: 1.5rem;
}
.social-icons a {
  margin: 0 8px;
  font-size: 1.2rem;
  color: #fbbf24;
  transition: transform 0.3s;
}
.social-icons a:hover {
  color: #fff;
  transform: scale(1.2);
}
@media (max-width: 600px) {
  body {
    padding: 1rem;
    font-size: 13px;
  }
  .timeline li {
    flex-direction: column;
    align-items: flex-start;
    gap: 0.3rem;
  }
}

  </style>
</head>
<body>
  <div class="container"><div class="section">
  <h1>👤 About Me</h1>
  <p>I'm <strong>Perfect</strong>, also known as <strong>realSAINT</strong>. I'm a creative programmer and a rising hip-hop artist. Whether I’m writing lines of code or writing rhymes, expression and innovation guide me. I believe music speaks when words fall short — and my journey has just begun.</p>
</div>

<div class="section">
  <h1>🎵 My Journey in Music</h1>
  <p><strong>From Rhymes to Reality – The Making of an Artist</strong></p>
  <p>
    Music isn’t just a hobby for me — it’s how I translate life into rhythm.
    What began as therapy grew into passion. Inspired by the likes of <strong>J. Cole</strong>, <strong>Kendrick Lamar</strong>, and others,
    I started experimenting with flows and finding my voice.
  </p>
</div>

<div class="section">
  <h2>✨ Sample Lyrics</h2>
  <div class="lyrics">
    “I walk through shadows but never fold,<br>
    They label me cold, but I’m chiseled in gold.<br>
    Pain in my chest, still I rise from the low,<br>
    With a pen as my weapon, I aim and reload.”
  </div>
</div>

<div class="section">
  <h2>🕰️ Milestone Timeline</h2>
  <ul class="timeline">
    <li><span>2022</span><span>Started writing lyrics seriously</span></li>
    <li><span>2023</span><span>Recorded my first freestyle on a phone mic</span></li>
    <li><span>2024</span><span>Joined local rap cyphers and got feedback from fellow artists</span></li>
    <li><span>2025</span><span>Working on my first EP project and sharing samples online</span></li>
  </ul>
</div>

<div class="section visuals">
  <h2>📸 Visuals & Next Steps</h2>
  <p><strong>Banner:</strong> Gritty street background, headphones on a mic stand, neon graffiti of my name (Perfect).</p>
  <p><strong>Photos:</strong> Me writing lyrics, recording sessions, and cypher moments.</p>
  <p>I’m working on my first official tracks. Every verse is one step closer to where I want to be. If you're into real hip-hop, keep your ears open. <strong>Perfect</strong> is just getting started.</p>
</div>

<div class="social-icons">
  <a href="https://instagram.com/yourhandle" target="_blank" title="Instagram"><i class="fab fa-instagram"></i></a>
  <a href="https://twitter.com/yourhandle" target="_blank" title="Twitter"><i class="fab fa-twitter"></i></a>
  <a href="https://soundcloud.com/yourhandle" target="_blank" title="SoundCloud"><i class="fab fa-soundcloud"></i></a>
  <a href="mailto:youremail@example.com" title="Email"><i class="fas fa-envelope"></i></a>
</div>

  </div>
</body>
</html>
