## Hi, I'm Tadiwa 👋

Backend developer and cybersecurity graduate (B.S. Cybersecurity, 2026) focused on cloud security, secure software development, and infrastructure automation. **Open to Cloud Security, DevSecOps, and SOC roles.**

I build RESTful APIs, database-driven applications, containerized services, and cloud security pipelines that detect, prevent, and respond to threats. I'm interested in cloud security engineering, infrastructure as code, and AI.

## Technical Focus

**Cloud & Security**
- AWS (EC2, RDS, S3, IAM, CloudTrail, GuardDuty, EventBridge, Lambda)
- Terraform (Infrastructure as Code)
- Checkov (static analysis), Trivy (container image scanning), and GitHub Actions (CI)
- IAM policy design, threat detection, MITRE ATT&CK

**Backend & Languages**
- Java, Python (boto3, Slack Bolt), SQL, Bash
- Spring Boot, Django, Flask
- RESTful APIs, OpenAPI/Swagger, automated testing
- PostgreSQL, MySQL, Redis

**Tools & Systems**
- Docker, Docker Compose
- Git, GitHub, Linux (RHEL 8/9)
- Networking fundamentals (Cisco CCNA: Introduction to Networks)
- Authentication, MFA, secure application design

## Featured Projects

**[Cloud SIEM Detection Lab](https://github.com/tadiwah-alt/cloud-siem-detection-lab)**
A detect, prevent, respond pipeline built entirely in Terraform on AWS. CloudTrail logs to S3, and GuardDuty findings are documented against MITRE ATT&CK. An EventBridge rule triggers a Lambda function that disables compromised IAM access keys. Checkov scans every push through GitHub Actions, and each accepted risk is documented. The repo includes a debugging write-up.
*Stack: Terraform, AWS, Python, GitHub Actions*

**[Container Scanning Pipeline](https://github.com/tadiwah-alt/container-scanning-pipeline)** *(in progress)*
A GitHub Actions pipeline that builds a Flask API image and scans it with Trivy, failing the build on fixable HIGH and CRITICAL findings. The baseline scan found 44 OS-level findings (8 unique CVEs, none yet patched upstream) and 2 fixable Python findings. Next: hardening the Dockerfile (pinned versions, non-root user, `.dockerignore`) and documenting the before and after.
*Stack: Docker, Trivy, GitHub Actions*

**[Cybersecurity RAG Education System](https://github.com/tadiwah-alt/cybersecurity-rag-capstone)**
Team capstone: a Python retrieval-augmented generation system using ChromaDB and OpenAI APIs, with custom retrieval evaluation metrics and a Streamlit dashboard. I served as Lead AI & Application Security Developer.
*Stack: Python, ChromaDB, OpenAI API, Streamlit*

**[Dockerized Banking Application](https://github.com/tadiwah-alt/cloud-banking-api)**
Flask and PostgreSQL application containerized with Docker Compose, with environment-based configuration and deployment documentation.
*Stack: Flask, PostgreSQL, Docker Compose*

**[PL FootSmart](https://github.com/tadiwah-alt/pl-it-bot)** *(in progress)*
A Slack bot that explains IT concepts through Premier League analogies. It has a no-repeat fact command and an interactive quiz with answer checking and input validation. Built with Python, Slack Bolt, and Socket Mode, with secrets kept out of source control.
*Stack: Python, Slack Bolt*

## Currently Learning

- AWS Solutions Architect Associate (in progress)
- Data structures and algorithms in Python
- Container and supply chain security
- AI-assisted security tooling and LLM security

## Contact

- LinkedIn: [linkedin.com/in/tadiwa-hukuimwe-6a9159249](https://www.linkedin.com/in/tadiwa-hukuimwe-6a9159249)
- Email: tadiwahukuimwe@gmail.com
