👋 Hi, I'm Sadagana Atchutha Rao
☁️ AWS Cloud & DevOps Trainee | ECE Graduate | Aspiring Cloud & DevOps Engineer
Bash
$ cat profile.json
{
  "Name": "Sadagana Atchutha Rao",
  "Education": "B.Tech in Electronics and Communication Engineering",
  "Role": "AWS Cloud & DevOps Trainee",
  "Focus": ["Infrastructure as Code", "CI/CD Pipeline Automation", "AWS Multi-Tier Architecture"],
  "Achievement": "IEEE Best Paper Award Recipient 🥇",
  "Motto": "Learn ➔ Build ➔ Automate ➔ Deploy ➔ Improve 🚀"
}
👨‍💻 About Me
🎓 B.Tech Graduate in Electronics and Communication Engineering

☁️ AWS Cloud & DevOps Trainee with hands-on experience in AWS Cloud infrastructure design & deployment

🐧 Proficient in Linux administration and EC2 instance management

🔧 Hands-on with Git, GitHub, Maven, Jenkins, and end-to-end CI/CD automation

⚙️ Skilled in Ansible configuration management and infrastructure automation

📦 Experienced with SonarQube, Nexus Repository, and artifact management pipelines

🌐 Practical experience deploying applications on Apache Tomcat

📊 Focused on high availability, automated backup strategies, and monitoring

🏗️ Designed and deployed enterprise AWS 3-Tier Architectures and serverless workflows

🏆 IEEE Best Paper Award recipient at an IEEE conference hosted by NIT Meghalaya

📚 Continuous learner focused on cloud native and automation practices

🛠️ Technical Skills & Ecosystem
☁️ Cloud Platforms & Core Infrastructure
🔧 DevOps & CI/CD Toolchain
🐧 Operating Systems & Databases
🔨 Developer Utilities
🚀 DevOps & AWS Projects
🔥 1. Automated CI/CD Deployment Pipeline
Plaintext
[ Developer ] ➔ [ GitHub ] ──(Webhook)──► [ Jenkins CI/CD ]
                                                │
          ┌─────────────────────────────────────┼─────────────────────────────────────┐
          ▼                                     ▼                                     ▼
   (Checkout / Build)                  (SonarQube Analysis)                  (Store Artifact)
      Apache Maven                         Code Quality                        Nexus / AWS S3
                                                │                                     │
                                                └──────────────────┬──────────────────┘
                                                                   ▼
                                                       [ Ansible Automation ]
                                                                   │
                                                                   ▼
                                                       [ Tomcat Worker Nodes ]
Tech Stack: GitHub, Jenkins, Maven, SonarQube, Nexus Repository, AWS S3, Ansible, Apache Tomcat, AWS EC2.

Key Implementation Highlights:

Configured Jenkins & Ansible integration on AWS EC2 nodes with SSH authentication.

Automated application building using Maven and generated .war artifacts.

Enforced Quality Gates using SonarQube scanning for bugs, code smells, and vulnerabilities.

Automated artifact archiving to Nexus Repository and Amazon S3.

Executed automated application deployments onto Tomcat server nodes using Ansible playbooks with Dev/Test/Prod parameterization.

🏗️ 2. AWS 3-Tier High-Availability Architecture
Plaintext
                              Route 53 (DNS)
                                    │
                            CloudFront (CDN)
                                    │
                         External ALB (Public)
                                    │
                 ┌──────────────────┴──────────────────┐
                 ▼                                     ▼
           Web Layer (EC2)                       Web Layer (EC2)
                 │                                     │
                 └──────────────────┬──────────────────┘
                                    ▼
                          Internal ALB (Private)
                                    │
                        Application Layer (EC2 ASG)
                                    │
                          Internal ALB (Private)
                                    │
                           Database Layer (RDS)
AWS Services: VPC, Public & Private Subnets, Security Groups, EC2, ALB, Auto Scaling, RDS MySQL, ACM, Route 53, CloudFront, S3.

Key Implementation Highlights:

Provisioned secure networking layout isolating Database and Application tiers inside private subnets.

Configured Application Load Balancers (ALB) and Auto Scaling groups to achieve high availability.

Attached AWS Certificate Manager (ACM) SSL/TLS certificates and routed traffic globally via Route 53 and CloudFront.

⚡ 3. Serverless Workflows
📬 Employee Management System
Plaintext
S3 ➔ API Gateway ➔ Producer Lambda ➔ SQS Queue ➔ Consumer Lambda ➔ DynamoDB
Built an asynchronous processing pipeline decoupling API traffic using SQS queues and storing record states in Amazon DynamoDB.

📝 Serverless Registration System
Plaintext
S3 ➔ API Gateway ➔ AWS Lambda ➔ Amazon RDS (MySQL)
Designed a lightweight web application architecture processing incoming registration requests directly into Amazon RDS.

🚀 4. Full-Stack AWS Application Deployment
Plaintext
User ➔ Nginx ➔ React Frontend ➔ Node.js API ➔ Redis Cache ➔ Amazon RDS (MySQL)
Deployed a multi-tier microservice stack incorporating Nginx reverse proxying, Redis in-memory caching, and RDS relational database backends.

☁️ AWS Skill & Service Deep-Dive
**🔍 Expand to View Detailed AWS Capabilities**

Compute & Automation: EC2, Lambda, Auto Scaling, Apache setup via User Data, CloudWatch EventBridge automation for EC2 power scheduling.

Storage & Backups: EBS volume resizing (30GB to 50GB live), EBS encrypted snapshots, AMI cross-region replication, EFS, DataSync, DLM lifecycle management.

Networking & Security: Custom VPCs, Public/Private Subnets, Route Tables, IGW, NAT Gateways, Security Groups, NACLs, VPC Endpoints, VPC Peering, Transit Gateway, IAM roles & policies.

Databases & Caching: RDS (MySQL & PostgreSQL) Multi-AZ deployments, Read Replica promotion, DynamoDB, ElastiCache (Redis & Memcached caching policies).

Migration & Analytics: AWS DMS, AWS DataSync migrations from S3 to EFS, Storage Gateway.

IaC & Management: Infrastructure provisioning using CloudFormation stacks, AWS Systems Manager.

🏆 Honors & Achievements
🥇 IEEE Best Paper Award
Paper Title: Impact of Thermal Induced Resonant Frequency Shift on Resonant Inverters

Conference: IEEE International Conference hosted by NIT Meghalaya

Core Research: Thermal drift behavior, Zero Voltage Switching (ZVS), and resonant inverter optimization.

📈 GitHub Analytics & Streak

🐍 Contribution Activity Graph
🤝 Connect With Me
[

](https://www.linkedin.com/in/sadagana-atchutha-rao/)
[

](mailto:atchuth142@gmail.com)
[

](https://github.com/Sadagana-Atchutha-Rao)
