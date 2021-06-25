# Papers-Stack
Keeping a track of research papers I've read.

Keys -> ||
:white_check_mark: : Done reading ||
:book: : In progress ||
:no_entry_sign: : Dropped ||


|No.| Status | Paper Name | Notes | Link | Year
|---| ---------------- | --------------- | --------------- | --- | --- |
|1| ✅ | WaveNet: A Generative Model for Raw Audio| notes |[arxiv](https://arxiv.org/abs/1609.03499) | 2016
| |                    | _Causal conv. layers with dilation. Autoregression model. Sequential inference_ | |
|2| ✅ | Fast Wavenet Generation Algorithm| notes |[arxiv](https://arxiv.org/abs/1611.09482) | 2016
| |                    | _WaveNet improvement. O(2<sup> L</sup>) -> O(L). Still sequential though. <br> Use queues to push & pop already computed states at each layer_ | |
|3| ✅ | Parallel WaveNet: Fast High-Fidelity Speech Synthesis | | [arxiv](https://arxiv.org/abs/1711.10433) | 2017
| | ⬇️⬆️ | Probability Density Distillation - Teacher + student based architecture. Marries efficient training of Wavenet with efficient IAF for sampling. Sampling is parallel here for realtime synthesis.<br>✔️[medium - An Explanation of Discretized Logistic Mixture Likelihood](https://medium.com/@smallfishbigsea/an-explanation-of-discretized-logistic-mixture-likelihood-bdfe531751f0)  <br> ✔️ [vimeo - Parallel WaveNet](https://vimeo.com/287766925) | |
|4|📕  | Improved Variational Inference with Inverse Autoregressive Flow || [arxiv](https://arxiv.org/abs/1606.04934) | 2016
| |⬇️⬆️| ⭐ ✔️ Introduction to Normalizing Flows (ECCV2020 Tutorial)| | [video](https://www.youtube.com/watch?v=u3vVyFVU_lI)|
|5| ✅ | Deep Unsupervised Learning UC Berkeley lectures | | [course](https://sites.google.com/view/berkeley-cs294-158-sp20/home) |
| |    | ✔️ L1 - Introduction -> Types: 1. Generative models 2. Self-supervised models| | 1:10:00 |
| |    | ✔️ L2 - Autoregressive Models -> histogram. parameterized distribution. 1.)RNN based 2.)Masking based. 2.1)MADE 2.2)Masked ConvNets | | 2:27:23 |
| |    | ✔️ L3 - Flow Models -> Model output != p_theta(x); instead z=f_theta(x). z comes from a prob dist. Sampling is inverse of f_inverse_theta(x). <br> -> Autoregressive Flows:- Fast training; Slow sampling <br> -> Inverse Autoregressive Flow:- Slow training; Fast Sampling  | | 1:56:53 |
| |     |  | |
| |     |  | |
|.| 🚫 | dummy | | link3 |
