
## 1. What is DevOps?

DevOps is a culture and practice that combines development and operations to deliver software faster, reliably, and with automation.

**Real-life:**
Manual releases taking weeks were reduced to multiple safe releases per day using CI/CD.

---

## 2. What DevOps tools have you used?

AWS, Git, Jenkins, Docker, Kubernetes, Terraform, CloudWatch, Prometheus, Grafana.

**Real-life:**
AWS for infrastructure, Jenkins for CI, Docker for packaging, Kubernetes for orchestration.

---

## 3. Explain CI/CD

CI automates build and testing.
CD automates deployment to environments.

**Real-life:**
Code push → Jenkins pipeline → Docker image → deploy to EC2/EKS.

---

## 4. Describe your CI/CD pipeline

* Code pushed to Git
* Jenkins triggers build
* Tests executed
* Docker image built
* Image pushed to ECR
* Deployment to EC2/EKS

---

## 5. What is Git?

Git is a version control system to track and manage code changes.

**Real-life:**
Used feature, develop, and main branches with pull requests.

---

## 6. Git merge vs rebase

* Merge preserves history
* Rebase creates linear history

**Real-life:**
Used merge to maintain audit trail.

---

## 7. What is Jenkins?

Jenkins is an automation server used for building CI/CD pipelines.

**Real-life:**
Configured Jenkins to trigger pipelines on every commit.

---

## 8. Jenkins Freestyle vs Pipeline

* Freestyle: UI-based
* Pipeline: Code-based (Jenkinsfile)

**Real-life:**
Used pipeline-as-code for version control and rollback.

---

## 9. What is Docker?

Docker packages applications and dependencies into containers.

**Real-life:**
Eliminated “works on my machine” issues.

---

## 10. Docker image vs container

* Image: Blueprint
* Container: Running instance

---

## 11. Why use Docker?

Consistency, portability, faster deployments.

---

## 12. What is Kubernetes?

Kubernetes manages container deployment, scaling, and self-healing.

**Real-life:**
Automatically restarted failed containers.

---

## 13. Kubernetes vs Docker Swarm

Kubernetes is more scalable and enterprise-ready.

---

## 14. What is EKS?

Amazon EKS is a managed Kubernetes service.

**Real-life:**
AWS managed control plane, we managed workloads.

---

## 15. What is EC2?

EC2 is a virtual server in AWS.

**Real-life:**
Backend APIs hosted on EC2 with Auto Scaling.

---

## 16. What is Auto Scaling?

Automatically adjusts EC2 instances based on load.

---

## 17. What is Load Balancer?

Distributes traffic across multiple servers.

**Real-life:**
Used ALB to avoid single point of failure.

---

## 18. What is S3?

Object storage service in AWS.

**Real-life:**
Stored logs, backups, and static assets.

---

## 19. S3 vs EBS

* S3: Object storage
* EBS: Block storage for EC2

---

## 20. What is IAM?

Identity and Access Management for AWS.

**Real-life:**
Used IAM roles instead of access keys.

---

## 21. IAM User vs Role

User: Human access
Role: Service-to-service access

---

## 22. What is VPC?

Virtual Private Cloud – private network in AWS.

---

## 23. Public vs Private Subnet

Public: Internet access
Private: No direct internet

---

## 24. What is Security Group?

Instance-level firewall.

---

## 25. What is CloudWatch?

Monitoring and logging service.

**Real-life:**
CPU alarms triggered scaling actions.

---

## 26. What is CloudTrail?

Tracks AWS API activity.

**Real-life:**
Identified who deleted a resource.

---

## 27. What is Infrastructure as Code?

Managing infrastructure using code.

**Real-life:**
Used Terraform to create EC2, ALB, and ASG.

---

## 28. Terraform vs CloudFormation

Terraform is cloud-agnostic.

---

## 29. What is Blue-Green Deployment?

Two environments; traffic switched after validation.

---

## 30. What is Canary Deployment?

Release to small user percentage first.

---

## 31. How do you manage secrets?

AWS Secrets Manager, environment variables.

---

## 32. How do you secure CI/CD pipelines?

Least privilege IAM, no hardcoded secrets, code scanning.

---

## 33. Monitoring vs Logging

Monitoring: Metrics
Logging: Events and details

---

## 34. SLA, SLO, SLI

Metrics used to measure reliability.

---

## 35. What is rollback?

Reverting to last stable version.

---

## 36. Handling production failure

Check monitoring → rollback → RCA.

---

## 37. High Availability

System remains available even if components fail.

---

## 38. Disaster Recovery

Restoring systems after major failures.

---

## 39. Backup strategy

Snapshots and S3 backups.

---

## 40. Horizontal vs Vertical Scaling

Horizontal: Add servers
Vertical: Increase server size

---

## 41. Container orchestration

Managing containers at scale.

---

## 42. Health check

Checks if application is running properly.

---

## 43. Reducing AWS cost

Right sizing, auto scaling, spot instances.

---

## 44. What is AMI?

Template for launching EC2 instances.

---

## 45. What is Bastion Host?

Secure jump server to access private resources.

---

## 46. Monitoring tools used

CloudWatch, Prometheus, Grafana.

---

## 47. Log aggregation

Centralizing logs from multiple systems.

---

## 48. What happens if a pod crashes?

Kubernetes restarts it automatically.

---

## 49. Biggest DevOps challenge faced

Manual deployments causing downtime; solved using CI/CD.

---

## 50. Why should we hire you?

I have hands-on AWS DevOps experience, strong CI/CD knowledge, and focus on automation, stability, and production reliability.

---

## ✅ Final Tip
