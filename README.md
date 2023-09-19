# Awesome-Robotics-and-Autonomous-Agents [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
> Areas covered in this repo:
> `Robotics`, `AI Agents`, `Autonomous Agents`, `Multi-agents`, `LLM`

All about Autonomous AI Agents you need are here.

Currently, there are two main directions, LLM-based Agents and RL-based Agents. This repo mainly focuses on LLM-based Agents.

**For more details please refer to:** [Ray's Notion Page](https://ruisun.notion.site/AI-Agents-02dfa18bd0ca448ea11e585f8b4bb40b?pvs=4)

## Table of Content

* [About Autonomous Agents](#about)
* [Papers](#papers)
	* [LLM Based](#llm_based)
	* [Traditional](#traditional)
	* [Consciousness](#consciousness)
* [Product](#product)
* [Expert Roles LLM](#expert_roles_llm)
* [Useful Blogs and Resources ](#blogs_and_resources)

## <a name="about"></a> About Autonomous Agents
**What is Agent?**
Agent = LLM + Memory + Plan + Tool + Neuron + Intuition

**How do agents collaborate?**
Multi-agents = Agents + Environment + SOP + Auditing + Routing + Subscribtion + Economics

**Three Models of Human-AI Synergy**
1. AI Embedded mode: The original task flow remains unchanged, people perform it step by step, and at some point in the middle we stop doing it ourselves and hand it over to the AI.
2. AI Copilot mode: Keeping the original task flow order, AI provides a shortcut to execute the entire task flow at once, and the whole process is transparent, so people can intervene at any step in between.
3. AI Agent mode: People don't care how the task is executed, leave it all to AI.
<div align="center">
<img align="center" height="400" src="http://p1.itc.cn/images01/20230810/2ef929fbf16e43c68b0da53775dfd2d7.png">
</div>


## <a name="papers"></a> Papers

For details please refer to [Papers List](papers)

### <a name="llm_based"></a> LLM Based

- **A Survey on Large Language Model based Autonomous Agents** `Survey`<br>
  *Lei Wang, Chen Ma, Xueyang Feng, Zeyu Zhang, Hao Yang, Jingsen Zhang, Zhiyuan Chen, Jiakai Tang, Xu Chen, Yankai Lin, Wayne Xin Zhao, Zhewei Wei, Ji-Rong Wen* <br>
  arXiv, 2023. [[Paper](https://arxiv.org/abs/2308.11432)] [[Code](https://github.com/Paitesanshi/LLM-Agent-Survey)]


- **AgentSims: An Open-Source Sandbox for Large Language Model Evaluation** <br>
  ** <br>
  arXiv, 2023.08. [[Paper](https://arxiv.org/abs/2308.04026)] [[Code](https://github.com/py499372727/AgentSims)]
  
- **MetaGPT: Meta Programming for Multi-Agent Collaborative Framework** <br>
  ** <br>
  arXiv, 2023.08. [[Paper](https://arxiv.org/abs/2308.00352)] [[Code](https://github.com/geekan/MetaGPT)]
  

- **WebArena: A Realistic Web Environment for Building Autonomous Agents** <br>
  ** <br>
  arXiv, 2023.07. [[Paper](https://arxiv.org/abs/2307.13854)] [[Code](https://github.com/web-arena-x/webarena)]


5. [[arXiv 2023.07]](https://arxiv.org/pdf/2307.05300) **Unleashing Cognitive Synergy in Large Language Models: A Task-Solving Agent through Multi-Persona Self-Collaboration** [[Code](https://github.com/MikeWangWZHL/Solo-Performance-Prompting)]
6. [[arXiv 2023.07]](https://arxiv.org/pdf/2307.00660) **Minimum Levels of Interpretability for Artificial Moral Agents**
7. [[arXiv 2023.05]](https://arxiv.org/pdf/2305.20076) **Decision-Oriented Dialogue for Human-AI Collaboration** [[Code](https://github.com/jlin816/dialop)]
8. [[arXiv 2023.05]](https://arxiv.org/pdf/2303.17580.pdf) **HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in Hugging Face**
9. [[arXiv 2023.05]](https://arxiv.org/abs/2305.13246) **Interactive Natural Language Processing** `Survey`
10. [[arXiv 2023.05]](https://arxiv.org/pdf/2305.11598) **Introspective Tips: Large Language Model for In-Context Decision Making**
- **ExpeL: LLM Agents Are Experiential Learners** <br>
  *Andrew Zhao, Daniel Huang, Quentin Xu, Matthieu Lin, Yong-Jin Liu, Gao Huang* <br>
  arXiv, 2023.08. [[Paper](https://arxiv.org/abs/2308.10144)] 
- **Communicative Agents for Software Development** <br>
  *Chen Qian, Xin Cong, Wei Liu, Cheng Yang, Weize Chen, Yusheng Su, Yufan Dang, Jiahao Li, Juyuan Xu, Dahai Li, Zhiyuan Liu, Maosong Sun* <br>
  arXiv, 2023.07 [[Paper](https://arxiv.org/abs/2307.07924)] 
- **Cognitive Architectures for Language Agents** <br>
  *Theodore Sumers, Shunyu Yao, Karthik Narasimhan, Thomas L. Griffiths* <br>
  arXiv, 2023.09 [[Paper](https://arxiv.org/abs/2309.02427)] 
- **AgentVerse: Facilitating Multi-Agent Collaboration and Exploring Emergent Behaviors in Agents** <br>
  *Weize Chen and Yusheng Su and Jingwei Zuo and Cheng Yang and Chenfei Yuan and Chen Qian and Chi-Min Chan and Yujia Qin and Yaxi Lu and Ruobing Xie and Zhiyuan Liu and Maosong Sun and Jie Zhou* <br>
  arXiv, 2023.08 [[Paper](https://arxiv.org/abs/2308.10848)] 
- **Agents: An Open-source Framework for Autonomous Language Agents** <br>
  *Wangchunshu Zhou, Yuchen Eleanor Jiang, Long Li, Jialong Wu, Tiannan Wang, Shi Qiu, Jintian Zhang, Jing Chen, Ruipu Wu, Shuai Wang, Shiding Zhu, Jiyu Chen, Wentao Zhang, Ningyu Zhang, Huajun Chen, Peng Cui, Mrinmaya Sachan* <br>
  arXiv, 2023.08 [[Paper](https://arxiv.org/abs/2309.07870)] 
- **The Rise and Potential of Large Language Model Based Agents: A Survey** <br>
  *Zhiheng Xi and Wenxiang Chen and Xin Guo and Wei He and Yiwen Ding and Boyang Hong and Ming Zhang and Junzhe Wang and Senjie Jin and Enyu Zhou and Rui Zheng and Xiaoran Fan and Xiao Wang and Limao Xiong and Yuhao Zhou and Weiran Wang and Changhao Jiang and Yicheng Zou and Xiangyang Liu and Zhangyue Yin and Shihan Dou and Rongxiang Weng and Wensen Cheng and Qi Zhang and Wenjuan Qin and Yongyan Zheng and Xipeng Qiu and Xuanjing Huang and Tao Gui* 复旦大学NLP <br>
  arXiv, 2023.08 [[Paper](https://arxiv.org/abs/2309.07864)] [[Code](https://github.com/WooooDyy/LLM-Agent-Paper-List)]


### <a name="traditional"></a> Traditional

1. [[IJCAI’22]](https://www.ijcai.org/proceedings/2022/0344.pdf) **Forming Effective Human-AI Teams: Building Machine Learning Models that Complement the Capabilities of Multiple Experts**
2. [[EMNLP’21]](https://aclanthology.org/2021.emnlp-main.85.pdf) **MindCraft: Theory of Mind Modeling for Situated Dialogue in Collaborative Tasks**
3. [[arXiv 2017.03]](https://arxiv.org/pdf/1704.00717) **It Takes Two to Tango: Towards Theory of AI's Mind**
4. [[arXiv 2021.03]](https://arxiv.org/pdf/2103.09990) **Human-AI Symbiosis: A Survey of Current Approaches**
5. [[arXiv 2023.08]](https://arxiv.org/abs/2308.08155) **AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation Framework**

### <a name="consciousness"></a> Consciousness
- **It Takes Two to Tango: Towards Theory of AI's Mind** `Survey`<br>
  *Patrick Butlin, Robert Long, Eric Elmoznino, Yoshua Bengio, Jonathan Birch, Axel Constant, George Deane, Stephen M. Fleming, Chris Frith, Xu Ji, Ryota Kanai, Colin Klein, Grace Lindsay, Matthias Michel, Liad Mudrik, Megan A. K. Peters, Eric Schwitzgebel, Jonathan Simon, Rufin VanRullen* <br>
  arXiv, 2023.08. [[Paper](https://arxiv.org/abs/2308.08708)] 

## <a name="product"></a> Product
For details please refer to [Products List](products)

AI Agents Landscape, by July 2023  [E2B](https://e2b.dev/blog/ai-agents-in-the-wild)
<div align="center">
<img align="center" height="800" src="https://framerusercontent.com/images/KbZcWUWytUkP0qPk1yF2eeM6E.png">
</div>

- `R&D` **BabyAG** <br>
[[Code](https://github.com/yoheinakajima/babyagi)]![](https://img.shields.io/github/stars/yoheinakajima/babyagi?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/yoheinakajima/babyagi?style=round-square&logo=Github&logoColor=white)
2. `R&D` [Langchain](https://github.com/hwchase17/langchain) ![](https://img.shields.io/github/stars/hwchase17/langchain?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/hwchase17/langchain?style=round-square&logo=Github&logoColor=white)
3. `R&D` [Auto-GPT](https://github.com/Significant-Gravitas/Auto-GPT) ![](https://img.shields.io/github/stars/Significant-Gravitas/Auto-GPT?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/Significant-Gravitas/Auto-GPT?style=round-square&logo=Github&logoColor=white)
4. `R&D` [MetaGPT](https://github.com/geekan/MetaGPT) ![](https://img.shields.io/github/stars/geekan/MetaGPT?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/geekan/MetaGPT?style=round-square&logo=Github&logoColor=white)
5. `R&D` [Generative Agents](https://github.com/joonspk-research/generative_agents) ![](https://img.shields.io/github/stars/joonspk-research/generative_agents?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/joonspk-research/generative_agents?style=round-square&logo=Github&logoColor=white)
6. `R&D` [WebArena](https://github.com/web-arena-x/webarena) ![](https://img.shields.io/github/stars/web-arena-x/webarena?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/web-arena-x/webarena?style=round-square&logo=Github&logoColor=white)
7. `R&D` [AI Town](https://github.com/a16z-infra/ai-town) ![](https://img.shields.io/github/stars/a16z-infra/ai-town?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/a16z-infra/ai-town?style=round-square&logo=Github&logoColor=white)
8. `R&D` [AgentSims](https://github.com/py499372727/AgentSims) ![](https://img.shields.io/github/stars/py499372727/AgentSims?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/py499372727/AgentSims?style=round-square&logo=Github&logoColor=white)
9. `R&D` [Lagent](https://github.com/InternLM/lagent) ![](https://img.shields.io/github/stars/InternLM/lagent?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/InternLM/lagent?style=round-square&logo=Github&logoColor=white)
10. `R&D` [GPT Researcher](https://github.com/assafelovic/gpt-researcher) ![](https://img.shields.io/github/stars/assafelovic/gpt-researcher?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/assafelovic/gpt-researcher?style=round-square&logo=Github&logoColor=white)
- `R&D` **ChatDev** <br>
[[Code](https://github.com/OpenBMB/ChatDev)]![](https://img.shields.io/github/stars/OpenBMB/ChatDev?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/OpenBMB/ChatDev?style=round-square&logo=Github&logoColor=white)

- `R&D` **AgentVerse** <br>
[[Code](https://github.com/OpenBMB/AgentVerse)]![](https://img.shields.io/github/stars/OpenBMB/AgentVerse?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/OpenBMB/AgentVerse?style=round-square&logo=Github&logoColor=white)

- `R&D Code Not Released` **CoALA** <br>
[[Code](https://github.com/ysymyth/awesome-language-agents)]![](https://img.shields.io/github/stars/ysymyth/awesome-language-agents?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/ysymyth/awesome-language-agents?style=round-square&logo=Github&logoColor=white)

- `R&D` **AIWaves Agents** <br>
[[Code](https://github.com/aiwaves-cn/agents)]![](https://img.shields.io/github/stars/aiwaves-cn/agents?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/aiwaves-cn/agents?style=round-square&logo=Github&logoColor=white)
11. `Business` [AI Agent](https://aiagent.app/) is a flexible app that lets user create their own agents, by setting a name with an objective.
12. `Business` [AgentGPT](https://github.com/reworkd/AgentGPT) ![](https://img.shields.io/github/stars/reworkd/AgentGPT?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/reworkd/AgentGPT?style=round-square&logo=Github&logoColor=white) Allowing user to configure and deploy Autonomous AI agents. Name users' own custom AI and have it embark on any goal imaginable. It will attempt to reach the goal by thinking of tasks to do, executing them, and learning from the results
13. `Business` [SuperAGI](https://github.com/TransformerOptimus/SuperAGI)![](https://img.shields.io/github/stars/TransformerOptimus/SuperAGI?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/TransformerOptimus/SuperAGI?style=round-square&logo=Github&logoColor=white)
- `Business` **Council** <br>
[[Code](https://github.com/chain-ml/council)]![](https://img.shields.io/github/stars/chain-ml/council?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/chain-ml/council?style=round-square&logo=Github&logoColor=white)
## <a name="expert_roles_llm"></a> Expert Roles LLM
### For Coding
1. `Based LLaMa 2` [Code Llama](https://about.fb.com/news/2023/08/code-llama-ai-for-coding/) By Meta AI · August 24, 2023

## <a name="blogs_and_resources"></a> Useful Blogs and Resources 

1. [AI领域的agent是什么意思？](https://www.zhihu.com/question/51195225/answer/3097467077) Answered by AI的潜意识 · July 3, 2023
2. [What is an AI agent?](https://zapier.com/blog/ai-agent/) By Miguel Rebelo · June 1, 2023
3. [框架阅读：langchain精读](https://deepwisdom.feishu.cn/wiki/wikcnhYysy7aaewetJ2sUlZMbeh) by MetaGPT team · May 8, 2023
4. [框架速度：SuperAGI](https://deepwisdom.feishu.cn/wiki/RlcCwJENIiC0YNkiu6Dcc9Ornlb) by MetaGPT team · Jun 5, 2023
5. [AI革新之路：14篇AI Agents论文，探讨人工智能未来](https://mp.weixin.qq.com/s/apSIgDlU6szfEuKSvvDXGw) by AMiner科技 · Sep 2, 2023
6. [AI Agent+to B，下一个入口级平台机会｜甲子光年](https://mp.weixin.qq.com/s/Lwr8CnJ0-Ky2md1j5TfW7w) by 武静静 · Sep 15, 2023
7. `Video` [Harrison Chase - Agents Masterclass from LangChain Founder (LLM Bootcamp)](https://www.youtube.com/watch?v=DWUdGhRrv2c) by The Full Stack · May 25, 2023  - Harrison Chase （LangChain CEO）25分钟关于GPT Agents的tutorial 


## Acknowledgement
- [Awesome-Embodied-AI](https://github.com/haoranD/Awesome-Embodied-AI) by Haoran Duan

----
## Citation
If you find this repository useful, please consider citing this list:
```
@misc{rui2023roboticsautonomousagentslist,
    title = {Awesome-Robotics-and-Autonomous-Agents},
    author = {Rui Sun},
    journal = {GitHub repository},
    url = {https://github.com/ray-ruisun/Awesome-Robotics-and-Autonomous-Agents},
    year = {2023},
}
```

## References
1. [MetaGPT作者深度解析直播回放](https://www.bilibili.com/video/BV1Ru411V7XL)
2. [从生成式AI到合成式AI ，MarTech下一步如何进化](http://news.sohu.com/a/710542412_99984157)by 晓晓 · Aug 10, 2023