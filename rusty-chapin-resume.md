# Rusty Chapin

206-510-9326 | rusty.chapin@gmail.com | LinkedIn: linkedin.com/in/rustychapin

## Professional Summary

Engineering leader with 7+ years managing engineering teams and 25 years of technical depth across cloud, distributed systems, and regulated financial services. Owns high-blast-radius platform infrastructure — the database, cache, and object-storage layer underpinning transaction processing and compliance for a global remittance platform — with accountability spanning architecture, FinOps, and regulatory audit posture. Builds high-performance Platform Engineering, SRE, and DevOps functions; has delivered multi-million-dollar cost reductions and platform transformations across AWS, Google Cloud, and Azure. Leads through psychological safety, data-driven decision making, and a deep belief that engineering culture is the ultimate force multiplier.

## Core Competencies

Engineering Leadership | Platform Engineering | Site Reliability Engineering (SRE) | DevOps Strategy | Internal Developer Platforms (IDP) | Cloud Architecture (AWS, GCP, Azure) | Infrastructure as Code (Terraform) | CI/CD Automation | Distributed Systems | Disaster Recovery and Business Continuity | Database Engineering (RDS Aurora, DynamoDB, PostgreSQL, MySQL) | Compliance and Audit (NIST CSF, NYDFS, SOX, DORA, PCI DSS, FinCEN) | AI/ML Infrastructure | Budget and Cost Management (FinOps) | Team Building and Mentorship | Hiring and Diversity Programs | Cross-Functional Leadership | Incident Management | Observability and APM

## Selected Career Highlights

- Enabled a **$7M+ product sale** at BitTitan by leading the team that re-architected a decade-old SaaS platform for portability in under 6 months on Azure and modern CI/CD.
- Cut operational costs **80%+** at Pyrofex by redesigning Google Cloud automation with Terraform and Cloud Run, eliminating compute waste and manual deployment.
- Led a full **datacenter-to-AWS migration** at People Connect end to end — business case, executive approval, unification of two teams, and delivery on Terraform and GitLab automation.
- Brought e-commerce uptime from **99% to 99.99%** at Sportswear Inc. through multi-region load balancing on Nginx and AWS CloudFront.
- Coached multiple engineers from underperformance to top-performer status.

## Professional Experience

### Engineering Manager III, Developer Platform — Persistence
**Remitly, Inc. | Seattle, WA | August 2024 – Present**

Lead the Persistence (PER) team within Remitly's Developer Platform organization — a focused team of 3 engineers in Seattle owning a disproportionately large surface area: the Aurora (PostgreSQL and MySQL), DynamoDB, ElastiCache, S3, and EFS layer that underpins transaction processing, compliance, and developer self-service for a global remittance platform. Accountable for the architecture, cost envelope, and regulatory posture of that layer company-wide.

**Platform Engineering — Forge Resource Controller Family**

- Own the persistence Forge Resource Controller (RC) family — a unified, declarative Internal Developer Platform pattern exposing Aurora PostgreSQL, Aurora MySQL, DynamoDB, and ElastiCache as self-service primitives for every engineering team in the company.
- Shipped Aurora PostgreSQL as a Generally Available offering on Forge, including declarative cluster management, parameter groups, replication, and IAM authentication. Established architectural policy prohibiting DNS aliasing for RDS — a deliberate tradeoff chosen to protect IAM authentication and Blue-Green deployment pathways over short-term routing convenience.
- Drove DynamoDB Resource Controller adoption from 0 to 50% of production tables, on track to 99%, eliminating ad-hoc DynamoDB provisioning across the organization.
- Launched Forge Postgres User Management GA, removing manual DB-user provisioning toil for every engineering team and integrating GRANT sequencing with Alembic schema migrations.
- Extended cross-region capability by delivering Aurora MySQL and PostgreSQL Global Databases for low-latency multi-region reads and regional failover.
- Reduced persistence operational spend by **$1M+ over two years** through platform consolidation and reservation strategy.

**Multiverse Cross-Account Data Migration Architecture**

- Authored Remitly's universal seven-stage zero-downtime data migration pattern (Replicate, Hydrate, Sync, Validate, Cutover, Soak, Terminate) for Multiverse — Remitly's multi-tenant, single-tenant-account architecture initiative.
- Designed Change Data Capture (CDC) driven migration patterns across Aurora MySQL, Aurora PostgreSQL, DynamoDB, S3, and EFS using AWS DMS, DataSync, DynamoDB Streams with Lambda, and Transit Gateway.
- Partnered with AWS Solutions Architects to validate pricing models and total cost of ownership at scale.

**AWS Strategic Partnership**

- Organized and ran AWS-led DynamoDB Immersion Days for the full Remitly engineering organization across Seattle (March 2026) and Kraków — covering NoSQL data modeling, advanced design patterns, DynamoDB Streams, and Global Tables; drove an org-wide skill-gap survey and distributed recordings for asynchronous learning.
- Secured AWS VP-level engagement that produced a dedicated Specialist Solutions Architect for Multiverse and roadmap commitments on Aurora MySQL currency, DSQL active-active migration patterns, and DynamoDB Global Secondary Index improvements.

**Cost Optimization (FinOps)**

- Authored the AWS Reservation Management Plan for RDS, DynamoDB, and ElastiCache with 90% reservation coverage and 90% utilization targets.
- Implemented Reserved Instance, Savings Plan, and Compute Savings Plan tracking across the persistence fleet; tracked Enterprise Cost Optimization (ECO) recovery against monthly commitments.

**Compliance, Audit, and Regulatory Posture**

- Own persistence-team evidence for FY24 SOX ITGC Control C.12 (Database Backup), 2025 Joint State Exam (JSE) money-transmitter audits, and Risk and Compliance Universal Framework (RCUF) control validation.
- Delivered User Access Review (UAR) automation through rds-user-manager; championed shifting UAR from a quarterly SOX checkbox to a bi-weekly engineering habit.

**Developer Intelligence and Observability**

- Led the Persistence team's contribution to Remitly's Developer Intelligence initiative — built the Persistence Policy Service surfacing actionable insights on database resource usage and compliance posture across all product teams.
- Built and maintained Grafana and CloudWatch dashboards giving product teams visibility into RDS cluster performance across production and pre-production.

**Incident Leadership**

- Led the remediation epic for a Large-Scale Event (LSE) involving DynamoDB production data loss; partnered cross-functionally to restore service, eliminate the failure mode, and harden the resource controller against recurrence.
- Directed the Kurator missed-records incident response — identified, fixed, audited, and re-designed the system to prevent recurrence, avoiding significant customer and regulatory impact.

**Team Leadership and Organizational Development**

- Lead a 3-engineer Seattle team owning the company's persistence layer; drive engagement through weekly one-on-ones, structured career-development frameworks, and roadmap alignment.
- Built the Persistence team operating system within the first six months: Sprint Playbook, Jira Intake Process, Code Ownership Split, Test Plan Template, and Outcomes-vs-Outputs coaching framework.
- Authored the Persistence Team North Star Metric (TB managed), tying infrastructure growth to customer transaction growth.
- Owned the Developer Platform organization engagement-survey readout to senior leadership (Q1 2025) with 91% participation; partnered with directors and skip-level VP on action plans.

### Vice President of Systems Engineering
**Pyrofex | Orem, UT (Remote) | January 2023 – August 2024**

Promoted from Senior Systems Engineer in recognition of impact. Assumed executive responsibility for engineering strategy, hiring, and infrastructure roadmap across Google Cloud and bare-metal environments. Company wound down in August 2024 following funding outcome.

- Led Agile sprint planning and delivery across operations and software engineering teams.
- Managed cross-functional priorities as the engineering leadership voice alongside the CEO.
- Implemented and evaluated multiple Large Language Model engines (LLaMA 2, Mistral 7B, ChatGPT) for internal AI product prototyping.

### Senior Systems Engineer
**Pyrofex | Orem, UT (Remote) | January 2022 – January 2023**

Hired as the sole systems engineer reporting directly to the CEO; designed and built the entire cloud and hardware infrastructure strategy from the ground up.

- Reduced cloud and infrastructure operating costs by over 80% through Infrastructure as Code automation and workload migration to Cloud Run.
- Designed a global infrastructure deployment system on Terraform, GitLab CI/CD, and Google Cloud — launching entire networks on a single code commit.
- Designed, procured, and deployed $1M+ of server hardware for a public-cloud startup; architected core network and firewall infrastructure.
- Implemented an observability stack with Prometheus, Grafana, and intelligent alert routing — reducing Mean Time to Resolution (MTTR) and improving incident visibility.

### Manager, Site Reliability Engineering and Data Operations
**People Connect | Seattle, WA | January 2021 – January 2022**

Hired to consolidate two separate teams (8 direct reports) and lead a full datacenter-to-AWS migration. Responsible for SRE, data operations, hiring strategy, and cloud architecture.

- Spearheaded the private-datacenter-to-AWS migration: built the business case, defined skill requirements, secured executive approval, and led the team through delivery.
- Reduced on-call events by championing a metrics-first culture across software engineering teams.
- Developed Terraform modules and GitLab automation pipelines supporting a deeply integrated microservices architecture.
- Implemented cloud-first architectural standards and team processes to sustain post-migration velocity.

### Manager of DevOps
**BitTitan | Bellevue, WA | January 2019 – January 2021**

Built and led a DevOps and SRE team responsible for service reliability, platform modernization, and cloud cost management. Within six months, the team's platform work enabled a $7M+ product sale.

- Architected a fully automated deployment system on Azure for a global, multi-region SaaS platform.
- Reduced cloud operating costs by 30% through targeted rightsizing and platform optimization.
- Implemented APM, alert routing, and a service-ownership model across software engineering — dramatically reducing outage frequency and duration.
- Built an internal education and career-development program for DevOps engineers.
- Championed data-driven, metrics-first engineering culture across the organization.

### Information Technology Operations Manager
**Sportswear Inc. | Seattle, WA | January 2014 – January 2019**

Managed all IT operations for an e-commerce company — datacenter hardware, networking, cloud productivity, and software-delivery automation.

- Built a fully automated build-and-deploy pipeline with TeamCity and Octopus Deploy, eliminating manual deployments and reducing release risk.
- Designed and implemented Chef-based infrastructure automation across the full server fleet.
- Brought uptime from 99% to 99.99% through multi-region load balancing with Nginx and AWS CloudFront.
- Led company-wide Agile adoption and improved executive visibility through dashboards and metrics programs.

### Lead DevOps Engineer
**Avalara | Seattle, WA | January 2013 – January 2014**

Led a five-person DevOps team managing deployment, monitoring, and reliability for a globally distributed, low-latency sales-tax API serving customers including Groupon.

- Architected and administered Splunk and Opsview monitoring platforms.
- Managed F5 load balancers, IIS, and SQL Server environments supporting a high-volume financial API.

### Earlier Experience

- **AT&T** (via Strong Bridge Consulting) — Lab and Production Environment Manager — Jan 2012 to Jan 2013
- **Brightlight Consulting** — Cloud Services Architect and Business Intelligence Consultant — Jan 2011 to Jan 2012
- **Demand Media** — Business Intelligence Engineer — Jan 2010 to Jan 2011
- **Cypress Consulting** (Contract at the Bill and Melinda Gates Foundation) — Senior Database Engineer — Jan 2008 to Jan 2009

## Technical Skills

**Cloud Platforms:** AWS — RDS Aurora, DynamoDB, S3, EFS, IAM, CloudWatch, EC2, VPC, CloudFront, Redshift, Blue-Green Deployments, DMS, DataSync, Transit Gateway; Google Cloud — Cloud Run, GKE, Cloud Build; Microsoft Azure.

**Infrastructure as Code and Automation:** Terraform, Ansible, Chef, GitLab CI/CD, GitHub Actions, Octopus Deploy, TeamCity.

**Observability and Monitoring:** Grafana, CloudWatch, Prometheus, Datadog, New Relic, Splunk, Elasticsearch.

**Containers and Infrastructure:** Kubernetes, Docker, OpenStack.

**Databases:** PostgreSQL, MySQL, DynamoDB, Microsoft SQL Server, Redis, MongoDB, Couchbase, IBM Netezza.

**Programming Languages:** Python, Bash, Go, C#, T-SQL.

**Compliance and Security:** NIST CSF, NYDFS NYCRR 500, SOX ITGC, DORA, PCI DSS, FinCEN, Disaster Recovery, RPO/RTO Design, IAM Authentication, S3 Object Lock Compliance Mode.

**Platform and Tooling:** Internal Developer Platforms (IDP), DORA Metrics, Developer Self-Service, Incident Management, FinOps.

**AI and Machine Learning:** LLaMA 2, Mistral 7B, ChatGPT and OpenAI API, ElevenLabs, LLM infrastructure.

**Leadership:** Engineering Management, Team Building, Hiring and Diversity Programs, Career Development, Budget Management, Agile, Scrum, Kanban.

## Education and Teaching

Coursework in Computer Science | Western Washington University, Bellingham, WA

Adjunct Instructor, Cloud Engineering | University of Washington Continuing Education Program
