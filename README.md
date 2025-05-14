# AI Project 2: AI Resume Critiquer

This project is an AI-powered resume critiquing tool built with Python and Streamlit. Users can upload their resume (PDF or TXT), specify a target job role, and receive tailored feedback and suggestions from an AI assistant powered by OpenAI's language models.

## Features

- **Resume Upload:** Supports PDF and TXT file uploads.
- **Job Role Targeting:** Optionally specify the job role you are applying for to get more relevant feedback.
- **AI-Powered Feedback:** Uses OpenAI's GPT models to analyze and critique your resume.
- **Simple Web Interface:** Built with Streamlit for easy interaction.

## Tools & Libraries Used

- [Streamlit](https://streamlit.io/): For building the interactive web app.
- [OpenAI API](https://platform.openai.com/): For generating resume critiques and suggestions.
- [PyPDF2](https://pypi.org/project/PyPDF2/): For extracting text from PDF files.
- [python-dotenv](https://pypi.org/project/python-dotenv/): For managing environment variables and API keys.

## Setup Instructions

1. **Clone the repository** and navigate to the project folder.
2. **Install dependencies** (using [uv](https://github.com/astral-sh/uv) or pip):
   ```
   uv pip install -r requirements.txt
   ```
   or
   ```
   pip install -r requirements.txt
   ```
3. **Set up your OpenAI API key:**
   - Create a `.env` file in the project directory.
   - Add your API key:
     ```
     OPENAI_API_KEY=your-openai-api-key
     ```

4. **Run the project:**
   ```
   streamlit run main.py
   ```

## How It Works

- The user uploads a resume file and optionally enters a target job role.
- The app extracts the text from the uploaded file.
- The extracted text and job role are sent to the OpenAI API for analysis.
- The AI provides feedback and suggestions to improve the resume.

## Example Usage

1. Open the app in your browser.
2. Upload your resume (PDF or TXT).
3. Enter the job role you are targeting (optional).
4. Click "Analyze Resume" to receive AI-powered feedback.

## Credits

- Built with [Streamlit](https://streamlit.io/) and [OpenAI](https://platform.openai.com/).
- Inspired by the need for accessible, AI-driven career tools.

---
Feel free to modify and extend this project for your own use!