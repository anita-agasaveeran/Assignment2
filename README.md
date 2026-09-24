# CMPE 255 — Assignment 2: Prerequisite Refresher Colabs

**Author:** Anita Agasaveeran · **Course:** CMPE 255, Fall 2026, SJSU

This repo archives my executed copies of the course prerequisite Colabs. Together they cover the basics of AI/ML: Python and its scientific tools (NumPy, pandas, matplotlib), the math that ML is built on (linear algebra, calculus, probability, statistics), tensors, and the basic structure of a learning system (model → loss → gradient → update).

For each Colab this repo includes:

1. A copy in my Google Drive, shared as **"Anyone with the link can view"**
2. The executed notebook with every input and output saved, in [`executed/`](executed/)
3. A video walkthrough that explains the notebook one code block at a time: the theory behind each block, what the key lines do, and what the output means. UI and plotting boilerplate is skipped.

The sections below follow the order of the assignment.

---

## Colabs and Videos

### Part A — Python and Scientific Tooling

| # | Notebook | What it covers | Colab | Video |
|---|---|---|---|---|
| 1 | [Intro to Python for ML](executed/Agasaveeran_final_Intro_to_Python_for_Machine_Learning.ipynb) | Variables, strings, data structures (list/tuple/dict/set), logic, control flow, functions, lambdas, built-ins | [Python for ML (Colab)](https://drive.google.com/file/d/1eFUBGQYbENx_-c7g2_FfzAtg8tM7SgGI/view?usp=sharing) | [Python for ML Walkthrough](https://www.loom.com/share/8fd53dc8199f4e2c8c94a71998ed2182) |
| 2 | [NumPy Foundations for Deep Learning](executed/Agasaveeran_final_numpy_foundations_for_deep_learning.ipynb) | ndarrays, shapes, dtypes, indexing/slicing, masking, element-wise ops, **broadcasting**, matrix multiplication, a forward pass | [NumPy Foundations (Colab)](https://drive.google.com/file/d/1cjG82yl0nbXPMF4f639Vy3mfVZxGzC0x/view?usp=sharing) | [NumPy Foundations Walkthrough](https://www.loom.com/share/92ed54ccbba743708c91f3c14b541f5e) |
| 3 | [pandas: Zero to Hero](executed/Agasaveeran_final_pandas_zero_to_hero.ipynb) | Series vs DataFrame, the index, loading and inspecting data, cleaning, selection, groupby, merge, reshaping (on a coffee-shop order log) | [pandas Zero to Hero (Colab)](https://drive.google.com/file/d/1bmOWSQmZLarZdIYS01_FFEusq4Od0uvp/view?usp=sharing) | [pandas Zero to Hero Walkthrough](https://www.loom.com/share/4f8b28f6db2845219c34be9e6ba462a1) |
| 4 | [matplotlib: Zero to Hero](executed/Agasaveeran_final_matplotlib_zero_to_hero.ipynb) | Figure/Axes anatomy, pyplot vs OO APIs, picking a chart type, labels, color, subplots, making a plot readable | [matplotlib Zero to Hero (Colab)](https://drive.google.com/file/d/1gXx0HhIQqdAhwh1Z2Dy60U7Vam04m7eR/view?usp=sharing) | [matplotlib Zero to Hero Walkthrough](https://www.loom.com/share/b347729fee974dc3bf5ab6a610ffdebb) |

### Part B — Linear Algebra

| # | Notebook | What it covers | Colab | Video |
|---|---|---|---|---|
| 5 | [Intro to Linear Algebra: Zero to Hero](executed/Agasaveeran_final_intro_to_linear_algebra_zero_to_hero_for_ml.ipynb) | Vectors, vector arithmetic, norms, dot product, matrices, matrix multiplication, transformations, systems & inverses, eigen-decomposition | [Intro to Linear Algebra (Colab)](https://drive.google.com/file/d/1qKwWW01ESIzsew1PZHYRKXe1dBiZOin3/view?usp=sharing) | [Intro to Linear Algebra Walkthrough](https://www.loom.com/share/e2ad48805ce3467799edff997e2c69df) |
| 6 | [Linear Algebra for Deep Learning](executed/Agasaveeran_linear_algebra_for_deep_learning.ipynb) | Scalars → vectors → matrices → **tensors**, matrix ops, transpose/inverse/determinant, eigenvalues, norms & distances | [Linear Algebra for DL (Colab)](https://drive.google.com/file/d/1A2iaRt3eomThUWADG8fP4gBR_vvqcFm0/view?usp=sharing) | [Linear Algebra for DL Walkthrough](https://www.loom.com/share/35d4f8fe88094314a408d52b83a7b304) |
| 7 | [Foundations 2 — Linear Algebra: the MODEL box](executed/Agasaveeran_final_foundations_2_linear_algebra.ipynb) | Matrices as transformations of space, basis vectors, dot product as projection, a neuron = one dot product, layers as matrices | [Foundations 2: Linear Algebra (Colab)](https://drive.google.com/file/d/1umugclarta_l_xqKO7uQsBasXN8t3ddO/view?usp=sharing) | [Foundations 2: Linear Algebra Walkthrough](https://www.loom.com/share/80ad429a5f314b91a3ec3f71efd7d519) |

### Part C — Probability and Statistics

| # | Notebook | What it covers | Colab | Video |
|---|---|---|---|---|
| 8 | [Intro to Probability: Zero to Hero](executed/Agasaveeran_final_intro_to_probability_zero_to_hero_for_ml.ipynb) | Sample spaces, events, probability rules, simulation, combining events, conditional probability, Bayes, random variables, distributions (spam-inbox example) | [Intro to Probability (Colab)](https://drive.google.com/file/d/1TWyGZkuZRsYPlhWR9TBEZ1TgxbDmKI0E/view?usp=sharing) | TODO |
| 9 | [Intro to Statistics: Zero to Hero](executed/final_intro_to_statistics_zero_to_hero_for_ml.ipynb) | Centre/spread/shape, robust statistics, populations vs samples, bias & variance of estimators, sampling distributions, CLT, confidence intervals, hypothesis testing | [Intro to Statistics (Colab)](https://drive.google.com/file/d/1_3ZYtgGdSZeR4AeL_Id5tlXL91VaxLbx/view?usp=sharing) | TODO |
| 10 | [Probability Fundamentals for Deep Learning](executed/Agasaveeran_final_probability_fundamentals_for_deep_learning.ipynb) | Probability vocabulary, rules, conditional probability, Bayes, distributions, expectation/variance, **MLE**, entropy & cross-entropy, softmax classification pipeline | [Probability Fundamentals for DL (Colab)](https://drive.google.com/file/d/1jkIIk6FuPoU18Pmx4k8ohFZwmxoDY4ds/view?usp=sharing) | TODO |
| 11 | [Statistics for Deep Learning](executed/Agasaveeran_final_statistics_for_deep_learning.ipynb) | Descriptive statistics, probability, distributions, expectation & variance, Bayes, MLE, and how each shows up in training neural nets | [Statistics for DL (Colab)](https://drive.google.com/file/d/1DGxtg2bdC3sn9Tw0IAaRT9gOG_BjPmxH/view?usp=sharing) | TODO |
| 12 | [Foundations 3 — Probability & Statistics: the DATA box](executed/Agasaveeran_final_foundations_3_probability.ipynb) | Conditional probability, Bayes' theorem, base rates (the medical-test example), distributions, likelihood | [Foundations 3: Probability (Colab)](https://drive.google.com/file/d/1x-zqvu65FPj10wXeJyNIzewrIl4XbGuR/view?usp=sharing) | TODO |

### Part D — Calculus

| # | Notebook | What it covers | Colab | Video |
|---|---|---|---|---|
| 13 | [Intro to Calculus: Zero to Hero](executed/Agasaveeran_final_intro_to_calculus_zero_to_hero_for_ml.ipynb) | Functions, rate of change, limits, continuity, derivatives, derivative rules, chain rule, partial derivatives, optimization | [Intro to Calculus (Colab)](https://drive.google.com/file/d/1QZusXhiGa7xZpA7HbgRCr6dpzSYfOzCW/view?usp=sharing) | TODO |
| 14 | [Calculus for Deep Learning](executed/Agasaveeran_final_calculus_for_deep_learning.ipynb) | Derivatives, chain rule, gradients, gradient descent, **backpropagation**, vanishing/exploding gradients, gradient checking, PyTorch autograd | [Calculus for DL (Colab)](https://drive.google.com/file/d/1r2R8xQCOrDvWptDzwVT-gqHUngpPx_No/view?usp=sharing) | TODO |
| 15 | [Foundations 4 — Calculus: the LOSS & UPDATE boxes](executed/Agasaveeran_final_foundations_4_calculus.ipynb) | Derivatives and their sign, partial derivatives, gradient as steepest ascent, gradient descent, chain rule → backprop | [Foundations 4: Calculus (Colab)](https://drive.google.com/file/d/13KLGuQHplxjtXJ3wjL6aIOyqgfCKhS4j/view?usp=sharing) | TODO |

### Part E — Foundations of Learning

| # | Notebook | What it covers | Colab | Video |
|---|---|---|---|---|
| 16 | [Foundations 1 — The Learning Machine](executed/Agasaveeran_final_foundations_1_the_learning_machine.ipynb) | AI ⊃ ML ⊃ DL, supervised/unsupervised/RL, model as tunable numbers, squared-error loss, gradient & learning rate, the full training loop | [Foundations 1: The Learning Machine (Colab)](https://drive.google.com/file/d/1Fw8SkddzK7Mp9atAFx-gpOKcM4oXiISV/view?usp=sharing) | TODO |

---

## Repository Structure

```
.
├── README.md                 ← this file (Colab + video links)
├── notebooks/                ← original Colab copies as downloaded from Drive
├── executed/                 ← notebooks re-executed end-to-end with all outputs saved
├── outputs/
│   ├── run_summary.md        ← status / runtime / errors for every notebook
│   ├── inputs.md             ← values supplied to interactive input() cells
│   └── <notebook>/
│       ├── outputs.md        ← every code cell with its text output, in order
│       └── figures/*.png     ← every plot the notebook produced
└── requirements.txt
```

## Execution Notes

To run locally, install the dependencies with `pip install -r requirements.txt` and open any notebook in Jupyter, or open it in Google Colab.

**Inputs:** the notebooks load no external datasets. All data is generated inside the notebooks with fixed random seeds, or comes from built-in scikit-learn datasets. The two `input()` cells in *Intro to Python* were given the value listed in [`outputs/inputs.md`](outputs/inputs.md) so they could run without a person typing.

**Environment:** Python 3.12, with library versions pinned close to Google Colab's (numpy 2.2, pandas 2.2, matplotlib 3.10, torch 2.x). Newer releases (numpy ≥ 2.5, matplotlib ≥ 3.11) break two cells: an eigenvector angle cell in *Intro to Linear Algebra* and a layout-overlap cell in *matplotlib*.

**Result:** all 16 notebooks, 955 code cells, **0 errors**. Details are in [`outputs/run_summary.md`](outputs/run_summary.md).
