AI-Powered VideoQA System
Overview

AI-Powered VideoQA System is an intelligent video understanding platform that enables users to upload videos, generate transcripts, ask questions about video content, and obtain AI-generated summaries.

The system combines speech recognition, computer vision, and large language models to understand both audio and visual information from videos.

Features
    Video Upload and Processing
    Automatic Speech-to-Text Transcription
    Visual Scene Understanding
    Video Summarization
    Question Answering on Video Content
    Relevant Clip Extraction
    Downloadable Transcripts
    FastAPI Backend
    Interactive Web Interface
Technologies Used
    Frontend
        HTML
        CSS
        JavaScript
    Backend
        Python
        FastAPI
    AI Models
        Whisper
        BLIP
        Mistral 7B
    Video Processing
        OpenCV
        MoviePy
Project Workflow
    User uploads a video
    Audio is converted into text using Whisper
    Key video frames are extracted
    BLIP generates image captions
    Transcript and captions are combined
    Mistral LLM answers user questions
    Summary and relevant clips are generated
Installation
git clone https://github.com/yourusername/AI-Powered-VideoQA-System.git

cd AI-Powered-VideoQA-System

pip install -r requirements.txt

python main.py
Future Enhancements
Multi-language support
Real-time video streaming
Speaker identification
Sentiment analysis
Advanced clip recommendations



---

## 📸 Project Screenshots

### 🏠 Home Page
![Home Page](screenshorts/Screenshot%202026-04-09%20193021.png)

### 🔗 Video Input — Paste YouTube URL
![Video Input URL](screenshorts/Screenshot%202026-04-09%20180644.png)

### 📁 Video Input — Direct File Upload
![Video Input Upload](screenshorts/Screenshot%202026-04-09%20180803.png)

### ⚡ Fast QA Mode — Asking a Question
![Fast QA Thinking](screenshorts/Screenshot%202026-04-09%20171213.png)

### ✅ Fast QA Mode — Answer Generated
![Fast QA Answer](screenshorts/Screenshot%202026-04-09%20180322.png)

### 🎬 QA + Clip Retrieval — Answer with Relevant Clip
![Clip Retrieval Answer](screenshorts/Screenshot%202026-04-09%20191244.png)

### 🎥 Clip Retrieval — Extracted Video Clip Playback
![Clip Playback](screenshorts/Screenshot%202026-04-09%20200839.png)

### 🌐 Multilingual Support — Language Selection
![Language Selection](screenshorts/Screenshot%202026-04-17%20161020.png)

### 🇮🇳 Multilingual Answer — Response in Telugu
![Telugu Answer](screenshorts/Screenshot%202026-04-17%20160850.png)
