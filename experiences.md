---
layout: default
title: "Expériences professionnelles"
---

# 🧰 Mes expériences professionnelles

Voici un aperçu de mes principales missions et projets en entreprise.  
Chaque expérience m’a permis de renforcer mes compétences en **administration systèmes, réseaux, sécurité et virtualisation.**

{% for experience in site.experiences %}
<div style="margin-bottom: 40px;">
  <h2>{{ experience.title }}</h2>
  <p><strong>{{ experience.company }}</strong> — {{ experience.location }}</p>
  <img src="{{ experience.image }}" alt="{{ experience.title }}" style="max-width:100%; border-radius:10px;">
  <p>{{ experience.excerpt | markdownify }}</p>
  <a href="{{ experience.url }}">🔍 Voir plus de détails</a>
</div>
{% endfor %}

