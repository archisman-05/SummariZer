# SummariZer

## Overview:
**SummariZer** is a desktop-based AI summarization tool built using Python and Tkinter. It allows users to input text or upload PDF documents and get concise, easy-to-understand summaries powered by **Google’s Gemini model**. The tool is designed for students, professionals, researchers, or anyone who wants to quickly grasp the essence of long content.

---

## Features:
1. Summarizes **user-entered text** with a single click.
2. Allows **PDF file uploads** and extracts text for summarization.
3. Uses **Google Gemini 1.5 Flash** and **2.0 Flash** AI models for high-quality results.
4. Summaries are returned in **simple, everyday language**.
5. Clean and responsive **GUI interface** using Tkinter.
6. Status bar and error handling for better user experience.
7. Warns and optionally trims long PDFs (over 1000 words) for optimal performance.

---

## Installation:

### Prerequisites:
Ensure you have the following installed:
1. Python 3.x
2. pip (Python package manager)
3. Google Generative AI SDK
4. PyPDF2

### Steps to Install:
1. Clone the repository
2. Install required dependencies
3. Get your Gemini API Key.

Visit:
1. https://makersuite.google.com/app/apikey
2. Replace "Your Gemini API Key" in the code with your actual key.

The App Processes:
1. Manual text input from users via GUI.
2. PDF upload and automatic text extraction.
3. Prompts Gemini AI with a tailored request to summarize the content.
4. Returns a brief, simplified summary suited for general understanding.

Output:
1. Textual summary displayed in a scrollable output box.
2. Easy-to-read language targeting middle-school comprehension.
3. Automatically clears previous outputs and updates status messages.
   
Technologies Used:
1. Python
2. Tkinter – for GUI development
3. Google Generative AI SDK – for Gemini-based summarization
4. PyPDF2 – for PDF parsing
   
Contribution:
Contributions are welcome! Follow these steps:

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Push to your branch and submit a pull request.

Contact: For any queries or support, reach out via email: archismankundu101@gmail.com
