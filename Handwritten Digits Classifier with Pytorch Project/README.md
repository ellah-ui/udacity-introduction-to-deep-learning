# 🖋️ Handwritten Digits Classifier with PyTorch

This project is a **handwritten digit classifier** built with **PyTorch**, trained on the famous **MNIST dataset**.  
It was created as part of the **Udacity – Introduction to Deep Learning** coursework and demonstrates how to design, train, and evaluate deep learning models.  

The project compares a **Fully Connected Neural Network (FCNN)** baseline with a more powerful **Convolutional Neural Network (CNN)**, showing the importance of model architecture in image classification.

---

## 📂 Project Structure

```
Handwritten Digits Classifier with Pytorch Project/
│
├── data/                  # Dataset directory (MNIST and related files)
│   └── README.md          # Details about dataset storage and usage
│
├── models/ (optional)     # Saved model checkpoints
│
├── notebooks/             # Jupyter notebooks for exploration & training
│
├── main.py (optional)     # Example training/testing script
│
└── README.md              # Main project documentation
```

---

## 🚀 What I Learned

- How to load and preprocess image data using **torchvision**
- Building custom neural networks with **`torch.nn`**  
- Implementing training loops with loss tracking and **GPU acceleration**  
- Comparing models (FCNN vs CNN) for performance on image data  
- Saving and reloading trained models with **`torch.save`**  

---

## 📊 Results

- The **FCNN baseline** achieved ~92–94% accuracy.  
- The **CNN model** improved accuracy to **98%+**, showing clear advantages on image data.  
- Loss curves confirmed smooth convergence across epochs.  

---

## ⚙️ How to Run

### 1. Clone the repository
```bash
git clone https://github.com/ellah-ui/udacity-introduction-to-deep-learning.git
cd "Handwritten Digits Classifier with Pytorch Project"
```

### 2. Install dependencies
```bash
pip install torch torchvision matplotlib numpy
```

### 3. Run Jupyter Notebook
```bash
jupyter notebook
```

Open the provided notebooks to explore, train, and test the models.

---

## 📂 Dataset

This project uses the **MNIST dataset** (70,000 grayscale images of handwritten digits).  
PyTorch’s `torchvision.datasets.MNIST` automatically downloads and manages the dataset in the `data/` directory.  

👉 For more details, see: [data/README.md](data/README.md)

---

## 💾 Saving and Loading Models

Save your trained model:
```python
torch.save(model.state_dict(), "models/mnist_cnn.pth")
```

Load it later:
```python
model.load_state_dict(torch.load("models/mnist_cnn.pth"))
```

---

## 🙌 Acknowledgments

- Udacity – Introduction to Deep Learning
- [PyTorch Documentation](https://pytorch.org/docs/stable/index.html)  
- MNIST dataset by Yann LeCun et al.  

---

## 🌟 Portfolio Note

This project demonstrates my ability to:  
- Work with **real datasets** and preprocess data for deep learning.  
- Build, train, and evaluate **neural networks** from scratch.  
- Apply **hyperparameter tuning** and architectural choices to improve accuracy.  
- Document and organize code in a professional, GitHub-ready format.  
