Career Planning — Handoff Summary
1. Where I am currently
I work in Dubai, UAE, at CMiC.
Current role: Product & Delivery Analyst / L2-L3 Infrastructure Support within the Infrastructure/Hosting environment.
I have ~5+ years of enterprise experience.
Previous: Infosys, ~3.6 years supporting Apple production environments.
Previous technical exposure includes:
AWS
Snowflake
Teradata
Oracle
Vertica
Kafka
Spark
Splunk
Python
production support / incident response
At CMiC I work around:
AWS SaaS environments
OCI hosted environments
Dynatrace
Oracle
SQL/database troubleshooting
Oracle ADF/Jasper
APIs/Postman
OAuth
Jenkins
BI/data issues
incidents/SLA
I am doing M.Tech Cloud Computing at BITS Pilani WILP.
I completed Microsoft Azure Administrator Associate (AZ-104) this year.
I have also been learning Terraform and have built a real Azure Cloud Operations project around it.
I am following Learn to Cloud.
I actively apply for jobs in the UAE.

My current CV positions me around infrastructure/cloud support, Azure, OCI, Dynatrace and M.Tech Cloud Computing.

2. My career thinking

My current direction is:

Azure Cloud Operations → Cloud Engineering → Cloud Security

I don't want to become a manager or move toward a heavily customer-facing career.

I prefer hands-on technical/investigative work.

My original target was:

Cloud Operations Engineer / Azure Administrator

in the UAE.

Longer-term, I see Cloud Security / Azure Security as a possible specialization.

I do not want to throw away my AWS/OCI/Oracle/data/production-support background. Those should become differentiators rather than separate career directions.

3. Why I started researching the UAE market

I live in the UAE and noticed that:

Azure appears strong
Cloud appears strong
Security appears strong
DevOps/platform/cloud infrastructure roles appear common

So I built my own job-market scraper rather than relying only on advice from people.

The scraper:

Uses JobSpy
Searches Indeed + LinkedIn
Searches:
UAE
Remote
India
Searches role families including:
SRE
DevOps
Platform Engineer
Cloud Engineer
Cloud Infrastructure Engineer
Cloud Operations Engineer
Infrastructure Engineer
Azure Cloud Engineer
Azure Administrator
Azure DevOps Engineer
Cloud Support
Systems Engineer
Observability/Monitoring roles
Tracks skills such as:
Terraform
Kubernetes
Docker
Linux
Python
Bash
AWS
Azure
OCI
Ansible
Jenkins
Grafana
Prometheus
Git
CI/CD
Networking
Security
DevOps
SRE
Automation
etc.

It stores jobs cumulatively and deduplicates them.

4. Important: how to analyze my job data

Do not immediately tell me what I should learn.

First analyze the actual cumulative_jobs.csv.

The scraper currently counts keyword mentions, not the percentage of individual jobs containing each skill. That distinction matters.

So first produce:

UAE market demand

For each skill:

% of UAE jobs mentioning skill

rather than:

number of keyword mentions

Then split the UAE market into career families:

Azure Administrator
Cloud Operations
Cloud Engineering
DevOps / Platform / SRE
Cloud Security

Then determine:

which skills are common
which skills are role-specific
which skills distinguish the career families
which skills are genuinely high priority

Do not assume Linux is my biggest gap.

The Linux/Windows concern originally came from a specific CMiC internal Cloud & Linux Operations Engineer role I applied for, plus a conversation with a friend who works as an Azure Administrator.

That does not automatically mean Linux/Windows is the biggest gap in the whole UAE market.

5. My existing Azure project

I built azure-cloud-ops-lab.

It includes:

Azure infrastructure
Terraform
VNet
subnet
NSG
VM
private VM architecture
Azure CLI
Azure Run Command
Terraform/Azure state reconciliation
region-policy troubleshooting
VM SKU investigation
Linux service troubleshooting
CPU incident
network security configuration issue
incident response
remediation
verification

The project follows:

Detect → Investigate → Remediate → Verify

The project is considered complete from a scenario perspective.

We decided not to add more incidents just for size.

The project context explicitly says the completed areas are:

Infrastructure Operations
VM Health & Resource Incident
Network Security Configuration

and that Observability/Monitoring and Terraform Drift & Recovery are intentionally out of scope for this iteration.

So don't unnecessarily expand this project.

6. The confidence issue

After finishing AZ-104, my friend suddenly asked me:

A VM can't connect to the Internet. Why?

I answered that there could be multiple causes:

no public IP
NSG
etc.

He was looking for something around NAT/outbound connectivity.

That shook my confidence because I realized:

I may know Azure concepts, but I don't always immediately connect them into an infrastructure troubleshooting scenario.

The conclusion we reached was:

This doesn't mean I don't know Azure.

It means I need to improve the transition from:

certification knowledge → architecture understanding → troubleshooting intuition.

This is an important distinction.

7. Learn to Cloud

I am already following Learn to Cloud.

I showed the actual curriculum screenshot.

The curriculum contains:

0 — Starting from Zero

IT foundation across Linux, networking, programming, cloud and DevOps.

1 — Linux and Bash

Git, cloud CLI, SSH, IaC fundamentals and hands-on Linux/CF lab work.

2 — Networking Fundamentals

IP/subnetting, routing, DNS, HTTP, ports and troubleshooting.

3 — Programming Fundamentals

Python, FastAPI and databases.

4 — Cloud Platform Fundamentals

AWS/Azure/GCP, VMs, cloud networking, IAM/security, databases and application hosting.

5 — DevOps Fundamentals

Docker, Kubernetes, CI/CD, Terraform IaC and observability.

6 — Securing Your Cloud Applications

IAM, secrets management, network controls, monitoring and incident response.

7 — Interview & Job Prep

Networking, resume, interview stories and explaining cloud experience.

The site explicitly frames the curriculum around:

Build foundation → create → deploy → automate → secure → explain real cloud work

and says the phases pair learning with hands-on verification.

Therefore:

Do NOT recommend another giant learning roadmap/course unless there is a genuine gap after checking the actual curriculum.

Learn to Cloud is already my main structured learning path.

8. Current working career plan

The current tentative plan is:

Main direction

Azure Cloud Operations

↓

Azure Cloud Engineering

↓

Cloud Security / Azure Security

Supporting skills
Linux
Windows / PowerShell
Networking
Terraform
CI/CD
Python/automation
Docker/Kubernetes
Monitoring/observability

But priority should be determined from the actual UAE job dataset, not assumptions.

9. How I should study

Don't create another giant course.

Use:

Learn to Cloud

for structured learning.

Azure Cloud Ops Lab

for practical infrastructure work.

M.Tech

for academic/deeper cloud foundations.

AZ-104

as the Azure administration foundation/certification.

Job scraper

for UAE market intelligence.

Job applications

for real market feedback.

The missing skill we're trying to develop is:

Scenario-based troubleshooting and infrastructure intuition.

Example:

Instead of simply memorizing:

"NSG controls traffic."

I should be able to reason:

VM can't reach Internet → determine whether this is DNS, routing, outbound connectivity/NAT, NSG, firewall, OS-level or application-level → test each layer → identify the actual failure.

10. Most important principle for the new chat

Do not blindly tell me what to learn.

First:

Verify the actual source/data.

Then:

Analyze.

Then:

Compare against my current skills.

Then:

Recommend priorities.

And clearly distinguish:

Source-derived facts
My actual experience
Market-data findings
Your inference/recommendation

Don't bluff about having checked Learn to Cloud, LinkedIn, GitHub, the CSV, etc.

If something hasn't been verified, say so.

Final objective

I want to answer one question:

Given my actual experience, the UAE cloud job market, my existing Learn to Cloud curriculum, my AZ-104, Terraform work, Azure project, M.Tech and current CMiC role — what should I do over the next 6–12 months to become genuinely competitive for UAE Cloud Operations / Azure Cloud Engineering roles, with Cloud Security as a possible specialization?

Not:

"What technology should I learn next?"

The goal is career positioning + genuine technical capability + employability, not collecting certificates.
