---
layout: splash
permalink: /
hidden: true
header:
  overlay_image: "https://github.com/hpc-days/Durham-HPC-Days-2026/blob/main/assets/images/Banner-home.png?raw=true"
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

a:hover {
  text-decoration: underline;
}



.hero {
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 3rem 1rem;
  width: 100%;
}

.hero-inner {
  position: relative;
  max-width: 960px;
  width: 100%;
  margin: 0 auto;
  border-radius: 14px;
  overflow: hidden;
  box-shadow: 0 8px 24px rgba(0,0,0,0.25);
}

.hero-video {
  position: relative;
  width: 100%;
  aspect-ratio: 16 / 9;
  overflow: hidden;
}

#yt-player {
  position: absolute;
  inset: 0;
  width: 100%;
  height: 100%;
  pointer-events: none;
}

.hero-inner::before {
  content: "";
  position: absolute;
  inset: 0;
  background: rgba(0,0,0,0.35);
  z-index: 1;
}

.hero-content {
  position: absolute;
  inset: 0;
  z-index: 2;

  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;

  text-align: center;
  color: white;
  padding: 1.5rem;
}

.hero-content h1 {
  margin-bottom: 0.5rem;
}

.hero-content p {
  max-width: 600px;
  margin-bottom: 1rem;
}



.btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;

  padding: 1rem 2.4rem;
  border-radius: 999px;

  font-weight: 700;
  font-size: 1rem;
  letter-spacing: 0.3px;

  text-decoration: none;
  cursor: pointer;

  transition: all 0.25s ease;
}

.btn-purple {
  background:  #002A41;
  color: #ffffff !important;
  box-shadow: 0 8px 20px rgba(0, 42, 65, 0.25);
}

.btn-purple:hover {
  transform: translateY(-4px);
  box-shadow: 0 14px 30px rgba(0, 42, 65, 0.35);
}

.btn-purple:active {
  transform: translateY(-1px);
}

.btn-purple:focus-visible {
  outline: 3px solid rgba(0, 61, 128, 0.5);
  outline-offset: 4px;
}



section {
  max-width: 900px;
  margin: 1rem auto;
  padding: 0 1.5rem;
  text-align: center;
}

section h2 {
  font-size: 2rem;
  margin-bottom: 1rem;
  line-height: 1.2;
}

section p {
  font-size: 1.1rem;
  line-height: 1.7;
  color: #333;
}


  .hero-content p {
    font-size: 0.95rem;
    color: #ffffff !important;
  }
  
/* Custom text tag fix */
t {
  font-size: 1rem;
  line-height: 1.7;
  color: #002A41;
  display: block;
}



.dual-cards {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 2rem;
  max-width: 1100px;
  margin:0.5rem auto;
  padding: 0 2rem;
}

.call-for-submissions {
  background: #ffffff;
  border-top: 4px solid #002A41;
  box-shadow: 0 10px 25px rgba(0,0,0,0.06);
  padding: 2rem;
  border-radius: 20px;
  text-align: center;

  display: flex;
  flex-direction: column;
  justify-content: center;

  transition: all 0.3s ease;
}

.call-for-submissions:hover {
  transform: translateY(-6px);
  box-shadow: 0 25px 45px rgba(0,0,0,0.12);
}

.call-for-submissions h2 {
  font-size: 1.4rem;
  color: #002A41;
  margin-bottom: 0.5rem;
}

.deadline-box {
  font-size: 1rem;
  background: #f5f7fa;
  color: #002A41;
  padding: 0.9rem 1rem;
  border-radius: 14px;
  font-weight: 500;
  margin: 1rem 0 1.5rem 0;
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
  border-radius: 12px;
  transition: transform 0.4s ease, box-shadow 0.4s ease;
}

.image-grid img:hover {
  transform: scale(1.05);
  box-shadow: 0 12px 24px rgba(0,0,0,0.2);
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



.page__content,
.page__inner-wrap,
.wrapper,
.initial-content {
  max-width: 100% !important;
  padding-left: 0 !important;
  padding-right: 0 !important;
}



@media (max-width: 900px) {

  .dual-cards {
    grid-template-columns: 1fr;
    padding: 0 1rem;
  }

  .hero-inner {
    border-radius: 10px;
  }

  .hero-content h1 {
    font-size: 1.5rem;
  }

  .hero-content p {
    font-size: 0.95rem;
    color: #ffffff !important;
  }
  


  .call-for-submissions {
    padding: 1.5rem;
  }

  .call-for-submissions .btn {
    width: 100%;
    padding: 1rem;
  }

  .image-grid {
    grid-template-columns: 1fr;
  }

  .image-grid img {
    height: auto;
  }

  section h2 {
    font-size: 1.5rem;
  }

}

@media (max-width: 900px) {
  
  .hero-content h1,
  .hero-content a:not([href*="youtu.be"]) {
    display: none;
  }


  .hero-content {
    justify-content: center;
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
    
      <h1>Durham HPC Days 2025 Video Recap</h1>
     
      <a href="https://durham.readthedocs.io/en/latest/hpcdays2025/index.html" class="btn btn-purple" target="_blank" rel="noopener">Visit last year's website</a>

      <a href="https://youtu.be/wPjtwACmaUg" class="btn btn-purple" target="_blank" rel="noopener">HPC Days 2025 Video</a>
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
  <a href="https://hpc-days.github.io/Durham-HPC-Days-2026/programme-week/" class="btn btn-purple">Full programme coming up soon</a>
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
