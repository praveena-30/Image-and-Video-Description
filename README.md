# Image-and-Video-Description
A Python-based application that generates accurate descriptions for images and videos. It extracts key frames from videos, applies vision-language models for captioning, and presents results through a user-friendly GUI. Useful for content analysis, accessibility, and media summarization.
# 🖼️ Image and Video Description Generator

This project is a Python-based tool that automatically generates meaningful descriptions for uploaded **images** and **videos**. It includes a simple **GUI interface** for easy interaction and uses advanced image/video processing to extract and analyze content.

---

## 🔍 Features

- 📷 Upload **images** and get instant descriptive captions.
- 🎞️ Upload **videos**, extract key frames, and generate contextual descriptions.
- 🧠 Uses intelligent frame sampling to capture the most relevant moments.
- 🖥️ Built with a user-friendly **Graphical User Interface (GUI)**.
- 💬 Helps visually understand multimedia content via auto-generated text.

---

## 🛠️ Technologies Used

- **Python**
- **OpenCV** – for frame extraction and video handling
- **Tkinter** – for GUI development
- **PIL (Pillow)** – for image manipulation
- **Pre-trained Vision-Language Models** (e.g., BLIP, Qwen-VL, or similar)

---

## 🚀 How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/praveena-30/image-video-description.git
    cd image-video-description
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the application:
    ```bash
    python app.py
    ```

---

## 📸 Sample Output

- **Image**:
    > "A group of people standing on a beach during sunset."

- **Video**:
    > "A person is walking a dog in a park. Children are playing in the background."

---

## 📁 Project Structure

