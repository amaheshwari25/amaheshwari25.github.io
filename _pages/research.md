---
layout: page
title: Research
permalink: /research/
description: Summaries of my primary research experiences thus far. 
nav: true
nav_order: 2
display_categories: [work, fun]
horizontal: false
---

<h4> Papers </h4>
<small> <i> All author orderings alphabetical, per convention in theoretical CS. </i> </small>


1. <b>AM</b>, S. Matthew Weinberg, Eric Xue. <i> Polynomial Sample Complexity for Blackbox Reductions in Mechanism Design with Independent Items.</i> In preparation. <div style="margin-top: 4px;">
    Preliminary version presented at EC'25 poster session and received Outstanding Senior Thesis Prize at Princeton.
    <a href="../assets/pdf/EC25_Poster_with_note.pdf" target="_blank">[poster]</a>
  </div>

2. <b>AM</b>, Elaine Shi. <i> Oblivious Priority Queue and SSSP in the External Memory Setting. </i> In submission.

3. Sara Logsdon, <b> AM </b>, István Miklós, Angelina Zhang. <i> A Dichotomy Theorem on the Complexity of 3-Uniform Hypergraphic Degree Sequence Graphicality. </i> In submission to <i> Electronic Journal of Combinatorics</i>. Presentation at Joint Mathematics Meetings (JMM'25). <a href="https://arxiv.org/abs/2411.19049" target="_blank">[arXiv]</a> 

<br>
<h4> Project Summaries </h4>
<small> Click on the triangles for a quick summary of the listed projects! </small>


<div class="projects-container">
  <!-- Project 1 -->
  <div class="project">
    <div class="project-header" id="project-matroids">
      <span class="triangle" onclick="toggleDetails(this)">▶</span>
      <span class="project-title">1. Sample Complexity for Blackbox Reductions in Mechanism Design. <a href="../assets/pdf/EC25_Poster_with_note.pdf" target="_blank">[poster]</a> </span>
    </div>
    <div class="details" style="display: none;">
      <p> Our work focuses on improving the sample complexity of blackbox reductions from mechanism design to algorithm design (in particular, the so-called epsilon-BIC-to-BIC reduction). Existing reductions are based on the <i> replica-surrogate bipartite matching </i> procedure, which requires exponentially-many samples from input distributions. </p>
      <p> We show that under some natural structural assumptions (independent items, and a Lipschitz-ness condition on valuation functions), we can improve the sample complexity to <i> polynomial </i> in the relevant parameters. <b> This resolves the central open question from a <a href="https://arxiv.org/pdf/1808.02458">FOCS'18 paper</a></b>. Our mechanism is based on a new variant of replica-surrogate matching, and our analysis uses concentration specific to product distributions as well as a few neat tricks to handle small errors and failure probabilities. 
      </p>
      <p> I worked on this project for my senior thesis at Princeton, advised by Matt Weinberg and Eric Xue. Stay tuned for a paper on our results! Meanwhile, you can check out slides from my thesis talk and a poster from EC'25 (both with a preliminary version of our current results) here: <a href="../assets/pdf/Thesis_Slides.pdf" target="_blank">[slides]</a> and <a href="../assets/pdf/Thesis_Slides.pdf" target="_blank">[slides]</a>.</p>
    </div>
  </div>

  <div class="project">
    <div class="project-header" id="project-matroids">
      <span class="triangle" onclick="toggleDetails(this)">▶</span>
      <span class="project-title">2. Matroid Intersection Prophet Inequalities <a href="../assets/pdf/JP_AryaMaheshwari.pdf" target="_blank">[report]</a></span>
    </div>
    <div class="details" style="display: none;">
      <p> Prophet inequalities are a class of online selection problems that ask how well an agent choosing online from a sequence of items, under some set of feasibility constraints, can approximate the offline optimal feasible subset of items. 
      <!-- The <i> approximation ratio </i> is the ratio of the offline optimal value to what the online agent can achieve, and the goal in a prophet inequality is to determine how large this can be. --> 
      The prophet inequality for <i> matroid intersection </i> constraints is a decade-old open problem, with an asymptotic gap between linear upper bounds and roughly-square-root lower bounds on the approximation ratio, and what's especially intriguing is that the existing lower bound construction satisfies many special conditions that need not hold in general—yet no alternate constructions have been explored.</p> 
      <!-- <br style="line-height:3px;"/> -->
      <p>
      My research focused on studying whether new generalization of the existing construction could improve the lower bound. I proved a couple new results that <i> rule out </i>  some classes of constructions from improving the lower bound. For instance, I showed that partition matroids are optimal for expressing the existing lower bound construction -- we can't hope to improve it by generalizing to arbitrary matroids. This particular result completes the reverse direction of a reduction in a <a href="https://arxiv.org/pdf/2209.05614"> 2022 paper </a> to show an <i>equivalence</i> between the current lower bound construction and graph-theoretic product dimension bounds.</p>
      <p>
      I worked on this project for my Junior Paper at Princeton, advised by Matt Weinberg. </p>
    </div>
  </div>

  <div class="project">
    <div class="project-header" id="project-graphs">
      <span class="triangle" onclick="toggleDetails(this)">▶</span>
      <span class="project-title">3. A Dichotomy Theorem for Hypergraphic Degree Sequence Graphicality <a href="https://arxiv.org/abs/2411.19049" target="_blank">[arXiv]</a></span>
    </div>
    <div class="details" style="display: none;">
      <p> Our work studies the <i>degree sequence graphicality</i> problem for 3-uniform hypergraphs, which asks whether a given degree sequence is realized by a 3-uniform hypergraph. We prove a <i> dichotomy theorem </i> on the complexity of this decision problem over all possible degree intervals, showing that the problem is either solvable in linear time (very easily) or NP-complete (and characterizing exactly when each case happens).</p>
      <p>I worked on this project with Prof. István Miklós (Rényi Institute) and two other students while at the Budapest Semesters in Mathematics.</p>
    </div>
  </div>
  <div class="project">
    <div class="project-header" id="project-qc">
      <span class="triangle" onclick="toggleDetails(this)">▶</span>
      <span class="project-title">4. Space-Depth Tradeoffs in Parity Synthesis in Quantum Computing <a href="../assets/pdf/IBM_PACM_Paper.pdf" target="_blank">[report]</a> <a href="../assets/pdf/PACMPresentation.pdf" target="_blank">[slides]</a></span>
    </div>
    <div class="details" style="display: none;">
      <p> I worked on research and implementations for new quantum compilation algorithms at IBM Quantum with Dr. Ali Javadi-Abhari. I proved a new result on the <i>space-depth tradeoff</i> between additional qubits and additional depth in parity synthesis for Hamiltonian simulation circuits. Specifically, I devised a new algorithmic framework for extending the block algorithm of <a href="https://arxiv.org/pdf/2201.06380">de Brugière et al.</a> in a way that enables finer-grained control of the space-depth tradeoff than previously possible, by leveraging additional ancilla to proportionally parallelize the existing computations.</p>
      <!-- <p> <b>Publication:</b> Paper on theoretical results currently being drafted. Code used for benchmarks in another recent <a href="https://arxiv.org/pdf/2404.03280">paper</a>.</p> -->
    </div>
  </div>
  <!-- Repeat for other projects -->
</div>

<script>
  function toggleDetails(triangle) {
    const details = triangle.parentElement.nextElementSibling; // Get the details section
    const isOpen = details.style.display === "block";

    // Toggle details visibility
    details.style.display = isOpen ? "none" : "block";

    // Rotate the triangle
    if (isOpen) {
      triangle.classList.remove("open");
    } else {
      triangle.classList.add("open");
    }
  }
</script>