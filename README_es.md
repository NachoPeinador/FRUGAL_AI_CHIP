# 🤖 FrugalAI Chip: Arquitectura Modular de Silicio para IA Desechable

[![Read in English](https://img.shields.io/badge/Lang-Read%20in%20English-blue?style=flat&logoColor=white&color=B31B1B)](https://github.com/NachoPeinador/FRUGAL_AI_CHIP/blob/main/README.md)
[![License](https://img.shields.io/badge/License-PolyForm_Noncommercial_1.0.0-blue.svg)](https://polyformproject.org/licenses/noncommercial/1.0.0/)
[![Python](https://img.shields.io/badge/Python-3.10%2B-green.svg)]()
[![PyTorch](https://img.shields.io/badge/PyTorch-2.0%2B-orange.svg)]()
[![Status](https://img.shields.io/badge/Status-Investigación_Completa-brightgreen.svg)]()
[![Papers](https://img.shields.io/badge/Paper-Read_PDF-B31B1B?style=flat&logo=latex&logoColor=white)](https://github.com/NachoPeinador/FRUGAL_AI_CHIP/blob/main/Papers/Frugal_AI_Chip.pdf)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Ejecutar_Experimentos-F37626.svg?style=flat&logo=Jupyter)](./Notebooks/Frugal_AI_Suite_Completa.ipynb)
[![DOI](https://img.shields.io/badge/DOI-10.5281/zenodo.17853543-blue)](https://doi.org/10.5281/zenodo.17853543)

**Autor**: José Ignacio Peinador Sala
**Contacto**: joseignacio.peinador@gmail.com
**ORCID**: [0009-0008-1822-3452](https://orcid.org/0009-0008-1822-3452)

---

## 🔍 Visión

FrugalAI desafía el dogma del "**rendimiento a cualquier precio**" en la industria de semiconductores. Mientras el coste de fabricación en nodos avanzados (3nm) se dispara, demostramos que combinando inteligentemente **silicio maduro (28nm)** con **descomposición algorítmica determinista**, podemos lograr una eficiencia de capital **10.9× superior** para aplicaciones de edge masivo.

> **Paradigma**: En lugar de un único chip monolítico, complejo y costoso, proponemos **múltiples chiplets simples y económicos** coordinados por software determinista.

---

## 📊 Validación Experimental Completa

[![CAPEX Efficiency](https://img.shields.io/badge/Eficiencia_CAPEX-10.9x-green)](#)
[![Accuracy Improvement](https://img.shields.io/badge/Mejora_Precisión-%2B4.8%25-blue)](https://cifar10.org/)
[![Communication Overhead](https://img.shields.io/badge/Overhead_Comunicación-0.05%25-lightgrey)](https://en.wikipedia.org/wiki/Overhead_(computing))
[![Carbon Reduction](https://img.shields.io/badge/Reducción_Carbono--91%25-brightgreen)](https://en.wikipedia.org/wiki/Embodied_energy)
[![Transformer Speedup](https://img.shields.io/badge/Speedup_Transformer-21.47x-orange)](https://arxiv.org/abs/1706.03762)

| Dominio | Métrica | Resultado | Implicación |
| :--- | :--- | :--- | :--- |
| **Económico** | Eficiencia CAPEX | **10.9× FPS/$ vs base** | Democratización del acceso al hardware |
| **Rendimiento** | Accuracy CIFAR-10 | **78.86%** (vs 74.04% monolítico) | El ensemble modular mejora la precisión |
| **Escalabilidad** | Overhead Comunic. | **0.05%** en ResNet-50 | Arquitectura limitada por cómputo, no ancho de banda |
| **Robustez** | Penalización Variabilidad | 15.7% (mitigada a **2.1%**) | Alta tolerancia a defectos de fabricación |
| **Sostenibilidad** | Carbono Embebido | **-91%** vs nodo 3nm | IA verdaderamente verde para ciclos cortos |
| **Extensibilidad** | Speedup Transformer | **21.47×** vs implementación naive | LLMs ligeros viables en el edge |

---

## 🧩 Innovaciones Nucleares

### 1. Static Slicing: Hardware Definido por Software

* **Isomorfismo Matricial** que elimina la necesidad de coherencia de caché ($\Delta < 10^{-6}$).
* Un compilador determinista que resuelve el **enrutamiento de datos en tiempo de compilación**.
* Overhead de comunicación despreciable (**0.05%** en cargas de trabajo reales como ResNet).

### 2. Arquitectura Shared-Nothing (Privacidad Intrínseca)

* **Aislamiento físico** de datos en memorias SRAM locales.
* **Privacidad por diseño hardware**, no dependiente de protocolos de software vulnerables.
* Efecto de "Ensemble Natural": **+4.8% de precisión** en CIFAR-10 debido a la especialización implícita de los workers.

### 3. Extensión a Transformers vía Atención Local

* Adaptación de mecanismos de atención global a **ventanas locales** para arquitecturas modulares.
* **Speedup de 21.47×** comparado con implementaciones distribuidas ingenuas (*naive*).
* Habilita la ejecución de **LLMs ligeros** en hardware de edge desechable.

---

## 📁 Estructura del Repositorio


```

Papers/
├── Frugal_AI_Chip.pdf          # Arquitectura hardware y análisis económico
└── Frugal_AI_Chip.tex          # Código fuente completo en LaTeX

Notebooks/
├── Frugal_AI_Complete_Suite.ipynb    # Suite de validación end-to-end:
│   ├── 1. Validación matemática del isomorfismo
│   ├── 2. Experimentos MNIST/CIFAR-10 (+4.8% accuracy)
│   ├── 3. Simulación económica (10.9× eficiencia CAPEX)
│   ├── 4. Análisis de carbono embebido (-91%)
│   ├── 5. Demostración del compilador Static Slicing
│   ├── 6. Extensión a Transformers (21.47× speedup)
│   └── 7. Análisis Monte Carlo de robustez (N=10,000)
└── requirements.txt

Images/                         # Figuras y visualizaciones

```

---

## 🚀 Comenzando

### Prerrequisitos

```bash
python>=3.8
torch>=2.0
numpy>=1.21
matplotlib>=3.5
jupyter>=1.0

```

### Ejecutar la Suite Completa

Opción 1:

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NachoPeinador/FRUGAL_AI_CHIP/blob/main/Notebooks/Frugal_AI_Suite_Completa.ipynb)

Opción 2:

```bash
git clone [https://github.com/NachoPeinador/FRUGAL_AI_CHIP.git](https://github.com/NachoPeinador/FRUGAL_AI_CHIP.git)
cd FRUGAL_AI_CHIP
pip install -r Notebooks/requirements.txt
jupyter notebook Notebooks/Frugal_AI_Complete_Suite.ipynb

```

---

## 🔬 Contribuciones

Este proyecto es el resultado de una investigación independiente. Las contribuciones en forma de:

* **Issues** reportando errores o sugerencias.
* **Pull requests** con mejoras en el código.
* **Discusiones** sobre extensiones arquitectónicas.

son bienvenidas y serán consideradas seriamente.

---

## 🎯 Filosofía de Diseño

> "La complejidad es el enemigo de la fiabilidad. Cuando el coste por transistor deja de disminuir, la innovación debe provenir de la arquitectura, no de la litografía."

FrugalAI representa un **cambio de paradigma**: en lugar de perseguir nodos cada vez más pequeños, optimizamos el rendimiento por dólar invertido a través de **modularidad extrema** y **software determinista**. No es solo otra NPU, es un manifiesto sobre cómo debería evolucionar la industria de semiconductores ante el **fin del escalado de Dennard**.

---

## 📝 Citación

Si utilizas este trabajo en tu investigación, por favor cítalo de la siguiente manera:

```bibtex
@article{peinador2025frugalai,
  title={FrugalAI Chip: Deterministic Modular Architecture for Low-Cost NPUs, A High Capital Efficiency (CAPEX) Approach for Disposable AI},
  author={Peinador Sala, José Ignacio},
  year={2025},
  publisher={Zenodo},
  doi={10.5281/zenodo.17853543},
  url={[https://doi.org/10.5281/zenodo.17853543](https://doi.org/10.5281/zenodo.17853543)}
}

```

---

## 📫 Contacto

Para consultas técnicas, colaboraciones de investigación o licencias comerciales:

* **Email**: joseignacio.peinador@gmail.com
* **Twitter/X**: [@todos_lumpen](https://www.google.com/search?q=https://twitter.com/todos_lumpen)

---

## ⚖️ Modelo de Licenciamiento Dual

Este proyecto utiliza un **Modelo de Licenciamiento Dual**:

### 🔬 Para Investigación y Educación

* **Licencia**: [PolyForm Noncommercial 1.0.0](https://polyformproject.org/licenses/noncommercial/1.0.0/)
* **Permitido**: Investigación académica, uso educativo, proyectos personales sin ánimo de lucro.
* **Requisitos**: Atribución y preservación de la licencia.
* **Términos Completos**: Ver archivo [LICENSE](https://github.com/NachoPeinador/FRUGAL_AI_CHIP/tree/main?tab=License-1-ov-file).

### 💼 Para Uso Comercial

**Todas las aplicaciones comerciales requieren permiso explícito por escrito.**

**El uso comercial incluye:**

* Fabricación/venta de hardware basado en esta arquitectura.
* Integración en productos o servicios comerciales.
* Consultoría o servicios que utilicen esta propiedad intelectual.
* Aplicaciones militares/de defensa.
* Contratos gubernamentales.

**📋 Restricciones Completas**: Ver [COPYRIGHT.md](https://github.com/NachoPeinador/FRUGAL_AI_CHIP/blob/main/COPYRIGHT.md) para términos detallados.

**📧 Consultas de Licencia**: joseignacio.peinador@gmail.com

*Asunto: "Consulta de Licencia Comercial FrugalAI"*

> **⚠️ Importante**: El uso comercial no autorizado será perseguido legalmente.

---

*Última actualización: Diciembre 2025*

```

```
