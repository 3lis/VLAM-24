# VLAM-24

Material for the course *Vision-Language-Action Models for Robotics and Autonomous Vehicles*.

Alice Plebe, March 2024.

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

## Exam

The exam is an oral presentation of a recent paper.
The list of papers to choose from is available [here](https://docs.google.com/spreadsheets/d/1_BlpGtml7ehKrvqoQ4U4G6oNvlb4T7-adD69wPUzOso).