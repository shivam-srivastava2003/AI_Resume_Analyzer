# 🤖 AI Resume Analyzer

An AI-powered resume analysis workflow built with **n8n**. It analyzes a
resume based on the user's target role and optional job description,
then provides a structured, human-readable report.

![Workflow Overview](Screenshot/Workflow-overview.png)

## 🔄 Workflow

``` text
Resume + Target Role + JD
        ↓
   Chat Trigger
        ↓
   Extract Resume
        ↓
     AI Agent
        ↓
Structured Output Parser
        ↓
    Edit Fields
        ↓
Code in JavaScript
        ↓
   Respond in Chat
```

## ✨ Features

-   📄 Resume PDF Upload
-   🎯 Target Role Analysis
-   💼 Job Description Analysis
-   🛠️ Skills & Skill Gap Analysis
-   📁 Project Relevance Analysis
-   💼 Experience Section Analysis
-   🎓 Education & Certification Analysis
-   📝 Resume Summary Analysis
-   🔍 ATS Keyword Analysis
-   📊 Overall Resume Structure Analysis
-   🚀 Resume Improvement Suggestions
-   ✅ Final Resume Decision

## 🎯 Problem Solved

Many candidates do not know whether their resume is suitable for a
specific job role. Manual resume checking is time-consuming and
candidates often miss important skills, ATS keywords, projects, and
improvement areas.

This workflow provides a quick AI-based analysis so candidates can
understand **what is strong, what is missing, and what should be
improved** before applying.

## 🧩 Customization

The workflow can be customized for different use cases such as:

-   Fresher resume analysis
-   Software developer roles
-   Data/AI/ML roles
-   Marketing and sales roles
-   Customer support roles
-   Role-specific ATS checking
-   Job-description based resume matching

## 🛠️ Tech Stack

-   **n8n** -- Workflow automation
-   **AI Agent** -- Resume analysis
-   **Structured Output Parser** -- Structured AI response
-   **JavaScript** -- Report formatting
-   **Chat Trigger** -- User interaction
   

## 🚀 Future Development

The project can be extended into a complete AI career assistant that can
compare a resume with multiple job descriptions, recommend suitable
jobs, generate role-specific resume improvements, optimize ATS keywords,
create customized cover letters, and track applications.

It can also be integrated with job platforms and email automation to
reduce repetitive job-search work and help candidates manage their
complete job-application process from one place.

## 📂 Project Files

``` text
AI_Resume_Analyzer/
│
├── workflow.json
├── README.md
└── screenshots/
    └── workflow-overview.png
    └── AI-Agent Parser.png
    └── chat-box.png
    └── chat-input.png
    └── Analysis-report.png
```

## ⚙️ Setup

1.  Import `workflow.json` into n8n.
2.  Configure the required AI/API credentials.
3.  Activate the workflow.
4.  Upload a resume and provide the target role.
5.  Optionally provide a job description.
6.  View the AI-generated analysis in chat.

> ⚠️ Do not upload real API keys, passwords, OAuth tokens, or private
> credentials to GitHub.

## 📌 Note

This project is an AI-assisted resume analysis tool. The recommendations
should be reviewed by the user before making career decisions.

## 👨‍💻 Author

**Shivam Kumar**

