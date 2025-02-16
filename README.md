# 🖌️ Image Analysis 🖼️

🚀 This project provides various image processing techniques using **OpenCV** and **Python**, offering insights into image characteristics, transformations, and facial recognition.

---

## 📈 Overview
This system enables multiple image processing tasks, including:
- **Channel Analysis**: Extracting and analyzing RGB channel intensity.
- **Histogram Calculation**: Generating histograms to visualize image pixel distributions.
- **Filtering Techniques**: Applying blurring, sharpening, and edge-detection filters.
- **Contrast & Brightness Enhancement**: Adjusting image intensity for better visualization.
- **Face Detection**: Identifying faces in images using **Haar Cascade Classifier**.

---

## 🏠 Project Workflow 📌
1. **Channel Analysis** 🎨: Extract individual RGB channels and compute their mean values.
2. **Histogram Processing** 📊: Generate and analyze pixel intensity distributions.
3. **Filtering** 🔧: Apply convolution filters such as Gaussian, Median, and Sobel.
4. **Contrast & Brightness Adjustment** 🌟: Modify intensity levels for enhancement.
5. **Face Detection** 👤: Detect faces in images using OpenCV's Haar Cascade classifier.

---

## 📂 Project Structure 🛠️
```
📚 Image-Analysis/
├── 📂 image/                       # Folder containing input images
├── 📂 histogram_output/            # Histogram result images
├── 📂 filter_output/               # Filtered images
├── 📂 contrast_brightness_output/  # Enhanced images
├── 🌐 haarcascade_frontalface.xml  # Haar Cascade model for face detection
├── 📚 Image Analysis.ipynb         # Jupyter Notebook for processing
├── 📄 number_of_faces.TXT          # Log of detected faces per image
├── 📄 output_mean_green.TXT        # Log of mean green channel values per image
```

---

## ✨ Features
✅ **Extracts and analyzes individual RGB channels**  

✅ **Generates histograms for pixel distribution visualization**  

✅ **Applies various filtering techniques**  

✅ **Enhances contrast and brightness dynamically**  

✅ **Detects faces in images and logs results**  

---

## 🛠 Technologies & Libraries
🔹 **Python** 🐍 

🔹 **OpenCV** 👀 

🔹 **NumPy** 💪  

🔹 **Matplotlib** 🌈

---

## 🚀 Installation
Ensure you have Python installed, then install dependencies:
```sh
pip install opencv-python numpy matplotlib
```

---

## 🎥 Usage
Run the Jupyter Notebook to analyze images:
```sh
jupyter notebook "Image Analysis.ipynb"
```
To view detected faces:
```sh
cat number_of_faces.TXT
```
To analyze mean green values:
```sh
cat output_mean_green.TXT
```

---

## 📊 Results
- **Histogram visualizations** of pixel intensities.
- **Filtered images** with different convolution techniques.
- **Enhanced images** with optimized contrast and brightness.
- **Face detection logs** showing the number of detected faces per image.

---

## 🌟 Future Improvements
🌟 Implement **deep learning models** for improved face detection accuracy.  

🌟 Extend **colour space analysis** beyond RGB (e.g., HSV, LAB).  

🌟 Integrate **adaptive contrast enhancement techniques**.  

---

## 🌍 Contributing
Contributions are welcome! Follow these steps to contribute:
1. **Fork the repository** 🌾  
2. **Create a new branch** 🌱  
3. **Make your changes** ✨  
4. **Submit a pull request** 🛠

*If you find this project useful, please **star ⭐ the repository** and share it with others!*

---

> **This project helps unveil hidden image insights through advanced analysis and processing! 🚀🌟**
