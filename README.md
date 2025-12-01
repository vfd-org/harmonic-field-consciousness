🚀 A Harmonic Field Model of Consciousness in the Human Brain
Code, Figures, and Reproducible Materials

This repository accompanies the paper:

Lee Smart (2025).
A Harmonic Field Model of Consciousness in the Human Brain.
Independent Researcher, Vibrational Field Dynamics Project.

The paper presents a unified, mathematically grounded account of consciousness based on connectome harmonics, oscillatory gating, and mode-wide integration, resolving the long-standing delta paradox and integrating recent advances in population coding and mixed selectivity (MillerLab, 2024–2025).

This repository contains the full reproducible workflow:

Python scripts for generating all five figures

Synthetic harmonic-mode simulations

Example “brain graph” Laplacians

Consciousness functional evaluation (H_mode, PR, R(t), Ṡ, κ)

LaTeX source for the full manuscript

Optional extensions for real-data examples (EEG/MEG using MNE)

📁 Repository Structure
harmonic-field-consciousness/
│
├── figures/
│   ├── fig1_harmonic_modes.png
│   ├── fig2_mode_power_states.png
│   ├── fig3_consciousness_components.png
│   ├── fig4_delta_paradox.png
│   ├── fig5_oscillatory_gating.png
│
├── code/
│   ├── generate_fig1_modes.py
│   ├── generate_fig2_states.py
│   ├── generate_fig3_functional.py
│   ├── generate_fig4_delta_paradox.py
│   ├── generate_fig5_gating.py
│   └── utils.py
│
├── latex/
│   ├── main.tex
│   ├── macros.tex
│   ├── refs.bib
│   └── sections/
│       ├── 01_intro.tex
│       ├── 02_geometry.tex
│       ├── 03_modes_dynamics.tex
│       ├── 04_consciousness_functional.tex
│       ├── 05_delta_paradox.tex
│       ├── 06_vfd_bridge.tex
│       ├── 07_discussion_future.tex
│       └── 08_appendix_math.tex
│
└── README.md

🔬 Reproducibility

All figures in the paper can be reproduced by running:

python code/generate_fig1_modes.py
python code/generate_fig2_states.py
python code/generate_fig3_functional.py
python code/generate_fig4_delta_paradox.py
python code/generate_fig5_gating.py


The scripts require only standard Python scientific libraries:

NumPy

SciPy

Matplotlib

NetworkX

(Optional real-data examples require mne).

🧠 About the Paper

The model formalizes consciousness as a global field configuration across the connectome:

The connectome Laplacian eigenmodes (ψₖ) form the natural harmonic basis.

Dynamics follow modewise second-order oscillators with nonlinear coupling.

Consciousness corresponds to a state with:

high harmonic richness

high mode participation ratio

high phase coherence

positive entropy production

a stable but metastable criticality index

This approach resolves the Delta Paradox by showing that frequency bands do not determine conscious state —
global field configuration and oscillatory gating do.

The framework is substrate-agnostic (biological, artificial, hybrid) and geometry-agnostic (any Laplace-type operator).

📬 Contact

Author: Lee Smart
Independent Researcher
Vibrational Field Dynamics Project

Email:
📧 contact@vibrationalfielddynamics.org

Twitter/X:
🔗 @vfd_org

📄 Citation

If you use this work, please cite:

Smart, L. (2025).
A Harmonic Field Model of Consciousness in the Human Brain.
Vibrational Field Dynamics Project.
https://github.com/vfd-org/harmonic-field-consciousness


(Once an arXiv DOI is available, we can update this block.)

🎯 Goals of This Repository

Enable transparent reproducibility of all figures

Provide a clean scientific baseline for further extensions

Support researchers studying:

connectome harmonics

population coding

mixed selectivity

oscillatory gating

consciousness metrics

large-scale neural dynamics

Offer a foundation for future publications and more advanced models

🔗 License

MIT License — open for academic and scientific use.

⭐ Final Note

This repository represents the “public scientific layer” of a larger ongoing research program exploring harmonic field dynamics and large-scale integrative neuroscience. Contributions, discussions, and collaborations are welcome.
