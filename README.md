# 🎨 Image Style Transfer  
**Transform ordinary images into stunning artwork using deep learning!**  

---

## 📚 Table of Contents  
- [Introduction](#introduction)  
- [Libraries](#libraries)  
- [Functions](#functions)  
  - [Load Image](#load-image)  
  - [Visualize Image](#visualize-image)  
- [Original and Style Images](#original-and-style-images)  
- [Stylize Image](#stylize-image)  
- [Export the Stylized Image](#export-the-stylized-image)  

---

## 🌟 Introduction  
This project leverages **Intel's OneAPI DevCloud** platform for optimized execution and faster results. We utilize **OneAPI’s OneDNN toolkit** for deep neural network computations, enabling efficient and high-performance image transformation.  

**Goal:** Apply the artistic style of one image onto another using deep learning! 🎭✨  

---

## 🛆 Libraries  
Before diving into the code, ensure you have the following libraries installed:  
```bash
pip install matplotlib numpy tensorflow tensorflow-hub pillow
```
**Required Libraries:**  
🔹 **Matplotlib** – Visualizing the results  
🔹 **NumPy** – Handling numerical operations  
🔹 **TensorFlow** – Deep learning framework  
🔹 **TensorFlow Hub** – Pre-trained models  
🔹 **PIL (Pillow)** – Image processing  

---

## 🔧 Functions  

### 📥 Load Image  
This function decodes images into three separate channels and processes them for optimal performance:  
✅ **Decodes image pixels**  
✅ **Crops the center of the image**  
✅ **Resizes the image to match content & style images**  

---

### 🎨 Visualize Image  
This function helps in **displaying images in a grid format**, making it easy to compare before & after results.  

---

## 🖌️ Original and Style Images  
This step is simple! Select two images—**one for content** and **one for style**—and import them into your code.  

We’ll use our **load_image()** function from earlier to process these images before applying the style transfer.  

---

## 🎨 Stylize Image  
The core of this project! We utilize **TensorFlow Hub’s Arbitrary Image Stylization model** to transfer styles between images.  

🛠 **Loading the Model:**  
You can load the model in two ways:  
1️⃣ **Directly from TensorFlow Hub**  
2️⃣ **Download & use it locally** (Recommended for faster execution)  

🔗 **[Download the model here](https://tfhub.dev/google/magenta/arbitrary-image-stylization-v1-256/2)**  
_(The folder has been renamed to `tf_model` for clarity.)_  

---

## 🎨 Export the Stylized Image  
We’re almost done! Now, we visualize the final result:  

✅ **Show before & after comparisons**  
✅ **Save the stylized output**  
✅ **Admire your AI-powered artwork!** 🎨  

---

## 🚀 Final Thoughts  
This project showcases the power of **Deep Learning & Computer Vision** in generating AI-powered art. 🖌️✨  

🔗 **Check out more projects:** [GitHub](https://github.com/Rohand19)  

📩 **Questions? Feel free to connect!** 🚀  

---
