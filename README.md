# AI Resume Analyzer & Job Matcher 📄🚀

A premium, ATS-inspired resume screening and optimization platform. This tool analyzes your resume against a job description to provide deep insights into technical skills, soft skills, experience, and education alignment.

## ✨ Features

- **Match Scoring**: Get an overall match percentage calculated using TF-IDF and Cosine Similarity.
- **Deep Breakdown**:
  - **Technical Skills**: Automated extraction and comparison of industry-standard tech stacks.
  - **Soft Skills**: Evaluation of leadership, communication, and analytical traits.
  - **Experience & Education**: Intelligent keyword matching for professional and academic background.
- **Visual Analytics**: Interactive progress bars and matching rings for a premium dashboard experience.
- **AI-Powered Suggestions**: Actionable feedback to improve your resume's selection chances.
- **Missing Keyword Highlighting**: Identify exactly what's missing from your resume based on the job requirements.
- **Glassmorphism UI**: A modern, responsive, and aesthetically pleasing interface built with Streamlit and Custom CSS.

## 🛠️ Technology Stack

- **Frontend**: Streamlit
- **Logic & NLP**: Python, Scikit-learn (TF-IDF, Cosine Similarity)
- **Data Handling**: Regex, NLTK-style keyword extraction
- **Styling**: Custom CSS (Modern UI/UX, Glassmorphism)

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- pip

### Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd "lokesh AI"
   ```

2. Install dependencies:
   ```bash
   pip install streamlit scikit-learn
   ```

### Running the App
```bash
streamlit run app.py
```

## 📂 Project Structure

- `app.py`: The main entry point containing the Streamlit UI and custom styling.
- `main.py`: The core logic for NLP-based resume analysis and scoring.
- `resume.txt`: Sample resume file for testing.
- `job.txt`: Sample job description file for testing.

## 🔮 Future Enhancements
- [ ] Integration with OpenRouter/OpenAI for advanced resume rewriting.
- [ ] PDF and Image (OCR) support for resume uploads.
- [ ] Automated interview question generation based on gaps.
- [ ] Learning roadmap suggestions for missing technologies.

---
Built with ❤️ for better career opportunities.
