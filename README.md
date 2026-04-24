# 🧠 Self-Pruning Neural Network

A deep learning project that implements a **self-pruning neural network** to improve model efficiency by automatically removing less important weights during training. This helps reduce model size, improve inference speed, and maintain performance.

---

## 🚀 Features

- ✨ Automatic weight pruning during training  
- ⚡ Reduced model complexity  
- 📉 Improved efficiency with minimal accuracy loss  
- 🧪 Easy experimentation using Jupyter Notebook  
- 🔍 Clear implementation for learning and research  

---

## 📁 Project Structure
├── self_pruning_neural_network.ipynb # Main implementation notebook
├── README.md # Project documentation

---

## 🛠️ Technologies Used

- Python 🐍  
- TensorFlow / PyTorch (depending on your notebook)  
- NumPy  
- Matplotlib  

---

## ⚙️ How It Works

1. Initialize a neural network model  
2. Train the model on dataset  
3. Apply pruning technique:
   - Identify low-importance weights
   - Remove or zero them out
4. Fine-tune the model after pruning  
5. Evaluate performance  

---

## 📊 Benefits of Pruning

- Reduces overfitting  
- Decreases memory usage  
- Speeds up inference  
- Makes models deployable on edge devices  

---

## ▶️ How to Run

### Option 1: Using Google Colab
1. Open notebook in Google Colab  
2. Run all cells step by step  

### Option 2: Local Setup
```bash
pip install numpy matplotlib tensorflow
