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
    <p class="home-subtitle">
      Previously, I was a visiting scholar in the <a href="https://www.matsprogram.org">ML Alignment &amp; Theory Scholars (MATS) Program</a> at Berkeley, and I also visited <a href="https://pliang279.github.io/">Paul Liang</a>'s group at MIT. I graduated from the Hong Kong University of Science and Technology, where I was advised by Professors <a href="https://sites.google.com/view/dyyeung">Dit-Yan Yeung</a> and <a href="http://www.wanghao.in/">Hao Wang</a>. I have also worked closely with <a href="https://arts.cuhk.edu.hk/web/index.php/professor-zhang-jiji">Jiji Zhang</a> and <a href="https://www.andrew.cmu.edu/user/kunz1/">Kun Zhang</a>.
    </p>
    <div class="home-actions">
      <a class="home-button primary" href="#papers">Papers</a>
      <a class="home-button" href="#blog">Blog</a>
      <!-- <a class="home-button" href="file/Resume_Guangyuan_Hao.pdf">CV</a> -->
      <a class="home-button" href="mailto:gh463@cornell.edu">Email</a>
    </div>
    <div class="quick-facts">
      <div class="fact-item">
        <span class="fact-label">Research</span>
        <span class="fact-value">RL Theory / Causality</span>
      </div>
      <div class="fact-item">
        <span class="fact-label">Current</span>
        <span class="fact-value">Cornell / Cornell Tech</span>
      </div>
      <div class="fact-item">
        <span class="fact-label">Recent</span>
        <span class="fact-value">NeurIPS 2024</span>
      </div>
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
