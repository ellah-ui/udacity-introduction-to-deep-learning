# Introduction to Deep Learning 📚

Welcome to my repository for the **Udacity – Introduction to Deep Learning** course. This project walks through how to build, train, and evaluate neural networks using **PyTorch**, focusing on classifying handwritten digits (MNIST).

---

##  Repository Overview

This repository includes:

- `Handwritten Digits Classifier with Pytorch Project/`  
  - Your primary project directory containing code and notebooks.
- `LICENSE`  
  - The open-source (MIT) license.
- `README.md`  
  - This file you're reading now.
- `Minimizing Error Functions`
   - Directory containing an exercise on Python functions.

---

##  MNIST Classification Project

Inside the `Handwritten Digits Classifier with Pytorch Project/` directory, you'll discover:
- **Data Loading & Preprocessing**: Using PyTorch's `torchvision.datasets.MNIST` to fetch and prepare data.
- **Model Architectures**: Comparison of a baseline Fully Connected Neural Network (FCNN) and a Convolutional Neural Network (CNN) that achieves better accuracy.
- **Training Workflow**: Custom training loops with real-time monitoring of loss and accuracy.
- **Model Evaluation**: Testing performance and analyzing output.
- **Model Persistence**: Saving (`torch.save`) and loading trained models.

---

##  Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/ellah-ui/udacity-introduction-to-deep-learning.git
   ```

2. Navigate into the project:

   ```bash
   cd udacity-introduction-to-deep-learning/"Handwritten Digits Classifier with Pytorch Project"
   ```

3. Install dependencies:

   ```bash
   pip install torch torchvision matplotlib numpy
   ```

4. Launch the Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Work through the notebook to explore data, train models, and track performance.

---

##  Results

- **FCNN Baseline**: Achieves approximately **92–94%** accuracy on MNIST.
- **CNN Model**: Boosts performance significantly — typically reaching **98%+** accuracy.

---

##  Acknowledgments

- Based on the **Udacity – Introduction to Deep Learning** foundational coursework.
- Built using **PyTorch**, with insights drawn from official documentation.
- Leveraging the classic MNIST dataset by Yann LeCun.

---

##  Why It Matters (Portfolio Highlight)

This project demonstrates:

- Hands-on experience with deep learning workflows in PyTorch.
- Practical skills in model building, evaluation, and tuning.
- The ability to document and organize projects clearly, great for showcasing on GitHub.

---

Enjoy exploring, learning, and experimenting — and feel free to reach out if you'd like to connect!
