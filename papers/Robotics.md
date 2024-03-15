# Robotics Papers
* [Robotics Papers](#robotics_papers)
  * [Data/Simulation Argument](#robo_data_sim_argu)
  * [Manipulation](#robo_manipulation)
  * [Navigation](#robo_navigation)
  * [Planning](#robo_planning)
  * [Task Adaptation](#robo_task_adapt)
  * [Dataset/Benchmark/Simulator/Tool](#robo_ben_sim_tool)
  * [Survey](#robo_survey)

## <a name="robo_data_sim_argu"></a> Data/Simulation Argument
- **cuRobo: Parallelized Collision-Free Minimum-Jerk Robot Motion Generation** <br>
  *Balakumar Sundaralingam, Siva Kumar Sastry Hari, Adam Fishman, Caelan Garrett, et al., Dieter Fox* <br>
  Team: NVlabs, NVIDIA <br>
  arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2310.17274)], [[PDF](https://arxiv.org/pdf/2310.17274.pdf)] <br>
  [[Code](https://github.com/NVlabs/curobo)] ![](https://img.shields.io/github/stars/NVlabs/curobo?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/NVlabs/curobo?style=round-square&logo=Github&logoColor=white)  <br>
- **GenSim: Generating Robotic Simulation Tasks via Large Language Models** <br>
  *Lirui Wang, Yiyang Ling, Zhecheng Yuan, et al., Xiaolong Wang* <br>
  arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2310.01361)] <br>
  [[Code](https://github.com/liruiw/GenSim)] ![](https://img.shields.io/github/stars/liruiw/GenSim?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/liruiw/GenSim?style=round-square&logo=Github&logoColor=white)  <br>
- **RoboGen: Towards Unleashing Infinite Data for Automated Robot Learning via Generative Simulation** <br>
  *Yufei Wang, Zhou Xian, Feng Chen, et al., Chuang Gan* <br>
  arXiv, 2023.11 [[Paper](https://arxiv.org/abs/2311.01455)] <br>
  [[Code](https://github.com/Genesis-Embodied-AI/RoboGen)] ![](https://img.shields.io/github/stars/Genesis-Embodied-AI/RoboGen?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/Genesis-Embodied-AI/RoboGen?style=round-square&logo=Github&logoColor=white)  <br>
## <a name="robo_manipulation"></a> Manipulation
- **Robo-ABC: Affordance Generalization Beyond Categories via Semantic Correspondence for Robot Manipulation** `Grasp` <br>
  *Yuanchen Ju, Kaizhe Hu, Guowei Zhang, et al., Huazhe Xu* <br>
  arXiv, 2024.01 [[Paper](https://arxiv.org/abs/2401.07487)], [[PDF](https://arxiv.org/pdf/2401.07487.pdf)], [[Home Page](https://tea-lab.github.io/Robo-ABC/)]  <br>
  [[Code (TBD)](https://github.com/TEA-Lab/Robo-ABC)] ![](https://img.shields.io/github/stars/TEA-Lab/Robo-ABC?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/TEA-Lab/Robo-ABC?style=round-square&logo=Github&logoColor=white)  <br>
- **Visual Robotic Manipulation with Depth-Aware Pretraining** <br>
  *Wanying Wang, Jinming Li, Yichen Zhu, et al., Jian Tang* <br>
  arXiv, 2024.01 [[Paper](https://arxiv.org/abs/2401.09038)], [[PDF](https://arxiv.org/pdf/2401.09038.pdf)]  <br>
- **ManipLLM: Embodied Multimodal Large Language Model for Object-Centric Robotic Manipulation** <br>
  *Xiaoqi Li, Mingxu Zhang, Yiran Geng, et al., Hao Dong* <br>
  arXiv, 2023.12 [[Paper](https://arxiv.org/abs/2312.16217)], [[PDF](https://arxiv.org/pdf/2312.16217.pdf)], [[Home Page](https://sites.google.com/view/manipllm)]  <br>
- **M2T2: Multi-Task Masked Transformer for Object-centric Pick and Place** `Grasp` <br>
  *Wentao Yuan, Adithyavairavan Murali, Arsalan Mousavian, Dieter Fox* <br>
  CoRL'23, arXiv, 2023.12 [[Paper](https://arxiv.org/abs/2311.00926)], [[PDF](https://arxiv.org/pdf/2311.00926.pdf)], [[Home Page](https://m2-t2.github.io/)] <br>
  [[Code](https://github.com/NVlabs/M2T2)] ![](https://img.shields.io/github/stars/NVlabs/M2T2?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/NVlabs/M2T2?style=round-square&logo=Github&logoColor=white)  <br>
- **Make a Donut: Language-Guided Hierarchical EMD-Space Planning for Zero-shot Deformable Object Manipulation** <br>
  *Yang You, Bokui Shen, Congyue Deng, et al., Leonidas Guibas* <br>
  arXiv, 2023.11 [[Paper](https://arxiv.org/abs/2311.02787)], [[PDF](https://arxiv.org/pdf/2311.02787.pdf)]  <br>
- **D3Fields: Dynamic 3D Descriptor Fields for Zero-Shot Generalizable Robotic Manipulation** `Multimodal` <br>
  Team: UIUC, Stanford University, Fei-Fei Li. <br>
  *Yixuan Wang, Zhuoran Li, Mingtong Zhang, et al., Li Fei-Fei, Yunzhu Li* <br>
  CoRL'23, arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2309.16118)], [[PDF](https://arxiv.org/pdf/2309.16118.pdf)], [[Home Page](https://robopil.github.io/d3fields/)], [[Demo](https://www.youtube.com/watch?v=yNkIOwAO3GA)]<br>
  [[Code](https://github.com/WangYixuan12/d3fields)] ![](https://img.shields.io/github/stars/WangYixuan12/d3fields?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/WangYixuan12/d3fields?style=round-square&logo=Github&logoColor=white)  <br>
- **Gen2Sim: Scaling up Robot Learning in Simulation with Generative Models** <br>
  *Pushkal Katara, Zhou Xian, Katerina Fragkiadaki* <br>
  arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2310.18308)], [[PDF](https://arxiv.org/pdf/2310.18308.pdf)], [[Home Page](https://gen2sim.github.io/)] <br>
  [[Code](https://github.com/pushkalkatara/Gen2Sim)] ![](https://img.shields.io/github/stars/pushkalkatara/Gen2Sim?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/pushkalkatara/Gen2Sim?style=round-square&logo=Github&logoColor=white)  <br>
- **How to Prompt Your Robot: A PromptBook for Manipulation Skills with Code as Policies** `Prompt Engineering` <br>
  Team: Google. <br>
  *Montserrat Gonzalez Arenas, Ted Xiao, Sumeet Singh, et al., Andy Zeng* <br>
  CoRL'23 workshop, 2023.10 [[Paper](https://openreview.net/forum?id=1aRNtmy5zX)], [[PDF](https://openreview.net/pdf?id=1aRNtmy5zX)] <br>
  - **Blogs**
    - [谷歌机器人研究员教你如何写prompt来完成机器人任务](https://zhuanlan.zhihu.com/p/678734754) By 智园AI-robotics · Jan 19, 2024 
- **RVT: Robotic View Transformer for 3D Object Manipulation** `Grasp` <br>
  Team: NVIDIA Labs <br>
  *Ankit Goyal, Jie Xu, Yijie Guo, et al., Dieter Fox* <br>
  **CoRL (Oral)**, arXiv, 2023.06 [[Paper](https://arxiv.org/abs/2306.14896)], [[PDF](https://arxiv.org/pdf/2306.14896.pdf)], [[Home Page](https://robotic-view-transformer.github.io/)], [[Demo](https://www.youtube.com/watch?v=mIQN4f3KSA8)] <br>
  [[Code](https://github.com/nvlabs/rvt)] ![](https://img.shields.io/github/stars/nvlabs/rvt?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/nvlabs/rvt?style=round-square&logo=Github&logoColor=white)  <br>
- **RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control** `Multimodal` `Robotic Control` `VLA` <br>
  Team: Google DeepMind <br>
  *Anthony Brohan, Noah Brown, Justice Carbajal, et al., Brianna Zitkovich* <br>
  arXiv, 2023.07 [[Paper](https://arxiv.org/abs/2307.15818)], [[PDF](https://arxiv.org/pdf/2307.15818.pdf)], [[Home Page](https://robotics-transformer2.github.io/)]  <br>
- **Distilled Feature Fields Enable Few-Shot Language-Guided Manipulation** `Grasp` <br>
  Team: MIT CSAIL <br>
  *William Shen, Ge Yang, Alan Yu, et al., Phillip Isola* <br>
  **CoRL'23 (Best Paper)**, arXiv, 2023.06 [[Paper](https://arxiv.org/abs/2308.07931)], [[PDF](https://arxiv.org/abs/2308.07931)], [[Home Page](https://f3rm.github.io/)], [[Demo](https://f3rm.github.io/#video)] <br>
  [Code](https://github.com/f3rm/f3rm)] ![](https://img.shields.io/github/stars/f3rm/f3rm?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/f3rm/f3rm?style=round-square&logo=Github&logoColor=white)  <br>
- **RT-1: Robotics Transformer for Real-World Control at Scale** `Multimodal` `Robotic Control` <br>
  Team: Robotics at Google, Everyday Robotics <br>
  *Anthony Brohan, Noah Brown, Justice Carbajal, et al., Brianna Zitkovich* <br>
  arXiv, 2022.12 [[Paper](https://arxiv.org/abs/2212.06817)], [[PDF](https://arxiv.org/pdf/2212.06817.pdf)], [[Home Page](https://robotics-transformer1.github.io/)], [[Demo](https://www.youtube.com/watch?v=UuKAp9a6wMs)]  <br>
  [[Code](https://github.com/google-research/robotics_transformer)] ![](https://img.shields.io/github/stars/google-research/robotics_transformer?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/google-research/robotics_transformer?style=round-square&logo=Github&logoColor=white)  <br>
- **Predicting Stable Configurations for Semantic Placement of Novel Objects** `Grasp` <br>
  Team: NVIDIA. <br>
  *Chris Paxton, Chris Xie, Tucker Hermans, Dieter Fox* <br>
  CoRL'22, arXiv, 2021.08 [[Paper](https://arxiv.org/abs/2108.12062)], [[PDF](https://arxiv.org/pdf/2108.12062.pdf)] <br>
## <a name="robo_navigation"></a> Navigation
- **MapGPT: Map-Guided Prompting for Unified Vision-and-Language Navigation** <br>
  *Jiaqi Chen, Bingqian Lin, Ran Xu, et al., Kwan-Yee K. Wong* <br>
  arXiv, 2024.01 [[Paper](https://arxiv.org/abs/2401.07314)], [[PDF](https://arxiv.org/pdf/2401.07314.pdf)]  <br>
- **Visual Language Maps for Robot Navigation** <br>
  *Chenguang Huang, Oier Mees, Andy Zeng, Wolfram Burgard* <br>
  ICRA'23, arXiv, 2022.10 [[Paper](https://arxiv.org/abs/2210.05714)], [[PDF](https://arxiv.org/pdf/2210.05714.pdf)], [[Home Page](https://vlmaps.github.io/)] <br>
  [[Code](https://colab.research.google.com/drive/1xsH9Gr_O36sBZaoPNq1SmqgOOF12spV0?usp=sharing)]  <br>
## <a name="robo_planning"></a> Planning
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
  arXiv, 2023.11 [[Paper](https://arxiv.org/abs/2311.12015)], [[PDF](https://arxiv.org/pdf/2311.12015.pdf)], [[Home Page](https://microsoft.github.io/GPT4Vision-Robot-Manipulation-Prompts/)]  <br>
  [[Code](https://github.com/microsoft/ChatGPT-Robot-Manipulation-Prompts)] ![](https://img.shields.io/github/stars/microsoft/ChatGPT-Robot-Manipulation-Prompts?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/microsoft/ChatGPT-Robot-Manipulation-Prompts?style=round-square&logo=Github&logoColor=white)  <br>
- **VoxPoser: Composable 3D Value Maps for Robotic Manipulation with Language Models** `Motion Planning`, `Multimodal`, `PoT` <br>
  Team: Stanford University, Fei-Fei Li. <br>
  *Wenlong Huang, Chen Wang, Ruohan Zhang, et al., Li Fei-Fei* <br>
  **CoRL'23(Oral)**, arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2307.05973)], [[PDF](https://arxiv.org/pdf/2307.05973.pdf)], [[Home Page](https://voxposer.github.io/)], [[Demo](https://www.youtube.com/watch?v=Yvn4eR05A3M)]  <br>
  [[Code](https://github.com/huangwl18/VoxPoser)] ![](https://img.shields.io/github/stars/huangwl18/VoxPoser?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/huangwl18/VoxPoser?style=round-square&logo=Github&logoColor=white)  <br>
- **Vision-Language Models are Zero-Shot Reward Models for Reinforcement Learning** `Reward Desgin`, `Multimodal` <br>
  *Juan Rocamonde, Victoriano Montesinos, Elvis Nava, Ethan Perez, David Lindner* <br>
  NeurIPS'23 workshop, arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2310.12921)], [[PDF](https://arxiv.org/pdf/2310.12921.pdf)], [[Home Page](https://sites.google.com/view/vlm-rm)]<br>
  [[Code](https://github.com/AlignmentResearch/vlmrm)] ![](https://img.shields.io/github/stars/AlignmentResearch/vlmrm?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/AlignmentResearch/vlmrm?style=round-square&logo=Github&logoColor=white)  <br>
- **Learning Reward for Physical Skills using Large Language Model** `Reward Desgin` <br>
  *Yuwei Zeng, Yiqing Xu* <br>
  CoRL'23 workshop, arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2310.14092)], [[PDF](https://arxiv.org/pdf/2310.14092.pdf)] <br>
- **Eureka: Human-Level Reward Design via Coding Large Language Models** `Reward Desgin` <br>
  Team: NVIDIA, UPenn. <br>
  *Yecheng Jason Ma, William Liang, Guanzhi Wang, et al., Anima Anandkumar* <br>
  arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2310.12931)], [[PDF](https://arxiv.org/pdf/2310.12931.pdf)], [[Home Page](https://eureka-research.github.io/)]  <br>
  [[Code](https://github.com/eureka-research/Eureka)] ![](https://img.shields.io/github/stars/eureka-research/Eureka?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/eureka-research/Eureka?style=round-square&logo=Github&logoColor=white)  <br>
- **RoboCLIP: One Demonstration is Enough to Learn Robot Policies** `Learning From Demo` <br>
  Team: UC Berkeley, Stanford University, Google  <br>
  *Sumedh A Sontakke, Jesse Zhang, Sébastien M. R. Arnold, et al., Laurent Itti* <br>
  NeurIPS'23, arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2310.07899)], [[PDF](https://arxiv.org/pdf/2310.07899.pdf)], [[Home Page](https://sites.google.com/view/roboclip/home)], [[Demo](https://youtu.be/NEWQsSAON7I)] <br>
  [[Code](https://github.com/sumedh7/RoboCLIP/tree/main)] ![](https://img.shields.io/github/stars/sumedh7/RoboCLIP?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/sumedh7/RoboCLIP?style=round-square&logo=Github&logoColor=white)  <br>
- **ConceptGraphs: Open-Vocabulary 3D Scene Graphs for Perception and Planning** <br>
  *Qiao Gu, Alihusein Kuwajerwala, Sacha Morin, et al., Liam Paull* <br>
  CoRL'23 workshop, arXiv, 2023.09 [[Paper](https://arxiv.org/abs/2309.16650)], [[PDF](https://arxiv.org/pdf/2309.16650.pdf)], [[Code](https://github.com/HybridRobotics/prompt2walk)], [[Home Page](https://prompt2walk.github.io/)]  <br>
- **Text2Reward: Automated Dense Reward Function Generation for Reinforcement Learning** `Reward Desgin` <br>
  *Tianbao Xie, Siheng Zhao, Chen Henry Wu, et al., Tao Yu* <br>
  arXiv, 2023.09 [[Paper](https://arxiv.org/abs/2309.11489)], [[PDF](https://arxiv.org/pdf/2309.11489.pdf)], [[Home Page](https://text-to-reward.github.io/)]  <br>
  [[Code](https://github.com/xlang-ai/text2reward)] ![](https://img.shields.io/github/stars/xlang-ai/text2reward?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/xlang-ai/text2reward?style=round-square&logo=Github&logoColor=white)  <br>
- **Prompt a Robot to Walk with Large Language Models** <br>
  *Yen-Jen Wang, Bike Zhang, Jianyu Chen, Koushil Sreenath* <br>
  arXiv, 2023.09 [[Paper](https://arxiv.org/abs/2309.09969)], [[PDF](https://arxiv.org/pdf/2309.09969.pdf)], [[Home Page](https://prompt2walk.github.io/)] <br>
  [[Code](https://github.com/HybridRobotics/prompt2walk)] ![](https://img.shields.io/github/stars/HybridRobotics/prompt2walk?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/HybridRobotics/prompt2walk?style=round-square&logo=Github&logoColor=white)  <br>
- **SayPlan: Grounding Large Language Models using 3D Scene Graphs for Scalable Robot Task Planning** `Task Planning` <br>
  *Krishan Rana, Jesse Haviland, Sourav Garg, et al., Niko Suenderhauf* <br>
  **CoRL'23(Oral)**, arXiv, 2023.07 [[Paper](https://arxiv.org/abs/2307.06135)], [[PDF](https://arxiv.org/pdf/2307.06135.pdf)], [[Home Page](https://sayplan.github.io/)], [[Demo](https://www.youtube.com/watch?v=3aMgpqnD2RY)] <br>
- **Scaling Up and Distilling Down: Language-Guided Robot Skill Acquisition** `Reward Desgin` <br>
  Team: Columbia University, Google Deepmind. <br>
  *Huy Ha, Pete Florence, Shuran Song* <br>
  CoRL'23, arXiv, 2023.07 [[Paper](https://arxiv.org/abs/2307.14535)], [[PDF](https://arxiv.org/pdf/2307.14535.pdf)], [[Home Page](https://www.cs.columbia.edu/~huy/scalingup/)], [[Demo](https://www.cs.columbia.edu/~huy/scalingup/static/videos/scalingup.mp4)]  <br>
  [[Code](https://github.com/columbia-ai-robotics/scalingup)]  ![](https://img.shields.io/github/stars/columbia-ai-robotics/scalingup?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/columbia-ai-robotics/scalingup?style=round-square&logo=Github&logoColor=white)  <br>
- **LARG, Language-based Automatic Reward and Goal Generation** `Reward Desgin` <br>
  *Julien Perez, Denys Proux, Claude Roux, Michael Niemaz* <br>
  arXiv, 2023.06 [[Paper](https://arxiv.org/abs/2306.10985)], [[PDF](https://arxiv.org/pdf/2306.10985.pdf)] <br>
- **Language to Rewards for Robotic Skill Synthesis** `Reward Desgin` <br>
  Team: Google Deepmind. <br>
  *Wenhao Yu, Nimrod Gileadi, Chuyuan Fu, etal., Fei Xia* <br>
  ICLR'23, arXiv, 2023.06 [[Paper](https://arxiv.org/abs/2306.08647)], [[PDF](https://arxiv.org/pdf/2306.08647.pdf)], [[Home Page](https://language-to-reward.github.io/)], [[Demo](https://www.youtube.com/watch?v=7KiKg0rdSSQ)]  <br>
  [[Code](https://github.com/google-deepmind/language_to_reward_2023)] ![](https://img.shields.io/github/stars/google-deepmind/language_to_reward_2023?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/google-deepmind/language_to_reward_2023?style=round-square&logo=Github&logoColor=white)  <br>
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
  ICLR'23, arXiv, 2023.02 [[Paper](https://arxiv.org/abs/2303.00001)], [[PDF](https://arxiv.org/pdf/2303.00001.pdf)]<br>
  [[Code](https://github.com/minaek/reward_design_with_llms)] ![](https://img.shields.io/github/stars/minaek/reward_design_with_llms?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/minaek/reward_design_with_llms?style=round-square&logo=Github&logoColor=white)  <br>
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
  arXiv, 2022.04 [[Paper](https://arxiv.org/abs/2204.01691)], [[PDF](https://arxiv.org/pdf/2204.01691.pdf)], [[Home Page](https://say-can.github.io/)], [[Demo](https://sites.research.google/palm-saycan)] <br>
  [[Code](https://github.com/google-research/google-research/tree/master/saycan)]
- **Sequence-of-Constraints MPC: Reactive Timing-Optimal Control of Sequential Manipulation** `Manipulation Planning`<br>
  *Marc Toussaint, Jason Harris, Jung-Su Ha, Danny Driess, Wolfgang Hönig* <br>
  IROS'22, arXiv, 2022.03 [[Paper](https://arxiv.org/abs/2203.05390)], [[PDF](https://arxiv.org/pdf/2203.05390.pdf)]<br>
- **Visually-Grounded Planning without Vision: Language Models Infer Detailed Plans from High-level Instructions** `Language Model Only` <br>
  *Peter A. Jansen* <br>
  EMNLP'20, arXiv, 2020.09 [[Paper](https://arxiv.org/abs/2009.14259)], [[PDF](https://arxiv.org/pdf/2009.14259.pdf)] <br>
  [[Code](https://github.com/cognitiveailab/alfred-gpt2/)] ![](https://img.shields.io/github/stars/cognitiveailab/alfred-gpt2?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/cognitiveailab/alfred-gpt2?style=round-square&logo=Github&logoColor=white)  <br>
### <a name="robo_task_adapt"></a> Task Adaptation
- **Bootstrap Your Own Skills: Learning to Solve New Tasks with Large Language Model Guidance** `Learn New Tasks` <br>
  Team: Robotics at Google, Everyday Robots. <br>
  *Jesse Zhang, Jiahui Zhang, Karl Pertsch, et al., Joseph J. Lim* <br>
  **CoRL'23(Oral)**, arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2310.10021)], [[PDF](https://arxiv.org/pdf/2310.10021.pdf)], [[Home Page](https://clvrai.github.io/boss/)] <br>
  [[Code](https://github.com/clvrai/boss)] ![](https://img.shields.io/github/stars/clvrai/boss?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/clvrai/boss?style=round-square&logo=Github&logoColor=white)  <br>
## <a name="robo_survey"></a> Survey
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
  arXiv, 2023.12 [[Paper](https://arxiv.org/abs/2312.08782)], [[PDF](https://arxiv.org/pdf/2312.08782.pdf)] <br>
  [[Code](https://github.com/JeffreyYH/robotics-fm-survey)] ![](https://img.shields.io/github/stars/JeffreyYH/robotics-fm-survey?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/JeffreyYH/robotics-fm-survey?style=round-square&logo=Github&logoColor=white)  <br>
- **Foundation Models in Robotics: Applications, Challenges, and the Future** <br>
  *Roya Firoozi, Johnathan Tucker, Stephen Tian, et al., Mac Schwager* <br>
  arXiv, 2023.12 [[Paper](https://arxiv.org/abs/2312.07843)] <br>
  [[Code](https://github.com/robotics-survey/Awesome-Robotics-Foundation-Models)] ![](https://img.shields.io/github/stars/robotics-survey/Awesome-Robotics-Foundation-Models?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/robotics-survey/Awesome-Robotics-Foundation-Models?style=round-square&logo=Github&logoColor=white)  <br>
- **Robot Learning in the Era of Foundation Models: A Survey** <br>
  *Xuan Xiao, Jiahang Liu, Zhipeng Wang, et al., Shuo Jiang* <br>
  arXiv, 2023.11 [[Paper](https://arxiv.org/abs/2311.14379)],  [[PDF](https://arxiv.org/pdf/2311.14379.pdf)]  <br>
- **Recent Advances in Robot Learning from Demonstration** <br>
  *Harish Ravichandar, Athanasios S. Polydoros, Sonia Chernova, Aude Billard <br>
  Annual Review of Control, Robotics, and Autonomous Systems, 2020.05 [[Paper](https://www.annualreviews.org/doi/abs/10.1146/annurev-control-100819-063206)], [[PDF](https://www.annualreviews.org/doi/pdf/10.1146/annurev-control-100819-063206)]  <br>
## <a name="robo_ben_sim_tool"></a> Dataset/Benchmark/Simulator/Tool
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
  arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2310.08864)], [[PDF](https://arxiv.org/pdf/2310.08864.pdf)], [[HomePage](https://robotics-transformer-x.github.io/)] <br>
  [[Code](https://github.com/google-deepmind/open_x_embodiment)] ![](https://img.shields.io/github/stars/google-deepmind/open_x_embodiment?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/google-deepmind/open_x_embodiment?style=round-square&logo=Github&logoColor=white)
- **ARNOLD: A Benchmark for Language-Grounded Task Learning With Continuous States in Realistic 3D Scenes** <br>
  *Ran Gong, Jiangyong Huang, Yizhou Zhao, et al., Siyuan Huang* <br>
  ICCV'23, 2023.04 [[Paper](https://arxiv.org/abs/2304.04321)], [[PDF](https://arxiv.org/pdf/2304.04321.pdf)] <br>
  [[Code](https://github.com/arnold-benchmark/arnold)] ![](https://img.shields.io/github/stars/arnold-benchmark/arnold?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/arnold-benchmark/arnold?style=round-square&logo=Github&logoColor=white)  <br>
- **RLBench: The Robot Learning Benchmark & Learning Environment** <br>
  Team: NVlabs NVIDIA <br>
  *Stephen James, Zicong Ma, David Rovick Arrojo, Andrew J. Davison* <br>
  IEEE Robotics and Automation Letters, 2019.09 [[Paper](https://arxiv.org/abs/1909.12271)]
  [[Code](https://github.com/stepjam/RLBench)] ![](https://img.shields.io/github/stars/stepjam/RLBench?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/stepjam/RLBench?style=round-square&logo=Github&logoColor=white)  <br>


## <a name="robo_uncategorized"></a> Uncategorized


