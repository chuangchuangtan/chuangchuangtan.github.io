---
permalink: /research-style/
title: "Research Style"
excerpt: "How I think about research: back to the task, define the problem, derive the method."
author_profile: false
---

<div class="faculty-subpage research-style-page">
<header class="clean-page-header rs-header">
  <h1>Research Style</h1>
  <p>我的科研思路可以归结为两个问题：<strong>好问题从哪里来？</strong>以及<strong>问题确定以后，方法从哪里来？</strong></p>
</header>

<div class="rs-overview" aria-label="Research style overview">
  <div class="rs-overview-step"><span>01</span><strong>Back to the Task</strong><small>回到任务本身</small></div>
  <div class="rs-arrow">→</div>
  <div class="rs-overview-step"><span>02</span><strong>Long-term Vision</strong><small>想清楚理想形态</small></div>
  <div class="rs-arrow">→</div>
  <div class="rs-overview-step"><span>03</span><strong>Define the Problem</strong><small>定义真正的问题</small></div>
  <div class="rs-arrow">→</div>
  <div class="rs-overview-step"><span>04</span><strong>Derive the Method</strong><small>由问题推导方法</small></div>
</div>

<section class="rs-section">
  <div class="rs-section-head"><span>01</span><div><h2>紧盯一手资料</h2><p>Back to the Task</p></div></div>
  <p class="rs-lead">信息传播会带来信息衰减。论文越读越多时，尤其需要穿过已有工作的层层解释，重新回到<strong>任务本身</strong>。</p>

  <div class="rs-decay">
    <div class="rs-decay-title">信息传播 <span>Information propagation</span></div>
    <div class="rs-decay-track">
      <div class="rs-source"><b>任务本身</b><small>Task itself</small><i style="--w:100%"></i></div>
      <div><b>开坑之作</b><small>Pioneering work</small><i style="--w:82%"></i></div>
      <div><b>后续论文</b><small>Follow-up works</small><i style="--w:63%"></i></div>
      <div><b>综述 / 教程</b><small>Survey / Tutorial</small><i style="--w:43%"></i></div>
      <div><b>博客 / PPT</b><small>Summary</small><i style="--w:24%"></i></div>
    </div>
    <p>越接近源头，越接近任务原本的动机、约束与尚未解决的问题。</p>
  </div>

  <div class="rs-contrast">
    <div class="rs-muted-box"><span>容易陷入</span><strong>沿着已有方法继续优化</strong><p>Method A → Method B → Method C → +1%</p></div>
    <div class="rs-vs">VS</div>
    <div class="rs-focus-box"><span>我更关注</span><strong>回到任务，先想理想情况</strong><p>Why this task? → Ideal form → Gap → New problem</p></div>
  </div>

  <div class="rs-vision">
    <div class="rs-vision-label">关键动作</div>
    <div class="rs-vision-main">
      <h3>先定义这个任务的远期愿景</h3>
      <p>暂时放下现有方法，问一个更直接的问题：<strong>如果这个任务最终被真正解决，它理想情况下应该发展成什么样？</strong></p>
      <div class="rs-inline-flow"><span>任务本身</span><b>→</b><span>理想形态</span><b>→</b><span>今天的能力</span><b>→</b><span class="accent">Gap</span><b>→</b><span class="accent">新问题</span></div>
    </div>
  </div>

  <div class="rs-example">
    <div class="rs-example-label">Example · AIGC Forensics</div>
    <h3>从 “Real or Fake?” 回到任务真正想解决什么</h3>
    <div class="rs-example-grid">
      <div class="rs-today"><small>Today's formulation</small><strong>Image → Real / Fake</strong><p>不断提高检测准确率与泛化能力。</p></div>
      <div class="rs-gap-arrow">→</div>
      <div class="rs-ideal"><small>Long-term vision</small><strong>What? · Where? · Why?</strong><p>不仅判断来源，还要指出异常、位置、原因与可解释证据。</p></div>
    </div>
    <p class="rs-takeaway">远期愿景不是答案，而是一把尺子：<strong>它让我们看见“今天”与“理想情况”之间真正值得研究的 Gap。</strong></p>
  </div>
</section>

<section class="rs-section">
  <div class="rs-section-head"><span>02</span><div><h2>现象、问题与方法</h2><p>Define the Problem, Derive the Method</p></div></div>
  <div class="rs-big-claim"><span>Problem</span><b>&gt;</b><span>Method</span></div>
  <p class="rs-lead">现象不是问题。先从现象中拆出<strong>元素</strong>，研究元素的<strong>特性</strong>，才能定义一个具体问题。问题一旦定义清楚，方法就不应该是随意选择的。</p>

  <div class="rs-problem-flow">
    <div><span>01</span><strong>现象</strong><small>Phenomenon</small><em>发生了什么？</em></div><b>→</b>
    <div><span>02</span><strong>元素</strong><small>Elements</small><em>谁参与其中？</em></div><b>→</b>
    <div><span>03</span><strong>特性</strong><small>Properties</small><em>什么在起作用？</em></div><b>→</b>
    <div class="key"><span>04</span><strong>问题</strong><small>Problem</small><em>到底要回答什么？</em></div><b>→</b>
    <div class="key"><span>05</span><strong>方法</strong><small>Method</small><em>如何解决这个问题？</em></div>
  </div>

  <div class="rs-example rs-tree-example">
    <div class="rs-example-label">Intuitive Example</div>
    <h3>“树叶落了”只是现象，不是问题</h3>
    <div class="rs-tree-root">🍂 <strong>现象：树叶落了</strong></div>
    <div class="rs-tree-elements"><span>树</span><span>叶子</span><span>环境</span><span>时间</span></div>
    <div class="rs-tree-properties"><span>水分</span><span>温度</span><span>光照</span><span>季节</span></div>
    <div class="rs-branches">
      <div><small>具体问题 A</small><strong>是否由缺水导致？</strong><span>↓</span><p>控制其他变量，改变浇水量</p></div>
      <div><small>具体问题 B</small><strong>是否由低温导致？</strong><span>↓</span><p>控制其他变量，改变温度</p></div>
      <div><small>具体问题 C</small><strong>是否由光照不足导致？</strong><span>↓</span><p>控制其他变量，改变光照</p></div>
    </div>
    <p class="rs-takeaway"><strong>不是现象决定方法，而是问题决定方法。</strong> 同一个现象可以产生不同问题，而每一个被清晰定义的问题，都对应着自己的解决路径。</p>
  </div>

  <div class="rs-derive">
    <div class="rs-method-first"><small>Method First</small><p>看到现象</p><b>↓</b><p>加 Attention？换 Backbone？加 Agent？</p><b>↓</b><p>哪个有效用哪个</p></div>
    <div class="rs-derive-center"><span>Define the Problem</span><b>↓</b><strong>约束解空间</strong><b>↓</b><span>Derive the Method</span></div>
    <div class="rs-problem-first"><small>Problem First</small><p>现象 → 元素 → 特性</p><b>↓</b><p><strong>定义具体问题</strong></p><b>↓</b><p>方法由问题自然推出</p></div>
  </div>

  <blockquote class="rs-quote">问题定义得越清楚，方法越不是“想出来”的，而是“推出来”的。<small>A well-defined problem constrains its solution.</small></blockquote>
</section>

<section class="rs-summary">
  <h2>我的研究路径</h2>
  <div class="rs-final-flow"><span>回到任务</span><b>→</b><span>远期愿景</span><b>→</b><span>发现 Gap</span><b>→</b><span>现象</span><b>→</b><span>元素与特性</span><b>→</b><span class="accent">定义问题</span><b>→</b><span class="accent">推导方法</span><b>→</b><span>证据</span></div>
  <p><strong>Back to the Task.</strong> Define the Problem. Derive the Method.</p>
</section>
</div>
