
## DevOps – Complete Breakdown with Tools

> **DEF-==DevOps is a set of practices, tools, and cultural philosophies that automate and integrate software development and IT operations to deliver applications faster and more reliably.**==

DevOps spans the **entire software delivery & operations lifecycle**.

### DevOps Lifecycle (Simple View)

```
Plan → Code → Build → Test → Release → Deploy → Operate → Monitor → Improve
```

### DevOps Engineer Core Skill Stack (Summary)

|Area|Must Know|
|---|---|
|Linux & Networking|✅|
|Git & CI/CD|✅|
|Cloud (AWS/Azure/GCP)|✅|
|Docker & Kubernetes|✅|
|IaC (Terraform)|✅|
|Monitoring & Security|✅|


### 1. Planning & Collaboration

**Purpose**
	- Requirements
	- Agile planning
	- Team collaboration
	- Issue tracking
**Tools**
	- Jira
	- Azure Boards
	- Trello
	- Asana
	- Confluence
	- Slack
	- Microsoft Teams

## 2. Source Code Management (SCM)

**Purpose**
	- Version control
	- Code collaboration
	- Branching strategies
**Tools**
	- Git (core technology)
	- GitHub
	- GitLab
	- Bitbucket
	- Azure Repos

## 3. Build Automation

**Purpose**
	- Compile code
	- Manage dependencies
	- Create build artifacts
**Tools**
	- Maven
	- Gradle
	- Ant
	- npm / yarn
	- MSBuild

## 4. Continuous Integration (CI)

**Purpose**
	- Automatically build & test on every commit
	- Catch bugs early
**Tools**
	- Jenkins
	- GitHub Actions
	- GitLab CI
	- CircleCI
	- Travis CI
	- Azure DevOps Pipelines

## 5. Automated Testing

**Purpose**
	- Ensure code quality
	- Prevent regressions

### Unit Testing

- JUnit
- TestNG
- pytest
- NUnit

### Integration & Functional Testing

- Selenium
- Cypress
- Playwright

### Performance & Load Testing

- JMeter
- Gatling
- Locust

### Code Quality & Security

- SonarQube
- ESLint
- Checkstyle

## 6. Artifact & Package Management

**Purpose**
	- Store build outputs
	- Versioned binaries
**Tools**
	- Nexus Repository
	- JFrog Artifactory
	- GitHub Packages
	- GitLab Package Registry

## 7. Continuous Delivery / Deployment (CD)

**Purpose**
	- Automated deployments
	- Environment promotion (Dev → Test → Prod)
**Tools**
	- Jenkins
	- GitHub Actions
	- GitLab CD
	- Argo CD
	- Spinnaker
	- Azure Release Pipelines

## 8. Infrastructure as Code (IaC)

**Purpose**
	- Automate infrastructure provisioning
	- Version-controlled infrastructure
**Tools**
	- Terraform
	- AWS CloudFormation
	- Azure Bicep
	- Pulumi

## 9. Configuration Management

**Purpose**
	- System configuration
	- Consistency across environments
**Tools**
	- Ansible
	- Chef
	- Puppet
	- SaltStack

## 10. Containers & Containerization

**Purpose**
	- Package applications with dependencies
	- Ensure consistency across environments
**Tools**
	- Docker
	- Podman
	- Buildah

## 11. Container Orchestration

**Purpose**
	- Manage containers at scale
	- High availability
	- Auto-scaling
**Tools**
	- Kubernetes
	- OpenShift
	- Docker Swarm

### Managed Kubernetes (Cloud)

- AWS EKS
- Azure AKS
- GCP GKE

## 12. Cloud Platforms

**Purpose**
	- On-demand infrastructure
	- Scalability & reliability
**Cloud Providers**
	- AWS
	- Microsoft Azure
	- Google Cloud Platform (GCP)

## 13. Monitoring & Observability

**Purpose**
	- Track system health
	- Metrics & alerts
	- Troubleshooting
**Tools**
	- Prometheus
	- Grafana
	- Datadog
	- New Relic
	- AWS CloudWatch
	- Azure Monitor

## 14. Logging & Log Management

**Purpose**
	- Centralized logs
	- Debugging & auditing
**Tools**
	- ELK Stack (Elasticsearch, Logstash, Kibana)
	- EFK Stack (Fluentd instead of Logstash)
	- Splunk
	- Loki

## 15. Security (DevSecOps)

**Purpose**
	- Shift security left
	- Automated security checks

### Static & Dynamic Analysis

- Snyk
- OWASP ZAP
- Checkmarx
- Trivy

### Secrets Management

- HashiCorp Vault
- AWS Secrets Manager
- Azure Key Vault

## 16. Release Management & Feature Control

**Purpose**
	- Safe releases
	- Gradual rollouts
**Tools**
	- LaunchDarkly
	- Flagger
	- Argo Rollouts

## 17. Backup, Recovery & Reliability (SRE)

**Purpose**
	- High availability
	- Disaster recovery
	- Reliability engineering
**Tools**
	- Velero (Kubernetes backup)
	- AWS Backup
	- Azure Site Recovery
	- Chaos Monkey (resilience testing)
