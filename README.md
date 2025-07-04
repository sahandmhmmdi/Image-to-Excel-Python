
OCR image processing project using EasyOCR to extract numeric tables from images and export to Excel using Python and Pandas.

# 🧠 Image to Excel – OCR Table Extractor

This Python project allows you to extract numerical data from industrial measurement images using **EasyOCR**, clean and structure the data, and export it to an Excel file.

📸 Input: Scanned or captured images of measurement data  
📊 Output: Cleaned table in `.xlsx` format (plus skipped entries)  
🧰 Built with: Python, OpenCV, EasyOCR, Pandas

---

## 🚀 Features

- Preprocessing with CLAHE, denoising, and adaptive thresholding
- Intelligent filtering to remove headers and noise
- Supports both single files and folders
- Parallel processing with `ProcessPoolExecutor`
- Automatically saves skipped/error rows

---

## 📁 Folder Structure

```bash
📂 sample_input/         → Sample images for testing
📂 processed_files/      → Automatically moved images after processing
📂 sample_output/        → Output Excel files
📄 main.py               → Main OCR + export logic
📄 requirements.txt      → Install dependencies
