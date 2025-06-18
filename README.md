# 🚁 Vision Transformer-based Drone Detector

A custom object detection project using **Conditional DETR (DEtection TRansformer)** to detect flying drones from aerial video frames. This implementation fine-tunes Microsoft's [conditional-detr-resnet-50](https://huggingface.co/microsoft/conditional-detr-resnet-50) on a custom YOLO-style drone dataset.

---

## 🔍 Overview

- **Backbone**: ResNet-50 + Transformer Encoder-Decoder
- **Model**: `microsoft/conditional-detr-resnet-50` from Hugging Face
- **Dataset**: Custom drone footage with YOLO-format labels
- **Task**: Object detection (bounding boxes) from aerial views
- **Final test loss**: `0.7161` after 50 epochs

---

## Project Structure

```bash
vision-transformer-drone-detector/
├── detr-based-object-detection.ipynb  # Complete training notebook
├── README.md
└── requirements.txt                # Optional


