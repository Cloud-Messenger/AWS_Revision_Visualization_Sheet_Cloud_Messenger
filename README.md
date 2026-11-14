<div align="center">

# ☁️ AWS Revision Visualization Sheet

### *Stop memorizing AWS. Start seeing it.*

**14 topics · Animated visual explainers · Interview questions · Real production outages · Fixes**

![Cloud Messenger](https://img.shields.io/badge/Cloud%20Messenger%E2%84%A2-Learn%20%E2%80%A2%20Build%20%E2%80%A2%20Visualize-1f3a5f?style=for-the-badge)
![AWS](https://img.shields.io/badge/AWS-Revision%20Sheet-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Interview Prep](https://img.shields.io/badge/Interview-Prep-2ea44f?style=for-the-badge)
![Hashtag](https://img.shields.io/badge/%23buildwithCloudMessenger-1155cc?style=for-the-badge)

📄 **[Open the PDF sheet](AWS_Revision_Visualization_Sheet_Cloud_Messenger.pdf)**

</div>

---

## 🎯 What is this?

Most AWS notes are walls of text. This sheet is different.

Every concept is paired with **a visual explainer you can click through**, the **interview questions** that usually come with it, and a **real production outage** with the **fix**. So you don't just learn *what* a VPC or an ALB is. You learn what breaks at 2 AM, and how to bring it back.

> 💡 **One row = one complete revision loop:**
> **See it** (visual) → **Explain it** (interview question) → **Break it** (production outage) → **Fix it** (resolution)

---

## 🗺️ What's inside

| # | Topic | Jump to the visual |
|---|-------|--------------------|
| 1 | **Cloud Fundamentals** (IaaS/PaaS/SaaS, deployment models, hypervisor, economics, Well-Architected, global infra) | [Service models](https://tejasskamble.github.io/cloud-service-models-visualizer/) · [Hypervisor](https://cloud-messenger.github.io/Virtualization-in-AWS-Hypervisor-Visual/) · [Well-Architected](https://cloud-messenger.github.io/AWS-Well-Architected-Framework-Visual/) |
| 2 | **Creating EC2** (Windows, Amazon Linux, Ubuntu, Red Hat) | [Amazon Linux](https://vinitshimpi4-cell.github.io/Ec2-amazon-linux-Visuals/) · [Ubuntu](https://cloud-messenger.github.io/ubuntu-ec2-visual/) |
| 3 | **SSH Clients** (CMD, PuTTY, MobaXterm, Git Bash) | [PuTTY](https://suraj-sanap.github.io/Amazon-linux-throug-putty/) · [MobaXterm](https://cloud-messenger.github.io/amazon-linux-mobaxterm-visual/) |
| 4 | **Turning Linux into a Web Server** | [Visual](https://parth-deshmukh-2004.github.io/Converting-Linux-Into-Web-Server-Visual/) |
| 5 | **Web Servers** (Apache, Nginx) | [Apache](https://vinitshimpi4-cell.github.io/Apache-server-visuals/) · [Nginx](https://vinitshimpi4-cell.github.io/Nginx-Server-visuals/) |
| 6 | **Elastic Load Balancing** (ALB, NLB) | [ALB](https://vinitshimpi4-cell.github.io/Load-Balancer-Visual/) · [NLB](https://mohitlohar1555-oss.github.io/Load-Balancer-visual/) |
| 7 | **Bastion Host / Jump Server** | [Visual](https://vinitshimpi4-cell.github.io/Bastion-Hosting-visuals/) |
| 8 | **S3 Website Hosting with CloudFront** | [Visual](https://ganeshnayak6622.github.io/aws-s3-cloudfront-visualizer/) |
| 9 | **Real-Time CPU Monitoring** (CloudWatch + SNS) | [Visual](https://abhijeetya01.github.io/cloudwatch-sns-visualization/) |
| 10 | **AWS CLI ↔ Console** (IAM users) | [Visual](https://vinitshimpi4-cell.github.io/gui-to-cli/) |
| 11 | **Databases on EC2** (MySQL, MariaDB, DynamoDB) | [RDS ↔ EC2](https://cloud-messenger.github.io/rds-ec2-connection-visual/) |
| 12 | **VPC** (subnets, IGW, NAT, SG, NACL, peering, Transit Gateway) | [VPC](https://cloud-messenger.github.io/vpc-visualization/) · [3-Tier](https://tejasskamble.github.io/aws-3tier-visualizer/) |
| 13 | **Serverless with Lambda** | [Visual](https://cloud-messenger.github.io/aws-serverless-lambda-visualizer/) |
| 14 | **ECS · ECR · Fargate** | [Visual](https://cloud-messenger.github.io/ecs-ecr-fargate-visual/) |

> The PDF lists **every** visualization link, interview question, outage and fix for each topic. The table above is just the quick-start.

---

## 🚀 How to use it

1. **Pick a topic** from the table, or open the PDF and start at row 1.
2. **Watch the visual first.** Don't read anything else yet.
3. **Cover the answer column** and try the interview question out loud.
4. **Read the production outage** and diagnose it before you look at the fix.
5. **Re-visit** the topics where your diagnosis was wrong.

**Great for:** AWS certification prep · DevOps / cloud interviews · on-call readiness · onboarding junior engineers · quick revision before a deployment

---

## 🧠 A taste of the outages you'll troubleshoot

- 🔥 ALB returns **502 Bad Gateway** after a production deployment
- 🔥 NGINX returns **504 Gateway Timeout** during peak traffic
- 🔥 Private EC2 instances **can't reach the internet** (route table / NAT mistakes)
- 🔥 CloudWatch alarm is in **ALARM** but the **SNS email never arrives**
- 🔥 Website shows an **old version** after deployment (CloudFront caching)
- 🔥 IAM access keys **accidentally pushed to GitHub**

Each one comes with the cause to look for and the fix to apply.

---

## 📁 Repository structure

```text
.
├── README.md
└── AWS_Revision_Visualization_Sheet_Cloud_Messenger.pdf   # the full sheet (4 pages, clickable links)
```

---

## 🤝 Contributing

Found a broken link? Have a better interview question or a production outage you've actually lived through?

1. Fork this repo
2. Create a branch: `git checkout -b improve-topic-name`
3. Commit your change and open a Pull Request

Please keep the same format: **Concept → Visual → Interview Question → Outage → Fix.**

---

## ⚖️ Copyright & attribution

© 2026 Cloud Messenger™. All rights reserved.
The compilation, structure, visual design, layout, illustrations, and branding of this sheet are original creative work of Cloud Messenger™ & Team. Cloud Messenger™ is a trademark of Open-Pathshala.

Please provide appropriate attribution when sharing or referencing this sheet.

---

## ☁️ About Cloud Messenger™

Cloud Messenger™ is focused on making **Cloud Computing, DevOps, and emerging technologies visual, practical, and accessible to everyone.**

**Our learning philosophy:** `Learn` • `Build` • `Visualize` • `Troubleshoot` • `Grow`

| | |
|---|---|
| 🌐 **Website** | [cloudmessenger.in](https://cloudmessenger.in) |
| 💼 **LinkedIn** | [linkedin.com/in/cloud-messenger](https://www.linkedin.com/in/cloud-messenger) |
| 🐙 **GitHub** | [github.com/Cloud-Messenger](https://github.com/Cloud-Messenger) |
| 🏷️ **Community Hashtag** | #buildwithCloudMessenger |

<div align="center">

**If this sheet helped you, give the repo a ⭐ and share it with someone preparing for AWS.**

*Learn • Build • Visualize • Troubleshoot • Grow*

</div>
