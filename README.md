# 🖼️ Image Resizer & Compressor (JavaScript)

This is a simple web-based tool that allows users to **resize** and **compress** images directly in the browser using HTML, CSS, and JavaScript.

## ✨ Features

- Upload images (JPG, PNG, etc.)
- Automatically detects original width and height
- Set custom width and height
- Lock or unlock aspect ratio
- Optional image quality compression
- Download the resized and compressed image

## 🚀 How It Works

1. Click the upload area and choose an image file.
2. Adjust the width and/or height as desired.
3. Use the “Lock aspect ratio” checkbox to maintain proportions.
4. Use the “Reduce quality” checkbox to compress the image (50% quality).
5. Click the **Download Image** button to save the result.

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)
- `<canvas>` API for image resizing & compression

## 📁 Project Files

📦 image-resizer-compressor
├── ht.html # Main HTML page
├── style.css # Styling for layout and UI
├── script.js # Logic for resizing and compressing the image
└── README.md # Project description and instructions
## 🧠 How Compression Works

The image is rendered on a hidden canvas with:
- New width and height set by the user
- Optional quality setting (e.g. 0.5 for 50% quality)
- Final image is converted to a base64 string via `canvas.toDataURL()`
- Download is triggered via an anchor (`<a>`) element

## ✅ Getting Started

1. Download or clone the repository.
2. Open `ht.html` in your browser.
3. Use the interface to resize and compress your image.

No server or installation required — it runs entirely in the browser!
