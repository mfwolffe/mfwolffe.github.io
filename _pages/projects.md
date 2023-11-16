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

  details.doc, details.proof, details.arr {
    margin-left: 0.8rem;
  }

  details.doc > summary, details.proof > summary, details.arr > summary {
    font-size: 1rem;
    font-weight: 400rem;
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



</style>

<link rel="stylesheet" href="/docs/prism(okaida).css">

<h2>WIP</h2>

<h2 class="larger-heading">Computer Science</h2>
------

<details open>
<summary class="project">Music CPR</summary>
<p class="roles"><em>Lead:</em> <a class="noul" target="_blank" href="https://hcientist.com/">Dr. Michael Stewart</a>   |   <em>Collaborator since 2023/08</em>   |   <a class="noul" target="_blank" href="https://github.com/JMU-CIME/CPR-Music">Github</a></p>

  <cite>from <a class="noul" href="httcites://musiccpr.org/about">musiccpr.org:</a></cite>
  <p>
    MusicCPR is a free web-based platform to promote standards-based instrumental music education. MusicCPR aligns with four artistic processes found in National Standards for Music Education: create, perform, respond, and connect and their manifestations in state standards for instrumental music education. 
  </p>


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
  <p>The styling is <em>very</em> basic, perhaps even ugly.</p>

</details>

<details open>
<summary class="project">GUI General Chemistry Toolkit (WIP)</summary>
<p class="roles"><em>Author</em></p>

  <p>
    JavaFX GenChem Toolkit. Started in 2022, but due to work and school, can only work on it intermittently. Contains various chemistry tools, like limiting reagent calculator & gas law calculators.
  </p>

  <p>
    The plan for this project is to migrate to either another framework or language altogether. While JavaFX can meet a lot of my goals for the app, there are certain tasks which prove to be such a headache it may be worth switching paradigms.
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
</math>Primality Test Instrumentation (WIP)</summary>
<p class="roles"><em>Author</em></p>

  <p>A necessary, though not sufficient condition of primailty for an integer <math display="inline" class="tml-display" style="display:block math;">
  <mrow>
  <mi>N</mi>
  </mrow>
</math> greater than 3, is whether it is of the form <math display="inline" class="tml-display" style="display:block math;">
<mrow>
  <mi>N</mi>
    <mo>=</mo>
    <mn>6</mn>
    <mi>n</mi>
    <mo>±</mo>
    <mn>1</mn>
  </mrow>
  </math></p>
  <p>Symbolically, this can be shown as: <math display="block" class="tml-display" style="display:block math;">
  <mrow>
    <mi>∀</mi>
    <mspace width="0.5em"></mspace>
    <mi>p</mi>
    <mo>&gt;</mo>
    <mn>3</mn>
    <mo>∈</mo>
    <mtext>PRIMES, </mtext>
    <mi>∃</mi>
    <mspace width="0.5em"></mspace>
    <mi>n</mi>
    <mo>∈</mo>
    <mi>ℤ</mi>
    <mo separator="true"></mo>
    <mspace width="0.5em"></mspace>
    <mi>s</mi>
    <mi>.</mi>
    <mi>t</mi>
    <mspace width="0.5em"></mspace>
    <mi>p</mi>
    <mo>=</mo>
    <mn>6</mn>
    <mi>n</mi>
    <mo>±</mo>
    <mn>1</mn>
  </mrow>
</math>
</p>

<p>
  Rather humorously, searching for who first observed this yields forum posts from all across the internet, with an OP claiming they have discovered something <em>incredible</em> about primes. Only for a commenter to state it has been well known for some time.
</p>

<p>
  The goal of this small project is to compare just how much faster a <math display="inline" class="tml-display" style="display:block math;">
  <mrow>
    <mn>6</mn>
    <mi>n</mi>
    <mo>±</mo>
    <mn>1</mn>
  </mrow>
</math>
Primality algorithm is compared to a brute-force approach on modern hardware with compiler optimizations.
</p>

<details class="proof">
<summary>Logic and Algorithm</summary>
<p>The algorithm under consideration follows the below logic</p>
<p>Observe that <em>any</em> integer can be written in the form,<math display="block" class="tml-display" style="display:block math;">
  <mrow>
    <mn>6</mn>
    <mi>n</mi>
    <mo>+</mo>
    <mi>k</mi>
    <mspace width="0.6em"></mspace>
    <mtext>for some integer</mtext>
    <mspace width="0.3em"></mspace>
    <mi>k</mi>
    <mspace width="0.3em"></mspace> 
    <mtext>in the set of integers mod 6:</mtext>
    <mspace width="0.45em"></mspace> 
    <mo form="prefix" stretchy="false">{</mo>
    <mspace width="0.1667em"></mspace>
    <mn>0,1,2,3,4,5</mn>
    <mo form="postfix" stretchy="false">}</mo>
    <mtext>, and a positive integer</mtext>
    <mspace width="0.3em"></mspace>
    <mi>n</mi>
  </mrow>
  </math>

Additionally,</p>
<math display="block" class="tml-display" style="display:block math;">
  <mrow>
    <mn>2</mn>
    <mspace width="0.1667em"></mspace>
    <mi>|</mi>
    <mspace width="0.1667em"></mspace>
    <mn>6</mn>
    <mi>n</mi>
    <mo>+</mo>
    <mn>0</mn>
  </mrow>
</math>
<math display="block" class="tml-display" style="display:block math;">
  <mrow>
    <mn>2</mn>
    <mspace width="0.1667em"></mspace>
    <mi>|</mi>
    <mspace width="0.1667em"></mspace>
    <mn>6</mn>
    <mi>n</mi>
    <mo>+</mo>
    <mn>2</mn>
  </mrow>
</math>
<math display="block" class="tml-display" style="display:block math;">
  <mrow>
    <mn>2</mn>
    <mspace width="0.1667em"></mspace>
    <mi>|</mi>
    <mspace width="0.1667em"></mspace>
    <mn>6</mn>
    <mi>n</mi>
    <mo>+</mo>
    <mn>4</mn>
  </mrow>
</math>
<p>and,</p>
<math display="block" class="tml-display" style="display:block math;">
  <mrow>
    <mn>3</mn>
    <mspace width="0.1667em"></mspace>
    <mi>|</mi>
    <mspace width="0.1667em"></mspace>
    <mn>6</mn>
    <mi>n</mi>
    <mo>+</mo>
    <mn>0</mn>
  </mrow>
</math>
  <math display="block" class="tml-display" style="display:block math;">
  <mrow>
    <mn>3</mn>
    <mspace width="0.1667em"></mspace>
    <mi>|</mi>
    <mspace width="0.1667em"></mspace>
    <mn>6</mn>
    <mi>n</mi>
    <mo>+</mo>
    <mn>3</mn>
  </mrow>
</math>

<p>As such, for any prime <math display="inline" class="tml-display" style="display:block math;">
<mrow>
<mi>p</mi>
<mo>,</mo>
<mspace width="0.5em"></mspace>
<mi>p</mi>
<mspace width="0.1667em"></mspace>
<mo>></mo>
<mspace width="0.1667em"></mspace>
<mn>3</mn>
<mo>,</mo>
<mspace width="0.5em"></mspace>
<mi>p</mi>
<mspace width="0.3em"></mspace>
<mtext>modulo</mtext>
<mspace width="0.3em"></mspace>
<mn>6</mn>
<mspace width="0.3em"></mspace>
</mrow>

</math>is in: 

  <math display="inline" class="tml-display" style="display:block math;">
    <mrow>
      <mo form="prefix" stretchy="false">{</mo>
      <mspace width="0.1667em"></mspace>
      <mn>0,1,2,3,4,5</mn>
      <mspace width="0.1667em"></mspace>
      <mo form="postfix" stretchy="false">}</mo>
      <mspace width="0.1667em"></mspace>
      <mo>\</mo>
      <mspace width="0.1667em"></mspace>
      <mo form="prefix" stretchy="false">{</mo>
      <mspace width="0.1667em"></mspace>
      <mn>0,2,3,4</mn>
      <mspace width="0.1667em"></mspace>
      <mo form="postfix" stretchy="false">}</mo>
      <mspace width="0.1667em"></mspace>
      <mo>=</mo>
      <mspace width="0.1667em"></mspace>
      <mo form="prefix" stretchy="false">{</mo>
      <mspace width="0.1667em"></mspace>
      <mn>1,5</mn>
      <mspace width="0.1667em"></mspace>
      <mo form="postfix" stretchy="false">}</mo>
    </mrow>
  </math>

</p>

<p>Furthermore, note that even in a naïve approach we need not check <em>every</em> number up to <math display="inline" class="tml-display" style="display:block math;">
    <mrow>
    <mi>p</mi>
    </mrow>
  </math>.

It is sufficient to check up to 
<math display="inline" class="tml-display" style="display:block math;">
  <msqrt>
    <mi>p</mi>
  </msqrt>
  </math>.

Hence, we need only check numbers in the range 
<math display="inline" class="tml-display" style="display:block math;">
  <mrow>
    <mo form="prefix" stretchy="false">[</mo>
    <mn>5</mn>
    <mo separator="true">,</mo>
    <msqrt>
      <mi>p</mi>
    </msqrt>
    <mo form="postfix" stretchy="false">]</mo>
  </mrow>
</math>

of the form 
<math display="inline" class="tml-display" style="display:block math;">
  <mrow>
    <mn>6</mn>
    <mi>n</mi>
    <mo>+</mo>
    <mn>1</mn>
  </mrow>
</math>

and 
<math display="inline" class="tml-display" style="display:block math;">
  <mrow>
    <mn>6</mn>
    <mi>n</mi>
    <mo>+</mo>
    <mn>5</mn>
  </mrow>
</math>
.</p>

<br>
<h3>Code</h3>
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
      <input type="radio" id="jav" name="isPrime" value="jav_block">
      <label for="jav">Java</label>
    </div>
    <div class="input">
      <input type="radio" id="cs" name="isPrime" value="cs_block">
      <label for="jav">C#</label>
    </div>
  </div>
</fieldset>
</form>

  <div class="box" id="c_block">
    <pre>
      <code class="language-C line-numbers" data-prismjs-copy="Copy">#include &lt;stdio.h&gt;
      #include &lt;stdbool.h&gt;
  
      bool isPrime(int p) {
        if (p &lt;= 1)
          return false;
  
        if (p &lt;= 3)
          return true;
  
        if (p % 2 == 0 || p % 3 == 0)
            return false;
  
        for (int i = 5; (i * i) &lt;= p; i += 6)
          if (p % i == 0 || p % (i + 2) == 0)
            return false;
  
        return true;
      }
  </code>
  </pre>
  
  </div>

  <div class="box" id="jav_block" style="display: none;">
    <pre>
      <code class="language-java line-numbers" data-prismjs-copy="Copy">public static boolean isPrime(int p) {
        if (p &lt;= 1)
          return false;
  
        if (p &lt;= 3)
          return true;
  
        if (p % 2 == 0 || p % 3 == 0)
          return false;

        for (int i = 5; i <= Math.sqrt(p); i += 6)
          if (p % i == 0 || p % (i + 2) == 0)
            return false;

        return true;
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

        return not(any(p % i == 0 or p % (i + 2) == 0 for i in range(5, int(sqrt(p)), 6)))
  </code>
  </pre>
  
  </div>

  <div class="box" id="cs_block" style="display: none; width: 58rem;">
    <pre>
      <code class="language-python line-numbers" data-prismjs-copy="Copy">using System;
      using System.Linq;

      class Primality {

        static bool isPrime(int p) {
          if (p &lt;= 1)
            return false;

          if (p &lt;= 3)
            return true;

          if (p % 2 == 0 || p % 3 == 0)
            return false;

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

<details open>
<summary class="project">A Tribute to Ennio Morricone</summary>
<p class="roles"><em>Arranger</em></p>

  <p>
    Italian composer Ennio Morricone, made famous by his sonically expansive film scores, sadly passed away in 2020. I have long loved his music and decided in 2023 to start arranging a tribute to Maestro Morricone, similar to the live concerts he would conduct throughout the world.
  </p>

  <details class="doc">
    <summary>Title Page</summary>
      <img class="center" src="/images/morricone/morricone-tribute/title-page.png" width="400">
  </details>

</details>

<details open>
<summary class="project">Arrangements</summary>
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

<details open>
<summary class="project">20th Century Crisis</summary>
<p class="roles"><em>Author</em></p>

  <p>
    This project is an antiwar retrospective on the 20th century; specifically the pendulum swinging from, to paraphrase Leonard Bernstein, inequality disguised as progress, to war, hysteria, and finally fascism. 
  </p>
  <p>
    The 'Pendulum Theory' of human history, the third law of German philosopher Georg Wilhelm Friedrich Hegel's Dialectic, describes the periodic shifts from thesis to antithesis before synthesis. In other words, the swing from one extreme to the other, before coming to rest.
  </p>
  <p>
    The project directs viewers/listeners to reflect on the swings of the 20th century and ask themselves, have we ever reached synthesis? <em>Is it even possible?</em> If so, is that period doomed to transience? Is injustice perpetual or is it liminal?
  </p>

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