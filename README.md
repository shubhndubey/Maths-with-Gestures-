# Maths-with-Gestures🎨🤖

## Overview

**GestureGlide** is an interactive AI-powered web application that allows users to **draw using hand gestures** detected through their webcam and receive **smart AI-generated answers** based on their drawings.

Built using **OpenCV**, **cvzone**, and **Streamlit**, and powered by **Google Gemini AI**, this project merges **computer vision**, **natural language processing**, and **gesture recognition** to deliver a fun, intuitive, and educational experience.

---

## 🔥 Features

- ✍️ **Hand Gesture Drawing**  
  Draw on a virtual canvas using your index finger — no mouse or touchscreen needed!

- 🧼 **Clear Canvas with Gesture**  
  Use a two-finger gesture (index + pinky) to instantly clear the drawing canvas.

- 🤖 **AI-Driven Answers**  
  Show four fingers to send the drawing to **Google Gemini AI** with a predefined prompt (e.g., “Solve me a math problem”).

- 📷 **Live Webcam Feed with Overlay**  
  View your live webcam feed and drawing in real-time within a clean Streamlit interface.

---

## 🧠 Technologies Used

- [OpenCV](https://opencv.org/) – Real-time video processing
- [cvzone](https://github.com/cvzone/cvzone) + [MediaPipe](https://google.github.io/mediapipe/) – Hand tracking
- [NumPy](https://numpy.org/) – Canvas manipulation
- [Pillow (PIL)](https://python-pillow.org/) – Image conversion
- [Google Generative AI (Gemini)](https://ai.google.dev/) – Content generation based on image + prompt
- [Streamlit](https://streamlit.io/) – Web app interface

---

## 📸 How It Works

1. **Start the app** — your webcam feed appears.
2. **Draw** with just your index finger up.
3. **Clear the screen** by holding up your index and pinky fingers.
4. **Trigger AI** by showing four fingers (thumb down).
5. The AI processes your drawing and displays a response in real time.

---

## 🤖 Gesture Commands

| Gesture | Action |
|--------|--------|
| ✋ Index finger up | Draw |
| 🤘 Index + Pinky up | Clear canvas |
| ✋ All fingers except thumb up | Send drawing to Gemini AI |

---

## 🚀 Getting Started

### 1. Clone the Repo

```bash
git clone https://github.com/your-username/GestureGlide.git
cd GestureGlide
