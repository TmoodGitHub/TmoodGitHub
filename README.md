# Hi, I'm Tamer Mahmoud 👋

**Software Engineer · Backend, Cloud & Data Systems · Northern Virginia · Open to Remote**

Full stack engineer building production systems: cloud services, data pipelines, microservices and APIs, and databases. That includes system design, untangling legacy systems, and building software and SaaS products that real people use every day. Lately I've been building with LLMs: retrieval (RAG), vision models, structured output, and AI-assisted triage. I use AI coding tools every day and review what they produce as carefully as any other code. I'm also an AWS Certified Solutions Architect - Associate, which backs up my work in cloud architecture.

---

## Projects

### 🛡️ AI Security Triage *(in progress)*
[GitHub Repo](https://github.com/TmoodGitHub/ai-security-triage)

AI-assisted triage of AWS security logs. It takes in CloudTrail events, cleans them into one standard format, removes duplicates, and stores them in PostgreSQL. For each finding, an LLM looks up related threat information and suggests a severity level with a short explanation. An analyst reviews every suggestion before anything is acted on. Planned next: a Findings API, an analyst screen, accuracy tests for the AI step, AWS infrastructure in Terraform, and tests on every push with GitHub Actions.

`TypeScript` `Node.js` `Python` `PostgreSQL` `AWS (Lambda, SQS, S3)` `Terraform` `Vitest`

---

### 🌿 Plant Health Predictor
[GitHub Repo](https://github.com/TmoodGitHub/plant-health-predictor)

Upload 2 to 10 photos of a plant taken over time and get back a health report. It identifies the plant (common name, scientific name, and family), scores each photo for health signs, finds trends across the whole set, and predicts where the plant is heading over the next 7 to 14 days, with recommended actions. The model's output is checked against a schema, with retries, rate limiting, and separate sessions per user. Reports can be exported.

`Node.js` `Express` `Anthropic Claude API` `Vision AI` `Multer` `Prompt engineering`

---

### 🔧 tmoodgit
[GitHub Repo](https://github.com/TmoodGitHub/tmoodgit)

Git, built from scratch in Node.js. Not a wrapper and not a tutorial follow-along. It implements the real internals: content-addressable object storage (blobs, trees, commits), SHA-1 hashing, a staging index, branch refs, HEAD resolution, and restoring files on checkout. It ships a full CLI with `init`, `add`, `commit`, `log`, `status`, `diff`, `branch`, and `checkout`, including a line-by-line diff engine.

`Node.js` `Git internals` `Content-addressable storage` `SHA-1` `Diff algorithms` `CLI`

---

### 🌌 AI-Powered Portfolio
[Live Site](https://vite-react-portfolio-lime.vercel.app/) · [GitHub Repo](https://github.com/TmoodGitHub/vite-react-portfolio)

My portfolio site, with a chatbot that answers questions about my work. A Python backend uses OpenAI embeddings to find the most relevant parts of my resume and project history, drops weak matches, and answers from those.

`React` `Vite` `Tailwind CSS` `Python` `OpenAI API` `Embeddings`

---

## Experience

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>Security Data Pipelines</h4>
      Ingestion and detection pipelines handling millions of security events per day from 100+ vendor integrations, at 99.9%+ availability. Go-based Pub/Sub services, a zero-downtime schema migration across 140+ files, and investigation tools (API, query engine, and React screens) for a 24/7 security operations team.
    </td>
    <td width="50%" valign="top">
      <h4>Ad Tech Data at Scale</h4>
      Backfills, daily syncs, and a rolling 7-day reconciliation pipeline over billions of ad events a month, using Lambda, Kinesis, PostgreSQL, MongoDB, and Amazon Athena. Alerting for a 24/7 malware operations desk, and dashboard work in React and PHP for 600+ publisher clients.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>Federal Healthcare Systems</h4>
      Work in the VA's VistA environment using M (MUMPS) and FileMan, tracing access and feature problems back to user profiles, rules, and permissions. Worked on a C# .NET Framework application that used Entity Framework to connect to Oracle, and modernized a legacy Visual Basic 6 application toward .NET, deploying it for multiple users on Citrix with CodeQL and Fortify code scanning.
    </td>
    <td width="50%" valign="top">
      <h4>Accessible Platforms</h4>
      Eight years as the sole engineer on a national American Sign Language proficiency evaluation platform: rebuilt its MSSQL data layer holding 30+ years of records, moved it to React and Node.js, and brought every screen up to WCAG 2.1 AA accessibility.
    </td>
  </tr>
</table>

---

## Stack

| | |
|---|---|
| **Languages** | TypeScript · JavaScript · Python · Go · PHP · Java |
| **Backend** | Node.js · REST APIs · GraphQL · Event-driven architecture · Microservices |
| **Databases** | PostgreSQL · MongoDB · MySQL · MSSQL · Oracle · BigQuery · Amazon Athena |
| **Cloud** | AWS (Lambda, S3, SQS, SNS, Kinesis, IAM, CloudFormation, API Gateway) · GCP (Pub/Sub) · Docker |
| **Healthcare & legacy** | VistA · M (MUMPS) · FileMan · C# · .NET Framework · Entity Framework · Visual Basic 6 |
| **Frontend** | React · Next.js · Angular · Ember.js · Tailwind CSS |
| **AI** | Anthropic Claude API · OpenAI API · Embeddings · Retrieval (RAG) · Prompt design |
| **Testing & CI** | Vitest · Jest · Cypress · React Testing Library · GitHub Actions · CircleCI |
| **Monitoring** | CloudWatch · Datadog · GCP Logging |

---

## Outside of work

Manga & anime fan · volleyball · lifting · toddler chaos · walking my dog · debugging production issues (yes, this is in the hobbies section)

---

## Let's connect

[![Portfolio](https://img.shields.io/badge/Portfolio-vite--react--portfolio-111111?logo=vercel&logoColor=white)](https://vite-react-portfolio-lime.vercel.app/)
[![Email](https://img.shields.io/badge/Email-tamerintech@gmail.com-D14836?logo=gmail&logoColor=white)](mailto:tamerintech@gmail.com)
