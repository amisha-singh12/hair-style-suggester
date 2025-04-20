# 💇‍♀️ Hair Style Suggester

**Hair Style Suggester** is a project that uses trained facial recognition models to analyze your facial features and determine your unique face shape. Based on this analysis, it recommends hairstyles that best complement your natural geometry—so you don’t have to go through the eternal struggle of "will this haircut look good on me?"

Because let’s be honest: choosing the right hairstyle can sometimes feel harder than solving a Dynamic Programming problem. At least in DP, there's an optimal solution. But with hair? One wrong snip and you're in damage control for months.

This project brings logic to the chaos, using real facial metrics and trained models to offer data-driven hairstyle suggestions tailored just for you. No more endless Pinterest scrolling or haircut regrets—just science-backed style choices.

---

## 📸 Demo

> *(Make sure to place your images in the `assets/` folder)*

### Face Shape Detection  
![Face Detection Demo](assets/face_detection_demo.png)

### Hairstyle Suggestions  
![Hairstyle Suggestion Example](assets/hairstyle_suggestion_example.png)

---

## ✨ Features

- 🧠 Facial metric analysis using trained models
- 🔍 Face shape classification (Oval, Round, Square, Heart, etc.)
- 💇 Hairstyle suggestions based on face geometry
- 📷 Upload image or use webcam for live analysis
- 💻 Simple and responsive interface

---

## 🧠 How It Works

1. User uploads a photo or uses the webcam.
2. The system detects key facial landmarks using a trained model (Dlib/Mediapipe).
3. Based on geometric proportions (forehead width, cheekbones, jawline), the face shape is classified.
4. Relevant hairstyle suggestions are presented according to the face shape.

---

## 🧰 Tech Stack

- **Python** for backend processing
- **OpenCV**, **Dlib**, or **Mediapipe** for face detection and landmark prediction
- **Flask** (or FastAPI) as the backend framework
- **HTML/CSS/JavaScript** for frontend interface
- *(Optional)* React.js for enhanced frontend experience

---

## 📁 Project Structure

