---
layout: splash
permalink: /
hidden: true
header:
  overlay_image: "https://github.com/hpc-days/Durham-HPC-Days-2026/blob/main/assets/images/Banner.png?raw=true"
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
  background: #002A41;
  color: #fff !important;
  font-size: 0.8rem; 
  transition: background 0.25s ease, transform 0.18s ease;
  margin-top:0px !important;
  font-weight: 800;
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
  background: #ffffff;
  border-top: 4px solid #002A41;
  box-shadow: 0 10px 18px rgba(0,0,0,0.05);
  padding: 2rem 2rem;
  border-radius: 22px;
  text-align: center;
  min-height: 260px;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.call-for-submissions hover{
  transform: translateY(-5px);
  box-shadow: 0 35px 55px rgba(0,0,0,0.3);
}

.call-for-submissions h2 {
  font-size: 1.5rem;
  color: #002A41;
  margin-bottom: 0.5rem;
}
.call-for-submissions .deadline-box {
  font-size: 1rem;
  background: white;
  color: #002A41;
  display: inline-block;
  padding: 1rem 1rem;
  border-radius: 15px;
  font-weight: 500;
  margin-top: 0.5rem;
  margin
}

.dual-cards {
  display: grid;
  grid-template-columns: repeat(2, minmax(400px, 1fr));
  gap: 2rem;
  max-width: 1200px;
  margin: 1rem auto;
  padding: 0 2rem;
  justify-content: center;  
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
@media (max-width: 900px) {

  /* Hero adjustments */
  .hero-inner {
    max-width: 100%;
    border-radius: 8px;
  }
  .hero-content h1 {
    font-size: 1.6rem;
    line-height: 2rem;
  }
  .hero-content p {
    font-size: 0.95rem;
    line-height: 1.3rem;
    max-width: 90%;
    word-wrap: break-word;
  }


  .call-for-submissions {
    padding: 1.5rem 1rem;
  }


  .call-for-submissions .btn {
    width: 100%;
    max-width: none;
    font-size: 1rem;
    padding: 0.75rem 1.6rem;
  }

  .image-grid {
    grid-template-columns: 1fr;
    gap: 1rem;fv
  }
  .image-grid img {
    height: auto;
  }

  section h2 {
    font-size: 1.5rem;
    line-height: 1.8rem;
  }
  section p, t {
    font-size: 0.95rem;
    line-height: 1.4rem;
  }
    .hero-content {
    padding: 1rem;
  }
  .hero-content .btn {
    display: block;
    width: 100%;
    max-width: 300px;
    margin: 0.5rem auto;
    font-size: 1rem;
    padding: 0.8rem 1rem;
  }

  /* Fade-in elements spacing */
  .fade-in {
    margin: 1rem 0;
  }

.hero-content .btn-mobile-only {
  display: none;
}


}


@media (max-width: 768px) {
  .hero-content h1,
  .hero-content p,
  .hero-content a.btn:not(.btn-mobile-only) {
    display: none;
  }

  .hero-content .btn-mobile-only {
    display: inline-block;
    font-size: 1.1rem;
    padding: 0.9rem 2rem;
    margin: 0 auto;
    
  }

  .hero-content h1 {
    font-size: 1.3rem;
    line-height: 1.5rem;
  }
  .hero-content p {
    font-size: 0.9rem;
    line-height: 1.2rem;
  }
  .call-for-submissions h2 {
    font-size: 1.1rem;
  }

  .hero-inner::before {
  background: rgba(0, 0, 0, 0.5); /* antes estaba 0.2 */
  z-index: 1;
}


.hero-content h1,
.hero-content p,
.hero-content .btn {
  text-shadow: 0 2px 6px rgba(0,0,0,0.6);
}

.hero-content .btn {
  background: rgba(0,42,65,0.85);
}
.hero-content .btn.btn-purple {
  background: rgba(104,36,109,0.85);
}



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
    <h2>📝 Registration   </h2>
    <div class="deadline-box">
      Register now to attend Durham HPC Days 2026
    </div>
    <br><br>
    <a href="https://pay.durham.ac.uk/event-durham/durham-hpc-days-2026" class="btn btn-purple">Register</a>
  </section>

  <section class="call-for-submissions">
    <h2>📢 Call for Talks</h2>
    <div class="deadline-box">
      🗓️ Submission Deadline: <strong>March 13th</strong>
    </div>
    <br><br>
    <a href="https://hpc-days.github.io/Durham-HPC-Days-2026/call-for-talks/" class="btn btn-purple">Submit Your Talk</a>
  </section>
  
  
</div>

<div class="hero">
  <div class="hero-inner">
    <div class="hero-video">
      <div id="yt-player"></div>
    </div>
    <div class="hero-content">
      <!-- Contenido original -->
      <h1>Durham HPC Days 2025 Video Recap</h1>
      <p>Take a look back at Durham HPC Days 2025 in this short recap featuring our keynote speakers.</p>
     
      <a href="https://durham.readthedocs.io/en/latest/hpcdays2025/index.html" class="btn" target="_blank" rel="noopener">Visit last year's website</a>

      <a href="https://youtu.be/wPjtwACmaUg" class="btn btn-mobile-only" target="_blank" rel="noopener">HPC Days 2025 Video</a>
    </div>
  </div>
</div>


<div class="header-image"></div>

<section id="gallery" class="fade-in">
  <h2>📸 Gallery</h2>
  <div class="image-grid">
    <img src="https://github.com/hpc-days/Durham-HPC-Days-2026/blob/main/assets/images/Sessions.jpg?raw=true" alt="Sessions">
    <img src="https://github.com/hpc-days/Durham-HPC-Days-2026/blob/main/assets/images/food-truck.jpg?raw=true" alt="Food truck">
    <img src="https://github.com/hpc-days/Durham-HPC-Days-2026/blob/main/assets/images/social.png?raw=true" alt="social">
  </div>
</section>

<section id="programme" class="fade-in">
  <h2>🗓️ Explore the Programme</h2>
  <t style="max-width: 700px; margin: 0 auto 2rem;">
    Discover the full schedule of keynotes, technical sessions, and social events for the upcoming conference.
    Check the programme to plan your participation and make the most of your experience at Durham HPC Days.<br>
  </t><br>
  <a href="https://hpc-days.github.io/Durham-HPC-Days-2026/programme-empty/" class="btn">Full programme coming up soon</a>
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

