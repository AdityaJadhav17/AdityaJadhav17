<div align="center">

<img src="media/banner.svg" alt="Aditya Jadhav: full-stack, AI, security" width="100%" />

**I build full-stack apps, AI agent systems and security automation, then test them.**

[![Website](https://img.shields.io/badge/Website-adityajadhav.dev-0D1117?style=flat-square&logo=safari&logoColor=white)](https://adityajadhav.dev/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Aditya%20Jadhav-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aditya-jadhav-06484123a/)
[![Email](https://img.shields.io/badge/Email-Say%20hello-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:aditya.jadhav7910@gmail.com)
[![Resume](https://img.shields.io/badge/Resume-PDF-1F6FEB?style=flat-square&logo=readme&logoColor=white)](https://adityajadhav.dev/Aditya_Jadhav_Resume.pdf)

<br>

<table>
<tr>
<td align="center" valign="top" width="25%"><h3>~30%</h3><sub>less manual security review</sub></td>
<td align="center" valign="top" width="25%"><h3>~40%</h3><sub>lower latency across AI agents</sub></td>
<td align="center" valign="top" width="25%"><h3>176</h3><sub>automated tests on Stockroom</sub></td>
<td align="center" valign="top" width="25%"><h3>0.9175</h3><sub>Kaggle mAP, synthetic to real</sub></td>
</tr>
</table>

</div>

<br>

## Now

**UC San Diego Enterprise IT** · I automated security reviews with Python, SQL and REST pipelines, cutting manual review work by about 30%. I also wrote 20+ automated tests for them.

**Lumulus Technologies** · As a software engineering intern, I build Windows tools in PySide6 for programming hardware.

**UC San Diego** · B.S. in Computer Science, graduating June 2027. Based in San Diego.

**Looking for** · Software engineering internships in full-stack, AI/ML or security.

<br>

## Projects

*Ranked by impact.*

### [WatchTower](https://github.com/cse110-sp26-group09/Watchtower-Course-Project) &nbsp;`Full-stack`
**Led the team that shipped a live monitoring platform.** As Technical Lead I owned CI/CD and architecture. Our browser SDK sends JavaScript errors, slow requests and user activity to a Node.js API, which stores them in Supabase and streams them to a Clerk-protected dashboard.

[Backend](https://watchtower-course-project-g8dv.onrender.com) · [Test app](https://cse110-sp26-group09.github.io/Watchtower-test-app/) · [Demo](https://youtu.be/tCBGQJBaOEo) &nbsp;|&nbsp; *JavaScript · Node.js · Supabase · Clerk · Jest · Playwright*

<a href="https://github.com/cse110-sp26-group09/Watchtower-Course-Project"><img src="https://adityajadhav.dev/watchtower.webp" alt="WatchTower's triage queue showing live captured JavaScript errors with severity, version and assignment" width="100%" /></a>

<br>

### [AI Travel Planner](https://github.com/AdityaJadhav17/Travel-Agntcy) &nbsp;`AI` `Full-stack`
**Cut inter-service latency by about 40%** by running the agents in Docker containers that talk over NATS. A LangGraph supervisor sends flight, hotel and activity searches to three FastAPI agents, and a React UI shows the combined plan.

[Demo](https://youtu.be/T0EkJ9J_IQU) &nbsp;|&nbsp; *Python · FastAPI · LangGraph · React · TypeScript · Docker · NATS*

<a href="https://github.com/AdityaJadhav17/Travel-Agntcy"><img src="https://adityajadhav.dev/travel-agntcy.webp" alt="Travel AGNTCY: an agent chat panel beside ranked flight options with airline, price and layover detail" width="100%" /></a>

<br>

### [Stockroom](https://github.com/AdityaJadhav17/Stockroom) &nbsp;`Full-stack` `Security`
**Wrote 165 integration tests and 11 browser tests for the purchase flow.** Members request stock and managers approve it. The app writes each stock change and its audit record in one transaction, so two requests can't sell the same item.

*C# · ASP.NET Core · EF Core · SQLite · Playwright*

<a href="https://github.com/AdityaJadhav17/Stockroom"><img src="https://adityajadhav.dev/stockroom.webp" alt="Stockroom's History page: a read-only log of purchase request events and stock movements with actor and note" width="100%" /></a>

<br>

### [Synthetic-to-Real Detection](https://github.com/AdityaJadhav17/Synthetic-to-Real-Object-Detection) &nbsp;`AI`
**Scored mAP 0.9175 (public) and 0.9074 (private) on Kaggle.** I trained YOLOv8 on synthetic images and ran domain-randomization experiments to make it work on real photos.

[Kaggle challenge](https://www.kaggle.com/competitions/synthetic-2-real-object-detection-challenge) &nbsp;|&nbsp; *Python · PyTorch · YOLOv8 · Albumentations*

<a href="https://github.com/AdityaJadhav17/Synthetic-to-Real-Object-Detection"><img src="https://adityajadhav.dev/sim2real.webp" alt="The detector finds a Cheerios box at 0.99 confidence in both a real photo and a synthetic render" width="560" /></a>

<br>

### [Talk-to-Robot](https://github.com/YangLin14/Talk-to-Robot) &nbsp;`AI`
**Reached ~98% end-to-end success on literal robot instructions.** Our team split an LLM that reads the instruction from a SAC+HER controller in MuJoCo, so you can see whether a failed push came from the language model or the policy. Success drops to 50% on functional-intent instructions.

*Python · Gemini · MuJoCo · Stable-Baselines3*

<a href="https://github.com/YangLin14/Talk-to-Robot"><img src="https://adityajadhav.dev/talk-to-robot.svg" alt="End-to-end success by instruction tier: 98.3% literal coordinates, 93.3% named regions, 76.7% relative offsets, 73.3% reference objects, 50% functional intent" width="100%" /></a>

<br>

### [Personal Tracker](https://github.com/AdityaJadhav17/Personal-Tracker) &nbsp;`Full-stack`
**Built a deadline and notes dashboard that keeps your data on your machine.** It runs in your browser with no account and no server.

*TypeScript · React · Vite*

<a href="https://github.com/AdityaJadhav17/Personal-Tracker"><img src="https://adityajadhav.dev/personal-tracker.webp" alt="Personal Tracker's Home view: today's date, one overdue item first, then the coming days with course tags" width="100%" /></a>

<details>
<summary><b>More work</b></summary>

<br>

**AI Chat Assistant (IBM Cloud).** A Watson Assistant and Node.js/Express chatbot that answered 150+ test queries at 90%+ accuracy. [Demo](https://youtu.be/9sRefMjn5Es)

**NutrifitWorld (intern, Jun to Oct 2025).** I shipped a responsive business site with CRM, scheduling and analytics.

**WatchTower team.** <br><img src="media/team-pic.jpeg" alt="UCSD CSE 110 Team 09, the WatchTower project team" width="480" />

</details>

<br>

## Toolkit

| Area | Tools |
|:--|:--|
| **Languages** | <img src="media/icons-languages.svg" alt="Python, C++, Java, C, C#, JavaScript, TypeScript" height="40" /><br><sub>+ SQL</sub> |
| **Backend** | <img src="media/icons-backend.svg" alt="FastAPI, Node.js, Express, .NET, MySQL, MongoDB, Supabase" height="40" /> |
| **Frontend** | <img src="media/icons-frontend.svg" alt="React, Vite, HTML, CSS" height="40" /> |
| **AI & Data** | <img src="media/icons-ai.svg" alt="PyTorch, TensorFlow" height="40" /><br><sub>+ LangGraph · YOLOv8 · NumPy · Pandas</sub> |
| **Infra** | <img src="media/icons-infra.svg" alt="Docker, AWS, Git, Linux, Windows, GitHub Actions" height="40" /><br><sub>+ NATS · Grafana</sub> |

<br>

<div align="center">

Email me at [aditya.jadhav7910@gmail.com](mailto:aditya.jadhav7910@gmail.com) about internships or any project above.

</div>
