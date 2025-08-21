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

I am a fifth-year student in the master’s-doctoral combined program at the University of Chinese Academy of Sciences (2020–present). My research interests include multimodal large model reasoning, multimodal agent reasoning, and knowledge distillation.

Feel free to contact me via email for academic discussions or internship opportunities! I am expected to graduate in June 2026 and look forward to job opportunities.

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2025.08*: &nbsp;🎉🎉 One paper on <span style="color:#a4dded;">**ChartMind (Chart Question Answering)**</span> has been accepted by <span style="color:#a4dded;">**EMNLP 2025**</span>.
- *2025.08*: &nbsp;🎉🎉 Our collaborative technical report with the <span style="color:#f4b400;">**Seed Team**</span>, <span style="color:#a4dded;">**StructVRM**</span>, has been released! This work focuses on deep thinking in large models and achieves remarkable performance in mathematical and scientific reasoning. [Paper link](https://arxiv.org/pdf/2508.05383), [Results link](https://mp.weixin.qq.com/s/fI8Xx2FvtnPLpREKjykIJA).
- *2025.07*: &nbsp;🎉🎉 One paper on <span style="color:#a4dded;">**Multimodal Scientific reasoning**</span> has been accepted by <span style="color:#a4dded;">**ACM Multimedia 2025**</span>.
- *2025.05*: &nbsp;🎉🎉 One paper on <span style="color:#a4dded;">**Multimodal Chain-of-Thought Verification**</span> has been accepted by <span style="color:#a4dded;">**ACL 2025**</span>.
- *2025.04*: &nbsp;🎉🎉 One paper on <span style="color:#a4dded;">**Sketch-to-Diagram**</span> has been accepted by <span style="color:#a4dded;">**IJCAI 2025**</span>.
- *2025.04*: &nbsp;🎉🎉 One paper on <span style="color:#a4dded;">**Chinese Multimodal Attribute Extraction**</span> has been accepted by <span style="color:#a4dded;">**ICIC 2025**</span>.
- *2025.04*: &nbsp;🎉🎉 One paper on <span style="color:#a4dded;">**Document Retrieval**</span> has been accepted by <span style="color:#a4dded;">**ICIC 2025**</span>.
- *2025.04*: &nbsp;🎉🎉 One paper on <span style="color:#a4dded;">**EEG-to-Text**</span> has been accepted by <span style="color:#a4dded;">**ICIC 2025**</span>.
- *2025.02*: &nbsp;🎉🎉 One paper on <span style="color:#a4dded;">**Text-to-Diagram**</span> has been accepted by <span style="color:#a4dded;">**CVPR 2025 (highlight)**</span>.  
- *2024.07*: &nbsp;🎉🎉 One paper on <span style="color:#a4dded;">**Multimodal Chain-of-Thought**</span> is accepted by <span style="color:#a4dded;">**ECCV 2024**</span>.  
- *2024.07*: &nbsp;🎉🎉 One paper on <span style="color:#a4dded;">**Multimodal Chain-of-Thought**</span> is accepted by <span style="color:#a4dded;">**NCAA**</span>.  
- *2024.06*: &nbsp;🎉🎉 One paper on <span style="color:#a4dded;">**A Survey on Multimodal Large Model Applications**</span> is accepted by <span style="color:#a4dded;">**CIBM**</span>.  
- *2024.05*: &nbsp;🎉🎉 One paper on <span style="color:#a4dded;">**Interpretable and Generalizable Spatiotemporal Learning**</span> is accepted by <span style="color:#a4dded;">**ECML-PKDD 2024**</span>.  
- *2024.04*: &nbsp;🎉🎉 One paper on <span style="color:#a4dded;">**Knowledge Distillation**</span> is accepted by <span style="color:#a4dded;">**IJCAI 2024**</span>.  
<!-- - *2025.06*: &nbsp;🎉🎉 I joined the <span style="color:#f4b400;">**Seed Team**</span> in April 2025! Congrats to our <span style="color:#f4b400;">**Deep Thinking LLM**</span> for successfully launching and achieving impressive results in the Gaokao! [PR link](https://mp.weixin.qq.com/s/fI8Xx2FvtnPLpREKjykIJA). -->

# 📝 Publications 
<div style="display: flex; align-items: center; justify-content: flex-start; margin-bottom: 30px; gap: 20px; width: 100%;">

  <!-- 左侧图片，占 1/3 页面宽度 -->
  <div style="flex: 1; max-width: 40%; text-align: center;">
    <div style="background-color: #007bff; color: white; padding: 5px 10px; display: inline-block; border-radius: 5px; margin-bottom: 10px;">
      CVPR 2025
    </div>
    <img src="images/paper_text_to_diagram.png" alt="Text-to-Diagram" style="width: 100%; height: auto; border-radius: 5px;">
  </div>

  <!-- 右侧文本，占 2/3 页面宽度 -->
  <div style="flex: 1; padding-left: 20px;">
    <h3 style="margin: 0;">
      <a href="https://arxiv.org/pdf/2411.11916" style="text-decoration: none; color: #007bff; font-weight: bold;">
        From Words to Structured Visuals: A Benchmark and Framework for Text-to-Diagram Generation and Editing
      </a>
    </h3>
    <p style="font-style: italic; margin: 5px 0;">
      Jingxuan Wei, Cheng Tan, Qi Chen, Gaowei Wu, Siyuan Li, Zhangyang Gao, Linzhuang Sun, Bihui Yu, Ruifeng Guo
    </p>
    <p>
      <a href="https://arxiv.org/pdf/2411.11916" style="text-decoration: none; color: #007bff; font-weight: bold;">[PDF]</a> &nbsp;|&nbsp;
      <a href="https://diagramagent.github.io/" style="text-decoration: none; color: #007bff; font-weight: bold;">[GitHub]</a> &nbsp;|&nbsp;
      <a href="#" style="text-decoration: none; color: #007bff; font-weight: bold;">[BibTeX]</a>
    </p>
    <!-- BibTeX 代码块，字体变小 -->
    <!-- BibTeX 代码块，优化换行 -->
<pre style="background-color: #f4f4f4; padding: 6px; border-radius: 3px; 
            overflow-x: auto; font-family: monospace; color: black; 
            white-space: pre-wrap; word-wrap: break-word; word-break: break-word; 
            font-size: 10px; line-height: 1.2; max-width: 100%;">
@article{wei2024words,
  title={From Words to Structured Visuals: A Benchmark and Framework for
         Text-to-Diagram Generation and Editing},
  author={Wei, Jingxuan and Tan, Cheng and Chen, Qi and Wu, Gaowei and 
          Li, Siyuan and Gao, Zhangyang and Sun, Linzhuang and Yu, Bihui and 
          Guo, Ruifeng},
  journal={CVPR},
  year={2025}
}
</pre>
  </div>
</div>

<!-- 第二篇论文 -->
<!-- 第二篇论文 -->
<div style="display: flex; align-items: center; justify-content: flex-start; margin-bottom: 30px; gap: 20px; width: 100%;">

  <!-- 左侧图片，占 40% 页面宽度 -->
  <div style="flex: 1; max-width: 40%; text-align: center;">
    <div style="background-color: #007bff; color: white; padding: 5px 10px; display: inline-block; border-radius: 5px; margin-bottom: 10px;">
      ECCV 2024
    </div>
    <img src="images/eccv.png" alt="Boosting Small Multimodal Models" style="width: 100%; height: auto; border-radius: 5px;">
  </div>

  <!-- 右侧文本，占 60% 页面宽度 -->
  <div style="flex: 1; padding-left: 20px;">
    <h3 style="margin: 0;">
      <a href="https://link.springer.com/chapter/10.1007/978-3-031-73661-2_17" style="text-decoration: none; color: #007bff; font-weight: bold;">
        Boosting the Power of Small Multimodal Reasoning Models to Match Larger Models with Self-Consistency Training
      </a>
    </h3>
    <p style="font-style: italic; margin: 5px 0;">
      Cheng Tan, Jingxuan Wei, Zhangyang Gao, Linzhuang Sun, Siyuan Li, Xihong Yang, Stan Z. Li
    </p>
    <p>
      <a href="https://link.springer.com/chapter/10.1007/978-3-031-73661-2_17" style="text-decoration: none; color: #007bff; font-weight: bold;">[PDF]</a> &nbsp;|&nbsp;
      <a href="https://github.com/chengtan9907/mc-cot" style="text-decoration: none; color: #007bff; font-weight: bold;">[GitHub]</a> &nbsp;|&nbsp;
      <a href="#" style="text-decoration: none; color: #007bff; font-weight: bold;">[BibTeX]</a>
    </p>
    <pre style="background-color: #f4f4f4; padding: 6px; border-radius: 3px; 
                overflow-x: auto; font-family: monospace; color: black; 
                white-space: pre-wrap; word-wrap: break-word; word-break: break-word; 
                font-size: 10px; line-height: 1.2; max-width: 100%;">
@inproceedings{tan2024boosting,
  title={Boosting the power of small multimodal reasoning models to match larger models with self-consistency training},
  author={Tan, Cheng and Wei, Jingxuan and Gao, Zhangyang and Sun, Linzhuang and 
          Li, Siyuan and Guo, Ruifeng and Yu, Bihui and Li, Stan Z},
  booktitle={European Conference on Computer Vision},
  pages={305--322},
  year={2024},
  organization={Springer}
}
    </pre>
  </div>
</div>

<!-- 第三篇论文 -->
<div style="display: flex; align-items: center; justify-content: flex-start; margin-bottom: 30px; gap: 20px; width: 100%;">

  <!-- 左侧图片，占 40% 页面宽度 -->
  <div style="flex: 1; max-width: 40%; text-align: center;">
    <div style="background-color: #007bff; color: white; padding: 5px 10px; display: inline-block; border-radius: 5px; margin-bottom: 10px;">
      Neural Computing and Applications, 2024
    </div>
    <img src="images/ncaa.png" alt="Enhancing Human-like Multimodal Reasoning" style="width: 100%; height: auto; border-radius: 5px;">
  </div>

  <!-- 右侧文本，占 60% 页面宽度 -->
  <div style="flex: 1; padding-left: 20px;">
    <h3 style="margin: 0;">
      <a href="https://arxiv.org/pdf/2307.12626" style="text-decoration: none; color: #007bff; font-weight: bold;">
        Enhancing Human-like Multimodal Reasoning: A New Challenging Dataset and Comprehensive Framework
      </a>
    </h3>
    <p style="font-style: italic; margin: 5px 0;">
      Jingxuan Wei, Cheng Tan, Zhangyang Gao, Linzhuang Sun, Siyuan Li, Bihui Yu, Ruifeng Guo, Stan Z. Li
    </p>
    <p>
      <a href="https://arxiv.org/pdf/2307.12626" style="text-decoration: none; color: #007bff; font-weight: bold;">[PDF]</a> &nbsp;|&nbsp;
      <a href="https://github.com/weijingxuan/COCO-MMR" style="text-decoration: none; color: #007bff; font-weight: bold;">[GitHub]</a> &nbsp;|&nbsp;
      <a href="#" style="text-decoration: none; color: #007bff; font-weight: bold;">[BibTeX]</a>
    </p>
    <pre style="background-color: #f4f4f4; padding: 6px; border-radius: 3px; 
                overflow-x: auto; font-family: monospace; color: black; 
                white-space: pre-wrap; word-wrap: break-word; word-break: break-word; 
                font-size: 10px; line-height: 1.2; max-width: 100%;">
@article{wei2024enhancing,
  title={Enhancing human-like multimodal reasoning: a new challenging dataset and comprehensive framework},
  author={Wei, Jingxuan and Tan, Cheng and Gao, Zhangyang and Sun, Linzhuang and 
          Li, Siyuan and Yu, Bihui and Guo, Ruifeng and Li, Stan Z},
  journal={Neural Computing and Applications},
  volume={36},
  number={33},
  pages={20849--20861},
  year={2024},
  publisher={Springer}
}
    </pre>
  </div>
</div>


<!-- 第四篇论文 -->
<div style="display: flex; align-items: center; justify-content: flex-start; margin-bottom: 30px; gap: 20px; width: 100%;">

  <!-- 左侧图片，占 40% 页面宽度 -->
  <div style="flex: 1; max-width: 40%; text-align: center;">
    <div style="background-color: #007bff; color: white; padding: 5px 10px; display: inline-block; border-radius: 5px; margin-bottom: 10px;">
      Computers in Biology and Medicine, 2024
    </div>
    <img src="images/survey.png" alt="Survey on Image-Text Multimodal Models" style="width: 100%; height: auto; border-radius: 5px;">
  </div>

  <!-- 右侧文本，占 60% 页面宽度 -->
  <div style="flex: 1; padding-left: 20px;">
    <h3 style="margin: 0;">
      <a href="https://www.sciencedirect.com/science/article/pii/S0010482524007947" style="text-decoration: none; color: #007bff; font-weight: bold;">
        A Survey on Advancements in Image-Text Multimodal Models: From General Techniques to Biomedical Implementations
      </a>
    </h3>
    <p style="font-style: italic; margin: 5px 0;">
      Ruifeng Guo, Jingxuan Wei, Linzhuang Sun, Bihui Yu, Guiyong Chang, Dawei Liu, Sibo Zhang, Zhengbing Yao, Mingjun Xu, Liping Bu
    </p>
    <p>
      <a href="https://www.sciencedirect.com/science/article/pii/S0010482524007947" style="text-decoration: none; color: #007bff; font-weight: bold;">[PDF]</a> &nbsp;|&nbsp;
      <!-- <span style="color: gray;">[No GitHub]</span> &nbsp;|&nbsp; -->
      <a href="#" style="text-decoration: none; color: #007bff; font-weight: bold;">[BibTeX]</a>
    </p>
    <pre style="background-color: #f4f4f4; padding: 6px; border-radius: 3px; 
                overflow-x: auto; font-family: monospace; color: black; 
                white-space: pre-wrap; word-wrap: break-word; word-break: break-word; 
                font-size: 10px; line-height: 1.2; max-width: 100%;">
@article{guo2024survey,
  title={A survey on advancements in image-text multimodal models: From general techniques to biomedical implementations},
  author={Guo, Ruifeng and Wei, Jingxuan and Sun, Linzhuang and Yu, Bihui and 
          Chang, Guiyong and Liu, Dawei and Zhang, Sibo and Yao, Zhengbing and 
          Xu, Mingjun and Bu, Liping},
  journal={Computers in Biology and Medicine},
  pages={108709},
  year={2024},
  publisher={Elsevier}
}
    </pre>
  </div>
</div>


<!-- 第五篇论文 -->
<div style="display: flex; align-items: center; justify-content: flex-start; margin-bottom: 30px; gap: 20px; width: 100%;">

  <!-- 左侧图片，占 40% 页面宽度 -->
  <div style="flex: 1; max-width: 40%; text-align: center;">
    <div style="background-color: #007bff; color: white; padding: 5px 10px; display: inline-block; border-radius: 5px; margin-bottom: 10px;">
      ECML-PKDD, 2024
    </div>
    <img src="images/pkdd.png" alt="Interpretable Spatiotemporal Predictive Learning" style="width: 100%; height: auto; border-radius: 5px;">
  </div>

  <!-- 右侧文本，占 60% 页面宽度 -->
  <div style="flex: 1; padding-left: 20px;">
    <h3 style="margin: 0;">
      <a href="https://link.springer.com/chapter/10.1007/978-3-031-70352-2_1" style="text-decoration: none; color: #007bff; font-weight: bold;">
        Interpretable and Generalizable Spatiotemporal Predictive Learning with Disentangled Consistency
      </a>
    </h3>
    <p style="font-style: italic; margin: 5px 0;">
      Jingxuan Wei, Cheng Tan, Zhangyang Gao, Linzhuang Sun, Bihui Yu, Ruifeng Guo, Stan Li
    </p>
    <p>
      <a href="https://link.springer.com/chapter/10.1007/978-3-031-70352-2_1" style="text-decoration: none; color: #007bff; font-weight: bold;">[PDF]</a> &nbsp;|&nbsp;
      <!-- <span style="color: gray;">[No GitHub]</span> &nbsp;|&nbsp; -->
      <a href="#" style="text-decoration: none; color: #007bff; font-weight: bold;">[BibTeX]</a>
    </p>
    <pre style="background-color: #f4f4f4; padding: 6px; border-radius: 3px; 
                overflow-x: auto; font-family: monospace; color: black; 
                white-space: pre-wrap; word-wrap: break-word; word-break: break-word; 
                font-size: 10px; line-height: 1.2; max-width: 100%;">
@inproceedings{wei2024interpretable,
  title={Interpretable and Generalizable Spatiotemporal Predictive Learning with Disentangled Consistency},
  author={Wei, Jingxuan and Tan, Cheng and Gao, Zhangyang and Sun, Linzhuang and 
          Yu, Bihui and Guo, Ruifeng and Li, Stan},
  booktitle={Joint European Conference on Machine Learning and Knowledge Discovery in Databases},
  pages={3--20},
  year={2024},
  organization={Springer}
}
    </pre>
  </div>
</div>


<!-- 第六篇论文 -->
<div style="display: flex; align-items: center; justify-content: flex-start; margin-bottom: 30px; gap: 20px; width: 100%;">

  <!-- 左侧图片，占 40% 页面宽度 -->
  <div style="flex: 1; max-width: 40%; text-align: center;">
    <div style="background-color: #007bff; color: white; padding: 5px 10px; display: inline-block; border-radius: 5px; margin-bottom: 10px;">
      IJCAI, 2024
    </div>
    <img src="images/ijcai2024.png" alt="Knowledge Distillation Study" style="width: 100%; height: auto; border-radius: 5px;">
  </div>

  <!-- 右侧文本，占 60% 页面宽度 -->
  <div style="flex: 1; padding-left: 20px;">
    <h3 style="margin: 0;">
      <a href="https://www.ijcai.org/proceedings/2024/0722.pdf" style="text-decoration: none; color: #007bff; font-weight: bold;">
        Sentence-Level or Token-Level? A Comprehensive Study on Knowledge Distillation
      </a>
    </h3>
    <p style="font-style: italic; margin: 5px 0;">
      Jingxuan Wei, Linzhuang Sun, Yichong Leng, Xu Tan, Bihui Yu, Ruifeng Guo
    </p>
    <p>
      <a href="https://www.ijcai.org/proceedings/2024/0722.pdf" style="text-decoration: none; color: #007bff; font-weight: bold;">[PDF]</a> &nbsp;|&nbsp;
      <!-- <span style="color: gray;">[No GitHub]</span> &nbsp;|&nbsp; -->
      <a href="#" style="text-decoration: none; color: #007bff; font-weight: bold;">[BibTeX]</a>
    </p>
    <pre style="background-color: #f4f4f4; padding: 6px; border-radius: 3px; 
                overflow-x: auto; font-family: monospace; color: black; 
                white-space: pre-wrap; word-wrap: break-word; word-break: break-word; 
                font-size: 10px; line-height: 1.2; max-width: 100%;">
@inproceedings{ijcai2024p722,
  title     = {Sentence-Level or Token-Level? A Comprehensive Study on Knowledge Distillation},
  author    = {Wei, Jingxuan and Sun, Linzhuang and Leng, Yichong and Tan, Xu and 
               Yu, Bihui and Guo, Ruifeng},
  booktitle = {Proceedings of the Thirty-Third International Joint Conference on
               Artificial Intelligence, {IJCAI-24}},
  publisher = {International Joint Conferences on Artificial Intelligence Organization},
  editor    = {Kate Larson},
  pages     = {6531--6540},
  year      = {2024},
  month     = {8},
  note      = {Main Track},
  doi       = {10.24963/ijcai.2024/722},
  url       = {https://doi.org/10.24963/ijcai.2024/722},
}
    </pre>
  </div>
</div>

[**Others**](https://scholar.google.com/citations?user=_rbVn8MAAAAJ&hl=zh-CN) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- **arXiv**: MM-Verify: Enhancing Multimodal Reasoning with Chain-of-Thought Verification. Sun, Linzhuang and Liang, Hao and **Wei, Jingxuan** et al.  
- **SMC**: Faster and More Efficient Subject Image Generation for Text-to-Image Diffusion Models. Yu, Bihui and Yao, Zhengbing and **Wei, Jingxuan** et al.  
- **SMC**: SAM-Wav2lip++: Enhancing Behavioral Realism in Synthetic Agents Through Audio-Driven Speech and Action Refinement. Yu, Bihui and Liu, Dawei and **Wei, Jingxuan** et al.  
- **ADMA**: TED-CS: Textual Enhanced Sensitive Video Detection with Common Sense Knowledge. Yu, Bihui and Sun, Linzhuang and **Wei, Jingxuan** et al.  
- **Computers & Electrical Engineering**: Feature-guided Multimodal Sentiment Analysis Towards Industry 4.0. Yu, Bihui and **Wei, Jingxuan** et al.  







# 🎖 Honors and Awards
- *2018.09* <span style="color: #007bff; font-weight: bold;">Inner Mongolia Autonomous Region Merit Student</span>
- *2019.09* <span style="color: #007bff; font-weight: bold;">National Scholarship</span>
- *2020.09* <span style="color: #007bff; font-weight: bold;">Inner Mongolia Autonomous Region Merit Student</span>
- *2021.09* <span style="color: #007bff; font-weight: bold;">University of Chinese Academy of Sciences Merit Student</span>
- *2022.09* <span style="color: #007bff; font-weight: bold;">University of Chinese Academy of Sciences Merit Student</span>
- *2022.09* <span style="color: #007bff; font-weight: bold;">National Scholarship</span>

# 📖 Educations
- *2023.03-present* Ph.D. in <span style="color: #007bff; font-weight: bold;">University of Chinese Academy of Sciences</span>.  Supervisor: <span style="color: #007bff; font-weight: bold;">Prof. Ruifeng Guo</span> and <span style="color: #007bff; font-weight: bold;">Prof. Bihui Yu</span>.  
- *2020.09-2022.12* M.S. in <span style="color: #007bff; font-weight: bold;">University of Chinese Academy of Sciences</span>.  Supervisor: <span style="color: #007bff; font-weight: bold;">Prof. Bihui Yu</span>.  
- *2016.09-2020.06* B.S. in <span style="color: #007bff; font-weight: bold;">Inner Mongolia University of Science and Technology</span>.  Ranks first in the major and college.

<!-- # 💬 Invited Talks -->
# 🛠 Services
<span style="color: #007bff; font-weight: bold;">Program committee member | Reviewer</span>

- Annual Meeting of the Association for Computational Linguistics (ACL)
- Empirical Methods in Natural Language Processing (EMNLP)
- IEEE International Conference on Acoustics, Speech, and Signal Processing (ICASSP)
- International Conference on Learning Representations (ICLR)
- International Conference on Machine Learning (ICML)
- Conference and Workshop on Neural Information Processing Systems (NeurIPS)
- ACM SIGKDD International Conference on Knowledge Discovery and Data Mining (KDD)
- International Journal of Computer Vision (IJCV)

<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->