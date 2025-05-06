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

<div style='font-size:14pt; text-align:justify; font-family:Georgia; margin-top: 50pt'>

<h2 id="about-me">About Me</h2>

  <div style='width: 95%; vertical-align: middle; margin-left: 3%'>
  I am final-year Ph.D. student majoring in Computer Science at Shanghai Jiao Tong University, under the supervision of Professor Weijia Jia. I am also honored to be guided by Dr. Bo Zhang from the Shanghai Artificial Intelligence Laboratory.
My research focuses on large language models, multimodal learning, and AIGC. I've delved in document understanding and chart analysis using multimodal large language models, along with mathematical reasoning with formal languages. I'm also exploring how multi-agent systems can drive automated scientific research.
  </div>
</div>

<div style='margin-top: 30pt'></div>

<h2 id="-news"># 🔥 News</h2>
  - <p style='text-align:justify'><i>2025.02</i>: &nbsp;🎉🎉 One paper (CDM) is accepted by <font color="red">CVPR 2025</font>. </p>
  - <p style='text-align:justify'><i>2024.12</i>: &nbsp;🎉🎉 One paper (GeoX) is accepted by <font color="red">ICLR 2025</font>.</p>
  - <p style='text-align:justify'><i>2023.12</i>: &nbsp;🎉🎉 One paper (LaTexNet) is accepted by <font color="red">ICASSP 2025</font>. </p>
  - <p style='text-align:justify'><i>2024.09</i>: &nbsp;🎉🎉 One papers (AdaptiveDiffusion) is accepted by <font color="red">NeurIPS 2024</font>. </p>
  - <p style='text-align:justify'><i>2024.07</i>: &nbsp;🎉🎉 One paper (Once-for-Both) is accepted by <font color="red">CVPR 2024</font>. </p>
  - <p style='text-align:justify'><i>2024.01</i>: &nbsp;🎉🎉 One paper (ReSimAD) is accepted by <font color="red">ICLR 2024</font>. </p>
  - <p style='text-align:justify'><i>2023.12</i>: &nbsp;🎉🎉 One paper (EASInst) is accepted by <font color="red">ICASSP 2024</font>. </p>

<div style='margin-top: 30pt'></div>



<h2 id="-publications"># 📝 Selected Publications & Preprints</h2>

<style>
.toggleButton {
  background-color: #007BFF; /* 按钮的背景颜色 */
  color: white; /* 按钮的文字颜色 */
  border: none; /* 去掉按钮的边框 */
  padding: 8px 20px; /* 调整后的内边距 */
  text-align: center; /* 文本居中 */
  text-decoration: none; /* 去掉文本装饰 */
  display: inline-block; /* 使按钮在行内显示 */
  font-size: 14px; /* 调整后的字体大小 */
  margin: 4px 2px; /* 外边距 */
  cursor: pointer; /* 鼠标悬停时显示手型光标 */
  border-radius: 20px; /* 胶囊形状 */
  transition-duration: 0.4s; /* 过渡效果 */
}

.toggleButton:hover {
  background-color: white; /* 鼠标悬停时的背景颜色 */
  color: black; /* 鼠标悬停时的文字颜色 */
  border: 1px solid #007BFF; /* 鼠标悬停时的边框颜色 */
}
</style>

<div style="display: flex; gap: 10px; margin-bottom: 10px;">
  <button class="toggleButton" data-target="publications">publications</button>
  <button class="toggleButton" data-target="preprints">preprints</button>
</div>

<div id="publications" style="display: block; margin-top: 10px;">
<!-- publications -->
  
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/cdm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Image Over Text: Transforming Formula Recognition Evaluation with Character Detection Matching](https://arxiv.org/pdf/2409.03643)

Bin Wang<sup>\*</sup>, Fan Wu<sup>\*</sup>, Linke Ouyang<sup>\*</sup>, Zhuangcheng Gu, Rui Zhang, **<u>Renqiu Xia</u>**, Botian Shi, Bo Zhang, Conghui He

[[**Project**]]()[[**Paper**]](https://arxiv.org/pdf/2409.03643)
- propose a Character Detection Matching (CDM) metric, ensuring the evaluation objectivity by designing an image-level rather than a LaTeX-level metric score. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/geox.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[GeoX: Geometric Problem Solving Through Unified Formalized Vision-Language Pre-training](https://arxiv.org/pdf/2412.11863v1)

**<u>Renqiu Xia</u>**<sup>\*</sup>, Mingsheng Li<sup>\*</sup>, Hancheng Ye, Wenjie Wu, Hongbin Zhou, Jiakang Yuan, Tianshuo Peng, Xinyu Cai, Xiangchao Yan, Bin Wang, Conghui He, Botian Shi, Tao Chen, Junchi Yan, Bo Zhang

[[**Project**]]()[[**Paper**]](https://arxiv.org/pdf/2412.11863v1)
- Propose GeoX, a multi-modal large model focusing on geometric understanding and reasoning tasks which reveals the large potential of formalized visual-language pre-training in enhancing geometric problem-solving abilities.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICASSP 2025</div><img src='images/latexnet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LaTeXNet: A Specialized Model for Converting Visual Tables and Equations to LaTeX Code](https://ieeexplore.ieee.org/document/10887698)

**<u>Renqiu Xia</u>**, Hongbin Zhou, Ziming Feng, Huanxi Liu, Boan Chen, Bo Zhang, Junchi Yan

[[**Project**]]()[[**Paper**]](https://ieeexplore.ieee.org/document/10887698)
- propose LaTeXNet, a specialized model designed to automate the conversion of visual tables and equations into LaTeX code. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/adaptivediffusion.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Training-Free Adaptive Diffusion with Bounded Difference Approximation Strategy](https://arxiv.org/pdf/2410.09873)

Hancheng Ye<sup>\*</sup>, Jiakang Yuan<sup>\*</sup>, **<u>Renqiu Xia</u>**, Xiangchao Yan, Tao Chen, Junchi Yan, Botian Shi, Bo Zhang

[[**Project**]](https://jiakangyuan.github.io/AdaptiveDiffusion-project-page/)[[**Paper**]](https://arxiv.org/pdf/2410.09873)
- Propose AdaptiveDiffusion to adaptively reduce the noise prediction steps during the denoising proces guided by the third-order latent difference. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/once-for-both.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Once for Both: Single Stage of Importance and Sparsity Search for Vision Transformer Compression](https://openaccess.thecvf.com/content/CVPR2024/papers/Ye_Once_for_Both_Single_Stage_of_Importance_and_Sparsity_Search_CVPR_2024_paper.pdf)

Hancheng Ye, Chong Yu, Peng Ye, **<u>Renqiu Xia</u>**, Yansong Tang, Jiwen Lu, Tao Chen, Bo Zhang

[[**Project**]]()[[**Paper**]](https://openaccess.thecvf.com/content/CVPR2024/papers/Ye_Once_for_Both_Single_Stage_of_Importance_and_Sparsity_Search_CVPR_2024_paper.pdf)
- Propose OFB, a cost-efficient approach that simultaneously evaluates both importance and sparsity scores for VTC. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2024</div><img src='images/resimad.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ReSimAD: Zero-Shot 3D Domain Transfer for Autonomous Driving with Source Reconstruction and Target Simulation](https://arxiv.org/abs/2309.05527)

Bo Zhang<sup>\*</sup>, Xinyu Cai<sup>\*</sup>, Jiakang Yuan, Donglin Yang, Jianfei Guo, Xiangchao Yan, **<u>Renqiu Xia</u>**, Botian Shi, Min Dou, Tao Chen, Si Liu, Junchi Yan, Yu Qiao

[[**Project**]]()[[**Paper**]](https://arxiv.org/abs/2309.05527)
- Provide a new perspective and approach of alleviating the domain shifts, by proposing a Reconstruction-Simulation-Perception scheme.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICASSP 2024</div><img src='images/easinst.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[Efficient Architecture Search for Real-Time Instance Segmentation](https://ieeexplore.ieee.org/document/10446079)

**<u>Renqiu Xia</u>**, Dongyuan Zhang, Yixin Dong, Juanping Zhao, Wenlong Liao, Tao He, Junchi Yan

[[**Project**]]()[[**Paper**]](https://ieeexplore.ieee.org/document/10446079)
- propose EASInst，an efficient framework that discover practical backbone and encoder architectures for the improved sparse activation instance segmentation model. 
</div>
</div>
</div>
<div style='margin-top: 30pt'></div>

<!-- Preprints -->
<div id="preprints" style="display: none; margin-top: 10px;">

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/trustgeogen.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TrustGeoGen: Scalable and Formal-Verified Data Engine for Trustworthy Multi-modal Geometric Problem Solving](https://arxiv.org/pdf/2504.15780)

Daocheng Fu<sup>\*</sup>, Zijun Chen<sup>\*</sup>, **<u>Renqiu Xia</u>**<sup>\*</sup>, Qi Liu, Yuan Feng, Hongbin Zhou, Renrui Zhang, Shiyang Feng, Peng Gao, Junchi Yan, Botian Shi, Bo Zhang, Yu Qiao

[[**Project**]]()[[**Paper**]](https://arxiv.org/pdf/2504.15780)
-  propose a scalable data engine called TrustGeoGen for geometric problem generation, with formal verification to provide a principled benchmark.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/surveyforge.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SurveyForge: On the Outline Heuristics, Memory-Driven Generation, and Multi-dimensional Evaluation for Automated Survey Writing](https://arxiv.org/abs/2503.04629)

Xiangchao Yan<sup>\*</sup>, Shiyang Feng<sup>\*</sup>, Jiakang Yuan, **<u>Renqiu Xia</u>**, Bin Wang, Bo Zhang, Lei Bai

[[**Project**]](https://github.com/Alpha-Innovator/SurveyForge)[[**Paper**]](https://arxiv.org/abs/2503.04629)
- Propose SurveyForge which can automatically generate and refine the content of survey.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/chimera.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Chimera: Improving Generalist Model with Domain-Specific Experts](https://arxiv.org/abs/2412.05983)

Tianshuo Peng<sup>\*</sup>, Mingsheng Li<sup>\*</sup>, Jiakang Yuan, Hongbin Zhou, **<u>Renqiu Xia</u>**, Renrui Zhang, Lei Bai, Song Mao, Bin Wang, Aojun Zhou, Botian Shi, Tao Chen, Bo Zhang, Xiangyu Yue

[[**Project**]](https://alpha-innovator.github.io/chimera_page/)[[**Paper**]](https://arxiv.org/abs/2412.05983)
- a scalable and low-cost multi-modal pipeline designed to boost the ability of existing LMMs with domain-specific experts.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/docgenome.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DocGenome: An Open Large-scale Scientific Document Benchmark for Training and Testing Multi-modal Large Language Models](https://arxiv.org/pdf/2406.11633)

**<u>Renqiu Xia</u>**<sup>\*</sup>, Song Mao<sup>\*</sup>, Xiangchao Yan<sup>\*</sup>, Hongbin Zhou, Bo Zhang, Haoyang Peng, Jiahao Pi, Daocheng Fu, Wenjie Wu, Hancheng Ye, Shiyang Feng, Bin Wang, Chao Xu, Conghui He, Pinlong Cai, Min Dou, Botian Shi, Sheng Zhou, Yongwei Wang, Bin Wang, Junchi Yan, Fei Wu, Yu Qiao

[[**Project**]](https://github.com/Alpha-Innovator/DocGenome)[[**Paper**]](https://arxiv.org/pdf/2406.11633)
- present DocGenome, a structured document benchmark constructed by annotating 500K scientific documents from 153 disciplines in the arXiv open-access community, using our custom auto-labeling pipeline.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/chartx.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ChartX & ChartVLM: A Versatile Benchmark and Foundation Model for Complicated Chart Reasoning](https://arxiv.org/pdf/2402.12185)

**<u>Renqiu Xia</u>**<sup>\*</sup>, Bo Zhang<sup>\*</sup>, Hancheng Ye<sup>\*</sup>, Xiangchao Yan, Qi Liu, Hongbin Zhou, Zijun Chen, Peng Ye, Min Dou, Botian Shi, Junchi Yan, Yu Qiao

[[**Project**]](https://github.com/Alpha-Innovator/ChartVLM)[[**Paper**]](https://arxiv.org/pdf/2402.12185)
- construct ChartX, a multi-modal evaluation set covering 18 chart types and develop ChartVLM to offer a new perspective on handling multi-modal tasks that strongly depend on interpretable patterns.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/structchart.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[StructChart: On the Schema, Metric, and Augmentation for Visual Chart Understanding](https://arxiv.org/pdf/2309.11268)

**<u>Renqiu Xia</u>**<sup>\*</sup>, Haoyang Peng, Hancheng Ye, Mingsheng Li, Xiangchao Yan, Peng Ye, Botian Shi, Yu Qiao, Junchi Yan, Bo Zhang

[[**Project**]]()[[**Paper**]](https://arxiv.org/pdf/2309.11268)
- introduce StructChart, a novel framework that leverages Structured Triplet Representations (STR) to achieve a unified and label-efficient approach to chart perception and reasoning tasks.
</div>
</div>


</div>

<script>
  // 获取所有按钮并添加点击事件
  document.querySelectorAll(".toggleButton").forEach(button => {
    button.addEventListener("click", function() {
      const targetId = this.getAttribute("data-target");
      // 隐藏所有内容块
      document.querySelectorAll("#publications, #preprints").forEach(content => {
        content.style.display = "none";
      });
      // 显示对应的内容块
      const targetContent = document.getElementById(targetId);
      if (targetContent) {
        targetContent.style.display = "block";
      }
    });
  });
</script>


<h2 id="-educations"># 📖 Educations</h2>
- *2021.04 - Now*, Ph.D in Computer Science, Shanghai Jiao Tong University. 
- *2019.02 - 2020.12*, Master in Electrical Engineering (Distinction), University of Melbourne.
- *2014.09 - 2018.06*, Bachelor in Instrument for Measurement & Control (Pilot Program), Jilin University.

<div style='margin-top: 30pt'></div>


<h2 id="-internships"># 💻 Internships</h2>

- *2024.10 - Now*, [Shanghai AI Laboratory](), China.

<div style='margin-top: 30pt'></div>

# 📝 Academic Services

- Reviewer of CVPR, ICCV, ECCV, NeurIPS, ICML, ICLR, KDD, TKDE.
