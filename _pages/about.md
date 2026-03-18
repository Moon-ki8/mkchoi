---
layout: about
title: about
permalink: /
subtitle: Postdoctoral Researcher, Materials Research Laboratory, University of Illinois Urbana-Champaign

profile: false

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

{%
include figure.liquid
path="/my_figure/main.png"
class="img-fluid rounded z-depth-0"
alt="Main research figure"
caption="<em>''How can different physical languages be connected across scales?''</em>"

avoid_scaling=true
%}

<div class="row mt-3">
  <div class="col-sm-3">
    {%
      include figure.liquid
      path="/assets/img/prof_pic.jpg"
      class="img-fluid rounded z-depth-1"
      alt="Moon-ki Choi photo"
      avoid_scaling=true
    %}
  </div>
  <div class="col-sm-9">
    <p>
      I am Moon-ki Choi, a <strong>Postdoctoral Researcher</strong> at the <strong>Materials Research Laboratory</strong>,
      <strong>University of Illinois Urbana-Champaign</strong>.
      I received my Ph.D. from the <strong>University of Minnesota Twin Cities</strong>.
      You can reach me at <a href="mailto:choi0652@illinois.edu">choi0652@illinois.edu</a>.
    </p>
    <p>My research focuses on translating different languages of physics across scales:</p>
    <ul>
      <li><strong>multi-scale simulation</strong> across quantum, atomistic, and continuum mechanics</li>
      <li><strong>physics-based modeling</strong> and <strong>machine-learning-based modeling</strong></li>
    </ul>
    <p>I am interested in defect dislocations, 2D materials, topological insulators, and biomaterials. I also have extensive hands-on experience in HPC, scientific coding, and simulation workflows forcomputational materials and mechanics problems.</p>
  </div>
</div>

<style>
  .about-gif-strip {
    max-width: 500px;
    margin-left: auto;
    margin-right: auto;
  }

  .about-gif-strip img {
    width: 100%;
    aspect-ratio: 1 / 1;
    object-fit: cover;
    border-radius: 0.2rem;
  }
</style>
