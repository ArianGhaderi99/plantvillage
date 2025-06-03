# 🌿 Plant Disease Detection Website

This project is a web application powered by artificial intelligence that allows users to upload images of their plants and flowers to detect possible diseases. The system uses a deep learning model (MobileNetV2) to analyze the image and return the result to the user.

## 📸 UI Demo

### Home Page
![Home Page](./screenshots/home.png)

### Treatment Page
![Treatment Page](https://github.com/ArianGhaderi99/plantvillage/blob/main/image/photo_2025-06-03_17-30-07.jpg)

## 🛠️ Technologies Used

- **Django** – Main backend framework  
- **Redis & Celery** – For task queue and background processing  
- **SQLite** – Lightweight local database  
- **HTML & CSS** – Frontend design  
- **MobileNetV2** – Deep learning model for image classification  

## 🧠 About the AI Model

We used the **MobileNetV2** model, which is lightweight, fast, and suitable for web-based applications. The trained model runs on the server side and processes the uploaded image to detect any plant diseases.

## 👨‍💻 Team Members

- **[Your Name]** – Backend & AI model developer  
- **[Your Friend's Name]** – Frontend & Celery/Redis configuration  

## 🧑‍🤝‍🧑 Team Name

> **Team Name: [Your Team Name]**

## ⚙️ Installation & Setup

```bash
git clone https://github.com/username/repo-name.git
cd repo-name

# Create virtual environment
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run Django server
python manage.py runserver
