# 🧠 YOLOv5 Object Detection Web App

A web-based object detection application built with **YOLOv5** and **Gradio**. Upload any image and see objects like people, cars, and bottles detected in real time!

---

## 🚀 Demo

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/halaalhomie/YOLOv5-Object-Detector/blob/main/yolov5_detector.ipynb)

---

## 📦 Features

- ✅ Pretrained YOLOv5s model (80 COCO classes)
- ✅ Upload any image for instant detection
- ✅ Gradio-powered interface
- ✅ Runs in Colab (no local setup required)

---

## 🛠️ Tech Stack

- [YOLOv5 (Ultralytics)](https://github.com/ultralytics/yolov5)
- [Gradio](https://www.gradio.app/)
- PyTorch, Google Colab

---

## 📸 Sample Output

| Input | Output |
|-------|--------|
| ![](input.jpg) | ![](output.jpg) |

---

## 🧠 How It Works

```python
model = torch.hub.load('ultralytics/yolov5', 'yolov5s')
results = model(image)
results.render()
