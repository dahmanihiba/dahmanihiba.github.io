---
permalink: /
title: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
.about-page {
  font-size: 1.02rem;
  line-height: 1.75;
}

.about-section {
  margin: 1.5rem 0;
  padding: 1.45rem;
  border: 1px solid #e2e8f0;
  border-radius: 14px;
  background: #f8fafc;
  color: #334155;
  box-shadow: 0 5px 18px rgba(15, 23, 42, 0.06);
}

.about-section h2 {
  margin: 0 0 0.9rem;
  color: #1e293b;
  font-size: 1.3rem;
}

.about-section p {
  margin: 0 0 1rem;
  color: #334155;
}

.about-section p:last-child {
  margin-bottom: 0;
}

.about-section strong {
  color: #1e293b;
  font-weight: 650;
}

.about-section a {
  color: #2563a6;
  font-weight: 600;
  text-decoration: none;
  text-underline-offset: 0.2em;
}

.about-section a:hover {
  text-decoration: underline;
}

.about-me {
  border-top: 4px solid #2563a6;
}

.research-interests {
  border-top: 4px solid #7c5cc4;
}

.background {
  border-top: 4px solid #2f855a;
}

.fun-part {
  border-top: 4px solid #d69e2e;
  background: #fffaf0;
}

.research-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.55rem;
  margin-top: 1.15rem;
}

.research-tag {
  display: inline-flex;
  align-items: center;
  padding: 0.38rem 0.75rem;
  border: 1px solid #cbd5e1;
  border-radius: 999px;
  background: #eef4f8;
  color: #1e293b;
  font-size: 0.84rem;
  font-weight: 600;
  line-height: 1.35;
}

/* Dark mode used by common Academic Pages themes */
html[data-theme="dark"] .about-section,
html.dark .about-section,
body.dark .about-section {
  border-color: #3b4652;
  background: #1e252c;
  color: #d6dde5;
  box-shadow: 0 5px 18px rgba(0, 0, 0, 0.28);
}

html[data-theme="dark"] .about-section h2,
html.dark .about-section h2,
body.dark .about-section h2,
html[data-theme="dark"] .about-section strong,
html.dark .about-section strong,
body.dark .about-section strong {
  color: #f1f5f9;
}

html[data-theme="dark"] .about-section p,
html.dark .about-section p,
body.dark .about-section p {
  color: #d6dde5;
}

html[data-theme="dark"] .about-section a,
html.dark .about-section a,
body.dark .about-section a {
  color: #79b8e8;
}

html[data-theme="dark"] .research-tag,
html.dark .research-tag,
body.dark .research-tag {
  border-color: #4b5f72;
  background: #263746;
  color: #f1f5f9;
}

html[data-theme="dark"] .about-me,
html.dark .about-me,
body.dark .about-me {
  border-top-color: #79b8e8;
}

html[data-theme="dark"] .research-interests,
html.dark .research-interests,
body.dark .research-interests {
  border-top-color: #b6a0e8;
}

html[data-theme="dark"] .background,
html.dark .background,
body.dark .background {
  border-top-color: #72c79a;
}

html[data-theme="dark"] .fun-part,
html.dark .fun-part,
body.dark .fun-part {
  border-top-color: #e8bd63;
  background: #302b1e;
}

/* Operating-system dark mode fallback */
@media (prefers-color-scheme: dark) {
  .about-section {
    border-color: #3b4652;
    background: #1e252c;
    color: #d6dde5;
    box-shadow: 0 5px 18px rgba(0, 0, 0, 0.28);
  }

  .about-section h2,
  .about-section strong {
    color: #f1f5f9;
  }

  .about-section p {
    color: #d6dde5;
  }

  .about-section a {
    color: #79b8e8;
  }

  .research-tag {
    border-color: #4b5f72;
    background: #263746;
    color: #f1f5f9;
  }

  .about-me {
    border-top-color: #79b8e8;
  }

  .research-interests {
    border-top-color: #b6a0e8;
  }

  .background {
    border-top-color: #72c79a;
  }

  .fun-part {
    border-top-color: #e8bd63;
    background: #302b1e;
  }
}

@media (max-width: 600px) {
  .about-page {
    font-size: 1rem;
  }

  .about-section {
    padding: 1.1rem;
  }

  .research-tags {
    gap: 0.45rem;
  }

  .research-tag {
    font-size: 0.8rem;
  }
}
</style>

<div class="about-page">

  <section class="about-section about-me">

    <h2>About me</h2>

    <p>
      Hi! I am <strong>Hiba Dahmani</strong>, a third-year PhD candidate
      in Computer Vision at
      <a href="https://www.huawei.com/en/"
         target="_blank"
         rel="noopener noreferrer">
        Huawei Paris Research Center
      </a>
      and
      <a href="https://www.univ-gustave-eiffel.fr/en/"
         target="_blank"
         rel="noopener noreferrer">
        COSYS, Gustave Eiffel University
      </a>,
      based in Paris, France.
    </p>

    <p>
      I work at the intersection of
      <strong>3D computer vision</strong>,
      <strong>computer graphics</strong>, and
      <strong>generative AI</strong>.
      My goal is to develop practical and scalable methods for understanding,
      reconstructing, and generating complex 3D environments.
    </p>

  </section>


  <section class="about-section research-interests">

    <h2>Research interests</h2>

    <p>
      My research focuses on large-scale 3D scene reconstruction and
      generation. I am particularly interested in methods that improve
      geometric consistency, visual fidelity, and computational efficiency
      when modelling real-world environments.
    </p>

    <p>
      My current work explores neural scene representations, diffusion-based
      generation, appearance modelling, semantic scene synthesis, and
      efficient novel-view rendering, with applications to autonomous
      driving and large-scale outdoor environments.
    </p>

    <div class="research-tags">
      <span class="research-tag">3D Computer Vision</span>
      <span class="research-tag">3D Scene Reconstruction</span>
      <span class="research-tag">Generative AI</span>
      <span class="research-tag">Diffusion Models</span>
      <span class="research-tag">3D Gaussian Splatting</span>
      <span class="research-tag">Neural Rendering</span>
      <span class="research-tag">Scene Generation</span>
    </div>

  </section>


  <section class="about-section background">

    <h2>Background</h2>

    <p>
      Before starting my PhD, I completed the
      <strong>M2 Mathematics, Vision and Learning (MVA)</strong>
      programme at
      <a href="https://www.ens-paris-saclay.fr/en"
         target="_blank"
         rel="noopener noreferrer">
        ENS Paris-Saclay
      </a>.
    </p>

    <p>
      I also earned an <strong> engineering degree </strong> from
      <a href="https://www.telecom-paris.fr/en"
         target="_blank"
         rel="noopener noreferrer">
        Télécom Paris
      </a>,
      where I specialised in <strong>machine learning, computer vision,</strong>
    </p>

  </section>


  <section class="about-section fun-part">

    <h2>Beyond research</h2>

    <p>
      Outside the lab, I enjoy movies, running, and football. I also continue testing the hypothesis that every
      difficult research problem can be solved with one more cup of
      coffee. ☕
    </p>

  </section>

</div>