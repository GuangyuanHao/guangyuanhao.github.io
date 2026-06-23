---
layout: home-modern
title: Guangyuan Hao
featured_video:
---

<section class="home-hero" id="about">
  <div>
    <div class="home-kicker">PhD Student / Cornell University</div>
    <h1 class="home-title">Guangyuan Hao</h1>
    <p class="home-subtitle">
      Hi, I am Guangyuan Hao, a PhD student at Cornell, where I work on reinforcement learning theory, causality, and their applications with <a href="https://nathankallus.com/">Nathan Kallus</a>. I will be based at Cornell Tech starting in the coming fall semester.
    </p>
    <div class="home-actions">
      <a class="home-button primary" href="#papers">Papers</a>
      <a class="home-button" href="#blog">Blog</a>
      <!-- <a class="home-button" href="file/Resume_Guangyuan_Hao.pdf">CV</a> -->
      <a class="home-button" href="mailto:gh463@cornell.edu">Email</a>
    </div>
  </div>

  <div class="portrait-panel">
    <img src="/guangyuan1.jpg" alt="Guangyuan Hao">
  </div>
</section>



<section class="home-section" id="news">
  <div class="section-head">
    <div>
      <div class="section-kicker">News</div>
      <h2 class="section-title">Updates</h2>
    </div>
  </div>
  <div class="paper-grid">
    <article class="paper-card">
      <div class="paper-meta">August 20th, 2025</div>
      <h3>Started PhD at Cornell</h3>
      <p>I started my PhD at Cornell and will be based at Cornell Tech in the coming fall semester.</p>
    </article>
    <article class="paper-card">
      <div class="paper-meta">September 25th, 2024</div>
      <h3>NeurIPS 2024 acceptance</h3>
      <p>A paper was accepted to NeurIPS 2024, introducing a new theoretical framework for counterfactual inference grounded in backtracking counterfactuals.</p>
    </article>
    <article class="paper-card">
      <div class="paper-meta">June 23rd, 2026</div>
      <h3>Homepage refresh</h3>
      <p>This homepage now brings research, writing, video, and social sharing into a single page.</p>
    </article>
  </div>
</section>

<section class="home-section" id="papers">
  <div class="section-head">
    <div>
      <div class="section-kicker">Research</div>
      <h2 class="section-title">Selected Papers</h2>
    </div>
    <a class="home-button" href="/publications/">All Publications</a>
  </div>
  <div class="paper-grid">
    <article class="paper-card">
      <div class="paper-meta">NeurIPS 2024</div>
      <h3><a href="/file/CFs.pdf">Natural Counterfactuals With Necessary Backtracking</a></h3>
      <p><strong>Guang-Yuan Hao</strong>, Jiji Zhang, Biwei Huang, Hao Wang, Kun Zhang. Previous version presented as an oral presentation at the ICML 2023 Workshop on Counterfactuals in Minds and Machines.</p>
    </article>
    <article class="paper-card">
      <div class="paper-meta">AAAI 2024</div>
      <h3><a href="/file/CAL-AAAI2024.pdf">Composite Active Learning</a></h3>
      <p>Towards multi-domain active learning with theoretical guarantees. Joint work with Hengguan Huang, Haotian Wang, Jie Gao, and Hao Wang.</p>
    </article>
    <article class="paper-card">
      <div class="paper-meta">ICLR 2023 Spotlight</div>
      <h3><a href="https://openreview.net/forum?id=pxStyaf2oJ5">Domain-Indexing Variational Bayes</a></h3>
      <p>An interpretable domain index for domain adaptation. Joint work with Zihao Xu, Hao He, and Hao Wang.</p>
    </article>
  </div>
</section>

<section class="home-section" id="blog">
  <div class="section-head">
    <div>
      <div class="section-kicker">Writing</div>
      <h2 class="section-title">Blog</h2>
    </div>
    <a class="home-button" href="/blogs/">Blog Archive</a>
  </div>
  <p class="section-copy">
    Notes on research, applications, web building, and life in academia.
  </p>
  <div class="blog-grid">
    <article class="blog-card">
      <div class="blog-meta">Sample</div>
      <h3><a href="/blogs/">A Future Blog Post</a></h3>
      <p>A placeholder for research notes, essays, or updates you may want to feature later.</p>
    </article>
    <!--
    <article class="blog-card">
      <div class="blog-meta">2024</div>
      <h3><a href="/blogs/24fall/">24Fall Application Notes</a></h3>
      <p>A long-form application record and reflection.</p>
    </article>
    <article class="blog-card">
      <div class="blog-meta">2023</div>
      <h3><a href="/blogs/web/">Personal Website Guide</a></h3>
      <p>A practical guide to building a lightweight personal website.</p>
    </article>
    <article class="blog-card">
      <div class="blog-meta">2022</div>
      <h3><a href="/blogs/cambridge/">Cambridge Research Memory</a></h3>
      <p>Notes from an online summer research experience.</p>
    </article>
    -->
  </div>
</section>

<section class="home-section" id="media">
  <div class="section-head">
    <div>
      <div class="section-kicker">Media</div>
      <h2 class="section-title">Video and X</h2>
    </div>
  </div>
  <div class="media-grid">
    <article class="media-card">
      <h3>Featured Video</h3>
      <div class="video-frame">
        {% if page.featured_video %}
        <iframe src="{{ page.featured_video }}" title="Featured video" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        {% else %}
        <div class="video-placeholder">Add a YouTube embed URL to <code>featured_video</code> in <code>index.md</code>.</div>
        {% endif %}
      </div>
    </article>
    <article class="x-card">
      <h3>Share on X</h3>
      <p>Use this page as a lightweight research hub for sharing papers, posts, and updates.</p>
      <div class="home-actions">
        <a class="home-button primary" href="https://twitter.com/intent/tweet?text=Guangyuan%20Hao%20-%20research%2C%20papers%2C%20and%20blog&url=https%3A%2F%2Fguangyuanhao.github.io" target="_blank" rel="noopener">Share</a>
        {% if site.owner.twitter %}
        <a class="home-button" href="https://x.com/{{ site.owner.twitter }}" target="_blank" rel="noopener">Follow</a>
        {% endif %}
      </div>
      {% if site.owner.twitter %}
      <blockquote class="twitter-timeline" data-height="320" data-chrome="noheader nofooter noborders" href="https://twitter.com/{{ site.owner.twitter }}">Posts by {{ site.owner.twitter }}</blockquote>
      {% else %}
      <p>To show a live X timeline, set <code>owner.twitter</code> in <code>_config.yml</code>.</p>
      {% endif %}
    </article>
    <article class="stat-card">
      <h3>Fun Stat</h3>
      <p>Website visitor counts by country since June 23, 2026:</p>
      <a href="https://info.flagcounter.com/2epM"><img src="https://s01.flagcounter.com/count2/2epM/bg_FFFFFF/txt_000000/border_CCCCCC/columns_8/maxflags_180/viewers_3/labels_0/pageviews_0/flags_0/percent_0/" alt="Flag Counter" border="0"></a>
    </article>
  </div>
</section>

<!--
Archived notes from the previous homepage draft.

I am Guangyuan Hao, currently serving as a research assistant with a focus on causality, physically in Abu Dhabi. My research is conducted under the guidance of esteemed professors [Kun Zhang](https://www.andrew.cmu.edu/user/kunz1/) at Carnegie Mellon University (CMU) and [Jiji Zhang](https://arts.cuhk.edu.hk/web/index.php/professor-zhang-jiji) at The Chinese University of Hong Kong (CUHK).

Additionally, since 2020, I have had the privilege of closely collaborating with Professor [Hao Wang](http://www.wanghao.in/) at Rutgers University, specifically in the field of Safe /Trustworthy AI.

Hi, I am Guangyuan Hao, a researcher dedicated to developing AI technologies that positively impact society. I am now working on the theoretical foundations of multimodal learning under Prof. Paul Liang at MIT.

I recently joined the [ML Alignment & Theory Scholars (MATS) Program](https://www.matsprogram.org) at Berkeley for a ten-week period, where I worked on AI safety research and participated in talks and workshops within the Berkeley alignment research community.

My research is focusing on AI Safety, especially for LLMs, under the guidance of [Dr. Steven Basart](https://stevenbas.art/) at Center for AI Safety.

Additionally, since 2021, I have had the privilege of closely collaborating with Professor [Hao Wang](http://www.wanghao.in/) at Rutgers University, specifically in the field of Safe /Trustworthy AI.

Furthermore, I am engaged in collaborative research endeavors with Professors [Yuanzhi Li](https://scholar.google.com/citations?user=aHtfItQAAAAJ&hl=en) and Kun Zhang at CMU, exploring the fascinating realm of the physics of Large Language Models (LLMs) recently.

I graduated from the Hong Kong University of Science and Technology with an MPhil, where my research focused on AI Safety, particularly in the areas of robustness and interpretability, advised by Professors [Dit-Yan Yeung (HKUST)](https://sites.google.com/view/dyyeung) and [Hao Wang (Rutgers)](http://www.wanghao.in/). My recent work has aimed to establish theoretical guarantees and develop methods to improve out-of-distribution (OOD) generalization and robustness. Driven by a deep interest in interpretability, I have spent over a year studying causality, working closely under the guidance of renowned professors [Jiji Zhang (CUHK)](https://arts.cuhk.edu.hk/web/index.php/professor-zhang-jiji) and [Kun Zhang (CMU)](https://www.andrew.cmu.edu/user/kunz1/).

Research Interests

- Safe and Trustworthy AI: Advancing distribution-shift robustness (out-of-distribution generalization), enhancing interpretability through causal frameworks, and ensuring alignment with human values and intent.
- Multimodal Learning: Investigating both theoretical foundations and practical methodologies for leveraging multimodal data, with impactful applications in domains such as healthcare and AI safety.
- Multisensory Intelligence: Exploration of both theoretical and practical approaches to understanding and utilizing multisensory data, with applications in areas like healthcare and AI safety.
- Physics of LLMs

My primary focus revolves around the development of theoretical frameworks aimed at explaining data and AI models and address real-world challenges to make AI systems trustworthy.

I am deeply dedicated to the field of causality, which plays a pivotal role in uncovering and comprehending cause-and-effect relationships. Causality inherently provides interpretability and robustness while enabling evidence-based decision-making. My ultimate goal is to extend the applicability of causality to deal with complex real-world data, such as images, texts, and videos.

Furthermore, I am fully immersed in the exploration of the Physics of Large Language Models (LLMs). My goal is to unravel the emergence of intelligence within these LLMs and potentially formulate corresponding theories. This endeavor aims to elevate the intelligence of Artificial General Intelligence (AGI) and mitigate the risk of its misuse.

I firmly believe that substantial theoretical advancements are driven by real-world applications. My specific focus revolves around harnessing the combined power of causality and LLMs for applications in trustworthy AI and groundbreaking scientific domains, including automated theorem proving, protein research, materials discovery, and more. These domains are pivotal in identifying urgent challenges and unlocking the untapped potential inherent in causality and the physics of LLMs.

Academic Background

- Sep. 2020 - Sep. 2022: Hong Kong University of Science and Technology, Master of Philosophy (MPhil) in Individualized Interdisciplinary Program (Artificial Intelligence); Awarded a full scholarship
- Sep. 2012 - July 2016: University of Electronic Science and Technology of China, Bachelor of Engineering (B.E.) in Information Display and Optoelectronic Technology; Ranking 1st/184
-->
