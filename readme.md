<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0A0E14,100:0D1420&height=90&section=header"/>

<img src="./assets/banner.svg" alt="Om — Backend-Focused Full-Stack Developer" width="100%"/>

![Profile Views](https://komarev.com/ghpvc/?username=Syl3r27&color=00D9A3&style=flat-square&label=Profile+Views)
[![LeetCode](https://img.shields.io/badge/LeetCode-350%2B%20Solved-00D9A3?style=flat-square&logo=leetcode&logoColor=white&labelColor=0A0E14)](https://leetcode.com/)
[![GitHub followers](https://img.shields.io/github/followers/Syl3r27?style=flat-square&color=00D9A3&labelColor=0A0E14)](https://github.com/Syl3r27)

</div>

<br/>

### `> whoami`

- 🎓 3rd-year B.E. Computer Science (AI/ML) @ Rungta College of Engineering and Technology, Bhilai
- 🛠️ Backend-focused full-stack developer — I care more about what happens when a request fails than when it succeeds
- 🔍 Actively looking for **Software Engineering Internships**
- 🧩 Competitive programmer — 350+ problems solved, contest rating ~1620

<br/>

### `> ./run_projects.sh`

Each project below is diagrammed the way I'd actually explain it in an interview — components, data flow, and the failure mode I designed around.

<details open>
<summary><b>💸 Okane — Async Payment Processing Backend</b></summary>
<br/>

<img src="./assets/okane-architecture.svg" width="100%" alt="Okane architecture diagram"/>

`Node.js` `TypeScript` `Redis` `BullMQ` `Docker` `CI/CD`

Built around the failure modes real payment systems hit: duplicate charges, dropped jobs, half-finished writes.
- **Idempotency** — Redis-backed keys stop a retried request from double-charging
- **Durability** — BullMQ queues decouple the API from processing, so a slow worker never blocks a client
- **Reproducibility** — fully containerized, with CI/CD running the same pipeline every time

</details>

<details open>
<summary><b>🧾 Splitzy — Real-Time Expense Sharing</b></summary>
<br/>

<img src="./assets/splitzy-architecture.svg" width="100%" alt="Splitzy architecture diagram"/>

`PostgreSQL` `Inngest` `RBAC` `Event-Driven`

Every balance is **derived**, not stored — so the ledger stays correct even when events arrive out of order.
- Event-driven pipeline via Inngest handles add/edit/settle as discrete events
- PostgreSQL ledger with reconciliation logic keeps historical accuracy
- RBAC scopes who can see or modify a given group's expenses

</details>

<details open>
<summary><b>⌨️ TypeCraft — Real-Time Multiplayer Typing Platform</b></summary>
<br/>

<img src="./assets/typecraft-architecture.svg" width="100%" alt="TypeCraft architecture diagram"/>

`Socket.io` `Custom Input Engine` `Dual-Mode Auth`

- Socket.io keeps every player's screen in sync with sub-second broadcast latency
- A custom input-handling architecture drives accurate WPM/accuracy calculation
- Dual-mode auth lets people race as a guest or a full account, same room logic either way

</details>

<br/>

### `> cat tech_stack.txt`

<div align="center">

![TypeScript](https://img.shields.io/badge/-TypeScript-0A0E14?style=for-the-badge&logo=typescript&logoColor=00D9A3)
![JavaScript](https://img.shields.io/badge/-JavaScript-0A0E14?style=for-the-badge&logo=javascript&logoColor=00D9A3)
![Node.js](https://img.shields.io/badge/-Node.js-0A0E14?style=for-the-badge&logo=node.js&logoColor=00D9A3)
![C++](https://img.shields.io/badge/-C++-0A0E14?style=for-the-badge&logo=c%2B%2B&logoColor=00D9A3)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-0A0E14?style=for-the-badge&logo=postgresql&logoColor=00D9A3)
![Redis](https://img.shields.io/badge/-Redis-0A0E14?style=for-the-badge&logo=redis&logoColor=00D9A3)
![Docker](https://img.shields.io/badge/-Docker-0A0E14?style=for-the-badge&logo=docker&logoColor=00D9A3)
![Socket.io](https://img.shields.io/badge/-Socket.io-0A0E14?style=for-the-badge&logo=socket.io&logoColor=00D9A3)
![Git](https://img.shields.io/badge/-Git-0A0E14?style=for-the-badge&logo=git&logoColor=00D9A3)

</div>

<br/>

### `> stats --all`

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Syl3r27&show_icons=true&hide_border=true&count_private=true&bg_color=0A0E14&title_color=00D9A3&icon_color=00D9A3&text_color=E6E6E6&border_color=1F2937" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Syl3r27&layout=compact&hide_border=true&bg_color=0A0E14&title_color=00D9A3&text_color=E6E6E6&border_color=1F2937" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Syl3r27&hide_border=true&background=0A0E14&ring=00D9A3&fire=FFB86B&currStreakLabel=00D9A3&sideLabels=E6E6E6&currStreakNum=E6E6E6&sideNums=E6E6E6&dates=6B7280" />

<img src="https://github-profile-trophy.vercel.app/?username=Syl3r27&no-frame=true&row=1&column=6&theme=darkhub" />

</div>

<br/>

### `> git log --graph`

<div align="center">
<img src="https://raw.githubusercontent.com/Syl3r27/Syl3r27/output/snake-dark.svg" width="100%" alt="contribution snake animation"/>
<sub>Animates automatically via the included GitHub Action — see setup note below.</sub>
</div>

<br/>

### `> whats_next --status`

```text
🔭 Building:      Okane, Splitzy & TypeCraft — polishing for internship interviews
🌱 Sharpening:    DSA/CP (350+ LeetCode, rating ~1620)
🎯 Looking for:   Software Engineering Internships (Backend / Full-Stack)
💬 Ask me about:  Payment idempotency, event-driven ledgers, real-time sync
```

<br/>

### `> contact --all`

<div align="center">

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A0E14?style=for-the-badge&logo=linkedin&logoColor=00D9A3)](https://linkedin.com/in/YOUR-LINKEDIN)
[![GitHub](https://img.shields.io/badge/-GitHub-0A0E14?style=for-the-badge&logo=github&logoColor=00D9A3)](https://github.com/Syl3r27)
[![LeetCode](https://img.shields.io/badge/-LeetCode-0A0E14?style=for-the-badge&logo=leetcode&logoColor=00D9A3)](https://leetcode.com/YOUR-LEETCODE)
[![Gmail](https://img.shields.io/badge/-Email-0A0E14?style=for-the-badge&logo=gmail&logoColor=00D9A3)](mailto:YOUR-EMAIL)

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1420,100:0A0E14&height=90&section=footer"/>