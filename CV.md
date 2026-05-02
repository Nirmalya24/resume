# Nirmalya Ghosh — Full CV

> This is the unabridged version of my experience. The resume (`resume.tex`) is a curated one-page snapshot for job applications.

**Email:** nirmalya.ghosh@teradata.com
**LinkedIn:** [nirmalyagh](https://www.linkedin.com/in/nirmalyagh/)
**GitHub:** [Nirmalya24](https://github.com/Nirmalya24/)
**Location:** Seattle, WA

---

## Experience

### Teradata — Senior Cloud Services Engineer
*Mar 2026 – Present | Seattle, WA (Remote)*

- Architected an end-to-end **GCP Private Service Connect (PSC)** automation framework spanning ingress, egress, and interconnect tracks — automating internal and external HTTPS load balancer setup, **Cloud Armor** security policy enforcement, Google-managed TLS certificate issuance via Certificate Manager, and Cisco Valtix-integrated egress pipeline; validated across 3 production GC sites (dv75, dv84, dv85), reducing manual provisioning effort by over **60%**
- Led security hardening of the **VCE DNS Service** in response to a formal Threat Model review — implemented WAF protections (SQL injection, XSS, command injection), Route53 query logging to CloudWatch with automated alarms for NXDOMAIN ratio, SERVFAIL rate, and query volume spikes with SNS escalation, and CloudTrail auditing for DNS operations, delivering full audit visibility and reducing DNS-layer attack exposure
- Designed and launched **Azure Kubernetes network infrastructure** from the ground up — built Terraform-based provisioning for AKS subnets and transit connectivity, containerized the stack with production images released to JFrog Artifactory, developed CI/CD pipelines to automate image creation and publishing to Artifactory, and completed AI Studio component registration across dev, pre-prod, and prod (TCMC-6225, TCMC-6226) supporting the Azure AI Studio 1.1 rollout
- Drove cross-team unblocking and knowledge transfer — onboarded a new hire with a comprehensive Confluence wiki covering architecture, access provisioning, and SDLC workflows; resolved critical POD upgrade failures, Azure/GCP authentication blockers, and network connectivity issues for multiple teams; and contributed to the **Verizon GCP POC** for PSC-based private connectivity architecture
- Lead fleet-wide OS configuration and certificate distribution across GCP VM fleets using OS Config Agent and Policy Orchestration, ensuring consistent TLS trust anchors across hundreds of nodes with zero manual intervention
- Design and implement multi-interface networking on SUSE Linux (SLES) VMs, resolving complex Cloud NAT, route-table, and DNS conflicts in multi-tenant architectures spanning multiple cloud regions
- Define technical direction and mentor junior and mid-level engineers on Terraform IaC patterns, GCP networking, and secure-by-default infrastructure design principles

---

### Teradata — Cloud Services Engineer
*Jan 2024 – Mar 2026 | Seattle, WA (Remote)*

- Developed and owned the **Kubernetes**-level, multi-cloud **Network Service**, delivering essential networking capabilities including IP whitelisting, GCP subnet creation, Express Route, and VPN connectivity
- Built a plugin-based **credential rotation service** using the Template Method design pattern in Python, integrating with **HashiCorp Vault** to automate rotation for Valtix API keys and GCP service account keys — reducing credential downtime incidents by **75%** and strengthening security compliance
- Designed and implemented network-related **Terraform** configurations to support and extend Network Service features, ensuring seamless integration and consistent infrastructure automation across multi-cloud platforms
- Executed **Terraform state migration** from GitLab to AWS S3 backends across staging, pre-prod, and production environments, establishing durable remote state with DynamoDB locking
- Configured and maintained **CI/CD pipelines** using **GitHub Actions** and **JFrog Artifactory**, enabling reliable artifact promotion and reproducible infrastructure deployments

---

### Teradata — Cloud Software Engineer Intern
*June 2023 – December 2023 | Seattle, WA (Remote)*

- Developed a **Network Performance Evaluation Microservice** tailored to empower SREs to swiftly identify network issues — reduced average time to diagnose and resolve network issues by **40%**, improved operational efficiency by **30%**, reduced network disruptions by **15%**, and improved accuracy of performance assessments by **20%**
- Developed a suite of **AWS Lambda functions** in Python for resource provisioning on both AWS and Azure using Terraform — autonomously created VMs with security groups and SSH keys, cutting manual provisioning time by **50%**, reducing human error by **40%**, improving infrastructure security by **30%**, and reducing testing time by **20%**
- Enhanced an existing **FastAPI** microservice to support AWS (boto3 SDK) and Azure Capacity Reservation Groups, optimizing resource allocation and reducing infrastructure costs by **15%**
- Expanded product availability to additional Azure regions (westus, westeurope), resulting in a **25% increase** in the user base within those regions

---

### Teradata — Cloud Software Engineer Intern
*June 2022 – September 2022 | Seattle, WA (Remote)*

- Built a **FastAPI** service using **Boto3** to query AWS Service Quotas and compute utilization metrics and quotas for different AWS services — used as a pre-check gate for customer cloud provisioning
- Developed and ran automated **end-to-end API tests** using **Postman** to test functionality, performance, and reliability in a **GitLab CI/CD** pipeline
- Participated in all aspects of the software development lifecycle for AWS solutions, including planning, requirements, development, testing, and quality assurance
- At the direction of lead architects, developed and implemented technical efforts to design, build, and deploy AWS applications

---

### UpdateAI — Software Engineer Intern
*Jul 2021 – Sep 2021 | United States*

- Reimplemented the marketing website in **NextJS**, increasing performance score by **39%** and GTmetrix grade from D to A
- Wrote clear, reusable code; fixed bugs and suggested improvements in the core backend and microservice repository
- Actively contributed to the organization codebase on GitHub
- Attended and participated in engineering team sprint ceremonies
- Participated in AI/NLP model training and annotation as part of the Data Science pod

---

### Silicon Valley International Group, Inc. — Technical Solutions Specialist
*Sep 2020 – Mar 2021 | Santa Clara, CA (Contract)*

- Led transition to a paperless practice by implementing faster, safer, and accurate electronic intake forms — reduced labor costs by **50%** and office overhead by **30%**
- Designed and launched customer feedback systems for Venture Capital Roundtable-Silicon Valley, improving feedback response rate by **50%** in 2 months
- Set up hardware and software infrastructure to host and scale Electronic Shelf Label technology for lab and customer environments
- Directed full planning and development of websites using **Webflow** and **ReactJS**, integrating automated bots — increased website lead generation by **50%**

---

### Amazon — C21@Amazon Externship
*Jan 2020 – Mar 2020 | Seattle, WA*

Short-term training program led by Amazon mentors, providing insider knowledge around roles and workforce diversity at a global technology company.

- Resume design and interview preparation
- Insider knowledge about roles within Amazon
- Exploring career paths across different industries
- Amazon's Leadership Principles

---

### Seattle City Light — GIS Intern
*Jun 2019 – Mar 2020 | Greater Seattle Area*

- Achieved an automated map publication process to manage city block maps, saving **5 hrs/week** of manual publication work
- Collaborated with an off-site team to evaluate and create summarized data reports using **Python** and **R Studio**
- Created accurate and detailed maps for city development in a GIS environment
- Worked with legal documents to ensure smooth functioning of deployed equipment throughout the city

---

### KRV Healthcare & Physiotherapy — Social Media Manager
*Jun 2018 – May 2019 | Gurugram, Haryana, India (Freelance)*

- Identified target audience and key segments through in-depth social media analysis and trend research
- Drove brand awareness by **110%** through Facebook online marketing campaigns
- Grew Facebook Business page likes from **2,000 to 4,200** in 2 months

---

### University of Washington, Foster School of Business — Research Assistant
*Jan 2018 – Mar 2018 | Greater Seattle Area*

- Developed a web scraping program in **Python** and **R** to download public data — collected over **10,000 hotel reviews** and locational records, enriching research efficiency by over **50%**
- Conceptualized and implemented a data storage pipeline, leading to **10x** improvement in query performance
- Examined and logged research data to ensure data quality, increasing research accuracy by **20%**

---

## Personal Projects

### LetsGoSEA Web Application
*ASP.NET, C#, Razor, JavaScript, Bootstrap CSS, NUnit*
[Azure](https://5110csi.azurewebsites.net/) | [GitHub](https://github.com/zwang4-code/TheCSharpInvestigators)

- Created a **full-stack** web application that allows users to explore beautiful Seattle neighborhoods
- Implemented **RESTful APIs** with **CRUD** features including rate, comment, and upload/delete images
- Integrated **Google Maps API** to display neighborhood location
- Conducted defensive programming in test-driven development, achieving **100% code coverage**
- Collaborated using Agile methodology while leveraging Git for version control

### Maze Runner
*Python, Socket, Multithreading*
[GitHub](https://github.com/Nirmalya24/maze-runner)

- **Led** development of a digital multiplayer maze runner game for users to compete against each other
- Managed account authentication, query handling, and data transfer with **Socket**, **TCP/IP, and RPCs**
- Implemented multiplayer concurrency using **thread pool and mutex lock**

---

## Education

**Master of Science — Computer Science (Software Engineering)**
Seattle University | December 2023 | Seattle, WA
- Award: Winner of ACM Club Project Competition, Winter '21 — Werewolf Online Game

**Bachelor of Arts — Geography**
University of Washington | Sept 2016 – Mar 2020 | Seattle, WA
- Award: Senior Year Dean's List
- Leadership: Community Manager, Plenum (Undergraduate Geography Research Journal)

---

## Skills

Python, FastAPI, REST API, Docker, Kubernetes, Terraform, HashiCorp Vault, Cloud Architecture & Orchestration, AWS (Lambda, S3, EC2, API Gateway, DynamoDB, Route53), Azure (VNet, Express Route, AKS), GCP (GKE, Cloud NAT, PSC), GitHub Actions, JFrog Artifactory, Shell Scripting, JavaScript, ReactJS, NodeJS, C++, PostgreSQL, MySQL, Git, Linux
