# 🤖 FrugalAI Chip: Modular Silicon Architecture for Disposable AI

[![Read in Spanish](https://img.shields.io/badge/Lang-Leer%20en%20Español-red?style=flat&logoColor=white&color=B31B1B)](https://github.com/NachoPeinador/FRUGAL_AI_CHIP/blob/main/README_es.md)
[![License](https://img.shields.io/badge/License-PolyForm_Noncommercial_1.0.0-blue.svg)](https://polyformproject.org/licenses/noncommercial/1.0.0/)
[![Python](https://img.shields.io/badge/Python-3.10%2B-green.svg)]()
[![PyTorch](https://img.shields.io/badge/PyTorch-2.0%2B-orange.svg)]()
[![Status](https://img.shields.io/badge/Status-Research_Complete-brightgreen.svg)]()
[![Papers](https://img.shields.io/badge/Paper-Read_PDF-B31B1B?style=flat&logo=latex&logoColor=white)](https://github.com/NachoPeinador/FRUGAL_AI_CHIP/blob/main/Papers/FrugalAI_Chip_v2.pdf)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Run_Experiments-F37626.svg?style=flat&logo=Jupyter)](./Notebooks/Frugal_AI_Complete_Suite.ipynb)
[![DOI](https://img.shields.io/badge/DOI-10.5281/zenodo.18508385-blue)](https://doi.org/10.5281/zenodo.18508385)

**Author**: José Ignacio Peinador Sala
**Contact**: joseignacio.peinador@gmail.com
**ORCID**: [0009-0008-1822-3452](https://orcid.org/0009-0008-1822-3452)

---

## 🔍 Vision

FrugalAI challenges the "**performance at any cost**" dogma of the semiconductor industry. As manufacturing costs in advanced nodes (3nm) skyrocket, we demonstrate that by intelligently combining **mature silicon (28nm)** with **deterministic algorithmic decomposition**, we can achieve **10.9× superior capital efficiency** for massive edge applications.

> **Paradigma**: Instead of a single, complex, and expensive monolithic chip, we propose **multiple simple, economical chiplets** coordinated by deterministic software.

---

## 📊 Comprehensive Experimental Validation

[![CAPEX Efficiency](https://img.shields.io/badge/CAPEX_Efficiency-10.9x-green)](#)
[![Accuracy Improvement](https://img.shields.io/badge/Accuracy_Improvement-%2B4.8%25-blue)](https://cifar10.org/)
[![Communication Overhead](https://img.shields.io/badge/Communication_Overhead-0.05%25-lightgrey)](https://en.wikipedia.org/wiki/Overhead_(computing))
[![Carbon Reduction](https://img.shields.io/badge/Carbon_Reduction--91%25-brightgreen)](https://en.wikipedia.org/wiki/Embodied_energy)
[![Transformer Speedup](https://img.shields.io/badge/Transformer_Speedup-21.47x-orange)](https://arxiv.org/abs/1706.03762)

| Domain | Metric | Result | Implication |
| :--- | :--- | :--- | :--- |
| **Economics** | CAPEX Efficiency | **10.9× FPS/$ vs baseline** | Democratization of hardware access |
| **Performance** | CIFAR-10 Accuracy | **78.86%** (vs 74.04% monolithic) | Modular ensemble improves precision |
| **Scalability** | Comm. Overhead | **0.05%** on ResNet-50 | Compute-bound architecture |
| **Robustness** | Variability Penalty | 15.7% (mitigated to **2.1%**) | High tolerance to manufacturing defects |
| **Sustainability** | Embodied Carbon | **-91%** vs 3nm node | Truly Green AI for short lifecycles |
| **Extensibility** | Transformer Speedup | **21.47×** vs naive implementation | Viable lightweight LLMs at the edge |

---

## 🧩 Core Innovations

### 1. Static Slicing: Software-Defined Hardware

* **Matrix Isomorphism** that eliminates the need for cache coherence ($\Delta < 10^{-6}$).
* A deterministic compiler that resolves data **routing at compile time**.
* Negligible communication overhead (**0.05%** in real workloads like ResNet-50).

### 2. Shared-Nothing Architecture (Intrinsic Privacy)

* **Physical isolation** of data in local SRAMs.
* **Privacy by hardware design**, not by complex software protocols.
* Natural Ensemble Effect: **+4.8% accuracy** on CIFAR-10 due to implicit worker specialization.

### 3. Transformer Extension via Local Attention

* Adaptation of global attention mechanisms to **local windows** for modular architectures.
* **21.47× Speedup** compared to naive distributed implementations.
* Enables **lightweight LLMs** on disposable edge hardware.

---

## 📁 Repository Structure


```

Papers/
├── Frugal_AI_Chip.pdf          # Hardware architecture and economic analysis
└── Frugal_AI_Chip.tex          # Full LaTeX source code

Notebooks/
├── Frugal_AI_Complete_Suite.ipynb    # End-to-end validation suite:
│   ├── 1. Mathematical validation of isomorphism
│   ├── 2. MNIST/CIFAR-10 Experiments (+4.8% accuracy)
│   ├── 3. Economic Simulation (10.9× CAPEX efficiency)
│   ├── 4. Embodied Carbon Analysis (-91%)
│   ├── 5. Static Slicing Compiler Demonstration
│   ├── 6. Transformer Extension (21.47× speedup)
│   └── 7. Monte Carlo Robustness Analysis (N=10,000)
└── requirements.txt

Images/                         # Figures and visualizations

```

---

## 🚀 Getting Started

### Prerequisites

```bash
python>=3.8
torch>=2.0
numpy>=1.21
matplotlib>=3.5
jupyter>=1.0

```

### Running the Full Suite

Optión 1:

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NachoPeinador/FRUGAL_AI_CHIP/blob/main/Notebooks/Frugal_AI_Complete_Suite.ipynb)

  Option 2:

```bash
git clone [https://github.com/NachoPeinador/FRUGAL_AI_CHIP.git](https://github.com/NachoPeinador/FRUGAL_AI_CHIP.git)
cd FRUGAL_AI_CHIP
pip install -r Notebooks/requirements.txt
jupyter notebook Notebooks/Frugal_AI_Complete_Suite.ipynb

```

---

## 🧠 Theoretical Foundation

FrugalAI Chip is the physical implementation of the **Modular Isomorphism** theory formalized in our foundational research.

### 📘 Scientific Basis
This architecture builds directly upon our paper **"Modular Isomorphism in Artificial Intelligence: From the Ring $\mathbb{Z}/6\mathbb{Z}$ to Shared-Nothing Architecture NPUs"** [[Read Paper]](https://github.com/NachoPeinador/Isomorfismo-Modular-Z-6Z-en-Inteligencia-Artificial/blob/main/Paper/AI_Modular_Isomorphism.pdf).

**Key Concepts Implemented:**
* **Tensor Decomposition Theorem**: Deterministic projection onto six orthogonal subspaces via $\mathbb{Z}/6\mathbb{Z}$
* **Inverse Generalization Gap**: Hardware-enforced partial blindness as structural regularizer (+24.37% generalization)
* **Node Arbitrage Model**: 28nm vs 3nm economics enabling 18× cost reduction

### 🔗 From Theory to Silicon
The mathematical framework directly translates to FrugalAI's core innovations:
* Static Slicing Compiler implements the modular projection operator
* Chiplet isolation design enables the Shared-Nothing paradigm
* 0.05% communication overhead validated through tensor isomorphism proofs

### 📚 Complete Scientific Foundation
For mathematical derivations, proofs, and experimental validations:
**[👉 Explore the Complete Research](https://github.com/NachoPeinador/Isomorfismo-Modular-Z-6Z-en-Inteligencia-Artificial)**

This scientific foundation ensures FrugalAI is not just another chip design, but a **scalable paradigm** with mathematically predictable performance characteristics.

---

## 🔬 Contributions

This project is the result of independent research. Contributions in the form of:

* **Issues** reporting bugs or suggestions.
* **Pull requests** with code improvements.
* **Discussions** regarding architectural extensions.

are welcome and will be seriously considered.

---

## 🎯 Design Philosophy

> "Complexity is the enemy of reliability. When the cost per transistor stops decreasing, innovation must come from architecture, not lithography."

FrugalAI represents a **paradigm shift**: instead of chasing smaller nodes, we optimize performance per dollar invested through **extreme modularity** and **deterministic software**. It is not just another NPU—it is a manifesto on how the semiconductor industry should evolve in the face of the **end of Dennard scaling**.

---

## 📝 Citation

If you use this work in your research, please cite it as follows:

```bibtex
@article{peinador2025frugalai,
  title={FrugalAI Chip: Deterministic Modular Architecture for Low-Cost NPUs, A High Capital Efficiency (CAPEX) Approach for Disposable AI},
  author={Peinador Sala, José Ignacio},
  year={2025},
  publisher={Zenodo},
  doi={10.5281/zenodo.17853543},
  url={[https://doi.org/10.5281/zenodo.18508385](https://doi.org/10.5281/zenodo.18508385)}
}

```

---

## 📫 Contact

For technical inquiries, research collaborations, or commercial licensing:

* **Email**: joseignacio.peinador@gmail.com
* **Twitter/X**: [@todos_lumpen](https://www.google.com/search?q=https://twitter.com/todos_lumpen)

---

## ⚖️ Dual Licensing Model

This project uses a **Dual Licensing Model**:

### 🔬 For Research and Education

* **License**: [PolyForm Noncommercial 1.0.0](https://polyformproject.org/licenses/noncommercial/1.0.0/)
* **Permitted**: Academic research, educational use, personal non-profit projects.
* **Requirements**: Attribution and preservation of the license.
* **Full Terms**: See [LICENSE](https://github.com/NachoPeinador/FRUGAL_AI_CHIP/tree/main?tab=License-1-ov-file) file.

### 💼 For Commercial Use

**All commercial applications require explicit written permission.**

**Commercial use includes:**

* Manufacturing/sale of hardware based on this architecture.
* Integration into commercial products or services.
* Consulting/services utilizing this intellectual property.
* Military/Defense applications.
* Government contracts.

**📋 Full Restrictions**: See [COPYRIGHT.md](https://github.com/NachoPeinador/FRUGAL_AI_CHIP/blob/main/COPYRIGHT.md) for detailed terms.

**📧 License Inquiries**: joseignacio.peinador@gmail.com

*Subject: "FrugalAI Commercial License Inquiry"*

> **⚠️ Important**: Unauthorized commercial use will be legally pursued.

---

*Last update: December 2025*

