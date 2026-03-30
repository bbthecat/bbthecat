<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:21262d&height=180&section=header&text=Nattacha%20Ackahat&fontSize=48&fontColor=58a6ff&animation=fadeIn&fontAlignY=40&desc=Network%20Engineer%20%7C%20KKU%20%7C%20CCNA%20Track&descAlignY=60&descColor=8b949e&stroke=58a6ff&strokeWidth=1" width="100%"/>
</div>

<br/>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=Network+%26+Microservices+Engineer;CCNA+Final+Exam+%3A+100%2F100+%F0%9F%8E%93;Docker+%7C+Nginx+%7C+PostgreSQL+%7C+Redis;Khon+Kaen+University+%F0%9F%8E%93)](https://github.com/bbthecat)

</div>

<br/>

<div align="center">

[![Email](https://img.shields.io/badge/📧-nattacha.a@kkumail.com-0078D4?style=for-the-badge&logoColor=white)](mailto:nattacha.a@kkumail.com)
&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-bbthecat-181717?style=for-the-badge&logo=github)](https://github.com/bbthecat)
&nbsp;
[![Cisco](https://img.shields.io/badge/CCNA-100%2F100-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)](https://github.com/bbthecat/Network-Microservices)

</div>

---

## 🏆 CCNA: Introduction to Networks — Academic Results

<div align="center">

```
┌─────────────────────────────────────────────────────────────┐
│              🎓 COURSE SCORECARD                            │
│─────────────────────────────────────────────────────────────│
│  Module Group Exams        579 / 600   ██████████  96.5%   │
│  Final Exam                100 / 100   ██████████  100%    │
└─────────────────────────────────────────────────────────────┘
```

| Checkpoint Exam | Date | Score |
|-----------------|------|:-----:|
| Basic Network Connectivity & Communications | 10 Jan 2026 | **94/100** ⭐ |
| Ethernet Concepts | 16 Jan 2026 | **100/100** 🏅 |
| Communicating Between Networks | 23 Jan 2026 | **100/100** 🏅 |
| IP Addressing | 20 Feb 2026 | **94/100** ⭐ |
| Network Application Communications | 20 Feb 2026 | **97/100** ⭐ |
| Building & Securing a Small Network | 20 Feb 2026 | **94/100** ⭐ |
| 🎯 **CCNA Introduction to Networks — Final** | 27 Mar 2026 | **100/100** 🥇 |

</div>

---

## 🚀 Featured Project

<a href="https://github.com/bbthecat/Network-Microservices">
  <img align="left" src="https://github-readme-stats.vercel.app/api/pin/?username=bbthecat&repo=Network-Microservices&theme=github_dark&border_color=30363d&title_color=58a6ff&icon_color=58a6ff&text_color=8b949e" />
</a>

<br clear="left"/>

> **Lab 7** — Docker-based topology replacing Cisco Packet Tracer  
> Nginx Edge Gateway → 2× API (Failover) → PostgreSQL + Redis → Loki Logging

```
 Internet ──► [Nginx: port 8000]  ← Rate Limit 10r/s · ACL · Load Balancer
                      │  172.20.0.0/24 (frontend-dmz)
    ══════════════════╪══════════════ 🔥 FIREWALL
                      │  172.21.0.0/24 (backend-secure, internal=true)
             ┌────────┴─────────┐
          [api-1]           [api-2]   ← Zero-Downtime Failover
             └────────┬─────────┘
               [PostgreSQL] [Redis]   ← Data Tier (ports PRIVATE)
               [Loki] [Grafana]       ← Centralized Logging (ms timestamps)
```

<div align="center">

| Test | Result |
|------|:------:|
| ✅ All containers healthy | PASS |
| ✅ Load balancer: api-1 55% / api-2 45% | PASS |
| ✅ Zero-downtime failover (95% uptime during stop) | PASS |
| ✅ Rate limit HTTP 429 on burst | PASS |
| ✅ Redis cache 83% faster than DB (8ms vs 47ms) | PASS |
| ✅ Cluster recovery after restart | PASS |
| **Total** | **24/24** 🟢 |

</div>

**Assignments:** 📎 [All Assignments PDF](https://drive.google.com/file/d/1j078RIAKxEhTDKiFeY7rLxs90CA9mNj3/view?usp=sharing) &nbsp;|&nbsp; 📄 [Lab Report](https://github.com/bbthecat/Network-Microservices/blob/main/LAB_REPORT.md)

---

## 🛠️ Tech Stack

<div align="center">

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Cisco](https://img.shields.io/badge/Cisco_CCNA-1BA0D7?style=flat-square&logo=cisco&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css3&logoColor=white)

</div>

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=bbthecat&show_icons=true&theme=github_dark&border_color=30363d&title_color=58a6ff&icon_color=58a6ff&text_color=8b949e&hide_border=false&count_private=true" height="160"/>
&nbsp;&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=bbthecat&layout=compact&theme=github_dark&border_color=30363d&title_color=58a6ff&text_color=8b949e&hide_border=false" height="160"/>

</div>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=bbthecat&theme=github-dark-blue&border=30363d&ring=58a6ff&fire=ff7b72&currStreakLabel=58a6ff" height="160"/>

</div>

---

<div align="center">

*🎓 CCNA Final: **100/100** &nbsp;·&nbsp; 📡 Network Engineering @ KKU &nbsp;·&nbsp; 🏅 Module Average: **96.5%***

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:21262d,50:161b22,100:0d1117&height=100&section=footer" width="100%"/>

</div>
