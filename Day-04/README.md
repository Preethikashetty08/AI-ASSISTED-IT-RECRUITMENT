# Day 4 — AI-Assisted Candidate Sourcing 🔎🤖

## Project 2: AI-Assisted Recruitment Workflow

### 📌 Overview

Day 4 focuses on using **AI to improve candidate sourcing** while keeping the recruiter responsible for validating the search strategy.

The workflow followed in this task is:

**Hiring Requirement → AI Assistance → Search Expansion → Boolean Search → Multi-Channel Sourcing → Recruiter Validation**

The objective is to demonstrate practical knowledge of **AI-assisted sourcing, Boolean search, keyword generation and candidate targeting**.

---

## 🎯 Objective

Use AI to generate and improve:

* Alternative job titles
* Search keywords
* Skill synonyms
* Boolean search strings
* Skill combinations
* Candidate personas
* Sourcing strategies

The AI-generated suggestions were then reviewed and refined based on the actual hiring requirement.

---

# 1. Hiring Requirement

**Company:** TechNova Solutions

**Position:** Junior Python Developer

**Experience:** 0–2 years

**Location:** Bengaluru / Hybrid

**Target Candidates:** Freshers and junior developers

### Mandatory Skills

* Python
* SQL
* Git/GitHub
* Programming fundamentals
* Problem-solving

### Preferred Skills

* HTML/CSS
* Flask/Django
* REST APIs

---

# 2. AI Prompt Used

```text
Act as an experienced IT recruiter and sourcing specialist.

For a Junior Python Developer position requiring 0–2 years of experience, generate alternative job titles, relevant keywords, technical skill synonyms, Boolean search strings, skill combinations and candidate personas.

The target candidates are freshers and junior developers.

Keep the suggestions relevant to Python development and avoid unrelated technologies.
```

---

# 3. AI-Assisted Alternative Job Titles

The AI was used to expand the primary job title into related search titles.

| Primary Title           | Alternative Titles           |
| ----------------------- | ---------------------------- |
| Junior Python Developer | Python Developer             |
| Junior Python Developer | Python Engineer              |
| Junior Python Developer | Junior Software Developer    |
| Junior Python Developer | Backend Developer – Python   |
| Junior Python Developer | Software Engineer – Python   |
| Junior Python Developer | Associate Python Developer   |
| Junior Python Developer | Python Backend Developer     |
| Junior Python Developer | Entry-Level Python Developer |

### Recruiter Validation

The following titles were excluded:

* Senior Python Developer
* Python Lead
* Python Architect

**Reason:** These titles generally indicate a level above the required 0–2 years of experience.

---

# 4. Search Keywords & Synonyms

### Python

```text
Python
Python3
Python Programming
Python Development
Python Developer
```

### SQL

```text
SQL
MySQL
PostgreSQL
SQL Queries
Relational Database
```

### Git

```text
Git
GitHub
Version Control
Source Control
```

### Backend

```text
Backend Development
Server-side Development
API Development
Web Development
```

---

# 5. Boolean Search Strings 🔍

### Basic Search

```text
("Python Developer" OR "Python Engineer")
AND Python
AND SQL
AND Git
```

### Fresher / Junior Search

```text
("Junior Python Developer"
OR "Python Developer"
OR "Associate Python Developer"
OR "Junior Software Developer")
AND Python
AND SQL
AND (Git OR GitHub)
```

### Backend Python Search

```text
("Python Developer"
OR "Python Engineer"
OR "Backend Developer")
AND Python
AND SQL
AND (Django OR Flask)
AND (Git OR GitHub)
```

### Broader Search

```text
("Python Developer"
OR "Python Engineer"
OR "Software Engineer"
OR "Backend Developer")
AND Python
AND SQL
AND ("0 years"
OR "1 year"
OR "2 years"
OR Fresher
OR Graduate)
```

### Exclusion Search

```text
("Python Developer" OR "Python Engineer")
AND Python
AND SQL
NOT ("Senior" OR "Lead" OR "Manager" OR "Architect")
```

---

# 6. Skill Combinations

Different combinations can be used depending on the size and quality of the candidate pool.

| Search Type    | Skill Combination           |
| -------------- | --------------------------- |
| Core Python    | Python + SQL + Git          |
| Python Backend | Python + Django/Flask + SQL |
| Python API     | Python + REST API + SQL     |
| Fresher        | Python + SQL + Projects     |
| Academic       | Python + SQL + Internship   |
| Broad          | Python + Git/GitHub + SQL   |

---

# 7. Candidate Persona 👤

### Target Candidate

**Junior Python Developer — Fresher**

**Education:**
BE/B.Tech/BCA/MCA in Computer Science, IT or related field

**Experience:**
0–2 years

**Technical Skills:**

* Python
* SQL
* Git/GitHub
* Programming fundamentals
* HTML/CSS

**Preferred Exposure:**

* Flask/Django
* REST APIs
* Academic projects
* Internship experience

**Soft Skills:**

* Communication
* Problem-solving
* Teamwork
* Willingness to learn

### Ideal Candidate Indicator

A candidate who has completed a Python-based academic, internship or personal project and demonstrates basic SQL and Git/GitHub knowledge.

---

# 8. Traditional + AI-Assisted Sourcing Strategy

| Sourcing Channel   | Traditional Approach         | AI Assistance                                 |
| ------------------ | ---------------------------- | --------------------------------------------- |
| LinkedIn           | Search candidate profiles    | Generate titles, keywords and Boolean strings |
| Naukri             | Search resumes               | Expand titles and skill combinations          |
| Indeed             | Search profiles              | Generate alternative keywords                 |
| Employee Referrals | Share JD internally          | Create candidate persona                      |
| Campus Recruitment | Target colleges and freshers | Identify suitable skill combinations          |
| GitHub/Portfolio   | Review candidate projects    | Generate project and skill keywords           |

---

# 9. Recruiter Validation

AI suggestions were not accepted blindly.

| AI Suggestion               | Recruiter Decision                     | Reason                             |
| --------------------------- | -------------------------------------- | ---------------------------------- |
| Python Developer            | ✅ Keep                                 | Direct match                       |
| Python Engineer             | ✅ Keep                                 | Relevant alternative               |
| Backend Developer           | ✅ Keep                                 | Relevant when combined with Python |
| Senior Python Developer     | ❌ Exclude                              | Experience mismatch                |
| Python Architect            | ❌ Exclude                              | Too senior                         |
| Python + SQL                | ✅ Keep                                 | Core requirement                   |
| Python + Cloud + Kubernetes | ⚠️ Optional / Exclude from core search | Not required                       |
| Django/Flask                | ✅ Preferred                            | Relevant additional exposure       |

---

# 10. Sourcing Funnel

```text
Hiring Requirement
        ↓
AI Search Expansion
        ↓
Alternative Job Titles
        ↓
Keywords & Synonyms
        ↓
Boolean Search
        ↓
LinkedIn / Naukri / Indeed / Referrals / Campus
        ↓
Candidate Profiles
        ↓
Recruiter Screening
        ↓
Shortlisted Candidates
```

---

# 11. AI + Recruiter Responsibility

### AI helps with:

* Generating search ideas
* Expanding job titles
* Finding synonyms
* Creating Boolean strings
* Suggesting skill combinations
* Building candidate personas

### Recruiter is responsible for:

* Validating the requirements
* Selecting relevant search terms
* Removing unnecessary skills
* Avoiding unrealistic requirements
* Checking candidate relevance
* Making the final sourcing decision

> **AI expands the search; the recruiter controls the search criteria.**

---

# 12. Skills Demonstrated ⭐

This task demonstrates:

* AI-Assisted Candidate Sourcing
* IT Recruitment
* Boolean Search
* LinkedIn Sourcing
* Naukri Sourcing
* Keyword Research
* Job Title Mapping
* Candidate Persona Creation
* Skill-Based Search
* Multi-Channel Sourcing
* Recruiter Validation
* Responsible AI Usage

---

# 13. Tools Used

* Generative AI
* Microsoft Word
* GitHub
* Boolean Search Techniques

---

# 14. Project Deliverable

The complete Day 4 documentation contains:

```text
Day-04/
│
├── README.md
│
└── Project_2_Day_4_AI_Assisted_Candidate_Sourcing.docx
```

The Word document contains the detailed **AI-assisted sourcing strategy, Boolean searches, candidate persona, sourcing channels and recruiter validation**.

---

# 🚀 Day 4 Outcome

Successfully created an **AI-Assisted Candidate Sourcing Strategy** for a Junior Python Developer role.

The project demonstrates how a recruiter can combine **traditional sourcing channels with AI assistance** to discover better search terms, build Boolean strings, identify relevant candidate profiles and create a more structured sourcing process.

### Key Learning

> **AI should assist the recruiter in sourcing — not replace recruiter judgment.**

**Day 4 Status: ✅ Completed**
