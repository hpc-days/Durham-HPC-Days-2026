---
layout: splash
title: "Tutorials"
permalink: /tutorials/
classes: wide

---
<style>
.parallax-hero {
  width: 100vw;
  margin-left: calc(50% - 50vw);
  margin-right: calc(50% - 50vw);

  height: 50vh;
  background-image: url("https://github.com/hpc-days/Durham-HPC-Days-2026/blob/main/assets/images/Banner-darker.png?raw=true");
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;

  display: flex;
  align-items: center;
  justify-content: center;
  background-position: 50% 100%; 
}


.parallax-hero h1 {
  font-size: 4rem;
  color:white;
  margin: 0;
}

.tutorials-description {
  max-width: 900px;
  margin: 2rem auto;
  font-size: 1.15rem;
  text-align: center;
  color: #333;
}

/* ===== Grid & Cards ===== */
.about-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 1.5rem;
  margin: 3rem auto;
}

.about-card {
  background: #fff;
  border-top: 4px solid #68246D;
  border-radius: 12px;
  padding: 1.5rem;
  text-align: left;
  box-shadow: 0 10px 25px rgba(0,0,0,0.08);
  display: flex;
  flex-direction: column;
  transition: transform 0.25s ease, box-shadow 0.25s ease;
  min-height: 220px;
}

.about-card:hover {
  transform: translateY(-6px);
  box-shadow: 0 18px 40px rgba(0,0,0,0.12);
}

.card-title {
  font-size: 1.25rem;
  color: #68246D;
  margin-bottom: 0.5rem;
}

.card-meta {
  display: flex;
  flex-direction: column; 
  gap: 0.2rem;
  font-size: 0.95rem;
  color: #555;
  margin-bottom: 1rem;
}

.card-meta span {
  font-weight: 600;
  margin-right: 0.3rem;
}

.card-description {
  font-size: 0.95rem;
  color: #555;
  margin-bottom: 1rem;
  flex-grow: 1;
}

.about-button {
  margin-top: auto;
  padding: 0.5rem 1.2rem;
  background: #68246D;
  color: white !important;
  border-radius: 999px;
  text-decoration: none;
  font-weight: 600;
  font-size: 0.9rem;
  transition: background 0.2s ease, transform 0.2s ease;
}

.about-button:hover {
  background: #4e1a53;
  transform: scale(1.05);
}


@media (max-width: 768px) {
  .parallax-hero {
    background-attachment: scroll; 
    background-position: center top; 
    height: 40vh;                  
  }
}


</style>

<section class="parallax-hero">
  <h1>Tutorials</h1>
</section>

<section class="tutorials-description">
  <p>
    Welcome to the Durham HPC Days 2026 tutorials. These sessions provide hands-on learning 
    with HPC tools, performance optimisation techniques, and cutting-edge research workflows.  
    Click on any tutorial below to see details, lecturers, institutions, and requirements.
  </p>
</section>

<section class="about-grid">
  {% assign tutorials = site.programme | where: "category", "Tutorial" | sort: "title" %}
  {% for tutorial in tutorials %}
    <div class="about-card">
      <div class="card-title">{{ tutorial.title }}</div>
      <a href="{{ tutorial.url | relative_url }}" class="about-button">View Tutorial</a>
    </div>
  {% endfor %}
</section>

