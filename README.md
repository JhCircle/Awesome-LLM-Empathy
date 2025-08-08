# <img src="assets/images/icon.png" alt="SVG Image" width="40px"> Awesome-LLM-Empathy Papers

[![Awesome](https://awesome.re/badge.svg)](https://github.com/JhCircle/Awesome-LLM-Empathy)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
![Last Commit](https://img.shields.io/github/last-commit/JhCircle/Awesome-LLM-Empathy?color=green)
![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-red)
![GitHub Repo stars](https://img.shields.io/github/stars/JhCircle/Awesome-LLM-Empathy?style=social)
> 🧭 Exploring empathetic AI? We hope this collection proves useful in your journey. If you'd like to support the project, feel free to ⭐️ the repo and share it with your peers. Contributions are warmly welcome!

---

## 🔥 News

> 📢 This list is **actively maintained**, and community contributions are always appreciated!  
> Feel free to [open a pull request](https://github.com/JhCircle/Awesome-LLM-Empathy/pulls) if you find any relevant papers.

- 🎉 `2025-05`: **Our paper [_ReflectDiffu_](https://aclanthology.org/2025.acl-long.1235/) was accepted at ACL 2025 Main!**
   _ReflectDiffu_ boosts empathetic dialogue through psychology-inspired emotion-intent reflection in RL-guided diffusion, achieving state-of-the-art performance across key metrics and outperforming strong baselines including LLMs. 
    <details>
      <summary><strong>🖼️ Click to view our ReflectDiffu Poster (ACL 2025)</strong></summary>
      <br>
      <div align="center">
        <em>Psychology-inspired diffusion with RL for empathetic dialogue</em><br><br>
        <img src="assets/poster/ReflectDiffu.png" alt="ReflectDiffu Poster" width="60%">
        <br><br>
        <a href="assets/poster/ReflectDiffu.png" target="_blank">📄 Download PNG</a>
      </div>
      <br>
    </details>

- 🎉 `2025-05`: **Repository launched to curate a comprehensive list of Empathy-focused LM research.**

---
- [🌟 Introduction](#-introduction)
- [📜 Papers](#-papers)
  - [💡 Theory & Frameworks](#-theory--frameworks)
  - [🗣️ Empathetic Dialogue Systems](#-empathetic-dialogue-systems)
    - [🧪 Generative Approaches for Empathetic Responses](#-generative-approaches-for-empathetic-responses)
    - [📚 Knowledge-Enhanced Empathetic Dialogue](#-knowledge-enhanced-empathetic-dialogue)
    - [🎛️ Controllable & Personalized Empathy](#-controllable--personalized-empathy)
  - [🧠 Emotion & Empathy Understanding](#-emotion--empathy-understanding)
    - [🎭 Emotion Recognition in Conversations (ERC)](#-emotion-recognition-in-conversations-erc)
    - [🧩 Cognitive & Affective Empathy Modeling](#-cognitive--affective-empathy-modeling)
  - [📊 Evaluation & Benchmarking](#-evaluation--benchmarking)
  - [🌍 Applications & Use Cases](#-applications--use-cases)
  - [⚖️ Ethics & Societal Impact](#️-ethics--societal-impact)
- [🚀 Resources](#-resources)
  - [📂 Datasets](#-datasets)
  - [📚 Surveys & Overviews](#-surveys--overviews)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)

---
## 🌟 Introduction
This repository offers a **comprehensive and up-to-date collection** of research papers on **Empathy in Large Language Models (LLMs)**.

> As LLMs are increasingly integrated into real-world applications, their ability to express, understand, and simulate empathy is critical for building trustworthy and human-centric AI.

This list spans across:
- Theoretical frameworks
- Dialogue systems
- Cognitive modeling
- Evaluation strategies
- Applications and ethical concerns

Whether you're a researcher, developer, or enthusiast, this is your go-to hub for exploring empathetic LLMs.

---
## 📜 Papers
> ⚠️ **Note:** To keep this README clean, the full paper list is shown below. You can also explore the [papers](#-papers) section directly or contribute using the guidelines at the end.
### 💡 Theory & Frameworks

1. **Affective Computing in the Era of Large Language Models: A Survey from the NLP Perspective.**  
   *Yongqiang Li, Chao Wang, Haichao Li, Hongliang Zhan, Hongliang Yu, Lingfeng Qiu, Zhaoxu Li, Jiafei Hong, Xueliang Li.* [[abs](https://arxiv.org/abs/2408.04638)], Arxiv 2024.08

2. **Empathy and the Right to Be an Exception: What LLMs Can and Cannot Do.**  
   *Ryan M. Doody, Jesse M. S. Harris.* [[abs](https://arxiv.org/abs/2401.14523)], Arxiv 2024.01

3. **The Illusion of Empathy: How AI Chatbots Shape Conversation Perception.**  
   *Tingting Liu, Salvatore Giorgi, Ankit Aich, Allison Lahnala, Brenda Curtis, Lyle Ungar, Joao Sedoc.* [[abs](https://arxiv.org/abs/2411.12877)], AAAI 2025

4. **Language Models Predict Empathy Gaps Between Social In-groups and Out-groups.**  
   *Yu Hou, Hal Daumé III, Rachel Rudinger.* [[pdf](https://aclanthology.org/2025.naacl-long.611/)], NAACL 2025

5. **Empathy Through Multimodality in Conversational Interfaces.**  
   *Mahyar Abbasian, Iman Azimi, Mohammad Feli, Amir M. Rahmani, Ramesh Jain.* [[abs](https://arxiv.org/abs/2405.04777)], Arxiv 2024.05

6. **SoulChat: Improving LLMs' Empathy, Listening, and Comfort Abilities.**  
   *Yirong Chen, Xiaofen Xing, Jingkai Lin, Huimin Zheng, Zhenyu Wang, Qi Liu, Xiangmin Xu.* [[abs](https://arxiv.org/abs/2311.00273)], Findings of EMNLP 2023

7. **CoMAE: A Multi-factor Hierarchical Framework for Empathetic Response Generation.**  
    *Chujie Zheng, Yong Liu, Wei Chen, Yongcai Leng, Minlie Huang.* [[abs](https://arxiv.org/abs/2105.08316)], ACL 2021
---

### 🗣️ Empathetic Dialogue Systems

#### 🧪 Generative Approaches for Empathetic Responses

1. **ReflectDiffu: Reflect between Emotion-intent Contagion and Mimicry for Empathetic Response Generation via a RL-Diffusion Framework.**  
   *Jiahao Yuan, Zixiang Di, Zhiqing Cui, Guisong Yang, Usman Naseem.* [[pdf](https://aclanthology.org/2025.acl-long.1235/)], ACL 2025

2. **Non-Emotion-Centric Empathetic Dialogue Generation.**  
   *Yuanxiang Huangfu, Peifeng Li, Yaxin Fan, Qiaoming Zhu.* [[pdf](https://aclanthology.org/2025.coling-main.66.pdf)], COLING 2025

3. **ECC: Synergizing Emotion, Cause and Commonsense for Empathetic Dialogue Generation.**  
   *Xu Wang, Bo Wang, Yihong Tang, Dongming Zhao, Jing Liu, Ruifang He, Yuexian Hou* [[pdf](https://aclanthology.org/2025.coling-main.367/)], COLING 2025

4. **Cause-Aware Empathetic Response Generation via Chain-of-Thought Fine-Tuning.**  
   *Xinhao Chen, Chong Yang, Man Lan, Li Cai, Yang Chen, Tu Hu, Xinlin Zhuang, Aimin Zhou* [[abs](https://arxiv.org/abs/2408.11599)], Arxiv 2024.08

5. **EmPO: Emotion Grounding for Empathetic Response Generation through Preference Optimization.**  
   *Xufan Qian, Kai Chen, Min Yang, Ruifeng Xu.* [[abs](https://arxiv.org/abs/2406.19071)], Arxiv 2024.06

7. **Harnessing the Power of Large Language Models for Empathetic Response Generation.**  
   *Yushan Qian, Wei-Nan Zhang, Ting Liu.* [[abs](https://arxiv.org/abs/2310.05140)], [[code](https://github.com/27182812/LLM4ED)], Findings of EMNLP 2023

8. **DiffusEmp: A Diffusion Model-Based Framework with Multi-Grained Control for Empathetic Response Generation.**  
   *Guanqun Bi, Lei Shen, Yanan Cao, Meng Chen, Yuqiang Xie, Zheng Lin, Xiaodong He.* [[abs](https://arxiv.org/abs/2306.01657)], ACL 2023

9. **InsideOut: Unifying Emotional LLMs to Foster Empathy.**  
   *Mikhail Mozikova, Nikita Severin, Maria Glushanina, Mikhail Baklashkin, Andrey Savchenko, Ilya Makarov.* [[pdf](https://ebooks.iospress.nl/pdf/doi/10.3233/FAIA241039)], ECAI 2024

10. **SoulChat: Improving LLMs' Empathy, Listening, and Comfort Abilities.**  
   *Yirong Chen, Xiaofen Xing, Jingkai Lin, Huimin Zheng, Zhenyu Wang, Qi Liu, Xiangmin Xu.* [[abs](https://arxiv.org/abs/2311.00273)], [[code](https://github.com/scutcyr/SoulChat)], Findings of EMNLP 2023

11. **MIME: Mimicking Emotions for Empathetic Response Generation.**  
   *Navonil Majumder, Devamanyu Hazarika, Soujanya Poria, Rada Mihalcea, Erik Cambria.* [[pdf](https://aclanthology.org/2020.emnlp-main.143/)], [[code](https://github.com/declare-lab/MIME)], EMNLP 2020

12. **CoMAE: A Multi-factor Hierarchical Framework.**  
    *Chujie Zheng, Yong Liu, Wei Chen, Yongcai Leng, Minlie Huang.* [[abs](https://arxiv.org/abs/2105.08316)], Findings of ACL 2021

13. **EmpDG: Multi-resolution Interactive Empathetic Dialogue Generation.**  
    *Qintong Li, Hongshen Chen, Zhaochun Ren, Pengjie Ren, Zhaopeng Tu, Zhumin Chen .* [[abs](https://arxiv.org/abs/1911.08698)],[[code](https://github.com/qtli/EmpDG)] , COLING 2020

---
#### 📚 Knowledge-Enhanced Empathetic Dialogue

1. **Sibyl: Empowering Empathetic Dialogue Generation in Large Language Models via Sensible and Visionary Commonsense Inference.**  
   *Lanrui Wang, Jiangnan Li, Chenxu Yang, Zheng Lin, Hongyin Tang, Huan Liu, Yanan Cao, Jingang Wang, Weiping Wang.* [[pdf](https://aclanthology.org/2025.coling-main.10.pdf)], [[code](https://github.com/wlr737/Sibyl)], COLING 2025

2. **TOOL-ED: Enhancing Empathetic Response Generation with the Tool Calling Capability of LLM.**  
   *Huiying Cao, Yiqun Zhang, Shi Feng, Xiaocui Yang, Daling Wang, Yifei Zhang.* [[pdf](https://aclanthology.org/2025.coling-main.355.pdf)], COLING 2025

3. **The Emotional Spectrum of LLMs: Leveraging Empathy and Emotion-Based Markers for Mental Health Support.**  
   *Alessandro De Grandi, Federico Ravenda, Andrea Raballo, Fabio Crestani.* [[abs](https://arxiv.org/abs/2412.20068)], Arxiv 2024.12

4. **Knowledge-enhanced Mixed-initiative Dialogue System for Emotional Support Conversations.**  
   *Yang Deng, Wenxuan Zhang, Yifei Yuan, Wai Lam* [[abs](https://arxiv.org/abs/2305.10172)], [[code](https://github.com/dengyang17/KEMI)], ACL 2023

5. **CEM: Commonsense-aware Empathetic Response Generation.**  
   *Sahand Sabour, Chujie Zheng, Minlie Huang* [[abs](https://arxiv.org/abs/2109.05739)], [[code](https://github.com/Sahandfer/CEM)], AAAI 2022
---
#### 🎛️ Controllable & Personalized Empathy
1. **Sibyl: Empowering Empathetic Dialogue Generation in Large Language Models via Sensible and Visionary Commonsense Inference.**  
   *Lanrui Wang, Jiangnan Li, Chenxu Yang, Zheng Lin, Hongyin Tang, Huan Liu, Yanan Cao, Jingang Wang, Weiping Wang.* [[pdf](https://aclanthology.org/2025.coling-main.10.pdf)], ACL 2025

2. **EmpCRL: Controllable Empathetic Response Generation via In-Context Reinforcement Learning.**  
   *Mingxiu Cai, Daling Wang, Shi Feng, Yifei Zhang.* [[pdf](https://aclanthology.org/2024.lrec-main.509/)], IREC 2024

3. **EmpHi: Generating Empathetic Responses with Human-like Intents.**  
   *Mao Yan Chen, Siheng Li, Yujiu Yang.* [[abs](https://arxiv.org/abs/2211.00255)], NAACL 2022

4. **CARE: Causality Reasoning for Empathetic Responses by Conditional Graph Generation.**  
   *Jiashuo Wang, Yi Cheng, Wenjie Li.* [[abs](https://arxiv.org/abs/2211.00255)], Findings of EMNLP 2022

5. **Improving Empathetic Response Generation by Recognizing Emotion Cause in Conversations.**  
   *Jun Gao, Yuhan Liu, Haolin Deng, Wei Wang, Yu Cao, Jiachen Du, Ruifeng Xu.* [[pdf](https://aclanthology.org/2021.findings-emnlp.70/)], Findings of EMNLP 2021

---
### 🧠 Emotion & Empathy Understanding
#### 🎭 Emotion Recognition in Conversations (ERC)

1. **DialogueMMT: Dialogue Scenes Understanding Enhanced Multi-modal Multi-task Tuning for Emotion Recognition in Conversations.**  
   *Chenyuan He, Senbin Zhu, Hongde Liu, Fei Gao, Yuxiang Jia, Hongying Zan, Min Peng.* [[pdf](https://aclanthology.org/2025.coling-main.170.pdf)], COLING 2025

2. **DialogueLLM: Context and Emotion Knowledge-Tuned Large Language Models for Emotion Recognition in Conversations.**  
   *Xingning Zhang, Wei-Nan Zhang, Chao Yang, Haotian Xu, Ting Liu.* [[pdf](https://aclanthology.org/2024.findings-naacl.117.pdf)], NAACL 2024

3. **Chinchunmei at WASSA 2024: Boosting LLM's Prediction with Role-play Augmentation and Contrastive Reasoning Calibration.**  
   *Tian Li, Nicolay Rusnachenko, Huizhi Liang.* [[pdf](https://aclanthology.org/2024.wassa-1.32/)], WASSA 2024

4. **Beyond Silent Letters: Amplifying LLMs in Emotion Recognition with Vocal Nuances.**  
   *Zehui Wu, Xiaochuan Li, Jiebo Luo.* [[pdf](https://aclanthology.org/2025.findings-naacl.117.pdf)], NAACL 2025

5. **LaERC-S: Improving LLM-based Emotion Recognition in Conversation with Speaker Characteristics.**  
   *Yanan Cao, Wei-Nan Zhang, Jingang Wang, Weiping Wang.* [[pdf](https://aclanthology.org/2025.coling-main.451/)], COLING 2025
---
#### 🧩 Cognitive & Affective Empathy Modeling
1. **APTNESS: Incorporating Appraisal Theory and Emotion Support Strategies for Empathetic Response Generation.**  
   *Yuxuan Hu, Minghuan Tan, Chenwei Zhang, Zixuan Li, Xiaodan Liang, Min Yang, Chengming Li, Xiping Hu* [[abs](https://arxiv.org/abs/2407.21048)], CIKM 2024

2. **CAB: Empathetic Dialogue Generation with Cognition, Affection and Behavior.**  
   *Hao Mei, Yanan Cao, Xin Li, Xiaodong Liu, Mengchen Zhao, Yuanjie Lu, Ruifeng Xu.* [[abs](https://arxiv.org/abs/2302.01935)], [[code](https://github.com/geri-emp/CAB)], DASFAA 2023

3. **MoEL: Mixture of Empathetic Listeners.**  
   *Zhaojiang Lin, Andrea Madotto, Genta Indra Winata, Pascale Fung.* [[pdf](https://aclanthology.org/D19-1083/)], [[code](https://github.com/HLTCHKUST/MoEL)], EMNLP 2019

4. **Rational Sensibility: LLM Enhanced Empathetic Response Generation Guided by Self-presentation Theory.**  
   *Linzhuang Sun, Yao Dong, Nan Xu, Jingxuan Wei, Bihui Yu, Yin Luo.* [[pdf](https://arxiv.org/abs/2312.08702)], Arxiv 2023.12

5. **Chain of empathy: Enhancing empathetic response of large language models based on psychotherapy models.**   
   *Yoon Kyung Lee, Inju Lee, Minjung Shin, Seoyeon Bae, Sowon Hahn.* [[abs](https://arxiv.org/abs/2311.04915)], Arxiv 2023.11
---
### 📊 Evaluation & Benchmarking

1. **Apathetic or Empathetic? Evaluating LLMs' Emotional Alignments with Humans.**  
   *Jen-tse Huang, Man Ho Lam, Eric John Li, Shujie Ren, Wenxuan Wang, Wenxiang Jiao, Zhaopeng Tu, Michael R. Lyu.* [[abs](https://proceedings.neurips.cc/paper_files/paper/2024/hash/b0049c3f9c53fb06f674ae66c2cf2376-Abstract-Conference.html)], NeurIPS 2024

2. **EmotionQueen: A Benchmark for Evaluating Empathy of Large Language Models.**  
   *Yuyan Chen, Songzhou Yan, Sijia Liu, Yueze Li, Yanghua Xiao.* [[pdf](https://aclanthology.org/2024.findings-acl.128/)], Findings of ACL 2024

3. **CuLEmo: Cultural Lenses on Emotion – Benchmarking LLMs for Cross-Cultural Emotion Understanding.**  
   *Souvik Mandal, Sai Chetan R, Subham Mund, Utkarsh Srivastava, Rishita Tiwari, Anubhav Singh, Mitasur Aich, Sumit Agrawal.* [[abs](https://arxiv.org/abs/2503.10688v1)], Arxiv 2025.03


---
### 🌍 Applications & Use Cases
1. **Customizing Emotional Support: How Do Individuals Construct and Interact With LLM-Powered Chatbots.**  
   *Xi Zheng, Zhuoyang Li, Xinning Gui, Yuhan Luo.*  [[pdf](https://dl.acm.org/doi/full/10.1145/3706598.3713453)], Arxiv 2025.04

2. **From Personas to Talks: Revisiting the Impact of Personas on LLM-Synthesized Emotional Support Conversations.**  
   *Zichang Lin, Ziyang Li, Wenji Mao, Kai Chen, Sijie Cheng.* [[abs](https://arxiv.org/abs/2502.11451v1)], Arxiv 2025.02

3. **From Traits to Empathy: Personality-Aware Multimodal Empathetic Response Generation.**  
   *Jiaqiang Wu, Xuandong Huang, Zhouan Zhu, Shangfei Wang.* [[pdf](https://aclanthology.org/2025.coling-main.598/)], COLING 2025

---
### ⚖️ Ethics & Societal Impact

1. **The Illusion of Empathy: How AI Chatbots Shape Conversation Perception.**  
   *Tingting Liu, Salvatore Giorgi, Ankit Aich, Allison Lahnala, Brenda Curtis, Lyle Ungar, Joao Sedoc.* [[pdf](https://ojs.aaai.org/index.php/AAAI/article/view/33569/35724)], AAAI 2025

2. **Language Models Predict Empathy Gaps Between Social In-groups and Out-groups.**  
   *Yu Hou, Hal Daumé III, Rachel Rudinger.* [[abs](https://aclanthology.org/2025.naacl-long.611/)], NAACL 2025

3. **Empathy and the Right to Be an Exception: What LLMs Can and Cannot Do.**  
   *Ryan M. Doody, Jesse M. S. Harris.* [[abs](https://arxiv.org/abs/2401.14523)], Arxiv 2024.01

---
## 🚀 Resources
### 📂 Datasets
1. **Towards Empathetic Open-domain Conversation Models: a New Benchmark and Dataset.**  
   *Hannah Rashkin, Eric Michael Smith, Margaret Li, Y-Lan Boureau.*  [[abs](https://arxiv.org/abs/1811.00207)], [[dataset](https://github.com/facebookresearch/EmpatheticDialogues)], ACL 2019

2. **PsyQA: A Chinese Dataset for Generating Long Counseling Text for Mental Health Support.**  
   Hao Sun, Zhenru Lin, Chujie Zheng, Siyang Liu, Minlie Huang.* [[pdf](https://aclanthology.org/2021.findings-acl.130/)], Findings of ACL 2021

3. **TOOL-ED: Enhancing Empathetic Response Generation with the Tool Calling Capability of LLM .**  
   *Huiying Cao, Yiqun Zhang, Shi Feng, Xiaocui Yang, Daling Wang, Yifei Zhang.* [abs](https://arxiv.org/abs/2412.03096)], [[code](https://anonymous.4open.science/r/EKTC-3FEF)], COLING 2025

4. **EmpathicStories++: A Multimodal Dataset for Empathy towards Personal Experiences.**  
   *Jocelyn Shen, Yubin Kim, Mohit Hulse, Wazeer Zulfikar, Sharifa Alghowinem, Cynthia Breazeal, Hae Won Park.* [[abs](https://arxiv.org/abs/2405.15708)], [[code](https://mitmedialab.github.io/empathic-stories-multimodal/)], Finding of ACL 2024

5. **STICKERCONV: Generating Multimodal Empathetic Responses from Scratch .**  
   *Yiqun Zhang, Fanheng Kong, Peidong Wang, Shuang Sun, Lingshuai Wang, Shi Feng, Daling Wang, Yifei Zhang, Kaisong Song.* [[abs](https://openreview.net/forum?id=F6h0v1CTpC)],[[code](https://github.com/ZhangYiqun018/StickerConv)], ACL 2024

---

### 📚 Surveys & Overviews

1. **Affective Computing in the Era of Large Language Models: A Survey from the NLP Perspective.**  
   *Yiqun Zhang, Xiaocui Yang, Xingle Xu, Zeran Gao, Yijie Huang, Shiyi Mu, Shi Feng, Daling Wang, Yifei Zhang, Kaisong Song, Ge Yu.* [[abs](https://arxiv.org/abs/2408.04638)], Arxiv 2024.08
---

## 🎉 Contributing
⭐ Help us grow this repository! If you know any valuable works we’ve missed, don’t hesitate to contribute — every suggestion makes a difference!

We welcome and appreciate all contributions! Here’s how you can help:

- 📄 **Add or Update a Paper**  
  Contribute by adding a new paper or improving details of an existing one. Please consider the most appropriate category for the work.

- ✍️ **Use Consistent Formatting**  
  Follow the format of the existing entries to maintain clarity and consistency across the list.

- 🔗 **Include Abstract Link**  
  If the paper is from arXiv, use the `/abs/` link format for the abstract (e.g., `https://arxiv.org/abs/xxxx.xxxxx`).

- 💡 **Explain Your Edit (Optional but Helpful)**  
  A short note on why you think the paper deserves to be added or updated is appreciated and helps maintainers process your PR faster.

> **✅ Don't worry about getting everything perfect!**  
> Minor mistakes are totally fine — we’ll help fix them. What matters most is your contribution. Let's highlight your awesome work together!

### Contributors
Thanks to all our amazing contributors!

<a href="https://github.com/JhCircle/Awesome-LLM-Empathy/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=JhCircle/Awesome-LLM-Empathy" />
</a>

---
## 🙌 Citation

If you're interested in empathetic dialogue, you're welcome to take a look at our recent paper — and feel free to cite it if you find it useful:

```bibtex
@inproceedings{yuan2025reflectdiffu,
    title = "ReflectDiffu: Reflect between Emotion-intent Contagion and Mimicry for Empathetic Response Generation via a {RL}-Diffusion Framework",
    author={Yuan, Jiahao and Di, Zixiang and Cui, Zhiqing and Yang, Guisong and Naseem, Usman},
    booktitle = "Proceedings of the 63rd Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)",
    pages = "25435--25449",
    year = "2025"
}
```

---

## 📄 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
