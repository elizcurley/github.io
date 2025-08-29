---
layout: default
title: Contact
permalink: /contact/
---

{% include hero.html
  kicker="Contact"
  title="Let’s start with a small step."
  sub="Tell me what you’re hoping for. I’ll reply with next steps within 2 business days."
%}

<div class="page-panel">
  <h2>Contact form</h2>
  <form action="https://formspree.io/f/{{ site.formspree_id }}" method="POST" class="contact-form">
    <label for="name">Full name
      <input id="name" type="text" name="name" autocomplete="name" required>
    </label>

    <label for="email">Email
      <input id="email" type="email" name="email" autocomplete="email" required>
    </label>

    <label for="message">What you’re hoping for
      <textarea id="message" name="message" rows="6" required></textarea>
    </label>

    <label for="accessibility">Accessibility needs (optional)
      <input id="accessibility" type="text" name="accessibility">
    </label>

    <!-- Anti-spam honeypot -->
    <input type="text" name="_gotcha" style="display:none" tabindex="-1" autocomplete="off">

    <!-- Subject line in your inbox -->
    <input type="hidden" name="_subject" value="New inquiry — Mangrove Method">

    <!-- Redirect after submit -->
    <input type="hidden" name="_redirect" value="{{ site.url }}{{ site.form_success_url | default: '/thanks/' }}">

    <button type="submit" class="button">Send</button>
  </form>

  <p class="sub" style="margin-top:8px">
    Prefer email first? Use the form above and I’ll offer times within 2 business days.
  </p>
</div>

## Book a Baseline Meet <a id="book"></a>

<!-- Uncomment when your Calendly is live -->
<!--
<link rel="stylesheet" href="https://assets.calendly.com/assets/external/widget.css">
<div class="calendly-inline-widget"
     data-url="https://calendly.com/your-calendly-link/intro?hide_gdpr_banner=1"
     style="min-width:320px;height:720px;"></div>
<script src="https://assets.calendly.com/assets/external/widget.js" async></script>
-->
