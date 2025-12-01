---
layout: default
title: Register
permalink: /register/
---

<style>
.parallax-hero {
  width: 100vw;
  margin-left: calc(50% - 50vw);
  height: 50vh;
  background-image: url('/assets/images/cathedral-cartoon.png');
  background-attachment: fixed;
  background-position: 50% 40%;
  background-repeat: no-repeat;
  background-size: cover;
  display: flex;
  align-items: center;
  justify-content: center;
}

.parallax-overlay {
  background: linear-gradient(rgba(104,36,109,0.85), rgba(70,20,75,0.85));
  color: white;
  padding: 2rem 20rem;
  text-align: center;
  border-radius: 14px;
  box-shadow: 0 15px 40px rgba(0,0,0,0.40);
}

.parallax-overlay h1 {
  font-size: 4rem;
  margin-bottom: 0.5rem;
}

.parallax-overlay p {
  font-size: 1.3rem;
  opacity: 0.95;
}


/* REGISTER CARD */
.card-highlight {
  background: white;
  padding: 2.5rem;
  border-left: 6px solid #68246D;
  border-radius: 12px;
  box-shadow: 0 12px 30px rgba(0,0,0,0.08);
  margin: 3rem auto;
  max-width: 1500px;
  width: 90%;
  text-align: center;
}

.card-highlight h2 {
  margin-bottom: 0.8rem;
}

.register-button {
  display: inline-block;
  margin-top: 1.5rem;
  padding: 0.9rem 2.2rem;
  background: #68246D;
  color: white !important;
  border-radius: 999px;
  text-decoration: none;
  font-weight: 600;
  font-size: 1rem;
  transition: background 0.2s ease, transform 0.2s ease;
}

.register-button:hover {
  background: #4e1a53;
  transform: scale(1.05);
}

.small-text {
  font-size: 0.85rem;
  color: #666;
  margin-top: 1rem;
}


/* CONTENT */
.section-register {
  max-width: 1200px;
  margin: auto;
  padding: 3rem 2rem;
}

.section-register h2 {
  margin-top: 1rem;
  font-size: 2rem;
}


/* CHECKLIST */
ul.checklist {
  list-style: none;
  padding: 0;
}

ul.checklist li {
  padding-left: 1.8rem;
  margin-bottom: 0.7rem;
  position: relative;
}

ul.checklist li::before {
  content: "✓";
  position: absolute;
  left: 0;
  color: #68246D;
  font-weight: bold;
}


/* INFO CENTRED BLOCK */
.info-centred {
  max-width: 720px;
  margin: 3rem auto;
  text-align: left;
}

.info-centred h2 {
  text-align: center;
}

.info-centred ul {
  padding-left: 1.2rem;
}


/* MOBILE */
@media (max-width: 768px) {

  .parallax-overlay {
    padding: 2rem;
    width: 95%;
  }

  .parallax-overlay h1 {
    font-size: 2.5rem;
  }

  .parallax-overlay p {
    font-size: 1.2rem;
  }

  .card-highlight {
    padding: 2.2rem;
  }

  .card-highlight h2 {
    font-size: 1.9rem;
  }

  .section-register {
    padding: 2rem 1.2rem;
  }

}

@media (max-width: 768px) {
  .parallax-overlay {
    padding: 2rem;
    width: 95%;
  }

  .parallax-overlay h1 {
    font-size: 2.5rem;
  }

  .parallax-overlay p {
    font-size: 1.2rem;
  }

  .card-highlight {
    padding: 2.5rem 2rem;
  }

  .card-highlight h2 {
    font-size: 1.9rem;
  }
}


</style>


<section class="parallax-hero">
  <div class="parallax-overlay">
    <h1>Register</h1>
    <p>Durham HPC Days 2026</p>
  </div>
</section>


<section class="section-register">
  <div class="card-highlight">
    <h2>Registration is now open</h2>
    <p>
      Secure your place at <strong>Durham HPC Days 2026</strong>, a leading UK event
      in High Performance Computing, hosted at Durham University.
    </p>

    <a class="register-button"
       href="https://pay.durham.ac.uk/event-durham/durham-hpc-days-2026"
       target="_blank" rel="noopener">
       Register Now
    </a>

    <p class="small-text">
      You will be redirected to the official Durham University registration system.
    </p>
  </div>

<div class="info-centred">

  <h2>Why attend?</h2>
  <ul class="checklist">
    <li>Keynotes by leading HPC researchers and practitioners</li>
    <li>Hands-on sessions and tutorials </li>
    <li>Networking with industry and academic experts</li>
    <li>Insights into modern HPC infrastructure and workflows</li>
    <li>Opportunities for collaboration and knowledge exchange</li>
  </ul>


  <h2>Important information</h2>
  <ul>
    <li>Places are limited — early registration is strongly recommended.</li>
    <li>Please get in touch if you have any questions.</li>
  </ul>
 </div>

</section>

