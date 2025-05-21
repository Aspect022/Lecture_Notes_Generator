# 📚 AI-Powered Automated Lecture Notes Generator

This is a Python-based AI mini-project that converts lecture materials from various formats into neat, summarized bullet-point notes using extractive text summarization.

---

## 📌 Features

✅ Paste your lecture content directly  
✅ Load from a `.txt` file  
✅ Load from a `.pdf` file  
✅ Load from a `.pptx` presentation  
✅ Convert handwritten notes (images) to text using OCR  

---

## 🚀 How It Works

- Uses **LSA (Latent Semantic Analysis)** based extractive summarization via the `sumy` library.
- Allows users to pick the number of sentences they want in their summarized notes.
- Displays clean, bullet-point lecture notes.

---

## 🛠️ Tech Stack

- Python 3.x  
- `sumy` (Text summarization)  
- `nltk` (Tokenization)  
- `PyPDF2` (PDF text extraction)  
- `python-pptx` (PPTX text extraction)  
- `pytesseract` + `Pillow` (OCR for handwritten images)

---

## 📥 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/lecture-notes-generator.git
   cd lecture-notes-generator


2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Install **Tesseract OCR**:

   * 📥 [Download for Windows](https://github.com/tesseract-ocr/tesseract/wiki)
   * macOS: `brew install tesseract`
   * Linux: `sudo apt install tesseract-ocr`

4. Download NLTK data:

   ```python
   import nltk
   nltk.download("punkt")
   nltk.download("punkt_tab")
   ```

---

## 📊 How to Run

1. Open the `main.ipynb` Jupyter notebook.
2. Run all setup cells.
3. Execute the final `main()` cell to start the interactive menu.
4. Choose your preferred input type, summarize your notes, and get bullet points instantly!

---

## 📑 Future Improvements

* Streamlit GUI for drag-and-drop files.
* Add support for DOCX files.
* Option to export notes to `.txt` or `.pdf`.
* Abstractive summarization via transformers (like T5, BART).

---

## 👨‍💻 Made By

**Jayesh RL** ✨

---

## 📄 License

This project is licensed under the MIT License.

---
Made with 💖 and python.
