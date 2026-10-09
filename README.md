<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1220,50:1E3A8A,100:2563EB&height=210&section=header&text=Abishek%20Paudel&fontSize=54&fontColor=FFFFFF&fontAlignY=36&desc=Backend%20Software%20Engineer%20%C2%B7%20Distributed%20Systems&descSize=19&descAlignY=57&animation=fadeIn" alt="Abishek Paudel, Backend Software Engineer" />

<a href="https://github.com/abishekpaudel">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=3000&pause=1000&color=3B82F6&center=true&vCenter=true&width=640&height=40&lines=High-performance+APIs+and+microservices;Event-driven+systems+with+RabbitMQ+and+Redis;PostgreSQL+design+and+query+optimization;Master's+student+in+Software+Engineering+at+MUN" alt="What I do" />
</a>

<br/>

<a href="https://www.linkedin.com/in/abishek-paudel-72a43b1b2/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:abishekpaudel56@gmail.com"><img src="https://img.shields.io/badge/Email-1E3A8A?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<img src="https://img.shields.io/badge/St.%20John's%2C%20Canada-0B1220?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location" />

</div>

<br/>

## About Me

I am a backend software engineer and a Master's student in Software Engineering at Memorial University of Newfoundland. Before moving to Canada, I spent five years at SWIFT Technology, growing from intern to full-time Software Engineer and building production backends used every day.

I care about systems that stay correct and available under load: well-designed APIs, reliable messaging, fast queries, and failures that are handled instead of hidden.

<table>
<tr>
<td width="50%" valign="top">

**Currently**

- Master's student, Software Engineering, Memorial University of Newfoundland
- Studying distributed systems and software architecture
- Exploring Kubernetes, event sourcing, and CQRS

</td>
<td width="50%" valign="top">

**Open to**

- Internships and co-op placements
- Full-time backend engineering roles
- Open-source collaboration and system design discussions

</td>
</tr>
</table>

## Career Timeline

| Period | Role | Organization |
| :--- | :--- | :--- |
| **Sep 2026 – Present** | Master's Student, Software Engineering | Memorial University of Newfoundland, Canada |
| **Jan 2023 – Jul 2026** | Software Engineer (full-time) | SWIFT Technology, Nepal |
| **2022 – 2023** | Trainee Software Engineer (part-time) | SWIFT Technology, Nepal |
| **2021** | Software Engineering Intern (part-time) | SWIFT Technology, Nepal |

## Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=nodejs,ts,js,cpp,express,postgres,redis,rabbitmq,docker,nginx,linux,git&perline=6" alt="Tech stack" />

<br/><br/>

<img src="https://img.shields.io/badge/gRPC-244C5A?style=for-the-badge&logo=google&logoColor=white" alt="gRPC" />
<img src="https://img.shields.io/badge/REST%20API-1E3A8A?style=for-the-badge&logo=openapiinitiative&logoColor=white" alt="REST API" />
<img src="https://img.shields.io/badge/WebSockets-0B1220?style=for-the-badge&logo=socketdotio&logoColor=white" alt="WebSockets" />
<img src="https://img.shields.io/badge/Sequelize-52B0E7?style=for-the-badge&logo=sequelize&logoColor=white" alt="Sequelize" />

</div>

## How I Design Systems

```mermaid
flowchart LR
    C[Clients] --> N[Nginx<br/>Load Balancer]
    N --> A[API Service<br/>REST · Node.js]
    A -- gRPC --> S1[Domain Service]
    A -- gRPC --> S2[Domain Service]
    A --> R[(Redis<br/>Cache)]
    S1 --> P[(PostgreSQL)]
    S2 --> P
    S1 -- publish --> Q{{RabbitMQ}}
    Q --> W[Async Workers]
    Q -. failed .-> D[Dead-Letter Queue]
    W --> P
```

| Principle | In practice |
| :--- | :--- |
| **Resilience** | Circuit breakers, retries with backoff, graceful degradation, health checks |
| **Scalability** | Stateless services, horizontal scaling, load balancing, connection pooling |
| **Performance** | Redis caching, query optimization, strategic indexing, async processing |
| **Messaging** | Pub/sub, dead-letter queues, idempotent consumers |
| **Observability** | Structured logging, metrics, tracing, alerting |

## Featured Projects

<!-- TODO: Replace with 2-3 real projects and pin the same repos on your profile.
     For each: what it does, the hard problem, and one measured result. -->

| Project | What it does | Stack |
| :--- | :--- | :--- |
| **[Project name](https://github.com/abishekpaudel/REPO)** | What it does, the hardest problem you solved, and one measured result. | `TypeScript` `PostgreSQL` `RabbitMQ` |
| **[Project name](https://github.com/abishekpaudel/REPO)** | What it does, the hardest problem you solved, and one measured result. | `Node.js` `gRPC` `Redis` |

## GitHub Activity

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=abishekpaudel&show_icons=true&include_all_commits=true&hide_border=true&bg_color=0B1220&title_color=3B82F6&text_color=CBD5E1&icon_color=3B82F6&ring_color=3B82F6" alt="GitHub stats" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=abishekpaudel&layout=compact&langs_count=6&hide_border=true&bg_color=0B1220&title_color=3B82F6&text_color=CBD5E1" alt="Top languages" />

<br/>

<img width="62%" src="https://streak-stats.demolab.com?user=abishekpaudel&hide_border=true&background=0B1220&stroke=1E3A8A&ring=3B82F6&fire=3B82F6&currStreakNum=FFFFFF&sideNums=FFFFFF&currStreakLabel=3B82F6&sideLabels=CBD5E1&dates=64748B" alt="GitHub streak" />

</div>

## Get in Touch

<div align="center">

I am always glad to talk about backend engineering, system design, or a role where I can contribute.

<a href="https://www.linkedin.com/in/abishek-paudel-72a43b1b2/"><img src="https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Connect on LinkedIn" /></a>
<a href="mailto:abishekpaudel56@gmail.com"><img src="https://img.shields.io/badge/Send%20an%20Email-1E3A8A?style=for-the-badge&logo=gmail&logoColor=white" alt="Send an email" /></a>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1220,50:1E3A8A,100:2563EB&height=110&section=footer" alt="" />

</div>
