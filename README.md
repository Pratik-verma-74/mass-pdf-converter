# 🚀 Mass Converter – Smart File Studio

A fully frontend, advanced file conversion and document management web app with an integrated **Mass AI Chatbot**. Built using pure HTML, CSS, and JavaScript — no backend, no APIs.

---

## 📌 Overview

Mass Converter is designed to simplify document preparation for exams like **NIMCET** and **CUET**, while also providing powerful tools for:

* File upload & management
* Image compression & resizing
* Format conversion (JPG / PNG / PDF)
* ZIP folder download with structure
* AI-based guidance (Mass AI chatbot)

---

## ⚙️ Features

### 🗂️ 1. File Management

* Drag & drop upload or manual selection
* Multiple file upload support
* Live preview (image thumbnails + file icons)
* Remove files individually
* Rename files before conversion
* Drag-to-reorder file cards
* Per-file format selection

---

### ⚙️ 2. Resize & Compress

* Adjustable size limit (KB / MB)
* JPEG quality slider
* Canvas-based image compression
* Maintains acceptable visual quality
* Manual override of size constraints

---

### 🔄 3. Format Conversion

* Convert files into:

  * JPG
  * PNG
  * PDF (using **pdf-lib**)
* PDF output formatted in A4 layout
* Works fully in-browser

---

### 📦 4. ZIP Download

* All files downloaded in a **single ZIP**
* Auto-organized folder structure:

```
01_Personal_Identity/
02_Educational/
03_Photo_Signature/
04_Other/
```

* Progress bar during ZIP generation
* Includes `README.txt` inside ZIP for extra documents

---

### 🤖 5. Mass AI Chatbot

* Greets users automatically
* Helps with:

  * File upload
  * Compression
  * Conversion
  * Download process

#### 📄 Suggested Documents

**Personal Identity & Address Proof**

* Aadhaar / Voter ID / Passport → 100 KB – 500 KB
* Domicile Certificate → 100 KB – 500 KB

**Educational Documents**

* 10th / 12th / Graduation → 200 KB – 1 MB
* Caste Certificate → 100 KB – 500 KB

**Photo & Signature**

* Passport Photo → 50 KB – 200 KB
* Signature → 50 KB – 200 KB

**Other Documents**

* Income / Disability → 100 KB – 500 KB

* Quick reply buttons for instant help

* Smart responses for common queries

---

### 🎨 6. UI/UX Design

* Glassmorphism (blur + transparency)
* Animated gradient mesh background
* Fully responsive (mobile / tablet / desktop)
* Smooth animations and transitions
* Toast notifications for actions
* Status indicators (idle / processing / done / error)

---

## 📚 Libraries Used

| Library       | Purpose           |
| ------------- | ----------------- |
| pdf-lib       | PDF generation    |
| Compressor.js | Image compression |
| JSZip         | ZIP creation      |
| FileSaver.js  | File download     |

---

## 🧠 How It Works

1. Upload files
2. Adjust size & format settings
3. Convert files in-browser
4. Download individually or as ZIP

All processing happens **client-side** — no data leaves your device.

---

## ⚠️ Limitations

* PDF conversion supports **images only**
* Large files may take time (browser dependent)
* No backend storage (files lost on refresh)

---

## 🔧 Customization

You can easily modify:

* Chatbot responses (JS section)
* File size limits
* UI themes (CSS variables)
* Folder structure in ZIP

---

## 💡 Future Enhancements

* Drag-and-drop sorting via SortableJS
* Advanced AI chatbot (LLM integration)
* Multi-page PDF support
* OCR text extraction

---

## 👨‍💻 Usage

1. Open `mass-converter.html` in browser
2. Upload files
3. Adjust settings
4. Convert
5. Download

---

## 📌 Final Note

This tool is designed for **students and applicants** who need:

* Quick document preparation
* Accurate file sizing
* Hassle-free uploads

---

✨ Built for efficiency, accuracy, and zero backend dependency.
