ResumeCraft AI 📄🔍

This Smart Application Tracking System (ATS) evaluates resumes against a given job description using Generative AI and fallback logic. It provides match percentages, keyword analysis, profile summaries, and personalized suggestions — all wrapped in an interactive Streamlit web app.
🚀 Features

    ✨ Streamlit Interface: Intuitive web app for seamless interaction.
    🧠 Gemini AI Integration: Uses Google's Generative AI to evaluate resumes based on the job description.
    📄 Multi-Resume PDF Support: Upload multiple PDF resumes at once.
    🎯 Realistic ATS Matching: Scores resumes strictly based on relevant skills, experience, and technologies.
    🔁 Fallback Matching: In case of AI failures, falls back to basic similarity scoring.
    ☁️ Word Cloud: Visualizes common missing keywords.
    🔍 Detailed Analysis: Profile summaries, suggestions, and keyword gaps per resume.
    �� Match % Filter: Easily filter and download high-matching resumes.

🛠 Setup

    Install Dependencies

Make sure Python is installed, then install the required libraries:

pip install -r requirements.txt

Ensure your requirements.txt includes:

streamlit
PyPDF2==3.0.1
google.generativeai
python-dotenv
streamlit_extras
matplotlib
wordcloud
pandas

    Set up Google API Key

Create a .env file or configure Streamlit Secrets with your Google API key:

GOOGLE_API_KEY=your_google_api_key

Or set it in .streamlit/secrets.toml like:

API_KEY = "your_google_api_key"

    Run the Application

streamlit run app.py

🧪 Usage

    Paste your Job Description in the text area.
    Upload one or more PDF resumes.
    Click Submit to evaluate.
    View:
        Ranked resume list with match % and source
        Detailed profile summaries, missing keywords, and suggestions
        Word cloud of most common missing keywords
        Match % distribution chart
    Use the Match % Filter to narrow results and export them as CSV.

🤝 Contributing

We welcome contributions! To get started:

    Fork this repository
    Create a feature branch
    Commit your changes
    Open a pull request

📬 Contact

Maintainer: Soumya Chandrakar
Email: soumyachandrakar2024@gmail.com
📄 License
This project is licensed under the MIT License.
