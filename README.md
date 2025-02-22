# 🏥 Medical Visual Question Answering (VQA) with IDEFICS & LLaVA

![Python](https://img.shields.io/badge/Python-3.x-blue) ![Flask](https://img.shields.io/badge/Flask-Backend-red) ![LLM](https://img.shields.io/badge/LLM-Multimodal-green)

A **Medical Visual Question Answering (VQA) system** using **fine-tuned IDEFICS and LLaVA models** to answer questions based on medical images. 

## 🚀 Features
- 🏥 Fine-tuned **IDEFICS** and **LLaVA** models for medical VQA
- 🎯 Achieved **42% accuracy** with IDEFICS and **38% accuracy** with LLaVA
- 💬 Interactive chat interface for medical image-based Q&A
- ⚡ Flask-based API for model inference

## 📑 Table of Contents
- [Tech Stack](#-tech-stack)
- [Installation](#-installation)
- [Usage](#-usage)
- [API Endpoints](#-api-endpoints)
- [Demo](#-demo)
- [Contributing](#-contributing)
- [License](#-license)
- [Author](#-author)

## 🛠 Tech Stack
- **Model:** IDEFICS & LLaVA (fine-tuned for medical VQA)
- **Backend:** Flask (Python)
- **Frontend:** MERN (MongoDB, Express, React, Node.js)

## ⚙️ Installation
### Prerequisites
- Python 3
- Node.js & npm
- Flask
- CUDA-enabled GPU (for faster inference)

### Backend Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name/backend
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Flask server:
   ```bash
   python app.py
   ```

### Frontend Setup
1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the React application:
   ```bash
   npm start
   ```

## 🎯 Usage
1. Upload a **medical image**.
2. Ask a question related to the image.
3. Receive AI-generated answers based on the trained models.

## 🌐 API Endpoints
### Predict Medical Answer
```bash
POST /predict
```
#### Example Usage
```bash
curl -X POST -F "image=@path/to/image.jpg" -F "question=What is in the X-ray?" http://127.0.0.1:5000/predict
```

## 📸 Demo
![Medical VQA Chatbot UI](path_to_screenshot.png)

## 🤝 Contributing
Contributions are welcome! Open an issue or submit a pull request to improve the project.

## 📜 License
This project is open-source under the MIT License.

## 👤 Author
Developed by [Your Name] for advancing **medical AI research**.

---
🔥 If you like this project, give it a ⭐ on GitHub! 🚀
