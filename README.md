# 🤖 AI Resume Analyzer

An AI-powered Resume Analyzer built with *n8n* that analyzes a resume based on the user's *target job role* and optional *Job Description (JD)*.

![AI Resume Analyzer Workflow](screenshots/Workflow-overview.png)

---

## 🎯 Problem

Job seekers often use the same resume for different jobs.

This can result in:

- Poor job-role matching
- Missing required skills
- Irrelevant projects
- Missing ATS keywords
- Weak resume sections

Manually reviewing and improving a resume for every job is also time-consuming.

---

## 💡 Solution

AI Resume Analyzer helps users analyze their resume for a specific job role and Job Description.

The user can:

- Upload a Resume PDF
- Define a Target Role
- Add an optional Job Description
- Analyze resume-job matching
- Identify missing and critical skills
- Analyze project relevance
- Check ATS compatibility
- Get resume improvement recommendations
- Generate a PDF analysis report

---

## 🔄 Workflow

```text
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
      Respond in chat

## ✨ **Features**

  📄 Resume PDF Upload
  🎯 Target Role Analysis
  📋 Job Description Analysis
  🛠️ Skills & Skill Gap Analysis
  💻 Project Relevance Analysis
  📊 ATS Analysis
  📈 Overall Match Score
  ⚠️ Resume Weakness Detection
  💡 Improvement Recommendations
  ✨ Resume Improvement Plan
📄 PDF Report Generation


## 🧠 **Tech Stack**

 - n8n — Workflow automation
 - AI Agent — Resume analysis
 - LLM — AI reasoning
 - Structured Output Parser — Structured AI response
 - JavaScript — Report formatting
 - PDF Extraction — Resume processing

## 🎯 Who Can Use It?

👨‍💻 Job Seekers
Analyze and improve their resume before applying for a specific job.

🎓 Students & Freshers
Understand skill gaps, project relevance and resume readiness.

🏫 Colleges & Placement Cells
Customize the workflow for student resume analysis and placement preparation.

💼 Career Coaches
Use AI for initial resume analysis and recommendations.

👥 Recruitment Platforms
Extend the workflow for candidate-to-job matching and resume analysis.

The workflow can be customized for different roles such as:
 - MERN Developer, Python Developer, AI Engineer, Data Analyst, Sales, Customer Support, HR, etc.

## 🚀 Future Development

The current Resume Analyzer can be extended into a complete AI Career Assistant.

🤖 AI Resume Optimization
Generate an improved version of the resume based on the target role and Job Description.

🔎 AI Job Matching
Find and rank jobs based on the candidate's skills, experience and target role.

📝 Application Assistant
Generate customized resumes, cover letters and application responses for specific jobs.

📧 Recruiter Communication
Generate personalized recruiter messages, follow-ups and professional emails.

🎤 Interview Preparation
Generate role-specific, JD-based and resume-based interview questions with AI mock interviews.

🧩 Skill Gap Analysis
Compare the candidate's current skills with the skills required for the target job.

📚 Learning Roadmap
Generate a personalized learning path and project recommendations based on the candidate's skill gaps
.
📊 Application Tracking
Track applied jobs, interview stages, follow-ups and application status.

# Long-Term Vision
The long-term goal is to expand the Resume Analyzer into an AI-powered Career Assistant that helps candidates throughout the job-search journey.

        Analyze Resume
            ↓
      Identify Skill Gaps
            ↓
      Improve Resume
            ↓
      Find Matching Jobs
            ↓
      Prepare Application
            ↓
      Track Applications
            ↓
      Prepare Interview
