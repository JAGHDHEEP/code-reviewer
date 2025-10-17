

Overview

The AI Code Review Assistant is a web-based application that automates the process of reviewing source code using Google’s Gemini AI model.  
It evaluates your code for readability, modularity, structure, and potential bugs, then provides detailed improvement suggestions in a clean, structured report.


 Features

✅ Upload and analyze code files (.py, .java, .js, etc.)  
✅ AI-generated code review using **Gemini 1.5 Pro**  
✅ Structured JSON report with insights and improvement suggestions  
✅ Optional dashboard to **upload, view, and manage reports**  
✅ Download reports as `.txt` or `.pdf`  
✅ (Optional) Authentication to store user-specific review history  


 How It Works

1. User uploads or pastes source code into the web dashboard.  
2. Backend sends the code to Gemini API using a structured prompt.  
3. Gemini analyzes the code and returns a report in JSON format.  
4. The report is displayed beautifully in the web app, categorized by:
   - Readability
   - Modularity
   - Potential Bugs
   - Suggestions



Tech Stack

| Component               | Technology                            |
| ----------------------- | ------------------------------------- |
| **Frontend**            | React + Tailwind CSS                  |
| **Backend**             | Node.js (Express) or Python (FastAPI) |
| **Database (optional)** | SQLite / Firebase / MongoDB           |
| **AI Model**            | Gemini 1.5 Pro                        |
| **Hosting (optional)**  | Firebase Hosting / Google Cloud Run   |




 Future Enhancements

* 🔄 GitHub/GitLab integration for pull request reviews
* 🧠 Code diff analysis for updated versions
* 📬 Email or Slack alerts for review summaries
* 🎨 Syntax highlighting for reviewed code
* 📊 Analytics dashboard for code quality trends


## 👨‍💻 Author

**Jagadeep**
B.Tech | AI & ML Enthusiast | VIT Vellore
🌐 [LinkedIn](https://linkedin.com) • [GitHub](https://github.com)
