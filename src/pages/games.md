---
title: 'Games'
permalink: '/games/index.html'
layout: 'layouts/page.njk'
---

## Milkshake Jump

<iframe width="560" height="315" src="https://www.youtube.com/embed/WA8DAXLNmjE" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

A simple game where you control a milkshake and tap to jump. It focuses purely on timing and increases in difficulty as you reach greater heights.

<div style="display: flex; justify-content: space-evenly; flex-wrap: wrap">
{%- for item in milkshake_jump.images -%}
<img src={{item.url}} width: "125" height: "250" style="width: 125px; margin-top: 10px;" alt={{item.alt}}>
{%- endfor -%}
</div>

<div style="display: flex; justify-content: center;"><a style="background:none;" href='https://play.google.com/store/apps/details?id=com.BattleKoi.MilkshakeJump&hl=en&gl=US&pcampaignid=pcampaignidMKT-Other-global-all-co-prtnr-py-PartBadge-Mar2515-1'><img style="height: 100px;" alt='Get it on Google Play' src='https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png'/></a></div>

---

Google Play and the Google Play logo are trademarks of Google LLC.
