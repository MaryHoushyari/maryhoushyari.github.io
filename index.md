---
layout: page
permalink: /
toc: false
comments: false
---

<div class="landing container-fluid px-0">
  <div class="row align-items-center g-4 py-4">
    <div class="col-12 col-lg-8">
      <h1 class="landing-name dynamic-title mb-2">Maryam Houshyari</h1>

      <p class="landing-title text-muted fs-5 mb-3">
        Software Developer | Research Assistant at University of Alberta
      </p>

      <p class="landing-mission mb-3">
        I'm a Python backend developer with over five years of experience designing, building, and maintaining
        reliable web applications. My core expertise is in Django, Flask, and PostgreSQL, and I currently build
        serverless systems on AWS and apply Retrieval-Augmented Generation to create AI-assisted tools.
      </p>

      <ul class="landing-bullets mb-4">
        <li>Python backend development with Django &amp; Flask</li>
        <li>AWS Lambda &amp; serverless architectures</li>
        <li>PostgreSQL, MongoDB &amp; database design</li>
        <li>RAG pipelines &amp; applied generative AI</li>
        <li>REST &amp; GraphQL API design</li>
      </ul>

      <div class="d-flex flex-wrap align-items-stretch gap-2 mb-3" style="column-gap: 0.5rem !important;">
        <a class="btn btn-primary landing-btn" href="{{ '/assets/Maryam-Houshyari-Resume.pdf' | relative_url }}" target="_blank" rel="noopener">
          Download Resume
        </a>
        <a class="btn btn-outline-primary landing-btn" href="{{ '/professional-experience/' | relative_url }}">
          Professional Experience
        </a>
        <a class="btn btn-outline-primary landing-btn" href="{{ '/contact/' | relative_url }}">
          Contact Me
        </a>
      </div>

      <p class="landing-note text-muted">
        Thanks for stopping by — feel free to explore my experience, education, and projects.
      </p>
    </div>

    <div class="col-12 col-lg-4 text-center">
      <img src="{{ '/assets/images/profile.png' | relative_url }}" alt="Maryam Houshyari" class="landing-avatar img-fluid rounded-circle">
    </div>
  </div>

  <hr class="my-4"/>

  <div class="row g-4 pb-3">
    <div class="col-12 col-lg-4">
      <div class="landing-card card h-100">
        <div class="card-body">
          <h2 class="landing-card-title card-title h5">Professional Experience</h2>
          <p class="landing-card-text card-text">
            Backend development in Python/Django, AWS serverless systems, and an AI-powered course teaching
            assistant built with RAG.
          </p>
          <a class="landing-card-link" href="{{ '/professional-experience/' | relative_url }}">See experience →</a>
        </div>
      </div>
    </div>

    <div class="col-12 col-lg-4">
      <div class="landing-card card h-100">
        <div class="card-body">
          <h2 class="landing-card-title card-title h5">Education &amp; Certifications</h2>
          <p class="landing-card-text card-text">
            Electrical Engineering degree from the University of Tehran, plus certifications in generative AI
            and agentic AI development.
          </p>
          <a class="landing-card-link" href="{{ '/education/' | relative_url }}">See education →</a>
        </div>
      </div>
    </div>

    <div class="col-12 col-lg-4">
      <div class="landing-card card h-100">
        <div class="card-body">
          <h2 class="landing-card-title card-title h5">Open-source &amp; Code</h2>
          <p class="landing-card-text card-text">
            Explore my projects and contributions on GitHub.
          </p>
          <a class="landing-card-link" href="https://github.com/MaryHoushyari" target="_blank" rel="noopener">
            GitHub profile →
          </a>
        </div>
      </div>
    </div>
  </div>
</div>
