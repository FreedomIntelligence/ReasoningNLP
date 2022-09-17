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
**Knowledge graph completion** task aims to complete the graph, while **multi-hop reasoning over KG** is the task querying in incomplete graphs, both of which require reasoning over knowledge graphs. **Temporal knowledge graph reasoning** aims to predict links in future with the past quadruples. 

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

9. **UniKER: A Unified Framework for Combining Embedding and Definite Horn Rule Reasoning for Knowledge Graph Inference** EMNLP (2021)

   *Kewei Cheng, Ziqing Yang, Ming Zhang, Yizhou Sun* [[pdf](https://aclanthology.org/2021.emnlp-main.769.pdf)]

10. **Is Multi-Hop Reasoning Really Explainable? Towards Benchmarking Reasoning Interpretability** EMNLP (2021)
   
      *Xin Lv, Yixin Cao, Lei Hou, Juanzi Li, Zhiyuan Liu, Yichi Zhang, Zelin Dai* [[pdf](https://aclanthology.org/2021.emnlp-main.700.pdf)] [[project](https://github.com/THU-KEG/BIMR)]

11. **GMH: A General Multi-hop Reasoning Model for KG Completion** EMNLP (2021)

      *Yao Zhang, Hongru Liang, Adam Jatowt, Wenqiang Lei, Xin Wei, Ning Jiang, Zhenglu Yang* [[pdf](https://aclanthology.org/2021.emnlp-main.276.pdf)]



### Multi-Hop Reasoning over KG
1. **Query2box: Reasoning over Knowledge Graphs in Vector Space Using Box Embeddings** ICLR Poster (2020)

   *Hongyu Ren, Weihua Hu, Jure Leskovec* [[pdf](https://openreview.net/pdf?id=BJgr4kSFDS)] [[project](http://snap.stanford.edu/query2box)]

2. **Beta Embeddings for Multi-Hop Logical Reasoning in Knowledge Graphs** NIPS (2020)

   *Hongyu Ren, Jure Leskovec* [[pdf](https://papers.nips.cc/paper/2020/file/e43739bba7cdb577e9e3e4e42447f5a5-Paper.pdf)] [[project](http://snap.stanford.edu/betae)]

3. **Probabilistic Entity Representation Model for Reasoning over Knowledge Graphs** NIPS (2021)

   *Nurendra Choudhary, Nikhil Rao, Sumeet Katariya, Karthik Subbian, Chandan K. Reddy* [[pdf](https://papers.nips.cc/paper/2021/file/c4d2ce3f3ebb5393a77c33c0cd95dc93-Paper.pdf)] [[project](https://github.com/Akirato/PERM-GaussianKG)]

4. **ConE: Cone Embeddings for Multi-Hop Reasoning over Knowledge Graphs** NIPS (2021)

   *Zhanqiu Zhang, Jie Wang, Jiajun Chen, Shuiwang Ji, Feng Wu* [[pdf](https://papers.nips.cc/paper/2021/file/a0160709701140704575d499c997b6ca-Paper.pdf)] [[project](https://github.com/MIRALab-USTC/QE-ConE)]



### Temporal Knowledge Graph Reasoning
1. **Explainable Subgraph Reasoning for Forecasting on Temporal Knowledge Graphs** ICLR Poster (2021)

   *Zhen Han, Peng Chen, Yunpu Ma, Volker Tresp* [[pdf](https://openreview.net/pdf?id=pGIHq1m7PU)] [[project](https://github.com/TemporalKGTeam/xERTE)]

2. **Search from History and Reason for Future: Two-stage Reasoning on Temporal Knowledge Graphs** ACL (2021)

   *Zixuan Li, Xiaolong Jin, Saiping Guan, Wei Li, Jiafeng Guo, Yuanzhuo Wang, Xueqi Cheng* [[pdf](https://aclanthology.org/2021.acl-long.365.pdf)]

3. **Complex Evolutional Pattern Learning for Temporal Knowledge Graph Reasoning** ACL (2022)

   *Zixuan Li, Saiping Guan, Xiaolong Jin, Weihua Peng, Yajuan Lyu, Yong Zhu, Long Bai, Wei Li, Jiafeng Guo, Xueqi Cheng* [[pdf](https://aclanthology.org/2022.acl-short.32.pdf)] [[project](https://github.com/Lee-zix/CEN)]



### Others
1. **Quantum Embedding of Knowledge for Reasoning** NIPS (2019)

   *Dinesh Garg, Shajith Ikbal, Santosh K. Srivastava, Harit Vishwakarma, Hima P. Karanam, L. Venkata Subramaniam* [[pdf](https://papers.nips.cc/paper/2019/file/cb12d7f933e7d102c52231bf62b8a678-Paper.pdf)] [[project](https://github.com/IBM/e2r)]

2. **Probabilistic Logic Neural Networks for Reasoning** NIPS (2019)

   *Meng Qu, Jian Tang* [[pdf](https://papers.nips.cc/paper/2019/file/13e5ebb0fa112fe1b31a1067962d74a7-Paper.pdf)]

3. **RNNLogic: Learning Logic Rules for Reasoning on Knowledge Graphs** ICLR Poster (2021)

   *Meng Qu, Junkun Chen, Louis-Pascal A. C. Xhonneux, Yoshua Bengio, Jian Tang* [[pdf](https://openreview.net/pdf?id=tGZu6DlbreV)] [[project](https://github.com/DeepGraphLearning/RNNLogic)]

4. **Efficient Probabilistic Logic Reasoning with Graph Neural Networks** ICLR Poster (2020)

   *Yuyu Zhang, Xinshi Chen, Yuan Yang, Arun Ramamurthy, Bo Li, Yuan Qi, Le Song* [[pdf](https://openreview.net/pdf?id=rJg76kStwH)]







## Mathematical Reasoning
Mathematics is a game of symbols and symbol manipulation rules full of reasoning, which makes it a natural problem to test AI's ability of reasoning. **Math word problem** aims to answer mathematical questions described by natural language text. **Automated theorem proving** focuses on theoretical proving. **Numerical reasoning** aims to solve problems that requires numerical calculation (e.g. addition, sorting and counting) over numerical evidence scattered in text or tables. 

### Math Word Problem
1. **Semantically-Aligned Equation Generation for Solving and Reasoning Math Word Problems** NAACL (2019)

   *Ting-Rui Chiang, Yun-Nung Chen* [[pdf](https://aclanthology.org/N19-1272.pdf)] [[project](https://github/MiuLab/E2EMathSolver)]

2. **Measuring and Improving BERT's Mathematical Abilities by Predicting the Order of Reasoning** ACL (2021)

   *Piotr Piekos, Mateusz Malinowski, Henryk Michalewski* [[pdf](https://aclanthology.org/2021.acl-short.49.pdf)]

3. **Learning to Reason Deductively: Math Word Problem Solving as Complex Relation Extraction** ACL (2022)

   *Zhanming Jie, Jierui Li, Wei Lu* [[pdf](https://aclanthology.org/2022.acl-long.410.pdf)] [[project](https://github.com/allanj/Deductive-MWP)]


### Automated Theorem Proving
1. **Mathematical Reasoning via Self-supervised Skip-tree Training** ICLR Spotlight (2021)

   *Markus Norman Rabe, Dennis Lee, Kshitij Bansal, Christian Szegedy* [[pdf](https://openreview.net/pdf?id=YmqAnY0CMEy)]

2. **LIME: Learning Inductive Bias for Primitives of Mathematical Reasoning** ICML (2021)

   *Yuhuai Wu, Markus N. Rabe, Wenda Li, Jimmy Ba, Roger B. Grosse, Christian Szegedy* [[pdf](http://proceedings.mlr.press/v139/wu21c/wu21c.pdf)] [[project](https://github.com/tonywu95/LIME)]



### Numerical Reasoning
1. **NumNet: Machine Reading Comprehension with Numerical Reasoning** EMNLP (2019)

   *Qiu Ran, Yankai Lin, Peng Li, Jie Zhou, Zhiyuan Liu* [[pdf](https://aclanthology.org/D19-1251.pdf)] [[project](https://github.com/ranqiu92/NumNet)]

2. **Question Directed Graph Attention Network for Numerical Reasoning over Text** EMNLP (2020)

   *Kunlong Chen, Weidi Xu, Xingyi Cheng, Zou Xiaochuan, Yuyu Zhang, Le Song, Taifeng Wang, Yuan Qi, Wei Chu* [[pdf](https://aclanthology.org/2020.emnlp-main.549.pdf)]

3. **Injecting Numerical Reasoning Skills into Language Models** ACL (2020)

   *Mor Geva, Ankit Gupta, Jonathan Berant* [[pdf](https://aclanthology.org/2020.acl-main.89.pdf)] [[project](https://github.com/ag1988/injecting_numeracy)]

4. **Neural Module Networks for Reasoning over Text** ICLR Poster (2020)

   *Nitish Gupta, Kevin Lin, Dan Roth, Sameer Singh, Matt Gardner* [[pdf](https://openreview.net/pdf?id=SygWvAVFPr)] [[project](http://cogcomp.org/page/publication_view/899)]

5. **OPERA: Operation-Pivoted Discrete Reasoning over Text** NAACL (2022)

   *Yongwei Zhou, Junwei Bao, Chaoqun Duan, Haipeng Sun, Jiahui Liang, Yifan Wang, Jing Zhao, Youzheng Wu, Xiaodong He, Tiejun Zhao* [[pdf](https://aclanthology.org/2022.naacl-main.119.pdf)] [[project](https://github.com/JD-AI-Research-NLP/OPERA)]

6. **FORTAP: Using Formulas for Numerical-Reasoning-Aware Table Pretraining** ACL (2022)

   *Zhoujun Cheng, Haoyu Dong, Ran Jia, Pengfei Wu, Shi Han, Fan Cheng, Dongmei Zhang* [[pdf](https://aclanthology.org/2022.acl-long.82.pdf)] [[project](https://github.com/microsoft/TUTA_table_understanding)]

7. **Incorporating External Knowledge to Enhance Tabular Reasoning** NAACL (2021)

   *J. Neeraja, Vivek Gupta, Vivek Srikumar* [[pdf](https://aclanthology.org/2021.naacl-main.224.pdf)] [[project](https://github.com/utahnlp/knowledge_infotabs)]

8. **Numerical reasoning in machine reading comprehension tasks: are we there yet?** EMNLP (2021)

   *Hadeel Al-Negheimish, Pranava Madhyastha, Alessandra Russo* [[pdf](https://aclanthology.org/2021.emnlp-main.759.pdf)]


### Benchmarks & Datasets
1. **Analysing Mathematical Reasoning Abilities of Neural Models** ICLR Poster (2019)

   *David Saxton, Edward Grefenstette, Felix Hill, Pushmeet Kohli* [[pdf](https://openreview.net/pdf?id=H1gR5iR5FX)] [[project](https://github.com/deepmind/mathematics_dataset)]

2. **HOList: An Environment for Machine Learning of Higher-Order Theorem Proving** ICML (2019)

   *Kshitij Bansal, Sarah M. Loos, Markus N. Rabe, Christian Szegedy, Stewart Wilcox* [[pdf](http://proceedings.mlr.press/v97/bansal19a/bansal19a.pdf)] [[project](http://deephol.org/t)]

3. **IsarStep: a Benchmark for High-level Mathematical Reasoning** ICLR Poster (2021)

   *Wenda Li, Lei Yu, Yuhuai Wu, Lawrence C. Paulson* [[pdf](https://openreview.net/pdf?id=Pzj6fzU6wkj)] [[project](https://github.com/Wenda302/IsarStep)]

4. **DROP: A Reading Comprehension Benchmark Requiring Discrete Reasoning Over Paragraphs** EMNLP (2019)

   *Dheeru Dua, Yizhong Wang, Pradeep Dasigi, Gabriel Stanovsky, Sameer Singh, Matt Gardner* [[pdf](https://aclanthology.org/N19-1246.pdf)] [[project](https://allennlp.org/drop)]

5. **Towards Table-to-Text Generation with Numerical Reasoning** ACL (2021)

   *Lya Hulliyyatus Suadaa, Hidetaka Kamigaito, Kotaro Funakoshi, Manabu Okumura, Hiroya Takamura* [[pdf](https://aclanthology.org/2021.acl-long.115.pdf)] [[project](https://github.com/titech-nlp/numeric-nlg)]

6. **SciGen: a Dataset for Reasoning-Aware Text Generation from Scientific Tables** NIPS (2021)

   *Nafise Sadat Moosavi, Andreas Rücklé, Dan Roth, Iryna Gurevych* [[pdf](https://datasets-benchmarks-proceedings.neurips.cc/paper/2021/file/149e9677a5989fd342ae44213df68868-Paper-round2.pdf)] [[project](https://github.com/UKPLab/SciGen)]

7. **MULTIHIERTT: Numerical Reasoning over Multi Hierarchical Tabular and Textual Data** ACL (2022)

   *Yilun Zhao, Yunxiang Li, Chenying Li, Rui Zhang* [[pdf](https://aclanthology.org/2022.acl-long.454.pdf)] [[project](https://github.com/psunlpgroup/MultiHiertt)]

8. **FINQA: A Dataset of Numerical Reasoning over Financial Data** EMNLP (2021)

   *Zhiyu Chen, Wenhu Chen, Charese Smiley, Sameena Shah, Iana Borova, Dylan Langdon, Reema Moussa, Matt Beane, Ting-Hao Huang, Bryan R. Routledge, William Yang Wang* [[pdf](https://aclanthology.org/2021.emnlp-main.300.pdf)] [[project](https://github.com/czyssrs/FinQA)]

9. **NUMGLUE: A Suite of Fundamental yet Challenging Mathematical Reasoning Tasks** ACL (2022)

   *Swaroop Mishra, Arindam Mitra, Neeraj Varshney, Bhavdeep Singh Sachdeva, Peter Clark, Chitta Baral, Ashwin Kalyan* [[pdf](https://aclanthology.org/2022.acl-long.246.pdf)] [[project](https://allenai.org/data/numglue)]

10. **Inter-GPS: Interpretable Geometry Problem Solving with Formal Language and Symbolic Reasoning** ACL (2021)

      *Pan Lu, Ran Gong, Shibiao Jiang, Liang Qiu, Siyuan Huang, Xiaodan Liang, Song-Chun Zhu* [[pdf](https://aclanthology.org/2021.acl-long.528.pdf)] [[project](https://lupantech.github.io/inter-gps)]


### Others
1. **Mathematical Reasoning in Latent Space** ICLR Oral (2020)

   *Dennis Lee, Christian Szegedy, Markus N. Rabe, Sarah M. Loos, Kshitij Bansal* [[pdf](https://openreview.net/pdf?id=Ske31kBtPr)]

2. **GraphMR: Graph Neural Network for Mathematical Reasoning** ACL (2021)

      *Weijie Feng, Binbin Liu, Dongpeng Xu, Qilong Zheng, Yun Xu* [[pdf](https://aclanthology.org/2021.emnlp-main.273.pdf)] [[project](https://github.com/nhpcc502/GraphMR)]



















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
