# ReasoningNLP
Paper list on reasoning in NLP. Here we mainly collect papers about datasets and methods using PLMs. (The collection is under the progress)

## Table Of Contents

- [Large Languague Model](#large-languague-model)
- [Logical Reasoning](#logical-reasoning)
- [Natural Language Inference](#natural-language-inference)
- [Commonsense Reasoning](#commonsense-reasoning)
- [Multi-hop Question Answering](#multi-hop-question-answering)
- [Fact Verification](#fact-verification)
- [Knowledge Graph Reasoning](#knowledge-graph-reasoning)
- [Mathematical Reasoning](#mathematical-reasoning)


## Large Languague Model
1. **Show Your Work: Scratchpads for Intermediate Computation with Language Models** arXiv (2021)

   *Maxwell Nye, Anders Johan Andreassen, Guy Gur-Ari, Henryk Michalewski, Jacob Austin, David Bieber, David Dohan, Aitor Lewkowycz, Maarten Bosma, David Luan, Charles Sutton, Augustus Odena* [[pdf](https://arxiv.org/pdf/2112.00114.pdf)]

2. **Chain of Thought Prompting Elicits Reasoning in Large Language Models** arXiv (2022)

   *Jason Wei, Xuezhi Wang, Dale Schuurmans, Maarten Bosma, Brian Ichter, Fei Xia, Ed Chi, Quoc Le, Denny Zhou* [[pdf](https://arxiv.org/pdf/2201.11903.pdf)] [[project](https://github.com/jasonwei20/chain-of-thought-prompting)]

3. **Self-Consistency Improves Chain of Thought Reasoning in Language Models** arXiv (2022)

   *Xuezhi Wang, Jason Wei, Dale Schuurmans, Quoc Le, Ed Chi, Sharan Narang, Aakanksha Chowdhery, Denny Zhou* [[pdf](https://arxiv.org/pdf/2203.11171.pdf)]

4. **STaR: Bootstrapping Reasoning With Reasoning** arXiv (2022)

   *Eric Zelikman, Yuhuai Wu, Jesse Mu, Noah D. Goodman* [[pdf](https://arxiv.org/pdf/2203.14465.pdf)]

5. **Selection-Inference: Exploiting Large Language Models for Interpretable Logical Reasoning** arXiv (2022)

   *Antonia Creswell, Murray Shanahan, Irina Higgins* [[pdf](https://arxiv.org/pdf/2205.09712.pdf)]

6. **Least-to-Most Prompting Enables Complex Reasoning in Large Language Models** arXiv (2022)

   *Denny Zhou, Nathanael Schärli, Le Hou, Jason Wei, Nathan Scales, Xuezhi Wang, Dale Schuurmans, Olivier Bousquet, Quoc Le, Ed Chi* [[pdf](https://arxiv.org/pdf/2205.10625.pdf)]

7. **Large Language Models are Zero-Shot Reasoners** arXiv (2022)

   *Takeshi Kojima, Shixiang Shane Gu, Machel Reid, Yutaka Matsuo, Yusuke Iwasawa* [[pdf](https://arxiv.org/pdf/2205.11916.pdf)] [[project](https://github.com/kojima-takeshi188/zero_shot_cot)]

8. **Language models show human-like content effects on reasoning** arXiv (2022)

   *Ishita Dasgupta, Andrew K. Lampinen, Stephanie C. Y. Chan, Antonia Creswell, Dharshan Kumaran, James L. McClelland, Felix Hill* [[pdf](https://arxiv.org/pdf/2207.07051.pdf)]

9. **Language Model Cascades** arXiv (2022)

   *David Dohan, Winnie Xu, Aitor Lewkowycz, Jacob Austin, David Bieber, Raphael Gontijo Lopes, Yuhuai Wu, Henryk Michalewski, Rif A. Saurous, Jascha Sohl-dickstein, Kevin Murphy, Charles Sutton* [[pdf](https://arxiv.org/pdf/2207.10342.pdf)] [[project](https://model-cascades.github.io/)]

10. **Faithful Reasoning Using Large Language Models** arXiv (2022)

      *Antonia Creswell, Murray Shanahan* [[pdf](https://arxiv.org/pdf/2208.14271.pdf)]

11. **Language Models Are Greedy Reasoners: A Systematic Formal Analysis of Chain-of-Thought** arXiv (2022)

      *Abulhair Saparov, He He* [[pdf](https://arxiv.org/pdf/2210.01240.pdf)] [[project](https://github.com/asaparov/prontoqa)]

12. **ThinkSum: Probabilistic reasoning over sets using large language models** arXiv (2022)

      *Batu Ozturkler, Nikolay Malkin, Zhen Wang, Nebojsa Jojic* [[pdf](https://arxiv.org/pdf/2210.01293.pdf)]

13. **Measuring and Narrowing the Compositionality Gap in Language Models** arXiv (2022)

      *Ofir Press, Muru Zhang, Sewon Min, Ludwig Schmidt, Noah A. Smith, Mike Lewis* [[pdf](https://arxiv.org/pdf/2210.03350.pdf)] [[project](https://github.com/ofirpress/self-ask)]















## Logical Reasoning

### Benchmarks & Datasets
1. **Towards AI-Complete Question Answering: A Set of Prerequisite Toy Tasks** ICLR Poster (2016)

   *Jason Weston, Antoine Bordes, Sumit Chopra, Tomás Mikolov* [[pdf](https://arxiv.org/pdf/1502.05698.pdf)] [[project](http://fb.ai/babi)]

2. **Transformers as Soft Reasoners over Language** IJCAI (2020)

   *Peter Clark, Oyvind Tafjord, Kyle Richardson* [[pdf](https://www.ijcai.org/proceedings/2020/0537.pdf)] [[project](https://allenai.org/data/ruletaker)]

3. **ProofWriter: Generating Implications, Proofs, and Abductive Statements over Natural Language** ACL findings (2021)

   *Oyvind Tafjord, Bhavana Dalvi, Peter Clark* [[pdf](https://aclanthology.org/2021.findings-acl.317.pdf)] [[project](https://allenai.org/data/proofwriter)]

4. **Critical Thinking for Language Models** IWCS (2021)

   *Gregor Betz, Christian Voigt, Kyle Richardson* [[pdf](https://aclanthology.org/2021.iwcs-1.7.pdf)] [[project](https://github.com/debatelab/aacorpus)]

5. **ROBUSTLR: A Diagnostic Benchmark for Evaluating Logical Robustness of Deductive Reasoners** arXiv (2022)

   *Soumya Sanyal, Zeyi Liao, Xiang Ren* [[pdf](https://arxiv.org/pdf/2205.12598.pdf)] [[project](https://github.com/INK-USC/RobustLR)]

6. **FOLIO: Natural Language Reasoning with First-Order Logic** arXiv (2022)

   *Simeng Han, Hailey Schoelkopf, Yilun Zhao, Zhenting Qi, Martin Riddell, Luke Benson, Lucy Sun, Ekaterina Zubova, Yujie Qiao, Matthew Burtell, David Peng, Jonathan Fan, Yixin Liu, Brian Wong, Malcolm Sailor, Ansong Ni, Linyong Nan, Jungo Kasai, Tao Yu, Rui Zhang, Shafiq R. Joty, Alexander R. Fabbri, Wojciech Kryscinski, Xi Victoria Lin, Caiming Xiong, Dragomir Radev* [[pdf](https://arxiv.org/pdf/2209.00840.pdf)] [[project](https://github.com/Yale-LILY/FOLIO)]


### papers

1. **PRover: Proof Generation for Interpretable Reasoning over Rules** EMNLP (2020)

   *Swarnadeep Saha, Sayan Ghosh, Shashank Srivastava, Mohit Bansal* [[pdf](https://aclanthology.org/2020.emnlp-main.9.pdf)] [[project](https://github.com/swarnaHub/PRover)]

2. **multiPRover: Generating Multiple Proofs for Improved Interpretability in Rule Reasoning** NAACL (2021)

   *Swarnadeep Saha, Prateek Yadav, Mohit Bansal* [[pdf](https://aclanthology.org/2021.naacl-main.287.pdf)] [[project](https://github.com/swarnaHub/multiPRover)]

3. **Explainable Multi-hop Verbal Reasoning Through Internal Monologue** NAACL (2021)

   *Zhengzhong Liang, Steven Bethard, Mihai Surdeanu* [[pdf](https://aclanthology.org/2021.naacl-main.97.pdf)] [[project](https://github.com/clulab/releases/tree/master/naacl2021-evr)]

4. **ProofWriter: Generating Implications, Proofs, and Abductive Statements over Natural Language** ACL findings (2021)

   *Oyvind Tafjord, Bhavana Dalvi, Peter Clark* [[pdf](https://aclanthology.org/2021.findings-acl.317.pdf)] [[project](https://allenai.org/data/proofwriter)]

5. **FaiRR: Faithful and Robust Deductive Reasoning over Natural Language** ACL (2022)

   *Soumya Sanyal, Harman Singh, Xiang Ren* [[pdf](https://aclanthology.org/2022.acl-long.77.pdf)] [[project](https://github.com/INK-USC/FaiRR)]

6. **Interpretable Proof Generation via Iterative Backward Reasoning** NAACL (2022)

   *Hanhao Qu, Yu Cao, Jun Gao, Liang Ding, Ruifeng Xu* [[pdf](https://aclanthology.org/2022.naacl-main.216.pdf)] [[project](https://github.com/find-knowledge/IBR)]

7. **Selection-Inference: Exploiting Large Language Models for Interpretable Logical Reasoning** arXiv (2022)

   *Antonia Creswell, Murray Shanahan, Irina Higgins* [[pdf](https://arxiv.org/pdf/2205.09712.pdf)]

8. **Language models show human-like content effects on reasoning** arXiv (2022)

   *Ishita Dasgupta, Andrew K. Lampinen, Stephanie C. Y. Chan, Antonia Creswell, Dharshan Kumaran, James L. McClelland, Felix Hill* [[pdf](https://arxiv.org/pdf/2207.07051.pdf)]

9. **Faithful Reasoning Using Large Language Models** arXiv (2022)

   *Antonia Creswell, Murray Shanahan* [[pdf](https://arxiv.org/pdf/2208.14271.pdf)]

10. **Language Models Are Greedy Reasoners: A Systematic Formal Analysis of Chain-of-Thought** arXiv (2022)

      *Abulhair Saparov, He He* [[pdf](https://arxiv.org/pdf/2210.01240.pdf)] [[project](https://github.com/asaparov/prontoqa)]





















## Natural Language Inference

### Benchmarks & Datasets

1. **A large annotated corpus for learning natural language inference** EMNLP (2015)

   *Samuel R. Bowman, Gabor Angeli, Christopher Potts, Christopher D. Manning* [[pdf](https://aclanthology.org/D15-1075.pdf)] [[project](nlp.stanford.edu/projects/snli/)]

2. **e-SNLI: Natural Language Inference with Natural Language Explanations** NIPS (2018)

   *Oana-Maria Camburu, Tim Rocktäschel, Thomas Lukasiewicz, Phil Blunsom* [[pdf](https://proceedings.neurips.cc/paper/2018/file/4c7a167bb329bd92580a99ce422d6fa6-Paper.pdf)] [[project](https://github.com/OanaMariaCamburu/e-SNLI)]

3. **Natural Language Inference from Multiple Premises** IJCNLP (2017)

   *Alice Lai, Yonatan Bisk, Julia Hockenmaier* [[pdf](https://aclanthology.org/I17-1011.pdf)] [[project](https://github.com/aylai/MultiPremiseEntailment)]

4. **A Broad-Coverage Challenge Corpus for Sentence Understanding through Inference** NAACL (2018)

   *Adina Williams, Nikita Nangia, Samuel R. Bowman* [[pdf](https://aclanthology.org/N18-1101.pdf)] [[project](https://cims.nyu.edu/~sbowman/multinli/)]

5. **XNLI: Evaluating Cross-lingual Sentence Representations** EMNLP (2018)

   *Alexis Conneau, Ruty Rinott, Guillaume Lample, Adina Williams, Samuel R. Bowman, Holger Schwenk, Veselin Stoyanov* [[pdf](https://aclanthology.org/D18-1269.pdf)] [[project](https://github.com/facebookresearch/XNLI/)]

6. **SCITAIL: A Textual Entailment Dataset from Science Question Answering** AAAI (2018)

   *Tushar Khot, Ashish Sabharwal, Peter Clark* [[pdf](http://ai2-website.s3.amazonaws.com/team/ashishs/scitail-aaai2018.pdf)] [[project](http://data.allenai.org/scitail)]

7. **Breaking NLI Systems with Sentences that Require Simple Lexical Inferences** ACL (2018)

   *Max Glockner, Vered Shwartz, Yoav Goldberg* [[pdf](https://aclanthology.org/P18-2103.pdf)] [[project](https://github.com/BIU-NLP/Breaking_NLI)]

8. **HELP: A Dataset for Identifying Shortcomings of Neural Models in Monotonicity Reasoning** NAACL (2019)

   *Hitomi Yanaka, Koji Mineshima, Daisuke Bekki, Kentaro Inui, Satoshi Sekine, Lasha Abzianidze, Johan Bos* [[pdf](https://aclanthology.org/S19-1027.pdf)] [[project](https://github.com/verypluming/HELP)]

9. **Can neural networks understand monotonicity reasoning?** ACL workshop (2019)

   *Hitomi Yanaka, Koji Mineshima, Daisuke Bekki, Kentaro Inui, Satoshi Sekine, Lasha Abzianidze, Johan Bos* [[pdf](https://aclanthology.org/W19-4804.pdf)] [[project](https://github.com/verypluming/MED)]

10. **Probing Natural Language Inference Models through Semantic Fragments** AAAI (2020)

      *Kyle Richardson, Hai Hu, Lawrence S. Moss, Ashish Sabharwal* [[pdf](https://arxiv.org/pdf/1909.07521.pdf)] [[project](https://github.com/yakazimir/semantic_fragments)]

11. **Are Natural Language Inference Models IMPPRESsive? Learning IMPlicature and PRESupposition** ACL (2020)

      *Paloma Jeretic, Alex Warstadt, Suvrat Bhooshan, Adina Williams* [[pdf](https://aclanthology.org/2020.acl-main.768.pdf)] [[project](https://github.com/fairinternal/Imppres)]

12. **ConjNLI: Natural Language Inference Over Conjunctive Sentences** EMNLP (2020)

      *Swarnadeep Saha, Yixin Nie, Mohit Bansal* [[pdf](https://aclanthology.org/2020.emnlp-main.661.pdf)] [[project](https://github.com/swarnaHub/ConjNLI)]

13. **What Can We Learn from Collective Human Opinions on Natural Language Inference Data?** EMNLP (2020)

      *Yixin Nie, Xiang Zhou, Mohit Bansal* [[pdf](https://aclanthology.org/2020.emnlp-main.734.pdf)] [[project](https://github.com/easonnie/ChaosNLI)]

14. **Figurative Language in Recognizing Textual Entailment** ACL findings (2021)

      *Tuhin Chakrabarty, Debanjan Ghosh, Adam Poliak, Smaranda Muresan* [[pdf](https://aclanthology.org/2021.findings-acl.297.pdf)] [[project](https://github.com/tuhinjubcse/Figurative-NLI)]

15. **DocNLI: A Large-scale Dataset for Document-level Natural Language Inference** ACL findings (2021)

      *Wenpeng Yin, Dragomir R. Radev, Caiming Xiong* [[pdf](https://aclanthology.org/2021.findings-acl.435.pdf)] [[project](https://github.com/salesforce/DocNLI)]

16. **ContractNLI: A Dataset for Document-level Natural Language Inference for Contracts** EMNLP findings (2021)

      *Yuta Koreeda, Christopher D. Manning* [[pdf](https://aclanthology.org/2021.findings-emnlp.164.pdf)] [[project](https://stanfordnlp.github.io/contract-nli/)]

17. **SCINLI: A Corpus for Natural Language Inference on Scientific Text** ACL (2022)

      *Mobashir Sadat, Cornelia Caragea* [[pdf](https://aclanthology.org/2022.acl-long.511.pdf)] [[project](https://github.com/msadat3/SciNLI)]

### papers

1. **Right for the Wrong Reasons: Diagnosing Syntactic Heuristics in Natural Language Inference** ACL (2019)

   *Tom McCoy, Ellie Pavlick, Tal Linzen* [[pdf](https://aclanthology.org/P19-1334.pdf)] [[project](https://github.com/tommccoy1/hans)]

2. **Evaluating BERT for natural language inference: a case study on the CommitmentBank** EMNLP (2019)

   *Nanjiang Jiang, Marie-Catherine de Marneffe* [[pdf](https://aclanthology.org/D19-1630.pdf)]

3. **NILE : Natural Language Inference with Faithful Natural Language Explanations** ACL (2020)

   *Sawan Kumar, Partha P. Talukdar* [[pdf](https://aclanthology.org/2020.acl-main.771.pdf)] [[project](https://github.com/SawanKumar28/nile)]

4. **Do Neural Models Learn Systematicity of Monotonicity Inference in Natural Language?** ACL (2020)

   *Hitomi Yanaka, Koji Mineshima, Daisuke Bekki, Kentaro Inui* [[pdf](http://aclanthology.lst.uni-saarland.de/2020.acl-main.543.pdf)] [[project](https://github.com/verypluming/systematicity)]

5. **Uncertain Natural Language Inference** ACL (2020)

   *Tongfei Chen, Zhengping Jiang, Adam Poliak, Keisuke Sakaguchi, Benjamin Van Durme* [[pdf](https://aclanthology.org/2020.acl-main.774.pdf)] [[project](http://nlp.jhu.edu/unli)]

6. **Discriminatively-Tuned Generative Classifiers for Robust Natural Language Inference** EMNLP (2021)

   *Xiaoan Ding, Tianyu Liu, Baobao Chang, Zhifang Sui, Kevin Gimpel* [[pdf](https://aclanthology.org/2020.emnlp-main.657.pdf)]

7. **Language Models for Lexical Inference in Context** EACL (2021)

   *Martin Schmitt, Hinrich Schütze* [[pdf](https://aclanthology.org/2021.eacl-main.108.pdf)] [[project](https://github.com/mnschmit/lm-lexical-inference)]

8. **Identifying inherent disagreement in natural language inference** NAACL (2021)

   *Xinliang Frederick Zhang, Marie-Catherine de Marneffe* [[pdf](https://aclanthology.org/2021.naacl-main.390.pdf)] [[project](https://github.com/FrederickXZhang/FgNLI)]

9. **KACE: Generating Knowledge Aware Contrastive Explanations for Natural Language Inference** ACL (2021)

   *Qianglong Chen, Feng Ji, Xiangji Zeng, Feng-Lin Li, Ji Zhang, Haiqing Chen, Yin Zhang* [[pdf](https://aclanthology.org/2021.acl-long.196.pdf)] [[project](https://github.com/AI4NLP/KACE)]

10. **Alignment Rationale for Natural Language Inference** ACL (2021)

      *Zhongtao Jiang, Yuanzhe Zhang, Zhao Yang, Jun Zhao, Kang Liu* [[pdf](https://aclanthology.org/2021.acl-long.417.pdf)] [[project](https://github.com/changmenseng/arec)]

11. **Investigating Transfer Learning in Multilingual Pre-trained Language Models through Chinese Natural Language Inference** ACL findings (2021)

      *Hai Hu, He Zhou, Zuoyu Tian, Yiwen Zhang, Yina Patterson, Yanting Li, Yixin Nie, Kyle Richardson* [[pdf](https://aclanthology.org/2021.findings-acl.331.pdf)] [[project](https://github.com/huhailinguist/ChineseNLIProbing)]

12. **Entailment Graph Learning with Textual Entailment and Soft Transitivity** ACL (2022)

      *Zhibin Chen, Yansong Feng, Dongyan Zhao* [[pdf](https://aclanthology.org/2022.acl-long.406.pdf)] [[project](https://github.com/ZacharyChenpk/EGT2)]

13. **Enhancing Cross-lingual Natural Language Inference by Prompt-learning from Cross-lingual Templates** ACL (2022)

      *Kunxun Qi, Hai Wan, Jianfeng Du, Haolan Chen* [[pdf](https://aclanthology.org/2022.acl-long.134.pdf)] [[project](https://github.com/qikunxun/PCT)]

14. **Generating Data to Mitigate Spurious Correlations in Natural Language Inference Datasets** ACL (2022)

      *Yuxiang Wu, Matt Gardner, Pontus Stenetorp, Pradeep Dasigi* [[pdf](https://aclanthology.org/2022.acl-long.190.pdf)] [[project](https://github.com/jimmycode/gen-debiased-nli)]

15. **Generating Intermediate Steps for NLI with Next-Step Supervision** arXiv (2022)

      *Deepanway Ghosal, Somak Aditya, Monojit Choudhury* [[pdf](https://arxiv.org/pdf/2208.14641.pdf)]
























## Commonsense Reasoning

### Benchmarks & Datasets
1. **Choice of Plausible Alternatives:An Evaluation of Commonsense Causal Reasoning** AAAI (2011)

   *Melissa Roemmele, Cosmin Adrian Bejan, Andrew S. Gordon* [[pdf](https://people.ict.usc.edu/~gordon/publications/AAAI-SPRING11A.PDF)] [[project](https://people.ict.usc.edu/~gordon/copa.html)]

2. **A Corpus and Cloze Evaluation for Deeper Understanding of Commonsense Stories** NAACL (2016)

   *Nasrin Mostafazadeh, Nathanael Chambers, Xiaodong He, Devi Parikh, Dhruv Batra, Lucy Vanderwende, Pushmeet Kohli, James F. Allen* [[pdf](https://aclanthology.org/N16-1098.pdf)] [[project](https://www.cs.rochester.edu/nlp/rocstories/)]

3. **Ordinal Common-sense Inference** TACL (2017)

   *Sheng Zhang, Rachel Rudinger, Kevin Duh, Benjamin Van Durme* [[pdf](https://aclanthology.org/Q17-1027.pdf)] [[project](https://github.com/sheng-z/JOCI)]

4. **Think you have Solved Question Answering? Try ARC, the AI2 Reasoning Challenge** arXiv (2018)

   *Peter Clark, Isaac Cowhey, Oren Etzioni, Tushar Khot, Ashish Sabharwal, Carissa Schoenick, Oyvind Tafjord* [[pdf](https://arxiv.org/pdf/1803.05457.pdf)] [[project](http://data.allenai.org/arc)]

5. **The Argument Reasoning Comprehension Task: Identification and Reconstruction of Implicit Warrants** NAACL (2018)

   *Ivan Habernal, Henning Wachsmuth, Iryna Gurevych, Benno Stein* [[pdf](https://aclanthology.org/N18-1175.pdf)] [[project](https://github.com/UKPLab/argumentreasoning-comprehension-task/)]

6. **SWAG: A Large-Scale Adversarial Dataset for Grounded Commonsense Inference** EMNLP (2018)

   *Rowan Zellers, Yonatan Bisk, Roy Schwartz, Yejin Choi* [[pdf](http://aclanthology.lst.uni-saarland.de/D18-1009.pdf)] [[project](https://rowanzellers.com/swag/)]

7. **Can a Suit of Armor Conduct Electricity? A New Dataset for Open Book Question Answering** EMNLP (2018)

   *Todor Mihaylov, Peter Clark, Tushar Khot, Ashish Sabharwal* [[pdf](http://aclanthology.lst.uni-saarland.de/D18-1260.pdf)] [[project](http://data.allenai.org/OpenBookQA)]

8. **CommonsenseQA: A Question Answering Challenge Targeting Commonsense Knowledge** NAACL (2019)

   *Alon Talmor, Jonathan Herzig, Nicholas Lourie, Jonathan Berant* [[pdf](https://aclanthology.org/N19-1421.pdf)] [[project](www.tau-nlp.org/commonsenseqa)]

9. **Probing Neural Network Comprehension of Natural Language Arguments** ACL (2019)

   *Timothy Niven, Hung-Yu Kao* [[pdf](https://aclanthology.org/P19-1459.pdf)] [[project](https://github.com/IKMLab/arct2)]

10. **HellaSwag: Can a Machine Really Finish Your Sentence?** ACL (2019)

      *Rowan Zellers, Ari Holtzman, Yonatan Bisk, Ali Farhadi, Yejin Choi* [[pdf](http://aclanthology.lst.uni-saarland.de/P19-1472.pdf)] [[project](https://rowanzellers.com/hellaswag/)]

11. **Explain Yourself! Leveraging Language Models for Commonsense Reasoning** ACL (2019)

      *Nazneen Fatema Rajani, Bryan McCann, Caiming Xiong, Richard Socher* [[pdf](https://aclanthology.org/P19-1487.pdf)] [[project](https://github.com/salesforce/cos-e)]

12. **Does it Make Sense? And Why? A Pilot Study for Sense Making and Explanation** ACL (2019)

      *Cunxiang Wang, Shuailong Liang, Yue Zhang, Xiaonan Li, Tian Gao* [[pdf](https://aclanthology.org/P19-1393.pdf)] [[project](https://github.com/wangcunxiang/Sen-Making-and-Explanation)]

13. **WIQA: A dataset for "What if..." reasoning over procedural text** EMNLP (2019)

      *Niket Tandon, Bhavana Dalvi, Keisuke Sakaguchi, Peter Clark, Antoine Bosselut* [[pdf](https://aclanthology.org/D19-1629.pdf)] [[project](http://data.allenai.org/wiqa/)]

14. **SOCIAL IQA: Commonsense Reasoning about Social Interactions** EMNLP (2019)

      *Maarten Sap, Hannah Rashkin, Derek Chen, Ronan Le Bras, Yejin Choi* [[pdf](https://aclanthology.org/D19-1454.pdf)] [[project](https://tinyurl.com/socialiqa)]

15. **Cosmos QA: Machine Reading Comprehension with Contextual Commonsense Reasoning** EMNLP (2019)

      *Lifu Huang, Ronan Le Bras, Chandra Bhagavatula, Yejin Choi* [[pdf](http://aclanthology.lst.uni-saarland.de/D19-1243.pdf)] [[project](https://wilburone.github.io/cosmos)]

16. **Counterfactual Story Reasoning and Generation** EMNLP (2019)

      *Lianhui Qin, Antoine Bosselut, Ari Holtzman, Chandra Bhagavatula, Elizabeth Clark, Yejin Choi* [[pdf](http://aclanthology.lst.uni-saarland.de/D19-1509.pdf)] [[project](https://github.com/qkaren/Counterfactual-StoryRW)]

17. **PIQA: Reasoning about Physical Commonsense in Natural Language** AAAI (2020)

      *Yonatan Bisk, Rowan Zellers, Ronan Le Bras, Jianfeng Gao, Yejin Choi* [[pdf](https://yonatanbisk.com/piqa/)] [[project](http://abductivecommonsense.xyz/)]

18. **QASC: A Dataset for Question Answering via Sentence Composition** AAAI (2020)

      *Tushar Khot, Peter Clark, Michal Guerquin, Peter Jansen, Ashish Sabharwal* [[pdf](https://arxiv.org/pdf/1910.11473.pdf)] [[project](https://github.com/allenai/qasc)]

19. **Abductive Commonsense Reasoning** ICLR Poster (2020)

      *Chandra Bhagavatula, Ronan Le Bras, Chaitanya Malaviya, Keisuke Sakaguchi, Ari Holtzman, Hannah Rashkin, Doug Downey, Wen-tau Yih, Yejin Choi* [[pdf](https://openreview.net/pdf?id=Byg1v1HKDB)] [[project](http://abductivecommonsense.xyz/)]

20. **Social Bias Frames: Reasoning about Social and Power Implications of Language** ACL (2020)

      *Maarten Sap, Saadia Gabriel, Lianhui Qin, Dan Jurafsky, Noah A. Smith, Yejin Choi* [[pdf](https://aclanthology.org/2020.acl-main.486.pdf)] [[project](http://tinyurl.com/social-bias-frames)]

21. **Learning to Explain: Datasets and Models for Identifying Valid Reasoning Chains in Multihop Question-Answering** EMNLP (2020)

      *Harsh Jhamtani, Peter Clark* [[pdf](http://aclanthology.lst.uni-saarland.de/2020.emnlp-main.10.pdf)] [[project](https://allenai.org/data/eqasc)]

22. **Reasoning about Goals, Steps, and Temporal Ordering with WikiHow** EMNLP (2020)

      *Li Zhang, Qing Lyu, Chris Callison-Burch* [[pdf](https://aclanthology.org/2020.emnlp-main.374v2.pdf)] [[project](https://github.com/zharry29/wikihow-goal-step)]

23. **ProtoQA: A Question Answering Dataset for Prototypical Common-Sense Reasoning** EMNLP (2020)

      *Michael Boratko, Xiang Li, Tim O'Gorman, Rajarshi Das, Dan Le, Andrew McCallum* [[pdf](https://aclanthology.org/2020.emnlp-main.85.pdf)] [[project](https://github.com/iesl/protoqa-data)]

24. **XCOPA: A Multilingual Dataset for Causal Commonsense Reasoning** EMNLP (2020)

      *Edoardo Maria Ponti, Goran Glavas, Olga Majewska, Qianchu Liu, Ivan Vulic, Anna Korhonen* [[pdf](https://aclanthology.org/2020.emnlp-main.185.pdf)] [[project](http://github.com/cambridgeltl/xcopa)]

25. **CommonGen: A Constrained Text Generation Challenge for Generative Commonsense Reasoning** EMNLP findings (2020)

      *Bill Yuchen Lin, Wangchunshu Zhou, Ming Shen, Pei Zhou, Chandra Bhagavatula, Yejin Choi, Xiang Ren* [[pdf](https://aclanthology.org/2020.findings-emnlp.165.pdf)] [[project](http://inklab.usc.edu/CommonGen/)]

26. **Conversational Neuro-Symbolic Commonsense Reasoning** AAAI (2021)

      *Forough Arabshahi, Jennifer Lee, Mikayla Gawarecki, Kathryn Mazaitis, Amos Azaria, Tom M. Mitchell* [[pdf](https://ojs.aaai.org/index.php/AAAI/article/view/16623/16430)] [[project](https://github.com/ForoughA/CORGI)]

27. **Temporal Reasoning on Implicit Events from Distant Supervision** NAACL (2021)

      *Ben Zhou, Kyle Richardson, Qiang Ning, Tushar Khot, Ashish Sabharwal, Dan Roth* [[pdf](https://aclanthology.org/2021.naacl-main.107.pdf)] [[project](https://leaderboard.allenai.org/tracie)]

28. **Explanations for CommonsenseQA: New Dataset and Models** ACL (2021)

      *Shourya Aggarwal, Divyanshu Mandowara, Vishwajeet Agrawal, Dinesh Khandelwal, Parag Singla, Dinesh Garg* [[pdf](https://aclanthology.org/2021.acl-long.238.pdf)] [[project](https://github.com/dair-iitd/ECQA-Dataset)]

29. **Common Sense Beyond English: Evaluating and Improving Multilingual Language Models for Commonsense Reasoning** ACL (2021)

      *Bill Yuchen Lin, Seyeon Lee, Xiaoyang Qiao, Xiang Ren* [[pdf](https://aclanthology.org/2021.acl-long.102.pdf)] [[project](https://inklab.usc.edu/XCSR/)]

30. **TellMeWhy: A Dataset for Answering Why-Questions in Narratives** ACL findings (2021)

      *Yash Kumar Lal, Nathanael Chambers, Raymond J. Mooney, Niranjan Balasubramanian* [[pdf](https://aclanthology.org/2021.findings-acl.53v2.pdf)] [[project](http://lunr.cs.stonybrook.edu/tellmewhy)]

31. **Moral Stories: Situated Reasoning about Norms, Intents, Actions, and their Consequences** EMNLP (2021)

      *Denis Emelin, Ronan Le Bras, Jena D. Hwang, Maxwell Forbes, Yejin Choi* [[pdf](https://aclanthology.org/2021.emnlp-main.54.pdf)] [[project](https://github.com/demelin/moral_stories)]

32. **Wino-X: Multilingual Winograd Schemas for Commonsense Reasoning and Coreference Resolution** EMNLP (2021)

      *Denis Emelin, Rico Sennrich* [[pdf](https://aclanthology.org/2021.emnlp-main.670.pdf)] [[project](https://github.com/demelin/Wino-X)]

33. **Differentiable Open-Ended Commonsense Reasoning** EMNLP (2021)

      *Bill Yuchen Lin, Haitian Sun, Bhuwan Dhingra, Manzil Zaheer, Xiang Ren, William W. Cohen* [[pdf](https://aclanthology.org/2021.naacl-main.366.pdf)] [[project](https://open-csr.github.io/)]

34. **CREAK: A Dataset for Commonsense Reasoning over Entity Knowledge** NIPS (2021)

      *Yasumasa Onoe, Michael J. Q. Zhang, Eunsol Choi, Greg Durrett* [[pdf](https://datasets-benchmarks-proceedings.neurips.cc/paper/2021/file/5737c6ec2e0716f3d8a7a5c4e0de0d9a-Paper-round2.pdf)] [[project](https://www.cs.utexas.edu/~yasumasa/creak)]

35. **e-CARE: a New Dataset for Exploring Explainable Causal Reasoning** ACL (2022)

      *Li Du, Xiao Ding, Kai Xiong, Ting Liu, Bing Qin* [[pdf](https://aclanthology.org/2022.acl-long.33.pdf)] [[project](https://github.com/Waste-Wood/e-CARE/)]

36. **Misinfo Reaction Frames: Reasoning about Readers’ Reactions to News Headlines** ACL (2022)

      *Saadia Gabriel, Skyler Hallinan, Maarten Sap, Pemi Nguyen, Franziska Roesner, Eunsol Choi, Yejin Choi* [[pdf](https://aclanthology.org/2022.acl-long.222.pdf)] [[project](https://github.com/skgabriel/mrf-modeling)]

37. **WikiWhy: Answering and Explaining Cause-and-Effect Questions** arXiv (2022)

      *Matthew Ho, Aditya Sharma, Justin Chang, Michael Saxon, Sharon Levy, Yujie Lu, William Yang Wang* [[pdf](https://arxiv.org/pdf/2210.12152.pdf)]

























## Multi-hop Question Answering

### Benchmarks & Datasets

1. **Constructing Datasets for Multi-hop Reading Comprehension Across Documents** TACL (2018)

   *Johannes Welbl, Pontus Stenetorp, Sebastian Riedel* [[pdf](https://aclanthology.org/Q18-1021.pdf)] [[project](http://qangaroo.cs.ucl.ac.uk/)]

2. **HOTPOTQA: A Dataset for Diverse, Explainable Multi-hop Question Answering** EMNLP (2018)

   *Zhilin Yang, Peng Qi, Saizheng Zhang, Yoshua Bengio, William Cohen, Ruslan Salakhutdinov, Christopher D. Manning* [[pdf](https://aclanthology.org/D18-1259.pdf)] [[project](https://hotpotqa.github.io/)]

3. **R4C: A Benchmark for Evaluating RC Systems to Get the Right Answer for the Right Reason** ACL (2020)

   *Naoya Inoue, Pontus Stenetorp, Kentaro Inui* [[pdf](https://aclanthology.org/2020.acl-main.602.pdf)] [[project](https://naoya-i.github.io/r4c/)]

4. **QASC: A Dataset for Question Answering via Sentence Composition** AAAI (2020)

   *Tushar Khot, Peter Clark, Michal Guerquin, Peter Jansen, Ashish Sabharwal* [[pdf](https://arxiv.org/pdf/1910.11473.pdf)] [[project](https://github.com/allenai/qasc)]

5. **Learning to Explain: Datasets and Models for Identifying Valid Reasoning Chains in Multihop Question-Answering** AAAI (2020)

   *Harsh Jhamtani, Peter Clark* [[pdf](http://aclanthology.lst.uni-saarland.de/2020.emnlp-main.10.pdf)] [[project](https://allenai.org/data/eqasc)]

6. **Constructing A Multi-hop QA Dataset for Comprehensive Evaluation of Reasoning Steps** COLING (2020)

   *Xanh Ho, Anh-Khoa Duong Nguyen, Saku Sugawara, Akiko Aizawa* [[pdf](https://aclanthology.org/2020.coling-main.580.pdf)] [[project](https://github.com/Alab-NII/2wikimultihop)]

7. **Answering Open-Domain Questions of Varying Reasoning Steps from Text** EMNLP (2021)

   *Peng Qi, Haejun Lee, Tg Sido, Christopher D. Manning* [[pdf](https://aclanthology.org/2021.emnlp-main.292.pdf)] [[project](https://beerqa.github.io/)]

### papers
1. **Understanding Dataset Design Choices for Multi-hop Reasoning** NAACL (2019)

   *Jifan Chen, Greg Durrett* [[pdf](https://aclanthology.org/N19-1405.pdf)]

2. **Question Answering by Reasoning Across Documents with Graph Convolutional Networks** NAACL (2019)

   *Nicola De Cao, Wilker Aziz, Ivan Titov* [[pdf](https://aclanthology.org/N19-1240.pdf)]

3. **BAG: Bi-directional Attention Entity Graph Convolutional Network for Multi-hop Reasoning Question Answering** NAACL (2019)

   *Yu Cao, Meng Fang, Dacheng Tao* [[pdf](https://aclanthology.org/N19-1032.pdf)] [[project](https://github.com/caoyu1991/BAG)]

4. **Dynamically Fused Graph Network for Multi-hop Reasoning** ACL (2019)

   *Lin Qiu, Yunxuan Xiao, Yanru Qu, Hao Zhou, Lei Li, Weinan Zhang, Yong Yu* [[pdf](https://aclanthology.org/P19-1617.pdf)] [[project](https://github.com/woshiyyya/DFGN-pytorch)]

5. **Multi-hop Reading Comprehension across Multiple Documents by Reasoning over Heterogeneous Graphs** ACL (2019)

   *Ming Tu, Guangtao Wang, Jing Huang, Yun Tang, Xiaodong He, Bowen Zhou* [[pdf](https://aclanthology.org/P19-1260.pdf)]

6. **Answering while Summarizing: Multi-task Learning for Multi-hop QA with Evidence Extraction** ACL (2019)

   *Kosuke Nishida, Kyosuke Nishida, Masaaki Nagata, Atsushi Otsuka, Itsumi Saito, Hisako Asano, Junji Tomita* [[pdf](https://aclanthology.org/P19-1225.pdf)]

7. **Multi-hop Reading Comprehension through Question Decomposition and Rescoring** ACL (2019)

   *Sewon Min, Victor Zhong, Luke Zettlemoyer, Hannaneh Hajishirzi* [[pdf](https://aclanthology.org/P19-1613.pdf)] [[project](https://github.com/shmsw25/DecompRC)]

8. **NLProlog: Reasoning with Weak Unification for Question Answering in Natural Language** ACL (2019)

   *Leon Weber, Pasquale Minervini, Jannes Münchmeyer, Ulf Leser, Tim Rocktäschel* [[pdf](https://aclanthology.org/P19-1618.pdf)] [[project](https://github.com/leonweber/nlprolog)]

9. **Avoiding Reasoning Shortcuts: Adversarial Evaluation, Training, and Model Development for Multi-Hop QA** ACL (2019)

   *Yichen Jiang, Mohit Bansal* [[pdf](https://aclanthology.org/P19-1262.pdf)] [[project](https://github.com/jiangycTarheel-zz/Adversarial-MultiHopQA)]

10. **Compositional Questions Do Not Necessitate Multi-hop Reasoning** ACL (2019)

      *Sewon Min, Eric Wallace, Sameer Singh, Matt Gardner, Hannaneh Hajishirzi, Luke Zettlemoyer* [[pdf](https://aclanthology.org/P19-1416.pdf)] [[project](https://github.com/shmsw25/single-hop-rc)]

11. **Self-Assembling Modular Networks for Interpretable Multi-Hop Reasoning** EMNLP (2019)

      *Yichen Jiang, Mohit Bansal* [[pdf](http://aclanthology.lst.uni-saarland.de/D19-1455.pdf)] [[project](https://github.com/jiangycTarheel/NMN-MultiHopQA)]

12. **Differentiable Reasoning over a Virtual Knowledge Base** ICLR (2020)

      *Bhuwan Dhingra, Manzil Zaheer, Vidhisha Balachandran, Graham Neubig, Ruslan Salakhutdinov, William W. Cohen* [[pdf](https://openreview.net/pdf?id=SJxstlHFPH)] [[project](http://www.cs.cmu.edu/~bdhingra/pages/drkit.html)]

13. **Learning to Retrieve Reasoning Paths over Wikipedia Graph for Question Answering** ICLR (2020)

      *Akari Asai, Kazuma Hashimoto, Hannaneh Hajishirzi, Richard Socher, Caiming Xiong* [[pdf](https://openreview.net/pdf?id=SJgVHkrYDH)] [[project](https://github.com/AkariAsai/learning_to_retrieve_reasoning_paths)]

14. **Transformer-XH: Multi-Evidence Reasoning with eXtra Hop Attention** ICLR Poster (2020)

      *Chen Zhao, Chenyan Xiong, Corby Rosset, Xia Song, Paul N. Bennett, Saurabh Tiwary* [[pdf](https://openreview.net/pdf?id=r1eIiCNYwS)] [[project](https://aka.ms/transformer-xh)]

15. **Low-Resource Generation of Multi-hop Reasoning Questions** ACL (2020)

      *Jianxing Yu, Wei Liu, Shuang Qiu, Qinliang Su, Kai Wang, Xiaojun Quan, Jian Yin* [[pdf](http://aclanthology.lst.uni-saarland.de/2020.acl-main.601.pdf)]

16. **SRLGRN: Semantic Role Labeling Graph Reasoning Network** EMNLP (2020)

      *Chen Zheng, Parisa Kordjamshidi* [[pdf](https://aclanthology.org/2020.emnlp-main.714.pdf)]

17. **Is Multihop QA in DiRe Condition? Measuring and Reducing Disconnected Reasoning** EMNLP (2020)

      *Harsh Trivedi, Niranjan Balasubramanian, Tushar Khot, Ashish Sabharwal* [[pdf](https://aclanthology.org/2020.emnlp-main.712.pdf)] [[project](https://github.com/stonybrooknlp/dire)]

18. **Answering Complex Open-Domain Questions with Multi-Hop Dense Retrieval** ICLR Poster (2021)

      *Wenhan Xiong, Xiang Lorraine Li, Srini Iyer, Jingfei Du, Patrick S. H. Lewis, William Yang Wang, Yashar Mehdad, Scott Yih, Sebastian Riedel, Douwe Kiela, Barlas Oguz* [[pdf](https://openreview.net/pdf?id=EMHoBG0avc1)] [[project](https://github.com/facebookresearch/multihop_dense_retrieval)]

19. **Multi-Step Reasoning Over Unstructured Text with Beam Dense Retrieval** NAACL (2021)

      *Chen Zhao, Chenyan Xiong, Jordan L. Boyd-Graber, Hal Daumé III* [[pdf](https://aclanthology.org/2021.naacl-main.368.pdf)] [[project](https://github.com/henryzhao5852/BeamDR)]

20. **Unsupervised Multi-hop Question Answering by Question Generation** NAACL (2021)

      *Liangming Pan, Wenhu Chen, Wenhan Xiong, Min-Yen Kan, William Yang Wang* [[pdf](https://aclanthology.org/2021.naacl-main.469.pdf)] [[project](https://github.com/teacherpeterpan/Unsupervised-Multi-hop-QA)]

21. **Robustifying Multi-hop QA through Pseudo-Evidentiality Training** ACL (2021)

      *Kyungjae Lee, Seung-won Hwang, Sang-eun Han, Dohyeon Lee* [[pdf](https://aclanthology.org/2021.acl-long.476.pdf)]

22. **Summarize-then-Answer: Generating Concise Explanations for Multi-hop Reading Comprehension** EMNLP (2021)

      *Naoya Inoue, Harsh Trivedi, Steven Sinha, Niranjan Balasubramanian, Kentaro Inui* [[pdf](https://aclanthology.org/2021.emnlp-main.490.pdf)] [[project](https://github.com/StonyBrookNLP/suqa)]

23. **Generative Context Pair Selection for Multi-hop Question Answering** EMNLP (2021)

      *Dheeru Dua, Cícero Nogueira dos Santos, Patrick Ng, Ben Athiwaratkun, Bing Xiang, Matt Gardner, Sameer Singh* [[pdf](https://aclanthology.org/2021.emnlp-main.561.pdf)] [[project](https://github.com/dDua/JointQA)]

24. **Breadth First Reasoning Graph for Multi-hop Question Answering** NAACL (2021)

      *Yongjie Huang, Meng Yang* [[pdf](https://aclanthology.org/2021.naacl-main.464.pdf)]

25. **Baleen: Robust Multi-Hop Reasoning at Scale via Condensed Retrieval** NIPS (2021)

      *Omar Khattab, Christopher Potts, Matei A. Zaharia* [[pdf](https://papers.nips.cc/paper/2021/file/e8b1cbd05f6e6a358a81dee52493dd06-Paper.pdf)] [[project](https://github.com/stanford-futuredata/Baleen)]

26. **Deep Inductive Logic Reasoning for Multi-Hop Reading Comprehension** ACL (2022)

      *Wenya Wang, Sinno Jialin Pan* [[pdf](https://aclanthology.org/2022.acl-long.343.pdf)]

27. **CQG: A Simple and Effective Controlled Generation Framework for Multi-hop Question Generation** ACL (2022)

      *Zichu Fei, Qi Zhang, Tao Gui, Di Liang, Sirui Wang, Wei Wu, Xuanjing Huang* [[pdf](https://aclanthology.org/2022.acl-long.475.pdf)] [[project](https://github.com/sion-zcfei/CQG)]

28. **Modeling Multi-hop Question Answering as Single Sequence Prediction** ACL (2022)

      *Semih Yavuz, Kazuma Hashimoto, Yingbo Zhou, Nitish Shirish Keskar, Caiming Xiong* [[pdf](https://aclanthology.org/2022.acl-long.69.pdf)]




















## Fact Verification

1. **GEAR: Graph-based Evidence Aggregating and Reasoning for Fact Verification** ACL (2019)

   *Jie Zhou, Xu Han, Cheng Yang, Zhiyuan Liu, Lifeng Wang, Changcheng Li, Maosong Sun* [[pdf](https://aclanthology.org/P19-1085.pdf)] [[project](https://github.com/thunlp/GEAR)]

2. **Topic-Aware Evidence Reasoning and Stance-Aware Aggregation for Fact Verification** ACL (2021)

   *Jiasheng Si, Deyu Zhou, Tongzhe Li, Xingyu Shi, Yulan He* [[pdf](https://aclanthology.org/2021.acl-long.128.pdf)] [[project](https://github.com/jasenchn/TARSA)]

3. **Reasoning Over Semantic-Level Graph for Fact Checking** ACL (2020)

   *Wanjun Zhong, Jingjing Xu, Duyu Tang, Zenan Xu, Nan Duan, Ming Zhou, Jiahai Wang, Jian Yin* [[pdf](https://aclanthology.org/2020.acl-main.549.pdf)]

4. **Exploring Listwise Evidence Reasoning with T5 for Fact Verification** ACL (2021)

   *Kelvin Jiang, Ronak Pradeep, Jimmy Lin* [[pdf](https://aclanthology.org/2021.acl-short.51.pdf)]

5. **Automatic Fake News Detection: Are Models Learning to Reason?** ACL (2021)

   *Casper Hansen, Christian Hansen, Lucas Chaves Lima* [[pdf](https://aclanthology.org/2021.acl-short.12.pdf)] [[project](https://github.com/casperhansen/fake-news-reasoning)]




















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

12. **Neural-Symbolic Commonsense Reasoner with Relation Predictors** ACL (2021)
   
      *Farhad Moghimifar, Lizhen Qu, Yue Zhuo, Gholamreza Haffari, Mahsa Baktashmotlagh* [[pdf](https://aclanthology.org/2021.acl-short.100.pdf)] [[project](https://github.com/farhadmfar/commonsense_reasoner)]


### Multi-Hop Reasoning over KG
1. **Query2box: Reasoning over Knowledge Graphs in Vector Space Using Box Embeddings** ICLR Poster (2020)

   *Hongyu Ren, Weihua Hu, Jure Leskovec* [[pdf](https://openreview.net/pdf?id=BJgr4kSFDS)] [[project](http://snap.stanford.edu/query2box)]

2. **Beta Embeddings for Multi-Hop Logical Reasoning in Knowledge Graphs** NIPS (2020)

   *Hongyu Ren, Jure Leskovec* [[pdf](https://papers.nips.cc/paper/2020/file/e43739bba7cdb577e9e3e4e42447f5a5-Paper.pdf)] [[project](http://snap.stanford.edu/betae)]

3. **Probabilistic Entity Representation Model for Reasoning over Knowledge Graphs** NIPS (2021)

   *Nurendra Choudhary, Nikhil Rao, Sumeet Katariya, Karthik Subbian, Chandan K. Reddy* [[pdf](https://papers.nips.cc/paper/2021/file/c4d2ce3f3ebb5393a77c33c0cd95dc93-Paper.pdf)] [[project](https://github.com/Akirato/PERM-GaussianKG)]

4. **ConE: Cone Embeddings for Multi-Hop Reasoning over Knowledge Graphs** NIPS (2021)

   *Zhanqiu Zhang, Jie Wang, Jiajun Chen, Shuiwang Ji, Feng Wu* [[pdf](https://papers.nips.cc/paper/2021/file/a0160709701140704575d499c997b6ca-Paper.pdf)] [[project](https://github.com/MIRALab-USTC/QE-ConE)]

5. **Complex Query Answering with Neural Link Predictors** ICLR Oral (2021)

   *Erik Arakelyan, Daniel Daza, Pasquale Minervini, Michael Cochez* [[pdf](https://openreview.net/pdf?id=Mos9F9kDwkz)] [[project](https://github.com/uclnlp/cqd)]


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

2. **Scalable Neural Methods for Reasoning With a Symbolic Knowledge Base** ICLR Poster (2020)

   *William W. Cohen, Haitian Sun, R. Alex Hofer, Matthew Siegler* [[pdf](https://openreview.net/pdf?id=BJlguT4YPr)]

3. **Probabilistic Logic Neural Networks for Reasoning** NIPS (2019)

   *Meng Qu, Jian Tang* [[pdf](https://papers.nips.cc/paper/2019/file/13e5ebb0fa112fe1b31a1067962d74a7-Paper.pdf)]

4. **RNNLogic: Learning Logic Rules for Reasoning on Knowledge Graphs** ICLR Poster (2021)

   *Meng Qu, Junkun Chen, Louis-Pascal A. C. Xhonneux, Yoshua Bengio, Jian Tang* [[pdf](https://openreview.net/pdf?id=tGZu6DlbreV)] [[project](https://github.com/DeepGraphLearning/RNNLogic)]

5. **Efficient Probabilistic Logic Reasoning with Graph Neural Networks** ICLR Poster (2020)

   *Yuyu Zhang, Xinshi Chen, Yuan Yang, Arun Ramamurthy, Bo Li, Yuan Qi, Le Song* [[pdf](https://openreview.net/pdf?id=rJg76kStwH)]

6. **Probabilistic Box Embeddings for Uncertain Knowledge Graph Reasoning** NAACL (2021)

   *Xuelu Chen, Michael Boratko, Muhao Chen, Shib Sankar Dasgupta, Xiang Lorraine Li, Andrew McCallum* [[pdf](https://aclanthology.org/2021.naacl-main.68.pdf)] [[project](https://github.com/stasl0217/beurre)]























## Mathematical Reasoning

### Benchmarks & Datasets
1. **Analysing Mathematical Reasoning Abilities of Neural Models** ICLR Poster (2019)

   *David Saxton, Edward Grefenstette, Felix Hill, Pushmeet Kohli* [[pdf](https://openreview.net/pdf?id=H1gR5iR5FX)] [[project](https://github.com/deepmind/mathematics_dataset)]

2. **HOList: An Environment for Machine Learning of Higher-Order Theorem Proving** ICML (2019)

   *Kshitij Bansal, Sarah M. Loos, Markus N. Rabe, Christian Szegedy, Stewart Wilcox* [[pdf](http://proceedings.mlr.press/v97/bansal19a/bansal19a.pdf)] [[project](http://deephol.org/t)]

3. **DROP: A Reading Comprehension Benchmark Requiring Discrete Reasoning Over Paragraphs** EMNLP (2019)

   *Dheeru Dua, Yizhong Wang, Pradeep Dasigi, Gabriel Stanovsky, Sameer Singh, Matt Gardner* [[pdf](https://aclanthology.org/N19-1246.pdf)] [[project](https://allennlp.org/drop)]

4. **IsarStep: a Benchmark for High-level Mathematical Reasoning** ICLR Poster (2021)

   *Wenda Li, Lei Yu, Yuhuai Wu, Lawrence C. Paulson* [[pdf](https://openreview.net/pdf?id=Pzj6fzU6wkj)] [[project](https://github.com/Wenda302/IsarStep)]

5. **Towards Table-to-Text Generation with Numerical Reasoning** ACL (2021)

   *Lya Hulliyyatus Suadaa, Hidetaka Kamigaito, Kotaro Funakoshi, Manabu Okumura, Hiroya Takamura* [[pdf](https://aclanthology.org/2021.acl-long.115.pdf)] [[project](https://github.com/titech-nlp/numeric-nlg)]

6. **Inter-GPS: Interpretable Geometry Problem Solving with Formal Language and Symbolic Reasoning** ACL (2021)

   *Pan Lu, Ran Gong, Shibiao Jiang, Liang Qiu, Siyuan Huang, Xiaodan Liang, Song-Chun Zhu* [[pdf](https://aclanthology.org/2021.acl-long.528.pdf)] [[project](https://lupantech.github.io/inter-gps)]

7. **FINQA: A Dataset of Numerical Reasoning over Financial Data** EMNLP (2021)

   *Zhiyu Chen, Wenhu Chen, Charese Smiley, Sameena Shah, Iana Borova, Dylan Langdon, Reema Moussa, Matt Beane, Ting-Hao Huang, Bryan R. Routledge, William Yang Wang* [[pdf](https://aclanthology.org/2021.emnlp-main.300.pdf)] [[project](https://github.com/czyssrs/FinQA)]

8. **SciGen: a Dataset for Reasoning-Aware Text Generation from Scientific Tables** NIPS (2021)

   *Nafise Sadat Moosavi, Andreas Rücklé, Dan Roth, Iryna Gurevych* [[pdf](https://datasets-benchmarks-proceedings.neurips.cc/paper/2021/file/149e9677a5989fd342ae44213df68868-Paper-round2.pdf)] [[project](https://github.com/UKPLab/SciGen)]

9. **MULTIHIERTT: Numerical Reasoning over Multi Hierarchical Tabular and Textual Data** ACL (2022)

   *Yilun Zhao, Yunxiang Li, Chenying Li, Rui Zhang* [[pdf](https://aclanthology.org/2022.acl-long.454.pdf)] [[project](https://github.com/psunlpgroup/MultiHiertt)]

10. **NUMGLUE: A Suite of Fundamental yet Challenging Mathematical Reasoning Tasks** ACL (2022)

      *Swaroop Mishra, Arindam Mitra, Neeraj Varshney, Bhavdeep Singh Sachdeva, Peter Clark, Chitta Baral, Ashwin Kalyan* [[pdf](https://aclanthology.org/2022.acl-long.246.pdf)] [[project](https://allenai.org/data/numglue)]


### papers
1. **Semantically-Aligned Equation Generation for Solving and Reasoning Math Word Problems** NAACL (2019)

   *Ting-Rui Chiang, Yun-Nung Chen* [[pdf](https://aclanthology.org/N19-1272.pdf)] [[project](https://github/MiuLab/E2EMathSolver)]

2. **A Multi-Type Multi-Span Network for Reading Comprehension that Requires Discrete Reasoning** EMNLP (2019)

   *Minghao Hu, Yuxing Peng, Zhen Huang, Dongsheng Li* [[pdf](https://aclanthology.org/D19-1170.pdf)] [[project](https://github.com/huminghao16/MTMSN)]

3. **NumNet: Machine Reading Comprehension with Numerical Reasoning** EMNLP (2019)

   *Qiu Ran, Yankai Lin, Peng Li, Jie Zhou, Zhiyuan Liu* [[pdf](https://aclanthology.org/D19-1251.pdf)] [[project](https://github.com/ranqiu92/NumNet)]

4. **Mathematical Reasoning in Latent Space** ICLR Oral (2020)

   *Dennis Lee, Christian Szegedy, Markus N. Rabe, Sarah M. Loos, Kshitij Bansal* [[pdf](https://openreview.net/pdf?id=Ske31kBtPr)]

5. **Neural Module Networks for Reasoning over Text** ICLR Poster (2020)

   *Nitish Gupta, Kevin Lin, Dan Roth, Sameer Singh, Matt Gardner* [[pdf](https://openreview.net/pdf?id=SygWvAVFPr)] [[project](http://cogcomp.org/page/publication_view/899)]

6. **Injecting Numerical Reasoning Skills into Language Models** ACL (2020)

   *Mor Geva, Ankit Gupta, Jonathan Berant* [[pdf](https://aclanthology.org/2020.acl-main.89.pdf)] [[project](https://github.com/ag1988/injecting_numeracy)]

7. **Question Directed Graph Attention Network for Numerical Reasoning over Text** EMNLP (2020)

   *Kunlong Chen, Weidi Xu, Xingyi Cheng, Zou Xiaochuan, Yuyu Zhang, Le Song, Taifeng Wang, Yuan Qi, Wei Chu* [[pdf](https://aclanthology.org/2020.emnlp-main.549.pdf)]

8. **Mathematical Reasoning via Self-supervised Skip-tree Training** ICLR Spotlight (2021)

   *Markus Norman Rabe, Dennis Lee, Kshitij Bansal, Christian Szegedy* [[pdf](https://openreview.net/pdf?id=YmqAnY0CMEy)]

9. **Incorporating External Knowledge to Enhance Tabular Reasoning** NAACL (2021)

   *J. Neeraja, Vivek Gupta, Vivek Srikumar* [[pdf](https://aclanthology.org/2021.naacl-main.224.pdf)] [[project](https://github.com/utahnlp/knowledge_infotabs)]

10. **Measuring and Improving BERT's Mathematical Abilities by Predicting the Order of Reasoning** ACL (2021)

      *Piotr Piekos, Mateusz Malinowski, Henryk Michalewski* [[pdf](https://aclanthology.org/2021.acl-short.49.pdf)]

11. **GraphMR: Graph Neural Network for Mathematical Reasoning** ACL (2021)

      *Weijie Feng, Binbin Liu, Dongpeng Xu, Qilong Zheng, Yun Xu* [[pdf](https://aclanthology.org/2021.emnlp-main.273.pdf)] [[project](https://github.com/nhpcc502/GraphMR)]

12. **LIME: Learning Inductive Bias for Primitives of Mathematical Reasoning** ICML (2021)

      *Yuhuai Wu, Markus N. Rabe, Wenda Li, Jimmy Ba, Roger B. Grosse, Christian Szegedy* [[pdf](http://proceedings.mlr.press/v139/wu21c/wu21c.pdf)] [[project](https://github.com/tonywu95/LIME)]

13. **Numerical reasoning in machine reading comprehension tasks: are we there yet?** EMNLP (2021)

      *Hadeel Al-Negheimish, Pranava Madhyastha, Alessandra Russo* [[pdf](https://aclanthology.org/2021.emnlp-main.759.pdf)]

14. **Learning to Reason Deductively: Math Word Problem Solving as Complex Relation Extraction** ACL (2022)

      *Zhanming Jie, Jierui Li, Wei Lu* [[pdf](https://aclanthology.org/2022.acl-long.410.pdf)] [[project](https://github.com/allanj/Deductive-MWP)]

15. **FORTAP: Using Formulas for Numerical-Reasoning-Aware Table Pretraining** ACL (2022)

      *Zhoujun Cheng, Haoyu Dong, Ran Jia, Pengfei Wu, Shi Han, Fan Cheng, Dongmei Zhang* [[pdf](https://aclanthology.org/2022.acl-long.82.pdf)] [[project](https://github.com/microsoft/TUTA_table_understanding)]

16. **Right for the Right Reason: Evidence Extraction for Trustworthy Tabular Reasoning** ACL (2022)

      *Vivek Gupta, Shuo Zhang, Alakananda Vempala, Yujie He, Temma Choji, Vivek Srikumar* [[pdf](https://aclanthology.org/2022.acl-long.231.pdf)] [[project](https://tabevidence.github.io/)]

17. **Turning Tables: Generating Examples from Semi-structured Tables for Endowing Language Models with Reasoning Skills** ACL (2022)

      *Ori Yoran, Alon Talmor, Jonathan Berant* [[pdf](https://aclanthology.org/2022.acl-long.416.pdf)] [[project](https://github.com/oriyor/turning_tables)]

18. **OPERA: Operation-Pivoted Discrete Reasoning over Text** NAACL (2022)

      *Yongwei Zhou, Junwei Bao, Chaoqun Duan, Haipeng Sun, Jiahui Liang, Yifan Wang, Jing Zhao, Youzheng Wu, Xiaodong He, Tiejun Zhao* [[pdf](https://aclanthology.org/2022.naacl-main.119.pdf)] [[project](https://github.com/JD-AI-Research-NLP/OPERA)]

















## Contributor

Fei Yu
