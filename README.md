# 🧠 GPT-Vision-Docs-LLM

An intelligent document-to-AI pipeline that extracts content from **PDFs, Word, PowerPoint, and images**, and processes it using **locally running Large Language Models (LLMs)** like TinyLLaMA, LLaMA 2 (GGUF), GPT-2, and more. Built for use in **Google Colab or local Python environments**, it's a perfect foundation for AI projects like **medical chatbots**, **document summarizers**, or **vision-based assistants**.

---

## 🚀 Features

- 📄 Supports multiple document formats: `.pdf`, `.docx`, `.pptx`
- 🖼️ Extracts text from images using OCR (Tesseract)
- 🤖 Works with Hugging Face models (TinyLLaMA, GPT-2) and GGUF-based local models (LLaMA, Mistral)
- 🧼 Includes a powerful noise-removal script for image preprocessing
- 💻 Ready-to-use in Google Colab with visual output
- 🩺 Perfect for medical chatbot projects like **MedGPT**

---

## 🧰 Tech Stack

| Component        | Tool/Library                |
|------------------|-----------------------------|
| LLMs             | `transformers`, `llama-cpp-python` |
| OCR/Image        | `pytesseract`, `OpenCV`, `Pillow` |
| PDF/Text Extract | `PyMuPDF`, `python-docx`, `python-pptx` |
| Vision Cleaning  | `cv2.fastNlMeansDenoisingColored` |
| IDE              | Google Colab / Jupyter Notebook |

---

## 📦 Setup Instructions (Colab Ready)

1. Install all dependencies:

```bash
pip install transformers accelerate bitsandbytes python-docx python-pptx pytesseract pillow pymupdf
apt install -y tesseract-ocr
