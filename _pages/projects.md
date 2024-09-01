---
layout: archive
title: "Projects"
permalink: /projects/
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

  summary:hover {
    text-shadow: 4px 4px 8px;
  }

  summary.doc {
    font-size: 0.9rem;
    font-weight: 300rem;
  }

  summary:hover {
    text-shadow: 4px 4px 8px;
  }

  details > p {
    margin-left: 1.3rem;
    margin-bottom: 0.6rem;
    margin-top: 0.4rem;
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

  img.center {
    text-align: center;
    display: block;
    margin: 0 auto;
  }

  details.doc, details.proof, details.arr, details.audio {
    margin-left: 0.8rem;
  }

  details.doc > summary, details.proof > summary, details.arr > summary, details.audio > summary {
    font-size: 1.1rem;
    font-weight: 500;
    margin-bottom: 1rem;
  }

  div.code {
    display: flex;
    gap: 1rem;
  }

  div.input {
    display: flex;
    gap: 0.4rem;
  }

  cite {
    color: gray;
    font-size: 0.9rem;
    margin-left: 1rem;
    margin-bottom:: 0rem;
    margin-top: 0.45rem;
  }

  div.arr-list {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 2rem;
  }

  div.arr-list > * {
    max-width: fit-content;
  }

  div.sib {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 2rem;
  }

  div.av {
    margin-top: 1rem;
    width: inherit;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 1rem;
  }

  figcaption {
    caption-side: top;
  }

  figure {
    display: block;
  }

  audio {
    border-radius: 8px;
  }

  figure {
    margin-top: .5rem;
    margin-bottom: .5rem;
  }

</style>

<link rel="stylesheet" href="/docs/prism(okaida).css">

<h2 class="larger-heading">Software</h2>
------

<details open>
<summary class="project">Music CPR</summary>
<p class="roles"><em>Lead:</em> <a class="noul" target="_blank" href="https://hcientist.com/">Dr. Michael Stewart</a>   |   <em>Collaborator since 2023/08</em>   |   <a class="noul" target="_blank" href="https://github.com/Lab-Lab-Lab/CPR-Music">Github</a></p>
  <cite>from <a class="noul" href="httcites://musiccpr.org/about">musiccpr.org:</a></cite>
  <p>
    MusicCPR is a free web-based platform to promote standards-based instrumental music education. MusicCPR aligns with four artistic processes found in National Standards for Music Education: create, perform, respond, and connect and their manifestations in state standards for instrumental music education. 
  </p>

  <h3>Contributions</h3>
  <ul>
    <li>
      Construction of a rudimentary digital audio workstation (DAW) as part of work towards an honors thesis.
      <figure>
      <img src="/images/features-1.png" style="width: 100%">
      <figcaption>Simple digital audio workstation constructed as part of my honor's thesis.</figcaption>
      </figure>
    </li>
    <li>
      DevOps - attempts to streamline development environment setup through assistance with devcontainers and codespaces, and my own work configuring quickly reproducible linux disk images, initially using <code>archiso</code>, then NixOS configurations.
    </li>
    <li>
      Algorithms for musical variations generation such as rhythmic & melodic permutations and retrograde.
      <figure>
      <img src="/images/variations1a.png" style="width: 100%; margin-top: 1rem" />
      <figcaption>Student motives from which to procedurally generate and render 11 musical variations.</figcaption>
      </figure>
      <figure>
        <img src="/images/variations2a.png" style="width: 100%; margin-top: 1rem" />
        <figcaption>The procedurally generated variations plus original motive combined into a single score.</figcaption>
      </figure>
    </li>
    <li>Musical consultation & preparation of references to make certain tasks easier for non-musician programmers, e.g., <a class="noul" href="../images/CPR/transposition_reference.png">Transposition Reference</a></li>
    <li>Reduction of tech-debt and general bug fixes</li>
  </ul>
</details>

<details open>
  <summary class="project">woof.sh</summary>
  <p class="roles"><em>Author</em> | <a class="noul" target="_blank" href="https://github.com/mfwolffe/woof">Github</a></p>
  <p>A command line utility (bash script) that randomly selects photos of Moby the border-aussie (or your own pup) and renders them in ascii art within the terminal, as stylishly or simply as the user so desires.</p>
</details>

<details open>
<summary class="project">A Better ATan2</summary>
<p class="roles"><em>Author</em> | <a class="noul" target="_blank" href="https://mfwolffe.github.io/improved-atan2/">Link</a></p>
  <p>A personal project I made as practice for learning (vanilla) JavaScript, and to save myself time when tutoring precalculus students.</p>
</details>

<details open>
<summary class="project">LocalToast</summary> 
<p class="roles"><em>Author</em> | <a class="noul" target="_blank" href="https://github.com/mfwolffe/localtoast">Github</a></p>
  <p>This is really a group of gag/joke projects; each one rhymes with "localhost". Others include LocalRoast, LocalGhost, and LocalBoast. LocalToast finds restaurants nearby which serve toast on their menu and allows you to review <strong><em>only</em></strong> the toast.</p>
</details>

<details open>
<summary class="project">Digital Dipole</summary>
<p class="roles"><em>Author</em> | <a class="noul" target="_blank" href="https://github.com/mfwolffe/digitaldipole">Github</a></p>
  <p>
    Digital Dipole is a chemistry toolkit web app. The project started as a JavaFX app, but I quickly realized that in order to accomplish what I want, I would have to switch platforms/frameworks and it is being migrated to a web app built with React, Vite, Django, and React-Bootstrap.
  </p>
</details>

<details open>
<summary class="project"><math display="inline" class="tml-display" style="display:block math;">
  <mrow>
    <mn>6</mn>
    <mi>n</mi>
    <mo>±</mo>
    <mn>1</mn>
  </mrow>
</math>Primality Test Instrumentation</summary>
<p class="roles"><em>Author</em></p>

  <p>A necessary, though not sufficient condition of primailty for an integer <math display="inline" class="tml-display" style="display:block math;">
  <mrow>
  <mi>p</mi>
  </mrow>
</math> greater than 3, is whether it is of the form <math display="inline" class="tml-display" style="display:block math;">
<mrow>
  <mi>p</mi>
    <mo>=</mo>
    <mn>6</mn>
    <mi>n</mi>
    <mo>±</mo>
    <mn>1</mn>
  </mrow>
  </math></p>
<p>
  The goal of this small project is to compare just how much faster a <math display="inline" class="tml-display" style="display:block math;">
  <mrow>
    <mn>6</mn>
    <mi>n</mi>
    <mo>±</mo>
    <mn>1</mn>
  </mrow>
</math>
Primality algorithm is compared to a brute-force approach on modern hardware with compiler optimizations. Dr. Michael Lam provided the impetus to try my hand at instrumenting these functions while I was in his Systems/Architecture class, along with suggestions of tools to use.
</p>
<br>
<details>
<summary class="project" style="padding-left: 1rem">Code</summary>
<p>Instrumentation will be done on functions written in C. I've included a python and C# version just because the oneliners are just so <em>fun</em></p>
<form id="radio" action="">
<fieldset>
  <div class="code">
    <div class="input">
      <input type="radio" id="c" name="isPrime" value="c_block" checked>
      <label for="c">C</label>
    </div>
    <div class="input">
      <input type="radio" id="py" name="isPrime" value="py_block">
      <label for="py">Python</label>
    </div>
    <div class="input">
      <input type="radio" id="cs" name="isPrime" value="cs_block">
      <label for="jav">C#</label>
    </div>
  </div>
</fieldset>
</form>

<style>
  .comment::after {
    clear: both;
    display: inline !important;
  }

  .comment {
    border-bottom: 0px !important;
  }
</style>

  <div class="box" id="c_block">
    <pre class="language-clike">
      <code class="language-clike line-numbers" data-prismjs-copy="Copy">#include &lt;stdio.h&gt;
      #include &lt;stdbool.h&gt;
  
      bool isPrime(int p) {
        if (p &lt;= 1)
          return false;   // 1 is not prime

        if (p &lt;= 3)
          return true;    // 2 and 3 are prime

        /* the loop below this leaves a gap b/c of the increment and
         * initial value i=5
         * i.e., 4, 6, 7, 8, 9, and 10 will not be examined with just
         * the loop and so 4, 6, 8, 9, and 10 would be incorrectly 
         * flagged as prime without the check below */
        if (p % 2 == 0 || p % 3 == 0)
          return false;

        // check all numbers between 5 and sqrt(n) with step=6
        for (int i = 5; (i * i) &lt;= p; i += 6)
          if (p % i == 0 || p % (i + 2) == 0)
            return false;
  
        return true;    // if you've made it this far, you're prime
      }
  </code>
  </pre>
  
  </div>
  
  <div class="box" id="py_block" style="display: none; width: 60rem;">
    <pre>
      <code class="language-python line-numbers" data-prismjs-copy="Copy">from math import sqrt

      def isPrime(p):
        if p &lt;= 1:
          return False

        if p &lt;= 3:
          return False

        if p % 2 == 0 or p % 3 == 0:
          return False

        # how legible, how fun!
        return not(any(p % i == 0 or p % (i + 2) == 0 for i in range(5, int(sqrt(p)), 6)))
  </code>
  </pre>
  </div>

  <div class="box" id="cs_block" style="display: none; width: 58rem;">
    <pre>
      <code class="language-csharp line-numbers" data-prismjs-copy="Copy">using System;
      using System.Linq;

      class Primality {

        static bool isPrime(int p) {
          if (p &lt;= 1)
            return false;

          if (p &lt;= 3)
            return true;

          if (p % 2 == 0 || p % 3 == 0)
            return false;

          // and you thought the python one-liner was bizarre ~_~
          return !(Array.Exists(Enumerable.Range(5, (int)Math.Sqrt(p))
                        .SkipWhile(i =&gt; i % 6 == 0)
                        .ToArray&lt;int&gt;(), (int x) =&gt; p % x == 0 || p % (x + 2) == 0));
        }
      }
  </code>
  </pre>
  
  </div>
</details>
</details>

<h2 class="larger-heading">Music</h2>
------

<details  open>
<summary class="project">A Tribute to Ennio Morricone</summary>
<p class="roles"><em>Arranger</em></p>

  <p>
    Italian composer Ennio Morricone, made famous by his sonically expansive film scores and distinctive style, sadly passed away in 2020. In my eyes, when discussing scores of westerns, Maestro Morricone's oeuvre is superlative. I have long loved his music and decided in June of 2023 to start arranging a tribute to the Maestro, similar to the live concerts he would conduct throughout the world.  Maestro Morricone's body of work is of course not public domain, so the majority of my score is transcribed by ear.
  </p>

  <p>
    The tribute is scored for extended orchestra and choir. I have begun to teach myself harmonica and stone flute (acquired from <a class="noul" href="https://stonewhistle.com/">Stonewhistle</a>) so that I can contribute more than just brass to an eventual overdub (live performance is out of the question due to licensure and scope of course).
  </p>

  <details class="audio">
    <summary>Audio snippets</summary>
    <p>
      The following are brief audio clips (Sibelius Sounds 7) of certain tracks within the tribute. 
      Balance and timbre can be better controlled in Pro Tools, but I don't plan on adjusting with such granularity until I have completed the tribute.
    </p>
      <div class="sib">
        <figure>
          <figcaption>from <em>Il Clan dei Siciliani</em></figcaption>
          <audio controls src="/audio/il_clan_dei_siciliani.mp3"></audio>
        </figure>
        <figure>
          <figcaption>from <em>le vent le cri</em></figcaption>
          <audio controls src="/audio/le_vent_le_cri.mp3"></audio>
        </figure>
      </div>
      <div class="sib">
        <figure>
          <figcaption>from <em>C'era una volta il West</em></figcaption>
          <audio controls src="/audio/cera_una_volta_il_west.mp3"></audio>
        </figure>
        <figure>
          <figcaption>from <em>Giù la testa</em></figcaption>
          <audio controls src="/audio/giu_la_testa.mp3"></audio>
        </figure>
      </div>
      <div class="sib">
        <figure>
          <figcaption>from <em>Come una sentenza</em></figcaption>
          <audio controls src="/audio/come_una_sentenza.mp3"></audio>
        </figure>
        <figure>
          <figcaption>from <em>le vent le cri (reprise)</em></figcaption>
          <audio controls src="/audio/le_vent_le_cri_reprise.mp3"></audio>
        </figure>
      </div>
      <div class="sib">
        <figure>
          <figcaption>from <em>Addio a Cheyenne</em></figcaption>
          <audio controls src="/audio/addio_a_cheyenne.mp3"></audio>
        </figure>
        <figure>
          <figcaption>from <em>Here's to You</em></figcaption>
          <audio controls src="/audio/heres_to_you.mp3"></audio>
        </figure>
      </div>
      <div class="sib">
        <figure>
          <figcaption>from <em>il triello</em></figcaption>
          <audio controls src="/audio/il_triello.mp3"></audio>
        </figure>
      </div>
  </details>
</details>

<details open>
<summary class="project">Other Arrangements</summary>
<p class="roles"><em>Arranger</em></p>

  <p>
    I have been arranging/transcribing/transposing since middle school. Finding a medley of John Williams film score tracks written for my instruments is generally a bit harder than for say, a trumpet player, so I learned to transpose early. A lot of the music is not public domain however, and so if I want to put together an arrangement, I often have to do it by ear. Here is a list of some recent arrangements I enjoyed putting together:
  </p>

  <details class="arr">
  <summary class="doc">Recent Arrangements</summary>
    <div class="arr-list">
      <ul>
        <li>
        <em>Goodbye</em><br>
          <cite>
            Bo Burnham
          </cite>
        </li>
        <li>
        <em>Without You</em><br>
          <cite>
            Evans & Ham (Nilsson version)
          </cite>
        </li>
        <li>
        <em>Froh Wie Seine Sonnen Fliegen</em><br>
          <cite>
            (tenor solo from <em>Symphony No. 9</em>) Beethoven
          </cite>
        </li>
        <li>
        <em>O Bella Ciao</em><br>
          <cite>
            Traditional
          </cite>
        </li>
        <li>
        <em>We'll Meet Again</em><br>
          <cite>
            Vera Lynn
          </cite>
        </li>
      </ul>
      <ul>
        <li>
        <em>That Funny Feeling</em><br>
          <cite>
            Bo Burnham
          </cite>
        </li>
        <li>
        <em>Who's Side Are You On</em><br>
          <cite>
            Pete Seeger
          </cite>
        </li>
        <li>
        <em>Grandma on the Roof</em><br>
          <cite>
            Alex Weston
          </cite>
        </li>
        <li>
        <em>Six Day War</em><br>
          <cite>
            Colonel Bagshot
          </cite>
        </li>
        <li>
        <em>Waiting for Hasan</em><br>
          <cite>
            Lily Ki
          </cite>
        </li>
      </ul>
    </div>
  </details>

</details>

<h2 class="larger-heading">Audio-Visual</h2>
------

<details>
<summary class="project">20th Century Crisis</summary>
<p class="roles"><em>Author</em></p>

  <p>
    This project is an antiwar retrospective on the 20th century, specifically examining the periodicity of greed and hypocrisy sparking global conflict, followed by injustice and hysteria on that same scale, finally culminating with the rise of fascism.
  </p>
  <p>
    German philosopher Georg Wilhelm Friedrich Hegel's Dialectic is characterized by periodic shifts from thesis to antithesis before finally reaching synthesis. Marx and Engels extended this concept to describe history in a materialistic sense; in layman's terms, development is propelled by the swinging of popular mood from one extreme to another over time, before eventually coming to rest, waiting for the next spark of momentum.
  </p>
  <p>
    The project directs viewers/listeners to reflect on the 'swings' of the 20th century and ask themselves, have we as a species ever really reached a synthesis? <em>Is it even possible?</em> If so, is that period of repose doomed to transience? Finally, it asks viewers to examine the world today and consider whether the displacement from synthesis is decreasing as it should, or increasing. Is the dimly flickering light at the end of the tunnel actually an oncoming train?
  </p>

  <div class="av">
    <img src="/images/AV_201.gif" alt="clip from 20th Century Crisis" width="250px">
    <img src="/images/AV_202.gif" alt="clip from 20th Century Crisis" width="250px">
    <img src="/images/AV_203.gif" alt="clip from 20th Century Crisis" width="250px">
  </div>

</details>

<script src="/docs/prism(okaida).js"></script>

<script>

  let form = document.getElementById("radio");
  let radios = document.getElementsByName("isPrime");

  form.addEventListener("input", function(event) {

  let lang = document.querySelector('input[name="isPrime"]:checked').value;

  for (radio of radios) {
    if (radio.value != lang) {
      document.getElementById(radio.value).style.display = "none";
    }
    else {
        document.getElementById(radio.value).style.display = "block";
    }
  }

});


</script>
