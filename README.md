# Multimodal Image Retrieval System

Multimodal Image Retrieval System | Python | PyTorch | CLIP | BLIP | Streamlit

---

## Overview
This project implements a multimodal system that aligns images and text in a shared embedding space. It enables cross-modal search (text-to-image and image-to-image) and generates natural language descriptions for better interpretability.

---

## 🚀 Features
- Text-to-image search  
- Image-to-image retrieval  
- Image captioning (BLIP)  
- Explanation module for retrieved results  

---

## Models
- CLIP — joint image-text embeddings  
- BLIP — image captioning  

---

## How it works
1. Images and text are encoded into a shared embedding space using CLIP  
2. Similarity between embeddings is computed (cosine similarity)  
3. Top-K relevant images are retrieved  
4. BLIP generates captions for selected images  
5. Explanation module highlights why results were selected  

---

## Dataset
- Flickr8k / Flickr30k / MS COCO (or custom dataset)

---

## Tech Stack
- Python  
- PyTorch  
- OpenAI CLIP  
- BLIP / BLIP-2  
- Streamlit  
- FAISS (optional)  

---

## ▶️ Installation

```bash
git clone https://github.com/your-username/multimodal-image-search.git
cd multimodal-image-search
pip install -r requirements.txt
