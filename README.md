<h2 align="center">Raghav Sharma</h2>

<p align="center">
Backend Developer &nbsp;·&nbsp; Java &nbsp;·&nbsp; Spring Boot &nbsp;·&nbsp; REST APIs &nbsp;·&nbsp; SQL
</p>

<p align="center">
  <a href="https://linkedin.com/in/raghav-sharma-478191270">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://leetcode.com/u/RaghavSharma03/">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" />
  </a>
  &nbsp;
  <a href="https://www.hackerrank.com/profile/22BCON1062">
    <img src="https://img.shields.io/badge/HackerRank-2EC866?style=for-the-badge&logo=hackerrank&logoColor=white" />
  </a>
  &nbsp;
  <a href="mailto:raghavv.s2003@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

---

I am a final-year CSE student at JECRC University (8.7 GPA) who builds backends that are meant to hold up under real conditions — not just work on localhost.

Most of my projects started with a question I couldn't answer yet. The machine events system came from wanting to understand how concurrent writes actually fail and how to prevent them at the database level. The appointment scheduler came from noticing how poorly most booking systems handle the simple question of *"when is the next available slot?"* I don't build to complete tasks. I build until I understand what I built.

I write Java for production-grade systems and TypeScript when the problem calls for it. I care about correctness, thread safety, clean schema design, and tests that actually test something.

Currently looking for backend developer roles where I can contribute from day one.

---

## Stack

**Primary**

![Java](https://img.shields.io/badge/Java_17%2F21-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/Spring_Data_JPA-6DB33F?style=flat-square&logo=spring&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**Also worked with**

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![TypeORM](https://img.shields.io/badge/TypeORM-FE0803?style=flat-square&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white)
![JUnit5](https://img.shields.io/badge/JUnit5-25A162?style=flat-square&logo=junit5&logoColor=white)
![H2](https://img.shields.io/badge/H2_In--Memory-0000BB?style=flat-square&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apache-maven&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-000000?style=flat-square&logo=intellij-idea&logoColor=white)

---

## Projects

### [Machine Event Processing System](https://github.com/Raghav-Sharma03/DemoMachine-Events)

Built to handle factory-floor machine events at high throughput. The core challenge was deduplication under concurrent load — solved using SHA-256 payload hashing combined with DB-level unique constraints and `@Transactional` boundaries so no two threads could write the same event simultaneously.

Benchmarked at **1,000+ events/sec** on local hardware with zero duplicate entries across all concurrent test runs. Covered with 8+ JUnit 5 tests — deduplication logic, time-window queries, update precedence, and concurrency scenarios.

`Java 17` `Spring Boot` `Spring Data JPA` `H2` `JUnit 5`

---

### [Doctor Appointment Scheduling System](https://github.com/Raghav-Sharma03/appointment-scheduler)

The problem with most appointment systems is they just say "today is full" and stop there. This one doesn't. It automatically finds the next available slot across days, handles emergency bookings with reserved slots, and reallocates freed slots the moment a cancellation happens.

Built with three real scheduling models used in actual clinics — Stream, Wave, and Modified Wave. Developed over 5 days with 21 commits, from auth to booking logic to full API documentation.

`NestJS` `TypeScript` `PostgreSQL` `TypeORM` `JWT`

---

### [Public Grievance Tracker](https://github.com/Raghav-Sharma03/public-grievance-tracker)

A complaint resolution system with full role separation — Citizens submit and track, Admins assign and resolve. Access control is enforced at the controller level using Spring Security, not just hidden in the UI. Unauthorised routes are blocked server-side regardless of what the frontend shows.

Complaint lifecycle tracked end to end: Submitted → Assigned → In Progress → Resolved. Schema is normalised with proper foreign key relationships managed via JPA/Hibernate.

`Java` `Spring Boot` `Spring Security` `MySQL` `JPA` `Thymeleaf`

---

## Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Raghav-Sharma03&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true&hide_title=true" height="160" />
  &nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Raghav-Sharma03&layout=compact&theme=github_dark&hide_border=true" height="160" />
</p>

---

## Outside of Projects

- Solved **300+ DSA problems** across LeetCode, HackerRank, and GFG
- **4-star rating** on HackerRank — Problem Solving and SQL (top 15% platform-wide)
- Oracle Cloud Infrastructure 2025 AI Foundations — Certified
- HPE Software Engineering Job Simulation — Certified
- Promoted from Volunteer to Coordinator at JU Rhythm (2,000+ attendees) — learned that leading under a hard deadline is its own kind of problem-solving

---

> Actively looking for backend developer roles. If my work looks relevant to what your team is building, reach out at **raghavv.s2003@gmail.com**
