---
layout: splash
title: "Socials"
permalink: /socials/
classes: wide

---
<style>

body {
  background: #faf8f4;
}

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

  max-width: 820px;

  margin: 4rem auto 2rem;
  padding: 0 1.5rem;

  font-size: 1.15rem;
  line-height: 1.9;

  color: #44525e;
}

.about-grid {
  display: grid;
  grid-template-columns: minmax(320px, 820px);
  justify-content: center;
  gap: 2rem;

  margin: 3rem auto 5rem;
  padding: 0 1.5rem;
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
  font-size: 1.5rem;
  font-weight: 650;
  color: #002A41;

  line-height: 1.2;
  margin-bottom: 1.4rem;

  letter-spacing: -0.02em;
  display: flex;
  flex-direction: column;
  text-align: center;
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


.parallax-hero-banner {
  height: 42vh;
  background-position: center 70%;
}

.parallax-hero-banner h1 {
  font-size: 3rem;
}


.parallax-hero {
  width: 100vw;
  margin-left: calc(50% - 50vw);
  margin-right: calc(50% - 50vw);

  height: 50vh;
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;

  display: flex;
  align-items: center;
  justify-content: center;

}

.image-1 {
  background-image: url('https://images.pexels.com/photos/30505255/pexels-photo-30505255.jpeg');
    background-position: 50% 100%; 
}


.image-2 {
  background-image: url('https://images.pexels.com/photos/5920661/pexels-photo-5920661.jpeg');
    background-position: 50% 50%; 
}


.image-3 {
  background-image: url('https://images.pexels.com/photos/36429592/pexels-photo-36429592.jpeg');
    background-position: 50% 50%; 
}


.image-4 {
  background-image: url('https://images.pexels.com/photos/23884118/pexels-photo-23884118.jpeg');
    background-position: 50% -20%; 
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
  font-size: 1.1rem;
  line-height: 1.5;
  width: 24px;
  opacity: 0.95;
  flex-shrink: 0;
}

.card-intro {
  font-size: 1rem;
  line-height: 1.7;
  color: #4b5b68;
  margin-bottom: 1.4rem;
}

.card-text {
  font-size: 0.95rem;
  color: #243746;
  line-height: 1.7;
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



  .parallax-hero-banner {
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


@media (max-width: 768px) {

  .card-text {
    font-size: 0.98rem;
    line-height: 1.7;
  }

  .about-card {
    padding: 1.5rem;
  }

  .card-title {
    font-size: 1.3rem;
    text-align: center;
  }

}

</style>

<section class="ws-hero">
  <div class="ws-hero__overlay"></div>
  <div class="ws-hero__grid"></div>
  <div class="ws-hero__content">
    <p class="ws-hero__eyebrow">Durham HPC Days 2026</p>
    <h1>Socials</h1>
  </div>
  </div>
</section>

<section class="description">
  <p>
Durham HPC Days 2026 is not only about talks, tutorials, and workshops -
it is also an opportunity to explore Durham, meet new people, exchange ideas,
build connections across the community, and enjoy the city together throughout the week!
  </p>


</section>


<section class="parallax-hero image-1">
</section>

<section class="about-grid">

  <!-- CEILIDH -->
  <div class="about-card">
    <div>
      <div class="card-title">
        Tuesday Evening Ceilidh
      </div>

      <div class="card-details">

        <div class="card-row">
          <div class="card-icon">🕖</div>
          <div class="card-text">
            Tuesday evening · 7:00pm to 9:00pm
          </div>
        </div>
        

        <div class="card-row">
          <div class="card-icon">🎻</div>
          <div class="card-text">
            Our main social event of the week will be a traditional ceilidh led by local musicians and dancers.
          </div>
        </div>

        <div class="card-row">
          <div class="card-icon">🎶</div>
          <div class="card-text">
            Music will include Scottish, Irish, and Northumbrian jigs and reels, accompanied by group folk dancing guided by a caller.
          </div>
        </div>

      </div>
    </div>
  </div>

</section>


<section class="parallax-hero image-2">
</section>


<section class="about-grid">


  <!-- FOOD TRUCKS -->
  <div class="about-card">
    <div>
      <div class="card-title">
        Evening Food Trucks & Informal Gatherings
      </div>

      <div class="card-details">

        <div class="card-row">
          <div class="card-icon">🍴</div>
          <div class="card-text">
            Dinner will be provided every evening by a selection of local food trucks.
          </div>
        </div>

        <div class="card-row">
          <div class="card-icon">📍</div>
          <div class="card-text">
            Food trucks will be located next to the Mountjoy Centre, creating a relaxed social and networking space for attendees after the day's sessions.
          </div>
        </div>


      </div>
    </div>
  </div>


</section>


<section class="parallax-hero image-3">
</section>



<section class="about-grid">

  <!-- MORNING RUNS -->
  <div class="about-card">
    <div>
      <div class="card-title">
        Morning Runs Along the River
      </div>

      <div class="card-details">

        <div class="card-row">
          <div class="card-icon">🏃</div>
          <div class="card-text">
            From Tuesday to Friday, optional organised morning runs will take place at 6:30am before the conference sessions begin.
          </div>
        </div>

        <div class="card-row">
          <div class="card-icon">🌤️</div>
          <div class="card-text">
            These easy 5k runs will follow scenic routes around the River Wear and through Durham city centre.
          </div>
        </div>

        <div class="card-row">
          <div class="card-icon">📍</div>
          <div class="card-text">
            Departure locations will be announced closer to the event.
          </div>
        </div>

      </div>
    </div>
  </div>

</section>



<section class="parallax-hero image-4">
</section>


<section class="about-grid">


  <!-- MORNING WALKS -->
  <div class="about-card">
    <div>
      <div class="card-title">
        Guided Walks to Campus
      </div>

      <div class="card-details">

        <div class="card-row">
          <div class="card-icon">🚶</div>
          <div class="card-text">
            Daily organised walks will depart from Durham city centre at 8:00am.
          </div>
        </div>

        <div class="card-row">
          <div class="card-icon">🏰</div>
          <div class="card-text">
            Each day will feature a different route passing through some of Durham’s most recognisable landmarks and green spaces. Routes may include the Cathedral, Castle, river bridges, Botanic Gardens, and surrounding areas.
          </div>
        </div>

      </div>
    </div>
  </div>

</section>


<section class="description">
  <p>
    Additional details, meeting points, and routes will be released closer to the event.
    Participation in all social activities is optional, and attendees are welcome to join as many or as few activities as they wish throughout the week.
  </p>
</section>
