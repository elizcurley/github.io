---
layout: default
title: Home
permalink: /
bg: stretched
---

{% include hero.html
  kicker='Rooted in care. Grounded by you. Grown together.'
  title='Move from complexity to clarity.'
  sub='We help you turn messy realities into decisions that stick—through practical research, clean systems, and artifacts your team will actually use.'
  cta_href='/contact/#book'
  cta_label='Free 20-min meet & introduction'
  cta2_href='/services/'
  cta2_label='Explore services'
  pills='Research & Evaluation|Forensic / Expert Work|Goals Coaching|Systems Design & Implementation'
%}

<span class="kicker">Highlights</span>
## What we do

<div class="grid" style="margin-top:8px">
  {% for item in site.data.services.home %}
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

<div class="page-panel" style="margin-top:12px">
  <h2>How it works</h2>
  <ol>
    <li><strong>Map:</strong> clarify choices, constraints, and success signals.</li>
    <li><strong>Decide:</strong> pick the smallest useful next step.</li>
    <li><strong>Build light systems:</strong> right-sized tools, no bloat.</li>
    <li><strong>Practice:</strong> short sprints → concrete artifacts.</li>
    <li><strong>Keep what works:</strong> document the routine; let the rest go.</li>
  </ol>

  <p class="cta-row">
    <a class="button" href="/contact/">Start a conversation</a>
    <a class="btn" href="/work/">See case notes</a>
  </p>
</div>
