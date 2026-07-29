---
layout: archive
title: "News & Updates"
permalink: /news/
author_profile: true
---

<div class="news-intro">
  <p>
    Research milestones, publications, conferences, workshops, and other updates.
  </p>
</div>
<div class="news-timeline">

  <!-- June 2026 -->
  <article class="news-item featured">
    <div class="news-marker">
      <span>🎉</span>
    </div>

    <div class="news-card">
      <div class="news-meta">
        <time datetime="2026-06">June 2026</time>
        <span class="news-badge publication">Publication</span>
      </div>

      <h2>SEMROVER accepted to ECCV 2026</h2>

      <p>
        Our paper <strong>SEMROVER</strong> was accepted to the
        <em>European Conference on Computer Vision (ECCV 2026)</em>
      </p>
        <p class="news-location">
        📍 Malmö, Sweden.
      </p>
    </div>
  </article>

  <!-- November 2024 -->
  <article class="news-item">
    <div class="news-marker">
      <span>🇮🇹</span>
    </div>

    <div class="news-card">
      <div class="news-meta">
        <time datetime="2024-11">November 2024</time>
        <span class="news-badge conference">Conference</span>
      </div>

      <h2>Presented SWAG at ECCV 2024</h2>

      <p>
        Presented the <strong>SWAG</strong> poster at the
        <em>European Conference on Computer Vision (ECCV 2024)</em>
      </p>
        <p class="news-location">
        📍 Milan, Italy.
      </p>
    </div>
  </article>

  <!-- June 2024 -->
  <article class="news-item featured">
    <div class="news-marker">
      <span>🏆</span>
    </div>

    <div class="news-card">
      <div class="news-meta">
        <time datetime="2024-06">June 2024</time>
        <span class="news-badge publication">Publication</span>
      </div>

      <h2>SWAG accepted to ECCV 2024</h2>

      <p>
        Our paper <strong>SWAG</strong> was accepted to the
        <em>European Conference on Computer Vision (ECCV 2024)</em>.
      </p>
    </div>
  </article>

  <!--  June 2024 -->
  <article class="news-item">
    <div class="news-marker">
      <span>🎤</span>
    </div>

    <div class="news-card">
      <div class="news-meta">
        <time datetime="2024-06-12">12 June 2024</time>
        <span class="news-badge event">University</span>
      </div>

      <h2>Attend the ED MSTIC PhD Day</h2>

      <p>
        participate to the
        <em>ED MSTIC PhD Day (Journée des doctorants)</em>,
        Université Gustave Eiffel.
      </p>

      <p class="news-location">
        📍 Champs-sur-Marne, France
      </p>
    </div>
  </article>

  <!-- February 2024 -->
  <article class="news-item">
    <div class="news-marker">
      <span>🎓</span>
    </div>

    <div class="news-card">
      <div class="news-meta">
        <time datetime="2024-02">February 2024</time>
        <span class="news-badge phd">PhD</span>
      </div>

      <h2>Started my PhD ! </h2>

      <p>
        Began my PhD in Computer Vision at <strong> Huawei Paris Research Center </strong>
        and <strong> Université Gustave Eiffel</strong>, focusing on
        3D scene reconstruction and generation under the supervision of : <strong> Nathan Piasco </strong> (Huawei),<strong> Roland Bremond </strong> (COSYS, Gustave Eiffel University), <strong> Laurent Caraffa </strong> (LASTIG,IGN-ENSG, Gustave Eiffel University), <strong> Jean-Philippe Tarel </strong> (COSYS, Gustave Eiffel University).
      </p>
        <p class="news-location">
        📍 Boulogne Billancourt, France
      </p>
    </div>
  </article>

  <!-- September 2023 -->
  <article class="news-item">
    <div class="news-marker">
      <span>🎓</span>
    </div>

    <div class="news-card">
      <div class="news-meta">
        <time datetime="2023-09">September 2023</time>
        <span class="news-badge education">Graduation</span>
      </div>

      <h2>Graduated from Télécom Paris</h2>

      <p>
        Graduated with an
        <strong>Engineering Degree</strong> from Télécom Paris and
        the <strong>Master MVA (Mathematics, Vision and Learning)</strong>.
      </p>
        <p class="news-location">
        📍 Palaiseau, France
      </p>
    </div>
  </article>

  <!-- April 2023 -->
  <article class="news-item">
    <div class="news-marker">
      <span>💼</span>
    </div>

    <div class="news-card">
      <div class="news-meta">
        <time datetime="2023-04">April 2023</time>
        <span class="news-badge internship">Internship</span>
      </div>

      <h2>Joined Dassault Systèmes as a Research Intern</h2>

      <p>
        Started a research internship at
        <strong>Dassault Systèmes</strong>, working on
        generative AI methods for <strong>3D CAD generation</strong>.
      </p>
        <p class="news-location">
        📍 Vélizy-Villacoublay, France
      </p>
    </div>
  </article>

</div>

<style>
.news-intro {
  max-width: 760px;
  margin: 0 0 2.5rem;
  color: #64748b;
  font-size: 1.05rem;
  line-height: 1.75;
}

.news-timeline {
  position: relative;
  max-width: 860px;
  margin: 0 auto;
  padding: 0.5rem 0 1rem;
}

/* Vertical timeline line */
.news-timeline::before {
  content: "";
  position: absolute;
  top: 0;
  bottom: 0;
  left: 27px;
  width: 3px;
  border-radius: 999px;
  background: linear-gradient(
    to bottom,
    #8b5cf6,
    #ec4899,
    rgba(139, 92, 246, 0.12)
  );
}

.news-item {
  position: relative;
  display: grid;
  grid-template-columns: 56px minmax(0, 1fr);
  gap: 1.25rem;
  margin-bottom: 1.75rem;
}

.news-marker {
  position: relative;
  z-index: 2;
  display: flex;
  align-items: flex-start;
  justify-content: center;
  padding-top: 1.15rem;
}

.news-marker span {
  display: grid;
  place-items: center;
  width: 44px;
  height: 44px;
  border: 4px solid #ffffff;
  border-radius: 50%;
  background: linear-gradient(135deg, #7c3aed, #ec4899);
  box-shadow:
    0 5px 18px rgba(124, 58, 237, 0.24),
    0 0 0 1px rgba(124, 58, 237, 0.1);
  font-size: 1.15rem;
}

.news-card {
  position: relative;
  overflow: hidden;
  padding: 1.35rem 1.5rem;
  border: 1px solid rgba(148, 163, 184, 0.25);
  border-radius: 18px;
  background:
    linear-gradient(
      135deg,
      rgba(139, 92, 246, 0.055),
      rgba(236, 72, 153, 0.025)
    ),
    #ffffff;
  box-shadow: 0 8px 28px rgba(15, 23, 42, 0.07);
  transition:
    transform 180ms ease,
    border-color 180ms ease,
    box-shadow 180ms ease;
}

.news-card::before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 5px;
  height: 100%;
  background: linear-gradient(to bottom, #8b5cf6, #ec4899);
  opacity: 0.85;
}

.news-card:hover {
  transform: translateY(-3px);
  border-color: rgba(139, 92, 246, 0.38);
  box-shadow: 0 15px 38px rgba(15, 23, 42, 0.11);
}

.news-item.featured .news-card {
  border-color: rgba(139, 92, 246, 0.38);
  background:
    linear-gradient(
      135deg,
      rgba(139, 92, 246, 0.11),
      rgba(236, 72, 153, 0.06)
    ),
    #ffffff;
}

.news-meta {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  gap: 0.65rem;
  margin-bottom: 0.65rem;
}

.news-meta time {
  color: #7c3aed;
  font-size: 0.82rem;
  font-weight: 700;
  letter-spacing: 0.045em;
  text-transform: uppercase;
}

.news-card h2 {
  margin: 0 0 0.55rem;
  color: #172033;
  font-size: 1.2rem;
  line-height: 1.35;
}

.news-card p {
  margin: 0;
  color: #526176;
  font-size: 0.98rem;
  line-height: 1.7;
}

.news-badge {
  display: inline-flex;
  align-items: center;
  padding: 0.28rem 0.65rem;
  border-radius: 999px;
  font-size: 0.72rem;
  font-weight: 700;
  letter-spacing: 0.025em;
}

.news-badge.publication {
  color: #6d28d9;
  background: rgba(139, 92, 246, 0.13);
}

.news-badge.event {
  color: #0369a1;
  background: rgba(14, 165, 233, 0.13);
}

.news-badge.workshop {
  color: #be185d;
  background: rgba(236, 72, 153, 0.13);
}

.news-link {
  display: inline-flex;
  align-items: center;
  gap: 0.35rem;
  margin-top: 0.9rem;
  color: #7c3aed;
  font-weight: 650;
  text-decoration: none;
}

.news-link:hover {
  text-decoration: underline;
}

/* Dark mode */
html[data-theme="dark"] .news-intro {
  color: #a9b4c5;
}

html[data-theme="dark"] .news-marker span {
  border-color: #1b1f27;
}

html[data-theme="dark"] .news-card {
  border-color: rgba(148, 163, 184, 0.2);
  background:
    linear-gradient(
      135deg,
      rgba(139, 92, 246, 0.13),
      rgba(236, 72, 153, 0.06)
    ),
    #20242d;
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.22);
}

html[data-theme="dark"] .news-item.featured .news-card {
  border-color: rgba(167, 139, 250, 0.42);
  background:
    linear-gradient(
      135deg,
      rgba(139, 92, 246, 0.2),
      rgba(236, 72, 153, 0.1)
    ),
    #20242d;
}

html[data-theme="dark"] .news-card:hover {
  border-color: rgba(167, 139, 250, 0.55);
  box-shadow: 0 15px 38px rgba(0, 0, 0, 0.32);
}

html[data-theme="dark"] .news-card h2 {
  color: #f1f5f9;
}

html[data-theme="dark"] .news-card p {
  color: #b8c1cf;
}

html[data-theme="dark"] .news-meta time,
html[data-theme="dark"] .news-link {
  color: #c4b5fd;
}

/* Mobile */
@media (max-width: 600px) {
  .news-timeline::before {
    left: 20px;
  }

  .news-item {
    grid-template-columns: 42px minmax(0, 1fr);
    gap: 0.8rem;
    margin-bottom: 1.25rem;
  }

  .news-marker {
    padding-top: 1rem;
  }

  .news-marker span {
    width: 36px;
    height: 36px;
    border-width: 3px;
    font-size: 0.95rem;
  }

  .news-card {
    padding: 1.15rem 1.1rem 1.15rem 1.25rem;
    border-radius: 15px;
  }

  .news-card h2 {
    font-size: 1.08rem;
  }
}
.news-badge.phd {
  color: #047857;
  background: rgba(16, 185, 129, 0.13);
}

.news-badge.conference {
  color: #0369a1;
  background: rgba(14, 165, 233, 0.13);
}

.news-location {
  margin-top: 0.7rem !important;
  color: #64748b !important;
  font-size: 0.88rem !important;
}
.news-badge.phd {
  color: #047857;
  background: rgba(16, 185, 129, 0.13);
}

.news-badge.education {
  color: #7c3aed;
  background: rgba(124, 58, 237, 0.13);
}

.news-badge.internship {
  color: #b45309;
  background: rgba(245, 158, 11, 0.15);
}

.news-badge.conference {
  color: #0369a1;
  background: rgba(14, 165, 233, 0.13);
}

.news-location {
  margin-top: 0.7rem !important;
  color: #64748b !important;
  font-size: 0.9rem !important;
}
</style>