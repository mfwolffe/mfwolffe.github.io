---
layout: archive
title: "Music"
permalink: /music/
author_profile: true
---

<!-- {% if author.googlescholar %}
  You can also find my articles on <u><a class="cust" href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %} -->

{% include base_path %}

{% for post in site.music reversed %}
  {% include archive-single.html %}
{% endfor %}

------

<style> 
  h2.larger-heading {
    font-size: 135%;
  }

  h2 {
    font-size: 100%
  }

  a.cust {
    text-decoration: none;
  }

  a.cust:hover {
    text-shadow: 4px 4px 8px;
    text-decoration: none;
  }

  div.square {
    display: flex;
    flex-direction: row;
    justify-content: flex-start;
    align-items: flex-start;
    gap: 2rem;
  }

  div.square > p {
    width: 45rem;
    height: inherit;
    margin: 0rem;
    padding-top: 0rem;
  }

  div.square > ul {
    height: 20rem;
    width: 45rem;
    margin: auto;
  }

  div.rect {
    display: flex;
    flex-direction: row;
    justify-content: flex-start;
    align-items: flex-start;
    gap: 2rem;
  }

  div.square > figure {
    width: 20rem;
    margin: auto;
  }

  div.square > figure > img {
    width: 20rem;
    margin: auto;
  }

  div.rect > p {
    height: inherit;
    padding-top: 0rem;
    width: 40rem;
    margin: 0rem;
  }

  div.rect > figure {
    width: 25rem;
    margin: auto;
  }

  div.rect > figure > img {
    width: 25rem;
    margin: auto;
  }

  div.rect > figure.vid {
    margin-top: 0rem;
    overflow: hidden;
    border-radius: 8px;
    transform: translateZ(0px);
    border: 2px solid black;
    height: 12rem;
    width: 25rem;
    margin-left: auto;
    margin-right: auto;
    margin-bottom: 0rem;
  }

  div.rect > figure.vid > iframe {
    width: 25rem;
    height: 15rem;
    margin: auto;
  }

  div.portrait {
    display: flex;
    flex-direction: row;
    justify-content: flex-start;
    align-items: flex-start;
    gap: 2rem;
  }

  div.portrait > p {
    width: 45rem;
    margin: 0rem;
  }

  div.portrait > figure {
    width: 20rem;
    margin: auto;
  }

  div.portrait > figure > img {
    width: 20rem;
    margin: auto;
  }

  p.attribution {
    margin-top: 0rem;
    margin-bottom: 0rem;
    size: 0.2rem;
    color: #BABABA;
    margin-left: 1rem;
    font-weight: lighter
  }

  figcaption {
    font-size: 0.8rem;
  }

  figcaption > a {
    text-decoration: none;
  }

  /* figcaption > a:hover {
    text-shadow: 4px 4px 8px;
  } */

  section.jump-to {
    font-size: 1rem;
  }

  section.jump-to > p {
    margin-bottom: 0rem;
  }

  section.jump-to > ul > li > a {
    font-size: 0.8rem;
    text-decoration: none;
  }

  section.jump-to > ul {
    margin-top: 0.4rem;
    line-height: 55%;
  }

  section.jump-to > ul > li {
    line-height: 55%;
  }

  summary.bio {
    font-size: 1.2rem;
    font-weight: 600;
  }

  summary:hover {
    text-shadow: 4px 4px 8px;
  }

  img.squared, figure.squared {
    width: 18rem;
    margin: auto;
  }

  img.portrait, figure.portrait {
    width: 18rem;
    margin: auto;
  }

  img.rect, figure.rect {
    width: 23rem;
    margin: auto;
  }

  div.squarefix {
    width: 67.45rem;
    display: flex;
    flex-direction: row;
    justify-content: flex-start;
    align-items: flex-start;
    gap: 2rem;
    margin-bottom: 1.5rem;
  }

  div.portfix {
    width: 67.45rem;
    display: flex;
    flex-direction: row;
    justify-content: flex-start;
    align-items: flex-start;
    gap: 2rem;
    margin-bottom: 1.5rem;
  }

  div.rectfix {
    width: 67.45rem;
    display: flex;
    flex-direction: row;
    justify-content: flex-start;
    align-items: flex-start;
    gap: 2rem;
    margin-bottom: 1.5rem;
  }

  div.squarefix p, div.portfix p {
    margin-top: 0rem;
    width: 45.5rem;
  }

  div.rectfix p {
    margin-top: 0rem;
    width: 40.5rem;
  }

  summary.equip {
    margin-left: 1rem;
  }

  ul.fix {
    margin-top: 0rem;
    width: 45.5rem;
  }

  /* section.jump-to > ul > li > a:hover {
    text-shadow: 4px 4px 8px;
  } */

</style>

<section class="jump-to">
  <p>Jump to:</p>
  <ul>
    <li><a class="cust" href="#Bio">Bio and Background</a></li>
    <li><a class="cust" href="#photo-gallery">Gallery</a></li>
    <li><a class="cust" href="#recordings">Recordings</a></li>

  </ul>
</section>

<h2 id="Bio" class="larger-heading">Bio and Background</h2>
  <div class="squarefix">
    <div>
      <p>
        I began practicing music seriously in the sixth grade after deciding to learn the tuba. I had started on trumpet but didn't enjoy it due to difficulties with embouchure. Developing tuba 'chops', for me at least, was more forgiving. As one might expect, the tuba parts in the pieces our sixth grade band was performing were not very exciting, and sheet music around 2007, let alone free sheet music, was not as ubiquitous as it is today. So I had to learn to transpose and transcribe pretty early on if I hoped to play any exciting rep.
      </p>
      <p>
        Our band director recommended I take private lessons and so I started studying with Joe Eggebeen. He must have heard something in my playing, as he quickly started encouraging me to audition for the regional band. I don't know how, but I placed first in the audition, and from then onward music became my priority. I discovered figures like Leonard Bernstein, who led me to discover the full scope of roles low brass can take on in an orchestra.
      </p>
    </div>
    <div>
        <figure class="squared">
          <img class="squared" src="../images/music-misc-webp/uncso-crop-UNUSED.webp">
          <figcaption>following a UNCSO performance</figcaption>
        </figure>
    </div>
    </div>
  <div class="portfix">
    <div>
        <p>
        I continued taking auditions throughout high school, so while my classmates at MHS were busy competing over AP qualifiers, I was traveling for performances. I remember during my sophomore year of high school, a friend's mother told me that I needed to stop focusing on music, otherwise I wouldn't get into any colleges. When my senior year rolled around though, I was honored to reeceive a New Jersey Governor's Award in Arts Education, followed by the William R. Kenan Jr. Music Scholarship, a four year, full scholarship to the University of North Carolina at Chapel Hill.
        </p>
        <p>
          During my time at UNC, I studied under retired principal trombonist of the North Carolina Symphony, Michael Kris. I performed frequently with the Symphony Orchestra, Wind Ensemble, Brass Quintet, Tuba/Euph Quartet, Sackbut Ensemble, and trombone choir. I also played in a local brass band, and in festivals during the summers. Thanks to professor Kris, I was able to explore the world of historically informed performance, learning and performing on instruments such as the Sackbut and Ophicleide.
        </p>
     </div>
     <div>
        <figure class="portrait">
          <img class="portrait" src="../images/webp-unc/cimbasso-demo.webp">
          <figcaption>Giving my grandma a demo of the cimbasso</figcaption>
        </figure>
    </div>
  </div>
  <div class="rectfix">
    <div>
      <p>
        I supplemented my studies by traveling and taking lessons with principal tubists of major orchestras up and down the east coast, and used the stipend included with my scholarship to study with principals throughout the UK and EU. Ultimately however, I chose to leave UNC before graduating due to persistent health issues and a combination of rather unforgiving imposter syndrome and constant ruminations about my future as a musician. I still practice and perform my own arrangements/transcriptions today. 
      </p>
      <p>
        Favorite composers include Mahler, Shostakovich, R. Strauss, Sibelius, G. Gabrieli, Tchaikovsky, Bruckner, Berlioz, Verdi as well as film composers like Ennio Morricone. I am currently teaching myself the harmonica & various <a class="noul" href="https://stonewhistle.com/">Stonewhistle</a> clay flutes for a larger tribute to Ennio Morricone I have been working on for about half a year.
      </p>
    </div>
    <div>
      <figure class="rect">
        <img class="rect" src="../images/europe/mahler8-rehearsal.webp">
        <figcaption>sitting in on a Mahler 8 rehearsal following a lesson in the Royal Albert Hall in London</figcaption>
      </figure>
    </div>
  </div>

  <div class="squarefix">
    <div>
      <ul class="fix">
        <li>B&S PT-6 Contrabass Tuba (C)</li>
        <li>Miraphone <em>Elektra</em> Bass Tuba (F)</li>
        <li>Dillon Cimbasso (F)</li>
        <li>Inexpensive no-name Bass Trombone</li>
        <li>Hohner <em>Special 20</em> in C, G, and A</li>
        <li>Stonewhistle <em>Natey</em> (G4)</li>
        <li>Stonewhistle <em>ZENFlute</em> (Large - E3)</li>
      </ul>
    </div>
    <div>
      <figure class="squared">
        <img class="squared" src="../images/webp-unc/liminal.webp">
        <figcaption>Tight squeeze</figcaption>
      </figure>
    </div>
  </div>


<h2 class="larger-heading" id="photo-gallery">Gallery</h2>

<style>
  div.section {
    width: 67.45rem;
    display: grid;
    grid-template-columns: 21.5rem 21.5rem 21.5rem;
    /* grid-template-rows: repeat(4, 1fr); */
    column-gap: 0.5rem;
    row-gap: 2rem;
    align-items: center;
    justify-content: center;
  }

  div.last-row {
    margin-left: auto;
    margin-right: auto;
    margin-top: 2rem;
    width: 67.45rem;
  }

  div.last-row > figure, div.last-row > figure > img {
    width: 26rem;
    margin: auto;
  }

  div.section > figure, div.section > figure > img {
    margin-top: 0rem;
    margin-bottom: 0rem;
    width: 21.5rem;
  }

  figure.span-full, img.span-full {
    grid-column: 2;
    width: 28rem;
  }

  summary.gallery {
    font-size: 1.1rem;
    font-weight: 600;
  }

  summary.gallery:hover {
    text-shadow: 4px 4px 8px;
  }

  hr.darker {
    color: black;
    opacity: 100%;
  }

</style>

<details open>
<summary class="gallery">Pre-UNC</summary>

<div class="section">

<figure>
<img src="../images/music-misc-webp/mattEggebeen.webp" alt="Viewing the Symphonic Band with Eggebeen after my performance in the Wind Ensemble">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/music-misc-webp/ASO5.webp" alt="ASO tutti orchestra + choir">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/music-misc-webp/FTM1.webp" alt="Contemporary music group performance in NYC">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/music-misc-webp/mattNJPAC.webp" alt="In the lobby at NJPAC">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/music-misc-webp/AS-WE-senior.webp" alt="final all state performance">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/music-misc-webp/govaward9.webp" alt="Contemporary music group performance in NYC">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/music-misc-webp/pepBand.webp" alt="MHS pep band on Thanksgiving">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/music-misc-webp/ftmPT6.webp" alt="Contemporary music group performance in NYC">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/music-misc-webp/govaward2.webp" alt="receiving the NJ governor's award in arts education">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/music-misc-webp/nycTuba.webp" alt="tuba + subway = bad time?">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/music-misc-webp/mattStevieTapes.webp" alt="Recording audition tapes with my uncle Stevie">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/music-misc-webp/pt64.webp" alt="Taking the PT6 home">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/music-misc-webp/twoba.webp" alt="mirafone hegemony at nationals">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/music-misc-webp/njpac-onstage.webp" alt="ASO onstage">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/music-misc-webp/regions3.webp" alt="post regions">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/music-misc-webp/matt_and_eggebeen.webp" alt="matt and eggebeen">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/music-misc-webp/studio95.webp" alt="taking a nap">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/music-misc-webp/6th_grade_regions.webp" alt="6th grade regions">
<figcaption></figcaption>
</figure>

</div>

<div class="last-row">
  <figure>
  <img src="../images/music-misc-webp/njpac-blur.webp" alt="njpac accidental panning">
  <figcaption></figcaption>
  </figure>
</div>

</details>

<hr class="darker">

<details open>
<summary class="gallery">NMF 2016</summary>
<div class="section">

<figure>
<img src="../images/music-misc-webp/nmf-tutti.webp" alt="NMF 2016 tutti orchestra">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/music-misc-webp/oph-on-stage.webp" alt="matt on stage with ophicleide">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/music-misc-webp/nmf-brass.webp" alt="NMF partial brass section">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/music-misc-webp/carter-matt-hq.webp" alt="Myself and Carter">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/music-misc-webp/lowbrass-stage2.webp" alt="Low brass at NMF">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/music-misc-webp/king-carter.webp" alt="Low brass at NMF">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/music-misc-webp/brass-atrium.webp" alt="Festival Opening Ceremony">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/music-misc-webp/oph-atrium.webp" alt="Festival Opening Ceremony">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/music-misc-webp/matt-mike-SF.webp" alt="Symphonie Fantastique on Ophicleide & Serpent">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/music-misc-webp/mute-n-apple.webp" alt="'artsy' mute shot">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/music-misc-webp/nmf-rehearsal1.webp" alt="in rehearsal">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/music-misc-webp/oph-on-stage2.webp" alt="SF with oph">
<figcaption></figcaption>
</figure>

</div>

<div class="last-row">
  <figure>
  <img src="../images/music-misc-webp/nmf-low-brass.webp" alt="The low brass section of NMF 2016">
  <figcaption></figcaption>
  </figure>
</div>

</details>

<hr class="darker">

<details open>

<summary class="gallery">UNC</summary>

<div class="section">

<figure>
<img src="../images/webp-unc/UNCSO1.webp" alt="UNCSO">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/webp-unc/duke-chapel-color-diff.webp" alt="UNCSO">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/webp-unc/WarRequiem.webp" alt="UNCSO">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/webp-unc/matt-ben-recital.webp" alt="Matt and Ben post recital">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/webp-unc/UNCSO2.webp" alt="UNCSO Low brass (partial) closeup">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/webp-unc/bronto-mitt-matt.webp" alt="matt and his pal bronto">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/webp-unc/brso.webp" alt="Stay busy">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/webp-unc/matt-andrew-belltower.webp" alt="belltower">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/webp-unc/bruckner4.webp" alt="Post-Bruckner 4">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/webp-unc/quartet-memorial.webp" alt="Tuba/Euph Quartet at Memorial">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/webp-unc/falstaffiade.webp" alt="Recital - Koetsier Falstaffiade">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/webp-unc/quintet-matt.webp" alt="Quintet in Person Recital">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/webp-unc/uncso-full-brass.webp" alt="UNCSO Full Brass">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/webp-unc/sackbut_spitvalve.webp" alt="Lowest brass">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/webp-unc/sackbut-durham.webp" alt="Lowest brass">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/webp-unc/UNCSO3.webp" alt="Lowest brass">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/webp-unc/pma.webp" alt="Lowest brass">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/webp-unc/mattEJ2.webp" alt="Lowest brass">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/webp-unc/unc-grad.webp" alt="Playing at graduation">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/webp-unc/cimbasso-pit.webp" alt="Meat in the Pit">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/webp-unc/duke-ch-rcm.webp" alt="RCM & UNC">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/webp-unc/baadsvik-matt.webp" alt="With Øystein Baadsvik">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/webp-unc/durham-bb.webp" alt="from the choir loft">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/webp-unc/cimbasso-standing.webp" alt="Playing cimbasso while standing">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/webp-unc/artsy-tuben.webp" alt="tuben">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/webp-unc/jon-matt.webp" alt="goofin">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/webp-unc/ITEF.webp" alt="at ITEF">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/webp-unc/durham-bb2.webp" alt="at the altar">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/webp-unc/mahler8.webp" alt="Mahler 8">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/webp-unc/meymandi-grandma.webp" alt="cramped">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/webp-unc/WE-matt-andrew.webp" alt="Wind Ensemble ft. Andrew">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/webp-unc/tuben-moben.webp" alt="Moby-action valve">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/webp-unc/requiem.webp" alt="Victoria Requiem">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/webp-unc/spodermin.webp" alt="with great power comes great electricity">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/webp-unc/quintet-on-the-road.webp" alt="It's...alive!">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/webp-unc/bronto-in-a-rut.webp" alt="bronto propulsion lab">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/webp-unc/mahler10.webp" alt="Mahler 10">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/webp-unc/thumbwar.webp" alt="Stay busy">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/webp-unc/durham-bb3.webp" alt="Slip n' Slide">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/webp-unc/ITEF2.webp" alt="changeup">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/webp-unc/mattEJ3.webp" alt="EJ & Myself - bell tower">
<figcaption></figcaption>
</figure>

<figure>
<img src="../images/webp-unc/flwrs.webp" alt="Someone gave me flowers">
<figcaption></figcaption>
</figure>

<!-- 
<figure>
<img src="../images/webp-unc/sbut-no-mike.webp" alt="w/out mike">
<figcaption></figcaption>
</figure> -->

</div>

<div class="last-row">
  <figure class="span-full">
    <img src="../images/webp-unc/uncso-rear.webp" alt="UNCSO low brass from behind">
  <figcaption></figcaption>
  </figure>
</div>

</details>

<hr class="darker">

<style>
  div.record-container {
    width: 67.45rem;
    display: flex;
    /* grid-template-columns: 21.5rem 21.5rem; */
    column-gap: 0.5rem;
    row-gap: 2rem;
    align-items: center;
    justify-content: center;
  }

  figure.rect-rec {
    /* position: relative; */
    width: 28rem;
    /* height: 22rem; */
    /* margin-bottom: 1rem; */
    margin-top: 0rem;
    margin-bottom: 0rem;
  }

  iframe.rect-rec {
    width: 28rem;
  }

  figure.rect-large {
    /* position: relative; */
    width: 48rem;
    /* margin-bottom: 1rem; */
    margin-top: 0rem;
    margin-bottom: 0.8rem;
  }

  iframe.rect-large {
    width: 48rem;
  }

  figure.rect-triple {
    position: relative;
    width: 18rem;
    height: 12rem;
    margin-bottom: 2rem;
  }

  iframe.rect-triple {
    width: 18rem;
  }

  figure.short {
    /* position: relative; */
    width: 20rem;
    /* margin-bottom: 2rem; */
    margin-top: 0rem;
    margin-bottom: 0rem;
  }

  iframe.short {
    width: 20rem;
  }

  div.single {
    display: block;
    margin: auto;
    width: inherit;
    margin-bottom: 1.5rem;
  }

  figure.single, figure.single > iframe {
    margin: auto;
    width: 28rem;
  }

  figcaption.short {
    /* position: absolute; */
    top: 37.6rem;
    margin-top: 0rem;
  }

  figcaption.rect-rec {
    /* position: absolute; */
    /* top: 16rem; */
    margin-top: 0rem;
  }

  figcaption.rect-triple {
    /* position: absolute; */
    /* top: 10rem; */
    margin-top: 0rem;
  }

  figcaption.rect-large {
    margin-top: 0.2rem;
  }

/* div.record-section {
  width: 67.45rem;
  display: flex;
  align-items: center;
  justify-content: center;
} */

div.record-section {
	width: 67.45rem;
	display: flex;
	justify-content: center;
	height: fit-content !important;
	flex-direction: row;
	align-items: start;
	gap: 2rem;
}

div.record-section-short {
  width: 67.45rem;
  display: flex;
  flex-direction: row;
  align-items: start;
  justify-content: space-around;
  margin-top: 0.4rem;
  margin-bottom: 2rem;
}

div.fluid-width-video-wrapper {
  margin-bottom: 0.4rem !important;
}

</style>

<details id="recordings" open>
<summary class="gallery">Misc Recordings</summary>
<p>
  Unfortunately, most of the recordings I have made over the years were lost after an older laptop died right before the onset of covid. Here's some of the recordings I was able to recover, albeit low quality ones as they were generally made with a very old iPhone camera/mic. Others are YouTube videos of live performances.
</p>

<div class="record-section">
  <figure class="rect-large">
    <iframe class="rect-large" width="560" height="315" src="https://www.youtube.com/embed/9xN6CouzZ70?si=LLDh5VrVgvU_NiQa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    <figcaption class="rect-large">Bruckner Symphony No. 4, <em>Romantische</em>. I'm torn on linking just the low brass highlights from the performance. The piece is monumental; lush, brooding, expansive. Words do no justice.</figcaption>
  </figure>
</div>

<div class="record-section">
<figure class="rect-rec">
    <iframe class="rect-rec" width="560" height="315" src="https://www.youtube.com/embed/2_uWm7Qw8SE?si=794Q6Q5IWEoFf9-q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    <figcaption class="rect-rec">Bruckner 8 in Ram's parking deck to give the folks at light night a show. I'm out of frame, but the this was of course on the contrabass (silver)</figcaption>
  </figure>
  
  <figure class="rect-rec">
    <iframe class="rect-rec" width="560" height="315" src="https://www.youtube.com/embed/2DOZoixFfyY?si=71czVarOlJyvMP-R" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    <figcaption class="rect-rec">Some early music. Title unknown. Youtube seems to think it's an original composition from a film, but the melody and bassline were pulled out of a pre-classical music history textbook</figcaption>
  </figure>
</div>

<div class="record-section-short">
  <figure class="short">
    <iframe class="short" width="300" height="560" src="https://youtube.com/embed/EdqeiqruZrk?si=rkknyKxhfKXU4r6E" title="YouTube video player"
    frameborder="0" allow="accelerometer; autoplay; clipboard-write encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    <figcaption class="short">First rehearsal on my cimbasso. Was still very much getting the feel for it. Excuse the omitted notes</figcaption>
  </figure>

  <figure class="short">
    <iframe class="short" width="300" height="560" src="https://youtube.com/embed/jUn5pLqAroA?si=fv9frxi9aCKzU-v7" title="YouTube video player"
    frameborder="0" allow="accelerometer; autoplay; clipboard-write encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    <figcaption class="short">Rehearsal of my arrangement of Bo Burnham's <em>Goodbye</em>. The show including this track marked the end of a 5 year hiatus from performing - and worse, practicing at all. Chops were still regaining their strength.</figcaption>
  </figure>
</div>

<div class="record-section">
  <figure class="rect-large">
    <iframe class="rect-large" width="560" height="315" src="https://www.youtube.com/embed/Wa08EktDEwc?si=nx8QPxeaCY_eWayN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    <figcaption class="rect-large">"Danse bacchanale" from <em>Samson et Dalila</em> with UNCSO. Frenetic, sublime, explosive, as a bacchanale should be I suppose.</figcaption>
  </figure>
</div>

<div class="record-section">
<figure class="rect-rec">
    <iframe class="rect-rec" width="560" height="315" src="https://www.youtube.com/embed/2E93Jvaykdo?si=Rtv86TVdc-WHAjPi" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    <figcaption class="rect-rec">Scherzo from Shostakovich 10 arranged for brass band. Was still getting used to Eb bass transposition, did a stand recording to check pitches. Half decent I'd wager. </figcaption>
  </figure>
  
  <figure class="rect-rec">
    <iframe class="rect-rec" width="560" height="315" src="https://www.youtube.com/embed/ovOGb0LrOOM?si=fDQfYPTE5rYjvDGP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    <figcaption class="rect-rec">As Mr. DNA would say, <a class="noul" href="https://www.reddit.com/r/JurassicPark/comments/9166bh/thanks_to_the_original_movie_i_cant_say_dinosaur/?rdt=43163">Dino<em>sawr</em></a>. This was at ITEF 2018, Dr. Adam Frey conducting a 300 piece tuba/euph choir, with myself on Cimbasso.</figcaption>
  </figure>
</div>

<div class="record-section">
  <figure class="rect-large">
    <iframe class="rect-large" width="560" height="315" src="https://www.youtube.com/embed/9hLF8JwjTCQ?si=S29KBUAiPRhD_pZj&amp;start=273" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    <figcaption class="rect-large">Verdi sans cimbasso. The whole overture is great, linked ~halfway through here.</figcaption>
  </figure>
</div>

<div class="record-section">
  <figure class="rect-rec">
    <iframe class="rect-rec" width="560" height="315" src="https://www.youtube.com/embed/ORGNAatIIbY?si=fE-hC5KnzSYPzIJg" title="YouTube video player"
    frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    <figcaption class="rect-rec"><em>Symphonie Fantastique</em> rehearsal clip, on ophicleide (we called this oph the (awful)cleide because it was falling apart and nigh impossible to get in tune. I had about a month and a half to learn how to play it. I thought following NMF I would never play it again, but that thing kept haunting me).</figcaption>
  </figure>

  <figure class="rect-rec">
    <iframe class="rect-rec" width="560" height="315" src="https://www.youtube.com/embed/UjwaBo3YsWs?si=7WBEeRSiY502VXk8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    <figcaption class="rect-rec">reconvening after summer break to aggressively blast excerpts at midnight is a bad habit, but it's fun</figcaption>
  </figure>
</div>

<div class="record-section">
  <figure class="rect-large">
    <iframe class="rect-large" width="560" height="315" src="https://www.youtube.com/embed/eAbvQAYtOZg?si=TRTO2fRJbEispnee&amp;start=1274" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    <figcaption class="rect-large">Clip from the final phrases of Hindemith's <em>Nobilissima visione</em> with UNCSO. We had a saying for when the trombones and I let loose: <em>run the meat</em></figcaption>
  </figure>
</div>

<div class="record-section-short">
  <figure class="short">
    <iframe class="short" width="300" height="560" src="https://youtube.com/embed/W3Q-wKn8yOc?si=xWnLrwBdXhOj2N2c" title="YouTube video player"
    frameborder="0" allow="accelerometer; autoplay; clipboard-write encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    <figcaption class="short">First rehearsal using the <em>Elektra</em>. Quintet had a yearly gig at the white-coating ceremony and Holst was always a fan-favorite (aka nobody paid attention to us)</figcaption>
  </figure>

  <figure class="short" >
    <iframe class="short" width="300" height="560" src="https://youtube.com/embed/OB-tpZYnxXs?si=p14SfIibSfnf554l" title="YouTube video player"
    frameborder="0" allow="accelerometer; autoplay; clipboard-write encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    <figcaption class="short"><em>Symphonie Fantastique</em> finale excerpt (not on ophicleide though thank gawd). I had realized there's an alternate fingering which makes the bursts of maniacal laughter easier and wanted to check the sound. Notes were missed, but I played more than was necessary to make check</figcaption>
  </figure>
</div>

<div class="record-section">
  <figure class="rect-large">
    <iframe class="rect-large" width="560" height="315" src="https://www.youtube.com/embed/wKJTnt2PGNs?si=Mu4-pDqvC5R0kEFI&amp;start=451" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    <figcaption class="rect-large">Some Berlioz with UNCSO. Something something 'all music is love music, pirate music, or both'</figcaption>
  </figure>
</div>

<div class="record-section-short">
  <figure class="short" >
    <iframe class="short" width="300" height="560" src="https://youtube.com/embed/tuK_QbsmjnA?si=E9qUSy6LD_zvoBqn" title="YouTube video player"
    frameborder="0" allow="accelerometer; autoplay; clipboard-write encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    <figcaption class="short">Goofin around. Simply a scale; I can't recall if the phrase is from Miklos Rozsa's film score to <em>The Thief of Bagdad</em> or one of the other pieces we did at NMF</figcaption>
  </figure>

  <figure class="short" >
    <iframe class="short" width="300" height="560" src="https://www.youtube.com/embed/pP1aE5UQ3bk" title="YouTube video player"
    frameborder="0" allow="accelerometer; autoplay; clipboard-write encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    <figcaption class="short">During that same white-coat rehearsal. My good pal Danny likes this folk tune.</figcaption>
  </figure>
</div>

<div class="record-container">
  <figure class="rect-large">
    <iframe class="rect-large" width="560" height="315" src="https://www.youtube.com/embed/zvaSX1aJ6MU?si=vW6JBAmfqb3JpcEL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    <figcaption class="rect-large">A wild ophicleide appeared - cover your ears. Nah at this point I was slightly better on oph, so maybe just partially cover (Oph is tacit for most of this so most would probably get bored and check out by the time the ophicleide (me) enters. Either they're startled awake by the atrocious sound, or bissfully unaware of the crimes against tonality propagating past them).</figcaption>
  </figure>
</div>

<div class="record-section-short">
  <figure class="short" >
    <iframe class="short" width="300" height="560" src="https://youtube.com/embed/81sWr58K6Gc?si=nTANxBLwkUeN_BZ3" title="YouTube video player"
    frameborder="0" allow="accelerometer; autoplay; clipboard-write encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    <figcaption class="short">Attempting the triplet varation of Carnival of Venice on...cimbasso? Why not.</figcaption>
  </figure>

  <figure class="short" >
    <iframe class="short" width="300" height="560" src="https://youtube.com/embed/8y0B7OQHQUc?si=oAInmCGfRwQ-lH0J" title="YouTube video player"
    frameborder="0" allow="accelerometer; autoplay; clipboard-write encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    <figcaption class="short">Carnival of Venice triplet variation again, but on bass tuba. Only linked to demo the differences in sound, I forgot to turn the page, and got butterfingers to boot. You can tell by my vocalizations I wasn't pleased.</figcaption>
  </figure>
</div>

<div class="record-section">
  <figure class="rect-large">
    <iframe class="rect-large" width="560" height="315" src="https://www.youtube.com/embed/6oOCbNENMYc?si=Q3dlqXnPotFUnIa2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    <figcaption class="rect-large">Britten, as it's written. We actually did Britten's War Requiem the year before this, however the recording is not public.</figcaption>
  </figure>
</div>

<div class="record-section">
  <figure class="rect-large">
    <iframe class="rect-large" width="560" height="315" src="https://www.youtube.com/embed/9TxqOCjhvHo?si=_Icg18sulZOgwmDr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    <figcaption class="rect-large">Some Brahms for your evening listening.</figcaption>
  </figure>
</div>

</details>




