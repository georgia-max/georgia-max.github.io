---
layout: minimal
permalink: /
title: ""
redirect_from: 
  - /about/
  - /about.html
---

<section class="bio" markdown="1">
I use LLMs to turn interviews, verbatim responses and quotes into causal graphs, and I build benchmarks that measure how closely those graphs match expert-built ones. I'm the founder of [Causena](https://causena.co/), where we turn interviews, debriefs and reports into source-cited causal graphs that show what drives real-world outcomes. Before Causena, I was a Postdoctoral Research Fellow at Harvard Medical School / Massachusetts General Hospital in the [MJ Lab](https://mj-lab.mgh.harvard.edu), where I built a framework for comparing causal graphs on both meaning and structure, and used it to evaluate 2,000 LLM-generated graphs. Before that, I was an AI Resident at [Google X](https://x.company/), using LLMs to automate causal modeling. I did my PhD in Industrial and Systems Engineering with Dr. Konstantinos Triantis in Virginia Tech's [Systems Performance Lab](https://www.spl.ise.vt.edu/index.html), and an MS in Computer Science focused on AI and machine learning.

I'm always happy to talk about LLM evaluation, information extraction, and causal AI for messy qualitative data.
</section>

<hr>

<section id="selected-work">
  <h2>Selected work</h2>
  <ul class="work-list">
    <li class="work-item">
      <a class="work-thumb" href="/images/causal-graph-benchmark-table4.png"><img src="/images/causal-graph-benchmark-table4-thumb.png" alt="Table 4: graph similarity scores (G1 to G5) for six variations of a reference causal loop diagram"></a>
      <div>
        <h3>Causal graph benchmark</h3>
        <p>Reviewed 40+ similarity metrics and evaluated 9 (4 semantic, 5 structural) on 2,000 LLM-generated causal graphs.</p>
        <span class="links-inline"><a href="https://arxiv.org/abs/2503.11046">Paper</a> · <a href="https://github.com/georgia-max/Causalgraph-comparison">Code</a></span>
      </div>
    </li>
    <li class="work-item">
      <a class="work-thumb" href="https://arxiv.org/abs/2503.21798"><img src="/images/cldmaker.gif" alt="Demo: typing a dynamic hypothesis and generating a causal loop diagram"></a>
      <div>
        <h3>LLMs for causal loop diagrams</h3>
        <p>Tested four prompting strategies for turning text into causal loop diagrams; for simple models, the best matched expert-built diagrams.</p>
        <span class="links-inline"><a href="https://arxiv.org/abs/2503.21798">Paper</a> · <a href="/talks/2024-08-06-LLM">Talk</a></span>
      </div>
    </li>
    <li class="work-item">
      <a class="work-thumb work-thumb--empty" href="https://causena.co/">Causena</a>
      <div>
        <h3>Causena</h3>
        <p>Automated large-scale analysis, turning 1,000 interviews and verbatim responses into source-cited causal graphs; adopted by our first customer.</p>
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

<section id="conferences-and-talks">
  <h2>Conferences &amp; talks</h2>
  <ul class="entries">
    {% for talk in site.data.conference_talks %}
    <li>
      <span>{% if talk.url %}<a href="{{ talk.url }}">{{ talk.title }}</a>{% else %}{{ talk.title }}{% endif %}<br><span class="meta">{{ talk.type }} · {{ talk.venue }}, {{ talk.location }}{% if talk.code %} · <a href="{{ talk.code }}">Code</a>{% endif %}</span></span>
      <span class="date">{{ talk.year }}</span>
    </li>
    {% endfor %}
  </ul>
</section>
