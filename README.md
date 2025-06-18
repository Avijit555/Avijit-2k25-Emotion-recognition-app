# 😄 Avijit AI 2k25 – Face Emotion Detector

**Avijit AI 2k25** is a real-time facial emotion recognition web application developed using **Streamlit**, **OpenCV**, and a custom **CNN-based deep learning model** trained on a rebalanced **FER-2013** dataset. The app allows users to detect emotions from both live webcam feeds and uploaded images in a user-friendly interface.

---

## 🚀 Features

- 🔐 **Secure Login System** – Basic user authentication  
- 📸 **Real-Time Emotion Detection** – Detects emotions from webcam input  
- 🖼️ **Image Upload Analysis** – Detects emotions in static uploaded images  
- 📊 **Confidence Score Visualization** – Displays probabilities for each emotion  
- 👥 **About Page** – Developer information and contact section  

---

## 🧠 Model Overview

| Detail           | Description                                 |
|------------------|---------------------------------------------|
| **Architecture** | Custom 5-layer CNN                          |
| **Dataset**      | FER-2013 (balanced: 5,000 images/class)     |
| **Accuracy**     | ~70% on test set                            |
| **Preprocessing**| Grayscale, normalization, class rebalancing |
| **Frameworks**   | TensorFlow, Keras, OpenCV                   |

---

## 📁 Project Structure

```bash
emotion-recognition-app/
├── app.py                         # Main Streamlit application
├── emotion_recognition_model.h5  # Trained CNN model
├── data balancing.ipynb           # Dataset rebalancing notebook
├── model Training.ipynb           # CNN training notebook
├── requirements.txt               # Python dependencies
├── README.md                      # Project documentation
├── assets/                        # UI images and icons
└── .streamlit/                    # Streamlit config files


``` 
## ⚙️ Installation & Setup

To run this app locally:

### 1. Clone the Repository

```bash
git clone https://github.com/Avijit555/Avijit-2k25-Emotion-recognition-app.git
cd Avijit 2k25 emotion-recognition-app
```



### 2. **Install Dependencies**
```bash
pip install -r requirements.txt
```

### 3. **Launch the Application**
```bash
streamlit run app.py
```
## 📸 Screenshots

### 🏠 Home Interface
<img src="assets/home.jpg" width="600"/>

### 🎥 Webcam Detection
<img src="assets/realtime emotion detection.jpg" width="600"/>

### 🖼️ Image Upload Result
<img src="assets/upload image.jpg" width="600"/>

---

## 🙋‍♂️ Developer Profile

### Avijit Paul  

<img src="assets/avijit.jpg" alt="Avijit Paul" width="140"/>

*Lead Developer & ML Engineer*

- 📧 Email: [raj44042065@gmail.com](mailto:raj44042065@gmail.com)  

## 🛠️ Tech Stack

| Category           | Tools & Technologies             |
|--------------------|----------------------------------|
| **Language**       | Python                           |
| **Frontend**       | Streamlit, HTML, CSS             |
| **Computer Vision**| OpenCV                           |
| **Deep Learning**  | TensorFlow, Keras                |
| **Data Handling**  | NumPy, Pandas                    |
| **Visualization**  | Matplotlib, Seaborn              |
| **Version Control**| Git, GitHub                      |

---

## 📈 Future Improvements

- 🚀 Deploy to Streamlit Cloud for public access  
- 📊 Add user session analytics  
- 📸 Multi-face detection & tracking  
- 🧠 Improve model accuracy with deeper architecture  
- 🤳 Expand dataset with user-submitted images  

---

## 📄 License

This project is intended for academic and educational use only.  
For reuse, extension, or commercial applications, please contact the developer.

---

## ⭐️ Support

If you found this project useful, please consider giving it a ⭐ on [GitHub](https://github.com/Avijit555/Avijit-2k25-Emotion-recognition-app.git)!
