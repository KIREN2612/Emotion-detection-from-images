# Facial Expression Detection Using CNN on FER-2013 Dataset

This project is a **deep learning-based facial expression detection system** built using **TensorFlow** and trained on the **FER-2013** dataset. It leverages a **custom Convolutional Neural Network (CNN)** model optimized for lightweight environments like **Google Colab**, and is intended as a **learning project** to understand facial expression recognition using neural networks.

---

## 📌 Project Goals

- Build a facial emotion recognition model from scratch using CNN.
- Learn preprocessing, augmentation, and training pipelines on grayscale images.
- Analyze accuracy, confusion matrix, and classification metrics.
- Provide a working baseline model that others can fork and improve.

---

## 🎯 Key Features

- Supports detection of 7 emotions: `Angry`, `Disgust`, `Fear`, `Happy`, `Sad`, `Surprise`, `Neutral`.
- Uses **custom CNN** designed for simplicity and interpretability.
- Includes **training visualization**, **confusion matrix**, and **classification report**.
- Optimized for use in **Google Colab** (low memory usage and efficient loading).
- Easily extendable with your own datasets or improvements.

---

## 📊 Model Performance

- **Validation Accuracy Achieved:** ~64%
- **Observations:** While validation accuracy may appear modest, the model **consistently predicts facial expressions correctly on real inputs**, especially when lighting and pose are controlled.
- **Interpretation:** This model can serve as a strong baseline and demonstrates promising results despite being compact.

---

## 🖼️ Screenshots

Screenshots of model predictions, training curves, and confusion matrix are provided in the `outputs/` folder.

---

## 🚀 How to Use

1. Clone this repository or open in Colab.
2. Ensure the FER-2013 dataset is structured as:
/fer2013_data/
/train/
/angry/, /happy/, ...
/validation/
/angry/, /happy/, ...
/test/
/angry/, /happy/, ...

yaml
Copy
Edit
3. Run the notebook or Python script (`facial_expression_detection.py`).
4. View training logs, evaluation results, and modify as needed.

---

## 🛠️ Dependencies

- TensorFlow >= 2.x
- NumPy, Matplotlib, Seaborn
- Scikit-learn

All dependencies are standard and installable via `pip`.

---

## 📂 Repository Structure

📁 Facial-Expression-Detection/
├── facial_expression_detection.py # Main training and evaluation script
├── outputs/
│ ├── training_plot.png
│ ├── confusion_matrix.png
│ └── example_predictions.png
├── README.md



---

## 📌 License & Contributions

This project is **free to use, modify, and extend**. Feel free to fork this repo, update the model architecture, or add features like webcam inference, live prediction, etc. Pull requests are welcome!

> ✨ **This was built as part of a self-learning exercise**, and while it’s not a production-grade model, it reflects strong foundational capabilities and can be a great starting point for others.

---

## 🙋‍♂️ Author

**Kiren S. (Sanji)**  
Made with ❤️ for learning and experimentation.

---
