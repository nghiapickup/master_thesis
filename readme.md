Master thesis - Study on Semi-Supervised Learning with the Framework of Generative Model
===
@ Nguyen Hoang Nghia - Defense date: June 26, 2019

This repository contains my master thesis on semi-supervised learning. 

Here we have
- [Thesis](https://github.com/nghiapickup/master_thesis/blob/master/thesis.pdf)
- Source code, experimental results: see the last heading below


Quick summary
---
I examined two generative methods of semi-supervised learning. Here is a quick summary:
- The first is the warm-up part with the common mixtur of multinomial models in *chapter 2*, I argured a trivial problem of the need of initialization of sub-components in class conditional distribution. You may only want to read *section 2.3* if you are familiar with this model.
- The main result is in *chapter 3* where I employed a simple graphical model for the graph representation of data (graph-based methods). It is faster to only follow the *section 3.3*.

If you want to know more about my motivation, you may refer to *section 1.2* of *Introduction* and the last paragraph of *Discussion* chapter.


Experimental Results (exp_results/)
---

| Name  | Description | source code |
| --- | --- | --- |
| ssl_multinomial_exp | Naive Bayes multinomial for text data | [link](https://github.com/nghiapickup/ssl_multinomial) |
| ssl_mincut_graphical_exp | Mincut graph-based and corresponding graphical model setup | [link](https://github.com/nghiapickup/ssl_mincut_graphical_model) |