# Awesome-Robotics-Learning [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
> Areas covered in this repo:
> `Robotics`, `AI Agents`, `Autonomous Agents`, `Multi-agents`, `LLM`

## Table of Content

* [About Autonomous Agents](#about)
* [Autonomous Agents Papers](#autonomous_agents_papers)
  * [LLM-Based Autonomous Agents](#llm_based_auto_agents)
  * [Traditional Autonomous Agents](#traditional_auto_agents)
  * [LLM-based Swarm Intelligence](#llm_based_swarm_intelligence)
  * [Consciousness](#consciousness)
  * [Dataset/Benchmark/Simulator/Tool](#ben_sim_tool)
  * [Survey](#agent_survey)
* [Robotics Papers](#robotics_papers)
  * [Data/Simulation Argument](#robo_data_sim_argu)
  * [Manipulation](#robo_manipulation)
  * [Navigation](#robo_navigation)
  * [Planning](#robo_planning)
  * [Task Adaptation](#robo_task_adapt)
  * [Dataset/Benchmark/Simulator/Tool](#robo_ben_sim_tool)
  * [Foundation Model](#foundation_model)
  * [Survey](#robo_survey)
  * [Foundation Model](#foundation_model)
* [Product](#product)
* [Expert Roles LLM](#expert_roles_llm)
* [Tools](#tools)
* [Useful Blogs and Resources ](#blogs_and_resources)

## <a name="autonomous_agents_papers"></a> Autonomous Agents Papers

For details please refer to [Papers List](papers/Agents.md)

### <a name="llm_based_auto_agents"></a> LLM-Based Autonomous Agents
- **LLM Agent Operating System** `Agents OS` <br>
  *Kai Mei, Zelong Li, Shuyuan Xu, et al., Yongfeng Zhang* <br>
  arXiv, 2024.03 [[Paper](https://arxiv.org/abs/2403.16971)], [[PDF](https://arxiv.org/pdf/2403.16971.pdf)], [[Code](https://github.com/agiresearch/AIOS)] <br>
- **Learning to Use Tools via Cooperative and Interactive Agents** <br>
  *Zhengliang Shi, Shen Gao, Xiuyi Chen, et al., Zhaochun Ren* <br>
  arXiv, 2024.03 [[Paper](https://arxiv.org/abs/2403.03031)], [[PDF](https://arxiv.org/pdf/2403.03031.pdf)] <br>
- **LoTa-Bench: Benchmarking Language-oriented Task Planners for Embodied Agents** `Embodied Agents` <br>
  *Jae-Woo Choi, Youngwoo Yoon, Hyobin Ong, Jaehong Kim, Minsu Jang* <br>
  ICLR'24, arXiv, 2024.02 [[Paper](https://arxiv.org/abs/2402.08178)], [[PDF](https://arxiv.org/pdf/2402.08178.pdf)], [[Code](https://github.com/lbaa2022/LLMTaskPlanning)], [[Home Page](https://choi-jaewoo.github.io/LoTa-Bench/)] <br>
- **AgentTuning: Enabling Generalized Agent Abilities for LLMs** <br>
  *Aohan Zeng, Mingdao Liu, Rui Lu, et al., Jie Tang* <br>
  arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2310.12823)], [[Code](https://github.com/THUDM/AgentTuning)] <br>
- **MusicAgent: An AI Agent for Music Understanding and Generation with Large Language Models** <br>
  *Dingyao Yu, Kaitao Song, Peiling Lu, et al., Jiang Bian* <br>
  Team: Microsoft <br>
  arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2310.11954)], [[Code](https://github.com/microsoft/muzic)] <br>
- **Language Agent Tree Search Unifies Reasoning Acting and Planning in Language Models** <br>
  *Andy Zhou, Kai Yan, Michal Shlapentokh-Rothman, Haohan Wang, Yu-Xiong Wang* <br>
  arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2310.04406)], [[Code](https://github.com/andyz245/LanguageAgentTreeSearch)] <br>
- **SmartPlay : A Benchmark for LLMs as Intelligent Agents** <br>
  *Yue Wu, Xuan Tang, Tom M. Mitchell, Yuanzhi Li* <br>
  Team: Microsoft <br>
  arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2310.01557)], [[Code](https://github.com/microsoft/SmartPlay)] <br>
- **A Survey on Large Language Model based Autonomous Agents** <br>
  *Lei Wang, Chen Ma, Xueyang Feng, et al., Ji-Rong Wen* <br>
  arXiv, 2023.08 [[Paper](https://arxiv.org/abs/2308.11432)], [[Code](https://github.com/Paitesanshi/LLM-Agent-Survey)] <br>
- **AgentSims: An Open-Source Sandbox for Large Language Model Evaluation** <br>
  *Jiaju Lin, Haoran Zhao, Aochi Zhang, et al., Qin Chen* <br>
  arXiv, 2023.08. [[Paper](https://arxiv.org/abs/2308.04026)], [[Code](https://github.com/py499372727/AgentSims)] <br>
- **MetaGPT: Meta Programming for Multi-Agent Collaborative Framework** <br>
  *Sirui Hong, Xiawu Zheng, Jonathan Chen, et al., Chenglin Wu* <br>
  arXiv, 2023.08. [[Paper](https://arxiv.org/abs/2308.00352)], [[Code](https://github.com/geekan/MetaGPT)] <br>
- **WebArena: A Realistic Web Environment for Building Autonomous Agents** <br>
  *Shuyan Zhou, Frank F. Xu, Hao Zhu, et al., Graham Neubig* <br>
  arXiv, 2023.07. [[Paper](https://arxiv.org/abs/2307.13854)], [[Code](https://github.com/web-arena-x/webarena)] <br>
- **Unleashing Cognitive Synergy in Large Language Models: A Task-Solving Agent through Multi-Persona Self-Collaboration** <br>
  *Zhenhailong Wang, Shaoguang Mao, Wenshan Wu, et al., Heng Ji* <br>
  arXiv, 2023.07. [[Paper](https://arxiv.org/pdf/2307.05300)], [[Code](https://github.com/MikeWangWZHL/Solo-Performance-Prompting)] <br>
- **Minimum Levels of Interpretability for Artificial Moral Agents** <br>
  *Avish Vijayaraghavan, Cosmin Badea* <br>
  arXiv, 2023.07. [[Paper](https://arxiv.org/pdf/2307.00660)]  <br>
- **Reflexion: Language Agents with Verbal Reinforcement Learning** <br>
  *Noah Shinn, Federico Cassano, Edward Berman, et al., Shunyu Yao* <br>
  NeurIPS'23, arXiv, 2023.05. [[Paper](https://arxiv.org/abs/2303.11366)], [[PDF](https://arxiv.org/pdf/2303.11366.pdf)], [[Code](https://github.com/noahshinn/reflexion)] <br>
- **Decision-Oriented Dialogue for Human-AI Collaboration** <br>
  *Jessy Lin, Nicholas Tomlin, Jacob Andreas, Jason Eisner* <br>
  arXiv, 2023.05. [[Paper](https://arxiv.org/pdf/2305.20076)], [[Code](https://github.com/jlin816/dialop)] <br>
- **HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in Hugging Face** <br>
  *Yongliang Shen, Kaitao Song, Xu Tan, et al., Yueting Zhuang* <br>
  arXiv, 2023.05. [[Paper](https://arxiv.org/abs/2303.17580)] <br>
- **Interactive Natural Language Processing** <br>
  *Zekun Wang, Ge Zhang, Kexin Yang, et al., Jie Fu* <br>
  arXiv, 2023.05. [[Paper](https://arxiv.org/abs/2305.13246)] <br>
- **Introspective Tips: Large Language Model for In-Context Decision Making** <br>
  *Liting Chen, Lu Wang, Hang Dong, et al., Dongmei Zhang* <br>
  arXiv, 2023.05. [[Paper](https://arxiv.org/pdf/2305.11598)] <br>
- **ExpeL: LLM Agents Are Experiential Learners** <br>
  *Andrew Zhao, Daniel Huang, Quentin Xu, et al., Gao Huang* <br>
  arXiv, 2023.08. [[Paper](https://arxiv.org/abs/2308.10144)] <br>
- **Communicative Agents for Software Development** <br>
  *Chen Qian, Xin Cong, Wei Liu, et al., Maosong Sun* <br>
  arXiv, 2023.07 [[Paper](https://arxiv.org/abs/2307.07924)] <br>
- **Cognitive Architectures for Language Agents** <br>
  *Theodore Sumers, Shunyu Yao, Karthik Narasimhan, Thomas L. Griffiths* <br>
  arXiv, 2023.09 [[Paper](https://arxiv.org/abs/2309.02427)] <br>
- **AgentVerse: Facilitating Multi-Agent Collaboration and Exploring Emergent Behaviors in Agents** <br>
  *Weize Chen, Yusheng Su, Jingwei Zuo, et al., Jie Zhou* <br>
  arXiv, 2023.08 [[Paper](https://arxiv.org/abs/2308.10848)] <br>
- **Agents: An Open-source Framework for Autonomous Language Agents** <br>
  *Wangchunshu Zhou, Yuchen Eleanor Jiang, Long Li, et al., Mrinmaya Sachan* <br>
  arXiv, 2023.08 [[Paper](https://arxiv.org/abs/2309.07870)] <br>
- **The Rise and Potential of Large Language Model Based Agents: A Survey** <br>
  *Zhiheng Xi, Wenxiang Chen, Xin Guo, et al., Tao Gui* <br>
  Team: NLP group, Fudan University <br>
  arXiv, 2023.08 [[Paper](https://arxiv.org/abs/2309.07864)], [[Code](https://github.com/WooooDyy/LLM-Agent-Paper-List)] <br>


### <a name="traditional_auto_agents"></a> Traditional Autonomous Agents

1. [[IJCAI’22]](https://www.ijcai.org/proceedings/2022/0344.pdf) **Forming Effective Human-AI Teams: Building Machine Learning Models that Complement the Capabilities of Multiple Experts**
2. [[EMNLP’21]](https://aclanthology.org/2021.emnlp-main.85.pdf) **MindCraft: Theory of Mind Modeling for Situated Dialogue in Collaborative Tasks**
3. [[arXiv 2017.03]](https://arxiv.org/pdf/1704.00717) **It Takes Two to Tango: Towards Theory of AI's Mind**
4. [[arXiv 2021.03]](https://arxiv.org/pdf/2103.09990) **Human-AI Symbiosis: A Survey of Current Approaches**
5. [[arXiv 2023.08]](https://arxiv.org/abs/2308.08155) **AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation Framework**

### <a name="llm_based_swarm_intelligence"></a> LLM-based Swarm Intelligence 
- **Exploring Large Language Models for Communication Games: An Empirical Study on Werewolf** <br>
  *Yuzhuang Xu, Shuo Wang, Peng Li, et al., Yang Liu* <br>
  arXiv, 2023.09 [[Paper](https://arxiv.org/abs/2309.04658)] 

### <a name="consciousness"></a> Consciousness
- **It Takes Two to Tango: Towards Theory of AI's Mind** <br>
  *Patrick Butlin, Robert Long, Eric Elmoznino, et al., Rufin VanRullen* <br>
  arXiv, 2023.08. [[Paper](https://arxiv.org/abs/2308.08708)] 

### <a name="ben_sim_tool"></a> Dataset/Benchmark/Simulator/Tool
- **Towards better Human-Agent Alignment: Assessing Task Utility in LLM-Powered Applications** <br>
  *Negar Arabzadeh, Julia Kiseleva, Qingyun Wu, et al., Charles Clarke* <br>
  Team: Univerity of Waterloo, Microsoft <br>
  arXiv, 2024.02 [[Paper](https://arxiv.org/abs/2402.09015)], [[PDF](https://arxiv.org/pdf/2310.17274.pdf)], [[Code (Notebook)](https://github.com/microsoft/autogen/blob/main/notebook/agenteval_cq_math.ipynb)]  <br>

### <a name="foundation_model"></a> Foundation Model
- **An Interactive Agent Foundation Model** <br>
  *Zane Durante, Bidipta Sarkar, Ran Gong, et al., Qiuyuan Huang* <br>
  Team: Stanford University Fei-Fei Li, Microsoft <br>
  arXiv, 2024.02 [[Paper](https://arxiv.org/abs/2402.05929)], [[PDF](https://arxiv.org/pdf/2402.05929.pdf)], [[Home Page](https://agentfoundationmodel.github.io/)] <br>

### <a name="agent_survey"></a> Survey
- **The Rise and Potential of Large Language Model Based Agents: A Survey** <br>
  *Zhiheng Xi, Wenxiang Chen, Xin Guo, et al., Tao Gui* <br>
  Team: Fudan University <br>
  arXiv, 2023.09 [[Paper](https://arxiv.org/abs/2309.07864)], [[PDF](https://arxiv.org/pdf/2309.07864.pdf)], [[Paper List](https://github.com/WooooDyy/LLM-Agent-Paper-List)] <br>





## <a name="robotics_papers"></a> Robotics Papers
For details please refer to [Papers List](papers/Robotics.md)

### <a name="robo_data_sim_argu"></a> Data/Simulation Argument
- **cuRobo: Parallelized Collision-Free Minimum-Jerk Robot Motion Generation** <br>
  *Balakumar Sundaralingam, Siva Kumar Sastry Hari, Adam Fishman, Caelan Garrett, et al., Dieter Fox* <br>
  Team: NVlabs NVIDIA <br>
  arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2310.17274)], [[PDF](https://arxiv.org/pdf/2310.17274.pdf)], [[Code](https://github.com/NVlabs/curobo)]  <br>
- **GenSim: Generating Robotic Simulation Tasks via Large Language Models** <br>
  *Lirui Wang, Yiyang Ling, Zhecheng Yuan, et al., Xiaolong Wang* <br>
  arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2310.01361)], [[Code](https://github.com/liruiw/GenSim)]  <br>
- **RoboGen: Towards Unleashing Infinite Data for Automated Robot Learning via Generative Simulation** <br>
  *Yufei Wang, Zhou Xian, Feng Chen, et al., Chuang Gan* <br>
  arXiv, 2023.11 [[Paper](https://arxiv.org/abs/2311.01455)], [[Code](https://github.com/Genesis-Embodied-AI/RoboGen)]  <br>
### <a name="robo_manipulation"></a> Manipulation
- **Embodied AI with Two Arms: Zero-shot Learning, Safety and Modularity** `Safty` <br>
  Team: Google Deep Mind Robotics, UNC Chapel Hill. <br>
  *Jake Varley, Sumeet Singh, Deepali Jain, et al., Vikas Sindhwani* <br>
  arXiv, 2024.04 [[Paper](https://arxiv.org/abs/2404.03570)], [[PDF](https://arxiv.org/pdf/2404.03570.pdf)]  <br>
- **Robo-ABC: Affordance Generalization Beyond Categories via Semantic Correspondence for Robot Manipulation** `Grasp` <br>
  *Yuanchen Ju, Kaizhe Hu, Guowei Zhang, et al., Huazhe Xu* <br>
  arXiv, 2024.01 [[Paper](https://arxiv.org/abs/2401.07487)], [[PDF](https://arxiv.org/pdf/2401.07487.pdf)], [[Code (TBD)](https://github.com/TEA-Lab/Robo-ABC)], [[Home Page](https://tea-lab.github.io/Robo-ABC/)]  <br>
- **Visual Robotic Manipulation with Depth-Aware Pretraining** <br>
  *Wanying Wang, Jinming Li, Yichen Zhu, et al., Jian Tang* <br>
  arXiv, 2024.01 [[Paper](https://arxiv.org/abs/2401.09038)], [[PDF](https://arxiv.org/pdf/2401.09038.pdf)]  <br>
- **ManipLLM: Embodied Multimodal Large Language Model for Object-Centric Robotic Manipulation** <br>
  *Xiaoqi Li, Mingxu Zhang, Yiran Geng, et al., Hao Dong* <br>
  arXiv, 2023.11 [[Paper](https://arxiv.org/abs/2312.16217)], [[PDF](https://arxiv.org/pdf/2312.16217.pdf)], [[Home Page](https://sites.google.com/view/manipllm)]  <br>
- **M2T2: Multi-Task Masked Transformer for Object-centric Pick and Place** `Grasp` <br>
  *Wentao Yuan, Adithyavairavan Murali, Arsalan Mousavian, Dieter Fox* <br>
  CoRL'23, arXiv, 2023.12 [[Paper](https://arxiv.org/abs/2311.00926)], [[PDF](https://arxiv.org/pdf/2311.00926.pdf)], [[Code](https://github.com/NVlabs/M2T2)], [[Home Page](https://m2-t2.github.io/)]  <br>
- **Make a Donut: Language-Guided Hierarchical EMD-Space Planning for Zero-shot Deformable Object Manipulation** <br>
  *Yang You, Bokui Shen, Congyue Deng, et al., Leonidas Guibas* <br>
  arXiv, 2023.11 [[Paper](https://arxiv.org/abs/2311.02787)], [[PDF](https://arxiv.org/pdf/2311.02787.pdf)]  <br>
- **D3Fields: Dynamic 3D Descriptor Fields for Zero-Shot Generalizable Robotic Manipulation** `Multimodal` <br>
  Team: UIUC, Stanford University, Fei-Fei Li. <br>
  *Yixuan Wang, Zhuoran Li, Mingtong Zhang, et al., Li Fei-Fei, Yunzhu Li* <br>
  CoRL'23, arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2309.16118)], [[PDF](https://arxiv.org/pdf/2309.16118.pdf)], [[Code](https://github.com/WangYixuan12/d3fields)], [[Home Page](https://robopil.github.io/d3fields/)], [[Demo](https://www.youtube.com/watch?v=yNkIOwAO3GA)]  <br>
- **Gen2Sim: Scaling up Robot Learning in Simulation with Generative Models** <br>
  *Pushkal Katara, Zhou Xian, Katerina Fragkiadaki* <br>
  arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2310.18308)], [[PDF](https://arxiv.org/pdf/2310.18308.pdf)], [[Code](https://github.com/pushkalkatara/Gen2Sim)], [[Home Page](https://gen2sim.github.io/)]  <br>
- **How to Prompt Your Robot: A PromptBook for Manipulation Skills with Code as Policies** `Prompt Engineering` <br>
  Team: Google. <br>
  *Montserrat Gonzalez Arenas, Ted Xiao, Sumeet Singh, et al., Andy Zeng* <br>
  CoRL'23 workshop, 2023.10 [[Paper](https://openreview.net/forum?id=1aRNtmy5zX)], [[PDF](https://openreview.net/pdf?id=1aRNtmy5zX)] <br>
- **RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control** `Multimodal` `Robotic Control` `VLA` <br>
  Team: Google DeepMind <br>
  *Anthony Brohan, Noah Brown, Justice Carbajal, et al., Brianna Zitkovich* <br>
  arXiv, 2023.07 [[Paper](https://arxiv.org/abs/2307.15818)], [[PDF](https://arxiv.org/pdf/2307.15818.pdf)], [[Home Page](https://robotics-transformer2.github.io/)]  <br>
- **RVT: Robotic View Transformer for 3D Object Manipulation** `Grasp` <br>
  Team: NVIDIA Labs <br>
  *Ankit Goyal, Jie Xu, Yijie Guo, et al., Dieter Fox* <br>
  **CoRL'23 (Oral)**, arXiv, 2023.06 [[Paper](https://arxiv.org/abs/2306.14896)], [[PDF](https://arxiv.org/pdf/2306.14896.pdf)], [[Code](https://github.com/nvlabs/rvt)], [[Home Page](https://robotic-view-transformer.github.io/)], [[Demo](https://www.youtube.com/watch?v=mIQN4f3KSA8)]  <br>
- **Distilled Feature Fields Enable Few-Shot Language-Guided Manipulation** `Grasp` <br>
  Team: MIT CSAIL <br>
  *William Shen, Ge Yang, Alan Yu, et al., Phillip Isola* <br>
  **CoRL'23 (Best Paper)**, arXiv, 2023.06 [[Paper](https://arxiv.org/abs/2308.07931)], [[PDF](https://arxiv.org/abs/2308.07931)], [[Code](https://github.com/f3rm/f3rm)], [[Home Page](https://f3rm.github.io/)], [[Demo](https://f3rm.github.io/#video)]  <br>
- **RT-1: Robotics Transformer for Real-World Control at Scale** `Multimodal` `Robotic Control` <br>
  Team: Robotics at Google, Everyday Robotics <br>
  *Anthony Brohan, Noah Brown, Justice Carbajal, et al., Brianna Zitkovich* <br>
  arXiv, 2022.12 [[Paper](https://arxiv.org/abs/2212.06817)], [[PDF](https://arxiv.org/pdf/2212.06817.pdf)], [[Code](https://github.com/google-research/robotics_transformer)], [[Home Page](https://robotics-transformer1.github.io/)], [[Demo](https://www.youtube.com/watch?v=UuKAp9a6wMs)]  <br>
- **Predicting Stable Configurations for Semantic Placement of Novel Objects** `Grasp` <br>
  Team: NVIDIA. <br>
  *Chris Paxton, Chris Xie, Tucker Hermans, Dieter Fox* <br>
  CoRL'22, arXiv, 2021.08 [[Paper](https://arxiv.org/abs/2108.12062)], [[PDF](https://arxiv.org/pdf/2108.12062.pdf)] <br>
### <a name="robo_navigation"></a> Navigation
- **MapGPT: Map-Guided Prompting for Unified Vision-and-Language Navigation** <br>
  *Jiaqi Chen, Bingqian Lin, Ran Xu, et al., Kwan-Yee K. Wong* <br>
  arXiv, 2024.01 [[Paper](https://arxiv.org/abs/2401.07314)], [[PDF](https://arxiv.org/pdf/2401.07314.pdf)]  <br>
- **Visual Language Maps for Robot Navigation** <br>
  *Chenguang Huang, Oier Mees, Andy Zeng, Wolfram Burgard* <br>
  ICRA'23, arXiv, 2022.10 [[Paper](https://arxiv.org/abs/2210.05714)], [[PDF](https://arxiv.org/pdf/2210.05714.pdf)], [[Code](https://arxiv.org/pdf/2308.07931.pdf)], [[Home Page](https://vlmaps.github.io/)]  <br>
### <a name="robo_planning"></a> Planning
- **DexCap: Scalable and Portable Mocap Data Collection System for Dexterous Manipulation** `Motion Planning` <br>
  Team: Fei-Fei Li, Stanford University. <br>
  *Chen Wang, Haochen Shi, Weizhuo Wang, Ruohan Zhang, Li Fei-Fei, C. Karen Liu* <br>
  arXiv, 2024.03 [[Paper](https://arxiv.org/abs/2403.07788)], [[PDF](https://arxiv.org/pdf/2403.07788.pdf)], [[Code](https://github.com/j96w/DexCap)], [[Home Page](https://dex-cap.github.io/)], [[Demo](https://dex-cap.github.io/)]  <br>
- **RT-H: Action Hierarchies Using Language** `Task Planning` <br>
  Team: Google DeepMind, Stanford University. <br>
  *Suneel Belkhale, Tianli Ding, Ted Xiao, et al., Dorsa Sadigh* <br>
  arXiv, 2024.03 [[Paper](https://arxiv.org/abs/2403.01823)], [[PDF](https://arxiv.org/pdf/2403.01823.pdf)], [[Home Page](https://rt-hierarchy.github.io/)], [[Demo](https://rt-hierarchy.github.io/)]  <br>
- **RePLan: Robotic Replanning with Perception and Language Models** `Motion Planning`,`Multimodal` <br>
  *Marta Skreta, Zihan Zhou, Jia Lin Yuan, et al., Animesh Garg* <br>
  arXiv, 2024.01 [[Paper](https://arxiv.org/abs/2401.04157)], [[PDF](https://arxiv.org/pdf/2401.04157.pdf)], [[Home Page](https://replan-lm.github.io/replan.github.io/)], [[Demo](https://youtu.be/mgqR-vLsH0E)]  <br>
- **Human Demonstrations are Generalizable Knowledge for Robots** `Task Planning`, `Human Demo` <br>
  *Guangyan Chen, Te Cui, Tianxing Zhou, et al., Yufeng Yue* <br>
  arXiv, 2023.12 [[Paper](https://arxiv.org/abs/2312.02419)], [[PDF](https://arxiv.org/pdf/2312.02419.pdf)]  <br>
- **Look Before You Leap: Unveiling the Power of GPT-4V in Robotic Vision-Language Planning** `Motion Planning`<br>
  Team: Tsinghua University. <br>
  *Yingdong Hu, Fanqi Lin, Tong Zhang, Li Yi, Yang Gao* <br>
  arXiv, 2023.11 [[Paper](https://arxiv.org/abs/2311.17842)], [[PDF](https://arxiv.org/pdf/2311.17842.pdf)], [[Home Page](https://robot-vila.github.io/)], [[Demo](https://www.youtube.com/watch?v=t8pPZ46xtuc)]  <br>
- **GPT-4V(ision) for Robotics: Multimodal Task Planning from Human Demonstration** `Task Planning`, `Human Demo`<br>
  Team: Microsoft. <br>
  *Naoki Wake, Atsushi Kanehira, Kazuhiro Sasabuchi, Jun Takamatsu, Katsushi Ikeuchi* <br>
  arXiv, 2023.11 [[Paper](https://arxiv.org/abs/2311.12015)], [[PDF](https://arxiv.org/pdf/2311.12015.pdf)], [[Code](https://github.com/microsoft/ChatGPT-Robot-Manipulation-Prompts)], [[Home Page](https://microsoft.github.io/GPT4Vision-Robot-Manipulation-Prompts/)]  <br>
- **VoxPoser: Composable 3D Value Maps for Robotic Manipulation with Language Models** `Motion Planning`, `Multimodal`, `PoT` <br>
  Team: Stanford University, Fei-Fei Li. <br>
  *Wenlong Huang, Chen Wang, Ruohan Zhang, et al., Li Fei-Fei* <br>
  **CoRL'23(Oral)**, arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2307.05973)], [[PDF](https://arxiv.org/pdf/2307.05973.pdf)], [[Code](https://github.com/huangwl18/VoxPoser)], [[Home Page](https://voxposer.github.io/)], [[Demo](https://www.youtube.com/watch?v=Yvn4eR05A3M)]   <br>
- **Vision-Language Models are Zero-Shot Reward Models for Reinforcement Learning** `Reward Desgin`, `Multimodal` <br>
  *Juan Rocamonde, Victoriano Montesinos, Elvis Nava, Ethan Perez, David Lindner* <br>
  NeurIPS'23 workshop, arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2310.12921)], [[PDF](https://arxiv.org/pdf/2310.12921.pdf)], [[Code](https://github.com/AlignmentResearch/vlmrm)], [[Home Page](https://sites.google.com/view/vlm-rm)]<br>
- **Learning Reward for Physical Skills using Large Language Model** `Reward Desgin` <br>
  *Yuwei Zeng, Yiqing Xu* <br>
  CoRL'23 workshop, arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2310.14092)], [[PDF](https://arxiv.org/pdf/2310.14092.pdf)] <br>
- **Eureka: Human-Level Reward Design via Coding Large Language Models** `Reward Desgin` <br>
  Team: NVIDIA, UPenn. <br>
  *Yecheng Jason Ma, William Liang, Guanzhi Wang, et al., Anima Anandkumar* <br>
  arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2310.12931)], [[PDF](https://arxiv.org/pdf/2310.12931.pdf)], [[Code](https://github.com/eureka-research/Eureka)], [[Home Page](https://eureka-research.github.io/)] <br>
- **RoboCLIP: One Demonstration is Enough to Learn Robot Policies** `Learning From Demo` <br>
  Team: UC Berkeley, Stanford University, Google  <br>
  *Sumedh A Sontakke, Jesse Zhang, Sébastien M. R. Arnold, et al., Laurent Itti* <br>
  NeurIPS'23, arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2310.07899)], [[PDF](https://arxiv.org/pdf/2310.07899.pdf)], [[Code](https://github.com/sumedh7/RoboCLIP/tree/main)], [[Home Page](https://sites.google.com/view/roboclip/home)], [[Demo](https://youtu.be/NEWQsSAON7I)] <br>
- **Text2Reward: Automated Dense Reward Function Generation for Reinforcement Learning** `Reward Desgin` <br>
  *Tianbao Xie, Siheng Zhao, Chen Henry Wu, et al., Tao Yu* <br>
  arXiv, 2023.09 [[Paper](https://arxiv.org/abs/2309.11489)], [[PDF](https://arxiv.org/pdf/2309.11489.pdf)], [[Code](https://github.com/xlang-ai/text2reward)], [[Home Page](https://text-to-reward.github.io/)]  <br>
- **ConceptGraphs: Open-Vocabulary 3D Scene Graphs for Perception and Planning** <br>
  *Qiao Gu, Alihusein Kuwajerwala, Sacha Morin, et al., Liam Paull* <br>
  CoRL'23 workshop, arXiv, 2023.09 [[Paper](https://arxiv.org/abs/2309.16650)], [[PDF](https://arxiv.org/pdf/2309.16650.pdf)], [[Code](https://github.com/HybridRobotics/prompt2walk)], [[Home Page](https://prompt2walk.github.io/)]  <br>
- **Prompt a Robot to Walk with Large Language Models** <br>
  *Yen-Jen Wang, Bike Zhang, Jianyu Chen, Koushil Sreenath* <br>
  arXiv, 2023.09 [[Paper](https://arxiv.org/abs/2309.09969)], [[PDF](https://arxiv.org/pdf/2309.09969.pdf)], [[Code](https://github.com/concept-graphs/concept-graphs)], [[Home Page](https://concept-graphs.github.io/)], [[Demo](https://www.youtube.com/watch?v=mRhNkQwRYnc)]  <br>
- **SayPlan: Grounding Large Language Models using 3D Scene Graphs for Scalable Robot Task Planning** `Task Planning` <br>
  *Krishan Rana, Jesse Haviland, Sourav Garg, et al., Niko Suenderhauf* <br>
  **CoRL'23(Oral)**, arXiv, 2023.07 [[Paper](https://arxiv.org/abs/2307.06135)], [[PDF](https://arxiv.org/pdf/2307.06135.pdf)], [[Home Page](https://sayplan.github.io/)], [[Demo](https://www.youtube.com/watch?v=3aMgpqnD2RY)] <br>
- **Scaling Up and Distilling Down: Language-Guided Robot Skill Acquisition** `Reward Desgin` <br>
  Team: Columbia University, Google Deepmind. <br>
  *Huy Ha, Pete Florence, Shuran Song* <br>
  CoRL'23, arXiv, 2023.07 [[Paper](https://arxiv.org/abs/2307.14535)], [[PDF](https://arxiv.org/pdf/2307.14535.pdf)], [[Code](https://github.com/columbia-ai-robotics/scalingup)], [[Home Page](https://www.cs.columbia.edu/~huy/scalingup/)], [[Demo](https://www.cs.columbia.edu/~huy/scalingup/static/videos/scalingup.mp4)]  <br>
- **LARG, Language-based Automatic Reward and Goal Generation** `Reward Desgin` <br>
  *Julien Perez, Denys Proux, Claude Roux, Michael Niemaz* <br>
  arXiv, 2023.06 [[Paper](https://arxiv.org/abs/2306.10985)], [[PDF](https://arxiv.org/pdf/2306.10985.pdf)] <br>
- **Language to Rewards for Robotic Skill Synthesis** `Reward Desgin` <br>
  Team: Google Deepmind. <br>
  *Wenhao Yu, Nimrod Gileadi, Chuyuan Fu, etal., Fei Xia* <br>
  ICLR'23, arXiv, 2023.06 [[Paper](https://arxiv.org/abs/2306.08647)], [[PDF](https://arxiv.org/pdf/2306.08647.pdf)], [[Code](https://github.com/google-deepmind/language_to_reward_2023)], [[Home Page](https://language-to-reward.github.io/)], [[Demo](https://www.youtube.com/watch?v=7KiKg0rdSSQ)]  <br>
- **PaLM-E: An Embodied Multimodal Language Model** `Task Planning`, `Multimodal` <br>
  Team: Robotics at Google. <br>
  *Danny Driess, Fei Xia, Mehdi S. M. Sajjadi, et al., Pete Florence* <br>
  ICML'23, arXiv, 2023.03 [[Paper](https://arxiv.org/abs/2303.03378)], [[PDF](https://arxiv.org/pdf/2303.03378.pdf)], [[Home Page](https://palm-e.github.io/)] <br>
- **Grounded Decoding: Guiding Text Generation with Grounded Models for Embodied Agents** `Multimodal` <br>
  Team: Stanford University, Robotics at Google. <br>
  *Wenlong Huang, Fei Xia, Dhruv Shah, et al., Brian Ichter* <br>
  arXiv, 2023.03 [[Paper](https://arxiv.org/abs/2303.00855)], [[PDF](https://arxiv.org/pdf/2303.00855.pdf)], [[Home Page](https://grounded-decoding.github.io/)], [[Demo](https://www.youtube.com/watch?v=KHhAlBIQftQ)] <br>
- **Reward Design with Language Models** `Reward Desgin` <br>
  Team: Stanford University, Deepmind. <br>
  *Minae Kwon, Sang Michael Xie, Kalesha Bullard, Dorsa Sadigh* <br>
  ICLR'23, arXiv, 2023.02 [[Paper](https://arxiv.org/abs/2303.00001)], [[PDF](https://arxiv.org/pdf/2303.00001.pdf)], [[Code](https://github.com/minaek/reward_design_with_llms)]<br>
- **Code as Policies: Language Model Programs for Embodied Control** `Task Planning`, `PoT` <br>
  Team: Robotics at Google. <br>
  *Jacky Liang, Wenlong Huang, Fei Xia, et al., Andy Zeng* <br>
  ICRA'23, CoRL openreview, 2022,11 [[Paper](https://ieeexplore.ieee.org/abstract/document/10160591?casa_token=nxmzysLMWckAAAAA:6N46qqpcOV4xMxqnmJUxm6RlX17xaXcK8efi_FiYvjLgvNu_VFy24OGOFQO8vE1-JZAp5xU)], [[PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10160591)], [[Code](https://github.com/google-research/google-research/tree/master/code_as_policies)], [[Home Page](https://code-as-policies.github.io/)] <br>
- **Correcting Robot Plans with Natural Language Feedback** `Motion Planning` <br>
  Team: NVIDIA, MIT. <br>
  *Pratyusha Sharma, Balakumar Sundaralingam, Valts Blukis, et al., Dieter Fox* <br>
  arXiv, 2022.04 [[Paper](https://arxiv.org/abs/2204.05186)], [[PDF](https://arxiv.org/pdf/2204.05186.pdf)] <br>
- **Do As I Can, Not As I Say: Grounding Language in Robotic Affordances** `Task Planning`, `Multimodal` <br>
  Team: Robotics at Google, Everyday Robots. <br>
  *Michael Ahn, Anthony Brohan, Noah Brown, et al., Andy Zeng* <br>
  arXiv, 2022.04 [[Paper](https://arxiv.org/abs/2204.01691)], [[PDF](https://arxiv.org/pdf/2204.01691.pdf)], [[Code](https://github.com/google-research/google-research/tree/master/saycan)], [[Home Page](https://say-can.github.io/)], [[Demo](https://sites.research.google/palm-saycan)] <br>
- **Sequence-of-Constraints MPC: Reactive Timing-Optimal Control of Sequential Manipulation** `Manipulation Planning`<br>
  *Marc Toussaint, Jason Harris, Jung-Su Ha, Danny Driess, Wolfgang Hönig* <br>
  IROS'22, arXiv, 2022.03 [[Paper](https://arxiv.org/abs/2203.05390)], [[PDF](https://arxiv.org/pdf/2203.05390.pdf)]<br>
- **Visually-Grounded Planning without Vision: Language Models Infer Detailed Plans from High-level Instructions** `Language Model Only` <br>
  *Peter A. Jansen* <br>
  EMNLP'20, arXiv, 2020.09 [[Paper](https://arxiv.org/abs/2009.14259)], [[PDF](https://arxiv.org/pdf/2009.14259.pdf)], [[Code](https://github.com/cognitiveailab/alfred-gpt2/)] <br>
### <a name="robo_task_adapt"></a> Task Adaptation
- **Bootstrap Your Own Skills: Learning to Solve New Tasks with Large Language Model Guidance** `Learn New Tasks` <br>
  Team: Robotics at Google, Everyday Robots. <br>
  *Jesse Zhang, Jiahui Zhang, Karl Pertsch, et al., Joseph J. Lim* <br>
  **CoRL'23(Oral)**, arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2310.10021)], [[PDF](https://arxiv.org/pdf/2310.10021.pdf)], [[Code](https://github.com/clvrai/boss)], [[Home Page](https://clvrai.github.io/boss/)] <br>
### <a name="robo_survey"></a> Survey
- **Real-World Robot Applications of Foundation Models: A Review** <br>
  *Kento Kawaharazuka, Tatsuya Matsushima, Andrew Gambardella, et al., Andy Zeng* <br>
  arXiv, 2024.02 [[Paper](https://arxiv.org/abs/2402.05741)], [[PDF](https://arxiv.org/pdf/2402.05741.pdf)]  <br>
- **Large Language Models for Robotics: Opportunities, Challenges, and Perspectives** <br>
  *Jiaqi Wang, Zihao Wu, Yiwei Li, et al., Shu Zhang* <br>
  arXiv, 2024.01 [[Paper](https://arxiv.org/abs/2401.04334)], [[PDF](https://arxiv.org/pdf/2401.04334.pdf)]  <br>
- **Toward General-Purpose Robots via Foundation Models: A Survey and Meta-Analysis** <br>
  *Yafei Hu, Quanting Xie, Vidhi Jain, etal., Yonatan Bisk* <br>
  arXiv, 2023.12 [[Paper](https://arxiv.org/abs/2312.08782)], [[PDF](https://arxiv.org/pdf/2312.08782.pdf)]  <br>
- **Language-conditioned Learning for Robotic Manipulation: A Survey** <br>
  *Hongkuan Zhou, Xiangtong Yao, Yuan Meng, et al., Alois Knoll* <br>
  arXiv, 2023.12 [[Paper](https://arxiv.org/abs/2312.10807)], [[PDF](https://arxiv.org/pdf/2312.10807.pdf)]  <br>
- **Toward General-Purpose Robots via Foundation Models: A Survey and Meta-Analysis** <br>
  *Yafei Hu, Quanting Xie, Vidhi Jain, et al., Yonatan Bisk* <br>
  arXiv, 2023.12 [[Paper](https://arxiv.org/abs/2312.08782)], [[Code](https://github.com/JeffreyYH/robotics-fm-survey)]  <br>
- **Foundation Models in Robotics: Applications, Challenges, and the Future** <br>
  *Roya Firoozi, Johnathan Tucker, Stephen Tian, et al., Mac Schwager* <br>
  arXiv, 2023.12 [[Paper](https://arxiv.org/abs/2312.07843)], [[PDF](https://arxiv.org/pdf/2312.08782.pdf)], [[Code](https://github.com/robotics-survey/Awesome-Robotics-Foundation-Models)]  <br>
- **Robot Learning in the Era of Foundation Models: A Survey** <br>
  *Xuan Xiao, Jiahang Liu, Zhipeng Wang, et al., Shuo Jiang* <br>
  arXiv, 2023.11 [[Paper](https://arxiv.org/abs/2311.14379)], [[PDF](https://arxiv.org/pdf/2311.14379.pdf)]  <br>
- **Recent Advances in Robot Learning from Demonstration** <br>
  *Harish Ravichandar, Athanasios S. Polydoros, Sonia Chernova, Aude Billard <br>
  Annual Review of Control, Robotics, and Autonomous Systems, 2020.05 [[Paper](https://www.annualreviews.org/doi/abs/10.1146/annurev-control-100819-063206)], [[PDF](https://www.annualreviews.org/doi/pdf/10.1146/annurev-control-100819-063206)]  <br>
### <a name="robo_ben_sim_tool"></a> Dataset/Benchmark/Simulator/Tool
- **DROID: A Large-Scale In-The-Wild Robot Manipulation Dataset** `Dataset` <br>
  Team: Stanford University, UC Berkeley, et al. <br>
  *Alexander Khazatsky, Karl Pertsch, Suraj Nair, et al., Chelsea Finn* <br>
  arXiv, 2024.03 [[Paper](https://arxiv.org/abs/2403.12945)], [[PDF](https://arxiv.org/pdf/2403.12945.pdf)], [[Home Page](https://droid-dataset.github.io/)], [[Dataset Visualizer](https://droid-dataset.github.io/visualizer/)], [[Colab Demo](https://colab.research.google.com/drive/1b4PPH4XGht4Jve2xPKMCh-AXXAQziNQa?usp=sharing)]  <br>
- **BEHAVIOR-1K: A Human-Centered, Embodied AI Benchmark with 1,000 Everyday Activities and Realistic Simulation** `Benchmark` <br>
  Team: Stanford University, Fei-fei Li <br>
  *Chengshu Li, Ruohan Zhang, Josiah Wong, et al., Li Fei-Fei* <br>
  CoRL'22 (preliminary version), arXiv, 2024.03 [[Paper](https://arxiv.org/abs/2403.09227)], [[PDF](https://arxiv.org/pdf/2403.09227.pdf)], [[Home Page](https://behavior.stanford.edu/)]  <br>
- **Universal Manipulation Interface: In-The-Wild Robot Teaching Without In-The-Wild Robots** `Data Collection Tool` <br>
  Team: Stanford University <br>
  *Cheng Chi, Zhenjia Xu, Chuer Pan, et al., Shuran Song* <br>
  arXiv, 2024.02 [[Paper](https://arxiv.org/abs/2402.10329)], [[PDF](https://arxiv.org/pdf/2402.10329.pdf)], [[Code](https://github.com/real-stanford/universal_manipulation_interface)], [[Home Page](https://umi-gripper.github.io/)]  <br>
- **Open X-Embodiment: Robotic Learning Datasets and RT-X Models** <br>
  Team: DeepMind <br>
  *Open X-Embodiment Collaboration, et al.* <br>
  arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2310.08864)], [[PDF](https://arxiv.org/pdf/2310.08864.pdf)], [[Code](https://github.com/arnold-benchmark/arnold)], [[Home Page](https://robotics-transformer-x.github.io/)]  <br>
- **ARNOLD: A Benchmark for Language-Grounded Task Learning With Continuous States in Realistic 3D Scenes** <br>
  *Ran Gong, Jiangyong Huang, Yizhou Zhao, et al., Siyuan Huang* <br>
  ICCV'23, 2023.04 [[Paper](https://arxiv.org/abs/2304.04321)], [[PDF](https://arxiv.org/pdf/2304.04321.pdf)], [[Code](https://github.com/google-deepmind/open_x_embodiment)]  <br>
- **RLBench: The Robot Learning Benchmark & Learning Environment** <br>
  Team: NVlabs NVIDIA <br>
  *Stephen James, Zicong Ma, David Rovick Arrojo, Andrew J. Davison* <br>
  IEEE Robotics and Automation Letters, 2019.09 [[Paper](https://arxiv.org/abs/1909.12271)], [[Code](https://github.com/stepjam/RLBench)]  <br>

### <a name="foundation_model"></a> Foundation Model
- **3D-VLA: A 3D Vision-Language-Action Generative World Model** `VLA` <br>
  *Haoyu Zhen, Xiaowen Qiu, Peihao Chen, et al., Chuang Gan* <br>
  arXiv, 2024.03 [[Paper](https://arxiv.org/abs/2403.09631)], [[PDF](https://arxiv.org/pdf/2403.09631.pdf)], [[Code](https://github.com/UMass-Foundation-Model/3D-VLA)], [[Home Page](https://vis-www.cs.umass.edu/3dvla/)]  <br>

  
## <a name="product"></a> Autonomous Agents Product
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

----
## Acknowledgement
- [Awesome-Embodied-AI](https://github.com/haoranD/Awesome-Embodied-AI) by Haoran Duan

## Citation
If you find this repository useful, please consider citing this list:
```
@misc{rui2023roboticsautonomousagentslist,
    title = {Awesome-Robotics-Learning},
    author = {Rui Sun},
    journal = {GitHub repository},
    url = {https://github.com/soraw-ai/Awesome-Robotics-Learning},
    year = {2023},
}
```

## Abbreviations List

| Symbol | Full Name             | Description  |
|--------|-----------------------|---|
| LLM    | Large Language Model  |   |
| VLM    | Vision Language Model |   |
| PoT    |    Program of Thoughts                   |   |


## References
1. [MetaGPT作者深度解析直播回放](https://www.bilibili.com/video/BV1Ru411V7XL)
2. [从生成式AI到合成式AI ，MarTech下一步如何进化](http://news.sohu.com/a/710542412_99984157)by 晓晓 · Aug 10, 2023
