# 🖼️ AI vs Real Image Classifier using SVM

A machine learning web application that classifies uploaded images as **AI-Generated** or **Real** using a **Support Vector Machine (SVM)** classifier. Built with **Python**, **Scikit-learn**, and **Streamlit**, the application provides a simple interface for real-time image classification.

> **Note:** This project is intended as a demonstration of classical machine learning for image classification and is not a universal AI image detector.

---

## 🚀 Features

* Upload an image for instant classification.
* Predicts whether an image is **AI-Generated** or **Real**.
* Fast inference using a pre-trained Support Vector Machine (SVM).
* Interactive and lightweight Streamlit web interface.
* Easy to run locally or deploy online.

---

## 🛠️ Tech Stack

* **Python**
* **Scikit-learn**
* **OpenCV**
* **NumPy**
* **Streamlit**
* **Joblib / Pickle**

---

## 📁 Project Structure

```text
SVM_image_classifier/
│── app.py                 # Streamlit web application
│── model_svm.pkl          # Trained SVM model
│── requirements.txt       # Project dependencies
│── README.md              # Project documentation
│── assets/                # Screenshots (optional)
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/anula-codes/SVM_image_classifier.git
cd SVM_image_classifier
```

### Create a virtual environment (Optional)

**Windows**

```bash
python -m venv venv
venv\Scripts\activate
```

**Linux/macOS**

```bash
python3 -m venv venv
source venv/bin/activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Application

Start the Streamlit application:

```bash
streamlit run app.py
```

Then open your browser and visit:

```
http://localhost:8501
```

---

## 🧠 How It Works

```
Input Image
      │
      ▼
Image Preprocessing
      │
      ▼
Feature Extraction
      │
      ▼
Support Vector Machine (SVM)
      │
      ▼
Prediction
      │
      ▼
AI-Generated / Real
```

---

## 📊 Model Details

| Attribute | Value                        |
| --------- | ---------------------------- |
| Model     | Support Vector Machine (SVM) |
| Framework | Scikit-learn                 |
| Input     | Image                        |
| Output    | AI-Generated or Real         |
| Interface | Streamlit                    |

---

## ⚠️ Limitations

This classifier is trained on a specific dataset and performs best on images that are **similar to those seen during training**.

As a result:

* It is **not a universal AI image detector**.
* Performance may decrease on images that differ significantly from the training dataset.
* Images with different styles, resolutions, editing techniques, or content may produce inaccurate predictions.
* The model should be considered a proof-of-concept demonstrating the use of classical machine learning for image classification.

Improving the diversity and size of the training dataset can significantly improve the model's ability to generalize.

---

## 📸 Demo
(will add)

---

## 📦 Requirements

```
streamlit
scikit-learn
opencv-python
numpy
Pillow
joblib
```

Install them using:

```bash
pip install -r requirements.txt
```

---

## 🎯 Future Improvements

* Improve model generalization with a larger and more diverse dataset.
* Display prediction confidence scores.
* Compare multiple machine learning and deep learning models.
* Add explainable AI (XAI) visualizations.
* Support batch image classification.
* Dockerize the application for easier deployment.

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new branch.

```bash
git checkout -b feature-name
```

3. Commit your changes.

```bash
git commit -m "Add new feature"
```

4. Push to your branch.

```bash
git push origin feature-name
```

5. Open a Pull Request.

---

## 👩‍💻 Author

**Anula Mishra**

GitHub: https://github.com/anula-codes

---

⭐ If you found this project helpful, consider giving it a **Star** on GitHub!
