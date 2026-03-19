# 🩺 Diabetic Retinopathy Detection using Deep Learning
![Python](https://img.shields.io/badge/Python-3.8-blue)
![Accuracy](https://img.shields.io/badge/Accuracy-98%25-brightgreen)
![Status](https://img.shields.io/badge/Project-Completed-success)
![Domain](https://img.shields.io/badge/Domain-Healthcare-red)
---
## 📌 Overview

Diabetic Retinopathy is a serious eye disease caused by diabetes that can lead to blindness if not detected early.

This project presents a **deep learning-based system** that automatically detects and classifies diabetic retinopathy from retinal fundus images, enabling early diagnosis and treatment.

---

## 🎯 Objectives

* Detect diabetic retinopathy from retinal images
* Classify severity levels using deep learning
* Build an automated and user-friendly system
* Assist in early medical diagnosis

---

## 🚀 Features

✔ Automated disease detection
✔ Multi-class classification (5 severity levels)
✔ High accuracy prediction (98%)
✔ Deep learning-based model
✔ User-friendly interface

---

## 🛠️ Tech Stack

* **Programming Language:** Python
* **Libraries:** NumPy, Pandas, OpenCV, Matplotlib
* **Frameworks:** PyTorch / TensorFlow
* **Frontend:** HTML, CSS (Flask Templates)
* **Tools:** Jupyter Notebook

---

## 📂 Project Structure

```bash id="4d9ed1"
Diabetic-Retinopathy-Detection/
│
├── backend/
│   └── model_training.ipynb
│
├── frontend/
│   └── web_app.ipynb
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 📁 Dataset

This project uses the **APTOS 2019 Blindness Detection dataset**.

🔗 https://www.kaggle.com/competitions/aptos2019-blindness-detection

### 📊 Dataset Details

* ~3662 training images
* Real-world retinal fundus images
* Labeled by medical experts

### 🧠 Classes

* 0 → No DR
* 1 → Mild
* 2 → Moderate
* 3 → Severe
* 4 → Proliferative DR

### ⚠️ Challenges

* Class imbalance
* Noise and blur in images
* Different lighting conditions

---

## ⚙️ How It Works

1. Image preprocessing (resizing, normalization, enhancement)
2. Deep learning model training
3. Feature extraction from retinal images
4. Classification into severity levels
5. Prediction through user interface

---

## ▶️ How to Run

### 1. Clone the repository

```bash id="b6y0br"
git clone https://github.com/your-username/diabetic-retinopathy-detection.git
```

### 2. Install dependencies

```bash id="u8d5me"
pip install -r requirements.txt
```

### 3. Run the project

```bash id="eym0wr"
jupyter notebook
```

---

## 📊 Results

The deep learning model achieved **excellent performance** on the dataset.

### ✅ Model Performance

* 🎯 **Accuracy:** 98%
* 📌 Effective multi-class classification
* 📌 Robust performance on real-world images

### 📈 Evaluation Insights

* Successfully distinguishes all 5 severity levels
* Handles class imbalance effectively
* Performs well under different image conditions

### 🧪 Model Evaluation (Optional)

<img width="815" height="674" alt="image" src="https://github.com/user-attachments/assets/ad545b28-93ad-4abe-962f-9a6ef80a154b" />


---

## 📸 Output Screenshots

(Add your UI and prediction screenshots here)

```bash id="f3m7l0"
![Output](output.png)
```

---

## 🔍 Future Improvements

* Improve accuracy using advanced architectures
* Deploy as a real-time web application
* Add mobile support
* Integrate with healthcare systems

---

## 📁 Dataset Note

Dataset is not included due to size limitations. Please download it from the provided Kaggle link.

---

## 👩‍💻 Author

**Hema Sri**

BTech Student | Machine Learning Enthusiast

---

## ⭐ Acknowledgement

* Kaggle for providing dataset
* Open-source libraries and research community

---

## 📬 Contact

Feel free to reach out for collaboration or queries!
