**DraftCheck – Web App for Article Analysis**

Hi, I’m Deepthi Reddy Kallam, and this is a full-stack web application I built with my team during our final year of undergraduate studies at GRIET. DraftCheck is designed to simplify the process of article and document analysis for students, researchers, and writers by offering multiple powerful tools in one place.
**
What is DraftCheck?**

In a world where content is everywhere and time is limited, DraftCheck provides a simple yet effective way to analyze and enhance articles. Instead of juggling between multiple websites to check grammar, count words, summarize text, or extract keywords, DraftCheck brings all these features into one unified platform.

**Features**

Article Summarization
Cuts down long texts into concise summaries using NLP and Adaptive Text Summarization APIs.

Keyword Extraction
Uses TF-IDF to pull out the most relevant terms from an article.

Word Count Tool
Instantly counts the number of words in any given document.

Spell Checker
Identifies and corrects spelling errors using the TextBlob library.

**Why We Built It**

Most existing tools only offer one or two of these features in isolation. We realized that users—especially students and content writers—need a one-stop solution to perform multiple checks on their drafts. DraftCheck solves that problem by offering:

A clean and user-friendly interface

Fast, accurate NLP-driven analysis

All tools in one app—no need to switch tabs

**Tech Stack**

Backend: Python, Flask

Frontend: HTML, CSS, basic JavaScript

NLP Libraries: TextBlob, TF-IDF (via scikit-learn)

Environment: Anaconda Navigator, Jupyter Notebook

Deployment: Localhost (can be extended to cloud)

**Project Structure**

php
Copy
Edit
DraftCheck/
├── app.py                    # Flask app logic and route handling
├── templates/
│   ├── home.html             # Main page
│   ├── summarizer.html       # Summary tool
│   ├── wordcount.html        # Word count tool
│   ├── keywords.html         # Keyword extraction tool
│   └── grammarcheck.html     # Spell check tool
└── static/                   # CSS, images (optional)

**Testing and Performance**

We tested each feature individually and together to ensure seamless interaction between the frontend and backend. We also conducted:

Unit Testing for each module

Integration Testing to verify how well the system components worked together

User Testing to identify usability issues

All key features performed as expected.

**Limitations & Future Scope**

Currently supports English-language articles only

URL-based article input was less accurate and needs refinement

**Future plans include:**

Plagiarism detection integration

Multilingual support

Mobile app version for easier access

Option to apply all analysis operations at once
