# 🎓 AI-Powered College Assistant

An interactive, AI-powered web assistant designed to support students both academically and emotionally. This project integrates facial recognition, emotion-aware recommendations, and a mental health companion — all built using **Flask** and **Streamlit**, and powered by machine learning and deep learning models.

##  Features

###  1. Face Recognition-Based Attendance System
- Utilizes a **pretrained deep learning model** for facial recognition.
- Automatically marks attendance by matching detected faces with registered students.
- Replaces traditional manual or biometric systems with a seamless experience.

###  2. Mental Health Chatbot
- A conversational AI chatbot trained or powered by a **pretrained NLP model** .
- Provides empathetic responses to support student mental well-being.
- Not rule-based — dynamically understands and replies based on context.

###  3. Mood-Based Movie & Book Recommendation
- Detects emotion from user’s uploaded image or manual input.
- Recommends movies/books based on mood and user preferences.
- considering mood, genre similarity (via cosine similarity), and user rating history.

##  Tech Stack

| Component            | Technology Used                        |
|----------------------|----------------------------------------|
| Backend              | Flask                                  |
| Frontend             | Streamlit                              |
| Face Recognition     | OpenCV, DeepFace / FaceNet (pretrained)|
| Chatbot              | HuggingFace Transformers               |
| Recommender System   | Scikit-learn, TensorFlow/Keras, NLP    |
| Mood Detection       | Pretrained Emotion Classifier Models   |


## 📌 Installation & Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/virusisnotavailable/Final_project.git
   cd ai-college-assistant
2. pip install -r requirements.txt
3. streamlit run streamlit_app.py
