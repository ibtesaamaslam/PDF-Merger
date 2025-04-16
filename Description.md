
# 📚 PDF Merger App | Python GUI Tool

A simple and intuitive **PDF Merger application** built with **Python and Tkinter** that allows you to combine multiple PDF files into a single document.

> ⚡ Lightweight, fast, and beginner-friendly tool for students, professionals, and developers!

---

## 🧰 Tech Stack

| Technology     | Purpose                         |
|----------------|---------------------------------|
| Python         | Core programming language       |
| Tkinter        | GUI interface                   |
| PyPDF2         | PDF file manipulation           |
| os             | File handling                   |

---

## ✨ Features

✅ Select and merge multiple PDFs  
✅ Reorder PDFs before merging  
✅ Save the combined file anywhere on your system  
✅ Clean and minimal GUI using Tkinter  
✅ Error handling for corrupted or unreadable files

---

## 📂 Project Structure

```
.
├── PDF Merger.ipynb        # Main application (can be converted to .py)
├── README.md               # Project documentation
└── merged_pdfs/            # Output folder for saved files (optional)
```

---

## ⚙️ Installation

### 🐍 Requirements

Install necessary Python packages using pip:

```bash
pip install PyPDF2
```

Tkinter is usually built-in with Python, but if it’s missing:

```bash
sudo apt-get install python3-tk     # for Linux
# or
brew install python-tk              # for macOS
```

---

## 🚀 How to Run

### ▶️ Option 1: Run via Notebook

- Open `PDF Merger.ipynb` in **Jupyter Notebook** or **Google Colab**
- Run all the cells
- Use the interactive widgets to add and merge PDF files

### ▶️ Option 2: Convert to Script (Optional)

Convert the notebook into a Python script:

```bash
jupyter nbconvert --to script "PDF Merger.ipynb"
python PDF\ Merger.py
```

---

## 💡 How It Works

1. The app uses a **file dialog** to let you select multiple PDFs.
2. Selected files are displayed in the GUI (order matters).
3. Once files are ready, click **"Merge PDFs"** to combine them.
4. The merged file is saved to your desired location.

---

## ✅ Use Cases

- Combine scanned documents into a single file  
- Merge invoices, academic papers, or eBooks  
- Prepare official documentation quickly

---

## 🔒 Note on Privacy

Your files never leave your local machine. Everything is processed **locally**.

---

## 🚧 Future Improvements

- Drag-and-drop file support  
- Support for removing/reordering selected files  
- Preview of PDFs before merging  
- Merge password-protected PDFs

---

## 🤝 Contributing

Feel free to fork the repository and suggest improvements or bug fixes through pull requests!
