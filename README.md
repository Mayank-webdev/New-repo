# CareerForge — AI Career & Resume Builder

A Python + Streamlit educational project starter.

## Download
Download `CareerForge_AI_Resume_Builder_COMPLETE.zip` from this repository using the **Code → Download ZIP** option, or open the ZIP file in the repository and choose Download.

## Included features
- Account signup and login (local SQLite)
- Resume builder with three templates and preview
- PDF export
- Keyword-based ATS coverage estimate
- Summary and bullet-writing helpers
- Role-based skill-gap checklist
- Save, view, and delete multiple resumes
- Optional OpenAI API integration for writing suggestions

## Run locally (Windows PowerShell)
```powershell
py -m venv .venv
.\.venv\Scripts\Activate.ps1
py -m pip install -r requirements.txt
py -m streamlit run app.py
```

Extract the ZIP first and open the extracted project folder in VS Code. Streamlit prints a local URL, usually `http://localhost:8501`.

## Important notes
- The ATS result is a keyword-coverage estimate, not a commercial ATS score or a prediction of hiring success.
- AI writing requires your own API key and may incur API charges. Never commit a real key to GitHub.
- SQLite data is stored locally. This prototype is not production-hardened and does not include payment processing, email verification, or cloud hosting.
