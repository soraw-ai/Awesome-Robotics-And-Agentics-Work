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
  *Balakumar Sundaralingam, Siva Kumar Sastry Hari, Adam Fishman, Caelan Garrett, Karl Van Wyk, Valts Blukis, Alexander Millane, Helen Oleynikova, Ankur Handa, Fabio Ramos, Nathan Ratliff, Dieter Fox* <br>
  Team: NVlabs, NVIDIA <br>
  arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2310.17274)], [[PDF](https://arxiv.org/pdf/2310.17274.pdf)] <br>
  [[Code](https://github.com/NVlabs/curobo)] ![](https://img.shields.io/github/stars/NVlabs/curobo?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/NVlabs/curobo?style=round-square&logo=Github&logoColor=white)
- **GenSim: Generating Robotic Simulation Tasks via Large Language Models** <br>
  *Lirui Wang, Yiyang Ling, Zhecheng Yuan, Mohit Shridhar, Chen Bao, Yuzhe Qin, Bailin Wang, Huazhe Xu, Xiaolong Wang* <br>
  arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2310.01361)] <br>
  [[Code](https://github.com/liruiw/GenSim)] ![](https://img.shields.io/github/stars/liruiw/GenSim?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/liruiw/GenSim?style=round-square&logo=Github&logoColor=white)
- **RoboGen: Towards Unleashing Infinite Data for Automated Robot Learning via Generative Simulation** <br>
  *Yufei Wang, Zhou Xian, Feng Chen, Tsun-Hsuan Wang, Yian Wang, Zackory Erickson, David Held, Chuang Gan* <br>
  arXiv, 2023.11 [[Paper](https://arxiv.org/abs/2311.01455)] <br>
  [[Code](https://github.com/Genesis-Embodied-AI/RoboGen)] ![](https://img.shields.io/github/stars/Genesis-Embodied-AI/RoboGen?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/Genesis-Embodied-AI/RoboGen?style=round-square&logo=Github&logoColor=white)
## <a name="robo_manipulation"></a> Manipulation
- **Robo-ABC: Affordance Generalization Beyond Categories via Semantic Correspondence for Robot Manipulation** `Grasp` <br>
  *Yuanchen Ju, Kaizhe Hu, Guowei Zhang, Gu Zhang, Mingrun Jiang, Huazhe Xu* <br>
  arXiv, 2024.01 [[Paper](https://arxiv.org/abs/2401.07487)], [[PDF](https://arxiv.org/pdf/2401.07487.pdf)], [[Home Page](https://tea-lab.github.io/Robo-ABC/)]
  [[Code (TBD)](https://github.com/TEA-Lab/Robo-ABC)] ![](https://img.shields.io/github/stars/TEA-Lab/Robo-ABC?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/TEA-Lab/Robo-ABC?style=round-square&logo=Github&logoColor=white)
- **Visual Robotic Manipulation with Depth-Aware Pretraining** <br>
  *Wanying Wang, Jinming Li, Yichen Zhu, Zhiyuan Xu, Zhengping Che, Yaxin Peng, Chaomin Shen, Dong Liu, Feifei Feng, Jian Tang* <br>
  arXiv, 2024.01 [[Paper](https://arxiv.org/abs/2401.09038)], [[PDF](https://arxiv.org/pdf/2401.09038.pdf)]
- **ManipLLM: Embodied Multimodal Large Language Model for Object-Centric Robotic Manipulation** <br>
  *Xiaoqi Li, Mingxu Zhang, Yiran Geng, Haoran Geng, Yuxing Long, Yan Shen, Renrui Zhang, Jiaming Liu, Hao Dong* <br>
  arXiv, 2023.12 [[Paper](https://arxiv.org/abs/2312.16217)], [[PDF](https://arxiv.org/pdf/2312.16217.pdf)], [[Home Page](https://sites.google.com/view/manipllm)]
- **M2T2: Multi-Task Masked Transformer for Object-centric Pick and Place** `Grasp` <br>
  *Wentao Yuan, Adithyavairavan Murali, Arsalan Mousavian, Dieter Fox* <br>
  CoRL'23, arXiv, 2023.12 [[Paper](https://arxiv.org/abs/2311.00926)], [[PDF](https://arxiv.org/pdf/2311.00926.pdf)], [[Home Page](https://m2-t2.github.io/)] <br>
  [[Code](https://github.com/NVlabs/M2T2)] ![](https://img.shields.io/github/stars/NVlabs/M2T2?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/NVlabs/M2T2?style=round-square&logo=Github&logoColor=white)
- **Make a Donut: Language-Guided Hierarchical EMD-Space Planning for Zero-shot Deformable Object Manipulation** <br>
  *Yang You, Bokui Shen, Congyue Deng, Haoran Geng, He Wang, Leonidas Guibas* <br>
  arXiv, 2023.11 [[Paper](https://arxiv.org/abs/2311.02787)], [[PDF](https://arxiv.org/pdf/2311.02787.pdf)]
- **D3Fields: Dynamic 3D Descriptor Fields for Zero-Shot Generalizable Robotic Manipulation** `Multimodal` <br>
  Team: UIUC, Stanford University, Fei-Fei Li. <br>
  *Yixuan Wang, Zhuoran Li, Mingtong Zhang, Katherine Driggs-Campbell, Jiajun Wu, Li Fei-Fei, Yunzhu Li* <br>
  CoRL'23, arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2309.16118)], [[PDF](https://arxiv.org/pdf/2309.16118.pdf)], [[Home Page](https://robopil.github.io/d3fields/)], [[Demo](https://www.youtube.com/watch?v=yNkIOwAO3GA)]<br>
  [[Code](https://github.com/WangYixuan12/d3fields)] ![](https://img.shields.io/github/stars/WangYixuan12/d3fields?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/WangYixuan12/d3fields?style=round-square&logo=Github&logoColor=white)
- **Gen2Sim: Scaling up Robot Learning in Simulation with Generative Models** <br>
  *Pushkal Katara, Zhou Xian, Katerina Fragkiadaki* <br>
  arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2310.18308)], [[PDF](https://arxiv.org/pdf/2310.18308.pdf)], [[Home Page](https://gen2sim.github.io/)] <br>
  [[Code](https://github.com/pushkalkatara/Gen2Sim)] ![](https://img.shields.io/github/stars/pushkalkatara/Gen2Sim?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/pushkalkatara/Gen2Sim?style=round-square&logo=Github&logoColor=white)
-  **RVT: Robotic View Transformer for 3D Object Manipulation** `Grasp` <br>
  Team: NVIDIA Labs <br>
  *Ankit Goyal, Jie Xu, Yijie Guo, Valts Blukis, Yu-Wei Chao, Dieter Fox* <br>
  **CoRL (Oral)**, arXiv, 2023.06 [[Paper](https://arxiv.org/abs/2306.14896)], [[PDF](https://arxiv.org/pdf/2306.14896.pdf)], [[Home Page](https://robotic-view-transformer.github.io/)], [[Demo](https://www.youtube.com/watch?v=mIQN4f3KSA8)] <br>
  [[Code](https://github.com/nvlabs/rvt)] ![](https://img.shields.io/github/stars/nvlabs/rvt?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/nvlabs/rvt?style=round-square&logo=Github&logoColor=white)
- **Distilled Feature Fields Enable Few-Shot Language-Guided Manipulation** `Grasp` <br>
  Team: MIT CSAIL <br>
  *William Shen, Ge Yang, Alan Yu, Jansen Wong, Leslie Pack Kaelbling, Phillip Isola* <br>
  **CoRL'23 (Best Paper)**, arXiv, 2023.06 [[Paper](https://arxiv.org/abs/2308.07931)], [[PDF](https://arxiv.org/abs/2308.07931)], [[Home Page](https://f3rm.github.io/)], [[Demo](https://f3rm.github.io/#video)] <br>
  [Code](https://github.com/f3rm/f3rm)] ![](https://img.shields.io/github/stars/f3rm/f3rm?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/f3rm/f3rm?style=round-square&logo=Github&logoColor=white)
## <a name="robo_navigation"></a> Navigation
- **MapGPT: Map-Guided Prompting for Unified Vision-and-Language Navigation** <br>
  *Jiaqi Chen, Bingqian Lin, Ran Xu, Zhenhua Chai, Xiaodan Liang, Kwan-Yee K. Wong* <br>
  arXiv, 2024.01 [[Paper](https://arxiv.org/abs/2401.07314)], [[PDF](https://arxiv.org/pdf/2401.07314.pdf)]
- **Visual Language Maps for Robot Navigation** <br>
  *Chenguang Huang, Oier Mees, Andy Zeng, Wolfram Burgard* <br>
  ICRA'23, arXiv, 2022.10 [[Paper](https://arxiv.org/abs/2210.05714)], [[PDF](https://arxiv.org/pdf/2210.05714.pdf)], [[Home Page](https://vlmaps.github.io/)] <br>
  [[Code](https://colab.research.google.com/drive/1xsH9Gr_O36sBZaoPNq1SmqgOOF12spV0?usp=sharing)]
## <a name="robo_planning"></a> Planning
- **RePLan: Robotic Replanning with Perception and Language Models** `Motion Planning`,`Multimodal` <br>
  *Marta Skreta, Zihan Zhou, Jia Lin Yuan, et al., Animesh Garg* <br>
  arXiv, 2024.01 [[Paper](https://arxiv.org/abs/2401.04157)], [[PDF](https://arxiv.org/pdf/2401.04157.pdf)], [[Home Page](https://replan-lm.github.io/replan.github.io/)], [[Demo](https://youtu.be/mgqR-vLsH0E)]
- **Human Demonstrations are Generalizable Knowledge for Robots** `Task Planning`, `Human Demo` <br>
  *Guangyan Chen, Te Cui, Tianxing Zhou, et al., Yufeng Yue* <br>
  arXiv, 2023.12 [[Paper](https://arxiv.org/abs/2312.02419)], [[PDF](https://arxiv.org/pdf/2312.02419.pdf)]
- **Look Before You Leap: Unveiling the Power of GPT-4V in Robotic Vision-Language Planning** `Motion Planning`<br>
  Team: Tsinghua University. <br>
  *Yingdong Hu, Fanqi Lin, Tong Zhang, Li Yi, Yang Gao* <br>
  arXiv, 2023.11 [[Paper](https://arxiv.org/abs/2311.17842)], [[PDF](https://arxiv.org/pdf/2311.17842.pdf)], [[Home Page](https://robot-vila.github.io/)], [[Demo](https://www.youtube.com/watch?v=t8pPZ46xtuc)]
- **GPT-4V(ision) for Robotics: Multimodal Task Planning from Human Demonstration** `Task Planning`, `Human Demo`<br>
  Team: Microsoft. <br>
  *Naoki Wake, Atsushi Kanehira, Kazuhiro Sasabuchi, Jun Takamatsu, Katsushi Ikeuchi* <br>
  arXiv, 2023.11 [[Paper](https://arxiv.org/abs/2311.12015)], [[PDF](https://arxiv.org/pdf/2311.12015.pdf)], [[Home Page](https://microsoft.github.io/GPT4Vision-Robot-Manipulation-Prompts/)]
  [[Code](https://github.com/microsoft/ChatGPT-Robot-Manipulation-Prompts)] ![](https://img.shields.io/github/stars/microsoft/ChatGPT-Robot-Manipulation-Prompts?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/microsoft/ChatGPT-Robot-Manipulation-Prompts?style=round-square&logo=Github&logoColor=white)
- **VoxPoser: Composable 3D Value Maps for Robotic Manipulation with Language Models** `Motion Planning`,`Multimodal` <br>
  Team: Stanford University, Fei-Fei Li. <br>
  *Wenlong Huang, Chen Wang, Ruohan Zhang, Yunzhu Li, Jiajun Wu, Li Fei-Fei* <br>
  **CoRL'23(Oral)**, arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2307.05973)], [[PDF](https://arxiv.org/pdf/2307.05973.pdf)], [[Home Page](https://voxposer.github.io/)], [[Demo](https://www.youtube.com/watch?v=Yvn4eR05A3M)]  <br>
  [[Code](https://github.com/huangwl18/VoxPoser)] ![](https://img.shields.io/github/stars/huangwl18/VoxPoser?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/huangwl18/VoxPoser?style=round-square&logo=Github&logoColor=white)
- **Prompt a Robot to Walk with Large Language Models** <br>
  *Yen-Jen Wang, Bike Zhang, Jianyu Chen, Koushil Sreenath* <br>
  arXiv, 2023.09 [[Paper](https://arxiv.org/abs/2309.09969)], [[PDF](https://arxiv.org/pdf/2309.09969.pdf)], [[Home Page](https://prompt2walk.github.io/)] <br>
  [[Code](https://github.com/HybridRobotics/prompt2walk)] ![](https://img.shields.io/github/stars/HybridRobotics/prompt2walk?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/HybridRobotics/prompt2walk?style=round-square&logo=Github&logoColor=white)
- **SayPlan: Grounding Large Language Models using 3D Scene Graphs for Scalable Robot Task Planning** `Task Planning` <br>
  *Krishan Rana, Jesse Haviland, Sourav Garg, Jad Abou-Chakra, Ian Reid, Niko Suenderhauf* <br>
  **CoRL'23(Oral)**, arXiv, 2023.07 [[Paper](https://arxiv.org/abs/2307.06135)], [[PDF](https://arxiv.org/pdf/2307.06135.pdf)], [[Home Page](https://sayplan.github.io/)], [[Demo](https://www.youtube.com/watch?v=3aMgpqnD2RY)] <br>
- **PaLM-E: An Embodied Multimodal Language Model** `Task Planning`, `Multimodal` <br>
  Team: Robotics at Google. <br>
  *Danny Driess, Fei Xia, Mehdi S. M. Sajjadi, et al., Pete Florence* <br>
  ICML'23, arXiv, 2023.03 [[Paper](https://arxiv.org/abs/2303.03378)], [[PDF](https://arxiv.org/pdf/2303.03378.pdf)], [[Home Page](https://palm-e.github.io/)] <br>
- **Grounded Decoding: Guiding Text Generation with Grounded Models for Embodied Agents** `Multimodal` <br>
  Team: Stanford University, Robotics at Google. <br>
  *Wenlong Huang, Fei Xia, Dhruv Shah, et al., Brian Ichter* <br>
  arXiv, 2023.03 [[Paper](https://arxiv.org/abs/2303.00855)], [[PDF](https://arxiv.org/pdf/2303.00855.pdf)], [[Home Page](https://grounded-decoding.github.io/)], [[Demo](https://www.youtube.com/watch?v=KHhAlBIQftQ)] <br>
- **Do As I Can, Not As I Say: Grounding Language in Robotic Affordances** `Task Planning`, `Multimodal` <br>
  Team: Robotics at Google, Everyday Robots. <br>
  *Michael Ahn, Anthony Brohan, Noah Brown, et al., Andy Zeng* <br>
  arXiv, 2022.04 [[Paper](https://arxiv.org/abs/2204.01691)], [[PDF](https://arxiv.org/pdf/2204.01691.pdf)], [[Home Page](https://say-can.github.io/)], [[Demo](https://sites.research.google/palm-saycan)] <br>
  [[Code](https://github.com/google-research/google-research/tree/master/saycan)]
- **Visually-Grounded Planning without Vision: Language Models Infer Detailed Plans from High-level Instructions** `Language Model Only` <br>
  *Peter A. Jansen* <br>
  EMNLP'20, arXiv, 2020.09 [[Paper](https://arxiv.org/abs/2009.14259)], [[PDF](https://arxiv.org/pdf/2009.14259.pdf)] <br>
  [[Code](https://github.com/cognitiveailab/alfred-gpt2/)] ![](https://img.shields.io/github/stars/cognitiveailab/alfred-gpt2?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/cognitiveailab/alfred-gpt2?style=round-square&logo=Github&logoColor=white)
### <a name="robo_task_adapt"></a> Task Adaptation
- **Bootstrap Your Own Skills: Learning to Solve New Tasks with Large Language Model Guidance** `Learn New Tasks` <br>
  Team: Robotics at Google, Everyday Robots. <br>
  *Jesse Zhang, Jiahui Zhang, Karl Pertsch, et al., Joseph J. Lim* <br>
  **CoRL'23(Oral)**, arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2310.10021)], [[PDF](https://arxiv.org/pdf/2310.10021.pdf)], [[Home Page](https://clvrai.github.io/boss/)] <br>
  [[Code](https://github.com/clvrai/boss)] ![](https://img.shields.io/github/stars/clvrai/boss?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/clvrai/boss?style=round-square&logo=Github&logoColor=white)
## <a name="robo_survey"></a> Survey
- **Large Language Models for Robotics: Opportunities, Challenges, and Perspectives** <br>
  *Jiaqi Wang, Zihao Wu, Yiwei Li, et al., Shu Zhang* <br>
  arXiv, 2024.01 [[Paper](https://arxiv.org/abs/2401.04334)], [[PDF](https://arxiv.org/pdf/2401.04334.pdf)]
- **Language-conditioned Learning for Robotic Manipulation: A Survey** <br>
  *Hongkuan Zhou, Xiangtong Yao, Yuan Meng, Siming Sun, Zhenshan BIng, Kai Huang, Alois Knoll* <br>
  arXiv, 2023.12 [[Paper](https://arxiv.org/abs/2312.10807)], [[PDF](https://arxiv.org/pdf/2312.10807.pdf)]
- **Toward General-Purpose Robots via Foundation Models: A Survey and Meta-Analysis** <br>
  *Yafei Hu, Quanting Xie, Vidhi Jain, et al., Yonatan Bisk* <br>
  arXiv, 2023.12 [[Paper](https://arxiv.org/abs/2312.08782)], [[PDF](https://arxiv.org/pdf/2312.08782.pdf)] <br>
  [[Code](https://github.com/JeffreyYH/robotics-fm-survey)] ![](https://img.shields.io/github/stars/JeffreyYH/robotics-fm-survey?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/JeffreyYH/robotics-fm-survey?style=round-square&logo=Github&logoColor=white)
- **Foundation Models in Robotics: Applications, Challenges, and the Future** <br>
  *Roya Firoozi, Johnathan Tucker, Stephen Tian, Anirudha Majumdar, Jiankai Sun, Weiyu Liu, Yuke Zhu, Shuran Song, Ashish Kapoor, Karol Hausman, Brian Ichter, Danny Driess, Jiajun Wu, Cewu Lu, Mac Schwager* <br>
  arXiv, 2023.12 [[Paper](https://arxiv.org/abs/2312.07843)] <br>
  [[Code](https://github.com/robotics-survey/Awesome-Robotics-Foundation-Models)] ![](https://img.shields.io/github/stars/robotics-survey/Awesome-Robotics-Foundation-Models?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/robotics-survey/Awesome-Robotics-Foundation-Models?style=round-square&logo=Github&logoColor=white)
- **Robot Learning in the Era of Foundation Models: A Survey** <br>
  *Xuan Xiao, Jiahang Liu, Zhipeng Wang, Yanmin Zhou, Yong Qi, Qian Cheng, Bin He, Shuo Jiang* <br>
  arXiv, 2023.11 [[Paper](https://arxiv.org/abs/2311.14379)],  [[PDF](https://arxiv.org/pdf/2311.14379.pdf)]
## <a name="robo_ben_sim_tool"></a> Dataset/Benchmark/Simulator/Tool
- **Open X-Embodiment: Robotic Learning Datasets and RT-X Models** <br>
  Team: DeepMind <br>
  *Open X-Embodiment Collaboration, et al.* <br>
  arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2310.08864)], [[PDF](https://arxiv.org/pdf/2310.08864.pdf)], [[HomePage](https://robotics-transformer-x.github.io/)] <br>
  [[Code](https://github.com/google-deepmind/open_x_embodiment)] ![](https://img.shields.io/github/stars/google-deepmind/open_x_embodiment?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/google-deepmind/open_x_embodiment?style=round-square&logo=Github&logoColor=white)
- **ARNOLD: A Benchmark for Language-Grounded Task Learning With Continuous States in Realistic 3D Scenes** <br>
  *Ran Gong, Jiangyong Huang, Yizhou Zhao, Haoran Geng, Xiaofeng Gao, Qingyang Wu, Wensi Ai, Ziheng Zhou, Demetri Terzopoulos, Song-Chun Zhu, Baoxiong Jia, Siyuan Huang* <br>
  ICCV'23, 2023.04 [[Paper](https://arxiv.org/abs/2304.04321)], [[PDF](https://arxiv.org/pdf/2304.04321.pdf)] <br>
  [[Code](https://github.com/arnold-benchmark/arnold)] ![](https://img.shields.io/github/stars/arnold-benchmark/arnold?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/arnold-benchmark/arnold?style=round-square&logo=Github&logoColor=white)
- **RLBench: The Robot Learning Benchmark & Learning Environment** <br>
  Team: NVlabs NVIDIA <br>
  *Stephen James, Zicong Ma, David Rovick Arrojo, Andrew J. Davison* <br>
  IEEE Robotics and Automation Letters, 2019.09 [[Paper](https://arxiv.org/abs/1909.12271)]
  [[Code](https://github.com/stepjam/RLBench)] ![](https://img.shields.io/github/stars/stepjam/RLBench?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/stepjam/RLBench?style=round-square&logo=Github&logoColor=white)


## <a name="robo_uncategorized"></a> Uncategorized
- **Eureka: Human-Level Reward Design via Coding Large Language Models** <br>
  *Yecheng Jason Ma, William Liang, Guanzhi Wang, De-An Huang, Osbert Bastani, Dinesh Jayaraman, Yuke Zhu, Linxi Fan, Anima Anandkumar* <br>
  arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2310.12931)] <br>
  [[Code](https://github.com/eureka-research/Eureka)] ![](https://img.shields.io/github/stars/eureka-research/Eureka?style=round-square&logo=Github&logoColor=white) ![](https://img.shields.io/github/last-commit/eureka-research/Eureka?style=round-square&logo=Github&logoColor=white)

