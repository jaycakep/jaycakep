# Hi, I'm Giant Rachman 👋

**Senior Software Architect · Indonesia**
*I build systems from scratch and rescue the ones that matter most.*

---

## 🧠 What I Do

I've spent 18+ years solving problems that sit at the intersection of software architecture and business operations. My work tends to fall into two categories:

**Building** — Designing and delivering complex systems from the ground up. ERP, MRP, POS, cooperative management, government information systems. Full-cycle: from domain analysis and database schema through deployment and maintenance.

**Rescuing** — Being called in when a system has failed, a developer has disappeared, or years of critical data are at risk. I've recovered 15 years of corrupted database records, cut invoice generation time from one month to under one minute, and rebuilt abandoned government systems that had paralyzed entire departments.

The through-line in both: **every technical decision carries a business consequence.** I don't just deliver features — I deliver systems that hold up under real operational pressure.

---

## 📂 Case Studies

These aren't tutorial projects. They're documented architectures from real systems I designed and built — including the edge cases, the constraints, and the decisions that didn't make it into the happy path.

### 🪦 [Cemetery &amp; Crematorium Management System](./cemetery-management-system-architecture)

> *Surabaya City Government · 2019 · PHP · CodeIgniter · MariaDB*

A municipal cemetery data system abandoned by its original developer — critical bugs, no audit trail, no billing engine, staff back on Excel. I rescued and rebuilt it into a fully operational system covering burial plot management, crematorium operations, automated retribution billing, multi-role access control, and document generation.

**Key result:** Invoice generation time from 1 month (manual) → under 1 minute.

---

### 🏪 [POS &amp; Cooperative Management System](./kopkar-pos-cooperative-system)

> *Koperasi Pegawai RSI Jemursari · Built 2013–2016 · Rescued 2019 · PHP · MySQL*

A full retail POS and cooperative management system serving 1,000+ hospital staff members — built from scratch, maintained through 2016, then recovered after a power failure corrupted 3 years of transaction data in 2019.

**Key innovation:** A custom data-driven form engine (`Common_CUQuery` + `form_attr`) that auto-generates INSERT/UPDATE queries from database configuration — eliminating redundant code across 12+ operational modules.

**Key result:** Point-of-sale report load time from 20+ minutes → under 30 seconds after database optimization.

---

### 🏭 [Manufacturing Resource Planning System](./bukit-baja-mrp-system)

> *Bukit Baja Anugrah Steel Pipe Manufacturer · 2013–2016 · PHP · MySQL · 70+ Tables*

A full MRP system for a 24-hour, 3-shift steel pipe manufacturer — covering order management, BOM, production scheduling, crew assignment, QC, inventory, packing, and shipping. The flagship feature was a recursive combinatorial algorithm that solved the steel coil slitting optimization problem.

**Key result:** Production scheduling from 3–4 days → under 30 minutes. Slitter calculation from 3–4 hours per coil → seconds, with mathematically guaranteed waste below 1%.

---

## 🛠️ Technical Depth

```
Languages       C++ · PHP · JavaScript · TypeScript · Node.js · Java · SQL · .NET
Databases       MySQL · MariaDB · PostgreSQL · Microsoft SQL Server · MongoDB
Architecture    ERP · MRP · Legacy Modernization · Distributed Systems
DevOps          Docker · Kubernetes · CI/CD · AWS · GCP · Azure
Frontend        React · Next.js · SvelteKit · Bootstrap · jQuery
Tooling         Git · Jira · Bitbucket · Linux · XAMPP
```

---

## 🔧 How I Work

I'm language-agnostic by philosophy — the stack follows the problem, not the other way around. My default questions before any architectural decision:

- Can the client's existing team maintain this after I leave?
- Can this run on the client's existing hardware?
- Does this complexity actually solve a business problem, or does it just look impressive?

A solution that requires expensive infrastructure or specialist knowledge to maintain is not a solution — it's a liability transferred to the client.

⚡ **AI-Augmented Delivery:** 

I operate multi-AI environments as force multipliers — training them with strict database schemas, business domain constraints, and architectural guardrails, while I own the code review, system boundaries, and every consequential decision. This allows me to deliver mid-sized team output with the alignment and accountability of a single Senior Architect.

---

## 📫 Let's Connect

I'm currently open to **long-term contract engagements** — fully remote, async-first.

If your business is dealing with system performance issues, legacy technical debt, or operational bottlenecks that have become business problems, let's talk.

- 🔗 [LinkedIn](https://linkedin.com/in/jaycakep)
- 📧 Available via LinkedIn message

---

*Based in Malang, Indonesia · Available globally · Async-first*
