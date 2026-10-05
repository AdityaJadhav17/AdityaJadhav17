<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=140&color=0:0D1117,100:1F6FEB&section=header&text=Aditya%20Jadhav&fontColor=ffffff&fontSize=44&fontAlignY=42&desc=Full-stack%20%C2%B7%20AI%20%C2%B7%20Security&descSize=16&descAlignY=64" alt="Aditya Jadhav: full-stack, AI, security" width="100%" />

**I'm a computer science student at UC San Diego. I build full-stack apps, AI agent systems and security automation, and I write the tests that check them.**

[![Website](https://img.shields.io/badge/Website-adityajadhav.dev-0D1117?style=flat-square&logo=safari&logoColor=white)](https://adityajadhav.dev/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Aditya%20Jadhav-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aditya-jadhav-06484123a/)
[![Email](https://img.shields.io/badge/Email-Say%20hello-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:aditya.jadhav7910@gmail.com)
[![Resume](https://img.shields.io/badge/Resume-PDF-1F6FEB?style=flat-square&logo=readme&logoColor=white)](https://adityajadhav17.github.io/Aditya_Jadhav_Resume.pdf)

</div>

<br>

## Now

|  |  |
|:--|:--|
| **UC San Diego Enterprise IT** | I automate security reviews with Python, SQL and REST services. The pipelines cut manual review effort by about 30%, and I added 20+ automated tests. |
| **Lumulus Technologies** | As a software engineering intern, I build Windows tools in PySide6 that program hardware. |
| **UC San Diego** | B.S. in Computer Science, graduating June 2027. Based in San Diego. |
| **Looking for** | Software engineering internships in full-stack, AI/ML or security. |

<br>

## Projects

*Ranked by impact.*

<table>
<tr>
<td width="50%" valign="top">
<img src="media/team-pic.jpeg" alt="UCSD CSE 110 Team 09, the WatchTower project team" width="100%" />
</td>
<td width="50%" valign="top">

### [WatchTower](https://github.com/cse110-sp26-group09/Watchtower-Course-Project)
`Full-stack`

A monitoring tool that catches JavaScript errors, slow requests and user activity on a website. I led the team as Technical Lead and owned CI/CD and architecture. We built a browser SDK, a Node.js ingest API, a Supabase/Postgres store and a Clerk-protected live dashboard, and tested them with Jest and Playwright.

**Impact:** the team shipped it with a live backend.<br>
[Backend](https://watchtower-course-project-g8dv.onrender.com) · [Test app](https://cse110-sp26-group09.github.io/Watchtower-test-app/) · [Demo](https://youtu.be/tCBGQJBaOEo)

<img src="https://skillicons.dev/icons?i=js,nodejs,supabase,jest,playwright&theme=dark" alt="JavaScript, Node.js, Supabase, Jest, Playwright" />

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [AI Travel Planner](https://github.com/AdityaJadhav17/Travel-Agntcy)
`AI` `Full-stack`

A LangGraph supervisor sends flight, hotel and activity searches to separate agents. Each agent runs as a FastAPI service, and a React UI shows the combined plan. Services talk over NATS, and Grafana and ClickHouse track their health.

**Impact:** containerized services on NATS cut inter-service latency by about 40%. [Demo](https://youtu.be/T0EkJ9J_IQU)

<img src="https://skillicons.dev/icons?i=python,fastapi,react,ts,docker,grafana&theme=dark" alt="Python, FastAPI, React, TypeScript, Docker, Grafana" />

</td>
<td width="50%" valign="top">

### [Stockroom](https://github.com/AdityaJadhav17/Stockroom)
`Full-stack` `Security`

An inventory app where members request purchases and managers approve them. Roles control who can do what, and every stock change lands in an audit history. Each change and its record commit in one transaction. Conditional updates stop two requests from selling the same stock.

**Impact:** 165 integration tests and 11 browser tests cover business rules, authorization, race conditions and rollback.

<img src="https://skillicons.dev/icons?i=cs,dotnet,sqlite,githubactions&theme=dark" alt="C#, .NET, SQLite, GitHub Actions" />

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Synthetic-to-Real Detection](https://github.com/AdityaJadhav17/Synthetic-to-Real-Object-Detection)
`AI`

A YOLOv8 pipeline for a Kaggle challenge where models train on synthetic images and run on real photos. I ran augmentation and domain-randomization experiments and wrote the submission tooling.

**Impact:** public mAP **0.9175**, private mAP **0.9074**. [Kaggle challenge](https://www.kaggle.com/competitions/synthetic-2-real-object-detection-challenge)

<img src="https://skillicons.dev/icons?i=python,pytorch&theme=dark" alt="Python, PyTorch" />

</td>
<td width="50%" valign="top">

### [Talk-to-Robot](https://github.com/YangLin14/Talk-to-Robot)
`AI`

Our team split a robot-control system into an LLM that reads the instruction and a SAC+HER controller in MuJoCo that moves the arm. The split shows whether a failed push came from the language model or the policy.

**Impact:** ~98% and ~93% end-to-end success on literal and region instructions, dropping on relative and intent-based ones.

<img src="https://skillicons.dev/icons?i=python,pytorch&theme=dark" alt="Python, PyTorch" />

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Personal Tracker](https://github.com/AdityaJadhav17/Personal-Tracker)
`Full-stack`

A dashboard for deadlines, notes, routines and goals. It runs in your browser on your machine. It needs no account and no server, and your data stays local.

<img src="https://skillicons.dev/icons?i=ts,react,vite&theme=dark" alt="TypeScript, React, Vite" />

</td>
<td width="50%" valign="top">

### More work
**AI Chat Assistant (IBM Cloud).** A Watson Assistant and Node.js/Express chatbot. It answered 150+ test queries at 90%+ accuracy. [Demo](https://youtu.be/9sRefMjn5Es)

**NutrifitWorld (intern, Jun to Oct 2025).** I shipped a responsive business site with CRM, scheduling and analytics.

</td>
</tr>
</table>

<br>

## Toolkit

|  |  |
|:--|:--|
| **Languages** | <img src="https://skillicons.dev/icons?i=py,cpp,java,c,cs,js,ts&theme=dark" alt="Python, C++, Java, C, C#, JavaScript, TypeScript, SQL" /> |
| **Backend** | <img src="https://skillicons.dev/icons?i=fastapi,nodejs,express,dotnet,mysql,mongodb,supabase&theme=dark" alt="FastAPI, Node.js, Express, .NET, MySQL, MongoDB, Supabase" /> |
| **Frontend** | <img src="https://skillicons.dev/icons?i=react,vite,html,css&theme=dark" alt="React, Vite, HTML, CSS" /> |
| **AI & Data** | <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,numpy,pandas&theme=dark" alt="PyTorch, TensorFlow, NumPy, Pandas" /> |
| **Infra** | <img src="https://skillicons.dev/icons?i=docker,aws,git,linux,windows,githubactions&theme=dark" alt="Docker, AWS, Git, Linux, Windows, GitHub Actions" /> |

<br>

## Activity

<div align="center">

<a href="https://github.com/AdityaJadhav17"><img height="170" src="https://github-readme-stats.vercel.app/api?username=AdityaJadhav17&show_icons=true&hide_border=true&theme=transparent&title_color=1F6FEB&icon_color=1F6FEB&text_color=8B949E" alt="GitHub stats" /></a>
<a href="https://github.com/AdityaJadhav17?tab=repositories"><img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AdityaJadhav17&layout=compact&hide_border=true&theme=transparent&title_color=1F6FEB&text_color=8B949E" alt="Top languages" /></a>

<br>

Email me at [aditya.jadhav7910@gmail.com](mailto:aditya.jadhav7910@gmail.com). I'd rather talk shop than read a pitch.

</div>
