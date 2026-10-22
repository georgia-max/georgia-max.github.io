---
layout: minimal
permalink: /
title: ""
redirect_from: 
  - /about/
  - /about.html
---

<section class="bio" markdown="1">
I build and evaluate LLM systems that turn unstructured text into structured causal knowledge. I'm the founder of [Causena](https://causena.co/), where we turn interviews, debriefs and reports into source-cited causal graphs that show what drives real-world outcomes. Before Causena, I was a Postdoctoral Research Fellow at Harvard Medical School / Massachusetts General Hospital in the [MJ Lab](https://mj-lab.mgh.harvard.edu), where I built benchmarks and extraction pipelines for LLM-generated causal graphs. Before that, I was an AI Resident at [Google X](https://x.company/), using LLMs to automate causal modeling. I hold a PhD in Industrial and Systems Engineering and an MEng in Computer Science from Virginia Tech.

I'm always happy to talk about LLM evaluation, information extraction, and causal AI for messy qualitative data. Reach me at [georgialiu63@gmail.com](mailto:georgialiu63@gmail.com).
</section>

<hr>

<section id="selected-work">
  <h2>Selected work</h2>
  <ul class="work-list">
    <li class="work-item">
      <a class="work-thumb" href="https://arxiv.org/abs/2503.11046"><img src="/images/causal-graph-benchmark.png" alt="Distribution of graph comparison metrics across 2,000 LLM-generated causal graphs"></a>
      <div>
        <h3>Causal graph benchmark</h3>
        <p>Reviewed 40+ similarity metrics and validated 9 on 2,000 LLM-generated causal graphs.</p>
        <span class="links-inline"><a href="https://arxiv.org/abs/2503.11046">Paper</a> · <a href="https://github.com/georgia-max/Causalgraph-comparison">Code</a></span>
      </div>
    </li>
    <li class="work-item">
      <a class="work-thumb" href="https://arxiv.org/abs/2503.21798"><img src="/images/cldmaker.gif" alt="Demo: typing a dynamic hypothesis and generating a causal loop diagram"></a>
      <div>
        <h3>LLMs for causal loop diagrams</h3>
        <p>Curated prompting turns text into expert-quality causal loop diagrams, cutting analysis time 10x.</p>
        <span class="links-inline"><a href="https://arxiv.org/abs/2503.21798">Paper</a> · <a href="/talks/2024-08-06-LLM">Talk</a></span>
      </div>
    </li>
    <li class="work-item">
      <a class="work-thumb work-thumb--empty" href="https://causena.co/">Causena</a>
      <div>
        <h3>Causena</h3>
        <p>Processed 1,000 healthcare transcripts into source-cited causal graphs; adopted by our first customer.</p>
        <span class="links-inline"><a href="https://causena.co/">Website</a></span>
      </div>
    </li>
  </ul>
</section>

<hr>

<section>
  <h2>Research</h2>
  <ul class="entries">
    <li><a href="https://arxiv.org/abs/2503.11046">Measuring Similarity in Causal Graphs: A Framework for Semantic and Structural Analysis</a><span class="date">2025</span></li>
    <li><a href="https://arxiv.org/abs/2503.21798">Leveraging Large Language Models for Automated Causal Loop Diagram Generation</a><span class="date">2025</span></li>
    <li><a href="https://doi.org/10.1016/j.ssci.2024.106775">The Relationships among Workload, Automation Reliance, and Human Errors in Safety-Critical Monitoring Roles</a><span class="date">2025</span></li>
    <li><a href="https://doi.org/10.1002/sres.3033">A Multi-dimensional Index of Evaluating Systems Thinking Skills from Textual Data</a><span class="date">2024</span></li>
    <li><a href="/publications/">All publications</a></li>
  </ul>
</section>

<hr>

<section>
  <h2>Talks</h2>
  <ul class="entries">
    {% for talk in site.talks reversed %}
    <li><a href="{{ talk.url }}">{{ talk.title }}</a><span class="date">{{ talk.date | date: "%b %Y" }}</span></li>
    {% endfor %}
  </ul>
</section>
