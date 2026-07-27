# 🐱🐶 Cat vs Dog Image Classification with Data Augmentation

A deep learning project built using TensorFlow and Keras to classify images of cats and dogs. This project demonstrates the use of **ImageDataGenerator**, **data augmentation**, and **convolutional neural networks (CNNs)**. Trained and evaluated on the popular `PetImages` dataset.

---

## 📁 Dataset

**Source**: [Kaggle - Dog and Cat Classification Dataset](https://www.kaggle.com/datasets/bhavikjikadara/dog-and-cat-classification-dataset)

**Structure**:

cat_dog_dataset/
└── PetImages/
├── Cat/
└── Dog/


> Note: The dataset contains some corrupt images. A cleaning script is included to remove them before training.
>
> 

## 🧠 Model Architecture

- Input shape: `(64, 64, 3)`
- 2 × Convolutional layers + MaxPooling
- Flatten layer
- Dense (ReLU)
- Output layer (Sigmoid for binary classification)

---

## 🧪 Training Details

- **Data Augmentation** used:
  - Rotation
  - Zoom
  - Horizontal Flip
- **Train-Validation Split**: 80/20
- **Optimizer**: Adam
- **Loss**: Binary Crossentropy
- **Metrics**: Accuracy
- **Epochs**: 5 (adjustable)
- **Batch Size**: 32

---

## 📈 Results

Achieved ~90% accuracy after 5–10 epochs

Effective data augmentation improved generalization

Faster training using target_size=(64, 64) and GPU runtime

## ✅ Future Improvements

Use transfer learning (e.g., MobileNetV2 or EfficientNet)
Deploy model via Streamlit or Flask
Add confusion matrix & classification report
Hyperparameter tuning

