<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2EA3F2&height=220&section=header&text=Aman%20Jain&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=Site%20Reliability%20Engineer%20%7C%20DevOps%20%7C%20Cloud%20Infrastructure&descAlignY=58&descSize=18&animation=fadeIn" width="100%"/>

<img src="https://komarev.com/ghpvc/?username=imaman4000&label=PROFILE%20UPTIME&color=2EA3F2&style=for-the-badge" />
<img src="https://img.shields.io/badge/MTTR-Reduced-success?style=for-the-badge" />
<img src="https://img.shields.io/badge/STATUS-open%20to%20work-brightgreen?style=for-the-badge" />

</div>

<br>

```
$ whoami
aman-jain — Information Systems Engineer (SRE) @ HCLSoftware

$ uptime
4 years, 6+ months | load average: automation, kubernetes, terraform

$ cat mission.txt
Build infrastructure so reliable, nobody remembers it's there.
```

<br>

## 🗺️ Infrastructure Map

Rather than a bullet list, here's how the pieces of my stack actually connect in production — this renders as a live diagram directly on GitHub:

```mermaid
flowchart LR
    Dev["👨‍💻 Code Push"] --> Git["Git / GitHub"]
    Git --> CI["Jenkins CI/CD"]
    CI --> SQ["SonarQube\nQuality Gate"]
    SQ --> Build["Docker Multi-stage\nBuild"]
    Build --> ECR["AWS ECR"]
    ECR --> CD["Helm Deploy"]
    CD --> EKS["AWS EKS\n20+ Microservices"]
    EKS --> CW["CloudWatch"]
    EKS --> Prom["Prometheus + Grafana"]
    CW --> PD["PagerDuty\nOn-call"]
    Prom --> PD
    Terra["Terraform Modules"] -.provisions.-> EKS
    Terra -.provisions.-> RDS["AWS RDS"]
    Terra -.provisions.-> VPC["VPC / IAM / S3"]
    Ansible["Ansible Playbooks"] -.configures.-> EKS

    style EKS fill:#2EA3F2,color:#fff
    style CI fill:#D24939,color:#fff
    style Terra fill:#7B42BC,color:#fff
    style Prom fill:#F46800,color:#fff
```

<br>

## 📟 System Metrics — Career Edition

<div align="center">

| Metric | Value | Trend |
|:--|:--:|:--:|
| Production Uptime Maintained | **99.95%** | 🟢 Stable |
| Deployment Cycle Time | **↓ 80%** | 🟢 Improved |
| Infrastructure Cost | **↓ 25%** | 🟢 Optimized |
| Legacy Apps Containerized | **10+** | 🟢 Migrated |
| Microservices Managed (EKS) | **20+** | 🟢 Live |
| Experience | **4.6+ yrs** | 🔵 Growing |

</div>

<br>

## 🧩 Stack Breakdown

<table>
<tr>
<td width="50%" valign="top">

**Orchestration & Containers**

<a href="https://www.docker.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" width="42" title="Docker"/></a>
<a href="https://kubernetes.io/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/kubernetes/kubernetes-plain.svg" width="42" title="Kubernetes"/></a>
<a href="https://helm.sh/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/helm/helm-original.svg" width="42" title="Helm"/></a>
<a href="https://aws.amazon.com/eks/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" width="42" title="AWS EKS"/></a>

[Docker](https://www.docker.com/) · [Docker Compose](https://docs.docker.com/compose/) · [Kubernetes](https://kubernetes.io/) · [AWS EKS](https://aws.amazon.com/eks/) · [Helm](https://helm.sh/) · Container Registries

</td>
<td width="50%" valign="top">

**CI/CD & GitOps**

<a href="https://www.jenkins.io/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/jenkins/jenkins-original.svg" width="42" title="Jenkins"/></a>
<a href="https://git-scm.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original-wordmark.svg" width="42" title="Git"/></a>
<a href="https://github.com/features/actions" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/githubactions/githubactions-original.svg" width="42" title="GitHub Actions"/></a>
<a href="https://www.sonarsource.com/products/sonarqube/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/sonarqube/sonarqube-original.svg" width="42" title="SonarQube"/></a>

[Jenkins](https://www.jenkins.io/) · [Git](https://git-scm.com/) · [GitHub Actions](https://github.com/features/actions) · GitFlow · [SonarQube](https://www.sonarsource.com/products/sonarqube/) Gates

</td>
</tr>
<tr>
<td width="50%" valign="top">

**Cloud — AWS**

<a href="https://aws.amazon.com/ec2/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" width="42" title="AWS"/></a>
<a href="https://aws.amazon.com/s3/" target="_blank"><img src="https://img.icons8.com/color/48/amazon-s3.png" width="42" title="S3"/></a>
<a href="https://aws.amazon.com/rds/" target="_blank"><img src="https://img.icons8.com/color/48/amazon-rds.png" width="42" title="RDS"/></a>
<a href="https://aws.amazon.com/lambda/" target="_blank"><img src="https://img.icons8.com/color/48/amazon-lambda.png" width="42" title="Lambda"/></a>

[EC2](https://aws.amazon.com/ec2/) · [S3](https://aws.amazon.com/s3/) · [VPC](https://aws.amazon.com/vpc/) · [IAM](https://aws.amazon.com/iam/) · [RDS](https://aws.amazon.com/rds/) · [Lambda](https://aws.amazon.com/lambda/) · [Route 53](https://aws.amazon.com/route53/) · Auto Scaling · [CloudWatch](https://aws.amazon.com/cloudwatch/)

</td>
<td width="50%" valign="top">

**IaC & Scripting**

<a href="https://www.terraform.io/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/terraform/terraform-original.svg" width="42" title="Terraform"/></a>
<a href="https://www.ansible.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/ansible/ansible-original.svg" width="42" title="Ansible"/></a>
<a href="https://www.gnu.org/software/bash/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bash/bash-original.svg" width="42" title="Bash"/></a>
<a href="https://www.python.org/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="42" title="Python"/></a>

[Terraform](https://www.terraform.io/) Modules · [Ansible](https://www.ansible.com/) Playbooks · [Bash](https://www.gnu.org/software/bash/) · [Python](https://www.python.org/)

</td>
</tr>
<tr>
<td width="50%" valign="top">

**Observability**

<a href="https://prometheus.io/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/prometheus/prometheus-original.svg" width="42" title="Prometheus"/></a>
<a href="https://grafana.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/grafana/grafana-original.svg" width="42" title="Grafana"/></a>
<a href="https://www.dynatrace.com/" target="_blank"><img src="https://img.icons8.com/color/48/dynatrace.png" width="42" title="Dynatrace"/></a>
<a href="https://www.pagerduty.com/" target="_blank"><img src="https://img.icons8.com/color/48/pagerduty.png" width="42" title="PagerDuty"/></a>

[Prometheus](https://prometheus.io/) · [Grafana](https://grafana.com/) · [Dynatrace](https://www.dynatrace.com/) · [CloudWatch](https://aws.amazon.com/cloudwatch/) · [PagerDuty](https://www.pagerduty.com/)

</td>
<td width="50%" valign="top">

**Systems**

<a href="https://www.linux.org/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" width="42" title="Linux"/></a>
<a href="https://ubuntu.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/ubuntu/ubuntu-plain.svg" width="42" title="Ubuntu"/></a>
<a href="https://www.redhat.com/en/technologies/linux-platforms/enterprise-linux" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redhat/redhat-original.svg" width="42" title="RHEL"/></a>
<a href="https://www.centos.org/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/centos/centos-original.svg" width="42" title="CentOS"/></a>

[Linux](https://www.linux.org/) Admin · [Ubuntu](https://ubuntu.com/) · [RHEL](https://www.redhat.com/en/technologies/linux-platforms/enterprise-linux)/[CentOS](https://www.centos.org/) · systemd · Cron · Perf Tuning

</td>
</tr>
</table>

<sub>Every icon above links straight to the tool's official site.</sub>

<br>

## 🎖️ Verified Certifications

<div align="center">

<a href="https://www.credly.com/badges/2ec3c896-02d9-4347-9d4f-ad8cf1f4549b"><img src="https://images.credly.com/images/88a6405e-0f26-442a-95ed-f9b9db4c857e/linkedin_thumb_blob" width="90" /></a>
<a href="https://www.credly.com/badges/03cf1e11-6e67-4997-9a6c-6b19e674bb06"><img src="https://images.credly.com/images/0e284c3f-5164-4b21-8660-0d84737941bc/linkedin_thumb_image.png" width="90" /></a>
<a href="https://www.credly.com/badges/07260c99-7c24-45a5-9ae8-f4891d25c0ac"><img src="https://images.credly.com/images/4d4693bb-530e-4bca-9327-de07f3aa2348/linkedin_thumb_image.png" width="90" /></a>
<a href="https://www.credly.com/badges/0881ca50-6903-4071-8bcd-9a68037ab5a1"><img src="https://images.credly.com/images/00634f82-b07f-4bbd-a6bb-53de397fc3a6/linkedin_thumb_image.png" width="90" /></a>
<a href="https://www.credly.com/badges/70b7e266-6b7f-4733-875f-6e2826268090"><img src="https://images.credly.com/images/8f006312-3154-45bf-a845-4a043641e83c/linkedin_thumb_blob" width="90" /></a>
<a href="https://www.credly.com/badges/79d42eca-a94e-46fe-9658-b60b0fa7fb19"><img src="https://images.credly.com/images/834f2c8d-2d2c-4ce7-9580-02a351c31626/linkedin_thumb_image.png" width="90" /></a>
<a href="https://www.credly.com/badges/44247c98-5732-4c44-8f54-f1636440f198"><img src="https://images.credly.com/images/4b5a8636-c554-482d-bbdc-7925fb3624c3/linkedin_thumb_blob" width="90" /></a>
<a href="https://www.credly.com/badges/4376db7d-78fb-42bb-9084-dcd0f1f136d4"><img src="https://images.credly.com/images/44994cda-b5b0-44cb-9a6d-d29b57163073/linkedin_thumb_image.png" width="90" /></a>

</div>

| Certification | Issuer |
|:--|:--|
| [AWS Certified CloudOps Engineer – Associate](https://www.credly.com/badges/2ec3c896-02d9-4347-9d4f-ad8cf1f4549b) | Amazon Web Services |
| [AWS Certified Solutions Architect – Associate](https://www.credly.com/badges/03cf1e11-6e67-4997-9a6c-6b19e674bb06) | Amazon Web Services |
| [AWS Certified AI Practitioner](https://www.credly.com/badges/07260c99-7c24-45a5-9ae8-f4891d25c0ac) · [Early Adopter](https://www.credly.com/badges/79d42eca-a94e-46fe-9658-b60b0fa7fb19) | Amazon Web Services |
| [AWS Certified Cloud Practitioner](https://www.credly.com/badges/0881ca50-6903-4071-8bcd-9a68037ab5a1) | Amazon Web Services |
| [AWS Partner: Technical Accredited](https://www.credly.com/badges/70b7e266-6b7f-4733-875f-6e2826268090) | Amazon Web Services |
| [LFS158: Introduction to Kubernetes](https://www.credly.com/badges/44247c98-5732-4c44-8f54-f1636440f198) | The Linux Foundation |
| [Cloud Digital Leader Certification](https://www.credly.com/badges/4376db7d-78fb-42bb-9084-dcd0f1f136d4) | Google Cloud |

<br>

## 📌 Featured Deployment

<div align="center">

[![speedex_courier](https://github-readme-stats.vercel.app/api/pin/?username=imaman4000&repo=speedex_courier&theme=react&hide_border=true)](https://github.com/imaman4000/speedex_courier)

</div>

<p align="center"><i>Java · JSP/Servlets · MySQL — booking, tracking, and admin workflows for a courier management system.</i></p>

<br>

## 📊 Live Telemetry

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=imaman4000&show_icons=true&theme=react&hide_border=true&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=imaman4000&layout=compact&theme=react&hide_border=true" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=imaman4000&theme=react&hide_border=true" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=imaman4000&theme=react-dark&hide_border=true" />

</div>

<details>
<summary><b>🐍 Contribution Snake (set up once, updates itself)</b></summary>
<br>

This is a rarely-used but genuinely cool GitHub feature: a GitHub Action eats your own contribution graph like a snake game and commits the animation back into your repo automatically, so it's always fresh.

1. Create `.github/workflows/snake.yml` in the `imaman4000/imaman4000` repo with the [Platane/snk](https://github.com/Platane/snk) action.
2. It generates `github-contribution-grid-snake.svg` on a schedule.
3. Embed it here:

```md
![snake](https://raw.githubusercontent.com/imaman4000/imaman4000/output/github-contribution-grid-snake.svg)
```

</details>

<br>

## 📮 Incident Response (a.k.a. Contact)

<div align="center">

<a href="https://www.linkedin.com/in/aman-jain-973b151b7/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:amanjain15799@gmail.com?subject=Let%27s%20Connect&body=Hi%20Aman%2C%0A%0A" target="_blank"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://mail.google.com/mail/?view=cm&fs=1&to=amanjain15799@gmail.com&su=Let%27s%20Connect" target="_blank"><img src="https://img.shields.io/badge/Compose%20in%20Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>

</div>

<p align="center"><sub>The first button opens your default mail app; the second opens Gmail directly in your browser with the message pre-addressed — use whichever actually works on your machine.</sub></p>

<br>

<div align="center">
<i>postmortem.log → "No root cause found. System performed exactly as designed: reliably, and without drama."</i>
</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2EA3F2,50:203A43,100:0F2027&height=120&section=footer" width="100%"/>
