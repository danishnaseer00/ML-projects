<h1 align="center">ML-projects</h1>

<p align="center">
  <a href="https://python.org"><img src="https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white" alt="Python"></a>
  <a href="https://jupyter.org"><img src="https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white" alt="Jupyter"></a>
  <a href="https://pytorch.org"><img src="https://img.shields.io/badge/PyTorch-1.10%2B-ee4c2c?logo=pytorch&logoColor=white" alt="PyTorch"></a>
  <a href="https://tensorflow.org"><img src="https://img.shields.io/badge/TensorFlow-2.x-FF6F00?logo=tensorflow&logoColor=white" alt="TensorFlow"></a>
  <a href="https://scikit-learn.org"><img src="https://img.shields.io/badge/Scikit--Learn-Latest-F7931E?logo=scikit-learn&logoColor=white" alt="Scikit-Learn"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-green.svg" alt="License"></a>
  <a href="https://github.com/danishnaseer00/ML-projects"><img src="https://img.shields.io/github/stars/danishnaseer00/ML-projects?style=social" alt="Stars"></a>
</p>

<p align="center">
  A curated collection of machine learning and deep learning projects covering supervised learning, neural networks, computer vision, NLP, and MLOps fundamentals. Each project is a self-contained Jupyter notebook with detailed walkthroughs, visualizations, and production-ready code.
</p>

---

## Projects

| Project | Category | Framework | Description |
|---------|----------|-----------|-------------|
| [Stacked BiLSTMs for Text Generation](Stacked-lSTMs-for-Text-Generation/) | Natural Language Processing | TensorFlow / Keras | Character-level text generation using stacked bidirectional LSTMs trained on Shakespeare corpus |
| [Image Classification with Data Augmentation (CNN)](Image-Classification-with-Data-Augmentation-CNN-/) | Computer Vision | TensorFlow / Keras | Cat vs Dog classification with CNN + data augmentation to reduce overfitting |
| [Credit Card Fraud Detection using ANN](Credit-Card-Fraud-Detection-using-ANN-/) | Anomaly Detection | TensorFlow / Keras | Binary classification on imbalanced transaction data using deep neural networks |
| [Hyperparameter Tuning for Neural Networks](Fine-Tuning-Hyperparameters-for-NN/) | Model Optimization | TensorFlow / Keras | Systematic hyperparameter search strategies for improving neural network performance |
| [Multiple Linear Regression from Scratch](Multiple-LR-Using-Stochastic-Gradient-Descent/) | Classical ML | NumPy | Linear regression implemented from scratch using Normal Equation and Stochastic Gradient Descent |
| [PyTorch Learnings](Pytorch-Learnings/) | Deep Learning | PyTorch | Foundational PyTorch experiments covering tensors, autograd, and neural network modules |
| [LLM Fine-Tuning with Unsloth](codeminx/) | LLM / Fine-Tuning | Unsloth / Hugging Face | Efficient fine-tuning of large language models using the Unsloth framework |
| [Matplotlib](Matplotlib/) | Data Visualization | Matplotlib | Comprehensive visualization techniques for exploratory data analysis |
| [Pandas](Pandas/) | Data Engineering | Pandas | Data manipulation, cleaning, and transformation workflows |

---

## Skills Covered

**Machine Learning** — Linear Regression, Stochastic Gradient Descent, Hyperparameter Tuning, Cross-Validation, Feature Engineering  
**Deep Learning** — Artificial Neural Networks, CNNs, LSTMs, Bidirectional RNNs, Transfer Learning, Fine-Tuning  
**Natural Language Processing** — Text Generation, Character-Level RNNs, Tokenization, Sequence Modeling  
**Computer Vision** — Image Classification, Data Augmentation, Convolutional Neural Networks  
**LLM & Fine-Tuning** — Unsloth, Parameter-Efficient Fine-Tuning, Hugging Face Ecosystem  
**Data Engineering** — Pandas, Data Cleaning, ETL Pipelines, Exploratory Data Analysis  
**Data Visualization** — Matplotlib, Statistical Plots, Insight Communication  
**MLOps Fundamentals** — Jupyter Notebooks, Reproducible Experiments, Model Evaluation Metrics

---

## Getting Started

```bash
# Clone the repository
git clone https://github.com/danishnaseer00/ML-projects.git
cd ML-projects

# Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install core dependencies
pip install numpy pandas matplotlib scikit-learn tensorflow pytorch jupyter
```

Open any project folder and launch its notebook:

```bash
jupyter notebook "Credit-Card-Fraud-Detection-using-ANN-/Credit_Card_Fraud_Detection (2).ipynb"
```

---

## Repository Structure

```
ML-projects/
├── Stacked-lSTMs-for-Text-Generation/     # NLP — BiLSTM text generation
├── Image-Classification-with-Data-Augmentation-CNN-/  # CV — CNN with augmentation
├── Credit-Card-Fraud-Detection-using-ANN-/   # Anomaly — Fraud detection
├── Fine-Tuning-Hyperparameters-for-NN/    # Hyperparameter search
├── Multiple-LR-Using-Stochastic-Gradient-Descent/  # ML from scratch
├── Pytorch-Learnings/                      # PyTorch fundamentals
├── codeminx/                               # LLM fine-tuning with Unsloth
├── Matplotlib/                             # Data visualization
├── Pandas/                                 # Data manipulation
└── README.md
```

---

## Key Highlights

- **From Scratch Implementations** — Linear regression built with pure NumPy to solidify mathematical foundations
- **Production Patterns** — Data pipelines, train/val/test splits, normalization, early stopping, and checkpointing
- **Imbalanced Learning** — Fraud detection using class weighting and threshold tuning on skewed datasets
- **NLP Pipeline** — Full text generation workflow: tokenization, sequence creation, stacked BiLSTM training, and temperature-based sampling
- **Modern LLM Fine-Tuning** — Efficient fine-tuning using Unsloth for reduced memory footprint and faster training

---

## License

This repository is available under the [MIT License](LICENSE).

---

## Connect

<p align="center">
  <b><a href="https://danishnaseer.tech">Danish Naseer</a></b><br>
  AI Engineer building agentic systems | DevOps (Docker, AWS, K8s)<br>
  <a href="https://github.com/danishnaseer00">GitHub</a> · <a href="https://linkedin.com/in/danishnaseer">LinkedIn</a> · <a href="https://twitter.com/thedanishNaseer">Twitter/X</a>
</p>