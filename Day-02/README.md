# 🤖 AI-Assisted IT Recruitment & Candidate Sourcing

## 📌 Project Overview

**AI-Assisted IT Recruitment & Candidate Sourcing** is a portfolio project that demonstrates how AI can assist recruiters throughout the IT hiring process.

The project focuses on using AI as a **recruitment assistant**, rather than replacing human recruiters. It helps structure hiring requirements, generate sourcing keywords, create Boolean search strings, support resume screening, prepare recruiter questions, and organize candidate evaluation.

The project is designed around three common IT roles:

* Java Developer
* QA Engineer
* Python Developer

---

## 🎯 Project Objective

The main objective is to design a practical recruitment workflow that combines:

**Recruiter Expertise + AI Assistance + Structured Screening**

The project aims to reduce repetitive recruitment work while maintaining human oversight in candidate evaluation and hiring decisions.

---

## 🏢 Hiring Scenario

A fictional technology company is expanding its technology team and requires early-career IT professionals.

### Open Positions

| Role             | Vacancies | Experience |
| ---------------- | --------: | ---------- |
| Java Developer   |         2 | 0–2 years  |
| QA Engineer      |         2 | 0–2 years  |
| Python Developer |         2 | 0–2 years  |
| **Total**        |     **6** |            |

### General Hiring Requirements

* Education: BE/B.Tech/MCA in Computer Science, IT, or related fields
* Employment: Full-Time
* Location: Bangalore / Hybrid
* Notice Period: Immediate to 30 days
* Candidate Level: Freshers and early-career professionals

---

# 🔄 Recruitment Workflow

```text
Hiring Requirement
        ↓
Job Description
        ↓
AI-Assisted Skill Analysis
        ↓
Sourcing Keywords
        ↓
Boolean Search
        ↓
Candidate Sourcing
        ↓
Resume Screening
        ↓
AI-Assisted Candidate Matching
        ↓
Human Recruiter Review
        ↓
Recruiter Screening
        ↓
Technical Assessment
        ↓
Technical Interview
        ↓
HR / Managerial Interview
        ↓
Offer
        ↓
Joining & Onboarding
```

---

# 🧩 Project Modules

## 1. Hiring Requirement

The first stage converts a business hiring need into a structured recruitment requirement.

The requirement contains:

* Job title
* Number of vacancies
* Experience
* Education
* Required skills
* Good-to-have skills
* Location
* Employment type
* Notice period
* Salary range
* Responsibilities
* Candidate profile

---

# 2. Job Descriptions

Three role-specific job descriptions are created.

### Java Developer

**Must-Have Skills:**

* Core Java
* OOP
* SQL
* Spring Boot
* REST APIs
* Git
* Basic data structures

**Good-to-Have:**

* Hibernate/JPA
* Microservices
* Docker
* AWS
* Maven
* JUnit

### QA Engineer

**Must-Have Skills:**

* Manual Testing
* SDLC
* STLC
* Test Cases
* Bug Reporting
* Functional Testing
* Regression Testing
* SQL

**Good-to-Have:**

* Selenium
* Postman
* JIRA
* API Testing
* Automation Testing
* Agile/Scrum

### Python Developer

**Must-Have Skills:**

* Python
* OOP
* SQL
* REST APIs
* Git
* Basic data structures
* Problem-solving

**Good-to-Have:**

* Django
* Flask
* FastAPI
* Pandas
* NumPy
* Docker
* AWS

---

# 3. AI-Assisted Sourcing

AI can help recruiters identify alternative keywords and related terms for each role.

### Example – Java Developer

Possible sourcing keywords:

```text
Java Developer
Java Engineer
Java Fresher
Junior Java Developer
Core Java
Spring Boot
Java Backend Developer
REST API
SQL
```

### Example – QA Engineer

```text
QA Engineer
QA Tester
Software Tester
Manual Tester
QA Fresher
Functional Testing
Regression Testing
Selenium
SQL
```

### Example – Python Developer

```text
Python Developer
Python Engineer
Python Fresher
Junior Python Developer
Python Backend
Django
Flask
FastAPI
REST API
SQL
```

---

# 4. Boolean Search

Boolean search strings are created to improve candidate sourcing on professional networking and job platforms.

### Java Developer

```text
("Java Developer" OR "Java Engineer" OR "Java Fresher")
AND (Java OR "Core Java")
AND ("Spring Boot" OR Spring)
AND SQL
```

### QA Engineer

```text
("QA Engineer" OR "QA Tester" OR "Software Tester" OR "Manual Tester")
AND ("Manual Testing" OR "Functional Testing")
AND (SQL OR Selenium)
```

### Python Developer

```text
("Python Developer" OR "Python Engineer" OR "Python Fresher")
AND Python
AND (Django OR Flask OR FastAPI OR "REST API")
AND SQL
```

---

# 5. AI-Assisted Resume Screening

AI can assist the recruiter in extracting relevant information from resumes.

The screening process checks:

* Education
* Experience
* Technical skills
* Projects
* Internship experience
* Tools
* Notice period
* Location
* Relevant keywords

The AI output can categorize skills into:

```text
Matched Must-Have Skills
        ↓
Missing Must-Have Skills
        ↓
Matched Good-to-Have Skills
        ↓
Relevant Experience
        ↓
Relevant Projects
        ↓
Preliminary Match Score
```

The recruiter then manually reviews the original resume before making a decision.

---

# 6. Candidate Match Score

A weighted candidate score can be used to prioritize recruiter review.

| Criteria                         |   Weight |
| -------------------------------- | -------: |
| Technical Skills                 |      30% |
| Relevant Experience / Internship |      15% |
| Projects                         |      10% |
| Problem Solving                  |      15% |
| Communication                    |      10% |
| Education                        |       5% |
| Notice Period                    |       5% |
| Location / Work Model            |       5% |
| Overall Role Fit                 |       5% |
| **Total**                        | **100%** |

### Interpretation

| Score     | Meaning       |
| --------- | ------------- |
| 85–100%   | Strong Match  |
| 70–84%    | Good Match    |
| 50–69%    | Partial Match |
| Below 50% | Low Match     |

**Important:** The score is a prioritization aid and not an automatic hiring decision.

---

# 7. AI Resume Screening Prompt

Example prompt used in the project:

> Analyze this candidate resume against the selected job requirement. Extract the candidate's education, experience, technical skills, projects, internship experience, notice period, and location. Separate matched must-have skills, missing must-have skills, and good-to-have skills. Provide a preliminary match percentage with evidence for each score. Do not make a final hiring decision and do not infer information that is not present in the resume.

---

# 8. Recruiter Screening

After AI-assisted resume screening, the recruiter conducts a human screening call.

### General Screening Questions

1. Please introduce yourself.
2. What interests you about this role?
3. What is your current location?
4. What is your notice period?
5. What are your salary expectations?
6. Are you comfortable working from Bangalore/hybrid?
7. Which project or internship is most relevant to this role?
8. Why are you interested in this career opportunity?

### Role-Specific Screening

Recruiters also ask technical questions relevant to the selected position.

---

# 9. Human-in-the-Loop Approach

This project follows a **Human-in-the-Loop** recruitment model.

AI assists with:

* Information extraction
* Keyword generation
* Boolean search creation
* Resume matching
* Candidate prioritization
* Screening question generation

The recruiter remains responsible for:

* Reviewing candidate information
* Verifying resume details
* Conducting screening calls
* Evaluating candidate suitability
* Making shortlist decisions
* Coordinating interviews
* Final hiring decisions

### Principle

```text
AI Recommendation
       ↓
Human Verification
       ↓
Recruiter Decision
```

---

# 🔐 Responsible AI Guidelines

The project avoids treating AI outputs as automatically correct.

Recruiters should:

* Verify AI-generated information against the original resume.
* Avoid making decisions solely from an AI-generated score.
* Never fabricate candidate skills or experience.
* Avoid using sensitive personal characteristics as selection criteria.
* Maintain candidate confidentiality.
* Review transferable skills and context before rejecting candidates.
* Keep human oversight throughout the recruitment process.

---

# 🛠️ Tools & Technologies

### Recruitment Tools

* LinkedIn
* Job portals
* Excel / Google Sheets
* ATS concepts

### AI Assistance

* Generative AI
* AI-assisted resume analysis
* AI-generated sourcing keywords
* AI-generated Boolean search strings
* AI-assisted screening questions

### Documentation

* Microsoft Word
* Microsoft Excel
* GitHub
* Markdown

---

# 📊 Expected Project Outcomes

The project demonstrates how AI can help recruiters:

* Structure hiring requirements faster.
* Generate relevant sourcing keywords.
* Build Boolean search strings.
* Organize candidate information.
* Prioritize resumes for manual review.
* Create consistent screening criteria.
* Prepare recruiter screening questions.
* Improve recruitment workflow organization.

---

# 📁 Repository Structure

```text
01_Hiring_Requirement/
02_Job_Descriptions/
03_AI_Sourcing/
04_Candidate_Screening/
05_Recruiter_Screening/
06_Recruitment_Workflow/
07_AI_Governance/
screenshots/
README.md
```

---

# 🚀 Future Improvements

Possible future versions of this project could include:

* Automated resume parser
* Resume-to-JD matching system
* Candidate database
* AI-generated candidate summaries
* Recruitment dashboard
* ATS-style candidate pipeline
* Email automation
* Interview scheduling workflow
* Candidate ranking dashboard
* Recruitment analytics
* Candidate experience tracking

---

# 👩‍💻 Skills Demonstrated

This project demonstrates practical skills in:

* IT Recruitment
* Talent Acquisition
* Candidate Sourcing
* Boolean Search
* Resume Screening
* Job Description Analysis
* Candidate Matching
* Recruitment Coordination
* AI-Assisted Recruitment
* Excel-based Recruitment Tracking
* Structured Candidate Evaluation
* Responsible AI Usage

---

# 📌 Disclaimer

This is a fictional portfolio project created for learning and demonstration purposes.

AI outputs are treated as recruitment assistance only. Final candidate evaluation and hiring decisions should remain under appropriate human review.
