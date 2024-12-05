---
permalink: /
title: "Junlin Yang's Personal Website"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi, I'm Junlin Yang, a third-year student in [Department of Computer Science and Technology](https://www.cs.tsinghua.edu.cn/csen/) at [Tsinghua University](https://www.tsinghua.edu.cn/en/), . Currently, I am fortunate to be a research intern at the [XLANG Lab](https://www.xlang.ai/) at The University of Hong Kong, under the guidance of Prof. [Tao Yu](https://taoyds.github.io/). In the past, I’ve had the privilege of interning at the [Tsinghua Pervasive HCI Group](https://pi.cs.tsinghua.edu.cn/), where I was advised with Prof. [Chun Yu](https://pi.cs.tsinghua.edu.cn/lab/people/ChunYu/) and Prof. [Yuanchun Shi](https://risingstarsasia.org/speaker_detail.php?id=34).

I am actively seeking PhD opportunities for **2026 Fall**. Feel free to reach out if you're interested in my research, looking for collaboration, or just want to chat!

<div style="text-align: center;">
   <img src="..\images\Res_interest.png" alt="替代文本" width="75%" height="75%"/>
</div>

## Research Interest
My research interests lie at the intersection of **Machine Learning** (focusing on **NLP**, **multimodal learning**, and **reinforcement learning**) and **Human-Computer Interaction** (particularly in **Human-AI Interaction**). Recently, these interests have crystallized into a core research question: 

*How can we build embodied agents—especially computer agents—that excel in solving human tasks and collaborating effectively with people?*

Within this overarching question, I have explored or am eager to explore the following topics:

1. **Building stronger embodied agents in real-world environments:**
   For instance, in the case of computer agents, what constitutes the ideal training paradigm and agent framework? What is the optimal data strategy? How can techniques from social reinforcement learning and embodied reinforcement learning be leveraged to enhance agent capabilities?
   
2. **Facilitating better Human-Agent interaction in open-world tasks:**
   How can agents more effectively understand and respond to both explicit and implicit human goals? How can they improve their performance in following instructions and collaborating with humans?
   
My ultimate aim is to guide technological development through insights derived from human and social behavior, enabling technology to better serve humanity and contribute meaningfully to society.

## Research Experience

### **AgentNet: Multimodal Computer Agent Data Scaling**  
*2024.7 - present*  
*Advised by Prof. [Tao Yu](https://taoyds.github.io/), The University of Hong Kong*  

- Proposed AgentNet, **a diverse, challenging, and real-world dataset** of computer usage scenarios aggregated from well-defined application contexts, inspired by Fei-Fei Li's ImageNet.
- Designed an efficient and handy data collection system, incorporating algorithms to improve the efficiency of collecting computer usage data, guided by HCI design principles.
- **Training VLMs** with this large volume of computer use data, exploring the scaling law of VLMs as computer use agents.
- Analyze and process AgentNet data carefully to gain valuable insights from these long-horizon human-generated tasks.

### **VideoAgentTrek: Extract Agent Trajectories from Hindsight Videos**  
*2024.7 - present*  
*Advised by Prof. [Tao Yu](https://taoyds.github.io/), The University of Hong Kong*  

- Enabled GUI agents to **learn trajectories from online videos** about computer use, inspired by OpenAI s Video PreTraining (VPT) methodology.
- **Trained an Inverse Dynamics Model (IDM)** to transform unlabeled online tutorial videos into pretraining trajectory data for autonomous agents.
- **Pretrained a vision-language model(VLM)** using large-scale data generated from online video.

### **Neural Network App Traverser Empowered by Reinforcement Learning**  
*2024.11 - present*  
*Advised by Prof. [Tao Yu](https://taoyds.github.io/), The University of Hong Kong*  

- **Designed a reward mechanism** to cost-effectively incentivize an agent to become an efficient computer interface traverser.  
- **Proposed an RL algorithmic framework** that fine-tunes VLMs with RL for computer interface traverse tasks.
- Utilized the trained computer interface traverser agent to collect large-scale grounding data with minimal human effort.  
- Designed experiments to investigate:
  - Whether an effective computer interface traverser agent can also be a competent computer task executor.  
  - **What core abilities** a computer use agent needs to acquire to considerably improve its performance in **instruction following**.  

### **EchoMind: Enhancing Group Discussions through Human-AI Collaborative Issue Mapping**  
*2023.10 - 2024.9*  
*Advised by Prof. [Chun Yu](https://pi.cs.tsinghua.edu.cn/lab/people/ChunYu/) and Prof. [Yuanchun Shi](https://www.cs.tsinghua.edu.cn/csen/info/1180/4037.htm), Tsinghua University*  

- Constructed an LLM-based AI agent to model the discussion process and the roles of participants, using this as a foundation to evaluate the seminars and guide individuals towards more effective discussions.
- implemented a practical system designed for seminar environments, specifically deployed in teaching seminar settings where a substantial amount of feedback is generated.

## Project Experience

### **MartialArtsLM: Pretraining and Fine-tuning a Model Capable of Answering Questions about Martial Arts Novels**  
*2023.8 - 2023.9*  

- **Pretrained the LM(Language Model)** using preprocessed data from novels by Louis Cha.
- **Fine-tuned the LM** with different data volumes and iteration counts, **Synthesize** an estimate of 400,000 pieces of Q&A **data** in 12 categories generated by LLM (Large Language Model).
- Built an interactive dialog system for Q&A with LM using Gradio.

### **What's the Buzz: Analysis of the Trend of Technology News Popularity on Chinese Websites in 2023**  
*2023.8 - 2023.9*  

- Crawled 8,495 news articles from sina.com from 2023.1 to 2023.8, and built an information retrieval system, using methods including inverted index, TF-IDF.
- Discovered and categorized trending tech events, using TfidfVectorizer, k-means algorithm, and t-SNE algorithm.

## Courses

### GPA: 3.91/4.00

### Selected courses over 4.0

#### CS
Introduction to Artificial Intelligence, Fundamentals of Computer Science, Foundation of Programming, Programming Training, Software Engineering, Computer Network, Formal Languages and Automata, Foundation of Object-Oriented Programming, Discrete Mathematics(2) etc.

#### Math
Probability Theory and Mathematical Statistic, Calculus A, Linear Algebra, Advanced topics in Linear Algebra, Introduction to Complex Analysis, University Physic etc.

## Awards and Honors

- **Overall Excellence Scholarship**, Tsinghua University, 2024
- **Overall Excellence Scholarship**, Tsinghua University, 2023
- **Freshman Scholarship**, Tsinghua University, 2022
- **Outstanding Student Cadre**, Tsinghua University, 2023

## Languages

- Mandarin (Native), English (Fluent)
- TOEFL: 110 (R:29, L:29, S:25, W:27)

## Skills

- Curiosity and passion for research and strong teamwork sense and skills
- Experience in pretraining, fine-tuning LM and VLM, and agent framework designing
- Experience in OpenRLHF, PyTorch, Sklearn
- Programming languages: Python > C/C++ > system verilog

## Service and Leadership

- **Class Monitor**, Tsinghua University, 2022.9 - 2023.9  
  - Honored with **Outstanding Class Award**
  - Organized several activities including lab visits, corporate visits, and interviews with **PhDs in HCI, AI**, etc., to help classmates discover research areas and future planning.

- **Founder of an Alumni Mutual-Help Platform**, Shenzhen Experimental School, 2023.1 - 2024.1  
  - The WeChat Official Account platform gained **over 50k reads** and **over 2.5k followers**
  - Disseminated comprehensive knowledge about university academic life to high school students from **diverse economic, family, and cognitive backgrounds**.

## Miscs

### Senior Mentors
At Tsinghua, I was fortunate to meet some incredibly kind, talented, and supportive seniors, including [Yuxuan Li](https://hcii.cmu.edu/people/yuxuan-li) and [Zirui Cheng](https://chengzr01.github.io/#/home), who gave me my first real insight into the world of research. During my internship at HKU, I was lucky to work closely with [Tianbao Xie](https://tianbaoxie.com/) and [Yiheng Xu](https://yihengxu.com/), who patiently guided me step by step through agent-based and multimodal research and helped me gain a deeper understanding of academic life. I’m also grateful to have collaborated with [Xinyuan Wang](https://xinyuanwangcs.github.io/) and [Bowen Wang](https://bowenbryanwang.github.io/) on projects like AgentNet. I learned much from them, and together we created meaningful work.

### Hobbies
- **Athletics**: Tennis, Badminton, jogging
- **Arts**: Music, film, reading

---
