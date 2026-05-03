<div align="center">

# Satvik Saluja

**ML · Scientific Computing · Reproducible Simulation Systems**

*Building continuous-time dynamical models, simulation validation infrastructure, and graph-based biological systems*

</div>

---

## 🏆 Google Summer of Code 2026

<div align="center">

<table border="0" cellspacing="0" cellpadding="24">
  <tr>
    <td align="center" width="180">
      <img src="assets/gsoc.png" height="90" alt="Google Summer of Code"/><br/>
      <sub><b>Google Summer of Code 2026</b></sub><br/>
      <sub>✅ Accepted</sub>
    </td>
    <td align="center" width="60"><sub>×</sub></td>
    <td align="center" width="180">
      <img src="assets/incf.png" height="90" alt="INCF"/><br/>
      <sub><b>INCF</b></sub><br/>
      <sub>Mentoring Organization</sub>
    </td>
    <td align="center" width="60"><sub>×</sub></td>
    <td align="center" width="180">
      <img src="assets/hnn.png" height="90" alt="HNN-Core"/><br/>
      <sub><b>HNN-Core</b></sub><br/>
      <sub>Project Repository</sub>
    </td>
  </tr>
</table>

</div>

**Project:** Refactoring Synaptic Behavior in HNN-Core

Selected as a **GSoC 2026 contributor** under **INCF** to improve biological realism in HNN-Core — placing synapses only at active connection sites, making synapse position along sections configurable, recording currents only from active synapses, and adding seeded biological variability to synaptic weights and delays.

> **Primary Mentor:** Katharina Duecker &nbsp;·&nbsp; **Mentors:** Nicholas Tolley, Austin Soplata, Anna Cattani

---

## About

Working at the intersection of ML and computational neuroscience — where correctness is verifiable and reproducibility is enforced by architecture.

GSoC 2026 contributor to **HNN-Core** (INCF), shipping production-quality changes to NEURON-based synaptic simulation internals.

Focus: Neural ODEs · Modular simulation pipelines · Structured validation frameworks for scientific Python

---

## Languages & Tools

<p align="center">
 <a href="https://www.python.org/"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/python-colored.svg" alt="Python" width="36" height="36" /></a>&nbsp;
 <a href="https://www.typescriptlang.org/"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/typescript-colored.svg" alt="TypeScript" width="36" height="36" /></a>&nbsp;
 <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/javascript-colored.svg" alt="JavaScript" width="36" height="36" /></a>&nbsp;
 <a href="https://docs.microsoft.com/en-us/cpp/?view=msvc-170"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/cplusplus-colored.svg" alt="C++" width="36" height="36" /></a>&nbsp;
 <a href="https://reactjs.org/"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/react-colored.svg" alt="React" width="36" height="36" /></a>&nbsp;
 <a href="https://fastapi.tiangolo.com/"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/fastapi-colored.svg" alt="Fast API" width="36" height="36" /></a>&nbsp;
 <a href="https://pytorch.org/"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/pytorch-colored.svg" alt="PyTorch" width="36" height="36" /></a>&nbsp;
 <a href="https://www.tensorflow.org/"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/tensorflow-colored.svg" alt="TensorFlow" width="36" height="36" /></a>&nbsp;
 <a href="https://www.linux.org"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/linux-colored.svg" alt="Linux" width="36" height="36" /></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white"/>
  <img src="https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB"/>
  <img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white"/>
  <img src="https://img.shields.io/badge/NEURON-FF6B35?style=flat-square&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
</p>

---

## Core Areas

```
Neural ODEs · Dynamical Systems · Simulation Pipeline Design
Numerical Validation · Solver Benchmarking · Graph Neural Networks
Biological System Modeling · ONNX Deployment · Scientific Python
NEURON Simulation · Synaptic Modeling · Computational Neuroscience
```

---

## Selected Projects

| Project | Stack | What it does |
|---|---|---|
| [HNN Simulation Validation](https://github.com/SatvikSaluja/hnn_simulation) | Python · NumPy · SciPy · pytest | Modular validation pipeline for neural simulation outputs — peak latency checks, waveform integrity, composable validator modules per drive type |
| [Neural ODE Cognitive Simulator](https://github.com/SatvikSaluja/Neuro-ODE) | PyTorch · torchdiffeq · FastAPI | Continuous-time model `dS/dt = f(S,U,θ)` of EEG-derived cognitive states using adaptive solvers (dopri5, RK45) |
| [Metabolic Pathway GNN](https://github.com/SatvikSaluja/TCA-PPP-glycolysis-simulation) | PyG · GATv2 · FastAPI · React | Glycolysis / TCA / PPP as bipartite graphs; GATv2 + FiLM for flux prediction, validated against literature ranges |
| [AirAware — Browser AQI](https://github.com/SatvikSaluja/AirAware) | ONNX Runtime · React · Tailwind | AQI model exported to ONNX, deployed client-side; <0.1% deviation vs Python outputs confirmed |

---

## Links

<p align="center">
  <a href="https://kaleidoscopic-souffle-ce8b9e.netlify.app/"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=netlify&logoColor=white"/></a>
</p>
