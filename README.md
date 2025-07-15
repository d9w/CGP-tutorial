# Introduction to Cartesian Genetic Programming (CGP) - GECCO 2025 Tutorial

This repository contains the tutorial materials for the **Cartesian Genetic Programming (CGP) tutorial** presented at **GECCO 2025**. The tutorial provides a hands-on introduction to CGP through a simple, educational implementation built from scratch.

## 📖 About This Tutorial

Cartesian Genetic Programming is a form of genetic programming that represents programs as directed acyclic graphs. This tutorial covers:

- **CGP representation**: Linear genome encoding computational graphs
- **Evolution**: Simple (1+λ) evolutionary strategy 
- **Applications**: Symbolic regression and reinforcement learning policy evolution
- **Implementation**: Complete CGP system built from scratch in Python

## 🎯 Learning Objectives

By the end of this tutorial, you will understand:
- How CGP represents programs as graphs with linear genomes
- The role of active and inactive nodes in CGP
- How to apply CGP to symbolic regression problems
- How to evolve policies for reinforcement learning tasks

## 📚 Tutorial Structure

The main tutorial is contained in the Jupyter notebook:

- **`cgp_tutorial.ipynb`** - Complete tutorial with theory and hands-on examples

### Topics Covered:

1. **Representation** - CGP's graph-based program representation
2. **Random Initialization** - Creating random CGP programs
3. **Active vs Inactive Nodes** - Understanding program execution flow
4. **Mutation** - Point mutation and neutral evolution
5. **Evolution** - Simple (1+λ) evolutionary algorithm
6. **Example 1**: Symbolic regression (evolving f(x,y) = x² + y²)
7. **Example 2**: Reinforcement learning (Mountain Car policy evolution)

## 🚀 Getting Started

### Local Installation

1. Clone this repository
2. Install the required dependencies

```bash
pip install numpy matplotlib gymnasium[classic_control]
```

3. Open `cgp_tutorial.ipynb` in Jupyter Lab/Notebook
4. Follow along with the tutorial!

### Google Colab

1. [Open this notebook directly on Colab](https://colab.research.google.com/github/d9w/CGP-tutorial/blob/main/cgp_tutorial_notebook.ipynb)

## ⚠️ Important Note

This is a **simplified educational implementation** designed for learning purposes. For production use or advanced research, consider the implementations listed below.

## 🔗 Production CGP Implementations

### Python
- **[pyCGP](https://github.com/scussatb/pyCGP)**: Python implementation focused on symbolic regression and image analysis
- **[CGPython](https://github.com/fhtanaka/CGPython)**: Another Python CGP implementation
- **[cartesian](https://github.com/Ohjeah/cartesian)**: Lightweight Python CGP for symbolic regression
- **[cartesian_genetic_programming](https://github.com/shinjikato/cartesian_genetic_programming)**: Sklearn-compatible CGP with cross-validation and grid search
- **[hal-cgp](https://github.com/Happy-Algorithms-League/hal-cgp)**: Extensible pure Python library supporting symbolic regression with export to NumPy, SymPy, and PyTorch

### Julia
- **[CartesianGeneticProgramming.jl](https://github.com/d9w/CartesianGeneticProgramming.jl)**: Julia implementation based on Cambrian.jl framework
- **[MAGE.jl](https://github.com/camilodlt/MAGE.jl)**: Multimodal Adaptive Graph Evolution, a typed extension of CGP

### C/C++
- **[cgp-plusplus](https://github.com/RomanKalkreuth/cgp-plusplus)**: Modern C++ implementation with concurrency, checkpointing, and benchmarks
- **[CGP-Library](https://github.com/AndrewJamesTurner/CGP-Library)**: Cross-platform C library for integration into larger projects

### Specialized Implementations
- **[dcgp](https://github.com/darioizzo/dcgp)**: Differentiable CGP with derivative information for advanced optimization
- **[dcgp.js](https://esa.github.io/dcgp.js/)**: JavaScript bindings for differential CGP (Node.js and web)
- **[CGPExperiments](https://github.com/mitchellspryn/CGPExperiments)**: Python framework for CGP experiments in image processing
- **[CGPNAS](https://github.com/Cosijopiii/CGPNAS)**: CGP for multi-objective neural architecture search
- **[gpFlappyBird](https://github.com/ShuhuaGao/gpFlappyBird)**: CGP trained to play Flappy Bird

## 👥 Tutorial Authors

This tutorial was developed for the GECCO 2025 conference. For questions or feedback about the tutorial materials, please open an issue in this repository.

## 📄 License

This tutorial is provided for educational purposes. Please refer to individual implementation repositories for their specific licenses.

---

**Happy Learning! 🧬💻**
