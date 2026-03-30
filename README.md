<!-- ═══════════════════════════════════════════════════════════ -->
<!--                    HEADER BANNER                         -->
<!-- ═══════════════════════════════════════════════════════════ -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,30:1a1f35,60:162447,100:1f4068&height=240&section=header&text=Nattacha%20Ackahat&fontSize=60&fontColor=58a6ff&animation=fadeIn&fontAlignY=45&desc=Computer%20Science%20%E2%80%A2%20Full-Stack%20Developer%20%E2%80%A2%20AI%20Explorer&descAlignY=65&descSize=18&descColor=8b949e" width="100%"/>

</div>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                  ANIMATED TYPING + BADGES                 -->
<!-- ═══════════════════════════════════════════════════════════ -->
<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&duration=2800&pause=700&color=58A6FF&center=true&vCenter=true&width=750&lines=💻+Computer+Science+%40+KKU;🌐+Network+%26+Microservices+Engineer;🤖+AI+%2F+NLP+%2F+Machine+Learning;🎵+Creative+Web+%26+Music+Developer;🗄️+Database+Systems+%26+Backend+Dev;🏅+CCNA+Final+Exam+%3A+100+%2F+100+🥇)](https://github.com/bbthecat)

<br/>

[![Gmail](https://img.shields.io/badge/Gmail-nattacha.a%40kkumail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nattacha.a@kkumail.com)
&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-bbthecat-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/bbthecat)
&nbsp;
[![CCNA](https://img.shields.io/badge/CCNA-100%2F100%20🏅-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)](#)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=bbthecat&style=for-the-badge&color=58a6ff&label=PROFILE+VIEWS)

</div>

---

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                     WHO AM I                              -->
<!-- ═══════════════════════════════════════════════════════════ -->

<img align="right" width="400" src="https://github-readme-stats.vercel.app/api/top-langs/?username=bbthecat&layout=donut&theme=tokyonight&border_radius=10&border_color=1f6feb&title_color=58a6ff&text_color=c9d1d9&bg_color=0d1117&langs_count=8" />

## `> whoami`

```typescript
const bbthecat = {
  name:       "Nattacha Ackahat",
  university: "Khon Kaen University — Computer Science 🇹🇭",
  major:     "Computer Science (CS)",
  focus: [
    "🌐  Network Architecture",
    "🐳  Docker & Microservices",
    "🤖  AI / NLP / Machine Learning",
    "🎵  Creative Web Development",
    "🗄️  Database Systems",
  ],
  achievement: "CCNA Final Exam → 100/100 🥇",
  currentlyLearning: "Kubernetes · CI/CD · MLOps",
  funFact: "I dockerized an entire Packet Tracer lab 😎",
} as const;
```

<br clear="right"/>

---

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                 GITHUB TROPHIES                           -->
<!-- ═══════════════════════════════════════════════════════════ -->

## 🏆 Trophies

<div align="center">

[![trophy](https://github-profile-trophy.vercel.app/?username=bbthecat&theme=tokyonight&no-frame=true&no-bg=true&margin-w=6&column=7&rank=SECRET,SSS,SS,S,AAA,AA,A,B,C)](https://github.com/bbthecat)

</div>

---

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                  PROJECT SHOWCASE                         -->
<!-- ═══════════════════════════════════════════════════════════ -->

## 🚀 Projects

### 🌐 Network & Infrastructure

<table width="100%">
<tr>
<td width="55%" valign="top">

**[⚡ Network-Microservices](https://github.com/bbthecat/Network-Microservices)**

Enterprise Docker topology replacing Cisco Packet Tracer.

```
🌍 Internet (port 80 / 8000)
         │
  ┌──────▼──────────┐
  │  Nginx Gateway  │  🔒 Rate Limit · ACL · LB
  └──────┬──────────┘  172.20.0.0/24
═════════╪════════════ 🔥 Firewall
  ┌──────┴──────────────────┐
  │ [api-1]     [api-2]     │ ⚡ Zero-Downtime Failover
  │ [PostgreSQL] [Redis]    │ 🔐 Private — no external port
  │ [Loki] [Grafana]        │ 📊 Centralized Logging
  └─────────────────────────┘  172.21.0.0/24
```

</td>
<td width="45%" valign="top">

**Resiliency Results:**

| Test Case | |
|-----------|:-:|
| All containers healthy | ✅ |
| LB: 55% api-1 / 45% api-2 | ✅ |
| Zero-downtime failover (95% uptime) | ✅ |
| Rate limit → HTTP 429 on burst | ✅ |
| Redis 83% faster than DB | ✅ |
| DB port blocked externally | ✅ |
| Cluster auto-recovery | ✅ |
| **24 / 24 Tests Passed** | 🟢 |

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

</td>
</tr>
</table>

---

### 🤖 AI & Machine Learning

<table width="100%">
<tr>
<td width="50%" valign="top">

**[🎬 Movie-Sentiment-Analyzer](https://github.com/bbthecat/Movie-Sentiment-Analyzer)**  
`Python` `NLP` `Scikit-learn`

Sentiment classification engine for movie reviews.  
Text preprocessing → Feature extraction → ML model → **Positive / Negative**

</td>
<td width="50%" valign="top">

**[🧠 Brain-Net-Architecture-Specification-v1.0](https://github.com/bbthecat/Brain-Net-Architecture-Specification-v1.0)**  
`Python` `Deep Learning`

Neural network architecture specification for deep learning systems.  
⭐ **Forked by the community**

</td>
</tr>
</table>

---

### 🎨 Web & Creative

<table width="100%">
<tr>
<td width="33%" valign="top">

**[🎵 musicwave](https://github.com/bbthecat/musicwave)**

Music-themed web app with waveform visualizations and interactive audio UI.

</td>
<td width="33%" valign="top">

**[🤝 Smart_Team_Builder](https://github.com/bbthecat/Smart_Team_Builder)**  
`Python`

Smart algorithm for building balanced teams based on skills & compatibility scores.

</td>
<td width="33%" valign="top">

**[📋 Team-Info-Task-assignment](https://github.com/bbthecat/Team-Info-and-Task-assignment)**  
`CSS` `HTML`

Team management dashboard with task tracking and member profiles.

</td>
</tr>
</table>

---

### 🗄️ Database & Systems

**[💾 DBMSFinal](https://github.com/bbthecat/DBMSFinal)** — `JavaScript`  
Database Management System final project. Full CRUD, relational schema design, and modern JS frontend interface.

---

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                 CCNA SCORECARD                            -->
<!-- ═══════════════════════════════════════════════════════════ -->

## 🎓 CCNA: Introduction to Networks

<div align="center">

| # | Checkpoint Exam | Date | Score | |
|:-:|:----------------|:----:|:-----:|:-:|
| 1 | Basic Network Connectivity & Communications | 10 Jan 2026 | **94/100** | ⭐⭐⭐⭐ |
| 2 | Ethernet Concepts | 16 Jan 2026 | **100/100** | 🏅 Perfect |
| 3 | Communicating Between Networks | 23 Jan 2026 | **100/100** | 🏅 Perfect |
| 4 | IP Addressing | 20 Feb 2026 | **94/100** | ⭐⭐⭐⭐ |
| 5 | Network Application Communications | 20 Feb 2026 | **97/100** | ⭐⭐⭐⭐+ |
| 6 | Building & Securing a Small Network | 20 Feb 2026 | **94/100** | ⭐⭐⭐⭐ |
| ➕ | **Module Average** | — | **579/600** | 🔥 **96.5%** |
| 🎯 | **CCNA Final Exam** | 27 Mar 2026 | **100/100** | 🥇 **100%** |

</div>

---

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                   TECH ARSENAL                            -->
<!-- ═══════════════════════════════════════════════════════════ -->

## 🛠️ Tech Arsenal

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

**Infrastructure & DevOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Cisco](https://img.shields.io/badge/Cisco_CCNA-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)

**Database & Cache**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

**AI & Data**

![scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

**Observability & Tools**

![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![VSCode](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

</div>

---

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                   GITHUB STATS                            -->
<!-- ═══════════════════════════════════════════════════════════ -->

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=bbthecat&show_icons=true&theme=tokyonight&border_radius=10&border_color=1f6feb&title_color=58a6ff&icon_color=ff7b72&text_color=c9d1d9&bg_color=0d1117&ring_color=58a6ff&count_private=true&include_all_commits=true" height="175"/>
&nbsp;&nbsp;
<img src="https://github-readme-streak-stats.herokuapp.com/?user=bbthecat&theme=tokyonight&border_radius=10&border=1f6feb&ring=58a6ff&fire=ff7b72&currStreakLabel=58a6ff&sideLabels=8b949e&dates=8b949e&background=0d1117" height="175"/>

<br/><br/>

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=bbthecat&theme=tokyo-night&bg_color=0d1117&color=58a6ff&line=1f6feb&point=ff7b72&area=true&area_color=1f6feb&hide_border=true&radius=8)](https://github.com/bbthecat)

</div>

---

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                      FOOTER                               -->
<!-- ═══════════════════════════════════════════════════════════ -->

<div align="center">

📎 [**All Assignments PDF**](https://drive.google.com/file/d/1j078RIAKxEhTDKiFeY7rLxs90CA9mNj3/view?usp=sharing) &nbsp;·&nbsp; 📦 [**Network Lab**](https://github.com/bbthecat/Network-Microservices) &nbsp;·&nbsp; 📄 [**Lab Report**](https://github.com/bbthecat/Network-Microservices/blob/main/LAB_REPORT.md)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1f4068,50:162447,100:0d1117&height=130&section=footer&desc=Thanks%20for%20visiting!%20Let's%20build%20something%20amazing%20together%20🚀&descAlign=50&descAlignY=65&descColor=8b949e&descSize=15" width="100%"/>

</div>
