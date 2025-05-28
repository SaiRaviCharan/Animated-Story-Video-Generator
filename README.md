# Animated-Story-Video-Generator
# 🎬 AI-Powered Multimedia Story Generator

A creative AI project that generates full multimedia stories using text prompts — combining language, image, audio, and video generation through Google's powerful Generative AI APIs.

---

## 📺 Demo

🎥 [Watch the full demo video on LinkedIn](https://www.linkedin.com/posts/sai-ravi-charan-neerumalla-b04740278_generativeai-geminiai-googlecloudconsole-activity-7329141148290052097-YtL0?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEO9njQB7CuXSy1YHVq1b3-RgrRro9m38pk)


## 🚀 Features

- ✍️ **Story Generation** using Gemini Flash (Generative Language API)
- 🖼️ **Image Generation** using Google Imagen API
- 🔊 **Audio Narration** from AI-generated stories
- 🎞️ **Video Composition** using `movie.py`
- 🌐 Powered and orchestrated via **Google Cloud Console**
- 💡 Built using Google AI Studio and Gemini API (Live)

---

## 🧠 Technologies Used

- [Google AI Studio](https://makersuite.google.com/) – for prompt development & API testing  
- [Gemini Flash API](https://ai.google.dev/) – to generate intelligent, fast responses  
- [Google Imagen API](https://cloud.google.com/imagine) – for high-quality image creation  
- [movie.py](https://zulko.github.io/moviepy/) – to stitch media into cohesive video files  
- Python for backend orchestration  
- Google Cloud Console for API management and billing

---

## 📦 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/SaiRaviCharan/Gemini-Story-Generator-AI.git
cd Gemini-Story-Generator-AI


# 🚀 Gemini Story Generator AI

## 🛠️ Setup Instructions

### 1. Create a Virtual Environment

```bash
python -m venv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate
2. Install Dependencies
pip install -r requirements.txt

3. Add Your API Keys
Create a .env file in the root directory and add the following:
GEMINI_API_KEY=your_gemini_api_key
IMAGEN_API_KEY=your_imagen_api_key
The script will:

📜 Take a prompt (or use a default one)

🧠 Generate a story using the Gemini API

🖼️ Create corresponding images with Imagen

🔊 Synthesize voice audio

🎬 Combine everything into a video using movie.py

📜 License
This project is open-source under the MIT Licens
