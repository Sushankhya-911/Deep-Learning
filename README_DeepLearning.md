# 🧠 Deep Learning — Image Classification & NLP

A collection of Jupyter notebooks covering core deep learning concepts, from image classification with CNNs to transfer learning and NLP with BERT and Word2Vec.

---

## 📁 Notebooks

### 🖼️ Image Classification

#### `CNN(1).ipynb`
Convolutional Neural Network built from scratch for image classification.
- Conv2D, MaxPooling, Flatten, Dense layers
- Training and evaluation on image datasets
- Accuracy/loss visualization

#### `Deep learning(1).ipynb`
Foundational deep learning notebook covering:
- Building and training neural networks with Keras/TensorFlow
- Data preprocessing and augmentation
- Model evaluation and performance metrics

#### `Transfer learning-(CNN)-(2).ipynb`
Transfer learning for image classification using pre-trained CNN architectures (e.g., VGG16, ResNet, MobileNet).
- Feature extraction from pre-trained models
- Fine-tuning on custom datasets
- Comparison with training from scratch

---

### 📝 Natural Language Processing

#### `BERT Embedding Vector Understanding.ipynb`
Exploration of BERT's contextual embedding vectors.
- Extracting token and sentence embeddings
- Visualizing vector representations
- Understanding attention and context

#### `BERT finetune.ipynb`
Fine-tuning a pre-trained BERT model for a downstream NLP task.
- Loading BERT from HuggingFace Transformers
- Task-specific classification head
- Training loop and evaluation

#### `Word2vect.ipynb`
Word2Vec word embedding model implementation and analysis.
- Training Word2Vec (Skip-gram / CBOW)
- Visualizing word similarity with t-SNE
- Exploring semantic relationships between words

---

## 🛠️ Tech Stack

| Library | Purpose |
|---|---|
| TensorFlow / Keras | Model building & training |
| PyTorch | Deep learning framework |
| HuggingFace Transformers | BERT models |
| scikit-learn | Evaluation metrics |
| NumPy / Pandas | Data handling |
| Matplotlib / Seaborn | Visualization |
| Gensim | Word2Vec |

---

## 🚀 Getting Started

### Prerequisites
```bash
pip install tensorflow torch transformers scikit-learn numpy pandas matplotlib seaborn gensim jupyter
```

### Run a Notebook
```bash
git clone https://github.com/Sushankhya-911/Deep-Learning.git
cd Deep-Learning
jupyter notebook
```
Then open any `.ipynb` file in your browser.

---

## 📊 Key Concepts Covered

- **CNN architecture** — convolution, pooling, and fully connected layers
- **Transfer learning** — leveraging pre-trained weights for new tasks
- **BERT** — bidirectional transformers and contextual embeddings
- **Word embeddings** — dense vector representations of words
- **Model fine-tuning** — adapting pre-trained models to specific datasets

---

## 👤 Author

**Sushankhya Poudel** — [@Sushankhya-911](https://github.com/Sushankhya-911)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
