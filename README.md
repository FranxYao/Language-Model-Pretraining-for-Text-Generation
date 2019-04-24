# Language-Model-Pretraining-for-Text-Generation
LM pretraining for generation, reading list, resources, conference mappings. 

First, the four mosts well known models: 

* Language Models are Unsupervised Multitask Learners (GPT2)

* BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding, NAACL 19 

* Improving Language Understanding by Generative Pre-Training (GPT)

* Deep contextualized word representations (ELMo)

In general, the current (more or less) consensus is, BERT is not suitable for generation. But GPT is. Because of the uni-directional v.s. bi-directional objective. s

Then, other published models 

* Unsupervised Pretraining for Sequence to Sequence Learning, EMNLP 17 
  * Prajit Ramachandran and Peter J. Liu and Quoc V. Le, Google Brain 
  * The LM pretraining idea, before BERT. Effective on MT and Summarization. 

* Pre-trained Language Model Representations for Language Generation, NAACL 19
  * Sergey Edunov, Alexei Baevski, Michael Auli, FAIR
  * LM pretraining fine tuned on different size of MT data. The smaller the more performance gain. 

* Semi-Supervised Sequence Modeling with Cross-View Training. (CVT) EMNLP 18  
  * Kevin Clark, Minh-Thang Luong, Christopher D. Manning, Quoc V. Le
  * Semi-supervised learning with multi-task learning. MT is one application. Also improvements on other tasks 

And other Arxiv papers

* Few-shot NLG with Pre-trained Language Model
  * Zhiyu Chen, Harini Eavani, Yinyin Liu, and William Yang Wang
  * Extreme few-shot supervision: **50 training instances get 26 BLEU**

* Cross-lingual Language Model Pretraining, Arxiv 19 
  * Guillaume Lample, Alexis Conneau, FAIR 
  * Application to Cross-lingual classification, Unsupervised machine translation, Supervised machine translation (low-resource), Low-resource language model 

* BERT has a Mouth, and It Must Speak: BERT as a Markov Random Field Language Model, Arxiv 19 
  * Alex Wang, Kyunghyun Cho, NYU 
  * Directly sample from BERT, not as effective. 

* Constant-Time Machine Translation with Conditional Masked Language Models ([link](https://arxiv.org/pdf/1904.09324.pdf))
  * Marjan Ghazvininejad, Omer Levy, Yinhan Liu and Luke Zettlemoyer
  * Iterative decoding: generate with BERT, then polish with BERT, then continue polish

