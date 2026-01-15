🩺 Breast Cancer Detection Using Neural Networks

📋 Project Overview
This project uses a feedforward neural network built with PyTorch to predict breast cancer. Accurate detection of breast cancer is critical for early treatment and better patient outcomes.

The workflow includes:
🔍 Data Loading and Exploration
⚙️ Data Preprocessing & Scaling
🤖 Neural Network Model Training

📊 Model Evaluation
The model achieves high accuracy (~98%) on both training and testing datasets.

📂 Dataset
We use the Breast Cancer Wisconsin dataset from scikit-learn.
Features: 30 numerical features representing cell nuclei properties
Target: 0 = Malignant, 1 = Benign

🔑 Key Steps
1️⃣ Data Preprocessing
Split the dataset into training and testing sets 🧪
Scaled features using StandardScaler ⚖️
Converted data to PyTorch tensors 🔥

2️⃣ Neural Network Model
Input layer → Hidden Layer (ReLU) → Output layer (Sigmoid)
Loss function: Binary Cross-Entropy Loss 🧮
Optimizer: Adam ⚡
Device: CPU or GPU (auto-detected) 💻

3️⃣ Training
Model trained for num_epochs epochs
Accuracy and loss printed every 10 epochs 📈
Final model achieves:
Training Accuracy: 98.46% 🏆
Testing Accuracy: 98.25% 🎯

4️⃣ Evaluation
Predicted outputs are rounded to 0 or 1
Calculated accuracy on both training and testing sets ✅

📊 Results
High accuracy on both training and testing datasets
Neural network effectively distinguishes malignant vs benign tumors
Provides a reliable baseline for early breast cancer detection

🌟 Future Improvements
🛠 Hyperparameter tuning (hidden layers, neurons, learning rate)
💡 Use dropout layers for better generalization
