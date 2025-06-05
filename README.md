# 😄 Emotion Detection from Images using FER and MTCNN

This project detects human emotions from facial images using the fer library in Python, with face detection powered by **MTCNN**. The system can identify emotions such as **happy, sad, angry, surprise**, and more — directly from uploaded images in a Google Colab notebook.

## 🔍 What This Project Does

- Accepts an image upload
- Detects faces using **MTCNN**
- Predicts the most likely **emotion** per face
- Annotates the image with emotion labels and confidence scores
- Displays the final output with bounding boxes and text


## 📁 Project Files

- `emotion_detection.ipynb` – Main Colab notebook
- `README.md` – Project overview
- `requirements.txt` *(optional)* – Dependencies (can include `fer`, `opencv-python`, `matplotlib`)

## 🚀 How to Use (Colab)

1. Open the notebook in **Google Colab**
2. Install required libraries:
    ```python
    !pip install fer opencv-python matplotlib
    ```
3. Upload an image file when prompted
4. The model will:
   - Detect faces
   - Annotate detected faces with the top emotion and score
   - Display the final image

## 🧠 Tech Stack

- Python
- Google Colab
- FER library (with MTCNN)
- OpenCV
- Matplotlib

