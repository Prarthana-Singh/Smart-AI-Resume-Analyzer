

#  **🏝️ Smart AI Resume Analyzer 🏝️**  



## <img src="https://github.com/user-attachments/assets/a6e4d77f-56d6-4aa8-8278-0f5a18ef5eb9" width="24px"> **What Makes Us Different?**  

**<img src="https://github.com/user-attachments/assets/76906dbc-343d-4267-ace5-048d428fff42" width="20px"> Next-Level Features for Success:**  
1. 🕵️ **Deep Resume Analysis:**  
   - 🛡️ ATS Compatibility Score  
   - 🔑 Keyword Gap Analysis  
   - 🧩 Role-specific Feedback  
   - 📊 Skills Gap Breakdown  

2. 🎨 **AI-Powered Resume Builder:**  
   - **Themes that Shine** (Modern, Minimal, Professional, Creative)  
   - **Smart Content Suggestions**  
   - **ATS-Optimized Formatting**  
   - **Customizable Sections**  

3. 🤖 **AI Optimization Engine:**  
   - 💡 Keyword Highlighting  
   - ✍️ Content Enhancement Tips  
   - 🌟 Industry-Specific Insights  

**🎉 Why Use Smart Resume AI?**  
Get real-time feedback, boost your resume’s impact, and maximize your chances of getting shortlisted—all with a sleek and intuitive interface.  

## <img src="https://github.com/user-attachments/assets/e5ac1371-6ac4-48b6-b95c-5ef9afaf1353" width="30"> **Live Demo**  
👨‍💻 Try it Now: [![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://resumeanalyzer-ai.streamlit.app/)  


## <img src="https://github.com/user-attachments/assets/0cefad05-58a9-4aa0-a070-f75a0c9b0353" height="32px">  Tech Stack 
<details>
  <summary>🌐 Frontend</summary>

| **🌟 Technology**    | **💼 Role**                                                             |  
|-----------------------|-------------------------------------------------------------------------|  
| [**Streamlit**](https://streamlit.io/)   | Builds interactive and user-friendly web apps for resume analysis.     |  
| [**HTML**](https://developer.mozilla.org/en-US/docs/Learn/HTML)  | Provides the basic structure for web pages.                             |  
| [**CSS**](https://developer.mozilla.org/en-US/docs/Web/CSS)      | Adds styling and layouts to the frontend.                               |  
| [**JavaScript**](https://developer.mozilla.org/en-US/docs/Learn/JavaScript) | Enables interactivity and dynamic behavior for the web pages.          |  

</details>

<details>
  <summary>⚙️ Backend</summary>

| **🌟 Technology**    | **💼 Role**                                                             |  
|-----------------------|-------------------------------------------------------------------------|  
| [**Streamlit**](https://streamlit.io/)   | Handles backend logic and integrates machine learning models.           |  
| [**Python**](https://www.python.org/)    | Provides core programming language for implementing functionalities.    |  

</details>

<details>
  <summary>🗄️ Database</summary>

| **🌟 Technology**    | **💼 Role**                                                             |  
|-----------------------|-------------------------------------------------------------------------|  
| [**SQLite3**](https://www.sqlite.org/index.html) | Stores and retrieves resume data for efficient processing.             |  

</details>

<details>
  <summary>📦 Modules</summary>

| **🌟 Technology**    | **💼 Role**                                                             |  
|-----------------------|-------------------------------------------------------------------------|  
| [**spaCy**](https://spacy.io/)          | Enhances NLP for keyword analysis and ATS compatibility checks.        |  
| [**Python-docx**](https://python-docx.readthedocs.io/en/latest/)    | Enables Word document editing for resume customization.                |  
| [**PyPDF2**](https://pypdf2.readthedocs.io/en/latest/)         | Processes PDF files for extracting and analyzing resumes.              |  
| [**scikit-learn**](https://scikit-learn.org/)   | Drives machine learning models for resume optimization.                |  
| [**Plotly**](https://plotly.com/)         | Creates interactive charts for skills gap and keyword analysis.        |  
| [**NLTK**](https://www.nltk.org/)         | Provides tools for tokenization, stemming, and text preprocessing in NLP. |  
| [**openpyxl**](https://openpyxl.readthedocs.io/en/stable/)      | Facilitates reading, writing, and modifying Excel files for data visualization and export. |  

</details>

## 💡 **How It Works**  

1. **Upload or Start from Scratch**  
   - Import your resume in **PDF/Word** or create one from scratch with our AI-powered builder.  

2. **Analyze Your Resume**  
   - **ATS Compatibility**: Ensure your resume meets recruiter expectations.  
   - **Keyword Insights**: Find and fill gaps in your content.  
   - **Skills Gap Analysis**: Discover key skills missing for your target role.  

3. **Build a Stunning Resume**  
   - Select from **4 unique templates** and customize sections like skills, achievements, or hobbies.  

4. **Download & Apply**  
   - Export your resume in **PDF** format, ready for submission.  


## <img src="https://github.com/user-attachments/assets/76906dbc-343d-4267-ace5-048d428fff42" width="30px"> **Setup in Minutes**  

Follow these steps to run Smart Resume AI:  

#### **Setup Instructions** 🛠️

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Prarthana-Singh/Smart-AI-Resume-Analyzer.git
   cd Smart-AI-Resume-Analyzer
   ```

2. **Create a virtual environment:**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Download the spaCy model:**

   ```bash
   python -m spacy download en_core_web_sm
   ```
   
``Congratulations 🥳😱 your set-up 👆 and installation is finished 🥳😱``

5. **Run the application:**

   ```bash
   streamlit run app.py
   ```

## Known Bug 🚨 Autofill Glitch in Resume Builder!  

### What's Happening? 🤔  
If you're using the **Browser's (e.g., Chrome, Edge, etc.) Autofill** feature to quickly fill out your **Name**, **Email**, and **Phone** details in our **Smart AI Resume Analyzer**, you might encounter this error in generating Resume:  
**"⚠️ Please enter your email address."**  

Even though the email field appears to be filled, this is a small bug in the **Resume Builder Feature** where our system doesn’t always recognize inputs from autofill.

### Quick Fix 🛠️  
Don’t worry—it’s a simple fix!  
1. **Edit the email(or Any) field manually:**  
   - Remove one character or number.  
   - Type it back in.  
2. Voilà! The error will disappear, and you can generate your resume smoothly.  
> _(“Voilà” means "there you have it!" or "problem solved!")_

### Why Does This Happen? 🌐  
This is a **known issue with the resume builder feature**, where the autofill behavior of browsers (e.g., Chrome, Edge, etc.) doesn’t trigger the necessary validation for some input fields. By manually editing the email, the system recognizes it correctly.  

We’re actively working on a permanent fix to ensure your experience is seamless. Thank you for your understanding and support! 🙏  


## 🎯 **Why Choose Smart Resume AI?**  

✨ **Tailored for You**  
Your resume is optimized for the job you're aiming for, using role-specific insights.  

🖼️ **Stunning Templates**  
Choose from polished and modern templates that stand out at first glance.  

⚡ **Time-Saving Automation**  
AI does the heavy lifting, helping you create a winning resume in minutes.  

📈 **Better Chances, Every Time**  
Get actionable feedback and align your resume to job descriptions effortlessly.  


## <img src="https://github.com/user-attachments/assets/1fd5ec3c-a43f-4df6-b9ec-31102a6b6564" width="30px"> **Contributing**  

Join the mission! Here's how:  
1. Fork the repository.  
2. Create a new branch for your feature: `git checkout -b feature-name`.  
3. Push changes and submit a Pull Request.  

##  <img src="https://github.com/user-attachments/assets/5b3cb883-6652-4525-a352-b4b9a3501e07" width = 35px height = 35px> **Why Users Love Smart Resume AI**  

- **Saves Time:** Create a stunning resume in minutes.  
- **Increases Job Opportunities:** Tailor your resume to any role.  
- **Professional Output:** Choose from modern and polished designs.  
- **Boosts Confidence:** Optimized, recruiter-ready resumes.  

## <img src="https://github.com/user-attachments/assets/e5ac1371-6ac4-48b6-b95c-5ef9afaf1353" width="30"> **Features That Set Us Apart**  

| **Feature**                   | **Description**                                                                                 |  
|--------------------------------|-------------------------------------------------------------------------------------------------|  
| 🔍 **Resume Analysis**         | Get an ATS score, identify keyword gaps, and find skills to add for role alignment.             |  
| ✨ **Customizable Templates**  | Choose from **4 sleek designs**: Modern, Minimal, Professional, Creative.                       |  
| 📈 **AI-Driven Insights**      | Receive smart suggestions for optimizing content, formatting, and keywords.                    |  
| 🎯 **Role-specific Guidance**  | Tailored recommendations for matching job descriptions and standing out in applications.        |  

## 🎥 **Quick Glance**  

<div align="center">  
<table>  
<tr>  
<td align="center"><b>
   
   [🏠 HOME](https://resumeanalyzer-ai.streamlit.app/)
   </b></td>  
<td align="center"><b>
   
   [🔍 RESUME ANALYZER(Below Example Analysis of Backend Deeveloper)](https://resumeanalyzer-ai.streamlit.app/)
</b></td>  
</tr>  
<tr>  
<td><img src="https://github.com/user-attachments/assets/2dc1b44d-7eb6-4371-81f9-3a140f83064c" alt="🏠 HOME" width="500px"></td>  
<td><img src="https://github.com/user-attachments/assets/b9f4c7b0-fbd6-40c4-9d8b-231d9fdd91a7" alt="🔍 RESUME ANALYZER" width="500px"></td>  
</tr>  
<tr>  
<td align="center"><b>
   
   [🔍 RESUME ANALYZER(Score And Recommendations)](https://resumeanalyzer-ai.streamlit.app/)
   </b></td>  
<td align="center"><b>
   
   [🔍 RESUME ANALYZER(According To Roles Recommendations)](https://resumeanalyzer-ai.streamlit.app/)
   </b></td>  
</tr>  
<tr>  
<td><img src="https://github.com/user-attachments/assets/02b6d379-a04f-421e-9377-1bb077324f17" alt="🔍 RESUME ANALYZER(Score And Recommendations Based on Role Selected)" width="500px"></td>  
<td><img src="https://github.com/user-attachments/assets/830e738e-a76b-4818-b426-d98189d8c441" alt="🔍 RESUME ANALYZER(Score And Recommendations Based on Role Selected)" width="500px"></td>  
</tr>  

<tr>  
<td align="center"><b>
   
   [🔍 RESUME ANALYZER(According To Roles Course Recommendations)](https://resumeanalyzer-ai.streamlit.app/)
   </b></td>  
<td align="center"><b>
   
   [🔍 RESUME ANALYZER(Videos Recommendations)](https://resumeanalyzer-ai.streamlit.app/)
   </b></td>  
</tr>  
<tr>  
<td><img src="https://github.com/user-attachments/assets/fcfb02f2-2831-4f26-a251-8c67266afca8" alt="🔍 RESUME ANALYZER" width="500px"></td>  
<td><img src="https://github.com/user-attachments/assets/90704043-a559-42fb-bcf1-330ebfedee2b" alt="🔍 RESUME ANALYZER" width="500px"></td>  
</tr> 
<tr>  
<td align="center"><b>
   
   [📝 RESUME BUILDER](#-interactive-resume-templates)
</b></td>  
<td align="center"><b>
   
   [📊 DASHBOARD](https://resumeanalyzer-ai.streamlit.app/)
</b></td>  
</tr>  
<tr>  
<td><img src="https://github.com/user-attachments/assets/7ebdf0d0-1172-47dd-a281-7d4bb058bd3f" alt="📝 RESUME BUILDER" width="500px"></td>  
<td><img src="https://github.com/user-attachments/assets/982f26b9-f84d-4cec-b8c2-beeec23b5e8b" alt="📊 DASHBOARD" width="500px"></td>  
</tr>  
<tr>  
<td align="center"><b>
   
   [🎯 JOB SEARCH](https://resumind.streamlit.app/)
   </b></td>  
<td align="center"><b>
   
   [🎯 JOB SEARCH(📊 Job Market Insights & 🏢 Featured Companies)](https://resumeanalyzer-ai.streamlit.app/)
   </b></td>  
</tr>  
<tr>  
<td><img src="https://github.com/user-attachments/assets/0b9bab57-5c73-4944-90bb-c9c374c4b559" alt="🎯 JOB SEARCH" width="500px"></td>  
<td><img src="https://github.com/user-attachments/assets/10aaa50e-3c28-415b-948d-a9744f942dcd" alt="🎯 JOB SEARCH(📊 Job Market Insights & 🏢 Featured Companies)" width="500px"></td>  
</tr>  
<tr>  
<td align="center"><b>
   
   [💬 FEEDBACK](https://resumeanalyzer-ai.streamlit.app/)
   </b></td>  
<td align="center"><b>
   
   [ℹ️ ABOUT](https://resumeanalyzer-ai.streamlit.app/)
   </b></td>  
</tr>  
<tr>  
<td><img src="https://github.com/user-attachments/assets/88f85cca-35df-4575-a949-b5ac49d822f5" alt="💬 FEEDBACK" width="500px"></td>  
<td><img src="https://github.com/user-attachments/assets/649625ed-a8c8-436a-bdbe-4f261b598ef3" alt="ℹ️ ABOUT" width="500px"></td>  
</tr>  
</table>  
</div>  



## 🎨 **Interactive Resume Templates**  

| ![Modern Template](https://github.com/user-attachments/assets/63a7c783-9903-4e45-bdc7-3bfb41f2606b) | ![Minimal Template](https://github.com/user-attachments/assets/ea1ade65-a726-4c67-a19c-2b29d8ab748e) |  
|---------------------------------------------------------------------------|-----------------------------------------------------------------------------|  
| **Modern Template** - Polished & stylish                                  | **Minimal Template** - Clean & elegant                                     |  

| ![Professional Template](https://github.com/user-attachments/assets/003532ae-99ec-41b7-a258-05bf3f97a4cc) | ![Creative Template](https://github.com/user-attachments/assets/0fc2aa14-e24b-473d-964e-2900e49631f1) |  
|-------------------------------------------------------------------------------------|---------------------------------------------------------------------------------|  
| **Professional Template** - Industry-standard                                     | **Creative Template** - Unique & visually appealing                          |  


## 📄 **License**  

This project is licensed under the [MIT License](https://github.com/Prarthana-Singh/Smart-AI-Resume-Analyzer/blob/main/LICENSE).  


## 🌟 **GitHub Repo**  

Explore the code, contribute, or drop a <img src="https://github.com/user-attachments/assets/35f6838c-52f5-4e48-8a98-c5203f8c57e3" style="width:20px; color: #FFD700" alt="Star GIF"> : [Smart Resume AI Repository](https://github.com/Prarthana-Singh/Smart-AI-Resume-Analyzer)  

## 🛡️ Maintainer  

> **_This repository is maintained by [Prarthana-Singh](https://github.com/Prarthana-Singh)._**  
> Have suggestions? Feel free to reach out to [me via email](mailto:prarthanas645@gmail.com). 📧


## 📰 News  
**Practice, practice, practice!** Keep working hard, and it will all fall into place. No shortcuts in this Field! 🛠️  
> Stay curious and keep learning. 🚀





**Thank you for your support! Every bit helps keep this repository going.** 🌈✨
