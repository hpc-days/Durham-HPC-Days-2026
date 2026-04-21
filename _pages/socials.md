---
layout: splash
title: "Socials"
permalink: /socials/
classes: wide

---
<style>



  .ws-hero {
    position: relative;
    width: 100vw;
    margin-left: calc(50% - 50vw);
    height: 52vh;
    min-height: 320px;
    background-image: url("https://github.com/hpc-days/Durham-HPC-Days-2026/blob/main/assets/images/eva-blue-banner-no-title.png?raw=true");
    background-attachment: fixed;
    background-position: center 60%;
    background-repeat: no-repeat;
    background-size: cover;
    display: flex;
    align-items: flex-end;
    justify-content: flex-start;
    overflow: hidden;
  }

  .ws-hero__overlay {
    position: absolute;
    inset: 0;
  background: 
    linear-gradient(rgba(0,0,0,0.35), rgba(0,0,0,0.35)),
    linear-gradient(
      135deg,
      rgba(140, 60, 0, 0.95) 0%,
      rgba(255, 140, 0, 0.75) 60%,
      rgba(140, 60, 0, 0.55) 100%
    );
  }


  .ws-hero__grid {
    position: absolute;
    inset: 0;
    background-image:
    linear-gradient(rgba(255, 220, 120, 0.06) 1px, transparent 1px),
    linear-gradient(90deg, rgba(255, 220, 120, 0.06) 1px, transparent 1px);
    background-size: 48px 48px;
    pointer-events: none;
  }

  .ws-hero__content {
    position: relative;
    z-index: 2;
    padding: 0 3rem 3rem;
    max-width: 860px;
  }

  .ws-hero__eyebrow {
    display: inline-flex;
    align-items: center;
    gap: 0.5rem;
    font-size: 0.72rem;
    font-weight: 600;
    letter-spacing: 0.18em;
    text-transform: uppercase;
    color: rgba(255,255,255,0.65);
    margin-bottom: 0.75rem;
  }

  .ws-hero__eyebrow::before {
    content: '';
    display: block;
    width: 28px;
    height: 2px;
  background: #ffffff;
    border-radius: 2px;
  }

  .ws-hero h1 {
    
    font-size: clamp(2.4rem, 5vw, 4rem);
    font-weight: 400;
    color: #ffffff;
    margin: 0 0 0.5rem;
    line-height: 1.08;
    letter-spacing: -0.02em;
  }

  .ws-hero h1 em {
    font-style: italic;
    color: #7ec8ff;
  }

  .ws-hero__sub {
    font-size: 1rem;
    color: rgba(255,255,255,0.60);
    font-weight: 300;
    margin: 0;
    letter-spacing: 0.01em;
  }


.description {
 

  
  text-align: center;
 
  line-height: 1.6;
  
    max-width: 700px;
  margin: 2rem auto 0.5rem;
  font-size: 1.05rem;
  color: #555;
}


.about-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 1.8rem;
  margin: 3rem auto 4rem;
  padding: 0 1rem;
}


.about-card {
  background: #ffffff;
  border-radius: 16px;
  padding: 1.2rem 1.3rem;
  box-shadow: 0 8px 22px rgba(0,0,0,0.05);

  display: flex;
  flex-direction: column;
  justify-content: space-between;

  min-height: 150px;

  transition: all 0.25s ease;
border-top: 6px solid #f5b800;
}


.about-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 14px 32px rgba(0,0,0,0.10);
}


.card-title {
  font-size: 1.05rem;
  font-weight: 600;
  color: #002A41;

  line-height: 1.35;
  margin-bottom: 0.8rem;


  display: -webkit-box;
  -webkit-line-clamp: 4; 
  -webkit-box-orient: vertical;
  overflow: hidden;

  min-height: 2.8em;
}


.about-button {
  align-self: flex-start;

  font-size: 0.78rem;
  font-weight: 600;

  padding: 0.4rem 1rem;
  border-radius: 999px;

  background: #002A41;
  color: #fff !important;
  text-decoration: none;

  transition: all 0.2s ease;
}

.about-button:hover {
  background: #f5b800;
  transform: scale(1.05);
}


.parallax-hero {
  height: 42vh;
  background-position: center 70%;
}

.parallax-hero h1 {
  font-size: 3rem;
}




.card-details {
  margin: 0.6rem 0 1rem;
  display: flex;
  flex-direction: column;
  gap: 0.6rem;
}


.card-row {
  display: flex;
  align-items: flex-start;
  gap: 0.6rem;
}


.card-icon {
  font-size: 0.9rem;
  line-height: 1.4;
  opacity: 0.8;
  width: 18px;
  flex-shrink: 0;
}


.card-text {
  font-size: 0.82rem;
  color: #002A41;
  line-height: 1.4;
}


.card-text div {
  margin-bottom: 0.1rem;
}


.card-text {
  display: -webkit-box;
  -webkit-line-clamp: 3;
  -webkit-box-orient: vertical;
  overflow: hidden;
}

@media (max-width: 768px) {
  .about-grid {
    gap: 1.2rem;
  }

  .ws-hero__eyebrow {
    display: none;
  }
  
  .card-title {
    -webkit-line-clamp: 2;
  }



  .parallax-hero {
    background-attachment: scroll;
    height: 38vh;
  }
  
    .ws-hero {
    height: 30vh;
    min-height: 150px;
      align-items: center;
  justify-content: center;
  text-align: center;

  }

.ws-hero__content {
  padding: 0 1.5rem;
}

  .about-grid {
    gap: 1.5rem;
  }

  .card-title {
    font-size: 1.05rem;
    -webkit-line-clamp: 2; 
    min-height: 2.8em;
  }
}


</style>

<section class="ws-hero">
  <div class="ws-hero__overlay"></div>
  <div class="ws-hero__grid"></div>
  <div class="ws-hero__content">
    <p class="ws-hero__eyebrow">Durham HPC Days 2026</p>
    <h1>Socials</h1>
    <p class="ws-hero__sub">
    More details coming up soon</p>
  </div>
  </div>
</section>

<section class="description">
  <p>
    Welcome to the Durham HPC Days 2026 social events. 
    More details coming up soon.
  </p>
</section>

