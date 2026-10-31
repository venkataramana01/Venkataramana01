<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,100:1F6FEB&height=220&section=header&text=Venkata%20Ramana%20Achuta&fontSize=44&fontColor=ffffff&fontAlignY=38&desc=Java%20Developer%20%7C%20AI%20Automation&descSize=20&descAlignY=60&animation=fadeIn" width="100%"/>

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=20&duration=2800&pause=1000&color=58A6FF&center=true&vCenter=true&width=620&lines=Java+%2B+Spring+Boot+REST+APIs;AI+Agents+and+n8n+Workflows;LLM-based+Automation" alt="Typing SVG"/>

<br/>

<a href="https://www.linkedin.com/in/venkataramanaachuta"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:venkataramanaachuta1@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<img src="https://komarev.com/ghpvc/?username=venkataramana01&label=Profile+Views&color=1F6FEB&style=for-the-badge"/>

</div>

---

## 👋 Hello

I'm a computer science student from Andhra Pradesh. I write backend services in **Java and Spring Boot**, and I build **AI automation workflows** that connect LLMs with tools people already use, such as Telegram, Gmail, and Google Sheets.

This page covers what I build, how the projects work, and what I am learning.

---

## 🧭 What I Do

<table>
<tr>
<td width="50%" valign="top">

### ☕ Backend Development
Java services with Spring Boot.

- REST APIs with CRUD operations
- Layered architecture
- JPA and Hibernate with MySQL
- Input validation and error handling

</td>
<td width="50%" valign="top">

### 🤖 AI Automation
Workflows built with n8n and LLM agents.

- Message and email classification
- Data extraction from text
- Scheduled reports and digests
- Integrations with Telegram, Gmail, Google Sheets

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=java,spring,python,javascript,react,mysql,mongodb,git,github&theme=dark" />

<br/><br/>

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![REST](https://img.shields.io/badge/REST_API-0D1117?style=for-the-badge)
![LLM](https://img.shields.io/badge/LLM_Agents-8957E5?style=for-the-badge)
![Telegram](https://img.shields.io/badge/Telegram_API-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)
![Gmail](https://img.shields.io/badge/Gmail_API-EA4335?style=for-the-badge&logo=gmail&logoColor=white)
![Sheets](https://img.shields.io/badge/Google_Sheets-34A853?style=for-the-badge&logo=googlesheets&logoColor=white)

</div>

---

## 🚀 Projects

Each project below includes a diagram of how it works. Expand a section for details.

### ☕ Task Management Service

A REST API for creating, reading, updating, and deleting tasks.

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/Spring_Data_JPA-6DB33F?style=flat-square&logo=spring&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

<p align="center"><img src="assets/task-management-flow.svg" alt="Task Management Service request flow" width="100%"/></p>

<details>
<summary><b>Details</b></summary>

<br/>

| Area | Approach |
|---|---|
| Architecture | Controller, Service, Repository layers |
| Persistence | Spring Data JPA and Hibernate, entity-to-table mapping in MySQL |
| Validation | DTO request objects with `@Valid`, `@NotBlank`, `@Size` |
| Error handling | `@RestControllerAdvice` and `@ExceptionHandler` with a custom `TaskNotFoundException` returning HTTP 404 |
| Code size | Lombok annotations remove boilerplate |

</details>

---

### 💰 AI-Powered Finance Tracker

A Telegram bot that records expenses from plain messages and sends monthly summaries.

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google_Sheets-34A853?style=flat-square&logo=googlesheets&logoColor=white)
![AI Agent](https://img.shields.io/badge/AI_Agent-1F6FEB?style=flat-square)

<p align="center"><img src="assets/finance-tracker-flow.svg" alt="AI Finance Tracker workflow" width="100%"/></p>

<details>
<summary><b>Details</b></summary>

<br/>

| Step | What happens |
|---|---|
| Input | The user sends a message to the Telegram bot |
| Classification | An AI agent labels the message as casual or financial |
| Extraction | For financial messages, the agent pulls out the transaction details |
| Storage | Transactions are saved in Google Sheets |
| Reporting | A scheduled trigger sends a monthly expense and profit summary through Telegram |

</details>

---

### 📧 AI Email Responder & Morning Digest

An email workflow that drafts replies and sends a daily summary of important mail.

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white)
![LLM](https://img.shields.io/badge/LLM-8957E5?style=flat-square)
![AI Agent](https://img.shields.io/badge/AI_Agent-1F6FEB?style=flat-square)

<p align="center"><img src="assets/email-automation-flow.svg" alt="AI Email Responder and Morning Digest workflow" width="100%"/></p>

<details>
<summary><b>Details</b></summary>

<br/>

| Feature | What it does |
|---|---|
| Reply generation | The agent analyzes the email and writes a response that fits the content |
| Morning digest | Summarizes important emails and delivers the summary each morning |
| Goal | Reduce manual email management |

</details>

---

## 📚 Currently Learning

| Topic | Focus |
|---|---|
| React | Frontend for the Spring Boot and automation projects |
| AI Agents | Tool use and multi-step workflows |
| Machine Learning | Amazon ML Summer School 2026 cohort |

---

## 🏅 Highlights

- **HBTM Hackathon**: Top 50 finisher, national-level event by IIIT Pune
- **NIT AP Hackathon**: Participant
- **Amazon ML Summer School 2026**: Selected
- **CodeChef**: 1000+ problems solved, Gold Badge
- **Certifications**: Salesforce Agentforce Specialist, Oracle AI Foundations Associate, TCS iON Young Professional

---

## 📊 GitHub Stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=venkataramana01&show_icons=true&theme=github_dark&hide_border=true&bg_color=0D1117"/>
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=venkataramana01&layout=compact&theme=github_dark&hide_border=true&bg_color=0D1117"/>

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=venkataramana01&theme=github-dark-blue&hide_border=true"/>

</div>

---

## 📬 Get in Touch

Open to Java backend and AI automation work, internships, and project collaboration.

<div align="center">

<a href="mailto:venkataramanaachuta1@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/venkataramanaachuta"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1F6FEB,100:0D1117&height=100&section=footer" width="100%"/>

</div>
