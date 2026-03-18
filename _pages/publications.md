---
layout: page
permalink: /publications/
title: publications
description: "# indicates co-first authors"
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<div class="publications">
  <p>
    Publications are listed in reverse chronological order. For an up-to-date list, see
    <a class="gs-link" href="https://scholar.google.com/citations?user=0-gjySkAAAAJ&hl=en&oi=ao" target="_blank" rel="noopener noreferrer">Google Scholar</a>.
  </p>

  <h2>Preprint</h2>
  {% capture preprint_count %}{% bibliography_count --query @*[keywords=preprint] %}{% endcapture %}
  <div class="pub-list" style="--pub-start: {{ preprint_count | strip | plus: 1 }};">
    {% bibliography --group_by none --query @*[keywords=preprint] %}
  </div>
  <hr class="pub-section-line">

  <h2>Peer-reviewed papers</h2>
  {% capture pub_count %}{% bibliography_count --query @*[keywords=pub] %}{% endcapture %}
  <div class="pub-list" style="--pub-start: {{ pub_count | strip | plus: 1 }};">
    {% bibliography --group_by none --query @*[keywords=pub] %}
  </div>
  <hr class="pub-section-line">

</div>

<style>
  .post .post-description .gs-link,
  .publications .gs-link {
    color: #7b2cbf !important;
  }

  .post .post-description .gs-link:hover,
  .publications .gs-link:hover {
    color: #5a189a !important;
  }

  .publications .pub-list {
    counter-reset: pub-item var(--pub-start, 0);
  }

  .publications .pub-list ol.bibliography > li {
    counter-increment: pub-item -1;
    position: relative;
    padding-left: 2.2rem;
    list-style: none;
  }

  .publications .pub-list ol.bibliography > li::before {
    content: counter(pub-item) ".";
    font-weight: 700;
    position: absolute;
    left: 0;
    top: 0.1rem;
    width: 1.8rem;
    text-align: right;
  }

  .publications .pub-section-line {
    margin: 1.2rem 0 1.8rem;
    border: 0;
    border-top: 1px solid var(--global-divider-color);
  }
</style>
