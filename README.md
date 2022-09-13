# ReasoningNLP
Paper list on reasoning in NLP.

## Languague Model Reasoning
1. **Critical Thinking for Language Models** IWCS (2021)

   *Gregor Betz, Christian Voigt, Kyle Richardson* [[pdf](https://aclanthology.org/2021.iwcs-1.7.pdf)] [[project](https://github.com/debatelab/aacorpus)]

2. **Show Your Work: Scratchpads for Intermediate Computation with Language Models** arXiv (2021)

   *Maxwell Nye, Anders Johan Andreassen, Guy Gur-Ari, Henryk Michalewski, Jacob Austin, David Bieber, David Dohan, Aitor Lewkowycz, Maarten Bosma, David Luan, Charles Sutton, Augustus Odena* [[pdf](https://arxiv.org/pdf/2112.00114.pdf)]

3. **Chain of Thought Prompting Elicits Reasoning in Large Language Models** arXiv (2022)

   *Jason Wei, Xuezhi Wang, Dale Schuurmans, Maarten Bosma, Brian Ichter, Fei Xia, Ed Chi, Quoc Le, Denny Zhou* [[pdf](https://arxiv.org/pdf/2201.11903.pdf)] [[project](https://github.com/jasonwei20/chain-of-thought-prompting)]

4. **STaR: Bootstrapping Reasoning With Reasoning** arXiv (2022)

   *Eric Zelikman, Yuhuai Wu, Jesse Mu, Noah D. Goodman* [[pdf](https://arxiv.org/pdf/2203.14465.pdf)]

5. **Selection-Inference: Exploiting Large Language Models for Interpretable Logical Reasoning** arXiv (2022)

   *Antonia Creswell, Murray Shanahan, Irina Higgins* [[pdf](https://arxiv.org/pdf/2205.09712.pdf)]

6. **Least-to-Most Prompting Enables Complex Reasoning in Large Language Models** arXiv (2022)

   *Denny Zhou, Nathanael Schärli, Le Hou, Jason Wei, Nathan Scales, Xuezhi Wang, Dale Schuurmans, Olivier Bousquet, Quoc Le, Ed Chi* [[pdf](https://arxiv.org/pdf/2205.10625.pdf)]

7. **Large Language Models are Zero-Shot Reasoners** arXiv (2022)

   *Takeshi Kojima, Shixiang Shane Gu, Machel Reid, Yutaka Matsuo, Yusuke Iwasawa* [[pdf](https://arxiv.org/pdf/2205.11916.pdf)] [[project](https://github.com/kojima-takeshi188/zero_shot_cot)]

8. **Faithful Reasoning Using Large Language Models** arXiv (2022)

   *Antonia Creswell, Murray Shanahan* [[pdf](https://arxiv.org/pdf/2208.14271.pdf)]


### Effect & Concern
1. **Language models show human-like content effects on reasoning** arXiv (2022)

   *Ishita Dasgupta, Andrew K. Lampinen, Stephanie C. Y. Chan, Antonia Creswell, Dharshan Kumaran, James L. McClelland, Felix Hill* [[pdf](https://arxiv.org/pdf/2207.07051.pdf)]

2. **On the Paradox of Learning to Reason from Data** arXiv (2022)

    *Honghua Zhang, Liunian Harold Li, Tao Meng, Kai-Wei Chang, Guy Van den Broeck* [[pdf](https://arxiv.org/pdf/2205.11502.pdf)] [[project](https://github.com/joshuacnf/paradox-learning2reason)]







## Knowledge Graph Reasoning
Knowledge graph completion task aims to complete the graph, while multi-hop reasoning is the task querying in incomplete graphs. Both these two tasks require reasoning over knowledge graphs. There are also some other reasoning tasks. 

### Knowledge Graph Completion
1. **Collaborative Policy Learning for Open Knowledge Graph Reasoning** EMNLP (2019)

   *Cong Fu, Tong Chen, Meng Qu, Woojeong Jin, Xiang Ren* [[pdf](http://aclanthology.lst.uni-saarland.de/D19-1269.pdf)] [[project](https://github.com/shanzhenren/CPL)]


2. **DIVINE: A Generative Adversarial Imitation Learning Framework for Knowledge Graph Reasoning** EMNLP (2019)

   *Ruiping Li, Xiang Cheng* [[pdf](https://aclanthology.org/D19-1266.pdf)] [[project](https://github.com/BUPT-Data-Intelligence-Lab/DIVINE)]

3. **Learning Collaborative Agents with Rule Guidance for Knowledge Graph Reasoning** EMNLP (2020)

   *Deren Lei, Gangrong Jiang, Xiaotao Gu, Kexuan Sun, Yuning Mao, Xiang Ren* [[pdf](https://aclanthology.org/2020.emnlp-main.688.pdf)] [[project](https://github.com/derenlei/KG-RuleGuider)]

4. **Incorporating Graph Attention Mechanism into Knowledge Graph Reasoning Based on Deep Reinforcement Learning** EMNLP (2019)

   *Heng Wang, Shuangyin Li, Rong Pan, Mingzhi Mao* [[pdf](https://aclanthology.org/D19-1264.pdf)] [[project](https://aclanthology.org/attachments/D19-1264.Attachment.zip)]

5. **Dynamically Pruned Message Passing Networks for Large-scale Knowledge Graph Reasoning** ICLR Poster (2020)

   *Xiaoran Xu, Wei Feng, Yunsheng Jiang, Xiaohui Xie, Zhiqing Sun, Zhi-Hong Deng* [[pdf](https://openreview.net/pdf?id=rkeuAhVKvB)] [[project](https://github.com/netpaladinx/DPMPN)]

6. **Inductive Relation Prediction by Subgraph Reasoning** ICML (2020)

   *Komal K. Teru, Etienne G. Denis, William L. Hamilton* [[pdf](https://proceedings.mlr.press/v119/teru20a/teru20a.pdf)] [[project](https://github.com/kkteru/grail)]

7. **Adapting Meta Knowledge Graph Information for Multi-Hop Reasoning over Few-Shot Relations** EMNLP (2019)

   *Xin Lv, Yuxian Gu, Xu Han, Lei Hou, Juanzi Li, Zhiyuan Liu* [[pdf](https://aclanthology.org/D19-1334.pdf)] [[project](https://github.com/THU-KEG/MetaKGR)]

8. **Dynamic Anticipation and Completion for Multi-Hop Reasoning over Sparse Knowledge Graph** EMNLP (2020)

   *Xin Lv, Xu Han, Lei Hou, Juanzi Li, Zhiyuan Liu, Wei Zhang, Yichi Zhang, Hao Kong, Suhui Wu* [[pdf](https://aclanthology.org/2020.emnlp-main.459.pdf)] [[project](https://github.com/THU-KEG/DacKGR)]


### Multi-Hop Reasoning
1. **Query2box: Reasoning over Knowledge Graphs in Vector Space Using Box Embeddings** ICLR Poster (2020)

   *Hongyu Ren, Weihua Hu, Jure Leskovec* [[pdf](https://openreview.net/pdf?id=BJgr4kSFDS)] [[project](http://snap.stanford.edu/query2box)]

2. **Beta Embeddings for Multi-Hop Logical Reasoning in Knowledge Graphs** NIPS (2020)

   *Hongyu Ren, Jure Leskovec* [[pdf](https://papers.nips.cc/paper/2020/file/e43739bba7cdb577e9e3e4e42447f5a5-Paper.pdf)] [[project](http://snap.stanford.edu/betae)]

3. **Probabilistic Entity Representation Model for Reasoning over Knowledge Graphs** NIPS (2021)

   *Nurendra Choudhary, Nikhil Rao, Sumeet Katariya, Karthik Subbian, Chandan K. Reddy* [[pdf](https://papers.nips.cc/paper/2021/file/c4d2ce3f3ebb5393a77c33c0cd95dc93-Paper.pdf)] [[project](https://github.com/Akirato/PERM-GaussianKG)]

4. **ConE: Cone Embeddings for Multi-Hop Reasoning over Knowledge Graphs** NIPS (2021)

   *Zhanqiu Zhang, Jie Wang, Jiajun Chen, Shuiwang Ji, Feng Wu* [[pdf](https://papers.nips.cc/paper/2021/file/a0160709701140704575d499c997b6ca-Paper.pdf)] [[project](https://github.com/MIRALab-USTC/QE-ConE)]


### Others
1. **Quantum Embedding of Knowledge for Reasoning** NIPS (2019)

   *Dinesh Garg, Shajith Ikbal, Santosh K. Srivastava, Harit Vishwakarma, Hima P. Karanam, L. Venkata Subramaniam* [[pdf](https://papers.nips.cc/paper/2019/file/cb12d7f933e7d102c52231bf62b8a678-Paper.pdf)] [[project](https://github.com/IBM/e2r)]

2. **Probabilistic Logic Neural Networks for Reasoning** NIPS (2019)

   *Meng Qu, Jian Tang* [[pdf](https://papers.nips.cc/paper/2019/file/13e5ebb0fa112fe1b31a1067962d74a7-Paper.pdf)]

3. **RNNLogic: Learning Logic Rules for Reasoning on Knowledge Graphs** ICLR Poster (2021)

   *Meng Qu, Junkun Chen, Louis-Pascal A. C. Xhonneux, Yoshua Bengio, Jian Tang* [[pdf](https://openreview.net/pdf?id=tGZu6DlbreV)] [[project](https://github.com/DeepGraphLearning/RNNLogic)]

4. **Efficient Probabilistic Logic Reasoning with Graph Neural Networks** ICLR Poster (2020)

   *Yuyu Zhang, Xinshi Chen, Yuan Yang, Arun Ramamurthy, Bo Li, Yuan Qi, Le Song* [[pdf](https://openreview.net/pdf?id=rJg76kStwH)]

5. **Explainable Subgraph Reasoning for Forecasting on Temporal Knowledge Graphs** ICLR Poster (2021)

   *Zhen Han, Peng Chen, Yunpu Ma, Volker Tresp* [[pdf](https://openreview.net/pdf?id=pGIHq1m7PU)] [[project](https://github.com/TemporalKGTeam/xERTE)]







## Mathematical Reasoning



## Commonsense Reasoning
### Winograd Schema Challenge & Pronoun Disambiguation Problem
1. **Unsupervised Deep Structured Semantic Models for Commonsense Reasoning** NAACL (2019)

   *Shuohang Wang, Sheng Zhang, Yelong Shen, Xiaodong Liu, Jingjing Liu, Jianfeng Gao, Jing Jiang* [[pdf](https://aclanthology.org/N19-1094.pdf)]

2. **Attention Is (not) All You Need for Commonsense Reasoning** EMNLP (2019)

   *Tassilo Klein, Moin Nabi* [[pdf](https://aclanthology.org/P19-1477.pdf)]

3. **How Reasonable are Common-Sense Reasoning Tasks: A Case-Study on the Winograd Schema Challenge and SWAG** EMNLP (2019)

   *Paul Trichelair, Ali Emami, Adam Trischler, Kaheer Suleman, Jackie Chi Kit Cheung* [[pdf](https://aclanthology.org/D19-1335.pdf)] [[project](https://github.com/ptrichel/How-Reasonable-are-Common-Sense-Reasoning-Tasks)]

### Grounded Commonsense Inference
1. **How Reasonable are Common-Sense Reasoning Tasks: A Case-Study on the Winograd Schema Challenge and SWAG** EMNLP (2019)

   *Paul Trichelair, Ali Emami, Adam Trischler, Kaheer Suleman, Jackie Chi Kit Cheung* [[pdf](https://aclanthology.org/D19-1335.pdf)] [[project](https://github.com/ptrichel/How-Reasonable-are-Common-Sense-Reasoning-Tasks)]

### Commonsense Question Answering
1. **Explain Yourself! Leveraging Language Models for Commonsense Reasoning** ACL (2019)

   *Nazneen Fatema Rajani, Bryan McCann, Caiming Xiong, Richard Socher* [[pdf](https://aclanthology.org/P19-1487.pdf)] [[project](https://github.com/salesforce/cos-e)]

### If-Then
1. **Modeling Event Background for If-Then Commonsense Reasoning Using Context-aware Variational Autoencoder** EMNLP (2019)

   *Li Du, Xiao Ding, Ting Liu, Zhongyang Li* [[pdf](https://aclanthology.org/D19-1270.pdf)] [[project](https://github.com/sjcfr/CWVAE)]

### Dataset
1. **Explain Yourself! Leveraging Language Models for Commonsense Reasoning** ACL (2019)

   *Nazneen Fatema Rajani, Bryan McCann, Caiming Xiong, Richard Socher* [[pdf](https://aclanthology.org/P19-1487.pdf)] [[project](https://github.com/salesforce/cos-e)]

2. **SOCIAL IQA: Commonsense Reasoning about Social Interactions** EMNLP (2019)

   *Maarten Sap, Hannah Rashkin, Derek Chen, Ronan Le Bras, Yejin Choi* [[pdf](https://aclanthology.org/D19-1454.pdf)] [[project](https://tinyurl.com/socialiqa)]

3. **Cosmos QA: Machine Reading Comprehension with Contextual Commonsense Reasoning** EMNLP (2019)

   *Lifu Huang, Ronan Le Bras, Chandra Bhagavatula, Yejin Choi* [[pdf](http://aclanthology.lst.uni-saarland.de/D19-1243.pdf)] [[project](https://wilburone.github.io/cosmos)]

4. **WIQA: A dataset for "What if..." reasoning over procedural text** EMNLP (2019)

   *Niket Tandon, Bhavana Dalvi, Keisuke Sakaguchi, Peter Clark* [[pdf](https://aclanthology.org/D19-1629.pdf)] [[project](http://data.allenai.org/wiqa)]


## Contributor

Fei Yu
