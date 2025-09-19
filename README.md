# Deep-Learning-Projects
A collection of deep learning  projects demonstrating CycleGAN-based image translation, fine-grained bird species classification, and word-level language modeling. Includes notebooks, datasets references, and instructions to reproduce results.

---

## 📂 Projects Overview

### 1. CycleGAN – Human ↔ Animal Style Transfer
**Objective:** Train a CycleGAN model to transfer images between human faces and cats/dogs.

**Key Features:**
- Trained using UTK Face, InceptionV3 (human faces), Dog Face, and Cat datasets.
- Generated visually plausible stylized images using CycleGAN.
- Adjustable hyperparameters for improved training and reduced overfitting.

**Notebook:** [CycleGAN Colab Notebook](https://colab.research.google.com/drive/1IBqrzfUyAd6SO7HiPCIiZaAxXeAFqXEk)  
**Dataset References:**
- [UTK Face Cropped](https://www.kaggle.com/datasets/abhikjha/utk-face-cropped)
- [nceptionv3](https://www.kaggle.com/code/bmarcos/image-recognition-gender-detection-inceptionv3/data)
- [Dog Face Dataset]( https://www.kaggle.com/datasets/wutheringwang/dog-face-recognition)  
- [Cat Dataset](https://www.kaggle.com/datasets/azmeenasiraj/cat-faces-data-set)  

---

### 2. Fine-Grained Bird Species Classification
**Objective:** Classify bird species with high accuracy using transfer learning.

**Key Features:**
- Achieved >90% accuracy on the CUB-200-2011 dataset using PyTorch.
- Hyperparameter tuning for optimal performance.
- Evaluated using Accuracy, Precision, Recall, and Confusion Matrix.

**Notebook:** [Bird Species Classification Colab Notebook](https://colab.research.google.com/drive/1t8jcUYhswvVZNGzxMLrGOnzkfqRVv--e)  
**Dataset Reference:** [CUB-200-2011](https://data.caltech.edu/records/65de6-vp158)  

---

### 3. Word-Level Language Model
**Objective:** Train a word-level language model to generate text in the style of Agatha Christie’s *“Poirot Investigates”*.

**Key Features:**
- Implemented using recurrent layers / transformer layers.
- Generates semantically and syntactically meaningful text when prompted.
- Includes checkpoints for inference with custom input prompts.

**Notebook:** [Language Model Colab Notebook](https://colab.research.google.com/drive/1AOSB2QzgxL46O3D9cIxPdfS8yJ8tsLPw)  
**Dataset Reference:** [Poirot Investigates by Agatha Christie](https://www.kaggle.com/datasets/jannesklaas/scifi-stories-text-corpus)


---

## ✅ How to Run
1. Open the respective Colab notebook.
2. Follow the instructions for dataset download, model training, and inference.
3. Use the provided checkpoints to reproduce results without retraining.

---

## 📌 Key Technologies
- **Frameworks:** PyTorch, TensorFlow, Keras  
- **ML Techniques:** CycleGAN, Transfer Learning, RNNs, Transformers  
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1, Confusion Matrix  
- **Tools:** Google Colab, GitHub, MLflow/W&B

