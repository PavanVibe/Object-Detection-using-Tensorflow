# 🐾 Animal Face Detection with TensorFlow

This is a real-time animal face detection project built using TensorFlow and OpenCV. The goal was to detect animal faces—like cats, dogs, or other species—from either a webcam or static image using a deep learning model. I used SSD MobileNet (pre-trained on COCO) and fine-tuned it on a custom dataset of animal faces.

The model achieves around **85% accuracy** and works smoothly with real-time input.

---

## 📌 Why I Built This

I wanted to take object detection a step further and explore a niche use case—**animal face detection**. Most tutorials cover human faces or generic objects, so I trained this on animal faces to experiment with transfer learning and fine-tuning for specific targets. It's a great intro to real-world AI problems like wildlife monitoring or intelligent pet tracking.

---

## 🔧 How It Works

- Loads a pre-trained **SSD MobileNet v2** model
- Fine-tuned on custom annotated animal face images
- Uses OpenCV to capture frames from webcam
- Applies bounding boxes + confidence scores to detected faces

---

## 🚀 What You’ll Need

- Python 3.x
- TensorFlow
- OpenCV
- NumPy
- Matplotlib (optional for plotting)

### 📥 Installation

```bash
pip install tensorflow opencv-python numpy matplotlib
