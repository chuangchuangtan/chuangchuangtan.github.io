---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>


I am a fourth-year Ph.D. student at the [Institute of Information Science(IIS)](http://iis.bjtu.edu.cn/en/Default.aspx), School of Computer Science & Technology, Beijing Jiaotong University (BJTU), under the guidance of [Prof. Yao Zhao](http://mepro.bjtu.edu.cn/zhaoyao/c_index.htm). I obtained my Master's degree from Beijing Jiaotong University and my Bachelor's degree from Yanshan University. My research is focused on AIGC detection and AI safety. I have published 19 research papers in respected conferences and journals such as CVPR, AAAI, and IEEE TMM.

If you have an interest in these topics or are seeking research collaboration, please feel free to contact me via email. I am always eager to collaborate with outstanding researchers!

<font color="red"> Additionally, I am actively seeking full-time positions. If you are interested, please do not hesitate to reach out. </font>





# 🔥 News
- *2024.2*: &nbsp;📄 2 paper Accepted by CVPR 2024! Thanks for all my co-authors!
- *2024.12*: &nbsp;📄 2 paper Accepted by AAAI 2025! Thanks for all my co-authors!


# 📝 Publications 


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='images/C2P-CLIP.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

C2P-CLIP: Injecting Category Common Prompt in CLIP to Enhance Generalization in Deepfake Detection. [pdf](https://arxiv.org/abs/2408.09647). [Github](https://github.com/chuangchuangtan/C2P-CLIP-DeepfakeDetection).

**Chuangchuang Tan**, Renshuai Tao, Huan Liu, Guanghua Gu, Baoyuan Wu, Yao Zhao, Yunchao Wei.

arXiv preprint arXiv:2408.09647.

- Underlying mechanisms of CLIP’s detection capabilities.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/NPR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Rethinking the up-sampling operations in cnn-based generative network for generalizable deepfake detection. [pdf](https://arxiv.org/abs/2312.10461). [Code](https://github.com/chuangchuangtan/NPR-DeepfakeDetection). [Online Demo](https://huggingface.co/spaces/tancc/Generalizable_Deepfake_Detection-NPR-CVPR2024).

**Chuangchuang Tan**, Huan Liu, Yao Zhao, Shikui Wei, Guanghua Gu, Ping Liu, Yunchao Wei.

Computer Vision and Pattern Recognition (*CVPR*) 2024. 

- Rethinking the upsampling structure in generators and mining Neighboring Pixel Relationships(NPR) as universal forgery traces.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/Lgrad.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Learning on Gradients: Generalized Artifacts Representation for GAN-Generated Images Detection. [pdf](https://openaccess.thecvf.com/content/CVPR2023/papers/Tan_Learning_on_Gradients_Generalized_Artifacts_Representation_for_GAN-Generated_Images_Detection_CVPR_2023_paper.pdf). [Code](https://github.com/chuangchuangtan/LGrad).

**Chuangchuang Tan**, Yao Zhao, Shikui Wei, Guanghua Gu, Yunchao Wei.

Computer Vision and Pattern Recognition (*CVPR*) 2023. 

- A new generalized feature, Gradients, is developed to serve as a representation of the artifacts produced
by GAN models.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2023</div><img src='images/DIO.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Data-Independent Operator: A Training-Free Artifact Representation Extractor for Generalizable Deepfake Detection. [pdf](https://arxiv.org/abs/2403.06803). [Code](https://github.com/chuangchuangtan/Data-Independent-Operator).

**Chuangchuang Tan**, Yao Zhao, Ping Liu, Guanghua Gu, ShiKui Wei, Baoyuan Wu, Yunchao Wei.

arXiv preprint arXiv:2403.06803.

- we definethe Data-Independent Operator (*DIO*) to achieve appealing improvements on unseen sources..

</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='images/freqnet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Frequency-Aware Deepfake Detection: Improving Generalizability through Frequency Space Domain Learning. [pdf](https://arxiv.org/abs/2403.07240). [Code](https://github.com/chuangchuangtan/FreqNet-DeepfakeDetection).

**Chuangchuang Tan**, Yao Zhao, Shikui Wei, Guanghua Gu, Ping Liu, Yunchao Wei.

Proceedings of the (*AAAI*) Conference on Artificial Intelligence 2024.

- A novel frequency-aware approach called FreqNet, centered around frequency domain learning.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2020</div><img src='images/dgl.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Dual-Gradients Localization Framework for Weakly Supervised Object Localization [](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&tzom=-480&user=ufR1PmMAAAAJ&citation_for_view=ufR1PmMAAAAJ:2tRrZ1ZAMYUC)

**Chuangchuang Tan**, Guanghua Gu, Tao Ruan, Shikui Wei, Yao Zhao.

ACM International Conference on Multimedia (*ACM MM*) 2020.

- An localization framework to achieve precise localization on any convolutional layer of a classification model by exploiting two kinds of gradients, called Dual-Gradients Localization (DGL) framework.  
</div>
</div>


# 📖 Educations
- *2021.09 - Now*, Ph.D. Student, School of Computer Science & Technology, Beijing Jiaotong University (BJTU), Beijing, China. 
- *2018.09 - 2021.06*, Master. Student, School of Computer Science & Technology, Beijing Jiaotong University (BJTU), Beijing, China.
- *2014.09 - 2018.06*, Bachelor, Yanshan University, Qinhuangdao, China. 



# 🎖 Awards
- *2024.10*, National Scholarship.
- *2020.06*, National Scholarship.
- *2017.06*, Awarded the title of ”Person of the Year” at Yanshan University.

# 💻 Internships
- *2024.09 - now*, MSRA • MC Group, Beijing, China.
- *2023.01 – 2023.10*, Visit to Singapore’s A*STAR • CFAR Exchange.
