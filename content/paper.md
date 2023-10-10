## CausalTime: Realistically Generated Time-series for Benchmarking of Causal Discovery
<!-- **Yuxiao Cheng, Ziqian Wang, Tingxiong Xiao, Qin Zhong, Jinli Suo, Kunlun He** -->

A novel pipeline capable of generating realistic time-series along with a ground truth causal graph that is generalizable to different fields.

<!-- [arXiv](https://arxiv.org/abs/2310.01753) | [Code🧑‍💻](https://github.com/jarrycyx/UNN/tree/main/CausalTime) ｜ [Official Website](https://www.causaltime.cc/) -->


## Abstract
Time-series causal discovery (TSCD) is a fundamental problem of machine learning. However, existing synthetic datasets cannot properly evaluate or predict the algorithms' performance on real data. This study introduces the CausalTime pipeline to generate time-series that highly resemble the real data and with ground truth causal graphs for quantitative performance evaluation. The pipeline starts from real observations in a specific scenario and produces a matching benchmark dataset. Firstly, we harness deep neural networks along with normalizing flow to accurately capture realistic dynamics. Secondly, we extract hypothesized causal graphs by performing importance analysis on the neural network or leveraging prior knowledge. Thirdly, we derive the ground truth causal graphs by splitting the causal model into causal term, residual term, and noise term. Lastly, using the fitted network and the derived causal graph, we generate corresponding versatile time-series proper for algorithm assessment. In the experiments, we validate the fidelity of the generated data through qualitative and quantitative experiments, followed by a benchmarking of existing TSCD algorithms using these generated datasets. CausalTime offers a feasible solution to evaluating TSCD algorithms in real applications and can be generalized to a wide range of fields. For easy use of the proposed approach, we also provide a user-friendly website, hosted on www.causaltime.cc.

![](https://raw.githubusercontent.com/jarrycyx/UNN/main/CausalTime/figures/arch.png)
<!-- <img src="https://raw.githubusercontent.com/jarrycyx/UNN/main/CausalTime/figures/arch.png" width="50%" align="center" /> -->


## Citing

If you find this dataset useful in your research, please consider citing us.

 <!-- the following paper: -->
<!-- ```bibtex
@misc{cheng2023causaltime,
      title={CausalTime: Realistically Generated Time-series for Benchmarking of Causal Discovery}, 
      author={Yuxiao Cheng and Ziqian Wang and Tingxiong Xiao and Qin Zhong and Jinli Suo and Kunlun He},
      year={2023},
      eprint={2310.01753},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
}
``` -->
