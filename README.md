# Multilingual-Speech-Vector-Similarity-using-ONNX

# Multilingual Speech Embedding using ONNX

This repository demonstrates how to convert a **multilingual sentence-transformer model** into the **ONNX format** for efficient inference and deployment in **resource-constrained environments** like mobile or edge devices.

We perform **text-to-vector encoding** for similarity search and matching tasks using the lightweight model:  
`sentence-transformers/distiluse-base-multilingual-cased-v1`.

> 🔥 Ideal for speech/chatbot vectorization, voice-to-intent matching, and multilingual embeddings in real-time apps.

---

## 🚀 Project Overview

✅ Convert HuggingFace Transformer model → ONNX  
✅ Supports dynamic batch sizes and multilingual inputs  
✅ Use `ONNX Runtime` for fast vector generation  
✅ Export embeddings to vector DBs (e.g., FAISS, Qdrant)  
✅ Plug-and-play ONNX model for mobile and cloud deployment  

---

## 🧠 Use Case

This project was created for a **freelance assignment on Kolabtree** to generate **multilingual sentence embeddings** and perform **similarity matching** using ONNX. The primary requirement was to reduce inference latency for deployment in lightweight applications (e.g., mobile assistants or voice-based interfaces).

---

## 🧰 Requirements

Install dependencies:

```bash
pip install torch transformers onnx onnxruntime
