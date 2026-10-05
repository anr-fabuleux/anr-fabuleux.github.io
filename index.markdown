---
layout: default
title: Accueil
---

# FABULEUX : Combattre les fabulations et le mésusage des LLM dans l’écriture scientifique

Le projet Fabuleux s'attaque à un sujet majeur pour la science: garantir la fiabilité et l'intégrité de l'écriture scientifique à l'ère des grands modèles de langue (LLM). Si les LLM sont de plus en plus utilisés par les chercheurs pour les assister dans la rédaction et la révision des textes scientifiques, leur usage introduit également de nouveaux risques, allant de la fabrication de contenus et de la distorsion de citations jusqu’à la génération à grande échelle d’articles frauduleux. Fabuleux vise à encourager un usage responsable des LLM dans l’écriture scientifique tout en en limitant les dérives, en développant des méthodologies pour détecter, analyser et contrôler les comportements problématiques dans la rédaction assistée par LLM. Le projet poursuit deux objectifs complémentaires : (1) rendre la révision assistée par LLM plus fiable et bénéfique pour les chercheurs, en détectant et en limitant la production de contenus inventés ou trompeurs, tout en fournissant des explications pour aider les auteurs à améliorer leurs compétences rédactionnelles; et (2) identifier les travaux scientifiques non fiables ou frauduleux, en concevant des méthodes et des outils permettant à la communauté scientifique de détecter les publications douteuses, de renforcer les pratiques éthiques et de préserver l’intégrité de la communication scientifique.

# Consortium

<div class="consortium">
  <a class="partner" href="https://www.ls2n.fr">
    <span class="partner-name">LS2N</span>
    <span class="partner-affiliation">Inria et Nantes Université</span>
  </a>
  <a class="partner" href="https://www.isir.upmc.fr">
    <span class="partner-name">ISIR</span>
    <span class="partner-affiliation">Sorbonne Université et CNRS</span>
  </a>
  <a class="partner" href="https://almanach.inria.fr">
    <span class="partner-name">Inria Paris</span>
    <span class="partner-affiliation">Équipe Almanach</span>
  </a>
  <a class="partner" href="https://www.loria.fr">
    <span class="partner-name">LORIA</span>
    <span class="partner-affiliation">Université de Lorraine, équipe Mosaik</span>
  </a>
</div>

# Actualités
{% if site.posts.size == 0 %}
<p class="news-empty">Aucune actualité pour le moment.</p>
{% endif %}
<ul class="news">
  {% for post in site.posts %}
    <li>
      <span class="news-date">{{ post.date | date: "%d/%m/%Y" }}</span>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>