---
permalink: /
title: "Qui sommes-nous ?"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

C'est officiel la chaîne Guingamp-Echecs Stream est lancé. 
C'est l'histoire d'un groupe d'amis fan d'échecs qui ont comme point commun d'être (presque) tous passés par l'échiquier Guingampais. 
Après le succès de la retransmission de notre participation au championnat d'Europe des clubs, nous allons continuer à partager notre passion avec fun et pédagogie.
Au programme session live, analyse et commentaires de compétitions !

Nos prochains rendez-vous
======
  * Lundi 3 Mai à 19h30 : (retour sur les meilleurs perfs du championnat d'Europe des équipes)
  * Samedi 8 Mai à 18h00 : blitz et annonce du programme du mois de Mai

News
======
{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}
