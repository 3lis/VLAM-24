# VLAM-24

Material for the course *Vision-Language-Action Models for Robotics and Autonomous Vehicles*.

Alice Plebe, March 2024.

## Slides, Recordings, and Exam

The lesson slides are available 
[here](https://www.dropbox.com/scl/fi/j9kxntxrj519jortstimm/slides.pdf?rlkey=j2enserwm8kkw1urn09kjimaz&dl=0).
Video recording of the lessons are available as well:

- [Lesson 1](https://www.dropbox.com/scl/fi/9sn950gk5ubpfvuqim3xw/lesson_01.mp4?rlkey=j49hc384f11dyn0d5300vjvnf&dl=0) (26/03/2024)
- [Lesson 2](https://www.dropbox.com/scl/fi/qllork1xrf7ssypjpljbr/lesson_02.mp4?rlkey=hrfidmbag3ug6l91sc6sqrken&dl=0) (27/03/2024)
- [Lesson 3](https://www.dropbox.com/scl/fi/hififujw7vw24ie6cyor9/lesson_03.mp4?rlkey=bu6ltdsfnlie6bqn53fneup34&dl=0) (28/03/2024)- Lesson 4 (TBD)

The **exam is an oral presentation** of a recent paper.
The list of papers to choose from is available [here](https://docs.google.com/spreadsheets/d/1_BlpGtml7ehKrvqoQ4U4G6oNvlb4T7-adD69wPUzOso).

## Software

- `attention.ipynb` contains:
	- an example of word embedding using GloVe,
	- an implementation of multi-head attention layer from scratch.
- `transformer.ipynb` contains:
	- an example of Tokenizer using SimpleBooks,
	- an implementation of Transformer block with visualization of attention matrix,
	-  an implementation of a simple GPT model producing completions with different Samplers.
- `pendulum.ipynb` contains an implementation of Transformer for time-series prediction usign Time2Vec embedding.
- `gpt4v.ipynb` contains an example of using OpenAI API to make inference with GPT4v.

## Downloads
Files used in the software:

- [`glove.6B.50d.txt`](https://www.dropbox.com/scl/fi/y328s9lbz8c9glp7al02p/glove.6B.50d.txt?rlkey=m81pwe06f8tpb947fl3y78nlo&dl=0)
- [`simplebooks-92-raw_train.txt`](https://www.dropbox.com/scl/fi/r6vnn7vccpvscvmzabmvf/simplebooks-92-raw_train.txt?rlkey=thwnurvjrda737sr8283qpdkg&dl=0)
- [`simplebooks-92-raw_valid.txt`](https://www.dropbox.com/scl/fi/txlel36qe8nxz7jth95xp/simplebooks-92-raw_valid.txt?rlkey=8sdbtycdx2ppokcybaolvrx7j&dl=0)
- [`simplebooks-92-raw_test.txt`](https://www.dropbox.com/scl/fi/3j9eifu45sdwnhof3r63q/simplebooks-92-raw_test.txt?rlkey=5c8z385wsu925h9zugz7p2d8v&dl=0)
- [`vocab_10000.txt`](https://www.dropbox.com/scl/fi/aix95cadh32i9ylzjzz0m/vocab_10000.txt?rlkey=qcwpxhw34c8z2x7hue37zu79d&dl=0)
- [`transf_v10000_s128_h4_e50.h5`](https://www.dropbox.com/scl/fi/la654e3fsjfn6iwrlmm1d/transf_v10000_s128_h4_e50.h5?rlkey=9qkdroty1i2l9lu1euaxjtkvg&dl=0)
- [`transf_v10000_s128_h4_e200.h5`](https://www.dropbox.com/scl/fi/tvevf1ocgatw2v0nl624f/transf_v10000_s128_h4_e200.h5?rlkey=0pxwmhyicvkyxdae3jsc0znsb&dl=0)
- [`gpt_v10000_s128_l2_h4_e50.h5`](https://www.dropbox.com/scl/fi/ryn31mv5ne6k9mc18kffh/gpt_v10000_s128_l2_h4_e50.h5?rlkey=p8x4bhe5oxb8lpw3f54i970ud&dl=0)
- [`gpt_v10000_s128_l2_h4_e100.h5`](https://www.dropbox.com/scl/fi/ie0y2rk65z2encjhj203x/gpt_v10000_s128_l2_h4_e100.h5?rlkey=xo46jcgl1qywu5fm9bpzclg0z&dl=0)
- [`pend_t2v_e2000.h5`](https://www.dropbox.com/scl/fi/fgsfklo5z944acm6l0nu3/pend_t2v_e2000.h5?rlkey=ej6uqo6tpggmtn204r88vg6fu&dl=0)
- [`pend.zip`](https://www.dropbox.com/scl/fi/ell5z8bje172n0c6st0e3/pend.zip?rlkey=t5mxsl2cev6xbugogcd3ej028&dl=0)
- [`image_01.jpg`](https://www.dropbox.com/scl/fi/5fkn00h925xjf51jcodcj/c1.jpg?rlkey=2a7kjoqphqaz5mt1wl3c5bp4i&dl=0)
- [`image_02.jpg`](https://www.dropbox.com/scl/fi/s5089zy9pt5ed10ocn46y/c2.jpg?rlkey=01qndot441zgst8g8cdz0emqw&dl=0)
- [`image_03.jpg`](https://www.dropbox.com/scl/fi/u65cc3yaz91y45yu28eq8/c3.jpg?rlkey=6ynt5npd51k5z0zqy2k4s17fe&dl=0)
- [`image_04.jpg`](https://www.dropbox.com/scl/fi/djmfggr7ho1os4nihkzg5/c6.jpeg?rlkey=hdp41x87gac6pvggn7rgf989v&dl=0)


## Papers

List of papers cited during the lessons, and more.

#### Foundations of Language models

- T. Mikolov et al., "Distributed Representations of Words and Phrases and their Compositionality", NeurIPS (2013).
- J. Pennington et al., "GloVe: Global Vectors for Word Representation", EMNLP (2014).
- D. Bahdanau et al., "Neural machine translation by jointly learning to align and translate", arXiv (2014).
- P. Christiano et al., "Deep Reinforcement Learning from Human Preferences", NeurIPS (2017).
- A. Vaswani et al., "Attention Is All You Need", NeurIPS (2017).
- A. Radford et al., "Improving Language Understanding by Generative Pre-Training" (2018).
- A. Radford et al., "Language Models are Unsupervised Multitask Learners" (2019).
- S. Kazemi et al., "Time2Vec: Learning a Vector Representation of Time", arXiv (2019).
- T. Brown et al., "Language Models are Few-Shot Learners", NeurIPS (2020).
- D. Ziegler et al., "Fine-Tuning Language Models from Human Preferences", arXiv (2020).
- L. Ouyang et al., "Training language models to follow instructions with human feedback", arXiv (2022).
- G. Franceschelli & M. Musolesi, "Reinforcement Learning for Generative AI: State of the Art, Opportunities and Open Research Challenges", Journal of Artificial Intelligence Research (2024).

#### Foundations of Multimodal Language models

- A. Ramesh et al., "Zero-Shot Text-to-Image Generation", PMLR (2020).
- A. Dosovitskiy et al., "An image is worth 16x16 words: Transformers for image recognition at scale", ICLR (2021).
- C. Jia et al., "Scaling Up Visual and Vision-Language Representation Learning With Noisy Text Supervision", PMLR (2021).
- A. Radford et al., "Learning Transferable Visual Models From Natural Language Supervision", PMLR (2021).
- M. Tsimpoukelli et al., "Multimodal Few-Shot Learning with Frozen Language Models", NeurIPS (2021).
- Z. Yang et al., "The Dawn of LMMs: Preliminary Explorations with GPT-4V(ision)", arXiv (2023).

#### Language models for Autonomous driving

- X. Li et al., "Towards Knowledge-driven Autonomous Driving", arXiv (2023).
- S. Wang et al., "ChatGPT as Your Vehicle Co-Pilot: An
Initial Attempt", IEEE T-IV (2023).
- L. Wen et al., "On the Road with GPT-4V(ision): Early Explorations of Visual-Language Model on Autonomous Driving", arXiv (2023).
- C. Cui et al., "A Survey on Multimodal Large Language Models for Autonomous Driving", WACV (2024).
- D. Fu et al., "Drive like a human: Rethinking autonomous driving with large language models", WACV (2024).
- S. Luo et al., "Delving into Multi-modal Multi-task Foundation Models for Road Scene Understanding: From Learning Paradigm Perspectives", arXiv (2024).

#### Language models for Robotics

- M. Ahn et al., "Do As I Can, Not As I Say: Grounding Language in Robotic Affordances", arXiv (2022).
- W. Huang et al., "Inner Monologue: Embodied Reasoning through Planning with Language Models", arXiv (2022).
- A. Brohan et al., "RT-1: Robotics Transformer
for Real-world Control at Scale", arXiv (2023).
- A. Brohan et al., "RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control", arXiv (2023).
- R. Firoozi et al., "Foundation Models in Robotics: Applications, Challenges, and the Future", arXiv (2023).
- S. Vemprala et al., "ChatGPT for Robotics:
Design Principles and Model Abilities", arXiv (2023).
- M. Ahn et al., "AutoRT: Embodied Foundation Models For Large Scale Orchestration of Robotic Agents", arXiv (2024).

