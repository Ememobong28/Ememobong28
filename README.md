<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:8B5CF6,50:6366F1,100:0EA5E9&text=Immanuella%20Emem%20Umoren&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=Software%20Engineer%20%E2%80%A2%20AI%20Builder%20%E2%80%A2%20Open%20Source%20Contributor&descAlignY=60&animation=fadeIn" alt="Immanuella Emem Umoren banner"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=900&color=8B5CF6&center=true&vCenter=true&width=750&lines=Master's+Student+in+Computer+Science+%40+Rice;Former+SWE+Intern+%40+Meta%2C+ServiceNow+%26+Oracle;Building+intelligent%2C+human-centered+products;Exploring+AI+Research+%26+Research+Engineering" alt="Animated introduction"/>
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Immanuella%20Umoren-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/immanuella-umoren/)
[![Email](https://img.shields.io/badge/Email-Let's%20Connect-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:immanuellaumoren@gmail.com)

<br/>

🎯 **Interested in Summer 2027 Software Engineering, AI Engineering & Research Engineering opportunities**

</div>

---

## 👩🏽‍💻 About Me

```python
immanuella = {
    "preferred_name": "Emem",
    "education": "M.S. Computer Science, AI Concentration @ Rice University",
    "experience": ["Meta", "ServiceNow", "Oracle"],
    "interests": [
        "Artificial Intelligence",
        "AI Research",
        "Full-Stack Engineering",
        "Open Source",
        "Research Engineering"
    ],
    "currently": "Building, contributing, researching, and learning"
}
````

I am a software engineer and graduate student at **Rice University**, pursuing a Master of Science in Computer Science with a concentration in Artificial Intelligence.

I have interned at **Meta, ServiceNow, and Oracle**, contributing to full-stack products, backend platforms, machine learning infrastructure, and large-scale engineering systems. I enjoy working across the product lifecycle — from understanding a problem and designing an experience to building, testing, and deploying the final solution.

My current interests sit at the intersection of **AI research, research engineering, intelligent product development, open-source collaboration, and scalable software systems**.

---

## ✨ Selected Highlights

* 🎓 **Valedictorian & Summa Cum Laude** — B.S. Computer Science, Philander Smith University
* 💼 Software Engineering internships at **Meta, ServiceNow, and Oracle**
* 🌱 **Open-source contributor to OSCAR EMR**, with code merged into a production healthcare platform
* 🚀 Built **GradPath**, a full-stack AI-assisted graduation-planning platform with **20+ API endpoints and 15 database models**
* ⚡ Built a vector-embedding caching system at Oracle that reduced execution time from approximately **1 hour 58 minutes to 3 minutes 58 seconds**
* 🏅 **Google Generation Scholar**
* 👩🏽‍💻 Founder of Philander Smith University's first **Girls Who Code** chapter

---

## 🔭 What I'm Working On

<table>
<tr>
<td width="50%" valign="top">

### 🌱 Open Source — OSCAR EMR

Contributing to **OSCAR EMR**, an open-source electronic medical records platform used within Canadian healthcare systems.

[![Merged PR #2975](https://img.shields.io/badge/PR%20%232975-MERGED-2EA44F?style=flat-square\&logo=github\&logoColor=white)](https://github.com/carlos-emr/carlos/pull/2975)
[![PR #3453](https://img.shields.io/badge/PR%20%233453-IN%20REVIEW-8B5CF6?style=flat-square\&logo=github\&logoColor=white)](https://github.com/carlos-emr/carlos/pull/3453)

#### ✅ Merged Contribution — PR #2975

Contributed a security-focused fix that strengthens logging and file handling across the CARLOS codebase.

Added `LogSanitizer` and `UploadedFileResolver` utilities, removed sensitive filename and path values from `EDocUtil` logs to reduce **PHI exposure and log-injection risks**, and added unit tests covering the new functionality.

#### 🔄 Active Contribution — PR #3453

Centralizing filename validation across file and document workflows using `PathValidationUtils`, replacing inconsistent local sanitization logic with shared validation rules.

The changes strengthen file-handling behavior across document caches, uploads, ZIP generation, and temporary files while preserving existing application contracts.

**Technologies:** Java 21 · Spring · JUnit · HL7/FHIR · Secure File Handling · Git

</td>

<td width="50%" valign="top">

### 🧠 Current Focus

Currently exploring and building around:

* **AI agents & agent evaluation**
* **Graph-based machine learning and dependency systems**
* **LLM applications and tool-using agents**
* **Vector embeddings & semantic retrieval**
* **Open-source software engineering**
* **Scalable AI-backed product systems**

I'm especially interested in the intersection of **AI research and production engineering** — understanding how intelligent systems behave, evaluating them rigorously, and turning research ideas into reliable software.

</td>
</tr>
</table>

---

## 🚀 Featured Project

<div align="center">

### 🎓 GradPath

**An AI graduation-planning platform that turns academic complexity into a personalized path toward graduation.**

[![Watch Demo](https://img.shields.io/badge/Watch%20Demo-Play-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://drive.google.com/file/d/1cHZ3BcIEC6xwpzkJvryU9W0fxVtJ4G_c/view?usp=sharing)
[![GradPath Repository](https://img.shields.io/badge/View%20Code-GradPath-8B5CF6?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Ememobong28/GradPath)
[![Figma Design](https://img.shields.io/badge/View%20Design-Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)](https://www.figma.com/design/EQdmbdyNJkmLZLJ6D4ZaOq/Gradpath-Design--Immanuella-Umoren-?node-id=3-14&t=e3NcWK8wsS3ioksD-0)

</div>

GradPath is a full-stack graduation-planning platform that transforms a student's transcript into a personalized, term-by-term academic plan.

### ✨ What It Does

* Parses transcript and academic information
* Maps course prerequisites using a dependency graph
* Generates a personalized graduation plan
* Detects high-risk prerequisite bottlenecks
* Produces a `0–100` graduation-delay risk score
* Explains academic risks in clear, student-friendly language
* Supports What-If academic planning scenarios
* Exports personalized plans as PDF reports

### 🏗️ How It Was Built

* Implemented prerequisite ordering with **Kahn's topological sorting algorithm**
* Developed a machine-learning-assisted academic risk model with **Scikit-learn**
* Built a **FastAPI and PostgreSQL backend** with more than **20 endpoints and 15 SQLAlchemy models**
* Developed a cross-platform frontend using **Flutter**
* Containerized and deployed the application using **Docker, Render, and GitHub Pages**

<div align="center">

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square\&logo=flutter\&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square\&logo=fastapi\&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square\&logo=postgresql\&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square\&logo=scikitlearn\&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square\&logo=docker\&logoColor=white)

</div>

---

## 💼 Engineering Experience

<table>
<tr>

<td align="center" width="33%">

### Oracle

**Software Engineering Intern**

Built a vector-embedding caching system for Oracle Analytics Cloud that reduced execution time on a dataset of more than one million records from approximately **1 hour 58 minutes to 3 minutes 58 seconds**.

Worked across caching architecture, embedding infrastructure, database integration, lifecycle management, and configuration.

</td>

<td align="center" width="33%">

### ServiceNow

**Software Engineering Intern**

Developed a backend platform feature that improved upgrade-plan creation efficiency by **15%**.

Expanded automated test coverage using Java and JUnit and contributed to platform reliability for upgrade workflows.

</td>

<td align="center" width="33%">

### Meta

**Software Engineering Intern**

Designed and built **TechHive**, a full-stack internship platform with personalized internship matching and real-time student-employer messaging.

Built across React, Node.js/Express, PostgreSQL, Socket.IO, and MongoDB.

</td>

</tr>
</table>

---

## 🧠 Research & Engineering Interests

I am increasingly interested in problems that sit between **computer science research and production systems**, particularly where rigorous experimentation can improve how intelligent software is designed and evaluated.

Current areas of interest include:

* **AI agents and long-horizon agent behavior**
* **Agent evaluation and benchmarking**
* **Graph machine learning**
* **LLM systems and tool use**
* **Retrieval, embeddings, and semantic search**
* **AI-assisted decision and recommendation systems**
* **Reliable and scalable AI infrastructure**

My goal is to continue developing both the **research intuition to investigate hard questions** and the **engineering depth to turn those ideas into usable systems**.

---

## 🧰 Technical Toolkit

### Languages

<p align="left">
<img src="https://skillicons.dev/icons?i=python,java,cpp,js,ts,html,css&perline=7" alt="Programming languages"/>
</p>

`Python` · `Java` · `C++` · `JavaScript` · `TypeScript` · `SQL` · `OCaml` · `HTML/CSS`

### Frameworks & Development

<p align="left">
<img src="https://skillicons.dev/icons?i=react,nodejs,fastapi,flutter,spring,vite&perline=6" alt="Frameworks and libraries"/>
</p>

`React` · `Node.js` · `FastAPI` · `Flutter` · `Spring` · `REST APIs` · `Socket.IO`

### Data, AI & Machine Learning

<p align="left">
<img src="https://skillicons.dev/icons?i=sklearn,postgres,mongodb,mysql&perline=4" alt="AI and data technologies"/>
</p>

`Scikit-learn` · `Vector Embeddings` · `Vector Search` · `ML-Assisted Optimization` · `Recommendation Systems` · `PostgreSQL` · `MongoDB` · `MySQL`

### Tools & Product Design

<p align="left">
<img src="https://skillicons.dev/icons?i=git,github,docker,figma,postman,linux&perline=6" alt="Development tools"/>
</p>

`Git` · `GitHub` · `Docker` · `Figma` · `Postman` · `Linux`

---

## 🌍 Community & Leadership

### 👩🏽‍💻 Girls Who Code

**Founder & President, Girls Who Code Club @ Philander Smith University**

Founded Philander Smith University's first Girls Who Code chapter in **November 2023**, growing it into an active chapter that ran for three consecutive years and engaged **15+ female students** in coding.

### 🤝 Additional Leadership & Community

* **Student Government Association** — Vice President
* **ColorStack**
* **Rewriting the Code**
* **CodePath**
* **Black Sisters in STEM**
* **HeadStart Fellowship**
* **Netflix & Formation Program**
* **Google Generation Scholar**

I care deeply about helping more students — especially women and students from underrepresented backgrounds — feel supported as they enter and grow within technology.

---

## 📊 GitHub Activity

<div align="center">

<img width="49%" src="https://github-readme-stats-drab-kappa-61.vercel.app/api?username=Ememobong28&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&theme=transparent&title_color=8B5CF6&icon_color=8B5CF6" alt="Immanuella's GitHub statistics"/>

<img width="70%" src="https://github-readme-streak-stats.herokuapp.com/?user=Ememobong28&hide_border=true&theme=transparent&ring=8B5CF6&fire=8B5CF6&currStreakLabel=8B5CF6" alt="GitHub contribution streak"/>

</div>

---

## 🐍 Contributions in Motion

<div align="center">

![Snake animation](https://raw.githubusercontent.com/Ememobong28/Ememobong28/output/github-contribution-grid-snake-dark.svg#gh-dark-mode-only)

![Snake animation](https://raw.githubusercontent.com/Ememobong28/Ememobong28/output/github-contribution-grid-snake.svg#gh-light-mode-only)

</div>

---

## 🤝 Let's Connect

I'm always interested in conversations about **software engineering, artificial intelligence, AI research, open source, research engineering, and opportunities to build technology with meaningful impact**.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/immanuella-umoren/)
[![Email](https://img.shields.io/badge/Send%20an%20Email-EA4335?style=for-the-badge\&logo=gmail\&logoColor=white)](mailto:immanuellaumoren@gmail.com)
[![GitHub](https://img.shields.io/badge/Explore%20My%20Work-181717?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/Ememobong28)

<br/>

<img src="https://komarev.com/ghpvc/?username=Ememobong28&label=Profile%20Views&color=8B5CF6&style=flat-square" alt="Profile view counter"/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:8B5CF6,50:6366F1,100:0EA5E9" alt="Footer decoration"/>

</div>
```
