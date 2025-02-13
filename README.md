# A Unified Evaluation Framework for Epistemic Predictions

This repository contains code for the AISTATS 2025 paper: [A Unified Evaluation Framework for Epistemic Predictions](https://arxiv.org/abs/2501.16912).


## 📄 Abstract
Predictions of uncertainty-aware models are diverse, ranging from single point estimates (often averaged over prediction samples) to predictive distributions, to set-valued or credal-set representations.  

We propose a **novel unified evaluation framework** for uncertainty-aware classifiers, applicable to a wide range of model classes. Our framework enables users to **tailor the trade-off between accuracy and precision** of predictions via a custom-designed performance metric. This allows for selecting the **most suitable model** for a given real-world application based on the desired trade-off.  

Our experiments on **CIFAR-10, MNIST, and CIFAR-100** evaluate Bayesian, ensemble, evidential, deterministic, credal, and belief function classifiers, demonstrating that our metric behaves as intended.

---

## 🚀 Getting Started

### **1️⃣ Environment Setup**
Set up the environment using `environment.yml`:
```
conda env create -f environment.yml
conda activate myenv
```

For GPU support, ensure TensorFlow GPU version is installed:
```
python3 -m pip install tensorflow[and-cuda]
```

### **2️⃣ Running the Evaluation**
Use the eval_epistemic_preds.ipynb notebook to compute the Evaluation Metric.

```
jupyter notebook eval_epistemic_preds.ipynb
```

---

### **📊 Experiments & Datasets**
The framework has been evaluated on the following datasets:
- **CIFAR-10**
- **MNIST**
- **CIFAR-100**

The experiments include evaluations on:
- **Bayesian classifiers**
- **Ensemble methods**
- **Evidential classifiers**
- **Deterministic models**
- **Credal classifiers**
- **Belief function classifiers**

### **📂 Repository Structure**
```
📂 root
│-- 📄 README.md             # This README file
│-- 📜 environment.yml       # Conda environment setup file
│-- 📁 notebooks/            # Jupyter Notebooks for evaluation
│   ├── eval_epistemic_preds.ipynb
│-- 📁 src/                  # Source code for evaluation framework
│-- 📁 data/                 # Sample datasets
```

---
### **📢 Citation**
If you use this code, please cite our paper:

```
@inproceedings{
manchingal2025a,
title={A Unified Evaluation Framework for Epistemic Predictions},
author={Shireen Kudukkil Manchingal and Muhammad Mubashar and Kaizheng Wang and Fabio Cuzzolin},
booktitle={The 28th International Conference on Artificial Intelligence and Statistics},
year={2025},
url={https://openreview.net/forum?id=kXC0Sdf8KN}
}
```

---
### **📬 Contact**
For questions or issues, feel free to open an issue or contact the [author](shireenmohammed67@gmail.com).

---
### **⭐ Acknowledgments**
This research has received funding from the European Union’s Horizon 2020 Research and Innovation program under Grant Agreement No. 964505 (E-pi).
