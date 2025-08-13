# Hugging Face Intro Tutorial

This repository contains a beginner-friendly Google Colab notebook demonstrating how to use [Hugging Face Transformers](https://huggingface.co/transformers/) pipelines for **text, image, and audio** tasks.

## 📌 What you'll learn
- How to set up and log in to Hugging Face in Colab
- Running **text generation** with GPT-2
- Performing **sentiment analysis** with DistilBERT
- Classifying **images** with Vision Transformer (ViT)
- Converting **speech to text** with OpenAI Whisper

## 🚀 Getting Started
1. Open the notebook in Google Colab.
2. Install dependencies with `pip install`.
3. Log in to Hugging Face using your access token.
4. Run the cells step-by-step.

## 📂 File
- `huggingface_basics.ipynb` — Main tutorial notebook.

## 🛠 Requirements
- Python 3
- Hugging Face account + access token
- Internet connection (for downloading models from Hugging Face Hub)

## 📷 Demo Tasks
| Task | Model Used | Pipeline |
|------|------------|----------|
| Text Generation | `distilgpt2` | `text-generation` |
| Sentiment Analysis | `distilbert-base-uncased-finetuned-sst-2-english` | `sentiment-analysis` |
| Image Classification | `google/vit-base-patch16-224` | `image-classification` |
| Speech-to-Text | `openai/whisper-tiny` | `automatic-speech-recognition` |

---

**Author**: Shirish Baral
**License**: MIT
