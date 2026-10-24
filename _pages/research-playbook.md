---
permalink: /research-playbook/
title: "Research Playbook"
excerpt: "A compact, shareable version of my research style."
author_profile: false
---

<div class="playbook-page" id="research-playbook">
  <div class="playbook-topbar">
    <a class="playbook-back" href="{{ '/research-style/' | relative_url }}">← Research Style</a>
    <div class="playbook-lang" role="group" aria-label="Language"><button class="active" data-lang="zh">中文</button><button data-lang="en">EN</button></div>
  </div>

  <header class="playbook-hero">
    <div class="playbook-kicker">RESEARCH PLAYBOOK</div>
    <h1 class="lang-zh">我如何做研究</h1><h1 class="lang-en">How I Do Research</h1>
    <p class="playbook-deck lang-zh">两个原则：<strong>回到任务本身</strong>，找到真正值得做的问题；<strong>定义问题，再推导方法</strong>。</p>
    <p class="playbook-deck lang-en">Two principles: <strong>go back to the task</strong> to find the right problem, then <strong>define the problem and derive the method</strong>.</p>
    <div class="playbook-core-flow">
      <span>Back to the Task</span><b>→</b><span>Ideal Vision</span><b>→</b><span>Gap</span><b>→</b><span class="core">Problem</span><b>→</b><span class="core">Method</span>
    </div>
  </header>

  <section class="playbook-principle">
    <div class="playbook-index">01</div>
    <div class="playbook-principle-body">
      <div class="playbook-eyebrow">BACK TO THE TASK</div>
      <h2 class="lang-zh">不要沿着论文往后追，要沿着任务往回看。</h2>
      <h2 class="lang-en">Don't follow the papers. Follow the task.</h2>
      <p class="lang-zh">论文会不断告诉我们“别人现在怎么做”。但一个简单高效的方式，是暂时放下现有方法，先为任务提出一个<strong>清晰、明了的理想愿景</strong>。</p>
      <p class="lang-en">Papers keep telling us how others currently solve a task. A simple alternative is to temporarily set methods aside and formulate a <strong>clear ideal vision</strong> of what the task should ultimately become.</p>

      <div class="playbook-split">
        <div class="playbook-deadend"><small class="lang-zh">沿着已有论文</small><small class="lang-en">Follow the papers</small><div class="paper-stack"><i>Paper A</i><b>↓</b><i>Paper B</i><b>↓</b><i>Paper C</i><b>↓</b><i>+0.8%</i></div><em class="lang-zh">局部优化</em><em class="lang-en">Local optimization</em></div>
        <div class="playbook-better"><small class="lang-zh">回到任务本身</small><small class="lang-en">Return to the task</small><div class="vision-stack"><i>THE TASK</i><b>↓</b><i>Ideal Vision</i><b>↓</b><i>What is missing?</i><b>↓</b><i>NEW PROBLEM</i></div><em class="lang-zh">从理想终点倒推今天</em><em class="lang-en">Work backward from the ideal</em></div>
      </div>

      <div class="playbook-rule lang-zh"><strong>知道理想情况是什么样，就可以倒推：</strong>哪些还没做好？差距在哪里？现在该做什么？</div>
      <div class="playbook-rule lang-en"><strong>Once the ideal is clear, work backward:</strong> What is missing? Where is the gap? What should we do now?</div>

      <div class="playbook-example">
        <div class="playbook-example-tag">EXAMPLE · AIGC FORENSICS</div>
        <div class="playbook-aigc">
          <div class="playbook-aigc-today"><small>TODAY</small><strong>Image</strong><b>↓</b><span>Detector</span><b>↓</b><em>Real / Fake</em></div>
          <div class="playbook-aigc-question"><span>?</span><p class="lang-zh">真正解决这个任务，最终只需要一个二分类标签吗？</p><p class="lang-en">If the task were truly solved, would a binary label be enough?</p></div>
          <div class="playbook-aigc-ideal"><small>IDEAL</small><strong>Image</strong><b>↓</b><div><span>Source</span><span>Where?</span><span>What?</span><span>Why?</span></div><b>↓</b><em>Evidence</em></div>
        </div>
        <p class="lang-zh"><strong>理想愿景与当前能力之间的差距，就是问题的来源。</strong></p>
        <p class="lang-en"><strong>The gap between the ideal vision and today's capability is where new problems come from.</strong></p>
      </div>
    </div>
  </section>

  <section class="playbook-principle second">
    <div class="playbook-index">02</div>
    <div class="playbook-principle-body">
      <div class="playbook-eyebrow">DEFINE THE PROBLEM, DERIVE THE METHOD</div>
      <h2 class="lang-zh">现象不是问题。问题清楚，方法才清楚。</h2>
      <h2 class="lang-en">A phenomenon is not a problem. A clear problem leads to a clear method.</h2>
      <div class="playbook-equations"><span>Phenomenon ≠ Problem</span><span>Problem → Method</span><span class="strong">Problem &gt; Method</span></div>

      <div class="playbook-tree">
        <div class="tree-top"><span>🍂</span><strong class="lang-zh">树叶落了</strong><strong class="lang-en">Leaves are falling</strong><small>PHENOMENON</small></div>
        <div class="tree-arrow">↓</div>
        <div class="tree-mid"><span>💧 <b class="lang-zh">水分</b><b class="lang-en">Water</b></span><span>🌡 <b class="lang-zh">温度</b><b class="lang-en">Temperature</b></span><span>☀ <b class="lang-zh">光照</b><b class="lang-en">Light</b></span></div>
        <div class="tree-arrow"><small>DEFINE THE PROBLEM</small> ↓</div>
        <div class="tree-bottom">
          <div><small>PROBLEM A</small><strong class="lang-zh">是否缺水？</strong><strong class="lang-en">Water deficiency?</strong><b>↓</b><span class="lang-zh">改变浇水量</span><span class="lang-en">Vary water</span><em>METHOD A</em></div>
          <div><small>PROBLEM B</small><strong class="lang-zh">是否低温？</strong><strong class="lang-en">Low temperature?</strong><b>↓</b><span class="lang-zh">改变温度</span><span class="lang-en">Vary temperature</span><em>METHOD B</em></div>
          <div><small>PROBLEM C</small><strong class="lang-zh">是否缺光？</strong><strong class="lang-en">Insufficient light?</strong><b>↓</b><span class="lang-zh">改变光照</span><span class="lang-en">Vary light</span><em>METHOD C</em></div>
        </div>
      </div>

      <div class="playbook-contrast">
        <div><small>METHOD FIRST</small><p class="lang-zh">看到现象 → Attention？Agent？新 Loss？</p><p class="lang-en">Phenomenon → Attention? Agent? New loss?</p></div>
        <b>VS</b>
        <div class="good"><small>PROBLEM FIRST</small><p>Phenomenon → Elements → Properties → <strong>Problem → Method</strong></p></div>
      </div>

      <blockquote><span class="lang-zh">问题越模糊，方法越多；问题越清楚，方法越确定。</span><span class="lang-en">The vaguer the problem, the larger the method space. The clearer the problem, the more constrained the method.</span></blockquote>
    </div>
  </section>

  <section class="playbook-signature">
    <div class="signature-label">THE WHOLE PLAYBOOK</div>
    <div class="signature-flow"><span>Task</span><b>→</b><span>Ideal Vision</span><b>→</b><span>Gap</span><b>→</b><span>Phenomenon</span><b>→</b><span>Elements & Properties</span><b>→</b><span class="focus">Problem</span><b>→</b><span class="focus">Method</span><b>→</b><span>Evidence</span></div>
    <h3>Back to the Task. Define the Problem. Derive the Method.</h3>
    <p class="lang-zh">从任务的理想形态倒推问题，从清晰定义的问题推导方法。</p><p class="lang-en">Work backward from the task's ideal form to find the problem; derive the method from a precisely defined problem.</p>
  </section>
</div>

<style>
.playbook-page{max-width:1080px;margin:0 auto;padding:34px 24px 80px;font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Arial,sans-serif;color:#20252a}.playbook-page .lang-en{display:none}.playbook-page[data-lang="en"] .lang-zh{display:none!important}.playbook-page[data-lang="en"] .lang-en{display:inline}.playbook-page[data-lang="en"] p.lang-en,.playbook-page[data-lang="en"] h1.lang-en,.playbook-page[data-lang="en"] h2.lang-en{display:block}.playbook-topbar{display:flex;justify-content:space-between;align-items:center;margin-bottom:54px}.playbook-back{color:#777!important;font-size:.78rem;text-decoration:none!important}.playbook-lang{display:flex;border:1px solid #d8dde2;padding:2px}.playbook-lang button{border:0;background:#fff;padding:5px 10px;font-size:.7rem;color:#777;cursor:pointer}.playbook-lang button.active{background:#1769aa;color:#fff}.playbook-hero{max-width:900px;margin:0 auto 72px;text-align:center}.playbook-kicker,.playbook-eyebrow,.signature-label{font-size:.65rem;letter-spacing:.14em;color:#1769aa;font-weight:800}.playbook-hero h1{margin:10px 0 15px;border:0;font-size:2.7rem;letter-spacing:-.035em}.playbook-deck{max-width:760px;margin:0 auto!important;font-size:1.02rem!important;line-height:1.75;color:#555}.playbook-core-flow,.signature-flow{display:flex;justify-content:center;align-items:center;flex-wrap:wrap;gap:8px;margin-top:28px}.playbook-core-flow span,.signature-flow span{padding:8px 12px;border:1px solid #dce2e7;background:#fff;font-size:.72rem}.playbook-core-flow .core,.signature-flow .focus{border-color:#1769aa;color:#1769aa;font-weight:700;background:#f7fbff}.playbook-core-flow b,.signature-flow b{color:#a8b0b6;font-weight:400}.playbook-principle{display:grid;grid-template-columns:72px minmax(0,1fr);gap:30px;padding:62px 0;border-top:1px solid #e2e5e8}.playbook-index{font-size:2.4rem;font-weight:800;color:#d7dde2;line-height:1}.playbook-principle-body>h2{max-width:790px;margin:8px 0 14px;border:0;font-size:1.85rem;line-height:1.3}.playbook-principle-body>p{max-width:820px;margin:0!important;color:#555;font-size:.95rem!important;line-height:1.75}.playbook-split{display:grid;grid-template-columns:1fr 1fr;gap:18px;margin:30px 0}.playbook-deadend,.playbook-better{padding:24px;border:1px solid #e1e5e8;background:#fafafa;text-align:center}.playbook-better{border-color:#a9c6db;background:#f8fbfe}.playbook-split small{display:block;font-size:.68rem;font-weight:700;color:#888}.playbook-better small{color:#1769aa}.paper-stack,.vision-stack{display:flex;align-items:center;justify-content:center;gap:9px;margin:20px 0}.paper-stack i,.vision-stack i{padding:7px 10px;border:1px solid #dde2e6;background:#fff;font-size:.7rem;font-style:normal}.paper-stack b,.vision-stack b{color:#aab1b6;font-weight:400}.playbook-split em{font-size:.72rem;color:#777;font-style:normal}.playbook-rule{margin:26px 0;padding:18px 20px;border-left:3px solid #1769aa;background:#f7fafc;color:#444;font-size:.9rem;line-height:1.65}.playbook-example{margin-top:35px;padding:28px;border:1px solid #dfe4e8;background:#fcfcfc}.playbook-example-tag{font-size:.63rem;color:#1769aa;font-weight:800;letter-spacing:.1em}.playbook-aigc{display:grid;grid-template-columns:1fr 1.1fr 1.35fr;gap:20px;align-items:center;margin:24px 0}.playbook-aigc-today,.playbook-aigc-ideal{min-height:210px;padding:18px;border:1px solid #dfe4e8;background:#fff;text-align:center;display:flex;flex-direction:column;justify-content:center;align-items:center}.playbook-aigc-ideal{border-color:#9cbdd6}.playbook-aigc small{font-size:.6rem;letter-spacing:.09em;color:#888}.playbook-aigc strong{margin-top:7px;font-size:.85rem}.playbook-aigc b{margin:5px;color:#aaa}.playbook-aigc span{padding:5px 10px;border:1px solid #dfe4e8;font-size:.68rem}.playbook-aigc em{font-style:normal;font-weight:700;color:#1769aa}.playbook-aigc-question{text-align:center}.playbook-aigc-question>span{display:inline-flex;align-items:center;justify-content:center;width:48px;height:48px;border-radius:50%;border:1px solid #1769aa;color:#1769aa;font-size:1.4rem}.playbook-aigc-question p{margin:10px 0 0!important;font-size:.75rem!important;line-height:1.55;color:#555}.playbook-aigc-ideal>div{display:grid;grid-template-columns:repeat(2,1fr);gap:6px;margin:7px 0}.playbook-example>p{text-align:center;margin:0!important;font-size:.82rem!important;color:#444}.playbook-equations{display:flex;gap:10px;flex-wrap:wrap;margin:24px 0}.playbook-equations span{padding:9px 12px;border:1px solid #dfe4e8;font-size:.78rem;font-weight:700}.playbook-equations .strong{border-color:#1769aa;color:#1769aa;background:#f8fbfe}.playbook-tree{max-width:850px;margin:30px auto;padding:28px;border:1px solid #dfe4e8;background:#fcfcfc;text-align:center}.tree-top{display:inline-flex;flex-direction:column;align-items:center;min-width:230px;padding:13px 24px;border:1px solid #dfe4e8;background:#fff}.tree-top>span{font-size:1.7rem}.tree-top strong{font-size:.83rem}.tree-top small{margin-top:4px;color:#a05b32;font-size:.57rem;font-weight:800}.tree-arrow{margin:9px;color:#9ca8b0}.tree-arrow small{margin-right:6px;color:#1769aa;font-size:.57rem;font-weight:700;letter-spacing:.08em}.tree-mid{display:flex;justify-content:center;gap:9px}.tree-mid span{min-width:130px;padding:9px 12px;border:1px solid #bfd3e2;background:#fff;font-size:.72rem}.tree-bottom{display:grid;grid-template-columns:repeat(3,1fr);gap:12px}.tree-bottom>div{padding:15px 10px;border:1px solid #9cbdd6;background:#fff;display:flex;flex-direction:column;align-items:center}.tree-bottom small{color:#1769aa;font-size:.58rem;font-weight:800}.tree-bottom strong{margin:6px 0;font-size:.75rem}.tree-bottom b{color:#aaa}.tree-bottom span{font-size:.7rem}.tree-bottom em{margin-top:7px;padding-top:7px;width:100%;border-top:1px solid #edf0f2;color:#777;font-size:.56rem;font-style:normal}.playbook-contrast{display:grid;grid-template-columns:1fr 50px 1fr;gap:14px;align-items:center;margin:30px 0}.playbook-contrast>div{padding:18px;border:1px solid #dfe4e8;background:#fafafa;text-align:center}.playbook-contrast>div.good{border-color:#9cbdd6;background:#f8fbfe}.playbook-contrast>div small{font-size:.62rem;font-weight:800;color:#888}.playbook-contrast>div.good small{color:#1769aa}.playbook-contrast p{margin:8px 0 0!important;font-size:.75rem!important}.playbook-contrast>b{text-align:center;color:#aaa;font-size:.65rem}.playbook-principle blockquote{margin:30px 0 0!important;padding:20px 22px!important;border-left:4px solid #1769aa!important;background:#f7fafc;font-size:1.05rem!important;font-style:normal!important;font-weight:600}.playbook-signature{padding:64px 25px 10px;border-top:1px solid #e2e5e8;text-align:center}.playbook-signature h3{margin:25px 0 8px;border:0;font-size:1.25rem}.playbook-signature p{margin:0!important;color:#666;font-size:.84rem!important}
@media(max-width:720px){.playbook-page{padding:25px 18px 60px}.playbook-topbar{margin-bottom:38px}.playbook-hero{margin-bottom:50px}.playbook-hero h1{font-size:2.05rem}.playbook-principle{grid-template-columns:1fr;gap:10px;padding:45px 0}.playbook-index{font-size:1.5rem}.playbook-principle-body>h2{font-size:1.45rem}.playbook-split,.playbook-aigc,.tree-bottom,.playbook-contrast{grid-template-columns:1fr}.paper-stack,.vision-stack{flex-wrap:wrap}.playbook-aigc-question{padding:8px 0}.tree-mid{display:grid;grid-template-columns:1fr}.tree-mid span{min-width:0}.playbook-contrast>b{padding:2px}.playbook-tree{padding:20px 12px}.playbook-signature{padding-left:0;padding-right:0}}
</style>

<script>
(function(){var page=document.getElementById('research-playbook');if(!page)return;var bs=page.querySelectorAll('.playbook-lang button');function setLang(l){page.setAttribute('data-lang',l);bs.forEach(function(b){b.classList.toggle('active',b.getAttribute('data-lang')===l);});try{localStorage.setItem('research-playbook-lang',l);}catch(e){}}bs.forEach(function(b){b.addEventListener('click',function(){setLang(b.getAttribute('data-lang'));});});var l='zh';try{l=localStorage.getItem('research-playbook-lang')||'zh';}catch(e){}setLang(l);})();
</script>
