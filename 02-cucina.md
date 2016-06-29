---
layout: page
title: Cucina
permalink: /cucina/
---

Ho sempre avuto una sana passione per il cibo, seguita poi, in età adulta, da
una geniuna passione per la preparazione di quello che mangio.

Nel corso degli anni ho provato a cucinare un pò di tutto, dai semplici primi di pasta
ai risotti, dai secondi di carne o pesce ai dolci e ai prodotti di panificazione.

La passione per la sperimentazione e la prova di diverse ricette mi ha portato ad
accumulare un sacco di biglietti e pizzini con liste ingredienti e indicazioni per
le preparazioni, come le vecchie massaie.

Da qui l'idea di raccogliere man mano queste ricette in forma di blog, per poterle
non solo condividere ma anche avere a comoda portata di mano ovunque mi trovi!!

<!-- Tags in tema cucina -->
{% assign current_cat = "cucina"%}
<div class="list">
  <h2 class="heading"><span>Argomenti</span></h2>
  {% include categories/tag-list.html %}
</div>

<div class="list">
    <h2 class="heading centered"><span>Le ricette</span></h2>
    {% assign current_cat = "cucina" %} {% include categories/post-list.html %}
</div>
