# Hi, I'm Rayen Mabrouk

**Cloud & DevOps engineering student** building and securing cloud platforms: Terraform-managed AWS, containers on ECS Fargate and Kubernetes, security-gated CI/CD, and secure networking.

Final year at EPI Digital School (Sousse, Tunisia), looking for a **4–6 month end-of-studies internship (PFE) from February 2027**. Open to any location in Tunisia. Working languages: Arabic, French, English.

---

## What I've built

### [EPIConnect](https://github.com/rayenmabrouk/EPIConnect): AWS migration and DevSecOps pipeline
Django/PostgreSQL campus platform moved from a single Azure VM to AWS ECS Fargate behind an ALB, with RDS in private subnets, S3 pre-signed uploads and Secrets Manager, all in Terraform. GitHub Actions pipeline with 10 blocking security gates, build-once delivery, smoke test and automatic rollback.

### [CloudPulse](https://github.com/rayenmabrouk/cloudpulse): AWS platform around an open-source app
3 Terraform modules, approval-gated plan/apply, keyless deploys through SSM, health-checked rollback proven with a deliberately broken image, encrypted backups, CloudWatch alarms and Prometheus/Grafana. About $16/month, with no NAT gateway or load balancer.

### [hybrid-ipsec-vpn](https://github.com/rayenmabrouk/hybrid-ipsec-vpn): on-prem to AWS
IKEv2/IPsec tunnel with hybrid post-quantum key exchange (ECDH P-384 + ML-KEM-768), offline PKI, Terraform and Ansible, and 11 documented tests.

### [epiconnect-k8s](https://github.com/rayenmabrouk/epiconnect-k8s): self-hosted Kubernetes
3-node k3s cluster built with 9 Ansible roles; Helm, StatefulSet, default-deny NetworkPolicy and 5 failure drills.

### [pulseboard](https://github.com/rayenmabrouk/pulseboard): Node.js on Kubernetes
Containerised Node.js service published to Docker Hub and deployed on k3s on AWS EC2, with probes and a pod-deletion self-healing test.

---

## Toolbox

| | |
|---|---|
| **Cloud** | AWS (ECS Fargate, EC2, VPC, RDS, S3, ECR, IAM, CloudWatch, SSM), Azure (Firewall, UDR, peering, Private DNS, Monitor) |
| **IaC & automation** | Terraform, Ansible |
| **Containers** | Docker, Kubernetes (k3s), Helm |
| **CI/CD & security** | GitHub Actions, Trivy, Checkov, CodeQL, gitleaks, OWASP ZAP |
| **Observability** | CloudWatch, Prometheus, Grafana |
| **Networking** | TCP/IP, OSPF, IPsec VPN, PKI, Wireshark |
| **Code** | Linux, Bash, Python, PostgreSQL, Git |

## Credentials

Verifiable on [Credly](https://www.credly.com/users/rayenmabrouk9): AWS Skill Builder knowledge badges, AWS Academy, Google Cloud, Cisco Networking Academy.
Microsoft Applied Skills: Azure networking security and Azure Monitor.

## Contact

[rayenmabrouk9@gmail.com](mailto:rayenmabrouk9@gmail.com)
