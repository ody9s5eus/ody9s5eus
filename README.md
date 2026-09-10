<!--
  Profile: Odys Lee (@ody9s5eus)
  Intent: signal craft, ownership, and production judgment in under 10 seconds.
-->

<p align="center">
  <img src="./assets/banner.svg" alt="Odys Lee — Build systems people trust" width="100%" />
</p>

<p align="center">
  <a href="mailto:ody9s5eus@icloud.com"><img src="https://img.shields.io/badge/Open_to_roles-Full--stack_%2F_Platform-0A1628?style=for-the-badge&labelColor=0A1628&color=D4A574" alt="Open to roles" /></a>
</p>

<p align="center">
  <a href="https://ody9s5eus.github.io/readme-generator/"><img src="https://img.shields.io/badge/Live_tools-GitHub_Pages-0A1628?style=flat-square&labelColor=132A3A&color=D4A574" alt="Live tools" /></a>
  <a href="mailto:ody9s5eus@icloud.com"><img src="https://img.shields.io/badge/Email-ody9s5eus%40icloud.com-0A1628?style=flat-square&labelColor=132A3A&color=9BB0C2" alt="Email" /></a>
  <a href="https://github.com/ody9s5eus"><img src="https://img.shields.io/badge/GitHub-ody9s5eus-0A1628?style=flat-square&labelColor=132A3A&color=E8C9A0" alt="GitHub" /></a>
</p>

---

### Who I am

**Odys Lee** — full-stack engineer who owns the path from prototype to production.

I build product surfaces people enjoy using, and the infrastructure that keeps them reliable: APIs, data stores, CI/CD, bare-metal and cloud ops. I’ve helped startups ship fundable demos and scale past the “it works on my machine” stage — including work that contributed to **~$5M in raised capital**.

I care about **latency, correctness, and trust**. Pretty UI without a solid system underneath is just a demo.

---

### What I optimize for

| Signal | How it shows up in my work |
| --- | --- |
| **Ship velocity** | Tight loops: TypeScript end-to-end, Vite/React for UI, Node/Nest for services |
| **Production reality** | Docker, PM2, Nginx, CI/CD, Ubuntu/RHEL — not just local happy paths |
| **Data that survives** | PostgreSQL, MongoDB, Redis; schema decisions that don’t paint you into a corner |
| **Trust & privacy** | PGP messaging, TOR-aware delivery, escrow flows — security as product, not a checkbox |
| **Craft** | Tools with live demos, typed interfaces, and readable architecture |

---

### How I think about a product system

```mermaid
flowchart LR
  U[Client surfaces<br/>Web · App · Admin] --> A[API layer<br/>Node / Nest / Java]
  A --> D[(Primary data<br/>Postgres / Mongo)]
  A --> C[(Cache & sessions<br/>Redis)]
  A --> J[Jobs & media<br/>PM2 · FFmpeg]
  U --> E[Edge & access<br/>Nginx · TOR paths]
  E --> A
  A --> X[Trust flows<br/>PGP · Escrow]
```

---

### Featured work

<table>
<tr>
<td width="50%" valign="top">

#### Domestic Monerochan (DMC)
**Privacy-first community platform** · production product

Image-board style forum with account identity, **PGP-encrypted DMs**, board permissions, media, and **XMR escrow** trading flows — designed for anonymity-preserving communities.

- TOR-aware access paths  
- Server + app + ops ownership  
- [domesticmonerochan.org](https://domesticmonerochan.org)

</td>
<td width="50%" valign="top">

#### Developer tools (live)
**DX products** · TypeScript / React / Vite

Small tools that remove friction for builders — shipped with real previews, not README vaporware.

- [README Generator](https://ody9s5eus.github.io/readme-generator/) — templates + live markdown preview  
- [TS Mock Gen](https://ody9s5eus.github.io/ts-mock-gen/) — interfaces → realistic JSON  
- [Markdown → Slides](https://ody9s5eus.github.io/instant-markdown-to-slides/) — write left, present right  

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### Image Converter
**In-browser media pipeline** · React + TypeScript

Upload → resize → crop → blur/redact → export (JPEG / PNG / WebP). Privacy-sensitive edits stay on the client.

- [Repository](https://github.com/ody9s5eus/image-converter)

</td>
<td width="50%" valign="top">

#### Interaction & graphics
**Product feel experiments**

- [Interactive Task Bubble](https://ody9s5eus.github.io/interactive-task-bubble/) — Matter.js physics tasks  
- [Solar System](https://ody9s5eus.github.io/solar-system-simulation/) — Three.js / R3F  
- [Color Palette](https://ody9s5eus.github.io/color-palette-generator/) — contrast-aware generator + Vitest  

</td>
</tr>
</table>

---

### Stack (what I reach for first)

```text
Languages     TypeScript · JavaScript · Java · Swift · Kotlin
Product UI    React · Next.js · Vue · Nuxt · React Native
Services      Node.js · NestJS · Spring Boot
Data          PostgreSQL · MongoDB · Redis
Delivery      Docker · Kubernetes · Nginx · PM2 · GitHub Actions / CI
Platforms     AWS · bare-metal · Ubuntu · RHEL / CentOS
Media         FFmpeg · browser image pipelines
```

<details>
<summary><strong>Badge strip</strong> (for scanners who like logos)</summary>
<br/>

![TypeScript](https://img.shields.io/badge/TypeScript-0A1628?style=flat-square&logo=typescript&logoColor=D4A574)
![React](https://img.shields.io/badge/React-0A1628?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-0A1628?style=flat-square&logo=nextdotjs&logoColor=E8C9A0)
![Node.js](https://img.shields.io/badge/Node.js-0A1628?style=flat-square&logo=nodedotjs&logoColor=339933)
![NestJS](https://img.shields.io/badge/NestJS-0A1628?style=flat-square&logo=nestjs&logoColor=E0234E)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0A1628?style=flat-square&logo=postgresql&logoColor=4169E1)
![MongoDB](https://img.shields.io/badge/MongoDB-0A1628?style=flat-square&logo=mongodb&logoColor=47A248)
![Redis](https://img.shields.io/badge/Redis-0A1628?style=flat-square&logo=redis&logoColor=DC382D)
![Docker](https://img.shields.io/badge/Docker-0A1628?style=flat-square&logo=docker&logoColor=2496ED)
![AWS](https://img.shields.io/badge/AWS-0A1628?style=flat-square&logo=amazonaws&logoColor=FF9900)
![Kubernetes](https://img.shields.io/badge/Kubernetes-0A1628?style=flat-square&logo=kubernetes&logoColor=326CE5)

</details>

---

### Operating principles

1. **Done time beats clever time** — ship the honest MVP, then harden what users actually touch.  
2. **Own the failure domain** — if it can break in prod, I’ve already thought about logs, restarts, and rollback.  
3. **UX is a system property** — performance, permissions, and copy are part of the same design.  
4. **Security is product** — encryption, identity, and threat models belong in the roadmap, not a postmortem.

---

### Snapshot

<p align="center">
  <img height="165" src="./assets/stats.svg" alt="GitHub snapshot" />
  &nbsp;&nbsp;
  <img height="165" src="./assets/languages.svg" alt="Top languages" />
</p>

---

### Let’s build

Open to **full-stack / platform / product engineering** roles where ownership matters.

**Email:** [ody9s5eus@icloud.com](mailto:ody9s5eus@icloud.com)

> *“Runtime is important. Done time is important as well.”*
