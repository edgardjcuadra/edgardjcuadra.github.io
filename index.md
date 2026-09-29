---
layout: default
---
<div class="page">

  <section class="intro reveal">
    <img class="headshot" src="{{ '/images/headshot.jpg' | relative_url }}" alt="Portrait of Edgard J. Cuadra" width="80" height="80">
    <div>
      <h1>Edgard J. Cuadra</h1>
      <p class="tagline">Financial engineering, quantitative modeling, and machine learning for markets.</p>
      {% include social.html %}
    </div>
  </section>

  <section id="projects" class="section section-wide">
    <h2 class="label">Selected Projects</h2>
    <div class="projects">
      {% for project in site.data.projects %}
        {% include project.html p=project %}
      {% endfor %}
    </div>
  </section>

  <section id="about" class="section reveal">
    <h2 class="label">About</h2>
    <p>I am passionate about the Financial Services Sector. Constantly looking to apply technical mathemtatics through data science methods in multidisciplinary projects throughout my academic and personal endeavors. Ultimately a curious thinker and problem solver.</p>
    <p class="education">Lehigh University<br>
      Integrated Business and Engineering Honors Program<br>
      Industrial and Systems Engineering<br>
      Finance Double Major</p>
    <p><a href="https://ibe.lehigh.edu/welcome-lehighs-ibe-honors-program" target="_blank" rel="noopener">Read About Lehigh's Integrated Business and Engineering (IBE) Honors Program &#8599;</a></p>
  </section>

</div>
