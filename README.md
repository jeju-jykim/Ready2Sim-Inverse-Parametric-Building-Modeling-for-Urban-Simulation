# [KDD 2026 AI for Sciences Track] Ready to Sim? Inverse Parametric Building Modeling via Universal Anchor Representation for Urban Simulation

Official implementation of 'Ready to Sim? Inverse Parametric Building Modeling via Universal Anchor Representation for Urban Simulation'.

Jaeyeon Kim, Po-Yen Lai, Jian Cheng Wong, Chin Chun Ooi, Yew-Soon Ong, Ivor Tsang

Institute of Advanced Intelligence and Computing (IAIC), A\*STAR, Singapore &nbsp;·&nbsp; Nanyang Technological University, Singapore

[Paper](https://openreview.net/forum?id=HDWuV3E94L)

## Abstract

Physics-based urban simulations require editable, topology-valid building representations, yet urban data are typically available only as images or segmentation masks. We propose Universal Anchor Representation (UAR), a normalized hierarchical parameterization that constrains inference to bounded coordinates $(t, s) \in [0, 1]^2$ while guaranteeing structural connectivity by construction. We pair UAR with a domain-specific language and compiler to produce executable parametric procedural graphs, and develop a vision-language model (VLM) guided pipeline with overlay-based refinement to recover them from top-view building images. Experiments on 110 real urban buildings spanning 11 morphological categories demonstrate that UAR-based generation achieves 75.2% F1 score and 100% compilation success, substantially outperforming absolute-coordinate generation, which attains 43.1% F1 and 57% success under identical model and prompt configurations. Wind simulation case studies further confirm that recovered parameters yield physically interpretable changes in flow fields under parametric edits.

## Poster

[Poster (PDF)](assets/poster.pdf)

Code released soon.

## Citation

If you find Ready2Sim useful in your research, please cite our paper:

```bibtex
@inproceedings{
kim2026ready,
title={Ready to Sim? Inverse Parametric Building Modeling via Universal Anchor Representation for Urban Simulation},
author={Jaeyeon Kim and Po-Yen Lai and Jian Cheng Wong and Chin Chun Ooi and Yew-Soon Ong and Ivor Tsang},
booktitle={32nd SIGKDD Conference on Knowledge Discovery and Data Mining - AI for Sciences Track},
year={2026},
url={https://openreview.net/forum?id=HDWuV3E94L}
}
```
