# README.md
Study Plan
# Cloud & AI Self Study Plan

## Goal
Build real hands-on skills in AWS and Python before focusing on certs.  
Certs will come naturally once the foundation is solid.

## Degree Context
WGU — Cloud and Networking with AWS focus.  
Certs are built into the degree, so no rush to chase them separately.

---

## Core Resources
- Cantrill (learn.cantrill.io) — networking and AWS concepts
- CS50P — Harvard Python course (edX)
- Automate the Boring Stuff with Python — practical scripting
- boto3 — Python library for AWS

---

## Tech Stack
- AWS account ($100 credits)
- AWS CLI
- GitHub
- Python (setup in Week 1)

---

## Python Learning Path
1. CS50P fundamentals (variables, functions, loops)
2. Automate the Boring Stuff (practical scripting)
3. boto3 (AWS automation)
4. AWS AI services (Bedrock, SageMaker, etc.)

---

## AWS Project Tiers

### Tier 1 — Foundations
- [ ] S3 static website (manual bucket policy)
- [ ] Lambda function (event-triggered)
- [ ] EC2 via CLI (no console clicking)

### Tier 2 — Integration
- [ ] S3 + Lambda + SNS pipeline
- [ ] EC2 + CloudWatch + alerts
- [ ] Custom VPC setup (subnets + security groups)

### Tier 3 — Real-World Style
- [ ] App on EC2/Lambda + API Gateway
- [ ] Infrastructure as Code (CloudFormation/Terraform)
- [ ] CI/CD pipeline (GitHub → AWS)

---

## AI Learning Path (Long-Term)
Focus: application + infrastructure (not heavy math)

Potential roles:
- AI Solutions Architect
- MLOps / AI Infrastructure
- AI Application Developer

Path:
1. Cloud + networking (current)
2. Python fundamentals
3. boto3 automation
4. AWS AI services
5. Build AI-powered apps
6. Specialize later

---

## Week 1 Plan

### Concepts (Mon–Tue)
- Cantrill Layer 2
- Cantrill Layer 3 (IP, routing)
- CS50P Lesson 1

### Hands-On (Wed–Thu)
- Set up Python
- CS50P Problem Set 1
- Start Automate the Boring Stuff

### Build (Fri–Weekend)
- Install boto3
- Python script: list S3 buckets
- Push to GitHub (even if messy)

---

## GitHub Documentation Habit
For every project:
- What it does
- AWS services used
- Steps taken
- Policies (JSON)
- Screenshots
- CLI commands

---

## Services Covered So Far
- EC2
- S3
- IAM
- VPC
- Lambda
- SNS
- EventBridge
- CloudWatch
- GuardDuty
- Macie

---

## Notes
- Tear down resources after use (avoid charges)
- Keep updating this doc as you progress
- Revisit Cantrill for cert prep later
- Use AWS Skill Builder closer to exams
