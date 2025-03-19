# 🦖 Dinosaur Name Generator – Character-Level RNN

This project trains a **character-level Recurrent Neural Network (RNN)** to generate **new dinosaur names** based on an existing dataset. The model learns common letter patterns in dinosaur names and produces realistic-sounding new ones.

## 📌 Features
✅ Implements a **simple RNN from scratch using NumPy**  
✅ Learns character sequences from a dataset of real dinosaur names  
✅ Uses **gradient clipping** to prevent exploding gradients  
✅ Supports **sampling** to generate new names after training  

## 📂 Dataset
The dataset consists of real dinosaur names stored in `dinos.txt`. The model trains on this data to generate new names.

## 🏗️ Project Structure
```
📁 Dinosaur-Name-Generator
│── 📜 Dinosaurus_Island_Character_level_language_model.ipynb  # Jupyter Notebook (Main Code)
│── 📜 utils.py  # Helper functions for RNN
│── 📜 dinos.txt  # Dataset (list of dinosaur names)
│── 📜 README.md  # Project Documentation
```

## 🚀 How to Run
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/Dinosaur-Name-Generator.git](https://github.com/NotAIModel/Dinosaur-Name-Generator
   ```
2. **Install dependencies** (only NumPy required):
   ```bash
   pip install numpy
   ```
3. **Run the Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```

## 📊 Results
After training, the model generates names like:
```
Drepanosaurus
Tyrannoraptor
Velocisaurus
```

## 🛠 Technologies Used
- **Python**
- **NumPy**
- **Jupyter Notebook**
- **Recurrent Neural Networks (RNNs)**

## 📜 License
This project is open-source and free to use.

---
🔥 **Have fun generating dinosaur names!** 🦖
