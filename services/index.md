---
layout: default
title: Services
permalink: /services/
---

{% include hero.html
  kicker="Services"
  title="Practical help, sized to fit."
  sub="We scope to the smallest useful next step—and leave you with products you’ll actually use."
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

<div class="page-panel" id="products" style="margin-top:12px">
  <h2>Products (examples)</h2>
  <p class="sub">A <strong>product</strong> is a concrete, usable thing that saves you time or decision effort. We’ll choose together based on your goals and capacity.</p>

  <div class="grid" style="margin-top:8px">
    <!-- Personal Systems & Growth -->
    <div class="card cols-4"><h3>Whole-Life Snapshot & Plan</h3><p>Gentle intake + barrier/support map → a simple plan.</p></div>
    <div class="card cols-4"><h3>Weekly rhythm map</h3><p>Blocks for focus, admin, and rest; predictable resets.</p></div>
    <div class="card cols-4"><h3>Fallback-day plan</h3><p>Low-capacity routine to keep momentum on thin days.</p></div>
    <div class="card cols-4"><h3>Decision map</h3><p>If-then branches for sticky choices to avoid stalls.</p></div>
    <div class="card cols-4"><h3>Boundary/request scripts</h3><p>Plain-language messages for common scenarios.</p></div>
    <div class="card cols-4"><h3>Habit worksheets</h3><p>Self-guided exercises that build consistency.</p></div>

    <!-- Programs & Ops -->
    <div class="card cols-4"><h3>Manualized program</h3><p>Plain-language, step-by-step guide staff actually use.</p></div>
    <div class="card cols-4"><h3>Process documents</h3><p>Service map, roles & lanes, handoffs, and timing.</p></div>
    <div class="card cols-4"><h3>Protocols & checklists</h3><p>What “good” looks like; fewer errors, faster onboarding.</p></div>
    <div class="card cols-4"><h3>Toolkits</h3><p>Grouped templates/scripts/forms for a specific use case.</p></div>

    <!-- Measurement & Data -->
    <div class="card cols-4"><h3>Progress signals</h3><p>Short list of “proof-we’re-moving” markers.</p></div>
    <div class="card cols-4"><h3>Measures menu</h3><p>Validated options in plain language + fit notes.</p></div>
    <div class="card cols-4"><h3>Data-capture forms</h3><p>Simple, reliable spreadsheets/forms that fit your work.</p></div>
    <div class="card cols-4"><h3>Starter measurement kit</h3><p>Signals + forms + check cadence in one place.</p></div>

    <!-- Funding & Partnerships -->
    <div class="card cols-4"><h3>Grants & LOIs</h3><p>Narratives, concept notes, and a reusable paragraph bank.</p></div>
    <div class="card cols-4"><h3>Partner outreach scripts</h3><p>Emails and talking points that get replies.</p></div>

    <!-- Training & Teaching -->
    <div class="card cols-4"><h3>Slide decks & trainings</h3><p>Clear decks + facilitator notes and activities.</p></div>
    <div class="card cols-4"><h3>Playbooks (6–10 pp)</h3><p>“How we do it here,” simple and action-first.</p></div>

    <!-- Career & Comms -->
    <div class="card cols-4"><h3>Resume & job docs</h3><p>ATS-friendly resume, cover letter bank, interview prep.</p></div>
    <div class="card cols-4"><h3>Project timeline</h3><p>Milestones, sprints, and check-ins you can follow.</p></div>
    <div class="card cols-4"><h3>Canva products</h3><p>Business cards, one-pagers, and reusable deck templates.</p></div>

    <!-- Legal / Forensic (Selective) -->
    <div class="card cols-4"><h3>Social history outline</h3><p>Context & themes in plain language.</p></div>
    <div class="card cols-4"><h3>Records timeline crosswalk</h3><p>What happened when, and where it’s documented.</p></div>
  </div>
</div>

<div class="page-panel" id="packages" style="margin-top:12px">
  <h2>Packages</h2>
  <p class="sub">Each package includes a set number of <strong>products</strong>. We’ll pick them together. Products may be from the menu above, or a product you believe has the best fit.</p>

  <h3 id="individuals" style="margin-top:10px">Individuals — Lifestyle management & creative problem-solving</h3>
  <ul>
    <li><strong>Root Session — $45:</strong> <em>1 product.</em> 60–75 minutes + a one-page starter plan.</li>
    <li><strong>Sustainable Flow — $225:</strong> <em>3 products.</em> Two sessions + 14-day check-in.</li>
    <li><strong>Growth Stage — $250/$375 per month:</strong> <em>2 products/month</em> + as-needed check-ins.</li>
    <li><strong>Reset Intensive (Half-Day) — $280/$400:</strong> <em>3–5 products</em> delivered that week.</li>
  </ul>

  <h3 id="teams" style="margin-top:16px">Community orgs & small teams — Right-sized implementation</h3>
  <ul>
    <li><strong>Program Clarity Sprint — $2,000:</strong> <em>3–4 products.</em> Typical mix: service map, 90-day rollout, roles & lanes, or a starter template.</li>
    <li><strong>Team Workshop — $750:</strong> <em>2 products.</em> Slide deck + quick-wins playbook.</li>
    <li><strong>Evaluation Lite — $3,500:</strong> <em>4 products.</em> Progress signals, measures menu, forms, report template.</li>
    <li><strong>Capacity Retainer — from $1,500/mo:</strong> <em>2–4 products/month</em> matched to need.</li>
  </ul>

  <h3 id="institutions" style="margin-top:16px">Institutions — Strategy, measurement & change sprints</h3>
  <ul>
    <li><strong>Change Blueprint — $6,000:</strong> <em>5 products.</em> Decision brief, option set, 90-day rollout, progress signals, executive deck.</li>
    <li><strong>Ops & Wellbeing Lab — $4,500:</strong> <em>4 products.</em> Friction audit, two pilot protocols, learning questions, starter measurement kit.</li>
    <li><strong>Executive Advisory — $3,000–$6,000/mo:</strong> <em>2–6 products/month.</em> Briefs, rollouts, signals updates.</li>
    <li><strong>Workshop Series — $4,000–$10,000:</strong> <em>3+ products.</em> Decks, playbooks, and templates sized to scope.</li>
  </ul>

  <div class="sub" style="margin-top:8px">
    <p><strong>Hourly:</strong> Individuals $150/$70/$30–$60 · Orgs $125/hr or $1,000/day · Institutions $200/hr or $1,600–$2,000/day.</p>
    <p><strong>Terms (plain-language):</strong> Individuals prepay. Fixed-fee org/institution work: 50% to start, 50% on delivery. Two light edit rounds per product (within 14 days). Rush ≤5 business days +25% if available. <em>You own your products.</em></p>
  </div>
</div>

<div class="page-panel" id="how" style="margin-top:12px">
  <h2>How it works</h2>
  <ol>
    <li><strong>Map:</strong> clarify choices, constraints, and progress signals.</li>
    <li><strong>Decide:</strong> pick the smallest useful next step.</li>
    <li><strong>Build light systems:</strong> right-sized tools, no bloat.</li>
    <li><strong>Practice:</strong> short sprints → concrete <em>products</em>.</li>
    <li><strong>Keep what works:</strong> document the routine; retire the rest.</li>
  </ol>

  <p class="cta-row">
    <a class="button" href="/contact/">Start a conversation</a>
    <a class="btn" href="/work/">See case notes</a>
  </p>
</div>
