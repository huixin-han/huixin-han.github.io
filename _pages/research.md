---
layout: page
title: Research
permalink: /research/
description: "Down the Rabbit-Hole"
nav: true
nav_order: 1
---

<style>
.personal-content{max-width:800px}.personal-content h2{font-size:1.35rem;font-weight:500;margin:2.1rem 0 .7rem}.personal-content p{line-height:1.8}.personal-note{border-left:2px solid var(--global-divider-color,#ddd);padding:.3rem 0 .3rem 1.1rem;color:var(--global-text-color-light,#777);font-size:.95rem}.personal-row{display:grid;grid-template-columns:145px 1fr;gap:1.5rem;padding:1.35rem 0;border-top:1px solid var(--global-divider-color,#ddd)}.personal-row h2,.personal-row h3{margin:0;font-size:1.05rem;font-weight:500}.personal-row p{margin:0;color:var(--global-text-color-light,#777);font-size:.95rem}.personal-about{display:grid;grid-template-columns:230px minmax(0,1fr);gap:2.5rem;align-items:start;margin-top:2rem}.personal-photo{width:100%;aspect-ratio:4/5;object-fit:cover;border-radius:2px}.personal-placeholder{display:flex;flex-direction:column;align-items:center;justify-content:center;border:1px solid var(--global-divider-color,#ddd);color:var(--global-text-color-light,#777);gap:.7rem}.personal-monogram{font-family:Georgia,serif;font-size:3rem;letter-spacing:.08em}.personal-placeholder small{font-size:.7rem;letter-spacing:.1em;text-transform:uppercase}.personal-affiliation{font-size:.8rem;color:var(--global-text-color-light,#777);line-height:1.7;margin-top:.85rem}.personal-bio p{line-height:1.9;margin-bottom:1.3rem}.personal-bio .personal-hello{font-size:1.12rem}.personal-links{display:flex;flex-wrap:wrap;gap:1.1rem;font-size:.9rem;margin-top:1.8rem}.personal-about-note{font-size:.9rem;color:var(--global-text-color-light,#777)}
@media(max-width:650px){.personal-about{grid-template-columns:150px minmax(0,1fr);gap:1.5rem}.personal-row{grid-template-columns:110px 1fr;gap:1rem}}
@media(max-width:480px){.personal-about{grid-template-columns:1fr;gap:1.6rem}.personal-portrait{max-width:190px}.personal-row{grid-template-columns:1fr;gap:.5rem}}
</style>

<div class="personal-content" markdown="1">
Research questions, work in progress, and the papers that grow from them.

## Research agenda

A space to introduce the questions that guide my work, the ideas behind them, and the approaches I use to investigate them.

<p class="personal-note">A research overview will be added here.</p>

## Work in progress

Working papers and ongoing studies will appear here, with a short summary of each project and links to available materials.

## Publications

{% bibliography %}
{% assign own_papers = site.bibliography | size %}
{% if own_papers == 0 %}<p class="personal-note">Publication details will be added as this page develops.</p>{% endif %}
</div>
