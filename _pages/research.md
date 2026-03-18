---
layout: page
title: research
permalink: /research/
description: Three core research topics with short descriptions and previews.
nav: true
nav_order: 2
---

## Multiscale Material Modeling

<div class="row mt-3 research-preview-strip">
  <div class="col-4 px-1">
    <a href="{{ '/publications/#choi2023atomistically' | relative_url }}">
      <img src="{{ '/assets/img/publication_preview/atomistically_informed.png' | relative_url }}" alt="Atomistically informed continuum modeling preview" loading="lazy">
    </a>
  </div>
  <div class="col-4 px-1">
    <a href="{{ '/publications/#choi2025mechanics' | relative_url }}">
      <img src="{{ '/assets/img/publication_preview/dislocation_graphene.gif' | relative_url }}" alt="Out-of-plane screw dislocation preview" loading="lazy">
    </a>
  </div>
  <div class="col-4 px-1">
    <a href="{{ '/publications/#1' | relative_url }}">
      <img src="{{ '/assets/img/publication_preview/statistical_mechanics.gif' | relative_url }}" alt="Statistical mechanics in a gas reservoir preview" loading="lazy">
    </a>
  </div>
</div>

<p><strong>Multiscale material modeling</strong> in my research connects <strong>quantum calculations</strong>, <strong>atomistic simulation</strong>, and <strong>continuum mechanics</strong> to understand how <strong>defects</strong>, <strong>interfaces</strong>, and environmental effects control material behavior, with a focus on physically interpretable constitutive descriptions and computational workflows that preserve the essential mechanics across scales.</p>

### Related papers

- [Atomistically-informed continuum modeling and isogeometric analysis of 2D materials over holey substrates]({{ '/publications/#choi2023atomistically' | relative_url }})
- [Mechanics of out-of-plane screw dislocation in a 2D material]({{ '/publications/#choi2025mechanics' | relative_url }})
- [Statistical mechanics of a 2D material in a gas reservoir]({{ '/publications/#1' | relative_url }})

## Strain Engineering of 2D Materials

<div class="row mt-3 research-preview-strip">
  <div class="col-4 px-1">
    <a href="{{ '/publications/#zhang2021holey' | relative_url }}">
      <img src="{{ '/assets/img/publication_preview/holey_substrate.png' | relative_url }}" alt="Holey substrate strain patterning preview" loading="lazy">
    </a>
  </div>
  <div class="col-4 px-1">
    <a href="{{ '/publications/#choi2024elastic' | relative_url }}">
      <img src="{{ '/assets/img/publication_preview/elastic_basis.png' | relative_url }}" alt="Twisted bilayer graphene deformation preview" loading="lazy">
    </a>
  </div>
  <div class="col-4 px-1">
    <a href="{{ '/publications/#ahmed2025quantifying' | relative_url }}">
      <img src="{{ '/assets/img/publication_preview/quantifying.gif' | relative_url }}" alt="Bilayer graphene superlubricity preview" loading="lazy">
    </a>
  </div>
</div>

<p>I study <strong>strain engineering</strong> in <strong>2D materials</strong> by tracking how <strong>substrates</strong>, <strong>holes</strong>, <strong>twist</strong>, and interfacial defects reshape <strong>deformation patterns</strong>, <strong>electronic structure</strong>, and <strong>mechanical response</strong>, using both atomistic and reduced-order models to connect nanoscale relaxation with experimentally relevant signatures.</p>

### Related papers

- [Holey substrate-directed strain patterning in bilayer MoS2]({{ '/publications/#zhang2021holey' | relative_url }})
- [Elastic plate basis for the deformation and electron diffraction of twisted bilayer graphene on a substrate]({{ '/publications/#choi2024elastic' | relative_url }})
- [Quantifying Superlubricity of Bilayer Graphene from the Mobility of Interface Dislocations]({{ '/publications/#ahmed2025quantifying' | relative_url }})

## Bio Materials

<div class="row mt-3 research-preview-strip">
  <div class="col-4 px-1">
    <a href="{{ '/publications/#lee2018facilitated' | relative_url }}">
      <img src="{{ '/assets/img/publication_preview/facilitated_water.png' | relative_url }}" alt="Facilitated water transport preview" loading="lazy">
    </a>
  </div>
  <div class="col-4 px-1">
    <a href="{{ '/publications/#park2025accelerated' | relative_url }}">
      <img src="{{ '/assets/img/publication_preview/accelerated_molecular_dynamics.png' | relative_url }}" alt="Accelerated molecular dynamics preview" loading="lazy">
    </a>
  </div>
  <div class="col-4 px-1">
    <a href="{{ '/publications/#7' | relative_url }}">
      <img src="{{ '/assets/img/publication_preview/AgNS.gif' | relative_url }}" alt="2D silver nanosheet assembly preview" loading="lazy">
    </a>
  </div>
</div>

<p>My work on <strong>bio materials</strong> focuses on <strong>membranes</strong>, <strong>nanochannels</strong>, and <strong>biomolecular dynamics</strong>, where molecular simulation is used to understand <strong>transport</strong>, <strong>collective motion</strong>, and structure-property relationships in <strong>soft matter</strong> and <strong>bio-inspired systems</strong>.</p>

### Related papers

- [Facilitated water transport through Graphene oxide membranes functionalized with aquaporin-mimicking peptides]({{ '/publications/#lee2018facilitated' | relative_url }})
- [An accelerated molecular dynamics study for investigating protein pathways using the bond-boost hyperdynamics method]({{ '/publications/#park2025accelerated' | relative_url }})
- [2D Silver Nanosheet Assembly for an Isotropic, Stretchable, and Highly Conductive Nanomembrane]({{ '/publications/#7' | relative_url }})

<style>
  .research-preview-strip {
    margin-bottom: 1rem;
  }

  .research-preview-strip a {
    display: block;
  }

  .research-preview-strip img {
    width: 100%;
    aspect-ratio: 1 / 1;
    object-fit: contain;
    background-color: var(--global-card-bg-color);
    border: 1px solid var(--global-divider-color);
    border-radius: 0.35rem;
  }
</style>
