---
layout: about
title: About
permalink: /
subtitle: PhD student, University of Georgia
profile: false
selected_papers: false
social: false
announcements:
  enabled: false
latest_posts:
  enabled: false
---

<style>
.personal-content{max-width:800px}.personal-content h2{font-size:1.35rem;font-weight:500;margin:2.1rem 0 .7rem}.personal-content p{line-height:1.8}.personal-note{border-left:2px solid var(--global-divider-color,#ddd);padding:.3rem 0 .3rem 1.1rem;color:var(--global-text-color-light,#777);font-size:.95rem}.personal-row{display:grid;grid-template-columns:145px 1fr;gap:1.5rem;padding:1.35rem 0;border-top:1px solid var(--global-divider-color,#ddd)}.personal-row h2,.personal-row h3{margin:0;font-size:1.05rem;font-weight:500}.personal-row p{margin:0;color:var(--global-text-color-light,#777);font-size:.95rem}.personal-about{display:grid;grid-template-columns:230px minmax(0,1fr);gap:2.5rem;align-items:start;margin-top:2rem}.personal-photo{width:100%;aspect-ratio:4/5;object-fit:cover;border-radius:2px}.personal-placeholder{display:flex;flex-direction:column;align-items:center;justify-content:center;border:1px solid var(--global-divider-color,#ddd);color:var(--global-text-color-light,#777);gap:.7rem}.personal-monogram{font-family:Georgia,serif;font-size:3rem;letter-spacing:.08em}.personal-placeholder small{font-size:.7rem;letter-spacing:.1em;text-transform:uppercase}.personal-affiliation{font-size:.8rem;color:var(--global-text-color-light,#777);line-height:1.7;margin-top:.85rem}.personal-bio p{line-height:1.9;margin-bottom:1.3rem}.personal-bio .personal-hello{font-size:1.12rem}.personal-links{display:flex;flex-wrap:wrap;gap:1.1rem;font-size:.9rem;margin-top:1.8rem}.personal-about-note{font-size:.9rem;color:var(--global-text-color-light,#777)}
@media(max-width:650px){.personal-about{grid-template-columns:150px minmax(0,1fr);gap:1.5rem}.personal-row{grid-template-columns:110px 1fr;gap:1rem}}
@media(max-width:480px){.personal-about{grid-template-columns:1fr;gap:1.6rem}.personal-portrait{max-width:190px}.personal-row{grid-template-columns:1fr;gap:.5rem}}
</style>

<div class="personal-about">
  <aside class="personal-portrait" aria-label="Portrait and affiliation">
    {% if site.data.personal.portrait and site.data.personal.portrait != "" %}
    <img class="personal-photo" src="{{ site.data.personal.portrait | prepend: '/assets/img/' | relative_url }}" alt="Portrait of Huixin Han" width="460" height="575" style="height: auto">
    {% else %}
    <div class="personal-photo personal-placeholder" role="img" aria-label="Portrait placeholder for Huixin Han"><span class="personal-monogram" aria-hidden="true">HH</span><small>Portrait to come</small></div>
    {% endif %}
    <p class="personal-affiliation">University of Georgia<br>PhD Candidate</p>
  </aside>
  <div class="personal-bio">
    <p class="personal-hello">I’m Huixin Han, a third-year PhD student at the University of Georgia, where I have the privilege of working with Dr. Elena Karahanna and Dr. Weifeng Li.</p>
    <p>My research interest is </p>
    <div class="personal-links">
      {% if site.data.personal.email and site.data.personal.email != "" %}<a href="mailto:{{ site.data.personal.email }}">Email</a>{% endif %}
      {% if site.data.personal.scholar_url and site.data.personal.scholar_url != "" %}<a href="{{ site.data.personal.scholar_url }}">Google Scholar</a>{% endif %}
      <a href="https://github.com/huixin-han">GitHub</a>
    </div>
  </div>
</div>
