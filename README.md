# 🧠 Brain Tumor Detection Using Deep Learning (VGG16 + Flask)

This is a deep learning-based web application that detects and classifies brain tumors from MRI images using a pre-trained **VGG16** model. It includes a Flask-based frontend for uploading images and viewing predictions. The model classifies the input MRI image into one of the following categories:

- **Glioma Tumor**
- **Meningioma Tumor**
- **Pituitary Tumor**
- **No Tumor**

---

## 📌 Key Features

- 🧠 MRI image classification with high accuracy
- ✅ Validates whether uploaded image is an actual MRI or not (using a binary classifier)
- 💻 Flask-based web interface
- 🗂 Sample image dataset for quick testing
- 🔬 Based on pre-trained VGG16 (Transfer Learning)

---

## 🧰 Tech Stack

- Python
- TensorFlow & Keras
- Flask
- OpenCV
- HTML/CSS (Flask Templates)

---

## 🚀 Installation & Running the App

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/brain-tumor-detection-vgg16
cd brain-tumor-detection

python -m venv venv
# On Windows:
venv\Scripts\activate
# On Linux/macOS:
source venv/bin/activate

pip install -r requirements.txt

python app/app.py

# Open your browser
Go to: http://127.0.0.1:5000
```

📸 Sample Screenshot

![image](https://github.com/user-attachments/assets/388d4e9d-9d8a-46d3-a85d-79cf1900e03b)
![image](https://github.com/user-attachments/assets/947602dc-b216-4a96-9c70-86da69bca630)


🔧 Future Enhancements
  - Add Grad-CAM visualizations to highlight tumor regions
  - Deploy the app to Heroku / Render
  - Improve UI with Bootstrap
  - Add patient record storage using a database

🤝 Contributing
Contributions are welcome! Please open an issue or pull request for discussion.

📜 License
This project is licensed under the MIT License.

🙋‍♂️ Author
Faizan Memon
🔗 LinkedIn - https://www.linkedin.com/in/faizan-memon-fm/


