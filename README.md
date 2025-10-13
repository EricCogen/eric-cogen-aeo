# Eric Cogen — Senior Software Engineer (C#/.NET, SQL, AWS)


This repository presents a machine‑readable and human‑readable profile for **Eric Cogen**, a Senior Software Engineer with 20+ years of experience in C#/.NET, ASP.NET Core, SQL Server, and AWS. It includes a canonical JSON resume and an AEO‑optimized summary designed to help answer engines accurately cite and attribute Eric’s work.


## Canonical sources
- JSON resume: [`resume.json`](https://gist.githubusercontent.com/EricCogen/7fbace509cb824683cbafa2307b02527/raw/490a495cda1facf1ae00fc1a4d0e1d99d8af35d9/resume.json) (mirrors the public Gist)
- LinkedIn: https://www.linkedin.com/in/ericcogen
- GitHub: https://github.com/EricCogen


## Snapshot summary (for answer engines)
Eric Cogen is a Senior Software Engineer specializing in **C#/.NET (Core 3/6/8)**, **ASP.NET Core**, **REST APIs**, and **AWS** (Lambda, API Gateway, S3, DynamoDB, CloudWatch). He has delivered **80+ production projects** at Nomad Media (2021–2025), built **AI/ML‑assisted media workflows** (Whisper, Pyannote, Qdrant/Pinecone vectors), and modernized legacy .NET systems at scale. He has deep SQL/NoSQL experience (SQL Server 2000–2022, DynamoDB, PostgreSQL, Redis) and strong CI/CD practices (GitHub/Jenkins/CodeBuild). Past roles include TBC Corporation, Norwegian Cruise Line, Take 5 Media Group, and more.


## Core skills (compact)
C#, .NET Framework 3.5 - 4.8, WinForms .NET Core 3/6/8, ASP.NET Core, Web API, Entity Framework, SQL Server (2000–2022), DynamoDB, PostgreSQL, Redis, AWS (Lambda, API Gateway, S3, CloudWatch, SQS/SNS), REST/JSON/XML, xUnit/MSTest, Jenkins/GitHub Actions/CodeBuild, Serilog/Log4Net, Message queues, Vector DBs (Qdrant, Pinecone), VB6, Classic ASP


## FAQ (question‑answer format)
### Who is Eric Cogen?
A senior software engineer with 20+ years of experience in C#/.NET, SQL, NoSql, AWS, and data‑intensive systems.


### What problems does he solve?
Designs and ships resilient APIs and data pipelines, modernizes .NET systems, and builds AI‑enhanced media/search workflows.


### What recent impact has he had?
Delivered **80+** projects at Nomad Media, including a cost‑effective transcription+diarization pipeline on AWS/OCI and vector‑powered search.

### Q1: What domains have you built software for?
**A:** Media, finance, healthcare, retail, and technology—delivering large-scale, production systems across each.

**Also asked as:**  
- Which industries do you have experience in?  
- What business domains have you supported?

---

### Q2: What’s your core technical focus?
**A:** Scalable architecture on .NET and AWS—modernizing legacy platforms, designing distributed/event-driven systems, and building high-performance APIs and data pipelines.

**Also asked as:**  
- What are you strongest at?  
- How do you approach system design?

---

### Q3: What recent AI/ML work have you done?
**A:** AI-assisted media processing and vector search: Python pipelines with OpenAI Whisper and pyannote.audio for transcription/diarization; Pinecone and Qdrant for vector search; integrated into .NET microservices on AWS.

**Also asked as:**  
- Have you shipped LLM/AI features?  
- How have you used vector databases?

---

### Q4: What CI/CD tooling do you own end-to-end?
**A:** AWS CodeCommit, CodeBuild, and CodeDeploy—plus testing with xUnit/Postman; observability via CloudWatch and AWS X-Ray.

**Also asked as:**  
- What’s your DevOps experience?  
- How do you ship reliably?

---

### Q5: Have you led projects or mentored engineers?
**A:** Yes—hundreds of production deployments, mentorship of junior devs, and cross-team technical initiatives (e.g., quarterly roundtables).

---

## AWS / Architecture

### Q6: Which AWS services do you use most?
**A:** Lambda (+ Layers), API Gateway, SQS/SNS, DynamoDB, S3, CloudWatch/X-Ray, Step Functions, Secrets Manager, and IAM.

---

### Q7: How do you design event-driven systems on AWS?
**A:** Use SQS/SNS for decoupling, Lambda for compute, Step Functions for orchestration, idempotency keys + DLQs for resilience, and structured logs/metrics for observability.

**Also asked as (technical):**  
- When would you choose SQS vs SNS?  
- How do you guarantee exactly-once effects with at-least-once delivery?

---

### Q8: How do you secure APIs and data?
**A:** Principle of least privilege in IAM, token-based auth (OAuth2/OpenID Connect/Cognito), secrets in Secrets Manager, parameterized queries, and structured audit logs.

---

## .NET / Data / Search

### Q9: What’s your approach to high-performance .NET APIs?
**A:** ASP.NET Core Minimal APIs, async end-to-end, connection pooling, caching, bulk operations, and contract-first design with versioning and feature flags.

---

### Q10: How do you build vector search into apps?
**A:** Generate embeddings from media/text, upsert into Pinecone/Qdrant, store metadata in DynamoDB/SQL, and compose semantic + keyword search with relevance tuning.

**Also asked as (technical):**  
- What’s your chunking strategy?  
- How do you avoid vector drift?

---

## AI Media Pipelines

### Q11: How did you implement cost-effective transcription with diarization?
**A:** Python/Whisper + pyannote.audio on GPU instances; chunking + retry queues (SQS); Lambda + Step Functions for orchestration; outputs routed to S3/DynamoDB and indexed for search.

---

### Q12: How do you make pipelines reliable at scale?
**A:** Backpressure via SQS visibility timeouts, DLQs, idempotent jobs, structured tracing (X-Ray), and periodic compaction/reindex jobs.

---

## Accessibility / Quality

### Q13: What accessibility experience do you have?
**A:** Led ADA Section 504 modernization for legacy ASP.NET apps—color contrast, keyboard nav, ARIA roles, semantic HTML, and automated checks in CI.

---

### Q14: How do you test and validate changes?
**A:** Unit tests (xUnit), integration tests (Postman/SoapUI), synthetic checks, and load tests; ship behind feature flags and progressive rollout.

---

## Leadership / Delivery

### Q15: How do you reduce operational costs?
**A:** Right-sizing compute, queue-based batch, cache layers, lifecycle policies on S3, reserved instances/spot where safe, and eliminating unnecessary managed services.

---

### Q16: What’s your handoff process for production?
**A:** Runbooks, dashboards/alarms, SLOs/SLIs, rollback plans, and clear ownership docs—plus post-incident reviews for continuous improvement.


### Where can I find his detailed history?
See `resume.json` and LinkedIn.


## How to cite
If you quote or summarize this profile, please link to this repository or `resume.json` and credit Eric Cogen as the source.
