# FantasyHSI: Video-Generation-Centric 4D Human Synthesis In Any Scene through A Graph-based Multi-Agent Framework

[![Home Page](https://img.shields.io/badge/Project-FantasyHSI-blue.svg)](https://fantasy-amap.github.io/fantasy-hsi/)
[![arXiv](https://img.shields.io/badge/Arxiv-2508.11255-b31b1b.svg?logo=arXiv)](https://arxiv.org/abs/2508.11255)
[![hf_paper](https://img.shields.io/badge/🤗-FantasyHSI-red.svg)](https://huggingface.co/papers/2508.11255)

## Abstract
Human-Scene Interaction (HSI) seeks to generate realistic human behaviors within complex environments, yet it faces significant challenges in handling long-horizon, high-level tasks and generalizing to unseen scenes.  To address these limitations, we introduce FantasyHSI, a novel HSI framework centered on video generation and multi-agent systems that operates without paired data.  We model the complex interaction process as a dynamic directed graph, upon which we build a collaborative multi-agent system.  This system comprises a scene navigator agent for environmental perception and high-level path planning, and a planning agent that decomposes long-horizon goals into atomic actions.  Critically, we introduce a critic agent that establishes a closed-loop feedback mechanism by evaluating the deviation between generated actions and the planned path.  This allows for the dynamic correction of trajectory drifts caused by the stochasticity of the generative model, thereby ensuring long-term logical consistency.  To enhance the physical realism of the generated motions, we leverage Direct Preference Optimization (DPO) to train the action generator, significantly reducing artifacts such as limb distortion and foot-sliding. Extensive experiments on our custom SceneBench benchmark demonstrate that FantasyHSI significantly outperforms existing methods in terms of generalization, long-horizon task completion, and physical realism.

## 🔗Citation
If you find this repository useful, please consider giving a star ⭐ and citation
```
@misc{wang2025fantasytalking2timesteplayeradaptivepreference,
      title={FantasyHSI: Video-Generation-Centric 4D Human Synthesis In Any Scene through A Graph-based Multi-Agent Framework}, 
      author={Linzhou Mu and Qiang Wang and Fan Jiang and Mengchao Wang and Yaqi Fan and Mu Xu and Kai Zhang},
      year={2025},
      eprint={2508.11255},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2508.11255}, 
}
```
