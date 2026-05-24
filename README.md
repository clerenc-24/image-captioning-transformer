# image-captioning-transformer
COCO Image Captioning using CNN Encoder and Transformer Decoder
# 🖼️ Image Captioning with Transformer

This project implements an image captioning model using:

- CNN Encoder (ResNet50)
- Transformer Decoder
- Attention visualization
- BLEU evaluation

## 📊 Dataset
MS COCO Captions 2017

## 🧠 Model Architecture
- Encoder: ResNet50 (fine-tuned)
- Decoder: Transformer (self-attention + cross-attention)

## ⚙️ Features
- Controllable caption generation (length-based)
- Cross-attention visualization
- BLEU-1 to BLEU-4 evaluation
- Comparison with BLIP pretrained model

## 🚀 How to Run

```bash
pip install -r requirements.txt
