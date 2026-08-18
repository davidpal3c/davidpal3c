[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=85E216&width=700&lines=Hi!+I'm+David;Software+Engineer%2C+Cloud+%26+Infrastructure)](https://git.io/typing-svg)

Software Engineer -Full-Stack · AWS Certified Solutions Architect – Associate <br>· [davidpalacios.dev](https://davidpalacios.dev) based in Calgary, AB, Canada

I design, build, and operate systems end to end — APIs and applications in C#/.NET, TypeScript/React, and Python, and the AWS/Azure infrastructure, Terraform, containers, and CI/CD pipelines where they run.

I like working on both sides of development and operations, I can read the application *and* the infrastructure under it, think in terms of business and follow a bug across the boundary.

---

### In short

- **Production software** — C#/ASP.NET Core, TypeScript/Next.js/React, Python/FastAPI, SQL Server/PostgreSQL. Cut reporting latency 40%+ and improved front-end performance ~30% on real systems with real users.

- **Cloud & infrastructure** — AWS (VPC, EC2, RDS, IAM, CloudWatch, Lambda) and Azure (AKS, DevOps, Key Vault), all Terraform-managed, with CI/CD and automated cost controls on live environments.

- **Currently building** — Ceiba, an API access/monetization platform, and a bare-metal Linux platform run with production-style operational discipline (see below).

---

### What I'm working on right now

| System | What it is | State |
|---|---|---|
| **[ceiba-infra](https://github.com/CeibaLabs/ceiba-infra)** | Terraform-managed AWS environment for a live product — VPC isolation, EC2 Graviton, RDS Postgres, least-privilege IAM, automated cost guardrails | **~$30/month**, deployable from a clean account in 25 minutes (free GitHub Actions runner) |
| **[@ceibalabs/ceiba-sdk](https://www.npmjs.com/package/@ceibalabs/ceiba-sdk)** | Node SDK for API keys, quotas, and subscription-gated access on Express and Fastify | Published on npm, MIT |
| **[mu-platform_homelab](https://github.com/davidpal3c/mu-platform_homelab)** | Single-node private cloud on bare metal — RAID1 boot mirror, four isolated storage tiers, k3s | Building; every change carries a verification step and a rollback |


---

### Stack and Tooling I use

| | |
|---|---|
| **Cloud** | AWS — VPC · EC2 · RDS · IAM · CloudWatch · Lambda · SNS · S3 <br> Azure — AKS · DevOps Pipelines · Key Vault|
| **Infrastructure as Code** | Terraform · Bash · Python · YAML |
| **Containers & CI/CD** | Docker · Kubernetes · AKS · k3s · Helm · GitHub Actions · Azure DevOps |
| **Systems** | Linux - Ubuntu Server · mdadm RAID · systemd · Nginx · IIS · Kestrel |
| **Backend** | C# / ASP.NET Core · Node.js / Express / Fastify · Python / FastAPI · REST APIs |
| **Frontend** | TypeScript · React · Next.js · state management (React Query, Zustand, Context API), HTML, CSS |
| **Data** | PostgreSQL · SQL Server · Redis |


---

### Worth opening

| Repo | What it proves |
|---|---|
| **[ceiba-infra](https://github.com/CeibaLabs/ceiba-infra)** | Terraform, AWS architecture, IAM design, and cost engineering — with the trade-offs written down, not just the result |
| **[MonetizeAPI](https://github.com/davidpal3c/MonetizeAPI)** | A paid product I built and deployed end to end |
| **[mu-platform_homelab](https://github.com/davidpal3c/mu-platform_homelab)** | Linux and platform engineering: failure-domain isolation by storage tier, and an operating model where everything done is verified and documented |
| **[CarbonSage](https://github.com/davidpal3c/CarbonSage_agentic_ai)** | Full-stack data platform — FastAPI, Next.js, RAG/retrieval, provenance-bearing contracts, deployment gates |
| **[CampusConnect](https://github.com/davidpal3c/CampusConnect_next_express)** | Full-stack delivery (Next.js/Node/PostgreSQL) *and* the Kubernetes deployment behind it — AKS, Ingress, TLS, GitHub Actions — for a 5-person team I led |
| **[ceiba-sdk-node](https://github.com/CeibaLabs/ceiba-sdk-node)** | Shipped developer tooling, published and MIT-licensed |



---

### Writing

Beyond results, here's some reasoning, architecture decisions, cost analysis, and things that broke on the way. 
[Visit my Blog for more](https://davidppalacios.dev/blog)


---

**davidpal3c@gmail.com** · [LinkedIn](https://linkedin.com/in/davidpal3c) · [Portfolio](https://davidpalacios.dev)

*Open to Software Engineering, Cloud, DevOps, and Platform Engineering roles — Calgary, remote across Canada, and contract engagements.*


> Building systems that are not only functional — but observable, reliable, and operable.
