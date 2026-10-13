<div align="center">

# Mak &nbsp;🦕

**Computer Science graduate &nbsp;·&nbsp; Software & Cloud Engineer &nbsp;·&nbsp; Al Khor, Qatar**

`Python · Java · Rust · TypeScript · AWS Lambda · FastAPI · Flask · Docker`

![Based in Qatar](https://img.shields.io/badge/Based_in-Qatar-0D9488?style=flat)
&nbsp;
![Valid QID](https://img.shields.io/badge/Valid_QID-no_relocation_needed-0D9488?style=flat)
&nbsp;
![Open to work](https://img.shields.io/badge/Open_to-SE_%26_Cloud_roles-F59E0B?style=flat)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-mak2025-0D9488?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/mak2025)
&nbsp;
[![Email](https://img.shields.io/badge/Email-mak252321%40gmail.com-0D9488?style=flat&logo=gmail&logoColor=white)](mailto:mak252321@gmail.com)
&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-Mak--beth-0D9488?style=flat&logo=github&logoColor=white)](https://github.com/Mak-beth)

</div>

---

## About

Computer Science graduate (Asia Pacific University, 2026) with production engineering experience and hands-on AWS delivery. I spent five months as a Software Engineering Intern at Joget Technology in Malaysia, shipping three production Java plugins to a live enterprise marketplace, cutting one codebase by ~40% through consolidating duplicate class logic, and integrating the platform with four enterprise databases under Docker. My core strengths are backend development, Python, Java, REST API design, and serverless architecture on AWS.

I got into software engineering because I wanted to build things that actually run in production, not just in theory. CyberMon is the clearest example — an 11,000+ line desktop SIEM alternative with a config-driven risk scoring engine, a client-server agent mode, and 318 passing tests at 13,400 events/second with zero false positives, built end to end by me. More recently I deployed a 13-endpoint serverless REST API on Lambda, API Gateway and RDS, which is where my focus is heading next. That drive to ship complete, tested, documented software is what I bring to every project.

Outside of work I'm into gaming, following the tech industry, and exploring whatever new tool or language catches my eye — that's how Rust ended up in my portfolio. I'm based in Al Khor, Qatar, I grew up here, and I'm genuinely excited to build my career in the region I call home. Valid QID, immediately available, no visa or relocation required.

---

## Fossil Record

<details>
<summary><strong>☁️ Accessibility Accommodation Portal &nbsp;—&nbsp; Serverless AWS Application</strong></summary>
<br>

A serverless accommodation-request platform built end to end on AWS. Deployed a **13-endpoint REST API** on **Lambda** behind **API Gateway**, backed by **Amazon RDS for MySQL** through SQLAlchemy ORM.

File traffic is kept off the API tier entirely — browsers upload directly to **S3** via pre-signed URLs issued by a dedicated Lambda endpoint. The data model is a 4-table schema with UUID keys, enum-constrained roles, and an allocation guard that blocks duplicate budget disbursement.

The frontend is a **React 19** single-page app with role-scoped dashboards for four distinct user types (student, faculty, finance, admin), driven by the same role model enforced server-side.

**Stack:** AWS Lambda · API Gateway · RDS (MySQL) · S3 · FastAPI · SQLAlchemy · React 19 · Vite · Tailwind CSS

[![Repo](https://img.shields.io/badge/View_Repo-0D9488?style=flat&logo=github&logoColor=white)](https://github.com/Mak-beth/Accessibility-Accommodation-Portal-)

</details>

<details>
<summary><strong>🛡️ CyberMon &nbsp;—&nbsp; Desktop Security Monitoring Platform</strong></summary>
<br>

An **11,000+ line** desktop SIEM alternative covering Linux syslog, Windows OpenSSH and Apache logs. Three detection rules feed a config-driven **1–25 likelihood × impact** scoring engine, with findings persisted to SQLite for querying and visualization.

Also runs in **client-server mode**: remote agents POST log batches to a Flask endpoint secured by `X-API-Key` auth, and detection state carries across batches — so a slow brute-force spread thin over hours still gets caught.

Benchmarked at **13,400 events/second** on real LogHub data with **318 passing pytest tests** and zero false positives. Ships as two self-contained Windows executables via PyInstaller.

**Stack:** Python 3.12 · PyQt6 · PyQtGraph · Flask · SQLite · pandas · pytest · PyInstaller

[![Repo](https://img.shields.io/badge/View_Repo-0D9488?style=flat&logo=github&logoColor=white)](https://github.com/Mak-beth/Cybermon)

</details>

<details>
<summary><strong>⚙️ RTS Wiki Pipeline &nbsp;—&nbsp; Real-Time Stream Processor</strong></summary>
<br>

A dual-architecture **Rust** pipeline consuming live Wikimedia SSE streams, built to compare async (**Tokio**) against threaded concurrency on identical workloads. Uses zero-copy parsing and a custom allocator achieving **≥95% zero-allocation per event**, benchmarked with Criterion.

**Stack:** Rust · Tokio · Crossbeam · Criterion

[![Repo](https://img.shields.io/badge/View_Repo-0D9488?style=flat&logo=github&logoColor=white)](https://github.com/Mak-beth/RTS_Wiki_Pipeline)

</details>

<details>
<summary><strong>🔗 Decentralized Marketplace &nbsp;—&nbsp; Blockchain Web Application</strong></summary>
<br>

**Solidity** smart contracts deployed via Hardhat to a local Ethereum testnet, with a **Next.js / TypeScript** frontend and MetaMask wallet integration covering listing and purchase flows.

**Stack:** Solidity · Hardhat · Next.js · TypeScript

[![Repo](https://img.shields.io/badge/View_Repo-0D9488?style=flat&logo=github&logoColor=white)](https://github.com/Mak-beth/BC_DAPP)

</details>

<details>
<summary><strong>🏢 CrestHRM &nbsp;—&nbsp; Distributed HR Management System</strong></summary>
<br>

A distributed Human Resource Management system architected in **Java RMI**, with remote method invocation across nodes and fault-tolerant service design.

**Stack:** Java · RMI

[![Repo](https://img.shields.io/badge/View_Repo-0D9488?style=flat&logo=github&logoColor=white)](https://github.com/Mak-beth/CrestHRMSystem)

</details>

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-0D9488?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-0D9488?style=flat&logo=openjdk&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-0D9488?style=flat&logo=rust&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-0D9488?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-0D9488?style=flat&logo=javascript&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-0D9488?style=flat&logo=solidity&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-0D9488?style=flat&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-0D9488?style=flat&logo=gnubash&logoColor=white)

**Web, API & Frameworks**

![FastAPI](https://img.shields.io/badge/FastAPI-0D9488?style=flat&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-0D9488?style=flat&logo=flask&logoColor=white)
![React](https://img.shields.io/badge/React-0D9488?style=flat&logo=react&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-0D9488?style=flat&logo=nextdotjs&logoColor=white)
![PyQt6](https://img.shields.io/badge/PyQt6-0D9488?style=flat&logo=qt&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-0D9488?style=flat&logo=tailwindcss&logoColor=white)

**Cloud & DevOps**

![AWS Lambda](https://img.shields.io/badge/AWS_Lambda-0D9488?style=flat&logo=awslambda&logoColor=white)
![API Gateway](https://img.shields.io/badge/API_Gateway-0D9488?style=flat&logo=amazonapigateway&logoColor=white)
![Amazon RDS](https://img.shields.io/badge/Amazon_RDS-0D9488?style=flat&logo=amazonrds&logoColor=white)
![Amazon S3](https://img.shields.io/badge/Amazon_S3-0D9488?style=flat&logo=amazons3&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-0D9488?style=flat&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-0D9488?style=flat&logo=linux&logoColor=white)
![Git](https://img.shields.io/badge/Git-0D9488?style=flat&logo=git&logoColor=white)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0D9488?style=flat&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-0D9488?style=flat&logo=mysql&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-0D9488?style=flat&logo=mariadb&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-0D9488?style=flat&logo=oracle&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-0D9488?style=flat&logo=sqlite&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-0D9488?style=flat&logo=sqlalchemy&logoColor=white)

**Certifications**

![Rocheston](https://img.shields.io/badge/Rocheston_Cybersecurity_L1-earned_2024-0D9488?style=flat&logo=shieldsdotio&logoColor=white)
&nbsp;
![AWS CLF-C02](https://img.shields.io/badge/AWS_Cloud_Practitioner-in_progress-F59E0B?style=flat&logo=amazonwebservices&logoColor=white)

---

## GitHub Analytics

<div align="center">

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Mak-beth&show_icons=true&theme=transparent&title_color=0D9488&icon_color=F59E0B&hide_border=false&border_color=0D9488&count_private=true)](https://github.com/Mak-beth)
&nbsp;
[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Mak-beth&layout=compact&theme=transparent&title_color=0D9488&hide_border=false&border_color=0D9488&langs_count=8)](https://github.com/Mak-beth)

</div>

---

## Contribution Art

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/Mak-beth/Mak-beth/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/Mak-beth/Mak-beth/output/github-contribution-grid-snake.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/Mak-beth/Mak-beth/output/github-contribution-grid-snake.svg" />
</picture>

<br/>

![Pac-Man contribution graph](https://raw.githubusercontent.com/Mak-beth/Mak-beth/output/pacman-contribution-graph.svg)

</div>

---

<div align="center">

*🦕 Fun fact: I like dinosaurs — fossils are just nature's version control.*

</div>
