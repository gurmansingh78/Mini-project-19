# 🖼️ Image to Text OCR using Tesseract & Pytesseract

This project performs Optical Character Recognition (OCR) on images using [Tesseract OCR](https://github.com/tesseract-ocr/tesseract) and the `pytesseract` Python wrapper in Google Colab. It allows you to upload an image, extract the text, and display it directly within a notebook.

---

## 📌 Features

- 🔍 Extracts readable text from images.
- 🧠 Uses Tesseract OCR via Python.
- 🖼️ Supports various image formats (PNG, JPEG, etc.).
- ☁️ Easily runs on Google Colab with no local setup required.
- 📤 Image upload support using Google Colab widgets.

---

## 📦 Requirements

- Python 3.x
- Google Colab
- Tesseract OCR
- `pytesseract` Python library
- `Pillow` for image processing

Install required packages:
```python
!sudo apt install tesseract-ocr
!pip install pytesseract
!pip install Pillow==9.0.0

