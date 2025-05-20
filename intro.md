
# Roadmap to Hybrid Quantum Physics-Informed Neural Networks (HQPINNs)

This roadmap integrates quantum computing, deep learning, and physics-informed modeling, tailored for theoretical physics and computational science researchers.

---

## 📘 Phase 1: Mathematical & Physical Foundations

### ✅ Topics
- Linear Algebra: Hermitian operators, eigenvalues/eigenvectors
- Differential Equations: ODEs, PDEs (Schrödinger, diffusion, etc.)
- Functional Analysis and Variational Methods
- Quantum Mechanics: Time-dependent and independent Schrödinger Equation
- Numerical Methods: Finite difference, spectral methods

### 📚 Resources
- _Mathematics for Physicists_ – Mary L. Boas
- _Introduction to Quantum Mechanics_ – David J. Griffiths
- [MIT OCW: Quantum Physics I](https://ocw.mit.edu/courses/8-04-quantum-physics-i-spring-2016/)
- _Numerical Recipes_ (for PDE solvers)

---

## 🧠 Phase 2: Deep Learning & PINNs

### ✅ Topics
- Neural Networks (MLPs), activation functions, backpropagation
- Autograd and symbolic differentiation
- PINNs architecture: Loss = Data + PDE residual + Boundary/IC
- Implementation with PyTorch or TensorFlow

### 📚 Resources
- Raissi et al., [“Physics-Informed Neural Networks”](https://arxiv.org/abs/1711.10561)
- [DeepXDE library](https://github.com/lululxvi/deepxde)
- YouTube: PINNs tutorials by Karniadakis Group or SciML
- [Neural PDEs tutorial](https://krasserm.github.io/2020/01/21/neural-pdes/) – Martin Krasser

---

## ⚛️ Phase 3: Quantum Computing Foundations

### ✅ Topics
- Qubits, Bloch sphere, superposition, entanglement
- Quantum gates and circuits
- Variational Quantum Algorithms (VQE, QAOA)
- Parameterized Quantum Circuits (PQCs)

### 📚 Resources
- _Quantum Computation and Quantum Information_ – Nielsen & Chuang
- [Qiskit Textbook](https://qiskit.org/learn)
- [PennyLane Tutorials](https://pennylane.ai/qml/)
- [MIT OCW: Quantum Computation](https://ocw.mit.edu/courses/6-845-quantum-complexity-theory-fall-2010/)

---

## 🧩 Phase 4: Hybrid Quantum-Classical PINNs

### ✅ Topics
- PQCs for function approximation or eigenvalue estimation
- Classical PINNs + Quantum subcircuits (e.g., solving quantum PDEs)
- Training with hybrid optimizers (e.g., ADAM + SPSA)
- Circuit Differentiation (parameter-shift rule)

### 📚 Tools
- [Qiskit + PyTorch integration](https://qiskit.org/ecosystem/machine-learning/)
- [PennyLane + PyTorch](https://pennylane.ai/qml/demos/tutorial_pytorch_interface.html)

### 📚 Papers
- Marrero et al., 2020 — [Quantum Neural Network Architectures](https://arxiv.org/abs/2010.15968)
- Quantum PINNs – [Quantum-assisted learning of quantum PDEs](https://arxiv.org/abs/2105.01417)
- Ghosh et al. – [Hybrid Quantum-Classical PINNs](https://arxiv.org/abs/2109.06259)

---

## 🧪 Phase 5: Applications & Projects

### 🧠 Project Ideas
- Solve the time-dependent Schrödinger equation with hybrid quantum NN
- Use VQE to find the ground state energy in PINNs setup
- Infer unknown potentials or Hamiltonians from quantum data

### 📚 Tools
- Jupyter Notebook + Qiskit/PennyLane
- PyTorch with autograd for PINNs loss
- Hugging Face for model hosting

---

## 🚀 Phase 6: Publication & Contribution

### ✅ Goals
- Publish code on GitHub (with tutorials)
- Contribute to DeepXDE, PennyLane, or Qiskit open-source
- Write and host a Jupyter Book with HQPINNs demos
- Upload pretrained HQPINN models on Hugging Face 🤗

---

@misc{PennyLane2024,
author = {Albornoz, C. and Alonso, G. and Andrenkov, M. and Angara, P. and Asadi, A. and Ballon, A. and Bapat, S. and Botelho, L. and De Vlugt, I. and Di Matteo, O. and Downing, P. and Finlay, P. and Fumagalli, A. and Gardhouse, A. and Geoffrion, J. and Girard, N. and Hayes, A. and Izaac, J. and Janik, R. and Kalajdzievski, T. and Kanwar Singh, A. and Khomchenko, A. and Killoran, N. and Kurečić, I. and Landon-Cardinal, O. and Martin, A. and Nino, D. and Otto, A. and Pere, C. and Pickering, J. and Renaud, K. and Soni, J. and Wakeham, D. and Young, L.},
title = {{PennyLane Codebook}},
note={\url{https://pennylane.ai/codebook}},
year = {2024}
}
