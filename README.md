# SeeFood 🍔📱  
A beginner-friendly iOS app that uses CoreML and Vision to identify food from photos taken with your camera. Inspired by the "Not Hotdog" app from HBO's *Silicon Valley*.

![IMG_0076](https://github.com/user-attachments/assets/6decbd73-ce1f-4fa4-b4f3-2ca24992c367)
![IMG_0077](https://github.com/user-attachments/assets/2b337f65-6ace-4a95-bedb-3f05ecea3950)


## 📚 What You'll Learn
This project is designed as a learning tool to help you understand how to:

- Use CoreML to integrate a machine learning model into an iOS app
- Use Vision to process and classify images
- Capture and handle photos using the iOS Camera
- Work with UIImagePickerController
- Customize the navigation bar and UI elements programmatically

## 🔍 How It Works
1. The app uses the camera (or photo library) to capture an image.
2. It converts the image to CIImage and feeds it into a CoreML model (Inceptionv3).
3. Using the Vision framework, it classifies the image.
4. If the top result contains "hotdog", it sets the navigation bar title to "Hotdog!" (green bar). Otherwise, it says "Not Hotdog!" (red bar).

## 🛠 Tech Stack
- Swift
- UIKit
- CoreML
- Vision
- Inceptionv3.mlmodel (Image Classification)

## 🚀 Getting Started

1. Clone the repository:
   git clone https://github.com/jscheth/SeeFood-CoreML-iOS-App.git

2. Open the .xcodeproj in Xcode.
3. Make sure you're running on a real device (camera required).
4. Build & run!

## 📦 Model Used
- Inceptionv3 – A powerful image classification model provided by Apple.

## 🧠 Future Ideas
- Use a custom-trained CoreML model for specific food categories
- Display top 3 prediction labels with confidence
- Support other camera features (zoom, flash, etc.)

## 📄 License
MIT License
