---
layout: default
title: "Snowflake, dbt, and AI-agent consulting"
description: "Snowflake, dbt, and AI-agent consulting from Nick Rogers. Contact me or submit a sanitized data problem for a free first-pass review."
---

<section class="hero">
  <p class="eyebrow">Snowflake · dbt · analytics engineering · AI workflows</p>
  <div class="title-row">
    <h1>Nick Rogers</h1>
    <a class="linkedin-inline" href="{{ site.linkedin_url }}" target="_blank" rel="noopener">LinkedIn ↗</a>
  </div>
  <p class="tagline">I help data teams make Snowflake, dbt, and AI-assisted analytics engineering faster, cheaper, and easier to trust.</p>
</section>

<section class="section compact-section">
  <h2>Where I can help</h2>
  <ul>
    <li>Reduce Snowflake cost and improve query/model performance.</li>
    <li>Clean up dbt projects, model grain, tests, documentation, and refactor plans.</li>
    <li>Find why dashboards, metrics, or stakeholder reports do not agree.</li>
    <li>Set up practical Claude/Cursor/ChatGPT workflows for SQL and dbt review.</li>
    <li>Provide senior analytics engineering review when your team is stretched.</li>
  </ul>
</section>

<section class="section compact-section testimonials">
  <h2>Reviews from people I’ve worked for</h2>
  <ul>
    <li>
      <p>“He inherited a Snowflake and dbt instance that was struggling to keep up with the volume and complexity of the data it was handling. He very quickly did two things that are conventionally in opposition — he increased performance significantly and reduced cost significantly. And by significantly I mean an order of magnitude. I’d hire Nick again in a heartbeat.”</p>
      <span>Matt W. — Chief Data Science Officer, NeuroID</span>
    </li>
    <li>
      <p>“Nick is an immediate asset, seeing gaps and offering solutions. His work is accurate and insightful, with good judgement and just enough impatience to move things along.”</p>
      <span>Duane J. — Engineering Manager, Crenlo</span>
    </li>
  </ul>
</section>

<section class="section actions-section">
  <h2>Want to talk?</h2>
  <p>Choose whichever is easier. Keep anything sensitive out of the form.</p>

  <div class="disclosure-actions">
    <details>
      <summary>Contact me</summary>
      <form class="contact-form" name="contact" method="POST" action="https://api.web3forms.com/submit">
        <input type="hidden" name="access_key" value="157f3c99-6b83-42d2-ac48-1e1488050071">
        <input type="hidden" name="subject" value="New contact from nickrogers.dev">
        <input type="hidden" name="from_name" value="nickrogers.dev">
        <input type="hidden" name="redirect" value="https://www.nickrogers.dev/thanks/">
        <input type="hidden" name="name" value="Website contact form">
        <p class="hidden-field"><label>Don’t fill this out: <input type="checkbox" name="botcheck"></label></p>
        <label>Reply email <input type="email" name="email" autocomplete="email" required></label>
        <label>Message <textarea name="message" rows="4" required placeholder="Short note, question, or context."></textarea></label>
        <button class="button primary" type="submit">Send</button>
      </form>
    </details>

    <details id="review">
      <summary>Free Snowflake/dbt problem review</summary>
      <div class="review-intro">
        <p>Send me a sanitized Snowflake, dbt, SQL, reporting, or AI-workflow problem. If it’s in my wheelhouse, I’ll spend 5–30 minutes thinking through it and send back how I’d approach it.</p>
        <p class="warning">Do not send credentials, private keys, customer data, or confidential records.</p>
      </div>
      <form class="problem-form" name="problem-review" method="POST" action="https://api.web3forms.com/submit">
        <input type="hidden" name="access_key" value="157f3c99-6b83-42d2-ac48-1e1488050071">
        <input type="hidden" name="subject" value="New Snowflake/dbt problem review request from nickrogers.dev">
        <input type="hidden" name="from_name" value="nickrogers.dev">
        <input type="hidden" name="redirect" value="https://www.nickrogers.dev/thanks/">
        <input type="hidden" name="name" value="Snowflake/dbt problem review form">
        <p class="hidden-field"><label>Don’t fill this out: <input type="checkbox" name="botcheck"></label></p>
        <label>Reply email <input type="email" name="email" autocomplete="email" required></label>
        <label>What are you trying to solve? <textarea name="problem" rows="5" required placeholder="Example: Snowflake cost jumped, dbt refactor feels risky, dashboard numbers disagree, AI-generated SQL is hard to review..."></textarea></label>
        <label>Stack / context <input type="text" name="stack" placeholder="Snowflake, dbt, Looker, Sigma, Fivetran, Airflow, Dagster, etc."></label>
        <label>Optional sanitized details <textarea name="sanitized-details" rows="4" placeholder="Sanitized SQL, model notes, symptoms, or architecture context. No secrets."></textarea></label>
        <label class="checkbox"><input type="checkbox" name="safe-to-share" required> I understand not to submit secrets or sensitive data.</label>
        <button class="button primary" type="submit">Send</button>
      </form>
    </details>
  </div>

</section>
