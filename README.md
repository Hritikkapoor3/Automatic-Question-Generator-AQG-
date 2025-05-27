# Automatic-Question-Generator-AQG-
Automatic Question Generator (AQG)
An AI-powered system that intelligently generates questions from PDFs and images, supporting both English and Hindi languages. The application features a React frontend and a Flask backend, integrating advanced OCR, language models, and image processing to produce context-aware Q&A pairs.

🧠 Features:
1. Multilingual Text Extraction:
   -English text extraction using PyMuPDF.
   -Hindi text extraction via Tesseract OCR.
   
2. Image Processing:
   -Extraction of images from documents.
   -Generation of image descriptions using the Gemini API.

3. AI-Driven Question Generation:
   -Utilizes leading language models (Gemini, Claude, GPT) to create context-aware question-answer pairs from combined textual and visual content.

4. Data Parsing and Storage:
   -Applies regex-based parsing to convert responses into LaTeX and JSON formats.
   -Stores structured data in MongoDB collections.

5. Interactive Frontend:
   -Real-time rendering and interaction through a React-based interface.
   -Custom Flask endpoint for HTTP request simulation using selected questions.


🛠️ Tech Stack:

  1.Frontend: React.js
  2. Backend: Flask (Python)
  3. OCR Tools: PyMuPDF (English), Tesseract OCR (Hindi)
  4. AI Models: Gemini, Claude, GPT
  5. Image Description: Gemini API
  6. Database: MongoDB
