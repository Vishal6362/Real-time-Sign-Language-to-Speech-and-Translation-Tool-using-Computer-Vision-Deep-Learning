<<<<<<< HEAD
# 🤟 SIGNSPEAK: Bridging Gestures, Speech, and Translation 🌐🗣️

![Python](https://img.shields.io/badge/Python-3.10-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Used-orange)
![MediaPipe](https://img.shields.io/badge/MediaPipe-Used-success)
![SpeechRecognition](https://img.shields.io/badge/SpeechRecognition-Enabled-green)
![Google Translate](https://img.shields.io/badge/Translation-Multilingual-informational)

> Translate hand gestures into spoken words in **any language** using AI, deep learning, and computer vision.

---

## 🚀 About the Project

**SIGNSPEAK** is an AI-powered system that:

* 📷 Detects hand gestures in real-time using your webcam
* 🤖 Classifies them using a trained deep learning model
* 🌐 Translates the recognized gesture to your chosen language
* 🗣️ Speaks the translated output using text-to-speech

It serves as an assistive tech for **speech-impaired individuals** or a demo combining computer vision, NLP, and TTS.

---

## 🎯 Key Features

* ✅ Real-time hand gesture recognition (MediaPipe + OpenCV)
* 🌍 Multilingual translation with `deep_translator`
* 🗣️ Offline text-to-speech (pyttsx3)
* 🧠 Custom-trained model for gesture recognition
* 🔍 CLI-based easy language selection

---

## 📚 Project Structure

```
SIGNSPEAK/
├── hand_gesture_translator.py     # Main script
├── gesture.names                  # Gesture class labels
├── mp_hand_gesture/               # Trained model folder
├── data.pickle                    # Training dataset (landmarks)
├── requirements.txt               # Dependencies
├── .gitignore                     # Ignore unnecessary files
└── README.md                      # Project documentation
```

---

## 📦 Installation

1. **Clone the Repository**

```bash
git clone https://github.com/rds-124/SIGNSPEAK.git
cd SIGNSPEAK
```

2. **Install Dependencies**

```bash
pip install -r requirements.txt
```

3. **Run the Application**

```bash
python hand_gesture_translator.py
```

---

## 🌐 Language Codes (for Translation)

| Language | Code |
| -------- | ---- |
| Spanish  | `es` |
| Hindi    | `hi` |
| Tamil    | `ta` |
| Kannada  | `kn` |
| German   | `de` |
| Japanese | `ja` |
| French   | `fr` |
| Telugu   | `te` |
| English  | `en` |

Find more codes [here](https://cloud.google.com/translate/docs/languages).

---

## 🧠 Model Details

* Built with MediaPipe for extracting hand landmark data
* Classifies gestures using a simple dense neural network
* Supports training on custom data (`data.pickle` file)

---

## 📈 Future Work

* 🎤 Voice-controlled language change
* 📲 Mobile deployment with TensorFlow Lite
* 🔧 GUI Interface with Tkinter or PyQt
* ⚡ Gesture dataset expansion with augmentation

---

## 🙏 Acknowledgements

* [MediaPipe](https://mediapipe.dev/) by Google
* [TensorFlow](https://www.tensorflow.org/)
* [deep\_translator](https://github.com/nidhaloff/deep-translator)
* [pyttsx3](https://pypi.org/project/pyttsx3/)

---

## 📅 License

This project is licensed under the **MIT License**.

---

## 📧 Contact

**Rohith D**
[LinkedIn](https://www.linkedin.com/in/rohith124) | [GitHub](https://github.com/rds-124)

> ⭐ If you found this useful, star the repo and share it!
=======
# Real-time-Sign-Language-to-Speech-and-Translation-Tool-using-Computer-Vision-Deep-Learning
>>>>>>> efa946b63a99a072000f299e34560d9481315ca4
