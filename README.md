# Language-Model-Pretraining-for-Text-Generation
LM pretraining for generation, reading list, resources, conference mappings. 

First, the four mosts well known models: 

* Language Models are Unsupervised Multitask Learners (GPT2)

* BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding

* Improving Language Understanding by Generative Pre-Training (GPT)

* Deep contextualized word representations (ELMo)

In general, the current (more or less) consensus is, BERT is not suitable for generation. But GPT is. Because of the uni-directional v.s. bi-directional objective. s

Then, other important models 

* Unsupervised Pretraining for Sequence to Sequence Learning, EMNLP 17 
  * Prajit Ramachandran and Peter J. Liu and Quoc V. Le, Google Brain 
  * The LM pretraining idea, before BERT. Effective on MT and Summarization. 

* Pre-trained Language Model Representations for Language Generation, NAACL 19
  * Sergey Edunov, Alexei Baevski, Michael Auli, FAIR
  * LM pretraining fine tuned on different size of MT data. The smaller the more performance gain. 

* BERT has a Mouth, and It Must Speak: BERT as a Markov Random Field Language Model, Arxiv 19 
  * Alex Wang, Kyunghyun Cho, NYU 
  * Directly sample from BERT, not as effective. 

* Cross-lingual Language Model Pretraining, Arxiv 19 
  * Guillaume Lample, Alexis Conneau, FAIR 
  * Application to Cross-lingual classification, Unsupervised machine translation, Supervised machine translation (low-resource), Low-resource language model 
