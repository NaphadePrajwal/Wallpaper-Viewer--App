# Wallpaper-Viewer-App

This is a simple Wallpaper Viewer App built with Python Tkinter and PIL (Pillow). It allows you to load and view wallpapers (or any images) from a folder one by one using a "Next" button.

## 📸 Features
- Loads all images from the wallpaper/ directory
- Resizes and displays them inside the GUI window
- Allows rotating through images using a single "Next" button
- Clean and minimal GUI design using Tkinter

## 📁 Folder Structure
project/
│
├── wallpaper/           # Folder containing your image files (e.g., JPG, PNG)
│   ├── image1.jpg
│   ├── image2.jpg
│   └── ...
├── wallpaper_viewer.py  # Main Python script
└── README.md

## 🔧 Prerequisites

Make sure the following are installed:
- Python 3.x
- Required Python modules: pip install pillow

## 🚀 Getting Started
-Run the App:- python wallpaper_viewer.py

## 📌 Notes
- Supported formats: JPG, PNG, BMP (any format supported by PIL)
- Images are automatically resized to fit 200x300 px
- If no images are present in the folder, the app will crash — make sure to add at least one image
