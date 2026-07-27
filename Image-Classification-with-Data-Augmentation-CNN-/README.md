<h1 align="center">Cat vs Dog Image Classification with Data Augmentation</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/TensorFlow-2.x-FF6F00?logo=tensorflow&logoColor=white" alt="TensorFlow">
  <img src="https://img.shields.io/badge/Keras-Latest-D00000?logo=keras&logoColor=white" alt="Keras">
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white" alt="Jupyter">
</p>

<p align="center">CNN-based image classification with data augmentation to classify cats and dogs using the PetImages dataset.</p>

---

## Dataset

- **Source**: [Kaggle - Dog and Cat Classification Dataset](https://www.kaggle.com/datasets/bhavikjikadara/dog-and-cat-classification-dataset)
- **Structure**: PetImages/ → Cat/ + Dog/ (includes corrupted images removed via cleaning script)

## Model Architecture

- Input shape: `(64, 64, 3)`
- 2x Convolutional layers + MaxPooling
- Flatten → Dense (ReLU) → Output (Sigmoid)

## Training Details

- **Data Augmentation**: Rotation, Zoom, Horizontal Flip
- **Train/Val Split**: 80/20
- **Optimizer**: Adam
- **Loss**: Binary Crossentropy
- **Epochs**: 5 (adjustable)
- **Batch Size**: 32

## Results

- ~90% accuracy after 5–10 epochs
- Data augmentation significantly improved generalization
- Faster training with target_size=(64, 64) and GPU runtime
