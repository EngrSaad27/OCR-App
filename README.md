#  🔍  Optical Character Reader (OCR) Using GOT-OCR 2.0 Models

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/downloads/)
[![Gradio](https://img.shields.io/badge/Gradio-5.0%2B-FF4B4B.svg)](https://www.gradio.app/)
[![VSCode](https://img.shields.io/badge/VSCode%20-1.96-76B900.svg)](https://code.visualstudio.com/download)

<p align="center">
  <img src="App Results/App interface.png" alt="Project Banner" width="800"/>
</p>

## 💼 Credit

***Special thanks to [Haoran Wei](https://github.com/Ucas-HaoranWei) who built OCR model for us!***


## 🌟 Project Description
Optical Character Recognition (OCR) is a widely used technology designed to extract text characters from images and convert them into editable text formats. Beyond text extraction, OCR is also employed for element detection and region-specific cropping within images, making it a versatile tool for document processing and analysis.

Modern OCR systems are tailored to handle various specialized tasks, leveraging advancements in machine learning and computer vision. However, Large Vision Language Models (LVLMs) have historically lagged in OCR capabilities. Continuous innovations are now bridging this gap, significantly enhancing OCR performance.

The next-generation OCR 2.0 models come with key features that set them apart:

- End-to-End Architecture: Streamlines processes, reducing maintenance overhead.
- Cost Efficiency: Ensures low training and inference costs.
- Versatility: Adaptable to a wide range of applications, making it suitable for diverse use cases.

## 🎯 Features
- Accurately extract text from images
- Support for printed, handwritten, or stylized text
- Easy to used App

## App Results
### 1st Input Snapshot
<p align="center">
  <img src="App Results/input 1.JPG" alt="Project Banner" width="600"/>
</p>

### 1st Output Snapshot
<p align="center">
  <img src="App Results/output 1.JPG" alt="Project Banner" width="600"/>
</p



### 2nd Input Snapshot
<p align="center">
  <img src="App Results/input 2.JPG" alt="Project Banner" width="600"/>
</p>


### 2nd Output Snapshot
<p align="center">
  <img src="App Results/output 2.JPG" alt="Project Banner" width="600"/>
</p>


### 3rd Input Snapshot
<p align="center">
  <img src="App Results/input 4.1.JPG" alt="Project Banner" width="600"/>
</p>


### 3rd Output Snapshot
<p align="center">
  <img src="App Results/output 4.1.JPG" alt="Project Banner" width="600"/>
</p>

### 📄 Project Workflow

1. **Model Uploading**
   - Initialize tokenizer and model
  
2. **Folder Uploading**
   - Define upload folder
  
3. **Gradio Interface**
   - Function to handle OCR process
   - Perform OCR based on selected mode
   - Launch the app  

## 🚀 App Activation & Library installation

### Environment Setup

```bash
# Create virtual environment
python -m venv venv

# Activate environment
# For Windows
.\venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

## 💻 Application Launch
```bash
python app.py
```
 
## 🙏 Acknowledgments

- [GOT-OCR2.0](https://github.com/Ucas-HaoranWei/GOT-OCR2.0)
- Gradio Community
- Visual Studio Code

## 📞 Contact
Feel free to reach out: [Email](mailto:isaad1066@gmail.com) | [LinkedIn](https://www.linkedin.com/in/saadkhalid123/) 





