# YOLOv11-Based Employee Activity Classifier

A Streamlit web application using a custom-trained YOLOv11 model (`best_path.pt`) to classify employee states as **"working"** or **"not working"** from uploaded images and videos. This project leverages computer vision to support real-time monitoring of workplace activity and well-being.

## 📌 Project Objective

Maintaining employee satisfaction and productivity is essential to organizational success. Traditional monitoring methods often lack real-time responsiveness. This system introduces an AI-powered approach to detect anomalies in employee behavior, enabling proactive support and creating a more responsive and employee-centric work environment.

## 🚀 Features

- 🔍 Real-time classification of uploaded images and videos  
- 📷 Detects "working" vs. "not working" states based on activity and facial expression  
- 🖥️ Simple, interactive Streamlit interface  
- 🧠 Powered by a custom YOLOv11 model (`best_path.pt`)

## 📁 File Structure

```
your\_project/
├── app.py              # Streamlit app
├── best\_path.pt        # Trained YOLOv11 model
└── README.md           # Project documentation

````

## 📷 Usage

* Upload an image or video file via the Streamlit interface.
* The model will process the file and display predictions.
* Results are visualized with annotated bounding boxes and labels.

## 🧠 Model

The model is a custom YOLOv11 object detector trained to distinguish between working and non-working states based on employee posture, gestures, and facial cues.

## 🛡️ License

This project is licensed under the MIT License.

---

**Author:** Jann Moises Nyll B. De los Reyes
**Contact:** \[[qjmnbdelosreyes@tip.edu.ph](qjmnbdelosreyes@tip.edu.ph)]

```

---

Let me know if you'd like to include a demo GIF or deploy it on Streamlit Cloud and link it here.
```
