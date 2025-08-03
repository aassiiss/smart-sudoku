# AI-Driven Sudoku Puzzle Solver 🧠📷
This project leverages Artificial Intelligence and Computer Vision techniques to recognize and solve Sudoku puzzles directly from real-world images.

---

## 📌 Features
This project leverages Artificial Intelligence and Computer Vision techniques to recognize and solve Sudoku puzzles directly from real-world images.

-🧠 Digit recognition using a Convolutional Neural Network (CNN)
-🧾 Extracts and identifies the Sudoku board from input images
-📦 Segments the board into 81 individual cells automatically
-🔍 Classifies the digits with a trained CNN model
-🧩 Applies recursive backtracking to find the solution
-✅ Robust to noisy, rotated, or skewed puzzle inputs

---


---

## 🚀 How It Works

### 1. Digit Classifier Training
A convolutional neural network is trained on a dataset of handwritten digits (0–9), with data augmentation applied to improve generalization.

```python
model.fit(datagen.flow(train_X, train_y, batch_size=32), epochs=30, ...)




