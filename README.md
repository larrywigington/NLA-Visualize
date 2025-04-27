
# 📊 NLA-Visualize
![License](https://img.shields.io/github/license/larrywigington/NLA-Visualize)

Animated, CPU- and GPU-accelerated visualizations of numerical linear algebra and optimization algorithms.  
Built for education, research, and scientific computing.

---

## 🧠 Project Overview

Understanding numerical linear algebra is critical to modern scientific computing, optimization, and machine learning.  
However, the dynamic behavior of iterative algorithms is often difficult to visualize through static textbooks alone.

**NLA-Visualize** provides a platform for:
- Step-by-step **animated visualizations** of core linear algebra and optimization algorithms
- **GPU-accelerated** demonstrations highlighting performance scaling
- **Intuitive exploration** of convergence behavior, numerical stability, and matrix structures

Built with:
- **Python 3.9+**
- **Matplotlib** (animations)
- **Plotly** (interactive visualizations)
- **NumPy**, **CuPy**, **SciPy** (computational backends)
- (Optional) **Numba** for GPU kernel customization

---

## 🚀 Core Visualizations (v1)

| Topic | Visualization |
|:------|:--------------|
| QR Factorization (Givens/Householder) | Animated rotations and reflections |
| Conjugate Gradient Method | Iterative path animation on quadratic contours |
| GMRES Algorithm | Basis expansion in Krylov subspaces |
| Simplex Method | Edge-walking animation across polytopes |
| Sparse Matrix Fill-in | Sparsity evolution during factorizations |
| Steepest Descent | Animated gradient path visualizations |

---

## 🛠️ How to Run

### Requirements

- Python 3.9+
- Matplotlib
- Plotly
- NumPy / SciPy
- (Optional) CuPy for GPU acceleration
- Jupyter Notebook (recommended)

### Installation

```bash
git clone https://github.com/larrywigington/NLA-Visualize.git
cd NLA-Visualize
pip install -r requirements.txt
```

### Running

```bash
jupyter notebook
# Open any of the notebooks inside the "notebooks/" directory
```

---

## 📂 Project Structure

```text
nla_visualize/
├── notebooks/
│   ├── QR_Factorization.ipynb
│   ├── Conjugate_Gradient.ipynb
│   ├── GMRES.ipynb
│   ├── Simplex_Method.ipynb
│   └── Sparse_Fillin.ipynb
├── src/
│   ├── qr.py
│   ├── cg.py
│   ├── gmres.py
│   ├── simplex.py
│   └── visualization_utils.py
├── assets/
│   └── animations/ (GIFs and MP4s)
├── requirements.txt
└── README.md
```

---

## 🔭 Future Roadmap

| Feature | Status |
|:--------|:------|
| QR / Givens rotation animations | ✅ Complete |
| CG / GMRES path visualizations | 🔄 In Progress |
| Sparse matrix fill-in animations | 🔄 In Progress |
| CuPy-based GPU demos | ⬜ Planned |
| Interactive web demos (Plotly Dash) | ⬜ Planned |
| Educational blog series tie-in | ⬜ Planned |

---

## 🎓 Educational Focus

- Designed for students, researchers, and engineers to **intuitively grasp** core linear algebra concepts
- Animated methods reveal **hidden structures** behind convergence and numerical behavior
- Bridge **theory, visualization, and GPU-accelerated practice**

---

## 📚 Related Resources

- [Matrix Computations (Golub and Van Loan)](https://www.cs.cornell.edu/cv/GVL4/)
- [SciPy Sparse Tools](https://docs.scipy.org/doc/scipy/reference/sparse.html)
- [Numba - CUDA Python Acceleration](https://numba.pydata.org/)

---

## 📜 License

MIT License — see [LICENSE](LICENSE) for details.

---

## 🔗 Connect

- 🌐 [Personal Website](https://www.larrywigington.com)
- 💼 [LinkedIn](https://www.linkedin.com/in/larrywigington/)
- 📬 GitHub Discussions — Open for feedback and collaborations!

---

> *"Seeing algorithms unfold brings intuition to life."* — Larry Wigington
