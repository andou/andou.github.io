---
layout: page
title: Trekking
permalink: /trekking/
---
Mi piace camminare e mi piace tenere traccia dei posti in cui sono stato. L'idea
è quella di raccogliere qui i giri che riesco a fare mano a mano che riesco a farli,
per ricordarmene in futuro ed eventualmente dare qualche consiglio pratico a chi
intende fare le stesse passeggiate. :)

<!-- Tags in tema trekking -->
{% assign current_cat = "trekking"%}
<div class="list">
  <h2 class="heading"><span>Posti e luoghi</span></h2>
  {% include categories/tag-list.html %}
</div>

<div class="list">
    <h2 class="heading centered"><span>Ultime escursioni</span></h2>
    {% assign current_cat = "trekking" %} {% include categories/post-list.html %}
</div>
