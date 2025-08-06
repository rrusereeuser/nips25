# CCTalker: When Compensatory Control Theory Meets 3D Emotional Talking Head Animation

![CCTalker Demo](https://raw.githubusercontent.com/rrusereeuser/nips25/main/paper_images/CCTalker.png)

**Official Project Page:** [cv2025.github.io/bwbwiwn.site](http://cv2025.github.io.bwbwiwn.site/) • **Code (anonymous):** [4open.science/CCTalker-D626](https://anonymous.4open.science/r/CCTalker-D626/)

---

## 🔍 Overview

CCTalker is a diffusion-based framework for speech-driven 3D talking-head animation that integrates **Compensatory Control Theory (CCT)** to improve emotional expressivity and temporal coherence. Inspired by human self-regulation, CCTalker interprets animation artifacts (e.g., misalignments, abrupt motions) as "loss-of-control" events and applies three collaborative modules—each executing a full CCT loop—to restore order:

1. **Control–Sense Modeling (CSM)**: Aligns frame-level emotion and audio control signals with mesh predictions, gating unexpected deviations.
2. **Compensatory Dynamic Enhancement (CDE)**: Detects dynamic regions via vertex speed masks and applies high-frequency detail enhancement or low-frequency smoothing.
3. **Information Order Modeling (IOM)**: Enforces cross-modal semantic alignment, causal temporal continuity, and physical plausibility across the full sequence.

Together, these modules follow an **align → refine → integrate** flow, yielding smoother, more expressive 3D facial animations.

## 🚀 Key Contributions

* **Psychology-Informed Paradigm**: First integration of CCT into 3D facial animation, bridging macro-level theory and micro-level operations.
* **Unified Compensatory Modules**: Three self-contained CCT loops addressing emotional consistency, dynamic detail, and sequence coherence.
* **State-of-the-Art Results**: Outperforms leading auto-regressive and diffusion-based baselines on the 3DMEAD and BIWI datasets.

## 🎬 Demos

Visit our [Project Page](http://cv2025.github.io.bwbwiwn.site/) for interactive videos showcasing CCTalker under various emotions and intensities.

## 📦 Installation

```bash
# Clone repository

# Install dependencies
```
*Note: Official code release pending paper acceptance.*

## ⚙️ Usage

```
1. **Prepare data**
2. **Train model**
3. **Inference**
4. **Visualization**
```
*Note: Official code release pending paper acceptance.*

## 📄 Citation

If you find this work useful, please cite:

```bibtex
@article{2025cctalker,
  title={CCTalker: When Compensatory Control Theory Meets 3D Emotional Talking Head Animation},
  author={Anonymous},
  year={2025},
  archivePrefix={arXiv},
  primaryClass={cs.CV}
}
```

## 🤝 Acknowledgements

Some components are based on the following open-source projects:

* [FaceDiffuser](https://github.com/uuembodiedsocialai/FaceDiffuser)
* Template inspired by [SyncTalk](https://github.com/ziqiaopeng/SyncTalk)

---

*Developed by the CCTalker team. For questions or contributions, please open an issue.*
