---
layout: archive
title: "Work Experience"
permalink: /experience/
author_profile: true
---

<div class="timeline-intro">
  <p>
    Research experience in computer vision, deep learning, generative modelling,
    and structured 3D representations.
  </p>
</div>
<!-- Huawei Paris Research Center -->
<article class="career-item featured">
  <div class="career-marker">
    <span>📡</span>
  </div>

  <div class="career-card">
    <div class="career-meta">
      <time datetime="2023-11">November 2023 – Present</time>
      <span class="career-badge phd">PhD Researcher</span>
    </div>

    <h2>PhD Researcher</h2>

    <h3>Huawei Paris Research Center</h3>

    <p class="career-topic">
       3D scene generation and reconstruction
    </p>

    <ul class="career-details">
      <li>
        Researching scalable 3D scene generation using diffusion models,
        neural rendering, and 3D representations.
      </li>

      <li>
        Developing generative methods for autonomous driving and
        large-scale outdoor environments.
      </li>

      <li>
        Designing efficient representations for high-fidelity
        scene reconstruction and novel view synthesis.
      </li>

      <li>
        Collaborating with Huawei researchers and academic partners,
        resulting in publications at top-tier computer vision conferences.
      </li>
    </ul>

    <div class="career-tags">
      <span>Computer Vision</span>
      <span>Diffusion Models</span>
      <span>Neural Rendering</span>
      <span>3D Scene Generation</span>
      <span>Autonomous Driving</span>
    </div>
  </div>
</article>
  <!-- Dassault Systèmes -->
  <article class="career-item featured">
    <div class="career-marker">
      <span>🏢</span>
    </div>

    <div class="career-card">
      <div class="career-meta">
        <time datetime="2023-04">April 2023 – September 2023</time>
        <span class="career-badge internship">Research Internship</span>
      </div>

      <h2>Research Engineer Intern</h2>

      <h3>Dassault Systèmes</h3>

      <p class="career-topic">
        Deep learning for exact and structured 3D modelling
      </p>

      <ul class="career-details">
        <li>
          Studied neural-network approaches for CAD models.
        </li>

        <li>
          Preprocessed structured datasets containing exact geometric
          representations.
        </li>

        <li>
          Designed a learning architecture for generating exact 3D geometries.
        </li>
      </ul>

      <div class="career-tags">
        <span>Deep Learning</span>
        <span>3D CAD</span>
        <span>Generative Modelling</span>
        <span>Exact Geometry</span>
      </div>
    </div>
  </article>

  <!-- Udini / DeepSmile Lab -->
  <article class="career-item">
    <div class="career-marker">
      <span>🦷</span>
    </div>

    <div class="career-card">
      <div class="career-meta">
        <time datetime="2021-06">June 2021 – August 2021</time>
        <span class="career-badge internship">Research Internship</span>
      </div>

      <h2>Computer Vision Research Intern</h2>

      <h3>Udini / DeepSmile Lab</h3>

      <p class="career-topic">
        Graph neural networks for analysing intra-oral 3D scans
      </p>

      <ul class="career-details">
        <li>
          Investigated graph neural network models for processing dental
          geometry.
        </li>

        <li>
          Worked with intra-oral 3D scans and graph-based geometric
          representations.
        </li>

        <li>
          Explored computer-vision methods for analysing structured medical 3D
          data.
        </li>
      </ul>

      <div class="career-tags">
        <span>Computer Vision</span>
        <span>Graph Neural Networks</span>
        <span>3D Scans</span>
        <span>Geometric Deep Learning</span>
      </div>
    </div>
  </article>



<style>
.timeline-intro {
  max-width: 760px;
  margin: 0 0 2.5rem;
  color: #64748b;
  font-size: 1.05rem;
  line-height: 1.75;
}

.career-timeline {
  position: relative;
  max-width: 880px;
  margin: 0 auto;
  padding: 0.5rem 0 1rem;
}

.career-timeline::before {
  content: "";
  position: absolute;
  top: 0;
  bottom: 0;
  left: 27px;
  width: 3px;
  border-radius: 999px;
  background: linear-gradient(
    to bottom,
    #2563eb,
    #8b5cf6,
    rgba(139, 92, 246, 0.12)
  );
}

.career-item {
  position: relative;
  display: grid;
  grid-template-columns: 56px minmax(0, 1fr);
  gap: 1.25rem;
  margin-bottom: 1.8rem;
}

.career-marker {
  position: relative;
  z-index: 2;
  display: flex;
  justify-content: center;
  padding-top: 1.15rem;
}

.career-marker span {
  display: grid;
  place-items: center;
  width: 44px;
  height: 44px;
  border: 4px solid #ffffff;
  border-radius: 50%;
  background: linear-gradient(135deg, #2563eb, #8b5cf6);
  box-shadow:
    0 6px 20px rgba(37, 99, 235, 0.22),
    0 0 0 1px rgba(37, 99, 235, 0.1);
  font-size: 1.15rem;
}

.career-card {
  position: relative;
  overflow: hidden;
  padding: 1.45rem 1.55rem;
  border: 1px solid rgba(148, 163, 184, 0.27);
  border-radius: 18px;
  background:
    linear-gradient(
      135deg,
      rgba(37, 99, 235, 0.055),
      rgba(139, 92, 246, 0.03)
    ),
    #ffffff;
  box-shadow: 0 8px 28px rgba(15, 23, 42, 0.07);
  transition:
    transform 180ms ease,
    border-color 180ms ease,
    box-shadow 180ms ease;
}

.career-card::before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 5px;
  height: 100%;
  background: linear-gradient(to bottom, #2563eb, #8b5cf6);
}

.career-card:hover {
  transform: translateY(-3px);
  border-color: rgba(37, 99, 235, 0.38);
  box-shadow: 0 15px 38px rgba(15, 23, 42, 0.11);
}

.career-item.featured .career-card {
  border-color: rgba(37, 99, 235, 0.38);
}

.career-meta {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  gap: 0.65rem;
  margin-bottom: 0.7rem;
}

.career-meta time {
  color: #2563eb;
  font-size: 0.82rem;
  font-weight: 700;
  letter-spacing: 0.045em;
  text-transform: uppercase;
}

.career-card h2 {
  margin: 0 0 0.2rem;
  color: #172033;
  font-size: 1.25rem;
  line-height: 1.35;
}

.career-card h3 {
  margin: 0 0 0.8rem;
  color: #7c3aed;
  font-size: 1rem;
  font-weight: 650;
}

.career-topic {
  margin: 0 0 0.9rem;
  color: #475569;
  font-weight: 600;
  line-height: 1.6;
}

.career-details {
  margin: 0.8rem 0 1rem;
  padding-left: 1.2rem;
}

.career-details li {
  margin-bottom: 0.45rem;
  color: #526176;
  line-height: 1.65;
}

.career-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.45rem;
  margin-top: 1rem;
}

.career-tags span {
  display: inline-flex;
  padding: 0.3rem 0.65rem;
  border-radius: 999px;
  color: #5b21b6;
  background: rgba(139, 92, 246, 0.11);
  font-size: 0.76rem;
  font-weight: 650;
}

.career-badge {
  display: inline-flex;
  padding: 0.28rem 0.65rem;
  border-radius: 999px;
  font-size: 0.72rem;
  font-weight: 700;
}

.career-badge.internship {
  color: #b45309;
  background: rgba(245, 158, 11, 0.15);
}

/* Dark mode */
html[data-theme="dark"] .timeline-intro {
  color: #a9b4c5;
}

html[data-theme="dark"] .career-marker span {
  border-color: #1b1f27;
}

html[data-theme="dark"] .career-card {
  border-color: rgba(148, 163, 184, 0.2);
  background:
    linear-gradient(
      135deg,
      rgba(37, 99, 235, 0.15),
      rgba(139, 92, 246, 0.08)
    ),
    #20242d;
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.22);
}

html[data-theme="dark"] .career-card h2 {
  color: #f1f5f9;
}

html[data-theme="dark"] .career-card h3,
html[data-theme="dark"] .career-meta time {
  color: #a5b4fc;
}

html[data-theme="dark"] .career-topic,
html[data-theme="dark"] .career-details li {
  color: #b8c1cf;
}

html[data-theme="dark"] .career-tags span {
  color: #ddd6fe;
  background: rgba(139, 92, 246, 0.2);
}

/* Mobile */
@media (max-width: 600px) {
  .career-timeline::before {
    left: 20px;
  }

  .career-item {
    grid-template-columns: 42px minmax(0, 1fr);
    gap: 0.8rem;
  }

  .career-marker span {
    width: 36px;
    height: 36px;
    border-width: 3px;
    font-size: 0.95rem;
  }

  .career-card {
    padding: 1.2rem 1.1rem 1.2rem 1.25rem;
    border-radius: 15px;
  }

  .career-card h2 {
    font-size: 1.1rem;
  }
}
</style>