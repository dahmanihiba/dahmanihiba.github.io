---
layout: archive
title: "Education"
permalink: /education/
author_profile: true
---



<div class="education-timeline">

  <!-- PhD -->
  <article class="education-item featured">
    <div class="education-marker">
      <span>🔬</span>
    </div>

    <div class="education-card">
      <div class="education-meta">
        <time datetime="2023">2023 – Present</time>
        <span class="education-badge phd">PhD</span>
      </div>

      <h2>PhD in Computer Vision</h2>

      <h3>
        Huawei Paris Research Center · COSYS · Université Gustave Eiffel
      </h3>

      <p class="education-highlight">
        Scalable 3D scene reconstruction and generation
      </p>

      <p>
        My research investigates neural 3D representations and generative
        models for constructing large-scale environments with improved
        geometric accuracy and rendering efficiency.
      </p>

      <div class="supervisors">
        <strong>Supervisors</strong>

        <ul>
          <li>Nathan Piasco — Huawei</li>
          <li>Roland Brémond — COSYS, Université Gustave Eiffel</li>
          <li>
            Laurent Caraffa — LASTIG, IGN-ENSG, Université Gustave Eiffel
          </li>
          <li>
            Jean-Philippe Tarel — COSYS, Université Gustave Eiffel
          </li>
        </ul>
      </div>

      <div class="education-tags">
        <span>Computer Vision</span>
        <span>Diffusion Models</span>
        <span>Neural Rendering</span>
        <span>3D Representations</span>
      </div>

      <p class="expected-date">
        Expected graduation: March 2027
      </p>
    </div>
  </article>

  <!-- MVA -->
  <article class="education-item">
    <div class="education-marker">
      <span>🧠</span>
    </div>

    <div class="education-card">
      <div class="education-meta">
        <time datetime="2022">2022 – 2023</time>
        <span class="education-badge master">Master's</span>
      </div>

      <h2>Master M2 MVA</h2>

      <h3>ENS Paris-Saclay</h3>

      <p class="education-highlight">
        Mathematics, Vision and Learning
      </p>

      <div class="course-section">
        <strong>Selected coursework</strong>

        <ul>
          <li>Optimisation</li>
          <li>Object Recognition and Computer Vision</li>
          <li>3D Computer Vision</li>
        </ul>
      </div>
    </div>
  </article>

  <!-- Télécom Paris -->
  <article class="education-item">
    <div class="education-marker">
      <span>🎓</span>
    </div>

    <div class="education-card">
      <div class="education-meta">
        <time datetime="2021">2021 – 2023</time>
        <span class="education-badge engineering">Engineering</span>
      </div>

      <h2>Engineering Degree</h2>

      <h3>Télécom Paris</h3>

      <div class="course-section">
        <strong>Selected coursework</strong>

        <ul>
          <li>Variational and Bayesian Methods</li>
          <li>Discrete Optimisation</li>
          <li>Convex Optimisation</li>
          <li>Graph Mining</li>
          <li>Machine Learning</li>
        </ul>
      </div>
    </div>
  </article>

  <!-- École Polytechnique de Tunisie -->
  <article class="education-item">
    <div class="education-marker">
      <span>⚙️</span>
    </div>

    <div class="education-card">
      <div class="education-meta">
        <time datetime="2019">2019 – 2021</time>
        <span class="education-badge engineering">Engineering</span>
      </div>

      <h2>Engineering Studies</h2>

      <h3>École Polytechnique de Tunisie</h3>

      <div class="course-section">
        <strong>Selected coursework</strong>

        <ul>
          <li>Mathematical Statistics and Probability</li>
          <li>Quantum Mechanics</li>
          <li>Signal Processing</li>
          <li>Scientific Computing</li>
          <li>Operations Research</li>
        </ul>
      </div>
    </div>
  </article>

  <!-- IPEST -->
  <article class="education-item">
    <div class="education-marker">
      <span>📐</span>
    </div>

    <div class="education-card">
      <div class="education-meta">
        <time datetime="2017">2017 – 2019</time>
        <span class="education-badge preparatory">Preparatory Classes</span>
      </div>

      <h2>Preparatory Classes — CPGE</h2>

      <h3>IPEST</h3>

      <p>
        Intensive preparatory studies in mathematics, physics, and engineering
        sciences.
      </p>
    </div>
  </article>

</div>

<style>
.education-intro {
  max-width: 760px;
  margin: 0 0 2.5rem;
  color: #64748b;
  font-size: 1.05rem;
  line-height: 1.75;
}

.education-timeline {
  position: relative;
  max-width: 880px;
  margin: 0 auto;
  padding: 0.5rem 0 1rem;
}

.education-timeline::before {
  content: "";
  position: absolute;
  top: 0;
  bottom: 0;
  left: 27px;
  width: 3px;
  border-radius: 999px;
  background: linear-gradient(
    to bottom,
    #7c3aed,
    #ec4899,
    rgba(124, 58, 237, 0.12)
  );
}

.education-item {
  position: relative;
  display: grid;
  grid-template-columns: 56px minmax(0, 1fr);
  gap: 1.25rem;
  margin-bottom: 1.8rem;
}

.education-marker {
  position: relative;
  z-index: 2;
  display: flex;
  justify-content: center;
  padding-top: 1.15rem;
}

.education-marker span {
  display: grid;
  place-items: center;
  width: 44px;
  height: 44px;
  border: 4px solid #ffffff;
  border-radius: 50%;
  background: linear-gradient(135deg, #7c3aed, #ec4899);
  box-shadow:
    0 6px 20px rgba(124, 58, 237, 0.22),
    0 0 0 1px rgba(124, 58, 237, 0.1);
  font-size: 1.15rem;
}

.education-card {
  position: relative;
  overflow: hidden;
  padding: 1.45rem 1.55rem;
  border: 1px solid rgba(148, 163, 184, 0.27);
  border-radius: 18px;
  background:
    linear-gradient(
      135deg,
      rgba(124, 58, 237, 0.055),
      rgba(236, 72, 153, 0.025)
    ),
    #ffffff;
  box-shadow: 0 8px 28px rgba(15, 23, 42, 0.07);
  transition:
    transform 180ms ease,
    border-color 180ms ease,
    box-shadow 180ms ease;
}

.education-card::before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 5px;
  height: 100%;
  background: linear-gradient(to bottom, #7c3aed, #ec4899);
}

.education-card:hover {
  transform: translateY(-3px);
  border-color: rgba(124, 58, 237, 0.4);
  box-shadow: 0 15px 38px rgba(15, 23, 42, 0.11);
}

.education-item.featured .education-card {
  border-color: rgba(124, 58, 237, 0.42);
}

.education-meta {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  gap: 0.65rem;
  margin-bottom: 0.7rem;
}

.education-meta time {
  color: #7c3aed;
  font-size: 0.82rem;
  font-weight: 700;
  letter-spacing: 0.045em;
  text-transform: uppercase;
}

.education-card h2 {
  margin: 0 0 0.2rem;
  color: #172033;
  font-size: 1.25rem;
  line-height: 1.35;
}

.education-card h3 {
  margin: 0 0 0.8rem;
  color: #be185d;
  font-size: 1rem;
  font-weight: 650;
  line-height: 1.5;
}

.education-card p,
.education-card li {
  color: #526176;
  line-height: 1.65;
}

.education-highlight {
  margin: 0 0 0.8rem;
  color: #475569 !important;
  font-weight: 650;
}

.course-section,
.supervisors {
  margin-top: 1rem;
}

.course-section strong,
.supervisors strong {
  color: #334155;
}

.course-section ul,
.supervisors ul {
  margin: 0.55rem 0 0;
  padding-left: 1.2rem;
}

.course-section li,
.supervisors li {
  margin-bottom: 0.35rem;
}

.education-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.45rem;
  margin-top: 1rem;
}

.education-tags span {
  display: inline-flex;
  padding: 0.3rem 0.65rem;
  border-radius: 999px;
  color: #6d28d9;
  background: rgba(139, 92, 246, 0.11);
  font-size: 0.76rem;
  font-weight: 650;
}

.expected-date {
  margin-top: 1rem !important;
  color: #7c3aed !important;
  font-size: 0.9rem;
  font-weight: 650;
}

.education-badge {
  display: inline-flex;
  padding: 0.28rem 0.65rem;
  border-radius: 999px;
  font-size: 0.72rem;
  font-weight: 700;
}

.education-badge.phd {
  color: #047857;
  background: rgba(16, 185, 129, 0.13);
}

.education-badge.master {
  color: #6d28d9;
  background: rgba(139, 92, 246, 0.13);
}

.education-badge.engineering {
  color: #0369a1;
  background: rgba(14, 165, 233, 0.13);
}

.education-badge.preparatory {
  color: #b45309;
  background: rgba(245, 158, 11, 0.15);
}

/* Dark mode */
html[data-theme="dark"] .education-intro {
  color: #a9b4c5;
}

html[data-theme="dark"] .education-marker span {
  border-color: #1b1f27;
}

html[data-theme="dark"] .education-card {
  border-color: rgba(148, 163, 184, 0.2);
  background:
    linear-gradient(
      135deg,
      rgba(124, 58, 237, 0.15),
      rgba(236, 72, 153, 0.07)
    ),
    #20242d;
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.22);
}

html[data-theme="dark"] .education-card h2 {
  color: #f1f5f9;
}

html[data-theme="dark"] .education-card h3 {
  color: #f9a8d4;
}

html[data-theme="dark"] .education-meta time,
html[data-theme="dark"] .expected-date {
  color: #c4b5fd !important;
}

html[data-theme="dark"] .education-card p,
html[data-theme="dark"] .education-card li,
html[data-theme="dark"] .education-highlight {
  color: #b8c1cf !important;
}

html[data-theme="dark"] .course-section strong,
html[data-theme="dark"] .supervisors strong {
  color: #e2e8f0;
}

html[data-theme="dark"] .education-tags span {
  color: #ddd6fe;
  background: rgba(139, 92, 246, 0.2);
}

/* Mobile */
@media (max-width: 600px) {
  .education-timeline::before {
    left: 20px;
  }

  .education-item {
    grid-template-columns: 42px minmax(0, 1fr);
    gap: 0.8rem;
  }

  .education-marker span {
    width: 36px;
    height: 36px;
    border-width: 3px;
    font-size: 0.95rem;
  }

  .education-card {
    padding: 1.2rem 1.1rem 1.2rem 1.25rem;
    border-radius: 15px;
  }

  .education-card h2 {
    font-size: 1.1rem;
  }
}
</style>