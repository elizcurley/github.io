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

<div class="page-panel" id="deep-dives" style="margin-top:12px">
  <h2>Deep dives</h2>
  <p class="sub">More detail on what the work looks like at different scales. Start small; we’ll right-size to your constraints.</p>

  <h3 id="individuals" style="margin-top:10px">Individuals — Lifestyle management & creative problem-solving</h3>
  <ul>
    <li><strong>Clarity Session (90 min):</strong> map constraints, pick the smallest useful next step, leave with a 1-pager.</li>
    <li><strong>Starter Sprint (2 weeks):</strong> two quick cycles → checklist(s), weekly plan, and a “done for now” decision memo.</li>
    <li><strong>Sustainable Flow (4–6 weeks):</strong> install light routines with fail-safes; keep only what works.</li>
    <li><strong>Stewardship (monthly):</strong> gentle accountability that respects bandwidth & privacy.</li>
  </ul>

  <h3 id="teams" style="margin-top:16px">Community orgs & small teams — Method implementation</h3>
  <ul>
    <li><strong>Pulse Check (2–3 weeks):</strong> right-sized measurement plan, clean data intake, executive summary.</li>
    <li><strong>Implementation Sprint (6–8 weeks):</strong> logic model refresh, SOPs that match reality, facilitator kit.</li>
    <li><strong>Partnership (quarterly):</strong> cadence of decision memos + refresh of artifacts as the work evolves.</li>
  </ul>

  <h3 id="institutions" style="margin-top:16px">Institutions — Strategy, evaluation & grant architecture</h3>
  <ul>
    <li><strong>Discovery & Design (4–6 weeks):</strong> mixed-methods plan, measurement strategy, and a lean learning agenda.</li>
    <li><strong>Pilot & Learn (12–16 weeks):</strong> reproducible pipelines, decision-grade dashboards, implementation check-ins.</li>
    <li><strong>Advisory On-Call (retainer):</strong> rapid reviews, briefings, and executive-ready artifacts.</li>
  </ul>

  <p class="cta-row" style="margin-top:12px">
    <a class="button" href="/contact/">Start a conversation</a>
    <a class="btn" href="/work/">See case notes</a>
  </p>
</div>
