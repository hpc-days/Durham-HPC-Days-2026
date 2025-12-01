---
layout: splash
permalink: /
hidden: true
header:
  overlay_image: "/assets/images/background-hpc-days.png"
---
<style>
body {
  margin: 0;
  font-family: 'Inter', sans-serif;
  color: #222;
  scroll-behavior: smooth;
}
h1, h2, h3 {
  font-weight: 600;
}
a {
  color: #0055aa;
  text-decoration: none;
}

s {
  color: #0055aa;
  text-decoration: none;
  font-size: 4rem;
}

s:hover {
  text-decoration: underline;
}
a:hover {
  text-decoration: underline;
}
.hero {
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 3rem 1rem;
  background: transparent;
  width: 100%;
}
.hero-inner {
  position: relative;
  max-width: 960px;
  width: 100%;
  margin: 0 auto;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 4px 16px rgba(0,0,0,0.3);
}
.hero-video {
  position: relative;
  width: 100%;
  aspect-ratio: 16 / 9;
  overflow: hidden;
}
#yt-player {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  pointer-events: none;
}
.hero-content {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: center;
  color: white;
  z-index: 2;
  padding: 1rem;
}
.hero-inner::before {
  content: "";
  position: absolute;
  inset: 0;
  background: rgba(0, 0, 0, 0.2);
  z-index: 1;
}
.btn {
  background: #002A41;
  color: white !important;
  padding: 0.9rem 2rem;
  border-radius: 30px;
  font-weight: 500;
  text-decoration: none;
  transition: all 0.3s ease;
  display: inline-block;
  font-size: 1.2rem;
}

.btn:hover {
  background: #003d80;
  transform: translateY(-3px);
}

.btn.btn-purple {
  background: #68246D;
  color: #fff !important;
  font-size: 1.2rem; 
  transition: background 0.25s ease, transform 0.18s ease;
}

/* hover */
.btn.btn-purple:hover {
  background: #8e3d94;  
  transform: translateY(-3px);
}


section {
  max-width: 900px;
  margin: 3rem auto;
  padding: 0 1.5rem;
  text-align: center;
}
section h2 {
  font-size: 2rem;
  margin-bottom: 1rem;
  line-height: 0.3;
}
section p {
  font-size: 1.1rem;
  line-height: 1.7;
  color: #ffff;
}
t {
  font-size: 0.9rem;
  line-height: 1.7;
  color: #002A41;
}
.image-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 1rem;
  margin-top: 2rem;
}
.image-grid img {
  width: 100%;
  height: 220px;
  object-fit: cover;
  border-radius: 10px;
  transition: transform 0.4s ease, box-shadow 0.4s ease;
}
.image-grid img:hover {
  transform: scale(1.05);
  box-shadow: 0 8px 16px rgba(0,0,0,0.3);
}
.fade-in {
  opacity: 0;
  transform: translateY(40px);
  transition: all 0.8s ease-out;
}
.fade-in.visible {
  opacity: 1;
  transform: translateY(0);
}
.footer-note {
  text-align: center;
  padding: 2rem 0;
  background: #003366;
  color: white;
  font-size: 0.9rem;
}
@keyframes fadeIn {
  from { opacity: 0; transform: translateY(40px); }
  to { opacity: 1; transform: translateY(0); }
}
.call-for-submissions {
  background: #002A41;
  color: white;
  padding: 2rem 2rem;
  border-radius: 22px;
  text-align: center;
  min-height: 260px;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.call-for-submissions h2 {
  font-size: 1.9rem;
  margin-bottom: 1.2rem;
}
.call-for-submissions .deadline-box {
  font-size: 1.1rem;
  background: white;
  color: #002A41;
  display: inline-block;
  padding: 1rem 2rem;
  border-radius: 15px;
  font-weight: 500;
  margin-top: 1.5rem;
}
.hero-content .btn {
  margin: 0.5rem;
}

.dual-cards {
  display: grid;
  grid-template-columns: repeat(2, minmax(360px, 1fr));
  gap: 3rem;
  max-width: 1200px;
  margin: 4rem auto;
  padding: 0 2rem;
}
.dual-cards .call-for-submissions {
  margin: 0;
}

.page__content,
.page__inner-wrap,
.wrapper,
.initial-content {
  max-width: 100% !important;
  padding-left: 0 !important;
  padding-right: 0 !important;
}


/* Mobile stacking */
@media (max-width: 780px) {
  .dual-cards {
    grid-template-columns: 1fr;
  }
}


@media (max-width: 900px) {
  .hero { padding: 2rem 1rem; }
  .hero-inner { max-width: 100%; border-radius: 8px; }
  .hero-content h1 { font-size: 1.6rem; }
}
</style>

<section id="about" class="fade-in">
  <h2>💡  15th to 19th of June 2026</h2>
  <t>
    The <strong>Durham HPC Days</strong> bring together researchers, developers, and practitioners
    to explore the frontiers of high-performance computing, data analysis, and scientific innovation.
  </t>
</section>

<div class="dual-cards fade-in">

  <section class="call-for-submissions">
    <h2>📢 Call for Sessions</h2>
    <div class="deadline-box">
      🗓️ Submission Deadline: <strong>January 31st</strong>
    </div>
    <br><br>
    <a href="/call-for-sessions/" class="btn btn-purple">Submit Your Session</a>
  </section>

  <section class="call-for-submissions">
    <h2>📝 Registration Open</h2>
    <div class="deadline-box">
      Register now to attend Durham HPC Days 2026
    </div>
    <br><br>
    <a href="https://pay.durham.ac.uk/event-durham/durham-hpc-days-2026" class="btn btn-purple">Register</a>
  </section>

</div>

<div class="hero">
  <div class="hero-inner">
    <div class="hero-video">
      <div id="yt-player"></div>
    </div>
    <div class="hero-content">
      <h1>Durham HPC Days 2025 Video Recap</h1>
      <p>Take a look back at Durham HPC Days 2025 in this short recap featuring our keynote speakers.</p>
      <a href="https://youtu.be/wPjtwACmaUg" class="btn" target="_blank" rel="noopener">View Video</a>
       <a href="https://durham.readthedocs.io/en/latest/hpcdays2025/index.html" class="btn" target="_blank" rel="noopener">Visit last year's website</a>
    </div>
  </div>
</div>



<div class="header-image"></div>

<section id="gallery" class="fade-in">
  <h2>📸 Gallery</h2>
  <div class="image-grid">
    <img src="/assets/images/Sessions.jpg" alt="Sessions">
    <img src="/assets/images/food-truck.jpg" alt="Food truck">
    <img src="/assets/images/social.png" alt="social">
  </div>
</section>

<section id="programme" class="fade-in">
  <h2>🗓️ Explore the Programme</h2>
  <t style="max-width: 700px; margin: 0 auto 2rem;">
    Discover the full schedule of keynotes, technical sessions, and social events for the upcoming conference.
    Check the programme to plan your participation and make the most of your experience at Durham HPC Days.<br>
  </t><br>
  <a href="/programme-empty/" class="btn">Full programme coming up soon</a>
</section>

<script>
(function() {
  function onScroll() {
    document.querySelectorAll('.fade-in').forEach(function(el) {
      var rect = el.getBoundingClientRect();
      if (rect.top < window.innerHeight - 100) el.classList.add('visible');
    });
  }
  document.addEventListener('scroll', onScroll);
  document.addEventListener('DOMContentLoaded', onScroll);
})();
</script>

<script>
var YT_VIDEO_ID = 'wPjtwACmaUg';
var player;
function onYouTubeIframeAPIReady() {
  player = new YT.Player('yt-player', {
    width: '100%',
    height: '100%',
    videoId: YT_VIDEO_ID,
    playerVars: {
      autoplay: 1,
      controls: 0,
      modestbranding: 1,
      rel: 0,
      mute: 1,
      playsinline: 1,
      loop: 1,
      playlist: YT_VIDEO_ID,
      iv_load_policy: 3
    },
    events: {
      onReady: function(e) {
        try { e.target.mute(); e.target.playVideo(); } catch (err) {}
      },
      onStateChange: function(e) {
        if (e.data === YT.PlayerState.ENDED) {
          try { e.target.seekTo(0); e.target.playVideo(); } catch (err) {}
        }
      }
    }
  });
}
(function loadYT() {
  if (window.YT && window.YT.Player) return onYouTubeIframeAPIReady();
  var tag = document.createElement('script');
  tag.src = "https://www.youtube.com/iframe_api";
  var firstScript = document.getElementsByTagName('script')[0];
  firstScript.parentNode.insertBefore(tag, firstScript);
})();
</script>

