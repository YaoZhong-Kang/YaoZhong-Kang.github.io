---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class='anchor' id='home'></span>

## Hi, I'm Yao-Zhong Kang.

I am an M.Sc. candidate in **Theoretical Physics at Shanghai University**, jointly trained at the **Shanghai Institute of Applied Physics, Chinese Academy of Sciences (SINAP, CAS)**.

My research lies at the intersection of **reactor physics, numerical methods, and scientific machine learning**. I am particularly interested in developing AI methods that can work together with established numerical solvers, rather than simply replacing them.

My current research focuses on **physics-informed machine learning**, **neural operators**, and **AI-assisted numerical methods for neutron diffusion eigenvalue problems**. Looking forward, I am interested in extending these ideas toward **Monte Carlo neutron transport and high-performance scientific computing**.

> **Research theme:**  
> Physics-informed learning → AI-assisted trusted solvers → AI-assisted Monte Carlo transport

---

## 🔬 What I Work On

### 01 · Physics-informed learning for neutron diffusion

My early work explored whether neural networks can directly solve reactor-physics PDEs under physical constraints.

I studied **physics-informed neural networks (PINNs)** for two-group heterogeneous neutron diffusion eigenvalue problems, with particular attention to material discontinuities, interface behavior, and spectral representation.

To improve the representation of heterogeneous flux distributions, I introduced a **multi-band Fourier feature enhancement strategy** and investigated its effects on convergence and solution accuracy.

**Keywords:**  
`PINNs` · `Fourier Features` · `Neutron Diffusion` · `Eigenvalue Problems`

---

### 02 · Neural operators as a warm start for conventional solvers

My more recent work shifts from **AI replacing numerical solvers** toward **AI assisting reliable numerical solvers**.

I developed a physics-informed neural-operator approach to predict an improved initial fission-source distribution for multi-group neutron diffusion eigenvalue calculations.

Instead of directly producing the final solution, the neural operator provides a **warm start**, after which the conventional finite-element source-iteration solver continues to convergence under the same numerical stopping criterion.

This design allows the traditional solver to retain control of the final accuracy while the learned model helps reduce unnecessary iterations.

**Keywords:**  
`Neural Operators` · `Warm Start` · `Finite Elements` · `Source Iteration`

---

### 03 · Toward AI-assisted Monte Carlo transport

My long-term research interest is to explore how machine learning can be integrated into **Monte Carlo neutron transport** without compromising the reliability and physical consistency of conventional simulation methods.

Possible directions that I am currently interested in include:

- learned initialization of fission-source distributions;
- data-driven acceleration of source convergence;
- AI-assisted importance functions and variance reduction;
- uncertainty-aware and physics-constrained surrogate models;
- hybrid workflows combining machine learning with high-performance Monte Carlo simulation.

Rather than treating AI as a standalone replacement, I am interested in **hybrid computational frameworks in which AI improves efficiency while trusted physics-based solvers guarantee the final solution quality**.

---

## 📚 Selected Research Work

### Physics-Informed Neural Networks with Multi-Band Fourier Feature Enhancement for Two-Group Heterogeneous Neutron Diffusion Eigenvalue Problems

**Yao-Zhong Kang**, et al.

*Nuclear Science and Techniques*

**Status:** Major Revision

This work investigates PINN-based solutions of heterogeneous two-group neutron diffusion eigenvalue problems and introduces multi-band Fourier features to improve the representation of spatially complex neutron-flux distributions.

<!-- Add links when available:
[Manuscript] [Code] [Project]
-->

---

### Physics-informed neural-operator fission-source warm-start method for multi-group neutron diffusion eigenvalue problems

**Yao-Zhong Kang**, Jian Guo, Rui Yan, Yang Zou

*Annals of Nuclear Energy*

**Status:** Under Review

This work develops a physics-informed neural operator for predicting improved initial fission-source distributions. The predicted source is coupled with a conventional finite-element solver to accelerate subsequent source iterations while maintaining the original convergence criterion.

<!-- Add links when available:
[Manuscript] [Code] [Project]
-->

---

## 🧭 My Research Perspective

One important change in my research has been the way I think about the role of AI in scientific computing.

My initial question was:

> *Can a neural network solve the governing equations directly?*

My current question is increasingly:

> *Can machine learning provide useful information to a trusted numerical solver, while the solver remains responsible for final accuracy and reliability?*

This shift motivates my current interest in **hybrid AI–physics computation**, particularly for reactor-physics and neutron-transport applications.

---

## 📌 Recent Highlights

- **2026** — Abstract *Neural-Operator Warm Start for Neutron Diffusion Eigenvalue Problems* accepted for presentation at the **2026 American Nuclear Society Winter Conference & Expo**.
- **2026** — Submitted the neural-operator fission-source warm-start work to *Annals of Nuclear Energy*.
- **2026** — Received a major-revision decision for the PINN neutron-diffusion work from *Nuclear Science and Techniques*.

---

## 🎓 Academic Background

**M.Sc. in Theoretical Physics**  
Shanghai University  
Joint training at Shanghai Institute of Applied Physics, Chinese Academy of Sciences  
2024 – 2027 (expected)

Research focus: AI-assisted numerical methods for reactor physics

---

**B.Sc. in Physics**  
Soochow University  
2020 – 2024

---

## 🧰 Research Toolkit

**Scientific Computing**

`Python` · `PyTorch` · `Finite Element Methods` · `Numerical Eigenvalue Problems`

**Machine Learning**

`Physics-Informed Neural Networks` · `Neural Operators` · `Scientific Machine Learning`

**Reactor Physics**

`Neutron Diffusion` · `Multi-group Methods` · `Fission Source Iteration`

**Currently Learning**

`Monte Carlo Neutron Transport` · `C++` · `High-Performance Computing`

---

## 🌱 Beyond Research

Outside research, I enjoy **badminton** and maintaining an active lifestyle.

I also enjoy learning about new developments in scientific computing, AI for science, and computational nuclear engineering.

---

## 📫 Contact

I am always happy to discuss research related to scientific machine learning, numerical reactor physics, and AI-assisted scientific computing.

**Email:** Add your preferred email here  
**GitHub:** [jr1128](https://github.com/jr1128)

<!--
Future links:
CV | Google Scholar | ORCID | LinkedIn
-->
