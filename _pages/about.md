---
permalink: /
title: ""
excerpt: "Chuangchuang Tan — Lecturer at Beijing Jiaotong University. Trustworthy visual intelligence, AIGC forensics, and multimodal reasoning."
author_profile: false
---

<div class="site-home" id="home">

<section class="intro-hero">
  <div class="intro-copy">
    <div class="eyebrow">Beijing Jiaotong University · Beijing, China</div>
    <h1>Chuangchuang Tan <span>谭创创</span></h1>
    <p class="intro-role">Lecturer, School of Computer Science & Technology</p>
    <p class="intro-thesis">I study how machines can <em>verify, explain, and reason about</em> visual information in the age of generative AI.</p>
    <p class="intro-bio">My research focuses on <strong>trustworthy visual intelligence</strong>, especially AI-generated content forensics, explainable deepfake detection, multimodal reasoning, and agentic visual understanding. I received my Ph.D. from Beijing Jiaotong University in 2025 under the supervision of Prof. Yao Zhao, and previously conducted research at A*STAR and Microsoft Research Asia.</p>

    <div class="intro-links">
      <a class="primary-link" href="mailto:tanchuangchuang@bjtu.edu.cn">Email <span>↗</span></a>
      <a href="https://scholar.google.com/citations?user=ufR1PmMAAAAJ" target="_blank" rel="noopener">Google Scholar <span>↗</span></a>
      <a href="https://github.com/chuangchuangtan" target="_blank" rel="noopener">GitHub <span>↗</span></a>
      <a href="https://faculty.bjtu.edu.cn/98940429/" target="_blank" rel="noopener">BJTU Faculty <span>↗</span></a>
    </div>
  </div>

  <div class="intro-portrait">
    <div class="portrait-frame">
      <img src="{{ '/images/tccphoto.jpg' | relative_url }}" alt="Portrait of Chuangchuang Tan">
    </div>
    <div class="portrait-caption">
      <span>Computer Vision · AI Safety</span>
      <span>AIGC Forensics · MLLMs</span>
    </div>
  </div>
</section>

<section class="home-block research-preview">
  <div class="block-title">
    <span class="block-number">01</span>
    <div>
      <div class="eyebrow">Research</div>
      <h2>What I work on</h2>
    </div>
    <a class="section-link" href="/research/">Research overview <span>→</span></a>
  </div>

  <div class="research-rows">
    <a class="research-row" href="/research/#forensics">
      <span class="research-index">A</span>
      <div><h3>Generalizable AIGC Forensics</h3><p>Transferable forensic evidence across unseen generators and open-world distributions.</p></div>
      <span class="row-arrow">↗</span>
    </a>
    <a class="research-row" href="/research/#reasoning">
      <span class="research-index">B</span>
      <div><h3>Explainable & Agentic Reasoning</h3><p>From binary detection to localized evidence, structured explanations, and multi-agent reasoning.</p></div>
      <span class="row-arrow">↗</span>
    </a>
    <a class="research-row" href="/research/#trustworthy">
      <span class="research-index">C</span>
      <div><h3>Trustworthy Multimodal Intelligence</h3><p>Connecting visual observations with physical knowledge, commonsense, and external evidence.</p></div>
      <span class="row-arrow">↗</span>
    </a>
  </div>
</section>

<section class="home-block selected-preview">
  <div class="block-title">
    <span class="block-number">02</span>
    <div>
      <div class="eyebrow">Selected work</div>
      <h2>Representative papers</h2>
    </div>
    <a class="section-link" href="/publications/">All publications <span>→</span></a>
  </div>

  <article class="latest-feature">
    <div class="latest-feature-copy">
      <div class="latest-feature-meta"><span>ICLR 2026</span><span>Latest research direction</span></div>
      <h3>Semantic Visual Anomaly Detection and Reasoning in AI-Generated Images</h3>
      <p>Moving beyond “is it AI-generated?” toward discovering <strong>what is semantically wrong</strong>, explaining <strong>why it is wrong</strong>, and assessing <strong>how severe the anomaly is</strong>.</p>
      <div class="latest-feature-links">
        <a href="https://openreview.net/forum?id=0iN4UKZwgn" target="_blank" rel="noopener">Paper ↗</a>
        <a href="https://github.com/chuangchuangtan/Semantic-Visual-Anomaly-Detection-and-Reasoning" target="_blank" rel="noopener">Code ↗</a>
      </div>
    </div>
    <div class="reasoning-visual" aria-label="AnomReason structured anomaly representation">
      <div class="reasoning-visual-label">ANOMALY / STRUCTURE</div>
      <div class="reasoning-cell reasoning-cell--wide"><span>01</span><strong>Observed</strong><p>What looks visually inconsistent?</p></div>
      <div class="reasoning-cell"><span>02</span><strong>Reasoning</strong><p>Why does it violate logic, physics, or commonsense?</p></div>
      <div class="reasoning-cell"><span>03</span><strong>Severity</strong><p>How strongly does the anomaly affect plausibility?</p></div>
      <div class="reasoning-flow">visual evidence <b>→</b> structured explanation <b>→</b> trustworthy judgment</div>
    </div>
  </article>

  <div class="visual-paper-grid">
    <article class="visual-paper-card">
      <a class="visual-paper-image" href="https://ojs.aaai.org/index.php/AAAI/article/view/32772" target="_blank" rel="noopener">
        <img src="{{ '/images/C2P-CLIP.png' | relative_url }}" alt="C2P-CLIP teaser">
      </a>
      <div class="visual-paper-body">
        <div class="visual-paper-meta"><span>AAAI 2025</span><span>Vision-Language</span></div>
        <h3>C2P-CLIP</h3>
        <p>Category-common prompting to strengthen CLIP generalization for deepfake detection.</p>
        <div class="paper-actions"><a href="https://ojs.aaai.org/index.php/AAAI/article/view/32772" target="_blank" rel="noopener">Paper ↗</a><a href="https://github.com/chuangchuangtan/C2P-CLIP-DeepfakeDetection" target="_blank" rel="noopener">Code ↗</a></div>
      </div>
    </article>

    <article class="visual-paper-card">
      <a class="visual-paper-image" href="https://openaccess.thecvf.com/content/CVPR2024/html/Tan_Rethinking_the_Up-Sampling_Operations_in_CNN-based_Generative_Network_for_Generalizable_CVPR_2024_paper.html" target="_blank" rel="noopener">
        <img src="{{ '/images/NPR.png' | relative_url }}" alt="NPR teaser">
      </a>
      <div class="visual-paper-body">
        <div class="visual-paper-meta"><span>CVPR 2024</span><span>Generator Priors</span></div>
        <h3>NPR</h3>
        <p>Neighboring pixel relationships induced by generator up-sampling as transferable forensic traces.</p>
        <div class="paper-actions"><a href="https://openaccess.thecvf.com/content/CVPR2024/html/Tan_Rethinking_the_Up-Sampling_Operations_in_CNN-based_Generative_Network_for_Generalizable_CVPR_2024_paper.html" target="_blank" rel="noopener">Paper ↗</a><a href="https://github.com/chuangchuangtan/NPR-DeepfakeDetection" target="_blank" rel="noopener">Code ↗</a></div>
      </div>
    </article>

    <article class="visual-paper-card">
      <a class="visual-paper-image" href="https://openaccess.thecvf.com/content/CVPR2023/html/Tan_Learning_on_Gradients_Generalized_Artifacts_Representation_for_GAN-Generated_Images_Detection_CVPR_2023_paper.html" target="_blank" rel="noopener">
        <img src="{{ '/images/Lgrad.png' | relative_url }}" alt="LGrad teaser">
      </a>
      <div class="visual-paper-body">
        <div class="visual-paper-meta"><span>CVPR 2023</span><span>Gradient Evidence</span></div>
        <h3>LGrad</h3>
        <p>Image gradients as a generalized representation of artifacts produced by generative models.</p>
        <div class="paper-actions"><a href="https://openaccess.thecvf.com/content/CVPR2023/html/Tan_Learning_on_Gradients_Generalized_Artifacts_Representation_for_GAN-Generated_Images_Detection_CVPR_2023_paper.html" target="_blank" rel="noopener">Paper ↗</a><a href="https://github.com/chuangchuangtan/LGrad" target="_blank" rel="noopener">Code ↗</a></div>
      </div>
    </article>
  </div>
</section>

<section class="home-block latest-preview">
  <div class="block-title">
    <span class="block-number">03</span>
    <div>
      <div class="eyebrow">Latest</div>
      <h2>Recent updates</h2>
    </div>
  </div>

  <div class="latest-list">
    <div class="latest-item"><time>2026</time><p><strong>AnomReason</strong> is published at ICLR 2026.</p></div>
    <div class="latest-item"><time>2026</time><p><strong>ForenDeX</strong> appears in CVPR 2026 Findings, exploring explainable AI-generated image forensics.</p></div>
    <div class="latest-item"><time>2025.06</time><p>Received my Ph.D. degree from Beijing Jiaotong University and was selected for an Outstanding Doctoral Dissertation of BJTU.</p></div>
  </div>
</section>

<footer class="home-end">
  <span>Chuangchuang Tan · 谭创创</span>
  <span>Last updated October 2026</span>
</footer>

</div>
