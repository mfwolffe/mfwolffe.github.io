---
layout: archive
title: "Projects"
permalink: /portfolio/
author_profile: true
---

{% include base_path %}


<!-- {% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
 -->

<style>

  h2.larger-heading {
    font-size: 130%;
  }

  a:hover {
    text-shadow: 4px 4px 8px;
  }

  hr.darker {
    color: black;
    opacity: 100%;
  }

  summary.project {
    font-size: 1.1rem;
    font-weight: 600;
  }

  summary.project:hover {
    text-shadow: 4px 4px 8px;
  }

  details > p {
    margin-left: 1.3rem;
    margin-bottom: 0.6rem;
  }

  h3 {
    margin-left: 0.8rem;
    margin-top: 0.3rem;
  }

  p.roles {
    margin-left: 0.8rem;
    margin-bottom: 0.2rem;
    margin-top: 0.3rem;
    font-size: 0.9rem;
  }

  ul {
    font-size: 0.9rem;
    margin-top: 0.4rem;
  }

  a.noul {
    text-decoration: none;
  }

  a.noul:hover {
    text-decoration: none;
    text-shadow: 4px 4px 8px;
  }

</style>

<h2>WIP</h2>

<h2 class="larger-heading">Computer Science</h2>
------

<details open>
<summary class="project">Music CPR</summary>
<p class="roles"><em>Lead:</em> <a class="noul" target="_blank" href="https://hcientist.com/">Dr. Michael Stewart</a>   |   <em>Collaborator since 2023/08</em>   |   <a class="noul" target="_blank" href="https://github.com/JMU-CIME/CPR-Music">Github</a></p>


  <p>A Web Based LMS for middle and high school band and orchestra from the JMU Center for Inclusive Music Education.</p>

  <h3>Contributions</h3>
  <ul>
    <li>
      Algorithms for variation generation such as rhythmic & melodic permutations and combinations of the two which correctly recombine pitches that were split by a previous shift.
    </li>
    <li>
      Musical consultation & preparation of references to make certain tasks easier for non-musician programmers.
      <br>
      For example:
      <ul>
      <li><a class="noul" href="../images/CPR/transposition_reference.png">Transposition Reference</a></li>
      </ul>
    </li>
  </ul>

</details>

<details open>
<summary class="project">A Better ATan2</summary>
<p class="roles"><em>Author</em> | <a class="noul" target="_blank" href="https://mfwolffe.github.io/improved-atan2/">Link</a></p>

  <p>A personal project I made as practice for learning javascript, and to save myself time when working with math students who need to get a positive angle in any quadrant.</p>
  <p>The styling is <em>very</em> basic. I plan to relocate as a page on this site, or just use a framework such as bootstrap to make it less...ugly.</p>

</details>
