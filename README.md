# ReasoningNLP
Paper list on reasoning in NLP. Here we mainly collect papers about datasets and methods using PLMs (under the progress). We will publish our comprehensive survey recently.

- [Methodology](#1)
   - [Large Languague Model](#1.1)
- [Natural Language Reasoning](#2)
   - [Classical Logical Reasoning](#2.1)
      - [Datasets & Benchmarks](#2.1.1)
      - [Related Works](#2.1.2)
   - [Natural Language Inference](#2.2)
      - [Datasets & Benchmarks](#2.2.1)
      - [Related Works](#2.2.2)
   - [Multi-hop Question Answering](#2.3)
      - [Datasets & Benchmarks](#2.3.1)
      - [Related Works](#2.3.2)
   - [Commonsense Reasoning](#2.4)
      - [Knowledge Bases](#2.4.1)
      - [Datasets & Benchmarks](#2.4.2)
      - [Related Works](#2.4.3)
- [Knowledge Graph Reasoning](#knowledge-graph-reasoning)
- [Mathematical Reasoning](#mathematical-reasoning)



<h2 id="1">Methodology</h2>


<h3 id="1.1">Large Languague Model</h3>


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













<h2 id="2">NLP Topics</h2>

<h3 id="2.1">Classical Logical Reasoning</h3>

Some datasets explicitly target at philosophical reasoning types, e.g. deduction, abduction and induction. Thus, we call them as ``classical logical reasoning tasks''. A key characteristic of this topic is that tasks are mostly artificial to study reasoning. 


<h4 id="2.1.1">Datasets & Benchmarks</h4>

<table>
  <tr>
      <th colspan="2" align="center">Inference Type</th>
      <th align="center">Dataset</th>
      <th align="center">Size</th>
      <th align="center">Task</th>
      <th align="center">Link</th>
      <th align="center">Remark</th>
  </tr >
  
  <tr>
      <th rowspan="6" colspan="2" align="center" valign="middle">Deductive Reasoning</th>
      <td align="center">babI-15</td>
      <td align="center">-</td>
      <td align="center">extraction</td>
      <td align="center"> <a href="https://arxiv.org/pdf/1502.05698.pdf">paper</a> <br /> <a href="http://fb.ai/babi">project</a>  </td>
      <td align="center">basic deduction</td>
  </tr>
  <tr>
      <td align="center">RuleTaker</td>
      <td align="center">500k</td>
      <td align="center">classification</td>
      <td align="center"> <a href="https://www.ijcai.org/proceedings/2020/0537.pdf">paper</a> <br /> <a href="https://allenai.org/data/ruletaker">project</a>  </td>
      <td align="center">the first large-scale benchmark (synthetic)</td>
  </tr>
  <tr>
      <td align="center">ProofWriter</td>
      <td align="center">500k</td>
      <td align="center">classification</td>
      <td align="center"> <a href="https://aclanthology.org/2021.findings-acl.317.pdf">paper</a> <br /> <a href="https://allenai.org/data/proofwriter">project</a>  </td>
      <td align="center">variant of RuleTaker</td>
  </tr>
  <tr>
      <td align="center">AAC</td>
      <td align="center">710k</td>
      <td align="center">generation</td>
      <td align="center"> <a href="https://aclanthology.org/2021.iwcs-1.7.pdf">paper</a> <br /> <a href="https://github.com/debatelab/aacorpus">project</a>  </td>
      <td align="center">synthetic, syllogistic arguments</td>
  </tr>
  <tr>
      <td align="center">LogicInference</td>
      <td align="center">200k</td>
      <td align="center">generation</td>
      <td align="center"> <a href="https://arxiv.org/pdf/2203.15099.pdf">paper</a> <br /> <a href="https://github.com/google-research/google-research/tree/master/logic_inference_dataset">project</a>  </td>
      <td align="center">synthetic, more tasks</td>
  </tr>
  <tr>
      <td align="center">FOLIO</td>
      <td align="center">1.4k</td>
      <td align="center">classification, generation</td>
      <td align="center"> <a href="https://arxiv.org/pdf/2209.00840.pdf">paper</a> <br /> <a href="https://github.com/Yale-LILY/FOLIO">project</a>  </td>
      <td align="center">expert-written, annotate with FOL</td>
  </tr>

  <tr>
      <th rowspan="6" align="center" valign="middle">Defeasible Reasoning</th>
      <th rowspan="2" align="center" valign="middle"><i>Abductive Reasoning</i></th>
      <td align="center">AbductionRules</td>
      <td align="center">-</td>
      <td align="center">generation</td>
      <td align="center"> <a href="https://arxiv.org/pdf/2203.12186.pdf">paper</a> <br /> <a href="https://github.com/Strong-AI-Lab/AbductionRule">project</a>  </td>
      <td align="center">variant of RuleTaker</td>
  </tr>
  <tr>
      <td align="center">ART <br /> (&alpha;NLI, &alpha;NLG)</td>
      <td align="center">17.8k</td>
      <td align="center">classification, generation</td>
      <td align="center"> <a href="https://openreview.net/pdf?id=Byg1v1HKDB">paper</a> <br /> <a href="http://abductivecommonsense.xyz/">project</a>  </td>
      <td align="center">commonsense, based on ROCStories</td>
  </tr>

  <tr>
      <th rowspan="3" align="center" valign="middle"><i>Inductive Reasoning</i></th>
      <td align="center">bAbI-16</td>
      <td align="center">-</td>
      <td align="center">extraction</td>
      <td align="center"> <a href="https://arxiv.org/pdf/1502.05698.pdf">paper</a> <br /> <a href="http://fb.ai/babi">project</a>  </td>
      <td align="center">basic induction</td>
  </tr>
  <tr>
      <td align="center">CLUTRR</td>
      <td align="center">-</td>
      <td align="center">extraction</td>
      <td align="center"> <a href="https://aclanthology.org/D19-1458.pdf">paper</a> <br /> <a href="https://github.com/facebookresearch/clutrr">project</a>  </td>
      <td align="center">induce kinship and apply to deduce (synthetic)</td>
  </tr>
  <tr>
      <td align="center">DEER</td>
      <td align="center">1.2k</td>
      <td align="center">generation</td>
      <td align="center"> <a href="https://arxiv.org/pdf/2212.10923.pdf">paper</a> <br /> project  </td>
      <td align="center">induce natural language rule (human-authored) from natural language facts (Webs)</td>
  </tr>

  <tr>
      <th align="center" valign="middle"><i>Others</i></th>
      <td align="center">defeasibleNLI</td>
      <td align="center">43.8k</td>
      <td align="center">classification, generation</td>
      <td align="center"> <a href="https://aclanthology.org/2020.findings-emnlp.418.pdf">paper</a> <br /> <a href="https://github.com/rudinger/defeasible-nli">project</a>  </td>
      <td align="center">direction on evidence updation, based on SNLI, ATOMIC, and Social-Chem-101</td>
  </tr>
</table>


Papers on dataset artifacts:

1. **On the Paradox of Learning to Reason from Data** arXiv (2022)

   *Honghua Zhang, Liunian Harold Li, Tao Meng, Kai-Wei Chang, Guy Van den Broeck* [[pdf](https://arxiv.org/pdf/2205.11502.pdf)] [[project](https://github.com/joshuacnf/paradox-learning2reason)]




<h4 id="2.1.2">Related Works</h4>
Deductive reasoning:

1. **Transformers as Soft Reasoners over Language** IJCAI (2020)

   *Peter Clark, Oyvind Tafjord, Kyle Richardson* [[pdf](https://www.ijcai.org/proceedings/2020/0537.pdf)] [[project](https://allenai.org/data/ruletaker)]

2. **PRover: Proof Generation for Interpretable Reasoning over Rules** EMNLP (2020)

   *Swarnadeep Saha, Sayan Ghosh, Shashank Srivastava, Mohit Bansal* [[pdf](https://aclanthology.org/2020.emnlp-main.9.pdf)] [[project](https://github.com/swarnaHub/PRover)]

3. **multiPRover: Generating Multiple Proofs for Improved Interpretability in Rule Reasoning** NAACL (2021)

   *Swarnadeep Saha, Prateek Yadav, Mohit Bansal* [[pdf](https://aclanthology.org/2021.naacl-main.287.pdf)] [[project](https://github.com/swarnaHub/multiPRover)]

4. **Critical Thinking for Language Models** IWCS (2021)

   *Gregor Betz, Christian Voigt, Kyle Richardson* [[pdf](https://aclanthology.org/2021.iwcs-1.7.pdf)] [[project](https://github.com/debatelab/aacorpus)]

5. **Explainable Multi-hop Verbal Reasoning Through Internal Monologue** NAACL (2021)

   *Zhengzhong Liang, Steven Bethard, Mihai Surdeanu* [[pdf](https://aclanthology.org/2021.naacl-main.97.pdf)] [[project](https://github.com/clulab/releases/tree/master/naacl2021-evr)]

6. **ProofWriter: Generating Implications, Proofs, and Abductive Statements over Natural Language** ACL findings (2021)

   *Oyvind Tafjord, Bhavana Dalvi, Peter Clark* [[pdf](https://aclanthology.org/2021.findings-acl.317.pdf)] [[project](https://allenai.org/data/proofwriter)]

7. **Flexible Generation of Natural Language Deductions** EMNLP (2021)

      *Kaj Bostrom, Xinyu Zhao, Swarat Chaudhuri, Greg Durrett* [[pdf](https://aclanthology.org/2021.emnlp-main.506.pdf)] [[project](https://github.com/alephic/ParaPattern)]

8. **FaiRR: Faithful and Robust Deductive Reasoning over Natural Language** ACL (2022)

   *Soumya Sanyal, Harman Singh, Xiang Ren* [[pdf](https://aclanthology.org/2022.acl-long.77.pdf)] [[project](https://github.com/INK-USC/FaiRR)]

9. **Interpretable Proof Generation via Iterative Backward Reasoning** NAACL (2022)

   *Hanhao Qu, Yu Cao, Jun Gao, Liang Ding, Ruifeng Xu* [[pdf](https://aclanthology.org/2022.naacl-main.216.pdf)] [[project](https://github.com/find-knowledge/IBR)]

10. **Selection-Inference: Exploiting Large Language Models for Interpretable Logical Reasoning** arXiv (2022)

      *Antonia Creswell, Murray Shanahan, Irina Higgins* [[pdf](https://arxiv.org/pdf/2205.09712.pdf)]

11. **Generating Natural Language Proofs with Verifier-Guided Search** arXiv (2022)

      *Kaiyu Yang, Jia Deng, Danqi Chen* [[pdf](https://arxiv.org/pdf/2205.12443.pdf)] [[project](https://github.com/princeton-nlp/NLProofS)]

12. **ROBUSTLR: A Diagnostic Benchmark for Evaluating Logical Robustness of Deductive Reasoners** arXiv (2022)

      *Soumya Sanyal, Zeyi Liao, Xiang Ren* [[pdf](https://arxiv.org/pdf/2205.12598.pdf)] [[project](https://github.com/INK-USC/RobustLR)]

13. **Language models show human-like content effects on reasoning** arXiv (2022)

      *Ishita Dasgupta, Andrew K. Lampinen, Stephanie C. Y. Chan, Antonia Creswell, Dharshan Kumaran, James L. McClelland, Felix Hill* [[pdf](https://arxiv.org/pdf/2207.07051.pdf)]

14. **Faithful Reasoning Using Large Language Models** arXiv (2022)

      *Antonia Creswell, Murray Shanahan* [[pdf](https://arxiv.org/pdf/2208.14271.pdf)]

15. **Language Models Are Greedy Reasoners: A Systematic Formal Analysis of Chain-of-Thought** arXiv (2022)

      *Abulhair Saparov, He He* [[pdf](https://arxiv.org/pdf/2210.01240.pdf)] [[project](https://github.com/asaparov/prontoqa)]

16. **LAMBADA: Backward Chaining for Automated Reasoning in Natural Language** arXiv (2022)

      *Seyed Mehran Kazemi, Najoung Kim, Deepti Bhatia, Xin Xu, Deepak Ramachandran* [[pdf](https://arxiv.org/pdf/2212.13894.pdf)]


Defeasible reasoning:

1. **Learning to Rationalize for Nonmonotonic Reasoning with Distant Supervision** AAAI (2020)

   *Faeze Brahman, Vered Shwartz, Rachel Rudinger, Yejin Choi* [[pdf](https://arxiv.org/pdf/2012.08012.pdf)] [[project](https://github.com/fabrahman/RationaleGen)]

2. **Could you give me a hint ? Generating inference graphs for defeasible reasoning** ACL findings (2021)

   *Aman Madaan, Dheeraj Rajagopal, Niket Tandon, Yiming Yang, Eduard H. Hovy* [[pdf](https://aclanthology.org/2021.findings-acl.456.pdf)] [[project](https://tinyurl.com/defeasiblegraphs)]


3. **Think about it! Improving defeasible reasoning by first modeling the question scenario** EMNLP (2021)

   *Aman Madaan, Niket Tandon, Dheeraj Rajagopal, Peter Clark, Yiming Yang, Eduard H. Hovy* [[pdf](https://aclanthology.org/2021.emnlp-main.508.pdf)] [[project](https://github.com/madaan/thinkaboutit)]

4. **Language Models as Inductive Reasoners** arXiv (2022)

   *Zonglin Yang, Li Dong, Xinya Du, Hao Cheng, Erik Cambria, Xiaodong Liu, Jianfeng Gao, Furu Wei* [[pdf](https://arxiv.org/pdf/2212.10923.pdf)]














<h3 id="2.2">Natural Language Inference</h3>

Task: given a premise-hypothesis pair, classify it into three classes: entailment, contradiction and neutral. 

There are mainly three types of premise-hypothesis pairs in NLI task: paraphrase, compound semantics understanding (CSU), and reasoning. Here we just consider the last one.

<table>
  <tr>
      <th align="center"></th>
      <th align="center">Premise</th>
      <th align="center">Hypothesis</th>
  </tr >

  <tr>
      <th align="center">Paraphrase</th>
      <td align="center">Two doctors perform surgery on patient</td>
      <td align="center">Doctors are performing surgery</td>
  </tr>
  <tr>
      <th align="center">CSU</th>
      <td align="center">Two women are embracing while holding to go packages</td>
      <td align="center">Two women are holding packages <br /> (<i>Two women are embracing</i>)</td>
  </tr>
  <tr>
      <th align="center">Reasoning</th>
      <td align="center">A soccer game with multiple males playing <br /> (<i>Soccer is a sport</i>)</td>
      <td align="center">Some men are playing a sport</td>
  </tr>
</table>


<h4 id="2.2.1">Datasets & Benchmarks</h4>

<table>
  <tr>
      <th align="center">Dataset</th>
      <th align="center">Size</th>
      <th align="center">Link</th>
      <th align="center">Remark</th>
  </tr >
  <tr>
      <th colspan=5 align="center">generic</th>
  </tr >

  <tr>
      <td align="center">SNLI</td>
      <td align="center">570k</td>
      <td align="center"> <a href="https://aclanthology.org/D15-1075.pdf">paper</a> <br /> <a href="nlp.stanford.edu/projects/snli/">project</a>  </td>
      <td align="center">the first large-scale NLI dataset <br/> one of the most typical</td>
  </tr>
  <tr>
      <td align="center">e-SNLI</td>
      <td align="center">-</td>
      <td align="center"> <a href="https://proceedings.neurips.cc/paper/2018/file/4c7a167bb329bd92580a99ce422d6fa6-Paper.pdf">paper</a> <br /> <a href="https://github.com/OanaMariaCamburu/e-SNLI">project</a>  </td>
      <td align="center">annotate natural language explanations for SNLI</td>
  </tr>
  <tr>
      <td align="center">MultiNLI</td>
      <td align="center">433k</td>
      <td align="center"> <a href="https://aclanthology.org/N18-1101.pdf">paper</a> <br /> <a href="https://cims.nyu.edu/~sbowman/multinli/">project</a>  </td>
      <td align="center">cover more styles and topics than SNLI <br/> one of the most typical</td>
  </tr>
  <tr>
      <td align="center">DebiasedNLI</td>
      <td align="center">7.5k</td>
      <td align="center"> <a href="https://aclanthology.org/2022.acl-long.190.pdf">paper</a> <br /> <a href="https://github.com/jimmycode/gen-debiased-nli">project</a>  </td>
      <td align="center">debiased versions of SNLI & MultiNLI</td>
  </tr>
  <tr>
      <td align="center">XNLI</td>
      <td align="center">7.5k</td>
      <td align="center"> <a href="https://aclanthology.org/D18-1269.pdf">paper</a> <br /> <a href="https://github.com/facebookresearch/XNLI/">project</a>  </td>
      <td align="center">cross-lingual, based on MultiNLI</td>
  </tr>
  <tr>
      <td align="center">MPE</td>
      <td align="center">10k</td>
      <td align="center"> <a href="https://aclanthology.org/I17-1011.pdf">paper</a> <br /> <a href="https://github.com/aylai/MultiPremiseEntailment">project</a>  </td>
      <td align="center">multiple premises</td>
  </tr>
  <tr>
      <td align="center">UNLI</td>
      <td align="center">61k</td>
      <td align="center"> <a href="https://aclanthology.org/2020.acl-main.774.pdf">paper</a> <br /> <a href="http://nlp.jhu.edu/unli">project</a>  </td>
      <td align="center">subjective probability assessment (regression rather than binary), based on SNLI</td>
  </tr>
  <tr>
      <td align="center">ChaosNLI</td>
      <td align="center">464k</td>
      <td align="center"> <a href="https://aclanthology.org/2020.emnlp-main.734.pdf">paper</a> <br /> <a href="https://github.com/easonnie/ChaosNLI">project</a>  </td>
      <td align="center">human opinion distribution, based on SNLI, MultiNLI and &alpha;NLI</td>
  </tr>

  <tr>
      <th colspan=5 align="center">science</th>
  </tr >
  <tr>
      <td align="center">SciTail</td>
      <td align="center">27k</td>
      <td align="center"> <a href="http://ai2-website.s3.amazonaws.com/team/ashishs/scitail-aaai2018.pdf">paper</a> <br /> <a href="http://data.allenai.org/scitail">project</a>  </td>
      <td align="center">the first NLI dataset with entirely existing text</td>
  </tr>
  <tr>
      <td align="center">SciNLI</td>
      <td align="center">107k</td>
      <td align="center"> <a href="https://aclanthology.org/2022.acl-long.511.pdf">paper</a> <br /> <a href="https://github.com/msadat3/SciNLI">project</a>  </td>
      <td align="center">data from scholarly papers</td>
  </tr>
</table>

Recently, some datasets are proposed to model different subjective opinions (on classifying into which class) of crowdworkers.

<table>
  <tr>
      <th align="center">Dataset</th>
      <th align="center">Domain</th>
      <th align="center">Size</th>
      <th align="center">Link</th>
      <th align="center">Remark</th>
  </tr >

  <tr>
      <td align="center">UNLI</td>
      <td align="center">generic</td>
      <td align="center">61k</td>
      <td align="center"> <a href="https://aclanthology.org/2020.acl-main.774.pdf">paper</a> <br /> <a href="http://nlp.jhu.edu/unli">project</a>  </td>
      <td align="center">subjective probability assessment (regression rather than binary), based on SNLI</td>
  </tr>
  <tr>
      <td align="center">ChaosNLI</td>
      <td align="center">generic</td>
      <td align="center">464k</td>
      <td align="center"> <a href="https://aclanthology.org/2020.emnlp-main.734.pdf">paper</a> <br /> <a href="https://github.com/easonnie/ChaosNLI">project</a>  </td>
      <td align="center">human opinion distribution, based on SNLI, MultiNLI and &alpha;NLI</td>
  </tr>
</table>

Some datasets for other language:
<table>
  <tr>
      <th align="center">Dataset</th>
      <th align="center">Language</th>
      <th align="center">Link</th>
      <th align="center">Remark</th>
  </tr >

  <tr>
      <td align="center">NLI-TR</td>
      <td align="center">Turkish</td>
      <td align="center"> <a href="https://aclanthology.org/2020.emnlp-main.662.pdf">paper</a> <br /> <a href="https://github.com/boun-tabi/NLI-TR">project</a>  </td>
      <td align="center">translate SNLI and MultiNLI</td>
  </tr>
  <tr>
      <td align="center">IndoNLI</td>
      <td align="center">Indonesian</td>
      <td align="center"> <a href="https://aclanthology.org/2021.emnlp-main.821.pdf">paper</a> <br /> <a href="https://github.com/ir-nlp-csui/indonli">project</a>  </td>
      <td align="center">data collection protocol from MultiNLI</td>
  </tr>
</table>

Papers on dataset artifacts:

1. **Performance Impact Caused by Hidden Bias of Training Data for Recognizing Textual Entailment** LREC (2018)

   *Masatoshi Tsuchiya* [[pdf](https://aclanthology.org/N19-1101.pdf)]

2. **Annotation Artifacts in Natural Language Inference Data** NAACL (2018)

   *Suchin Gururangan, Swabha Swayamdipta, Omer Levy, Roy Schwartz, Samuel R. Bowman, Noah A. Smith* [[pdf](https://aclanthology.org/N18-2017.pdf)]

3. **Hypothesis Only Baselines in Natural Language Inference** SEM (2019)

   *Adam Poliak, Jason Naradowsky, Aparajita Haldar, Rachel Rudinger, Benjamin Van Durme* [[pdf](https://aclanthology.org/S18-2023.pdf)]



<h4 id="2.2.2">Related Works</h4>


1. **NILE : Natural Language Inference with Faithful Natural Language Explanations** ACL (2020)

   *Sawan Kumar, Partha P. Talukdar* [[pdf](https://aclanthology.org/2020.acl-main.771.pdf)] [[project](https://github.com/SawanKumar28/nile)]


2. **Identifying inherent disagreement in natural language inference** NAACL (2021)

   *Xinliang Frederick Zhang, Marie-Catherine de Marneffe* [[pdf](https://aclanthology.org/2021.naacl-main.390.pdf)] [[project](https://github.com/FrederickXZhang/FgNLI)]


3. **KACE: Generating Knowledge Aware Contrastive Explanations for Natural Language Inference** ACL (2021)

   *Qianglong Chen, Feng Ji, Xiangji Zeng, Feng-Lin Li, Ji Zhang, Haiqing Chen, Yin Zhang* [[pdf](https://aclanthology.org/2021.acl-long.196.pdf)] [[project](https://github.com/AI4NLP/KACE)]

4. **Investigating Transfer Learning in Multilingual Pre-trained Language Models through Chinese Natural Language Inference** ACL findings (2021)

   *Hai Hu, He Zhou, Zuoyu Tian, Yiwen Zhang, Yina Patterson, Yanting Li, Yixin Nie, Kyle Richardson* [[pdf](https://aclanthology.org/2021.findings-acl.331.pdf)] [[project](https://github.com/huhailinguist/ChineseNLIProbing)]

5. **Enhancing Cross-lingual Natural Language Inference by Prompt-learning from Cross-lingual Templates** ACL (2022)

   *Kunxun Qi, Hai Wan, Jianfeng Du, Haolan Chen* [[pdf](https://aclanthology.org/2022.acl-long.134.pdf)] [[project](https://github.com/qikunxun/PCT)]

6. **Generating Intermediate Steps for NLI with Next-Step Supervision** arXiv (2022)

   *Deepanway Ghosal, Somak Aditya, Monojit Choudhury* [[pdf](https://arxiv.org/pdf/2208.14641.pdf)]























<h3 id="2.3">Multi-hop Question Answering</h3>

This topic studies answering the complex questions that require to reason over evidences scattered in different contexts. The term ``hop'' here indicates the number of contexts required to reason. There are two settings on the required contexts: (1) all provided along with some distractors (i.e. distractor), (2) need to be retrieved (i.e. retrieval).




<h4 id="2.3.1">Datasets & Benchmarks</h4>

Some datasets annotate the ground supporting evidences (paragraph-level, sentence-level, or triple-level), decomposed sub-questions (and the corresponding evidences), or reasoning paths.

<table>
  <tr>
      <th align="center">Dataset</th>
      <th align="center">Size</th>
      <th align="center">Knowledge Source</th>
      <th align="center">Setting</th>
      <th align="center">Answer Type</th>
      <th align="center">Evidence</th>
      <th align="center">Link</th>
      <th align="center">Remark</th>
  </tr >

  <tr>
      <th colspan=8 align="center">generic</th>
  </tr >
  <tr>
      <td align="center">WikiHop</td>
      <td align="center">51k</td>
      <td align="center">Wikipedia</td>
      <td align="center">distractor</td>
      <td align="center">choice</td>
      <td align="center">-</td>
      <td align="center"> <a href="https://aclanthology.org/Q18-1021.pdf">paper</a> <br /> <a href="http://qangaroo.cs.ucl.ac.uk/">project</a>  </td>
      <td align="center">one of the most typical</td>
  </tr>
  <tr>
      <td align="center">HotpotQA</td>
      <td align="center">112k</td>
      <td align="center">Wikipedia</td>
      <td align="center">distractor, retrieval</td>
      <td align="center">span, yes/no</td>
      <td align="center">sentence</td>
      <td align="center"> <a href="https://aclanthology.org/D18-1259.pdf">paper</a> <br /> <a href="https://hotpotqa.github.io/">project</a>  </td>
      <td align="center">the most popular one</td>
  </tr>
  <tr>
      <td align="center">R4C</td>
      <td align="center">4.6k</td>
      <td align="center">-</td>
      <td align="center">-</td>
      <td align="center">-</td>
      <td align="center">triple</td>
      <td align="center"> <a href="https://aclanthology.org/2020.acl-main.602.pdf">paper</a> <br /> <a href="https://naoya-i.github.io/r4c/">project</a>  </td>
      <td align="center">annotate atomic facts for HotpotQA</td>
  </tr>
  <tr>
      <td align="center">BeerQA</td>
      <td align="center">530</td>
      <td align="center">Wikipedia</td>
      <td align="center">retrieval</td>
      <td align="center">span, yes/no</td>
      <td align="center">-</td>
      <td align="center"> <a href="https://aclanthology.org/2021.emnlp-main.292.pdf">paper</a> <br /> <a href="https://beerqa.github.io/">project</a>  </td>
      <td align="center">more hops</td>
  </tr>
  <tr>
      <td align="center">2WikiMultiHopQA</td>
      <td align="center">192k</td>
      <td align="center">Wikipedia</td>
      <td align="center">distractor</td>
      <td align="center">span</td>
      <td align="center">sentence <br /> triple</td>
      <td align="center"> <a href="https://aclanthology.org/2020.coling-main.580.pdf">paper</a> <br /> <a href="https://github.com/Alab-NII/2wikimultihop">project</a>  </td>
      <td align="center">similar to WikiHop</td>
  </tr>
  <tr>
      <td align="center">MuSiQue</td>
      <td align="center">25k</td>
      <td align="center">Wikipedia</td>
      <td align="center">distractor</td>
      <td align="center">span</td>
      <td align="center">paragraph <br /> sub-questions</td>
      <td align="center"> <a href="https://aclanthology.org/2022.tacl-1.31.pdf">paper</a> <br /> <a href="https://github.com/stonybrooknlp/musique">project</a>  </td>
      <td align="center">more hops</td>
  </tr>
  <tr>
      <td align="center">StrategyQA</td>
      <td align="center">2.7k</td>
      <td align="center">Wikipedia</td>
      <td align="center">retrieval</td>
      <td align="center">yes/no</td>
      <td align="center">paragraph <br /> sub-questions</td>
      <td align="center"> <a href="https://aclanthology.org/2021.tacl-1.21.pdf">paper</a> <br /> <a href="https://allenai.org/data/strategyqa">project</a>  </td>
      <td align="center">implicit mult-hop questions</td>
  </tr>

  <tr>
      <th colspan=8 align="center">specific domain</th>
  </tr >
  <tr>
      <td align="center">MedHop</td>
      <td align="center">2.5k</td>
      <td align="center">Medline</td>
      <td align="center">distractor</td>
      <td align="center">choice</td>
      <td align="center">-</td>
      <td align="center"> <a href="https://aclanthology.org/Q18-1021.pdf">paper</a> <br /> <a href="http://qangaroo.cs.ucl.ac.uk/">project</a>  </td>
      <td align="center">medicine. similar to WikiHop</td>
  </tr>
  <tr>
      <td align="center">QASC</td>
      <td align="center">9.9k</td>
      <td align="center">WorldTree</td>
      <td align="center">retrieval</td>
      <td align="center">choice</td>
      <td align="center">sentence</td>
      <td align="center"> <a href="https://arxiv.org/pdf/1910.11473.pdf">paper</a> <br /> <a href="https://github.com/allenai/qasc">project</a>  </td>
      <td align="center">science</td>
  </tr>
  <tr>
      <td align="center">eQASC</td>
      <td align="center">-</td>
      <td align="center">-</td>
      <td align="center">-</td>
      <td align="center">-</td>
      <td align="center">reasoning path</td>
      <td align="center"> <a href="http://aclanthology.lst.uni-saarland.de/2020.emnlp-main.10.pdf">paper</a> <br /> <a href="https://allenai.org/data/eqasc">project</a>  </td>
      <td align="center">annotate reasoning paths for QASC</td>
  </tr>
</table>

Papers on dataset artifacts:

1. **Understanding Dataset Design Choices for Multi-hop Reasoning** NAACL (2019)

   *Jifan Chen, Greg Durrett* [[pdf](https://aclanthology.org/N19-1405.pdf)]

2. **Avoiding Reasoning Shortcuts: Adversarial Evaluation, Training, and Model Development for Multi-Hop QA** ACL (2019)

   *Yichen Jiang, Mohit Bansal* [[pdf](https://aclanthology.org/P19-1262.pdf)] [[project](https://github.com/jiangycTarheel-zz/Adversarial-MultiHopQA)]

3. **Compositional Questions Do Not Necessitate Multi-hop Reasoning** ACL (2019)

      *Sewon Min, Eric Wallace, Sameer Singh, Matt Gardner, Hannaneh Hajishirzi, Luke Zettlemoyer* [[pdf](https://aclanthology.org/P19-1416.pdf)] [[project](https://github.com/shmsw25/single-hop-rc)]

4. **Is Multihop QA in DiRe Condition? Measuring and Reducing Disconnected Reasoning** EMNLP (2020)

      *Harsh Trivedi, Niranjan Balasubramanian, Tushar Khot, Ashish Sabharwal* [[pdf](https://aclanthology.org/2020.emnlp-main.712.pdf)] [[project](https://github.com/stonybrooknlp/dire)]



<h4 id="2.3.2">Related Works</h4>

1. **Dynamically Fused Graph Network for Multi-hop Reasoning** ACL (2019)

   *Lin Qiu, Yunxuan Xiao, Yanru Qu, Hao Zhou, Lei Li, Weinan Zhang, Yong Yu* [[pdf](https://aclanthology.org/P19-1617.pdf)] [[project](https://github.com/woshiyyya/DFGN-pytorch)]

2. **Multi-hop Reading Comprehension across Multiple Documents by Reasoning over Heterogeneous Graphs** ACL (2019)

   *Ming Tu, Guangtao Wang, Jing Huang, Yun Tang, Xiaodong He, Bowen Zhou* [[pdf](https://aclanthology.org/P19-1260.pdf)]

3. **Answering while Summarizing: Multi-task Learning for Multi-hop QA with Evidence Extraction** ACL (2019)

   *Kosuke Nishida, Kyosuke Nishida, Masaaki Nagata, Atsushi Otsuka, Itsumi Saito, Hisako Asano, Junji Tomita* [[pdf](https://aclanthology.org/P19-1225.pdf)]

4. **Multi-hop Reading Comprehension through Question Decomposition and Rescoring** ACL (2019)

   *Sewon Min, Victor Zhong, Luke Zettlemoyer, Hannaneh Hajishirzi* [[pdf](https://aclanthology.org/P19-1613.pdf)] [[project](https://github.com/shmsw25/DecompRC)]


5. **Differentiable Reasoning over a Virtual Knowledge Base** ICLR (2020)

   *Bhuwan Dhingra, Manzil Zaheer, Vidhisha Balachandran, Graham Neubig, Ruslan Salakhutdinov, William W. Cohen* [[pdf](https://openreview.net/pdf?id=SJxstlHFPH)] [[project](http://www.cs.cmu.edu/~bdhingra/pages/drkit.html)]

6. **Transformer-XH: Multi-Evidence Reasoning with eXtra Hop Attention** ICLR Poster (2020)

   *Chen Zhao, Chenyan Xiong, Corby Rosset, Xia Song, Paul N. Bennett, Saurabh Tiwary* [[pdf](https://openreview.net/pdf?id=r1eIiCNYwS)] [[project](https://aka.ms/transformer-xh)]

7. **Low-Resource Generation of Multi-hop Reasoning Questions** ACL (2020)

   *Jianxing Yu, Wei Liu, Shuang Qiu, Qinliang Su, Kai Wang, Xiaojun Quan, Jian Yin* [[pdf](http://aclanthology.lst.uni-saarland.de/2020.acl-main.601.pdf)]

8. **SRLGRN: Semantic Role Labeling Graph Reasoning Network** EMNLP (2020)

   *Chen Zheng, Parisa Kordjamshidi* [[pdf](https://aclanthology.org/2020.emnlp-main.714.pdf)]

9. **Learning to Retrieve Reasoning Paths over Wikipedia Graph for Question Answering** ICLR (2020)

   *Akari Asai, Kazuma Hashimoto, Hannaneh Hajishirzi, Richard Socher, Caiming Xiong* [[pdf](https://openreview.net/pdf?id=SJgVHkrYDH)] [[project](https://github.com/AkariAsai/learning_to_retrieve_reasoning_paths)]

10. **Robustifying Multi-hop QA through Pseudo-Evidentiality Training** ACL (2021)

      *Kyungjae Lee, Seung-won Hwang, Sang-eun Han, Dohyeon Lee* [[pdf](https://aclanthology.org/2021.acl-long.476.pdf)]

11. **Summarize-then-Answer: Generating Concise Explanations for Multi-hop Reading Comprehension** EMNLP (2021)

      *Naoya Inoue, Harsh Trivedi, Steven Sinha, Niranjan Balasubramanian, Kentaro Inui* [[pdf](https://aclanthology.org/2021.emnlp-main.490.pdf)] [[project](https://github.com/StonyBrookNLP/suqa)]

12. **Generative Context Pair Selection for Multi-hop Question Answering** EMNLP (2021)

      *Dheeru Dua, Cícero Nogueira dos Santos, Patrick Ng, Ben Athiwaratkun, Bing Xiang, Matt Gardner, Sameer Singh* [[pdf](https://aclanthology.org/2021.emnlp-main.561.pdf)] [[project](https://github.com/dDua/JointQA)]

13. **Breadth First Reasoning Graph for Multi-hop Question Answering** NAACL (2021)

      *Yongjie Huang, Meng Yang* [[pdf](https://aclanthology.org/2021.naacl-main.464.pdf)]

14. **Answering Complex Open-Domain Questions with Multi-Hop Dense Retrieval** ICLR Poster (2021)

      *Wenhan Xiong, Xiang Lorraine Li, Srini Iyer, Jingfei Du, Patrick S. H. Lewis, William Yang Wang, Yashar Mehdad, Scott Yih, Sebastian Riedel, Douwe Kiela, Barlas Oguz* [[pdf](https://openreview.net/pdf?id=EMHoBG0avc1)] [[project](https://github.com/facebookresearch/multihop_dense_retrieval)]

15. **Multi-Step Reasoning Over Unstructured Text with Beam Dense Retrieval** NAACL (2021)

      *Chen Zhao, Chenyan Xiong, Jordan L. Boyd-Graber, Hal Daumé III* [[pdf](https://aclanthology.org/2021.naacl-main.368.pdf)] [[project](https://github.com/henryzhao5852/BeamDR)]

16. **Unsupervised Multi-hop Question Answering by Question Generation** NAACL (2021)

      *Liangming Pan, Wenhu Chen, Wenhan Xiong, Min-Yen Kan, William Yang Wang* [[pdf](https://aclanthology.org/2021.naacl-main.469.pdf)] [[project](https://github.com/teacherpeterpan/Unsupervised-Multi-hop-QA)]

17. **If You Want to Go Far Go Together: Unsupervised Joint Candidate Evidence Retrieval for Multi-hop Question Answering** NAACL (2021)

      *Vikas Yadav, Steven Bethard, Mihai Surdeanu* [[pdf](https://aclanthology.org/2021.naacl-main.363.pdf)] [[project](https://github.com/vikas95/WAIR_interpretability)]

18. **Baleen: Robust Multi-Hop Reasoning at Scale via Condensed Retrieval** NIPS (2021)

      *Omar Khattab, Christopher Potts, Matei A. Zaharia* [[pdf](https://papers.nips.cc/paper/2021/file/e8b1cbd05f6e6a358a81dee52493dd06-Paper.pdf)] [[project](https://github.com/stanford-futuredata/Baleen)]

19. **Modeling Multi-hop Question Answering as Single Sequence Prediction** ACL (2022)

      *Semih Yavuz, Kazuma Hashimoto, Yingbo Zhou, Nitish Shirish Keskar, Caiming Xiong* [[pdf](https://aclanthology.org/2022.acl-long.69.pdf)]

20. **CQG: A Simple and Effective Controlled Generation Framework for Multi-hop Question Generation** ACL (2022)

      *Zichu Fei, Qi Zhang, Tao Gui, Di Liang, Sirui Wang, Wei Wu, Xuanjing Huang* [[pdf](https://aclanthology.org/2022.acl-long.475.pdf)] [[project](https://github.com/sion-zcfei/CQG)]




























<h3 id="2.4">Commonsense Reasoning</h3>

Commonsense reasoning deals with implicit commonsense knowledge, which may be non-trivial to machines since they are difficult to retrieve from the web due to reporting bias. <!-- While it is named with "reasoning", the common theme of this topic is commonsense knowledge rather than reasoning.  -->



<h4 id="2.4.1">Knowledge Bases</h4>

<table>
  <tr>
      <th align="center">KB</th>
      <th align="center">Type of Knowledge</th>
      <th align="center">Format of Knowledge</th>
      <th align="center">Link</th>
  </tr >

  <tr>
      <td align="center">CYC</td>
      <td align="center">generic</td>
      <td align="center">LISP-style logic</td>
      <td align="center"> <a href="https://dl.acm.org/doi/pdf/10.1145/219717.219745">paper</a> <br /> project </td>
  </tr>
  <tr>
      <td align="center">ConceptNet</td>
      <td align="center">linguistics</td>
      <td align="center">triple</td>
      <td align="center"> <a href="https://agents.media.mit.edu/projects/commonsense/ConceptNet-BTTJ.pdf">paper</a> <br /> <a href="http://www.conceptnet.org/">project</a>  </td>
  </tr>
  <tr>
      <td align="center">ConceptNet 5.5</td>
      <td align="center">linguistics</td>
      <td align="center">triple</td>
      <td align="center"> <a href="https://arxiv.org/pdf/1612.03975.pdf">paper</a> <br /> <a href="https://github.com/commonsense/conceptnet5">project</a>  </td>
  </tr>
  <tr>
      <td align="center">GenericsKB</td>
      <td align="center">generic</td>
      <td align="center">statement</td>
      <td align="center"> <a href="https://arxiv.org/pdf/2005.00660.pdf">paper</a> <br /> <a href="https://allenai.org/data/genericskb">project</a>  </td>
  </tr>
  <tr>
      <td align="center">Event2Mind</td>
      <td align="center">mental state</td>
      <td align="center">statement</td>
      <td align="center"> <a href="https://aclanthology.org/P18-1043.pdf">paper</a> <br /> <a href="https://tinyurl.com/event2mind">project</a>  </td>
  </tr>
  <tr>
      <td align="center">ATOMIC</td>
      <td align="center">social causality</td>
      <td align="center">statement</td>
      <td align="center"> <a href="https://arxiv.org/pdf/1811.00146.pdf">paper</a> <br /> <a href="https://allenai.org/data/atomic">project</a>  </td>
  </tr>
  <tr>
      <td align="center">ATOMIC 2020</td>
      <td align="center">+physical and eventive causality</td>
      <td align="center">statement</td>
      <td align="center"> <a href="https://arxiv.org/pdf/2010.05953.pdf">paper</a> <br /> <a href="https://github.com/allenai/comet-atomic-2020">project</a>  </td>
  </tr>
  <tr>
      <td align="center">Social-Chem-101</td>
      <td align="center">rules-of-thumb</td>
      <td align="center">statement</td>
      <td align="center"> <a href="https://aclanthology.org/2020.emnlp-main.48.pdf">paper</a> <br /> <a href="https://github.com/mbforbes/social-chemistry-101">project</a>  </td>
  </tr>
</table>


<h4 id="2.4.2">Datasets & Benchmarks</h4>

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

17. **WinoGrande: An Adversarial Winograd Schema Challenge at Scale** AAAI (2020)

      *Keisuke Sakaguchi, Ronan Le Bras, Chandra Bhagavatula, Yejin Choi* [[pdf](https://arxiv.org/pdf/1907.10641.pdf)] [[project](http://winogrande.allenai.org/)]

18. **PIQA: Reasoning about Physical Commonsense in Natural Language** AAAI (2020)

      *Yonatan Bisk, Rowan Zellers, Ronan Le Bras, Jianfeng Gao, Yejin Choi* [[pdf](https://yonatanbisk.com/piqa/)] [[project](http://abductivecommonsense.xyz/)]

19. **QASC: A Dataset for Question Answering via Sentence Composition** AAAI (2020)

      *Tushar Khot, Peter Clark, Michal Guerquin, Peter Jansen, Ashish Sabharwal* [[pdf](https://arxiv.org/pdf/1910.11473.pdf)] [[project](https://github.com/allenai/qasc)]

20. **Abductive Commonsense Reasoning** ICLR Poster (2020)

      *Chandra Bhagavatula, Ronan Le Bras, Chaitanya Malaviya, Keisuke Sakaguchi, Ari Holtzman, Hannah Rashkin, Doug Downey, Wen-tau Yih, Yejin Choi* [[pdf](https://openreview.net/pdf?id=Byg1v1HKDB)] [[project](http://abductivecommonsense.xyz/)]

21. **Social Bias Frames: Reasoning about Social and Power Implications of Language** ACL (2020)

      *Maarten Sap, Saadia Gabriel, Lianhui Qin, Dan Jurafsky, Noah A. Smith, Yejin Choi* [[pdf](https://aclanthology.org/2020.acl-main.486.pdf)] [[project](http://tinyurl.com/social-bias-frames)]

22. **A Method for Building a Commonsense Inference Dataset based on Basic Events** EMNLP (2020)

      *Kazumasa Omura, Daisuke Kawahara, Sadao Kurohashi* [[pdf](https://aclanthology.org/2020.emnlp-main.192.pdf)] [[project](http://nlp.ist.i.kyoto-u.ac.jp/EN/index.php?JCID)]

23. **Learning to Explain: Datasets and Models for Identifying Valid Reasoning Chains in Multihop Question-Answering** EMNLP (2020)

      *Harsh Jhamtani, Peter Clark* [[pdf](http://aclanthology.lst.uni-saarland.de/2020.emnlp-main.10.pdf)] [[project](https://allenai.org/data/eqasc)]

24. **Reasoning about Goals, Steps, and Temporal Ordering with WikiHow** EMNLP (2020)

      *Li Zhang, Qing Lyu, Chris Callison-Burch* [[pdf](https://aclanthology.org/2020.emnlp-main.374v2.pdf)] [[project](https://github.com/zharry29/wikihow-goal-step)]

25. **ProtoQA: A Question Answering Dataset for Prototypical Common-Sense Reasoning** EMNLP (2020)

      *Michael Boratko, Xiang Li, Tim O'Gorman, Rajarshi Das, Dan Le, Andrew McCallum* [[pdf](https://aclanthology.org/2020.emnlp-main.85.pdf)] [[project](https://github.com/iesl/protoqa-data)]

26. **XCOPA: A Multilingual Dataset for Causal Commonsense Reasoning** EMNLP (2020)

      *Edoardo Maria Ponti, Goran Glavas, Olga Majewska, Qianchu Liu, Ivan Vulic, Anna Korhonen* [[pdf](https://aclanthology.org/2020.emnlp-main.185.pdf)] [[project](http://github.com/cambridgeltl/xcopa)]

27. **CommonGen: A Constrained Text Generation Challenge for Generative Commonsense Reasoning** EMNLP findings (2020)

      *Bill Yuchen Lin, Wangchunshu Zhou, Ming Shen, Pei Zhou, Chandra Bhagavatula, Yejin Choi, Xiang Ren* [[pdf](https://aclanthology.org/2020.findings-emnlp.165.pdf)] [[project](http://inklab.usc.edu/CommonGen/)]

28. **Conversational Neuro-Symbolic Commonsense Reasoning** AAAI (2021)

      *Forough Arabshahi, Jennifer Lee, Mikayla Gawarecki, Kathryn Mazaitis, Amos Azaria, Tom M. Mitchell* [[pdf](https://ojs.aaai.org/index.php/AAAI/article/view/16623/16430)] [[project](https://github.com/ForoughA/CORGI)]

29. **Temporal Reasoning on Implicit Events from Distant Supervision** NAACL (2021)

      *Ben Zhou, Kyle Richardson, Qiang Ning, Tushar Khot, Ashish Sabharwal, Dan Roth* [[pdf](https://aclanthology.org/2021.naacl-main.107.pdf)] [[project](https://leaderboard.allenai.org/tracie)]

30. **Explanations for CommonsenseQA: New Dataset and Models** ACL (2021)

      *Shourya Aggarwal, Divyanshu Mandowara, Vishwajeet Agrawal, Dinesh Khandelwal, Parag Singla, Dinesh Garg* [[pdf](https://aclanthology.org/2021.acl-long.238.pdf)] [[project](https://github.com/dair-iitd/ECQA-Dataset)]

31. **Common Sense Beyond English: Evaluating and Improving Multilingual Language Models for Commonsense Reasoning** ACL (2021)

      *Bill Yuchen Lin, Seyeon Lee, Xiaoyang Qiao, Xiang Ren* [[pdf](https://aclanthology.org/2021.acl-long.102.pdf)] [[project](https://inklab.usc.edu/XCSR/)]

32. **TellMeWhy: A Dataset for Answering Why-Questions in Narratives** ACL findings (2021)

      *Yash Kumar Lal, Nathanael Chambers, Raymond J. Mooney, Niranjan Balasubramanian* [[pdf](https://aclanthology.org/2021.findings-acl.53v2.pdf)] [[project](http://lunr.cs.stonybrook.edu/tellmewhy)]

33. **COM2SENSE: A Commonsense Reasoning Benchmark with Complementary Sentences** ACL findings (2021)

      *Shikhar Singh, Nuan Wen, Yu Hou, Pegah Alipoormolabashi, Te-Lin Wu, Xuezhe Ma, Nanyun Peng* [[pdf](https://aclanthology.org/2021.findings-acl.78.pdf)] [[project](https://github.com/PlusLabNLP/Com2Sense)]

34. **Moral Stories: Situated Reasoning about Norms, Intents, Actions, and their Consequences** EMNLP (2021)

      *Denis Emelin, Ronan Le Bras, Jena D. Hwang, Maxwell Forbes, Yejin Choi* [[pdf](https://aclanthology.org/2021.emnlp-main.54.pdf)] [[project](https://github.com/demelin/moral_stories)]

35. **Wino-X: Multilingual Winograd Schemas for Commonsense Reasoning and Coreference Resolution** EMNLP (2021)

      *Denis Emelin, Rico Sennrich* [[pdf](https://aclanthology.org/2021.emnlp-main.670.pdf)] [[project](https://github.com/demelin/Wino-X)]

36. **Differentiable Open-Ended Commonsense Reasoning** EMNLP (2021)

      *Bill Yuchen Lin, Haitian Sun, Bhuwan Dhingra, Manzil Zaheer, Xiang Ren, William W. Cohen* [[pdf](https://aclanthology.org/2021.naacl-main.366.pdf)] [[project](https://open-csr.github.io/)]

37. **RICA: Evaluating Robust Inference Capabilities Based on Commonsense Axioms** EMNLP (2021)

      *Pei Zhou, Rahul Khanna, Seyeon Lee, Bill Yuchen Lin, Daniel Ho, Jay Pujara, Xiang Ren* [[pdf](https://aclanthology.org/2021.emnlp-main.598.pdf)] [[project](https://sites.google.com/usc.edu/rica)]

38. **CREAK: A Dataset for Commonsense Reasoning over Entity Knowledge** NIPS (2021)

      *Yasumasa Onoe, Michael J. Q. Zhang, Eunsol Choi, Greg Durrett* [[pdf](https://datasets-benchmarks-proceedings.neurips.cc/paper/2021/file/5737c6ec2e0716f3d8a7a5c4e0de0d9a-Paper-round2.pdf)] [[project](https://www.cs.utexas.edu/~yasumasa/creak)]

39. **CommonsenseQA 2.0: Exposing the Limits of AI through Gamification** NIPS (2021)

      *Alon Talmor, Ori Yoran, Ronan Le Bras, Chandra Bhagavatula, Yoav Goldberg, Yejin Choi, Jonathan Berant* [[pdf](https://openreview.net/pdf?id=qF7FlUT5dxa)] [[project](http://allenai.github.io/csqa2)]

40. **e-CARE: a New Dataset for Exploring Explainable Causal Reasoning** ACL (2022)

      *Li Du, Xiao Ding, Kai Xiong, Ting Liu, Bing Qin* [[pdf](https://aclanthology.org/2022.acl-long.33.pdf)] [[project](https://github.com/Waste-Wood/e-CARE/)]

41. **Misinfo Reaction Frames: Reasoning about Readers’ Reactions to News Headlines** ACL (2022)

      *Saadia Gabriel, Skyler Hallinan, Maarten Sap, Pemi Nguyen, Franziska Roesner, Eunsol Choi, Yejin Choi* [[pdf](https://aclanthology.org/2022.acl-long.222.pdf)] [[project](https://github.com/skgabriel/mrf-modeling)]

42. **WikiWhy: Answering and Explaining Cause-and-Effect Questions** arXiv (2022)

      *Matthew Ho, Aditya Sharma, Justin Chang, Michael Saxon, Sharon Levy, Yujie Lu, William Yang Wang* [[pdf](https://arxiv.org/pdf/2210.12152.pdf)]




<h4 id="2.4.3">Related Works</h4>



1. **Attention Is (not) All You Need for Commonsense Reasoning** ACL (2019)

   *Tassilo Klein, Moin Nabi* [[pdf](https://aclanthology.org/P19-1477.pdf)]

2. **COMET: Commonsense Transformers for Automatic Knowledge Graph Construction** ACL (2019)

   *Antoine Bosselut, Hannah Rashkin, Maarten Sap, Chaitanya Malaviya, Asli Celikyilmaz, Yejin Choi* [[pdf](https://aclanthology.org/P19-1470.pdf)] [[project](https://github.com/atcbosselut/comet-commonsense)]

3. **Explain Yourself! Leveraging Language Models for Commonsense Reasoning** ACL (2019)

   *Nazneen Fatema Rajani, Bryan McCann, Caiming Xiong, Richard Socher* [[pdf](https://aclanthology.org/P19-1487.pdf)] [[project](https://github.com/salesforce/cos-e)]

4. **Commonsense Knowledge Mining from Pretrained Models** EMNLP (2019)

   *Joe Davison, Joshua Feldman, Alexander M. Rush* [[pdf](https://aclanthology.org/D19-1109.pdf)]

5. **Modeling Event Background for If-Then Commonsense Reasoning Using Context-aware Variational Autoencoder** EMNLP (2019)

   *Li Du, Xiao Ding, Ting Liu, Zhongyang Li* [[pdf](https://aclanthology.org/D19-1270.pdf)] [[project](https://github.com/sjcfr/CWVAE)]

6. **How Reasonable are Common-Sense Reasoning Tasks: A Case-Study on the Winograd Schema Challenge and SWAG** EMNLP (2019)

   *Paul Trichelair, Ali Emami, Adam Trischler, Kaheer Suleman, Jackie Chi Kit Cheung* [[pdf](https://aclanthology.org/D19-1335.pdf)] [[project](https://github.com/ptrichel/How-Reasonable-are-Common-Sense-Reasoning-Tasks)]

7. **Guided Generation of Cause and Effect** IJCAI (2020)

   *Zhongyang Li, Xiao Ding, Ting Liu, J. Edward Hu, Benjamin Van Durme* [[pdf](https://www.ijcai.org/proceedings/2020/0502.pdf)] [[project](http://nlp.jhu.edu/causalbank)]

8. **Contrastive Self-Supervised Learning for Commonsense Reasoning** ACL (2020)

   *Tassilo Klein, Moin Nabi* [[pdf](https://aclanthology.org/2020.acl-main.671.pdf)] [[project](https://github.com/SAP-samples/acl2020-commonsense/)]

9. **Pre-training Is (Almost) All You Need: An Application to Commonsense Reasoning** ACL (2020)

   *Alexandre Tamborrino, Nicola Pellicanò, Baptiste Pannier, Pascal Voitot, Louise Naudin* [[pdf](https://aclanthology.org/2020.acl-main.357.pdf)]

10. **Evidence-Aware Inferential Text Generation with Vector Quantised Variational AutoEncoder** ACL (2020)

      *Daya Guo, Duyu Tang, Nan Duan, Jian Yin, Daxin Jiang, Ming Zhou* [[pdf](https://aclanthology.org/2020.acl-main.544.pdf)] [[project](https://github.com/microsoft/EA-VQ-VAE)]

11. **Scalable Multi-Hop Relational Reasoning for Knowledge-Aware Question Answering** EMNLP (2020)

      *Yanlin Feng, Xinyue Chen, Bill Yuchen Lin, Peifeng Wang, Jun Yan, Xiang Ren* [[pdf](https://aclanthology.org/2020.emnlp-main.99.pdf)] [[project](https://github.com/INK-USC/MHGRN)]

12. **Back to the Future: Unsupervised Backprop-based Decoding for Counterfactual and Abductive Commonsense Reasoning** EMNLP (2020)

      *Lianhui Qin, Vered Shwartz, Peter West, Chandra Bhagavatula, Jena D. Hwang, Ronan Le Bras, Antoine Bosselut, Yejin Choi* [[pdf](https://aclanthology.org/2020.emnlp-main.58.pdf)] [[project](https://github.com/qkaren/unsup_gen_for_cms_reasoning)]

13. **Self-Supervised Knowledge Triplet Learning for Zero-Shot Question Answering** EMNLP (2020)

      *Pratyay Banerjee, Chitta Baral* [[pdf](https://aclanthology.org/2020.emnlp-main.11.pdf)]

14. **Paragraph-level Commonsense Transformers with Recurrent Memory** AAAI (2021)

      *Saadia Gabriel, Chandra Bhagavatula, Vered Shwartz, Ronan Le Bras, Maxwell Forbes, Yejin Choi* [[pdf](https://arxiv.org/pdf/2010.01486.pdf)] [[project](https://github.com/skgabriel/paracomet)]

15. **Knowledge-driven Data Construction for Zero-shot Evaluation in Commonsense Question Answering** AAAI (2021)

      *Kaixin Ma, Filip Ilievski, Jonathan Francis, Yonatan Bisk, Eric Nyberg, Alessandro Oltramari* [[pdf](https://arxiv.org/pdf/2011.03863.pdf)] [[project](https://github.com/Mayer123/HyKAS-CSKG)]

16. **Doing Good or Doing Right? Exploring the Weakness of Commonsense Causal Reasoning Models** ACL (2021)

      *Mingyue Han, Yinglin Wang* [[pdf](https://aclanthology.org/2021.acl-short.20.pdf)]

17. **Learning Event Graph Knowledge for Abductive Reasoning** ACL (2021)

      *Li Du, Xiao Ding, Ting Liu, Bing Qin* [[pdf](https://aclanthology.org/2021.acl-long.403.pdf)] [[project](https://github.com/sjcfr/ege-RoBERTa)]

18. **ExCAR: Event Graph Knowledge Enhanced Explainable Causal Reasoning** ACL (2021)

      *Li Du, Xiao Ding, Kai Xiong, Ting Liu, Bing Qin* [[pdf](https://aclanthology.org/2021.acl-long.183.pdf)] [[project](https://github.com/sjcfr/ExCAR)]

19. **Differentiable Open-Ended Commonsense Reasoning** NAACL (2021)

      *Bill Yuchen Lin, Haitian Sun, Bhuwan Dhingra, Manzil Zaheer, Xiang Ren, William W. Cohen* [[pdf](https://aclanthology.org/2021.naacl-main.366.pdf)] [[project](https://open-csr.github.io/)]

20. **QA-GNN: Reasoning with Language Models and Knowledge Graphs for Question Answering** NAACL (2021)

      *Michihiro Yasunaga, Hongyu Ren, Antoine Bosselut, Percy Liang, Jure Leskovec* [[pdf](https://aclanthology.org/2021.naacl-main.45.pdf)] [[project](https://github.com/michiyasunaga/qagnn)]

21. **Towards Zero-shot Commonsense Reasoning with Self-supervised Refinement of Language Models** EMNLP (2021)

      *Tassilo Klein, Moin Nabi* [[pdf](https://aclanthology.org/2021.emnlp-main.688.pdf)] [[project](https://github.com/SAP-samples/emnlp2021-contrastive-refinement)]

22. **Exploring Strategies for Generalizable Commonsense Reasoning with Pre-trained Models** EMNLP (2021)

      *Kaixin Ma, Filip Ilievski, Jonathan Francis, Satoru Ozaki, Eric Nyberg, Alessandro Oltramari* [[pdf](https://aclanthology.org/2021.emnlp-main.445.pdf)] [[project](https://github.com/Mayer123/CS_Model_Adaptation)]

23. **Shortcutted Commonsense: Data Spuriousness in Deep Learning of Commonsense Reasoning** EMNLP (2021)

      *Ruben Branco, António Branco, João António Rodrigues, João Ricardo Silva* [[pdf](https://aclanthology.org/2021.emnlp-main.113.pdf)] [[project](https://github.com/nlx-group/Shortcutted-Commonsense-Reasoning)]

24. **Improving Unsupervised Commonsense Reasoning Using Knowledge-Enabled Natural Language Inference** EMNLP findings (2021)

      *Canming Huang, Weinan He, Yongmei Liu* [[pdf](https://aclanthology.org/2021.findings-emnlp.420.pdf)] [[project](https://github.com/sysuhcm/NLI-KB)]

25. **Uncovering Implicit Gender Bias in Narratives through Commonsense Inference** EMNLP findings (2021)

      *Tenghao Huang, Faeze Brahman, Vered Shwartz, Snigdha Chaturvedi* [[pdf](https://aclanthology.org/2021.findings-emnlp.326.pdf)] [[project](https://github.com/tenghaohuang/Uncover_implicit_bia)]

26. **SalKG: Learning From Knowledge Graph Explanations for Commonsense Reasoning** NIPS (2021)

      *Aaron Chan, Jiashu Xu, Boyuan Long, Soumya Sanyal, Tanishq Gupta, Xiang Ren* [[pdf](https://proceedings.neurips.cc/paper/2021/file/9752d873fa71c19dc602bf2a0696f9b5-Paper.pdf)] [[project](https://github.com/INK-USC/SalKG)]

27. **GreaseLM: Graph REASoning Enhanced Language Models** ICLR Spotlight (2022)

      *Xikun Zhang, Antoine Bosselut, Michihiro Yasunaga, Hongyu Ren, Percy Liang, Christopher D. Manning, Jure Leskovec* [[pdf](https://openreview.net/pdf?id=41e9o6cQPj)] [[project](https://github.com/snap-stanford/GreaseLM)]






























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


### Papers
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
