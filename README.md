# Awesome-Robotics-and-Autonomous-Agents [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
> Areas covered in this repo:
> `Robotics`, `AI Agents`, `Autonomous Agents`, `Multi-agents`, `LLM`

All about Autonomous AI Agents you need are here.

Currently, there are two main directions, LLM-based Agents and RL-based Agents. This repo mainly focuses on LLM-based Agents.

## Table of Content

* [About Autonomous Agents](#about)
* [Autonomous Agents Papers](#autonomous_agents_papers)
	* [LLM-Based Autonomous Agents](#llm_based_auto_agents)
	* [Traditional Autonomous Agents](#traditional_auto_agents)
	* [LLM-based Swarm Intelligence](#llm_based_swarm_intelligence)
	* [Consciousness](#consciousness)
* [Robotics Papers](#robotics_papers)
  * [Foundation Model Based Robotics](#foundation_model_based_robotics)
* [Product](#product)
* [Expert Roles LLM](#expert_roles_llm)
* [Tools](#tools)
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


## <a name="autonomous_agents_papers"></a> Autonomous Agents Papers

For details please refer to [Papers List](papers)

### <a name="llm_based_auto_agents"></a> LLM-Based Autonomous Agents
- **AgentTuning: Enabling Generalized Agent Abilities for LLMs** <br>
  *Aohan Zeng, Mingdao Liu, Rui Lu, Bowen Wang, Xiao Liu, Yuxiao Dong, Jie Tang* <br>
  arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2310.12823)] [[Code](https://github.com/THUDM/AgentTuning)]
- **MusicAgent: An AI Agent for Music Understanding and Generation with Large Language Models** <br>
  *Dingyao Yu, Kaitao Song, Peiling Lu, Tianyu He, Xu Tan, Wei Ye, Shikun Zhang, Jiang Bian* <br>
  Team: Microsoft <br>
  arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2310.11954)] [[Code](https://github.com/microsoft/muzic)]
- **Language Agent Tree Search Unifies Reasoning Acting and Planning in Language Models** <br>
  *Andy Zhou, Kai Yan, Michal Shlapentokh-Rothman, Haohan Wang, Yu-Xiong Wang* <br>
  arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2310.04406)] [[Code](https://github.com/andyz245/LanguageAgentTreeSearch)]
- **SmartPlay : A Benchmark for LLMs as Intelligent Agents** <br>
  *Yue Wu, Xuan Tang, Tom M. Mitchell, Yuanzhi Li* <br>
  Team: Microsoft <br>
  arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2310.01557)] [[Code](https://github.com/microsoft/SmartPlay)]
- **A Survey on Large Language Model based Autonomous Agents** `Survey`<br>
  *Lei Wang, Chen Ma, Xueyang Feng, Zeyu Zhang, Hao Yang, Jingsen Zhang, Zhiyuan Chen, Jiakai Tang, Xu Chen, Yankai Lin, Wayne Xin Zhao, Zhewei Wei, Ji-Rong Wen* <br>
  arXiv, 2023.08 [[Paper](https://arxiv.org/abs/2308.11432)] [[Code](https://github.com/Paitesanshi/LLM-Agent-Survey)]
- **AgentSims: An Open-Source Sandbox for Large Language Model Evaluation** <br>
  *Jiaju Lin, Haoran Zhao, Aochi Zhang, Yiting Wu, Huqiuyue Ping, Qin Chen* <br>
  arXiv, 2023.08. [[Paper](https://arxiv.org/abs/2308.04026)] [[Code](https://github.com/py499372727/AgentSims)]
- **MetaGPT: Meta Programming for Multi-Agent Collaborative Framework** <br>
  *Sirui Hong, Xiawu Zheng, Jonathan Chen, Yuheng Cheng, Jinlin Wang, Ceyao Zhang, Zili Wang, Steven Ka Shing Yau, Zijuan Lin, Liyang Zhou, Chenyu Ran, Lingfeng Xiao, Chenglin Wu* <br>
  arXiv, 2023.08. [[Paper](https://arxiv.org/abs/2308.00352)] [[Code](https://github.com/geekan/MetaGPT)]
- **WebArena: A Realistic Web Environment for Building Autonomous Agents** <br>
  *Shuyan Zhou, Frank F. Xu, Hao Zhu, Xuhui Zhou, Robert Lo, Abishek Sridhar, Xianyi Cheng, Yonatan Bisk, Daniel Fried, Uri Alon, Graham Neubig* <br>
  arXiv, 2023.07. [[Paper](https://arxiv.org/abs/2307.13854)] [[Code](https://github.com/web-arena-x/webarena)]
- **Unleashing Cognitive Synergy in Large Language Models: A Task-Solving Agent through Multi-Persona Self-Collaboration** <br>
  *Zhenhailong Wang, Shaoguang Mao, Wenshan Wu, Tao Ge, Furu Wei, Heng Ji* <br>
  arXiv, 2023.07. [[Paper](https://arxiv.org/pdf/2307.05300)] [[Code](https://github.com/MikeWangWZHL/Solo-Performance-Prompting)]
- **Minimum Levels of Interpretability for Artificial Moral Agents** <br>
  *Avish Vijayaraghavan, Cosmin Badea* <br>
  arXiv, 2023.07. [[Paper](https://arxiv.org/pdf/2307.00660)] 
- **Decision-Oriented Dialogue for Human-AI Collaboration** <br>
  *Jessy Lin, Nicholas Tomlin, Jacob Andreas, Jason Eisner* <br>
  arXiv, 2023.05. [[Paper](https://arxiv.org/pdf/2305.20076)] [[Code](https://github.com/jlin816/dialop)]
- **HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in Hugging Face** <br>
  *Yongliang Shen, Kaitao Song, Xu Tan, Dongsheng Li, Weiming Lu, Yueting Zhuang* <br>
  arXiv, 2023.05. [[Paper](https://arxiv.org/abs/2303.17580)]
- **Interactive Natural Language Processing** <br>
  *Zekun Wang, Ge Zhang, Kexin Yang, Ning Shi, Wangchunshu Zhou, Shaochun Hao, Guangzheng Xiong, Yizhi Li, Mong Yuan Sim, Xiuying Chen, Qingqing Zhu, Zhenzhu Yang, Adam Nik, Qi Liu, Chenghua Lin, Shi Wang, Ruibo Liu, Wenhu Chen, Ke Xu, Dayiheng Liu, Yike Guo, Jie Fu* <br>
  arXiv, 2023.05. [[Paper](https://arxiv.org/abs/2305.13246)]
- **Introspective Tips: Large Language Model for In-Context Decision Making** <br>
  *Liting Chen, Lu Wang, Hang Dong, Yali Du, Jie Yan, Fangkai Yang, Shuang Li, Pu Zhao, Si Qin, Saravan Rajmohan, Qingwei Lin, Dongmei Zhang* <br>
  arXiv, 2023.05. [[Paper](https://arxiv.org/pdf/2305.11598)]
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
  *Zhiheng Xi and Wenxiang Chen and Xin Guo and Wei He and Yiwen Ding and Boyang Hong and Ming Zhang and Junzhe Wang and Senjie Jin and Enyu Zhou and Rui Zheng and Xiaoran Fan and Xiao Wang and Limao Xiong and Yuhao Zhou and Weiran Wang and Changhao Jiang and Yicheng Zou and Xiangyang Liu and Zhangyue Yin and Shihan Dou and Rongxiang Weng and Wensen Cheng and Qi Zhang and Wenjuan Qin and Yongyan Zheng and Xipeng Qiu and Xuanjing Huang and Tao Gui* <br>
  Team: NLP group, Fudan University <br>
  arXiv, 2023.08 [[Paper](https://arxiv.org/abs/2309.07864)] [[Code](https://github.com/WooooDyy/LLM-Agent-Paper-List)]


### <a name="traditional_auto_agents"></a> Traditional Autonomous Agents

1. [[IJCAI’22]](https://www.ijcai.org/proceedings/2022/0344.pdf) **Forming Effective Human-AI Teams: Building Machine Learning Models that Complement the Capabilities of Multiple Experts**
2. [[EMNLP’21]](https://aclanthology.org/2021.emnlp-main.85.pdf) **MindCraft: Theory of Mind Modeling for Situated Dialogue in Collaborative Tasks**
3. [[arXiv 2017.03]](https://arxiv.org/pdf/1704.00717) **It Takes Two to Tango: Towards Theory of AI's Mind**
4. [[arXiv 2021.03]](https://arxiv.org/pdf/2103.09990) **Human-AI Symbiosis: A Survey of Current Approaches**
5. [[arXiv 2023.08]](https://arxiv.org/abs/2308.08155) **AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation Framework**

### <a name="llm_based_swarm_intelligence"></a> LLM-based Swarm Intelligence 
- **Exploring Large Language Models for Communication Games: An Empirical Study on Werewolf** <br>
  *Yuzhuang Xu, Shuo Wang, Peng Li, Fuwen Luo, Xiaolong Wang, Weidong Liu, Yang Liu* <br>
  arXiv, 2023.09 [[Paper](https://arxiv.org/abs/2309.04658)] 

### <a name="consciousness"></a> Consciousness
- **It Takes Two to Tango: Towards Theory of AI's Mind** `Survey`<br>
  *Patrick Butlin, Robert Long, Eric Elmoznino, Yoshua Bengio, Jonathan Birch, Axel Constant, George Deane, Stephen M. Fleming, Chris Frith, Xu Ji, Ryota Kanai, Colin Klein, Grace Lindsay, Matthias Michel, Liad Mudrik, Megan A. K. Peters, Eric Schwitzgebel, Jonathan Simon, Rufin VanRullen* <br>
  arXiv, 2023.08. [[Paper](https://arxiv.org/abs/2308.08708)] 

## <a name="robotics_papers"></a> Robotics Papers
### <a name="foundation_model_based_robotics"></a> Foundation Model Based Robotics
- **Eureka: Human-Level Reward Design via Coding Large Language Models** <br>
  *Yecheng Jason Ma, William Liang, Guanzhi Wang, De-An Huang, Osbert Bastani, Dinesh Jayaraman, Yuke Zhu, Linxi Fan, Anima Anandkumar* <br>
  arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2310.12931)], [[Code](https://github.com/eureka-research/Eureka)]
- **Toward General-Purpose Robots via Foundation Models: A Survey and Meta-Analysis** `Survey`<br>
  *Yafei Hu, Quanting Xie, Vidhi Jain, Jonathan Francis, Jay Patrikar, Nikhil Keetha, Seungchan Kim, Yaqi Xie, Tianyi Zhang, Zhibo Zhao, Yu-Quan Chong, Chen Wang, Katia Sycara, Matthew Johnson-Roberson, Dhruv Batra, Xiaolong Wang, Sebastian Scherer, Zsolt Kira, Fei Xia, Yonatan Bisk* <br>
  arXiv, 2023.12 [[Paper](https://arxiv.org/abs/2312.08782)], [[Code](https://github.com/JeffreyYH/robotics-fm-survey)]
- **Foundation Models in Robotics: Applications, Challenges, and the Future** `Survey`<br>
  *Roya Firoozi, Johnathan Tucker, Stephen Tian, Anirudha Majumdar, Jiankai Sun, Weiyu Liu, Yuke Zhu, Shuran Song, Ashish Kapoor, Karol Hausman, Brian Ichter, Danny Driess, Jiajun Wu, Cewu Lu, Mac Schwager* <br>
  arXiv, 2023.12 [[Paper](https://arxiv.org/abs/2312.07843)], [[Code](https://github.com/robotics-survey/Awesome-Robotics-Foundation-Models)]
- **RoboGen: Towards Unleashing Infinite Data for Automated Robot Learning via Generative Simulation** <br>
  *Yufei Wang, Zhou Xian, Feng Chen, Tsun-Hsuan Wang, Yian Wang, Zackory Erickson, David Held, Chuang Gan* <br>
  arXiv, 2023.11 [[Paper](https://arxiv.org/abs/2311.01455)], [[Code](https://github.com/Genesis-Embodied-AI/RoboGen)]
- **GenSim: Generating Robotic Simulation Tasks via Large Language Models** <br>
  *Lirui Wang, Yiyang Ling, Zhecheng Yuan, Mohit Shridhar, Chen Bao, Yuzhe Qin, Bailin Wang, Huazhe Xu, Xiaolong Wang* <br>
  arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2310.01361)], [[Code](https://github.com/liruiw/GenSim)]
- **VoxPoser: Composable 3D Value Maps for Robotic Manipulation with Language Models** <br>
  Team: Stanford University, Fei-Fei Li. <br>
  *Wenlong Huang, Chen Wang, Ruohan Zhang, Yunzhu Li, Jiajun Wu, Li Fei-Fei* <br>
  arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2307.05973)], [[Code](https://github.com/huangwl18/VoxPoser)]
- **RVT: Robotic View Transformer for 3D Object Manipulation** <br>
  Team: NVIDIA Labs <br>
  *Ankit Goyal, Jie Xu, Yijie Guo, Valts Blukis, Yu-Wei Chao, Dieter Fox* <br>
  **CoRL (Oral)**, arXiv, 2023.06 [[Paper](https://arxiv.org/abs/2307.05973)], [[Code](https://github.com/nvlabs/rvt)]

## <a name="product"></a> Product
For details, please refer to [Products List](products)

AI Agents Landscape, by Nov 15, 2023  [E2B](https://e2b.dev/blog/will-openai-s-gpts-kill-ai-agents)
<div align="center">
  <img align="center" height="800" src="https://framerusercontent.com/images/XSI5aYgmRt8JSuEYsajAUPzVCs.png">
</div>

- `R&D` **XAgent** <br>
  Team: OpenBMB; NLP, Tsinghua University <br>
  [[Code](https://github.com/OpenBMB/XAgent)] ![](https://img.shields.io/github/stars/OpenBMB/XAgent?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/OpenBMB/XAgent?style=round-square&logo=Github&logoColor=white)
- `R&D` **AIWaves Agents** <br>
  [[Code](https://github.com/aiwaves-cn/agents)] ![](https://img.shields.io/github/stars/aiwaves-cn/agents?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/aiwaves-cn/agents?style=round-square&logo=Github&logoColor=white)
- `R&D` **CoALA** `Code Not Released`<br>
  [[Code](https://github.com/ysymyth/awesome-language-agents)] ![](https://img.shields.io/github/stars/ysymyth/awesome-language-agents?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/ysymyth/awesome-language-agents?style=round-square&logo=Github&logoColor=white)
- `R&D` **AgentVerse** <br>
  Team: OpenBMB <br>
  [[Code](https://github.com/OpenBMB/AgentVerse)] ![](https://img.shields.io/github/stars/OpenBMB/AgentVerse?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/OpenBMB/AgentVerse?style=round-square&logo=Github&logoColor=white)
  
- `R&D` **ChatDev** <br>
  [[Code](https://github.com/OpenBMB/ChatDev)] ![](https://img.shields.io/github/stars/OpenBMB/ChatDev?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/OpenBMB/ChatDev?style=round-square&logo=Github&logoColor=white)
- `R&D` **GPT Researcher** <br>
  [[Code](https://github.com/assafelovic/gpt-researcher)] ![](https://img.shields.io/github/stars/assafelovic/gpt-researcher?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/assafelovic/gpt-researcher?style=round-square&logo=Github&logoColor=white)
- `R&D` **Lagent** <br>
  [[Code](https://github.com/InternLM/lagent)] ![](https://img.shields.io/github/stars/InternLM/lagent?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/InternLM/lagent?style=round-square&logo=Github&logoColor=white)
- `R&D` **AgentSims** <br>
  [[Code](https://github.com/py499372727/AgentSims)] ![](https://img.shields.io/github/stars/py499372727/AgentSims?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/py499372727/AgentSims?style=round-square&logo=Github&logoColor=white)
- `R&D` **AI Town** <br>
  [[Code](https://github.com/a16z-infra/ai-town)] ![](https://img.shields.io/github/stars/a16z-infra/ai-town?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/a16z-infra/ai-town?style=round-square&logo=Github&logoColor=white)
- `R&D`**WebArena** <br>
  [[Code](https://github.com/web-arena-x/webarena)] ![](https://img.shields.io/github/stars/web-arena-x/webarena?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/web-arena-x/webarena?style=round-square&logo=Github&logoColor=white)
- `R&D` **Generative Agents** <br>
  [[Code](https://github.com/joonspk-research/generative_agents)] ![](https://img.shields.io/github/stars/joonspk-research/generative_agents?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/joonspk-research/generative_agents?style=round-square&logo=Github&logoColor=white)
- `R&D`**MetaGPT** <br>
  [[Code](https://github.com/geekan/MetaGPT)] ![](https://img.shields.io/github/stars/geekan/MetaGPT?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/geekan/MetaGPT?style=round-square&logo=Github&logoColor=white)
- `R&D` **Auto-GPT** <br>
  [[Code](https://github.com/Significant-Gravitas/Auto-GPT)] ![](https://img.shields.io/github/stars/Significant-Gravitas/Auto-GPT?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/Significant-Gravitas/Auto-GPT?style=round-square&logo=Github&logoColor=white)
- `R&D` **Langchain** <br>
  [[Code](https://github.com/hwchase17/langchain)] ![](https://img.shields.io/github/stars/hwchase17/langchain?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/hwchase17/langchain?style=round-square&logo=Github&logoColor=white)
- `R&D` **BabyAG** <br>
  [[Code](https://github.com/yoheinakajima/babyagi)] ![](https://img.shields.io/github/stars/yoheinakajima/babyagi?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/yoheinakajima/babyagi?style=round-square&logo=Github&logoColor=white)
- `Business` **AutoGen** <br>
  Team: Microsoft <br>
  [[Site](https://microsoft.github.io/autogen/)]<br>
  [[Code](https://github.com/microsoft/autogen)] ![](https://img.shields.io/github/stars/microsoft/autogen?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/microsoft/autogen?style=round-square&logo=Github&logoColor=white)
- `Business` **Council** <br>
  [[Code](https://github.com/chain-ml/council)] ![](https://img.shields.io/github/stars/chain-ml/council?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/chain-ml/council?style=round-square&logo=Github&logoColor=white)
- `Business`**SuperAGI** <br>
  [[Code](https://github.com/TransformerOptimus/SuperAGI)] ![](https://img.shields.io/github/stars/TransformerOptimus/SuperAGI?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/TransformerOptimus/SuperAGI?style=round-square&logo=Github&logoColor=white)
- `Business` **AgentGPT** <br>
  [[Code](https://github.com/reworkd/AgentGPT)] ![](https://img.shields.io/github/stars/reworkd/AgentGPT?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/reworkd/AgentGPT?style=round-square&logo=Github&logoColor=white) 
  Allowing user to configure and deploy Autonomous AI agents. Name users' own custom AI and have it embark on any goal imaginable. It will attempt to reach the goal by thinking of tasks to do, executing them, and learning from the results
- `Business` **AI Agent** <br>
  [[Site](https://aiagent.app/)]
  AI Agent is a flexible app that lets user create their own agents, by setting a name with an objective.

## <a name="expert_roles_llm"></a> Expert Roles LLM
### For Coding
- `Based LLaMa 2` [Code Llama](https://about.fb.com/news/2023/08/code-llama-ai-for-coding/) By Meta AI · August 24, 2023

## <a name="tools"></a> Tools
- **TensorRT-LLM**<br>
By NVIDIA
[[Code](https://github.com/NVIDIA/TensorRT-LLM)] ![](https://img.shields.io/github/stars/NVIDIA/TensorRT-LLM?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/NVIDIA/TensorRT-LLM?style=round-square&logo=Github&logoColor=white)
- **llama_ros**<br>
[[Code](https://github.com/mgonzs13/llama_ros)] ![](https://img.shields.io/github/stars/mgonzs13/llama_ros?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/mgonzs13/llama_ros?style=round-square&logo=Github&logoColor=white)
This repository provides a set of ROS 2 packages to integrate llama.cpp into ROS 2. By using the llama_ros packages, you can easily incorporate the powerful optimization capabilities of llama.cpp into your ROS 2 projects.

## <a name="blogs_and_resources"></a> Useful Blogs and Resources 

- [AI领域的agent是什么意思？](https://www.zhihu.com/question/51195225/answer/3097467077) Answered by AI的潜意识 · July 3, 2023
- [What is an AI agent?](https://zapier.com/blog/ai-agent/) By Miguel Rebelo · June 1, 2023
- [框架阅读：langchain精读](https://deepwisdom.feishu.cn/wiki/wikcnhYysy7aaewetJ2sUlZMbeh) by MetaGPT team · May 8, 2023
- [框架速度：SuperAGI](https://deepwisdom.feishu.cn/wiki/RlcCwJENIiC0YNkiu6Dcc9Ornlb) by MetaGPT team · Jun 5, 2023
- [AI革新之路：14篇AI Agents论文，探讨人工智能未来](https://mp.weixin.qq.com/s/apSIgDlU6szfEuKSvvDXGw) by AMiner科技 · Sep 2, 2023
- [AI Agent+to B，下一个入口级平台机会｜甲子光年](https://mp.weixin.qq.com/s/Lwr8CnJ0-Ky2md1j5TfW7w) by 武静静 · Sep 15, 2023
- `Video` [Harrison Chase - Agents Masterclass from LangChain Founder (LLM Bootcamp)](https://www.youtube.com/watch?v=DWUdGhRrv2c) by The Full Stack · May 25, 2023  - Harrison Chase （LangChain CEO）25分钟关于GPT Agents的tutorial 


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
