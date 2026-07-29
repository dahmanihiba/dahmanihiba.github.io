---
layout: single
title: "Resume"
permalink: /Resume/
author_profile: true
---

<style>
.cv-page {
  margin-top: 0.5rem;
}

.cv-header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 1.5rem;
  margin-bottom: 1.5rem;
  padding: 1.25rem 1.4rem;
  border: 1px solid #e5e7eb;
  border-radius: 14px;
  background: #fafafa;
}

.cv-header-text h2 {
  margin: 0 0 0.35rem;
  font-size: 1.3rem;
}

.cv-header-text p {
  margin: 0;
  color: #666;
  font-size: 0.95rem;
}

.cv-actions {
  display: flex;
  flex-shrink: 0;
  gap: 0.65rem;
}

.cv-button {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  padding: 0.6rem 1rem;
  border-radius: 8px;
  font-size: 0.9rem;
  font-weight: 600;
  text-decoration: none !important;
  transition:
    transform 0.2s ease,
    box-shadow 0.2s ease,
    opacity 0.2s ease;
}

.cv-button:hover {
  transform: translateY(-2px);
  box-shadow: 0 5px 14px rgba(0, 0, 0, 0.12);
}

.cv-button-primary {
  background: #2f6f9f;
  color: #fff !important;
}

.cv-button-secondary {
  border: 1px solid #d1d5db;
  background: #fff;
  color: #333 !important;
}

.cv-viewer {
  overflow: hidden;
  width: 100%;
  height: 82vh;
  min-height: 720px;
  border: 1px solid #e5e7eb;
  border-radius: 14px;
  background: #f3f4f6;
  box-shadow: 0 8px 28px rgba(0, 0, 0, 0.08);
}

.cv-viewer iframe {
  display: block;
  width: 100%;
  height: 100%;
  border: 0;
}

.cv-mobile-message {
  display: none;
  padding: 2rem 1rem;
  text-align: center;
}

@media (max-width: 768px) {
  .cv-header {
    align-items: flex-start;
    flex-direction: column;
  }

  .cv-actions {
    width: 100%;
  }

  .cv-button {
    flex: 1;
  }

  .cv-viewer {
    height: 70vh;
    min-height: 520px;
  }
}

@media (max-width: 480px) {
  .cv-actions {
    flex-direction: column;
  }
}
</style>

<div class="cv-page">



  <div class="cv-viewer">

    <iframe
      src="{{ '/files/Hiba_Dahmani_CV.pdf' | relative_url }}#view=FitH"
      title="Hiba Dahmani Resume"
      loading="lazy">
    </iframe>

    <div class="cv-mobile-message">
      <p>Your browser cannot display the embedded PDF.</p>

      <a
        class="cv-button cv-button-primary"
        href="{{ '/files/Hiba_Dahmani_CV.pdf' | relative_url }}"
        target="_blank"
        rel="noopener">
        Open the CV
      </a>
    </div>

  </div>

</div>