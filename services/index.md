---
layout: default
title: Services
permalink: /services/
---

{% include hero.html
  kicker="Services"
  title="Practical help, sized to fit."
  sub="We scope to the smallest useful next step—and leave you with artifacts you’ll actually use."
%}

<span class="kicker">At a glance</span>
## What we offer

<div class="grid" style="margin-top:8px">
  {% for item in site.data.services.all %}
    <div class="card {{ item.cols | default: 'cols-6' }}">
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
  <h2>How it works</h2>
  <ol>
    <li><strong>Map:</strong> clarify choices, constraints, and success signals.</li>
    <li><strong>Decide:</strong> pick the smallest useful next step.</li>
    <li><strong>Build light systems:</strong> right-sized tools, no bloat.</li>
    <li><strong>Practice:</strong> short sprints → concrete artifacts.</li>
    <li><strong>Keep what works:</strong> document the routine; retire the rest.</li>
  </ol>

  <p class="cta-row">
    <a class="button" href="/contact/">Start a conversation</a>
    <a class="btn" href="/work/">See case notes</a>
  </p>
</div>
