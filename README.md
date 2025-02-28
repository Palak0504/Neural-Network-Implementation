# Simple Neural Network from Scratch in Python

A basic feedforward neural network implemented from scratch using **NumPy**. This project demonstrates how a neural network learns using **forward propagation, backpropagation, and gradient descent**—without using deep learning libraries like TensorFlow or PyTorch.

---

##  Features
✔️ Implements **forward pass & backpropagation**  
✔️ Uses the **sigmoid activation function**  
✔️ Trains on the **XOR problem**  
✔️ Updates weights using **gradient descent**  

---

## 🔧 Installation & Usage
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/simple-neural-network.git
cd simple-neural-network
```

### 2️⃣ Install Dependencies
Only **NumPy** is required:
```bash
pip install numpy
```

### 3️⃣ Run the Neural Network
```bash
python neural_network.py
```

---

##  How It Works
1. **Forward Pass** – Inputs pass through the network, producing an output.  
2. **Loss Calculation** – The error between predicted and actual values is computed using **Mean Squared Error (MSE)**.  
3. **Backpropagation** – The error is used to adjust weights using **gradient descent**.  
4. **Training** – The network repeats these steps until the loss is minimized.  

---

##  Training Example Output
```
Epoch 0 - Loss: 0.5136
Epoch 1000 - Loss: 0.1083
Epoch 9000 - Loss: 0.0496

Predictions after training:
[[0.99]  # ~1 for (0,0)
 [0.01]  # ~0 for (0,1)
 [0.02]  # ~0 for (1,0)
 [0.98]] # ~1 for (1,1)
```

---

##  Future Improvements
🔹 Add more activation functions (ReLU, Tanh)  
🔹 Implement batch training  
🔹 Expand to a multi-class classification problem  

---

## Contributing
Feel free to fork this repo, suggest improvements, or open issues!

