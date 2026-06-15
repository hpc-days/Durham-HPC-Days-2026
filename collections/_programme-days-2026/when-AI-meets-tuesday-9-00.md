```yaml
---
# ============================================================
# TALKS
# ============================================================

title: "Science & AI"

hybrid: "https://events.teams.microsoft.com/event/f39ee0fc-f056-42a7-9dba-52cd2752c650@7250d88b-4b68-4529-be44-d59a2d8a6f94"

# -------------------------
# FACILITATORS
facilitator: "Fawada Qaiser, Jeyan Thiyagalingam"

facilitator_photos:
  - "assets/images/generic.jpg"
  - "assets/images/generic.jpg"

facilitator_links:
  - ""
  - ""

# -------------------------
# TALKS (morning session)
contributor: "Daniele Sorini, Gavin Leroy, Craig Bower, Fawad Qaiser"

contributor_photos:
  - "assets/images/generic.jpg"
  - "assets/images/generic.jpg"
  - "assets/images/generic.jpg"
  - "assets/images/generic.jpg"

contributor_links:
  - ""
  - ""
  - ""
  - ""

# -------------------------
# AFFILIATION
institution: ""
institution_logo: ""
institution_link: ""

organiser: ""
organiser_logo: ""
organiser_link: ""

supported: ""
supported_logo: ""
supported_link: ""

# -------------------------
# DESCRIPTION

description: "
<b>Session Part 1 (Tuesday 16 Jun, 09:00 - 10:30)</b><br><br>

## Linking galaxy properties to halo gas density profiles with interpretable machine learning

**Daniele Sorini**

Stellar and AGN feedback shape the distribution of gas from galaxies out to the intergalactic medium, but how this connects to galaxy properties remains uncertain. In this talk, I present a random forest algorithm that predicts the radial gas density profile within haloes from global properties of the central galaxy, including gas and stellar mass, star formation rate, and black hole mass and accretion rate. The model is trained on cosmological hydrodynamical simulations (EAGLE, IllustrisTNG, and Simba) and accurately recovers the simulated gas density profiles across a wide range of halo masses and redshifts. I will show how the predictions can be interpreted using statistical tools, including Sobol sensitivity analysis, to identify which galaxy properties are most closely linked to the gas distribution and what this reveals about feedback physics.

---

## Spotting the Giants: Finding Galaxy Clusters in Noisy Weak-Lensing Convergence Maps

**Gavin Leroy**

Galaxy clusters are among the most massive bound structures in the Universe and are key probes of cosmology and large-scale structure formation. In weak gravitational lensing surveys, they can appear as localized features in convergence maps. However, their detection is complicated by projection effects, shape noise, filtering choices, and the intrinsically non-Gaussian structure of the cosmic matter field.

In this work, we investigate supervised machine-learning approaches for detecting galaxy clusters in filtered convergence maps. Motivated by the fact that clusters correspond to rare, localized departures from the surrounding lensing field, we frame the problem physically as the identification of anomalous cluster-like structures embedded in a complex, noisy background. We compare convolutional U-Net-based models and Vision Transformer approaches for predicting cluster-sensitive maps from which candidate detections are extracted.

This study explores how modern deep-learning architectures can exploit spatial and statistical information in weak-lensing convergence maps while maintaining a clear connection to the underlying physical problem of cluster detection.

---

## Trustworthy Digital Twins of AREPO AGN-Jet Simulations: Continuous, Physics-Enforced Neural-Field Emulation with Adaptive Conformal Uncertainty

**Craig Bower**

AGN jets are among the most powerful regulators in the Universe, yet each high-resolution AREPO simulation costs millions of core-hours, and every jet power demands a fresh run. We ask how close a fast, queryable emulator can come to a digital twin of these simulations, in Grieves' strict three-element sense.

Our virtual element is a continuous, physics-informed neural field mapping position, time, and Eddington ratio to the hydrodynamic fields. It is accurate on thermodynamic fields at jet powers never seen in training (Pearson r ≈ 0.89–0.99), enforces mass conservation and the equation of state by projection to near machine precision, and can be queried at any spatial resolution.

For the connection, we show that distribution-free conformal uncertainty collapses across jet power for one identifiable reason—the non-exchangeability of the error scores—and that adaptive conformal inference, updated online from sparse truth, restores honest 90% coverage at both interpolation and extrapolation.

We close on what this does and does not establish as a digital twin, and where the same recipe transfers.

---

## From Automation to Autonomy: Agentic AI in HPC

**Dr Fawad Qaiser**

High-performance computing has automated many aspects of scientific research, yet researchers still spend substantial time coordinating workflows across simulations, data, models, schedulers, and analysis tools. As science becomes more distributed and heterogeneous, this orchestration burden is becoming a serious barrier to productivity and discovery.

This talk examines how agentic AI could move HPC from automation to autonomy by enabling workflows that can reason, plan, act, and adapt across multi-step scientific tasks. It outlines opportunities in simulation steering, adaptive exploration, hybrid simulation-AI pipelines, and tool orchestration, while addressing requirements for trust, provenance, reproducibility, and human oversight.

---

<b>Session Part 2 (Tuesday 16 Jun, 13:00 - 14:30)</b><br><br>

## Talk: AI and HPC Systems Perspective

**Prof Jeyan Thiyagalingam**

(A talk on HPC systems, AI acceleration, and scalable scientific computing — placeholder abstract can be refined if you provide full text)

---

## Panel Discussion: The Future of AI in Scientific Computing

**Moderator:** Dr Fawad Qaiser

**Panel Members:**
- Prof Jeyan Thiyagalingam
- Prof Mark Wilkinson
- Daniele Sorini
- Gavin Leroy
- Craig Bower

This 30-minute panel discussion brings together researchers working across scientific AI, cosmology, simulation, and HPC systems to discuss the future direction of AI in computational science. Topics include trustworthy AI, scientific machine learning, digital twins, agentic workflows, and the evolving role of HPC infrastructure in enabling next-generation discovery.
"
# -------------------------
# SCHEDULING (DO NOT TOUCH BELOW)

layout: talk
category: "talk"

day: "Tuesday"
track: "C"

start_time: "09:00"
end_time: "10:30"

day_1: "Tuesday"
start_time_1: "09:00"
end_time_1: "10:30"

day_1: "Tuesday"
start_time_2: "13:00"
end_time_2: "14:30"

room: "MJC2004"
---
```
