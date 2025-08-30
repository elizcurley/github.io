---
layout: default
title: Who we help
permalink: /audiences/
---

{% include hero.html
  kicker="Who we help"
  title="Choose your path."
  sub="Individuals, community orgs, and institutions. Selective expert/forensic work by fit."
%}

<div class="grid" style="margin-top:8px">
  {% for item in site.data.audiences %}
    <div class="card {{ item.cols | default: 'cols-4' }}">
      <h3>{{ item.title }}</h3>
      <ul>
        {% for li in item.list %}
          <li>{{ li }}</li>
        {% endfor %}
      </ul>
    </div>
  {% endfor %}
</div>

<div class="page-panel">
  <h2>Not sure where you fit?</h2>
  <p class="sub">Tell me what you’re working with. We’ll recommend the smallest useful next step.</p>
  <p class="cta-row">
    <a class="button" href="/contact/">Start a conversation</a>
    <a class="btn" href="/services/">See services</a>
  </p>
</div>
