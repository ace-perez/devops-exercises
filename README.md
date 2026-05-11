# DevOps Interview Questions

A comprehensive collection of DevOps interview questions covering fundamentals, tooling, cloud, containers, security, system design and more. Click any question to expand its answer.

---

## 📚 Table of Contents

- [🧭 DevOps Fundamentals](#devops-fundamentals) — 59 questions
- [⚙️ Scripting & Automation](#scripting-automation) — 50 questions
- [🔀 Version Control (Git)](#version-control-git) — 60 questions
- [🚀 CI/CD & DevOps Best Practices](#cicd-devops-best-practices) — 49 questions
- [🏗️ Infrastructure as Code](#infrastructure-as-code) — 60 questions
- [📦 Containers (Docker & Kubernetes)](#containers-docker-kubernetes) — 60 questions
- [☁️ Cloud Computing](#cloud-computing) — 48 questions
- [🐧 Linux & System Administration](#linux-system-administration) — 60 questions
- [🖥️ Operating Systems](#operating-systems) — 17 questions
- [🔮 Virtualization](#virtualization) — 13 questions
- [🌐 Networking](#networking) — 73 questions
- [🔗 HTTP & Load Balancers](#http-load-balancers) — 37 questions
- [📊 Monitoring, Logging & Observability](#monitoring-logging-observability) — 77 questions
- [💾 Storage](#storage) — 13 questions
- [🕸️ Distributed Systems](#distributed-systems) — 8 questions
- [🏛️ System Design](#system-design) — 55 questions
- [🧪 Testing](#testing) — 19 questions
- [🔧 Hardware](#hardware) — 14 questions
- [📦 Release Management](#release-management) — 23 questions
- [🧩 Miscellaneous (API, YAML, Firmware)](#miscellaneous-api-yaml-firmware) — 32 questions
- [💬 Questions To Ask Interviewers](#questions-to-ask-interviewers) — 7 questions
- [🏢 Real-World Case Studies](#real-world-case-studies) — 10 questions

---

## 🧭 DevOps Fundamentals

### 🟢 Beginner

<details>
<summary><b>What is DevOps?</b></summary>

DevOps is a set of practices that combine software development (Dev) and IT operations (Ops) to improve collaboration, automate workflows, and accelerate software delivery.

</details>

<details>
<summary><b>What are the main goals of DevOps?</b></summary>

Faster delivery of software
Improved collaboration between teams
Automation of repetitive tasks
Continuous feedback and improvement

</details>

<details>
<summary><b>What are the key components of DevOps?</b></summary>

CI/CD (Continuous Integration/Continuous Deployment)
Infrastructure as Code (IaC)
Monitoring and Logging
Collaboration and Communication

</details>

<details>
<summary><b>How does DevOps differ from traditional IT operations?</b></summary>

DevOps focuses on automation, collaboration, and continuous feedback, whereas traditional IT operations follow a siloed approach with manual deployments and slow release cycles.

</details>

<details>
<summary><b>What is Continuous Integration (CI)?</b></summary>

CI is a practice where developers frequently integrate code into a shared repository, followed by automated testing to detect errors early.

</details>

<details>
<summary><b>What is Continuous Deployment (CD)?</b></summary>

CD is the automated release of validated code changes into production, ensuring rapid and reliable delivery.

</details>

<details>
<summary><b>What is Infrastructure as Code (IaC)?</b></summary>

IaC is managing infrastructure using code, enabling automation, consistency, and easy scalability. Examples: Terraform, CloudFormation.

</details>

<details>
<summary><b>What is version control, and why is it important?</b></summary>

Version control tracks code changes, enabling collaboration and rollback. Example: Git.

</details>

<details>
<summary><b>What are some popular version control tools?</b></summary>

Git, GitHub, GitLab, Bitbucket, Subversion (SVN).

</details>

<details>
<summary><b>What is a DevOps pipeline?</b></summary>

A DevOps pipeline automates software delivery using stages like build, test, deploy, and monitor.

</details>

<details>
<summary><b>What is containerization?</b></summary>

Containerization packages applications with dependencies, making them portable and consistent across environments. Example: Docker.

</details>

<details>
<summary><b>What are microservices?</b></summary>

Microservices are small, independent services that communicate via APIs, improving scalability and maintainability.

</details>

<details>
<summary><b>What is a monolithic vs. microservices architecture?</b></summary>

Monolithic apps have a single codebase; microservices break the application into independent, loosely coupled services.

</details>

<details>
<summary><b>What are some common DevOps automation tools?</b></summary>

CI/CD: Jenkins, GitHub Actions
Configuration Management: Ansible, Puppet
Infrastructure as Code: Terraform

</details>

<details>
<summary><b>What is Shift-Left Testing?</b></summary>

Shift-left testing integrates testing early in the development cycle to detect bugs earlier.

</details>

<details>
<summary><b>What is observability in DevOps?</b></summary>

Observability provides insights into system health using logs, metrics, and tracing.

</details>

<details>
<summary><b>What is a rollback strategy?</b></summary>

A rollback strategy reverts to a previous stable version if a new deployment fails.

</details>

<details>
<summary><b>What is the role of a DevOps Engineer?</b></summary>

A DevOps engineer bridges development and operations, focusing on automation, CI/CD, and cloud management.

</details>

<details>
<summary><b>What are feature flags in DevOps?</b></summary>

Feature flags allow toggling features on/off without deploying new code.

</details>

<details>
<summary><b>What is a blue-green deployment?</b></summary>

Blue-green deployment maintains two environments, switching traffic between them for zero-downtime updates.

</details>

### 🟡 Intermediate

<details>
<summary><b>What is Site Reliability Engineering (SRE)?</b></summary>

SRE applies software engineering principles to operations, improving reliability and scalability.

</details>

<details>
<summary><b>How does DevOps help in cloud computing?</b></summary>

DevOps automates infrastructure, deployments, and monitoring, making cloud environments scalable and efficient.

</details>

<details>
<summary><b>What is Immutable Infrastructure?</b></summary>

Immutable infrastructure replaces servers instead of modifying them, ensuring consistency and reducing drift.

</details>


<details>
<summary><b>What are the benefits of CI/CD pipelines?</b></summary>

Faster releases
Automated testing
Reduced manual errors
Enhanced collaboration

</details>

<details>
<summary><b>What is canary deployment?</b></summary>

Canary deployment gradually rolls out changes to a small user group before full deployment.

</details>

<details>
<summary><b>What are some common monitoring tools?</b></summary>

Prometheus, Grafana, ELK Stack, Datadog, New Relic.

</details>

<details>
<summary><b>What is Configuration Management in DevOps?</b></summary>

Configuration management automates infrastructure setup and maintenance. Examples: Ansible, Puppet, Chef.

</details>

<details>
<summary><b>What is GitOps?</b></summary>

GitOps manages infrastructure using Git repositories, ensuring version control and automation.

</details>

<details>
<summary><b>What is Chaos Engineering?</b></summary>

Chaos Engineering tests system resilience by introducing controlled failures.

</details>

<details>
<summary><b>What is an API gateway?</b></summary>

An API gateway manages API traffic, security, and load balancing.

</details>

<details>
<summary><b>How do you optimize CI/CD pipelines?</b></summary>

By parallelizing builds, caching dependencies, and using automated testing.

</details>

<details>
<summary><b>What is hybrid cloud in DevOps?</b></summary>

A hybrid cloud combines private and public cloud environments.

</details>

<details>
<summary><b>What is observability vs. monitoring?</b></summary>

Monitoring collects data; observability provides deeper insights into system behavior.

</details>


<details>
<summary><b>What is A/B testing in DevOps?</b></summary>

A/B testing compares different versions of an application to determine the best performance.

</details>

<details>
<summary><b>What is autoscaling in cloud environments?</b></summary>

Autoscaling automatically adjusts resource allocation based on demand.

</details>

### 🔴 Advanced

<details>
<summary><b>What is the Twelve-Factor App methodology?</b></summary>

The Twelve-Factor App is a set of best practices for building modern, scalable cloud applications. The 12 principles focus on aspects like codebase, dependencies, configuration, logging, and disposability.

</details>

<details>
<summary><b>How do you implement zero-trust security in DevOps?</b></summary>

Zero-trust security enforces strict identity verification and least-privilege access across the entire system. It includes:

Multi-factor authentication (MFA)
Role-Based Access Control (RBAC)
Encryption of data in transit and at rest
Continuous monitoring and logging

</details>

<details>
<summary><b>What are sidecars in Kubernetes?</b></summary>

A sidecar is a helper container that runs alongside a main application container within the same pod. Sidecars enhance functionality without modifying the primary application (e.g., logging, monitoring, service mesh).

</details>

<details>
<summary><b>How does Kubernetes handle self-healing?</b></summary>

Kubernetes ensures self-healing by:

Restarting failed containers
Rescheduling pods on healthy nodes
Automatically scaling replicas
Rolling back deployments if necessary

</details>

<details>
<summary><b>What is progressive delivery?</b></summary>

Progressive delivery is an advanced deployment strategy that introduces new changes incrementally to users, using techniques like:

Canary releases (small group testing)
Feature flags (turning features on/off dynamically)
A/B testing (comparing multiple versions in production)

</details>

<details>
<summary><b>What is a service mesh, and why is it important?</b></summary>

A service mesh (e.g., Istio, Linkerd) is a dedicated infrastructure layer that manages service-to-service communication in microservices architectures. It provides:

Traffic control (load balancing, retries)
Security (mutual TLS authentication)
Observability (tracing, metrics, logging)

</details>

<details>
<summary><b>What is GitOps, and how does it improve DevOps workflows?</b></summary>

GitOps uses Git repositories as the single source of truth for declarative infrastructure and applications. Benefits include:

Version-controlled deployments
Automated reconciliation of state
Increased security via RBAC

</details>

<details>
<summary><b>What is Blue/Green vs. Rolling deployment?</b></summary>

Blue/Green Deployment: Two identical environments (Blue and Green). Traffic is switched instantly.
Rolling Deployment: Gradual update of application instances, minimizing downtime but increasing rollback complexity.

</details>

<details>
<summary><b>How do you handle secrets management in DevOps?</b></summary>

Best practices for secrets management include:

Using vault solutions (e.g., HashiCorp Vault, AWS Secrets Manager)
Avoiding hardcoded secrets in code
Using environment variables or encrypted configuration files

</details>

<details>
<summary><b>What is a chaos engineering experiment?</b></summary>

Chaos engineering involves intentionally introducing failures to test system resilience. Examples include:

Network disruptions (latency, packet loss)
Server crashes (killing pods or nodes)
Resource exhaustion (CPU/memory spikes)

</details>

<details>
<summary><b>How do you implement compliance in DevOps pipelines?</b></summary>

Compliance can be enforced using:

Automated security scans (e.g., SonarQube, Snyk)
Policy-as-Code (e.g., Open Policy Agent)
Audit logging and access controls

</details>

<details>
<summary><b>What is infrastructure drift, and how do you prevent it?</b></summary>

Infrastructure drift occurs when real-world infrastructure deviates from its declared state in code. Prevention methods:

Use Infrastructure as Code (IaC) tools
Regularly run drift detection checks
Automate infrastructure provisioning

</details>

<details>
<summary><b>What is a deployment freeze, and when should it be used?</b></summary>

A deployment freeze is a temporary halt on new releases, typically during critical business periods (e.g., holiday sales, tax season).

</details>

<details>
<summary><b>How do you ensure high availability in a DevOps environment?</b></summary>

High availability can be ensured through:

Multi-region deployments
Load balancing & auto-scaling
Database replication & failover mechanisms

</details>

<details>
<summary><b>What is a multi-cloud strategy?</b></summary>

A multi-cloud strategy uses multiple cloud providers (e.g., AWS, Azure, GCP) to:

Reduce vendor lock-in
Improve redundancy and fault tolerance
Optimize costs

</details>


<details>
<summary><b>What are the challenges of DevOps adoption in large enterprises?</b></summary>

Legacy system integration
Security and compliance concerns
Cultural resistance to automation
Skill gaps within teams

</details>


<details>
<summary><b>What are observability pillars in DevOps?</b></summary>

The three pillars of observability are:

Logs (text-based records of system events)
Metrics (numerical measurements like CPU usage)
Tracing (tracking requests across distributed systems)

</details>

<details>
<summary><b>What are the best practices for incident response in DevOps?</b></summary>

Automated alerts and monitoring (PagerDuty, Prometheus)
Runbooks and playbooks for issue resolution
Post-mortems for continuous learning

</details>

---

## ⚙️ Scripting & Automation

### 🟢 Beginner

<details>
<summary><b>What is automation in DevOps?</b></summary>

Automation in DevOps refers to scripting repetitive tasks like provisioning, configuration, deployment, and monitoring to improve efficiency and reduce errors.

</details>

<details>
<summary><b>What are the benefits of scripting in DevOps?</b></summary>

- Reduces manual effort
- Increases consistency and repeatability
- Improves efficiency and speed
- Reduces errors and enhances security

</details>

<details>
<summary><b>What is Bash scripting?</b></summary>

Bash scripting is writing command-line instructions in a script file (.sh) to automate tasks in Unix/Linux environments.

</details>

<details>
<summary><b>How do you write a basic Bash script?</b></summary>

```bash
#!/bin/bash
echo "Hello, DevOps!"
```
Save the file (`script.sh`), make it executable (`chmod +x script.sh`), and run it (`./script.sh`).

</details>

<details>
<summary><b>What is the difference between Bash and Shell scripting?</b></summary>

Bash is a type of shell, but shell scripting can also be done in other shells like `sh`, `csh`, and `zsh`. Bash provides more advanced scripting features.

</details>

<details>
<summary><b>What are variables in Bash?</b></summary>

Variables store values and are defined without a `$` sign but accessed using `$`.
```bash
name="DevOps"
echo "Hello, $name"
```

</details>

<details>
<summary><b>What is Python scripting used for in DevOps?</b></summary>

- Infrastructure as Code (IaC)
- CI/CD automation
- Log analysis
- Cloud automation (AWS, Azure, GCP SDKs)

</details>

<details>
<summary><b>How do you define a function in Python?</b></summary>

```python
def greet():
    print("Hello, DevOps!")
greet()
```

</details>



<details>
<summary><b>What is the shebang (`#!`) in a script?</b></summary>

The shebang (`#!/bin/bash` or `#!/usr/bin/python3`) specifies the interpreter for executing the script.

</details>

<details>
<summary><b>What are loops in Bash?</b></summary>

Bash supports `for`, `while`, and `until` loops. Example:
```bash
for i in {1..5}; do echo "Iteration $i"; done
```

</details>

<details>
<summary><b>What are conditional statements in Bash?</b></summary>

`if-else` statements execute different code based on conditions.
```bash
if [ $USER == "root" ]; then echo "Admin access"; else echo "User access"; fi
```

</details>

<details>
<summary><b>How do you read input in Bash?</b></summary>

```bash
echo "Enter name: "
read name
echo "Hello, $name"
```

</details>

<details>
<summary><b>How do you create a Python virtual environment?</b></summary>

```bash
python3 -m venv myenv
source myenv/bin/activate
```

</details>

</details>

<details>
<summary><b>What is the `awk` command in Bash?</b></summary>

`awk` is used for text processing. Example:
```bash
awk '{print $1}' file.txt
```
Extracts the first column from `file.txt`.

</details>


### 🟡 Intermediate

<details>
<summary><b>How do you pass arguments to a Bash script?</b></summary>

```bash
#!/bin/bash
echo "Hello, $1!"
```
Run: `./script.sh DevOps` → Output: `Hello, DevOps!`

</details>

<details>
<summary><b>How do you handle errors in Bash scripts?</b></summary>

Use `set -e` to stop execution on errors.

</details>

<details>
<summary><b>How do you handle exceptions in Python?</b></summary>

```python
try:
    print(1 / 0)
except ZeroDivisionError:
    print("Cannot divide by zero")
```

</details>

<details>
<summary><b>How do you schedule a script with Cron?</b></summary>

Edit `crontab -e` and add:
```
0 5 * * * /path/to/script.sh
```
Runs the script daily at 5 AM.

</details>

<details>
<summary><b>How do you create a list in Python?</b></summary>

```python
mylist = [1, 2, 3]
print(mylist[0])
```

</details>

<details>
<summary><b>What is `sed` in Bash?</b></summary>

Used for text replacement. Example:
```bash
sed -i 's/old/new/g' file.txt
```

</details>

<details>
<summary><b>How do you define a dictionary in Python?</b></summary>

```python
mydict = {"name": "DevOps"}
print(mydict["name"])
```

</details>


<details>
<summary><b>How do you install Python modules?</b></summary>

```bash
pip install requests
```

</details>

<details>
<summary><b>How do you iterate over a dictionary in Python?</b></summary>

```python
for key, value in mydict.items():
    print(key, value)
```

</details>

<details>
<summary><b>How do you set environment variables in Bash?</b></summary>

```bash
export VAR="DevOps"
```

</details>


<details>
<summary><b>What is a multiline string in YAML?</b></summary>

```yaml
message: |
  Line 1
  Line 2
```

</details>

<details>
<summary><b>What is an associative array in Bash?</b></summary>

```bash
declare -A myarray
myarray[name]="DevOps"
echo ${myarray[name]}
```

</details>

<details>
<summary><b>How do you run a shell command in Python?</b></summary>

```python
import os
os.system("ls")
```

</details>

<details>
<summary><b>What is `jq` in Linux?</b></summary>

Used to parse JSON. Example:
```bash
cat data.json | jq '.name'
```

</details>

<details>
<summary><b>How do you exit a script with a status code?</b></summary>

```bash
exit 1
```

</details>

### 🔴 Advanced

<details>
<summary><b>How do you debug a Bash script?</b></summary>

Use `set -x` for debugging:
```bash
#!/bin/bash
set -x
echo "Debugging mode enabled"
```

</details>

<details>
<summary><b>How do you trap signals in a Bash script?</b></summary>

```bash
trap "echo 'Script interrupted'; exit" SIGINT SIGTERM
```
Catches Ctrl+C (SIGINT) and terminates gracefully.

</details>

<details>
<summary><b>What is the difference between `$(command)` and backticks in Bash?</b></summary>

Both execute commands, but `$(command)` is preferred as it is nestable.

</details>

<details>
<summary><b>How do you handle multiline commands in a Bash script?</b></summary>

Use `\` for line continuation:
```bash
echo "This is a \
multiline command"
```

</details>

<details>
<summary><b>How do you use conditionals inside a YAML file?</b></summary>

With Jinja2 templating in Ansible:
```yaml
tasks:
  - name: Install package
    yum:
      name: httpd
    when: ansible_os_family == "RedHat"
```

</details>

<details>
<summary><b>How do you execute a Python script inside a Bash script?</b></summary>

```bash
python3 <<EOF
print("Hello from Python")
EOF
```

</details>

<details>
<summary><b>What is the difference between `continue` and `break` in Bash loops?</b></summary>

- `break` exits the loop entirely.
- `continue` skips the current iteration.

</details>

<details>
<summary><b>How do you parse a JSON file in Bash?</b></summary>

Use `jq`:
```bash
cat data.json | jq '.key'
```

</details>

<details>
<summary><b>How do you set a timeout for a script in Bash?</b></summary>

```bash
timeout 10s ./script.sh
```

</details>

<details>
<summary><b>How do you execute a Bash function in a subshell?</b></summary>

```bash
(my_function)
```
Runs in a new shell, not affecting the parent script.

</details>

<details>
<summary><b>How do you use Python to send an HTTP request?</b></summary>

```python
import requests
response = requests.get("https://example.com")
print(response.text)
```

</details>

<details>
<summary><b>How do you handle authentication in a Python script?</b></summary>

```python
import requests
requests.get("https://example.com", auth=("user", "pass"))
```

</details>

<details>
<summary><b>How do you execute a script remotely via SSH in Bash?</b></summary>

```bash
ssh user@server 'bash -s' < local_script.sh
```

</details>

---

## 🚀 CI/CD & DevOps Best Practices

### 🟢 Beginner

<details>
<summary><b>What are DevOps best practices?</b></summary>

Key DevOps best practices include:
- Infrastructure as Code (IaC)
- Continuous Integration and Continuous Deployment (CI/CD)
- Monitoring and Logging
- Automated Testing
- Security as Code

</details>

<details>
<summary><b>What are the key components of a CI/CD pipeline?</b></summary>

- Code commit
- Build
- Test
- Deploy
- Monitor

</details>

<details>
<summary><b>What is the difference between Continuous Deployment and Continuous Delivery?</b></summary>

- **Continuous Delivery:** Automated testing, but manual deployment approval.
- **Continuous Deployment:** Fully automated release process.

</details>

<details>
<summary><b>What is the importance of automated testing in DevOps?</b></summary>

Automated testing ensures code quality, catches bugs early, and speeds up deployment.

</details>

<details>
<summary><b>What is the purpose of monitoring in DevOps?</b></summary>

Monitoring tools (e.g., Prometheus, Grafana, ELK) track system performance and detect issues in real-time.

</details>

<details>
<summary><b>What is the role of logging in DevOps?</b></summary>

Logging helps in troubleshooting, analyzing trends, and ensuring application reliability.

</details>

<details>
<summary><b>How do you manage secrets in DevOps?</b></summary>

Using secret management tools like HashiCorp Vault, AWS Secrets Manager, and Kubernetes Secrets.

</details>


### 🟡 Intermediate

<details>
<summary><b>How do you ensure high availability in a cloud-based architecture?</b></summary>

Using load balancing, auto-scaling, multi-region deployments, and failover mechanisms.

</details>


<details>
<summary><b>How do you secure a CI/CD pipeline?</b></summary>

- Use least privilege access.
- Store secrets securely.
- Scan dependencies for vulnerabilities.
- Implement code signing.

</details>

<details>
<summary><b>What are some common DevOps anti-patterns?</b></summary>

- Siloed teams
- Manual deployments
- Lack of monitoring
- Ignoring security

</details>

<details>
<summary><b>What is a Service Level Agreement (SLA)?</b></summary>

An SLA defines the expected level of service, including uptime and response times.

</details>

<details>
<summary><b>How do you ensure compliance in DevOps?</b></summary>

By automating security checks, auditing, and following regulatory frameworks like GDPR and SOC 2.

</details>

<details>
<summary><b>How do you reduce deployment downtime?</b></summary>

Using rolling updates, blue-green deployments, and zero-downtime migrations.

</details>

<details>
<summary><b>How do you handle database migrations in CI/CD?</b></summary>

Using tools like Flyway, Liquibase, or Django migrations in an automated pipeline.

</details>

<details>
<summary><b>How do you implement infrastructure testing?</b></summary>

Using tools like Terratest (for Terraform), InSpec, and Pester.

</details>

<details>
<summary><b>What is the difference between SLO and SLI?</b></summary>

- **SLO (Service Level Objective):** A target level of reliability (e.g., 99.9% uptime).
- **SLI (Service Level Indicator):** A measurable metric (e.g., response time < 200ms).

</details>


<details>
<summary><b>How do you handle rollback in a Kubernetes environment?</b></summary>

```bash
kubectl rollout undo deployment <deployment_name>
```

</details>

<details>
<summary><b>What are the best practices for writing Dockerfiles?</b></summary>

- Use lightweight base images.
- Minimize layers.
- Avoid hardcoding secrets.
- Use multi-stage builds.

</details>


### 🔴 Advanced


<details>
<summary><b>How do you handle incident response in DevOps?</b></summary>

Using an on-call rotation, alerting, and post-mortems.

</details>

<details>
<summary><b>How do you manage hybrid cloud environments?</b></summary>

Using tools like Anthos, Azure Arc, and Terraform.

</details>

<details>
<summary><b>How do you implement auto-remediation in DevOps?</b></summary>

Using AWS Lambda, Ansible, or Kubernetes operators to fix issues automatically.

</details>

<details>
<summary><b>How do you secure a Kubernetes cluster?</b></summary>

- Use RBAC (Role-Based Access Control)
- Enable Pod Security Policies
- Rotate TLS certificates

</details>

---

## 🏗️ Infrastructure as Code

### 🟢 Beginner

<details>
<summary><b>What is Infrastructure as Code (IaC) and why is it important?</b></summary>

Infrastructure as Code (IaC) is a method of managing and provisioning infrastructure using code instead of manual processes. It allows:
✅ Automation of infrastructure deployment
✅ Consistency by reducing human errors
✅ Scalability through repeatable scripts

</details>

<details>
<summary><b>What is Terraform and how does it work?</b></summary>

Terraform is an open-source IaC tool by HashiCorp that helps define and provision infrastructure using a declarative configuration language. It follows three steps:

Write: Define infrastructure in .tf files
Plan: Preview changes before applying
Apply: Deploy and manage resources
Example:

provider "aws" {
  region = "us-east-1"
}

resource "aws_instance" "my_instance" {
  ami           = "ami-12345678"
  instance_type = "t2.micro"
}

</details>

<details>
<summary><b>What is the difference between Terraform and Ansible?</b></summary>

Feature	Terraform	Ansible
Type	Declarative	Imperative
Purpose	Infrastructure provisioning	Configuration management
State Management	Uses state file	Stateless
Example Use	Creating VMs, Networks	Installing software, configuring OS

</details>

<details>
<summary><b>What are Terraform Providers?</b></summary>

Providers are plugins that allow Terraform to manage resources on different platforms (AWS, Azure, GCP, Kubernetes, etc.).

Example:

provider "aws" {
  region = "us-west-2"
}

</details>

<details>
<summary><b>What is a Terraform State File?</b></summary>

Terraform maintains infrastructure details in a state file (terraform.tfstate), which:
✅ Tracks existing resources
✅ Enables incremental changes
✅ Supports remote storage (e.g., S3, Azure Blob)

To store state remotely:

backend "s3" {
  bucket = "my-terraform-state"
  key    = "terraform.tfstate"
  region = "us-east-1"
}

</details>

<details>
<summary><b>What is the purpose of terraform init?</b></summary>

It initializes the working directory by:
✅ Downloading providers
✅ Setting up backend storage
✅ Validating configuration

Command:

terraform init

</details>

<details>
<summary><b>How does Terraform manage dependencies between resources?</b></summary>

Terraform uses implicit and explicit dependencies:

Implicit: Recognized automatically
Explicit: Defined using depends_on
Example:

resource "aws_instance" "web" {
  ami           = "ami-12345678"
  instance_type = "t2.micro"
}

resource "aws_ebs_volume" "data" {
  size          = 10
  availability_zone = "us-east-1a"
  depends_on    = [aws_instance.web]
}

</details>

<details>
<summary><b>What is the difference between Terraform apply and plan?</b></summary>

Command	Purpose
terraform plan	Shows proposed changes before applying
terraform apply	Executes changes to create/update resources

</details>

<details>
<summary><b>What is a Terraform Module?</b></summary>

A module is a reusable collection of Terraform configurations that helps organize code.

Example of a module (main.tf):

module "network" {
  source = "./modules/vpc"
}

</details>

<details>
<summary><b>How do you destroy resources in Terraform?</b></summary>

Use:

terraform destroy
This removes all resources defined in the configuration.

Ansible Questions

</details>

<details>
<summary><b>What is Ansible and how does it work?</b></summary>

Ansible is an open-source configuration management tool that automates tasks like software installation, updates, and deployments. It works agentless, using SSH or WinRM.

</details>

<details>
<summary><b>What are Ansible Playbooks?</b></summary>

A playbook is a YAML-based automation script that defines tasks to be executed.

Example (playbook.yml):

- name: Install Nginx
  hosts: web
  tasks:
    - name: Install Nginx
      apt:
        name: nginx
        state: present

</details>

<details>
<summary><b>What is an Ansible Inventory file?</b></summary>

The inventory file lists managed servers and their details.

Example (inventory.ini):

[web]
server1 ansible_host=192.168.1.10
server2 ansible_host=192.168.1.11

</details>

<details>
<summary><b>What is the difference between Ansible Roles and Playbooks?</b></summary>

Feature	Playbook	Role
Scope	Task-oriented	Component-oriented
Organization	Single YAML file	Structured directory
Usage	Small-scale automation	Large-scale projects

</details>

<details>
<summary><b>How do you run an Ansible Playbook?</b></summary>

Command:

ansible-playbook playbook.yml -i inventory.ini

</details>

<details>
<summary><b>What is AWS CloudFormation?</b></summary>

AWS CloudFormation is an IaC service that provisions AWS infrastructure using YAML/JSON templates.

Example:

Resources:
  MyBucket:
    Type: "AWS::S3::Bucket"

</details>

<details>
<summary><b>How do you create a CloudFormation stack?</b></summary>

Command:

aws cloudformation create-stack --stack-name my-stack --template-body file://template.yml

</details>

### 🟡 Intermediate

<details>
<summary><b>What is the difference between Terraform local and remote state?</b></summary>

Terraform state can be stored locally (on disk) or remotely (in S3, Consul, etc.).

Storage	Pros	Cons
Local State (terraform.tfstate)	Fast, simple	Not suitable for teams
Remote State (S3, etc.)	Shared, secure	Slightly slower
Example remote state (S3 backend):

terraform {
  backend "s3" {
    bucket = "my-terraform-state"
    key    = "prod/terraform.tfstate"
    region = "us-east-1"
  }
}

</details>

<details>
<summary><b>How do you handle secrets in Terraform?</b></summary>

Avoid hardcoding secrets in .tf files:
✅ Use environment variables
✅ Use Terraform Vault Provider
✅ Store secrets in AWS Secrets Manager

</details>

<details>
<summary><b>What is Terraform Workspaces?</b></summary>

Terraform Workspaces allow managing multiple environments within a single configuration.

terraform workspace new dev
terraform workspace select dev

</details>

<details>
<summary><b>How does Terraform handle drift detection?</b></summary>

Terraform detects drift by running:

terraform plan
Drift occurs when actual infrastructure changes outside Terraform’s control.

</details>

<details>
<summary><b>How do you use Ansible variables?</b></summary>

Variables can be defined in:
✅ Playbooks (vars:)
✅ Inventory (host_vars, group_vars)
✅ Command-line (-e flag)

Example:

- hosts: web
  vars:
    app_port: 8080
  tasks:
    - debug: msg="App runs on port {{ app_port }}"

</details>

<details>
<summary><b>What are Ansible Facts?</b></summary>

Facts are system information collected automatically.

Example:

ansible all -m setup

</details>

<details>
<summary><b>What is the purpose of Ansible Handlers?</b></summary>

Handlers run only when notified.

Example:

- name: Install Nginx
  apt:
    name: nginx
  notify: Restart Nginx

- name: Restart Nginx
  service:
    name: nginx
    state: restarted
  listen: Restart Nginx

</details>

<details>
<summary><b>How does Ansible manage dependencies?</b></summary>

Ansible Roles handle dependencies using meta/main.yml.

Example:

dependencies:
  - role: common

</details>

<details>
<summary><b>What is the difference between command and shell modules in Ansible?</b></summary>

Module	When to Use	Example
command	Runs a command without shell features	ansible all -m command -a "ls"
shell	Runs commands with shell features (`	,&&`)

</details>

<details>
<summary><b>What is Ansible Dynamic Inventory?</b></summary>

Dynamic Inventory fetches live host lists from AWS, Azure, GCP.

Example for AWS:

ansible-inventory --list -i aws_ec2.yml
CloudFormation Questions

</details>

<details>
<summary><b>What are the main components of AWS CloudFormation?</b></summary>

Component	Description
Templates	Defines resources in YAML/JSON
Stacks	Collection of AWS resources
StackSets	Deploy stacks across multiple accounts

</details>


<details>
<summary><b>What is AWS CloudFormation Drift Detection?</b></summary>

Detects manual changes to resources outside CloudFormation.

Run drift check:

aws cloudformation detect-stack-drift --stack-name my-stack

</details>

### 🔴 Advanced

<details>
<summary><b>How do you implement CI/CD pipelines with Terraform?</b></summary>

Terraform can be integrated into CI/CD pipelines using GitHub Actions, GitLab CI, or Jenkins.
✅ Linting & Validation: terraform fmt, terraform validate
✅ Planning: terraform plan -out=tfplan
✅ Apply Changes: terraform apply tfplan

</details>

<details>
<summary><b>What are Terraform Data Sources?</b></summary>

Data sources allow Terraform to query external resources without managing them.

Example:

data "aws_vpc" "existing_vpc" {
  filter {
    name   = "tag:Name"
    values = ["my-vpc"]
  }
}

</details>

<details>
<summary><b>How do you manage Terraform module versions?</b></summary>

Use version constraints in source.

Example (versions.tf):

module "vpc" {
  source  = "terraform-aws-modules/vpc/aws"
  version = "3.5.0"
}

</details>

<details>
<summary><b>How does Terraform handle circular dependencies?</b></summary>

Terraform detects and prevents circular dependencies by analyzing the DAG (Directed Acyclic Graph).
Solution:
✅ Use depends_on explicitly
✅ Refactor resources

Example:

resource "aws_instance" "web" {
  depends_on = [aws_s3_bucket.logs]
}

</details>

<details>
<summary><b>What are Terraform locals and output variables?</b></summary>

locals: Store temporary values
output: Expose values after deployment
Example:

locals {
  env_name = "dev"
}

output "instance_ip" {
  value = aws_instance.web.public_ip
}

</details>

<details>
<summary><b>What is a Terraform Sentinel Policy?</b></summary>

Sentinel is a policy-as-code framework that enforces compliance.

Example policy (enforce_cost.sentinel):

import "tfplan"

main = rule { tfplan.cost_estimate.total_monthly_cost < 500 }

</details>

<details>
<summary><b>How do you roll back changes in Terraform?</b></summary>

Option 1: Use version control (git revert)

Option 2: Manually restore the previous state

Option 3: Import last known working state:

terraform apply "tfstate-previous.json"

</details>

<details>
<summary><b>What is Terraform Refresh?</b></summary>

terraform refresh updates the state file without modifying resources.

terraform refresh

</details>

<details>
<summary><b>How do you enforce security best practices in Terraform?</b></summary>

✅ Use IAM least privilege for Terraform executions
✅ Store state files securely (S3 + DynamoDB)
✅ Run security scans with tools like tfsec

Example:

tfsec .

</details>

<details>
<summary><b>How do you test Ansible Playbooks before applying them?</b></summary>

✅ Use ansible-lint for syntax validation
✅ Use Molecule for testing

Example:

molecule test

</details>

<details>
<summary><b>How do you handle error handling in Ansible?</b></summary>

Use ignore_errors: yes or rescue blocks.

Example:

tasks:
  - name: Try to restart service
    service:
      name: nginx
      state: restarted
    ignore_errors: yes

</details>

<details>
<summary><b>How do you implement Ansible Vault in CI/CD?</b></summary>

Use environment variables to decrypt secrets.

Example:

ANSIBLE_VAULT_PASSWORD="myvaultpassword" ansible-playbook deploy.yml

</details>

<details>
<summary><b>How do you ensure Ansible Playbooks are idempotent?</b></summary>

✅ Always use state: present
✅ Run playbooks multiple times to check consistency

Example:

- name: Ensure Nginx is installed
  apt:
    name: nginx
    state: present
CloudFormation Questions

</details>


<details>
<summary><b>How do you debug CloudFormation failures?</b></summary>

✅ Check the CloudFormation console
✅ Use aws cloudformation describe-stack-events
✅ Enable rollback debugging

Example:

aws cloudformation describe-stack-events --stack-name my-stack

Linux & System Administration - DevOps Interview Questions

</details>

---

## 📦 Containers (Docker & Kubernetes)

### 🟢 Beginner

<details>
<summary><b>What is Docker, and why is it used?</b></summary>

Docker is a containerisation platform that allows developers to package applications along with their dependencies into a single unit called a container. It ensures consistent environments across different machines, is lightweight and faster than virtual machines, and enables easy scaling in microservices architectures.

</details>

<details>
<summary><b>What is the difference between Docker and a Virtual Machine (VM)?</b></summary>

| Feature | Docker | Virtual Machine |
|---|---|---|
| Isolation | Uses containers to isolate apps | Uses hypervisor to run separate OS instances |
| Performance | Faster, lightweight | Slower, resource-intensive |
| Startup Time | Milliseconds | Minutes |
| Use Case | Ideal for microservices | Best for full OS emulation |

</details>

<details>
<summary><b>What is a Docker image?</b></summary>

A Docker image is a read-only template containing everything needed to run an application, including source code, libraries and dependencies, and configuration files. A container is created from a Docker image using the `docker run` command.

</details>

<details>
<summary><b>What is a Docker container?</b></summary>

A Docker container is a running instance of a Docker image. It is lightweight (shares OS kernel), isolated (has its own filesystem, network, and process space), and portable (can run on any system with Docker installed).

</details>

<details>
<summary><b>How do you create and run a Docker container?</b></summary>

```bash
docker run -d --name myapp nginx
```
- `-d`: Run in detached mode (background).
- `--name myapp`: Name the container.
- `nginx`: Use the nginx image.

</details>

<details>
<summary><b>What is the purpose of the Dockerfile?</b></summary>

A Dockerfile is a script containing instructions to build a Docker image.
```dockerfile
FROM node:16
WORKDIR /app
COPY . .
RUN npm install
CMD ["node", "app.js"]
```

</details>

<details>
<summary><b>What are Docker volumes?</b></summary>

Docker volumes store persistent data outside a container's filesystem. Types include anonymous volumes (`docker run -v /data nginx`), named volumes (`docker volume create mydata`), and bind mounts (`docker run -v /host/path:/container/path nginx`).

</details>

<details>
<summary><b>How do you list running Docker containers?</b></summary>

```bash
docker ps          # List running containers
docker ps -a       # List all containers including stopped ones
```

</details>

<details>
<summary><b>What is Docker Compose?</b></summary>

Docker Compose is a tool for defining and running multi-container applications using a `docker-compose.yml` file.
```yaml
version: "3"
services:
  web:
    image: nginx
    ports:
      - "80:80"
  db:
    image: mysql
    environment:
      MYSQL_ROOT_PASSWORD: root
```
Start with `docker-compose up -d`, stop with `docker-compose down`.

</details>

<details>
<summary><b>What is the difference between CMD and ENTRYPOINT in Docker?</b></summary>

| Feature | CMD | ENTRYPOINT |
|---|---|---|
| Purpose | Default command | Fixed executable command |
| Overridable? | Yes | No (unless `--entrypoint` is used) |

#### Kubernetes Basics

</details>

<details>
<summary><b>What is Kubernetes?</b></summary>

Kubernetes (K8s) is an orchestration platform for managing containerised applications, providing automated scaling, self-healing (restarts failed containers), load balancing, and rolling updates.

</details>

<details>
<summary><b>What is a Kubernetes Pod?</b></summary>

A Pod is the smallest unit in Kubernetes. It groups one or more containers that share the same network and storage.

</details>

<details>
<summary><b>What is a Kubernetes Deployment?</b></summary>

A Deployment manages Pod creation and updates.
```yaml
apiVersion: apps/v1
kind: Deployment
metadata:
  name: my-app
spec:
  replicas: 3
  selector:
    matchLabels:
      app: my-app
  template:
    metadata:
      labels:
        app: my-app
    spec:
      containers:
        - name: app
          image: nginx
```

</details>

<details>
<summary><b>What is a Kubernetes Service?</b></summary>

A Service exposes a set of Pods over a network. Types include ClusterIP (default), NodePort (exposes on a fixed port), and LoadBalancer (uses cloud provider's load balancer).

</details>

<details>
<summary><b>What is the purpose of Kubernetes ConfigMaps and Secrets?</b></summary>

ConfigMaps store non-sensitive configuration data, while Secrets store sensitive data like passwords and API keys.

</details>

<details>
<summary><b>What is a Kubernetes Namespace?</b></summary>

Namespaces logically separate resources within a cluster.
```bash
kubectl create namespace dev
kubectl get namespaces
```

</details>

<details>
<summary><b>What is a StatefulSet in Kubernetes?</b></summary>

A StatefulSet is used for stateful applications like databases. Unlike Deployments, it maintains stable pod identity and persistent storage.

</details>

<details>
<summary><b>How do you scale a Deployment in Kubernetes?</b></summary>

```bash
kubectl scale deployment my-app --replicas=5
```

</details>

<details>
<summary><b>What is a DaemonSet?</b></summary>

A DaemonSet ensures that one Pod runs on every node (e.g., for logging agents or monitoring).

</details>

<details>
<summary><b>How do you update a Kubernetes Deployment?</b></summary>

```bash
kubectl set image deployment/my-app my-container=nginx:latest
```

</details>

### 🟡 Intermediate

<details>
<summary><b>How do you optimize Docker images?</b></summary>

- Use smaller base images (e.g., `alpine` instead of `ubuntu`).
- Use multi-stage builds to reduce image size:

</details>

<details>
<summary><b>How do you debug a running Docker container?</b></summary>

```bash
docker logs my-container                   # View logs
docker exec -it my-container /bin/sh       # Attach to container
docker inspect my-container               # Inspect container details
```

</details>

<details>
<summary><b>What is a Docker Multi-Stage Build?</b></summary>

A multi-stage build reduces image size by using multiple `FROM` statements, so the final image only contains what is needed to run the application.
```dockerfile
FROM golang:1.17 AS builder
WORKDIR /app
COPY . .
RUN go build -o myapp

FROM alpine
COPY --from=builder /app/myapp /myapp
ENTRYPOINT ["/myapp"]
```

</details>

<details>
<summary><b>How does Docker handle networking?</b></summary>

- **Bridge network (default):** Containers communicate via a virtual network.
- **Host network:** Container shares the host's networking stack.
- **Overlay network:** Used in Docker Swarm for multi-host networking.
```bash
docker network create mynetwork
docker run --network=mynetwork nginx
```

</details>

<details>
<summary><b>How do you remove unused Docker images and containers?</b></summary>

```bash
docker system prune -a
```
This removes stopped containers, unused networks, and dangling images.

</details>

<details>
<summary><b>How do you limit container resource usage?</b></summary>

```bash
docker run --memory=512m --cpus=1 nginx
```
This limits memory to 512MB and CPU usage to 1 core.

</details>

#### Kubernetes Intermediate

<details>
<summary><b>How does Kubernetes handle high availability?</b></summary>

Kubernetes uses multiple master nodes to avoid single points of failure, Deployments with replica sets to keep applications running, and load balancing with failover mechanisms to ensure availability.

</details>

<details>
<summary><b>What is the role of kubelet in Kubernetes?</b></summary>

Kubelet runs on each node and communicates with the master node, ensures containers are running, and monitors container health.

</details>

<details>
<summary><b>How do you check logs of a running Pod in Kubernetes?</b></summary>

```bash
kubectl logs my-pod
kubectl logs -f my-pod   # Stream logs in real-time
```

</details>

<details>
<summary><b>What are Kubernetes Labels and Selectors?</b></summary>

Labels identify resources, while selectors filter resources.
```yaml
metadata:
  labels:
    app: my-app
```
```bash
kubectl get pods -l app=my-app
```

</details>


<details>
<summary><b>What is the difference between Horizontal Pod Autoscaler (HPA) and Vertical Pod Autoscaler (VPA)?</b></summary>

| Feature | HPA | VPA |
|---|---|---|
| Scaling Type | Adds/removes pods | Adjusts CPU/memory of existing pods |
| Use Case | High traffic apps | Resource optimisation |

```bash
kubectl autoscale deployment my-app --cpu-percent=50 --min=2 --max=10
```

</details>

<details>
<summary><b>What is a Kubernetes Persistent Volume (PV) and Persistent Volume Claim (PVC)?</b></summary>

A Persistent Volume (PV) is a storage resource, and a Persistent Volume Claim (PVC) requests storage.
```yaml
apiVersion: v1
kind: PersistentVolumeClaim
metadata:
  name: my-pvc
spec:
  accessModes:
    - ReadWriteOnce
  resources:
    requests:
      storage: 1Gi
```

</details>

<details>
<summary><b>How do you upgrade a running application in Kubernetes?</b></summary>

```bash
kubectl set image deployment/my-app my-container=nginx:1.20
kubectl rollout status deployment my-app
```

</details>

<details>
<summary><b>What is a Kubernetes Job and CronJob?</b></summary>

A Job runs once and exits, while a CronJob runs on a schedule (like a Linux cron).
```yaml
apiVersion: batch/v1
kind: CronJob
metadata:
  name: my-cronjob
spec:
  schedule: "0 * * * *"
  jobTemplate:
    spec:
      template:
        spec:
          containers:
            - name: hello
              image: busybox
              command: ["echo", "Hello from Kubernetes"]
          restartPolicy: OnFailure
```

</details>

<details>
<summary><b>How do you debug Kubernetes pods stuck in "CrashLoopBackOff"?</b></summary>

```bash
kubectl logs my-pod              # Check pod logs
kubectl describe pod my-pod      # Describe the pod for errors
kubectl exec -it my-pod -- /bin/sh  # Exec into the container
```

</details>

### 🔴 Advanced

<details>
<summary><b>What are Docker namespaces and cgroups?</b></summary>

Namespaces isolate resources (PID, network, mount points, etc.) for each container, while cgroups (Control Groups) limit CPU, memory, and disk usage. Together, they ensure process isolation and resource allocation.

</details>

<details>
<summary><b>What is the difference between Docker Volumes, Bind Mounts, and tmpfs?</b></summary>

| Type | Persistent? | Use Case |
|---|---|---|
| Volumes | Yes | Best for data persistence |
| Bind Mounts | Yes | Direct host file access |
| tmpfs | No | In-memory storage for performance |

</details>

<details>
<summary><b>How do you secure a Docker container?</b></summary>

- Use minimal base images (e.g., `alpine`).
- Run as a non-root user.
- Limit container capabilities (`--cap-drop=ALL`).
- Use read-only filesystems (`--read-only`).
```bash
docker run --user 1001 --read-only nginx
```

</details>

<details>
<summary><b>How do multi-stage builds improve security in Docker?</b></summary>

Multi-stage builds keep sensitive files out of the final image and reduce the attack surface by discarding unnecessary dependencies. New image versions are deployed instead of patching live containers.

</details>

<details>
<summary><b>How do you troubleshoot a Docker daemon issue?</b></summary>

```bash
journalctl -u docker.service   # Check logs
systemctl restart docker       # Restart service
dockerd --debug                # Run in debug mode
```

</details>

<details>
<summary><b>What is the difference between Docker Stack and Docker Compose?</b></summary>

Docker Compose is for single-host deployments, while Docker Stack is for multi-node Swarm clusters.

</details>


#### Kubernetes Advanced

</details>

<details>
<summary><b>How does Kubernetes handle stateful applications?</b></summary>

Kubernetes uses StatefulSets instead of Deployments to provide stable network identities and persistent storage.
```yaml
apiVersion: apps/v1
kind: StatefulSet
metadata:
  name: mysql
spec:
  serviceName: "mysql"
  replicas: 3
```

</details>

<details>
<summary><b>How do you secure Kubernetes Secrets?</b></summary>

Use encryption at rest and store secrets in external vaults (e.g., HashiCorp Vault).
```bash
kubectl create secret generic db-secret --from-literal=password=mysecurepassword
```

</details>

<details>
<summary><b>How does Kubernetes handle node failures?</b></summary>

Kubelet marks the node as `NotReady`, pods are rescheduled onto healthy nodes, and node auto-repair triggers in cloud-managed clusters.

</details>


<details>
<summary><b>How do you debug networking issues in Kubernetes?</b></summary>

```bash
kubectl exec -it pod1 -- ping pod2        # Check Pod-to-Pod connectivity
kubectl get networkpolicy                  # Inspect network policies
kubectl exec -it pod -- nslookup my-service  # Validate DNS resolution
```

</details>


<details>
<summary><b>What is Kubernetes Cluster Federation?</b></summary>



</details>

---

## ☁️ Cloud Computing

### 🟢 Beginner

<details>
<summary><b>What is cloud computing?</b></summary>

Cloud computing is the on-demand delivery of computing services such as servers, storage, databases, networking, and software over the internet. It eliminates the need for owning and maintaining physical hardware, allowing users to access scalable resources on a pay-as-you-go model.

</details>

<details>
<summary><b>What are the different types of cloud computing?</b></summary>

- **Public Cloud:** Services provided by third-party vendors like AWS, Azure, and GCP, accessible over the internet.
- **Private Cloud:** Cloud infrastructure dedicated to a single organization, either on-premises or hosted by a provider.
- **Hybrid Cloud:** A combination of public and private clouds, allowing data and applications to be shared between them.

</details>

<details>
<summary><b>What are the benefits of cloud computing?</b></summary>

- **Scalability:** Resources can be easily scaled up or down.
- **Cost Efficiency:** No need to invest in physical hardware.
- **Flexibility:** Access from anywhere using the internet.
- **Disaster Recovery:** Cloud providers offer backup and recovery solutions.

</details>

<details>
<summary><b>What are the different cloud service models?</b></summary>

- **Infrastructure as a Service (IaaS):** Provides virtualized computing resources (e.g., AWS EC2, Azure Virtual Machines).
- **Platform as a Service (PaaS):** Offers a managed environment for application development (e.g., AWS Elastic Beanstalk, Google App Engine).
- **Software as a Service (SaaS):** Delivers software applications over the internet (e.g., Gmail, Office 365, Salesforce).

</details>

<details>
<summary><b>What is serverless computing?</b></summary>

Serverless computing allows developers to run applications without managing underlying infrastructure. The cloud provider dynamically allocates resources as needed. Examples include AWS Lambda, Azure Functions, and Google Cloud Functions.

</details>

<details>
<summary><b>What is virtualization in cloud computing?</b></summary>

Virtualization is the process of creating virtual instances of servers, storage, or networks. It enables multiple virtual machines (VMs) to run on a single physical server, improving resource utilization.

</details>

<details>
<summary><b>What is multi-cloud?</b></summary>

Multi-cloud refers to using multiple cloud service providers (e.g., AWS, Azure, GCP) for redundancy, cost optimization, and avoiding vendor lock-in.

</details>

<details>
<summary><b>What are some common cloud deployment models?</b></summary>

- **Community Cloud:** Shared infrastructure for a specific group of organizations.
- **Hybrid Cloud:** Combination of on-premises, private, and public clouds.
- **Public Cloud:** Services offered to multiple customers over the internet.

</details>

<details>
<summary><b>What is the difference between vertical and horizontal scaling?</b></summary>

- **Vertical Scaling (Scaling Up):** Increasing resources (CPU, RAM) in an existing server.
- **Horizontal Scaling (Scaling Out):** Adding more servers to distribute the load.

</details>

<details>
<summary><b>What is an Availability Zone (AZ)?</b></summary>

An Availability Zone is a physically separate data center within a cloud provider's region, designed for fault tolerance and high availability.

</details>

<details>
<summary><b>What is the Shared Responsibility Model in cloud security?</b></summary>

Cloud providers and customers share security responsibilities:
- **Provider:** Secures hardware, networking, and cloud infrastructure.
- **Customer:** Secures applications, data, and user access.

</details>

<details>
<summary><b>What is a Virtual Private Cloud (VPC)?</b></summary>

A VPC is an isolated cloud environment where users can define their own network settings, including subnets, IP addresses, and security groups.

</details>

<details>
<summary><b>What is an Elastic Load Balancer (ELB)?</b></summary>

An ELB distributes incoming traffic across multiple servers to ensure high availability and fault tolerance.

</details>

<details>
<summary><b>What is Object Storage in the cloud?</b></summary>

Object storage is a cloud-based storage architecture that stores data as objects (instead of files or blocks). Examples include Amazon S3 and Azure Blob Storage.

</details>

<details>
<summary><b>What is Block Storage in cloud computing?</b></summary>

Block storage stores data in fixed-sized blocks, commonly used for databases and virtual machines. Examples: AWS EBS, Azure Managed Disks.

</details>

<details>
<summary><b>What is a Content Delivery Network (CDN)?</b></summary>

A CDN is a distributed network of servers that caches content close to users for faster delivery. Examples: AWS CloudFront, Azure CDN.

</details>

<details>
<summary><b>What is an IAM role in cloud security?</b></summary>

An IAM (Identity and Access Management) role grants permissions to cloud services without needing credentials stored on a server.

</details>

### 🟡 Intermediate

<details>
<summary><b>What is a cloud region?</b></summary>

A cloud region is a geographic area where a cloud provider has multiple data centers. Each region consists of multiple Availability Zones (AZs), ensuring redundancy and high availability. For example, AWS `us-east-1` (North Virginia) has multiple AZs like `us-east-1a`, `us-east-1b`, etc.

</details>


<details>
<summary><b>How do you secure data in cloud storage?</b></summary>

- **Encryption:** Use AES-256 for data at rest and TLS for data in transit.
- **Access Control:** Implement IAM policies and bucket policies to restrict access.
- **Versioning:** Enable object versioning to recover deleted or modified files.
- **Auditing:** Use AWS CloudTrail, Azure Monitor, or GCP Audit Logs to track access.

</details>

<details>
<summary><b>What is a Stateful vs. Stateless application in the cloud?</b></summary>

- **Stateless Application:** Doesn't retain session data. Each request is independent (e.g., REST APIs, serverless functions). Scales easily.
- **Stateful Application:** Retains user state across requests (e.g., databases, messaging queues). Requires persistent storage (e.g., AWS EBS, Azure Managed Disks).

</details>

<details>
<summary><b>What is auto-scaling, and how does it work?</b></summary>

Auto-scaling automatically adjusts the number of cloud instances based on traffic load. Horizontal scaling adds/removes instances, while vertical scaling increases/decreases resources on existing instances. For example, an AWS Auto Scaling Group increases EC2 instances when CPU usage exceeds 70%.

</details>

<details>
<summary><b>What is Terraform, and how does it help in cloud automation?</b></summary>

Terraform is an Infrastructure as Code (IaC) tool used to define and provision cloud resources using declarative configurations. It enables version control for infrastructure, supports multi-cloud deployments, and automates infrastructure provisioning.

</details>

<details>
<summary><b>How do you handle logging in a cloud environment?</b></summary>

- **AWS:** Use CloudWatch Logs and CloudTrail.
- **Azure:** Use Monitor and Log Analytics.
- **GCP:** Use Stackdriver Logging.
- Best practices include centralised logging, structured logs (JSON), and retention policies.

</details>

<details>
<summary><b>What is a Bastion Host, and why is it used?</b></summary>

A Bastion Host is a publicly accessible server that provides secure SSH access to private cloud resources. It reduces attack surface by acting as a single controlled entry point to internal instances.

</details>

### 🔴 Advanced

<details>
<summary><b>What is a Service Level Agreement (SLA) in cloud computing?</b></summary>

An SLA is a contract between a cloud provider and a customer defining uptime guarantees (e.g., AWS offers 99.99% uptime for EC2), response times, and penalties if the SLA is not met (e.g., refunds or service credits).

</details>

<details>
<summary><b>How do you optimize cloud costs?</b></summary>

- Use Reserved or Spot Instances instead of On-Demand.
- Enable Auto-scaling to scale down during low traffic.
- Monitor usage with AWS Cost Explorer or Azure Cost Management.
- Right-size resources by selecting appropriate instance sizes.

</details>


<details>
<summary><b>How do you implement multi-region deployments?</b></summary>

- **Data Replication:** Sync databases across regions.
- **Traffic Routing:** Use DNS-based routing (e.g., AWS Route 53).
- **Failover Mechanism:** Auto-switch to another region in case of failure.

</details>

---

## 🐧 Linux & System Administration

### 🟢 Beginner

<details>
<summary><b>What is Linux and why is it popular in DevOps?</b></summary>

Linux is an open-source operating system kernel initially created by Linus Torvalds in 1991. It has become the foundation of modern infrastructure due to several key characteristics that make it ideal for DevOps environments. Its open-source nature allows for customization and community-driven improvements, while its stability and security provide reliable foundations for production systems. The modular design enables users to install only necessary components, reducing attack surfaces and resource consumption.

Linux powers most servers, cloud platforms, and containerization technologies like Docker and Kubernetes, making it fundamental to DevOps practices. Its powerful command-line interface facilitates automation through scripting, and built-in networking capabilities support distributed systems. The wide variety of distributions (Ubuntu, CentOS, RHEL, etc.) offers flexibility for different use cases, from lightweight container hosts to enterprise servers.

Additionally, Linux's permission model and user management align well with DevOps security practices, while its resource efficiency allows for higher density deployments compared to other operating systems. The extensive tooling ecosystem developed around Linux provides solutions for every aspect of the software development lifecycle.

</details>

<details>
<summary><b>What are the fundamental Linux file permissions?</b></summary>

Linux file permissions are categorized into three types (read, write, execute) for three user classes (owner, group, others). Read (r=4) allows viewing file contents, write (w=2) enables modification, and execute (x=1) permits running as a program. These are displayed in the format rwxrwxrwx representing permissions for owner, group, and others respectively. For example, -rwxr-xr-- shows the owner has full permissions (7), the group can read and execute (5), and others can only read (4). These permissions can be modified using the chmod command with either symbolic (u+x) or numeric (755) notation.

</details>

<details>
<summary><b>How do you change file permissions in Linux?</b></summary>

File permissions in Linux are changed using the chmod command in two formats: symbolic or numeric mode. Symbolic mode uses the format chmod [who][operation][permissions] where 'who' is u (user/owner), g (group), o (others), or a (all); 'operation' is + (add), - (remove), or = (set exactly); and 'permissions' are r (read), w (write), or x (execute). For example, chmod u+x script.sh adds execute permission for the owner. Numeric mode uses octal values where read=4, write=2, execute=1; adding these values for each user class creates a 3-digit code. For instance, chmod 755 script.sh sets rwx for owner (7) and r-x for group and others (5).

</details>

<details>
<summary><b>What is the difference between soft link and hard link in Linux?</b></summary>

Hard links and soft links (symbolic links) are two ways to reference files in Linux. A hard link is a direct reference to the inode of an existing file, essentially creating another directory entry pointing to the same data. Hard links share the same inode number, cannot cross filesystem boundaries, and the original data remains accessible even if the original file is deleted. Soft links, created with ln -s, are special files that point to the pathname of another file, similar to shortcuts in Windows. They have different inode numbers from the original file, can span across filesystems, and become invalid if the original file is deleted.

</details>

<details>
<summary><b>What is a process in Linux and how do you manage processes?</b></summary>

A process in Linux is an instance of a running program with its own memory space and system resources, identified by a unique Process ID (PID). Processes can be managed using commands like ps to view current processes, top or htop for interactive monitoring, and kill to terminate processes by sending signals. You can control processes with commands like nice and renice to adjust priority, or use bg and fg to move processes between background and foreground. Additionally, you can start programs in the background by appending & to commands, and use jobs to list background processes.

</details>

<details>
<summary><b>What is the difference between a daemon and a regular process?</b></summary>

A daemon is a background process that runs without direct user interaction, typically started at system boot and running continuously to provide services. Daemons often have names ending with 'd' (e.g., sshd, httpd), run with system privileges, have no controlling terminal, and are managed via service management tools like systemd. In contrast, regular processes are usually started by users directly, run in the foreground with user interaction, have a controlling terminal, typically run with the privileges of the user who started them, and terminate when their task is complete or when explicitly terminated by the user.

</details>

<details>
<summary><b>Explain the Linux directory structure and key directories</b></summary>

Linux follows the Filesystem Hierarchy Standard (FHS) with key directories including: / (root directory), /bin (essential commands), /boot (boot loader files), /etc (system configuration), /home (user home directories), /var (variable data like logs), /usr (user programs), /lib (libraries), /tmp (temporary files), /proc and /sys (virtual filesystems for system information), and /dev (device files). Important directories for system administrators include /var/log (system logs), /etc/systemd/system (systemd service files), and /opt (optional software). This standardized structure helps maintain consistency across different Linux distributions.

</details>

<details>
<summary><b>What are environment variables and how do you set them in Linux?</b></summary>

Environment variables are dynamic named values that affect the behavior of running processes in Linux. They store information like the system's search path, default shell, and user session details. You can view variables using env or echo $VARIABLE_NAME. To set variables for the current session, use export VARIABLE=value or simply VARIABLE=value (for shell-only scope). For persistent settings, add export commands to shell profiles like ~/.bashrc (user-specific) or /etc/profile (system-wide). Common variables include PATH (executable search path), HOME (user's home directory), and USER (current username).

</details>

<details>
<summary><b>What is SSH and how do you use it securely?</b></summary>

SSH (Secure Shell) is a cryptographic network protocol used for secure remote system administration and file transfers. Basic usage is ssh username@hostname, but security best practices include: using key-based authentication instead of passwords (ssh-keygen to create keys, ssh-copy-id to deploy), disabling root login, changing the default port, implementing fail2ban to prevent brute force attacks, and using strong encryption algorithms. The SSH config file (~/.ssh/config) can simplify connections and set per-host security options. For additional security, consider implementing two-factor authentication and limiting user access with AllowUsers/AllowGroups directives.

</details>

<details>
<summary><b>What is systemd and how do you manage services with it?</b></summary>

Systemd is the init system and service manager used in most modern Linux distributions to manage system startup and services. Common systemd commands include: systemctl start/stop/restart service to control services, systemctl enable/disable service to set autostart at boot, systemctl status service to check service status, and journalctl -u service to view service logs. Systemd uses unit files (typically stored in /etc/systemd/system/) to define service behavior, dependencies, and startup conditions. To create a custom service, you write a unit file with [Unit], [Service], and [Install] sections, then run systemctl daemon-reload to register it.

</details>

<details>
<summary><b>How do you schedule tasks in Linux using cron?</b></summary>

Cron is a time-based job scheduler in Linux that allows users to automate tasks at specified intervals. The crontab format consists of five time fields (minute, hour, day of month, month, day of week) followed by the command to execute. For example, 0 2 * * * /backup.sh runs a backup script at 2 AM daily. You manage cron jobs with crontab -e (edit), crontab -l (list), and crontab -r (remove). Special time shortcuts include @daily, @weekly, and @reboot. System-wide cron directories like /etc/cron.daily/ can also be used. For jobs that need to run at odd intervals, consider using anacron which ensures tasks run even if the computer was powered off at the scheduled time.

</details>

<details>
<summary><b>How do you monitor system performance in Linux?</b></summary>

Linux provides various commands for system performance monitoring. For CPU and memory, use top or htop for real-time monitoring, uptime for load averages, and free -h for memory usage. For disk usage and I/O, use df -h for filesystem space, du -sh for directory sizes, and iostat for I/O statistics. Network monitoring tools include netstat, ss, and iftop. More comprehensive tools include sysstat (providing sar for historical data collection), glances for all-in-one monitoring, and nmon for performance analysis. For distributed systems, consider implementing monitoring solutions like Prometheus, Grafana, or Nagios.

</details>

<details>
<summary><b>What is a package manager and how do you use it?</b></summary>

A package manager is a tool that automates installing, updating, configuring, and removing software on Linux. Debian-based distributions (Ubuntu) use APT with commands like apt update (refresh package lists), apt install package (install software), apt upgrade (update all packages), and apt remove package (uninstall software). Red Hat-based distributions (RHEL/CentOS) use YUM or DNF with similar commands. Package managers handle dependencies automatically, maintain a database of installed software, and can verify package integrity. They also support repositories (software sources), which can be added to extend available packages. Common operations include searching for packages (apt search or yum search) and listing installed packages (apt list --installed or yum list installed).

</details>

<details>
<summary><b>What is RAID and what are the common RAID levels?</b></summary>

RAID (Redundant Array of Independent Disks) combines multiple physical disks into logical units for data redundancy, performance improvement, or both. Common RAID levels include: RAID 0 (striping) which splits data across disks for performance but offers no redundancy; RAID 1 (mirroring) which duplicates data for redundancy but uses 50% capacity; RAID 5 which uses distributed parity for redundancy with better space efficiency; RAID 6 which adds double parity to survive two disk failures; and RAID 10 (combining RAID 1+0) which offers both mirroring and striping for high performance and redundancy. Linux systems typically implement RAID using either hardware controllers or software RAID via the mdadm utility.

</details>

<details>
<summary><b>What is LVM and why is it useful?</b></summary>

LVM (Logical Volume Manager) is a storage abstraction layer that provides flexible disk management in Linux. It consists of Physical Volumes (PVs), which are grouped into Volume Groups (VGs), from which Logical Volumes (LVs) are created as the actual partitions. LVM's key benefits include: the ability to resize volumes on-the-fly without downtime, spanning volumes across multiple disks, taking snapshots for backups, and migrating data between storage devices while online. Common LVM commands include pvcreate, vgcreate, lvcreate for creation; pvdisplay, vgdisplay, lvdisplay for viewing information; and lvextend followed by resize2fs for growing filesystems.

</details>

<details>
<summary><b>What is the purpose of /etc/fstab file?</b></summary>

The /etc/fstab (file system table) file is a configuration file that defines how disk partitions, block devices, or remote filesystems should be mounted into the Linux file system hierarchy. Each line represents a mount configuration with six fields: the device/partition (UUID or path), mount point, filesystem type, mount options, dump flag (for backups), and fsck order (for filesystem checks). The file is read at boot time to automatically mount filesystems, but users can also reference it with commands like mount -a. Common mount options include defaults, auto/noauto (mount at boot or not), ro/rw (read-only/read-write), and noexec (prevent execution of files). Using UUIDs instead of device paths is recommended for stability.

</details>

<details>
<summary><b>How do you troubleshoot network connectivity issues in Linux?</b></summary>

Network troubleshooting in Linux follows a systematic approach. First, check interface status with ip addr or ifconfig. Test basic connectivity with ping to localhost, gateway, and external IPs to isolate the issue. Verify DNS resolution with nslookup or dig. Examine routing with ip route or route -n. For specific service issues, check if ports are open with ss -tulpn or netstat -tulpn. Test remote connectivity with telnet or nc. Analyze the network path with traceroute or mtr. For detailed packet analysis, use tcpdump. Review firewall rules with iptables -L or firewall-cmd --list-all. Finally, examine system logs in /var/log/syslog or using journalctl for error messages.

</details>

<details>
<summary><b>How do you set up and configure a basic firewall in Linux?</b></summary>

Linux offers several firewall options. For Ubuntu/Debian, UFW (Uncomplicated Firewall) provides a simple interface: sudo ufw default deny incoming, sudo ufw default allow outgoing, sudo ufw allow ssh (or other services/ports), then sudo ufw enable. For RHEL/CentOS, firewalld is the default: sudo firewall-cmd --permanent --add-service=ssh, sudo firewall-cmd --permanent --add-service=http, then sudo firewall-cmd --reload. For lower-level control, iptables can be used: sudo iptables -A INPUT -p tcp --dport 22 -j ACCEPT, sudo iptables -A INPUT -m state --state ESTABLISHED,RELATED -j ACCEPT, sudo iptables -P INPUT DROP. Always allow SSH access before enabling firewall rules to prevent lockouts.

</details>

<details>
<summary><b>What is SELinux and AppArmor? How do they enhance security?</b></summary>

SELinux and AppArmor are Linux Security Modules (LSMs) that implement Mandatory Access Control (MAC) to enhance system security beyond traditional permissions. SELinux, developed by the NSA and used in Red Hat systems, uses security contexts and policies to control process actions based on types, roles, and levels. AppArmor, used in Ubuntu and SUSE, uses profiles to restrict programs' capabilities based on file paths. Both restrict processes even when running as root, limiting damage from compromised applications and preventing privilege escalation. They operate in different modes: enforcing/permissive for SELinux and enforce/complain for AppArmor, allowing administrators to test policies before full enforcement.

</details>

<details>
<summary><b>How do you manage user accounts and permissions in Linux?</b></summary>

User management in Linux involves several commands: useradd/adduser to create users, usermod to modify accounts, passwd to set passwords, and userdel to remove users. For groups, use groupadd, groupmod, and groupdel. File permissions are managed with chown (change owner), chgrp (change group), and chmod (change permissions). The sudo mechanism allows delegated privileges without sharing the root password, configured via visudo. For enhanced access control beyond the basic user/group/other model, Access Control Lists (ACLs) can be implemented with setfacl and getfacl. Password policies and account expiration can be set with chage, while user resource limits are configured through /etc/security/limits.conf.

</details>

### 🟡 Intermediate

<details>
<summary><b>How do you optimize Linux server performance?</b></summary>

Optimizing Linux server performance requires a systematic approach addressing multiple subsystems. For CPU optimization, start by identifying bottlenecks using tools like top, htop, and mpstat, then adjust process priorities with nice/renice commands, configure CPU governors (switching from "powersave" to "performance" mode), and consider CPU affinity settings with taskset to bind critical processes to specific cores. Process scheduling can be further tuned through kernel parameters in /proc/sys/kernel/.

Memory optimization involves adjusting the swappiness parameter (vm.swappiness) to control how aggressively the kernel swaps to disk, implementing huge pages for database workloads, and managing the cache pressure. File system cache behavior can be tuned through vm.dirty_ratio and related parameters. For applications, especially Java-based ones, configure appropriate heap sizes and garbage collection strategies.

Disk I/O performance can be significantly improved by selecting appropriate filesystems (like XFS for large files or ext4 for general use), using mount options like noatime to reduce unnecessary writes, selecting optimal I/O schedulers for your workload (deadline for SSDs, cfq for HDDs with mixed workloads), and implementing RAID configurations or SSD caching for frequently accessed data. Network performance enhancements include adjusting TCP buffer sizes, window scaling, configuring jumbo frames for high-throughput environments, and optimizing NIC interrupt coalescence.

Beyond these specific subsystems, implement appropriate resource limits in /etc/security/limits.conf, tune kernel parameters via sysctl.conf, and adjust application-specific settings like database buffer pools, connection handling, and web server worker processes. Establish performance baselines and regularly monitor metrics to identify emerging bottlenecks before they impact users.

</details>

<details>
<summary><b>How do you implement centralized logging in a Linux environment?</b></summary>

Centralized logging collects logs from multiple servers to a central location for analysis, troubleshooting, and compliance. Common architectures include the ELK stack (Elasticsearch for storage, Logstash for processing, Kibana for visualization) with Filebeat as a log shipper, or Graylog which combines Elasticsearch and MongoDB. For simpler setups, rsyslog can forward logs to a central server by configuring clients with *.* @logserver:514 and the server to receive and store these logs. Security considerations include encrypting log transmission (TLS/SSL), implementing log rotation for storage management, and setting proper retention policies. The implementation typically involves installing the necessary components, configuring servers to ship logs, setting up parsing rules for structured logging, and creating dashboards for visualization.

</details>

<details>
<summary><b>How do you implement backup and recovery strategies for Linux systems?</b></summary>

A comprehensive Linux backup strategy balances Recovery Point Objective (RPO) and Recovery Time Objective (RTO) requirements. Common tools include rsync for file-level backups (rsync -avz --delete /source/ /backup/), tar for archiving, and dd for disk imaging. For databases, use specialized tools like mysqldump or pg_dump for logical backups, or tools like XtraBackup for hot physical backups. Implement incremental backups to reduce storage and backup windows. For enterprise environments, consider solutions like Bacula, Amanda, or Restic. Schedule regular backups using cron and implement retention policies to manage storage. Critical components include encryption for sensitive data, off-site copies (following the 3-2-1 rule), automated verification testing, and well-documented recovery procedures with regular recovery testing.

</details>

<details>
<summary><b>How do you secure a Linux server?</b></summary>

Securing a Linux server involves multiple layers. Minimize the attack surface by installing only necessary packages and disabling unused services. Implement strong user account security with password policies, regular password rotation, and principle of least privilege using sudo. Harden SSH by disabling root login, using key-based authentication, and changing the default port. Configure a firewall (UFW, firewalld, or iptables) to restrict access to required services only. Implement Mandatory Access Control with SELinux or AppArmor. Keep the system updated with security patches, using automatic updates for critical fixes. Set up intrusion detection with tools like fail2ban to block brute force attempts. Enable system auditing, implement secure mount options, and ensure proper file permissions. Regularly review logs and conduct security audits to identify potential vulnerabilities.

</details>

<details>
<summary><b>How do you manage kernel parameters and modules in Linux?</b></summary>

Kernel parameters control Linux kernel behavior and can be viewed with sysctl -a. Temporary changes are made with sysctl -w parameter=value or by writing to files in /proc/sys/. For permanent changes, add entries to /etc/sysctl.conf or files in /etc/sysctl.d/. Kernel modules extend functionality and are managed with commands like lsmod (list loaded modules), modinfo (show module details), modprobe (load modules with dependencies), and rmmod (unload modules). To load modules at boot, add them to /etc/modules. Blacklist unwanted modules by adding entries to /etc/modprobe.d/blacklist.conf. Module parameters can be set temporarily via /sys/module/<module>/parameters/ or permanently in configuration files under /etc/modprobe.d/.

</details>

<details>
<summary><b>How do you troubleshoot high CPU, memory, or disk I/O usage in Linux?</b></summary>

Troubleshooting resource issues in Linux requires identifying the source of the problem. For high CPU usage, use top/htop to identify CPU-intensive processes, ps aux --sort=-%cpu to sort by CPU usage, and tools like perf for profiling. For memory issues, use free -h to check available memory, ps aux --sort=-%mem to identify memory-hungry processes, and vmstat to monitor swapping activity. Disk I/O bottlenecks can be diagnosed with iostat -x, iotop to see which processes are causing I/O, and df/du to find disk space usage. For a holistic view, tools like sysstat (providing sar), glances, or nmon can monitor multiple resources simultaneously. Once the cause is identified, remediation might involve optimizing application configuration, adjusting resource limits, or upgrading hardware.

</details>

<details>
<summary><b>What is load balancing and how do you implement it in Linux?</b></summary>

Load balancing distributes traffic or workloads across multiple servers to improve reliability, performance, and availability. Linux offers several load balancing options: HAProxy and Nginx operate at layer 7 (application level) allowing content-based routing, while Linux Virtual Server (LVS) with Keepalived works at layer 4 (transport level) for higher throughput. HAProxy implementation involves installing the package, configuring frontend (client-facing) and backend (server pool) sections in /etc/haproxy/haproxy.cfg, choosing an algorithm (round-robin, least connections, etc.), and setting health checks. Nginx configuration uses the upstream directive to define server pools. For high availability, implement master-backup configurations with Keepalived using Virtual Router Redundancy Protocol (VRRP) to provide automatic failover between load balancers.

</details>

<details>
<summary><b>What is containerization and how do you use containers in Linux?</b></summary>

Containerization is a lightweight virtualization technology that packages applications with their dependencies, providing consistency across environments while sharing the host OS kernel. Docker is the most popular container platform in Linux, allowing you to build, share, and run containers. Basic Docker commands include: docker pull image to download images, docker run image to start containers, docker ps to list running containers, and docker build -t name . to build custom images from a Dockerfile. Containers can be orchestrated with Kubernetes for production deployments, providing features like scaling, self-healing, and rolling updates. Container advantages include isolation, portability across environments, efficient resource utilization, and faster deployment compared to traditional VMs. Security considerations include image scanning, running as non-root users, and implementing resource limits.

</details>

<details>
<summary><b>How do you implement configuration management in Linux environments?</b></summary>

Configuration management automates and standardizes system configuration across multiple servers. Popular tools include Ansible (agentless, uses SSH, YAML-based), Puppet (agent-based, uses its DSL, pull model), Chef (agent-based, Ruby-based, pull model), and SaltStack (agent-based, event-driven). Ansible implementation involves creating an inventory file with target hosts, writing playbooks (YAML files defining desired state), and executing with ansible-playbook playbook.yml. Best practices include version controlling configuration code, using roles or modules for reusability, implementing environment-specific variables, testing changes in staging environments first, and documenting the configuration structure. This approach provides benefits like consistency across servers, automated provisioning, reduced configuration drift, easier scaling, and comprehensive change tracking with the ability to quickly recover from misconfigurations.

</details>

<details>
<summary><b>What is Software RAID and how do you implement it in Linux?</b></summary>

Software RAID (Redundant Array of Independent Disks) in Linux provides disk redundancy or performance improvements using the kernel's md (multiple device) driver. It's implemented using the mdadm utility. Common implementations include: RAID 1 (mirroring) with mdadm --create /dev/md0 --level=1 --raid-devices=2 /dev/sda1 /dev/sdb1, RAID 5 (striping with parity) with mdadm --create /dev/md0 --level=5 --raid-devices=3 /dev/sda1 /dev/sdb1 /dev/sdc1, or RAID 10 (mirroring and striping) for both redundancy and performance. After creation, the array can be formatted (mkfs.ext4 /dev/md0) and mounted. For persistence across reboots, update /etc/mdadm/mdadm.conf with mdadm --detail --scan >> /etc/mdadm/mdadm.conf and add the array to /etc/fstab. Monitor RAID health with cat /proc/mdstat or mdadm --detail /dev/md0.

</details>

<details>
<summary><b>How do you manage disk quotas in Linux?</b></summary>

Disk quotas limit the amount of disk space users or groups can use on Linux filesystems. To implement quotas, first modify /etc/fstab to include quota options (usrquota,grpquota) for the target filesystem, then remount it. Create quota database files with quotacheck -cum /mount/point. Enable quotas with quotaon -v /mount/point. Set quotas using edquota -u username for users or edquota -g groupname for groups, defining soft limits (warnings), hard limits (strict enforcement), and grace periods. Copy quota settings between users with edquota -p reference_user -u target_user. Monitor usage with repquota -a for all filesystems or quota -u username for specific users. Quotas help prevent individual users from consuming excessive resources, especially on multi-user systems or shared hosting environments.

</details>

<details>
<summary><b>What is systemd-networkd and how do you configure networking with it?</b></summary>

Systemd-networkd is a system daemon for managing network configurations in systemd-based Linux distributions, providing a modern alternative to traditional networking scripts. To use it, enable the service with systemctl enable --now systemd-networkd and systemctl enable --now systemd-resolved. Network configurations are defined in /etc/systemd/network/ using .network files for interface settings and .netdev files for virtual devices. A basic static IP configuration would use a .network file containing [Match] section to identify the interface and [Network] section for IP settings. For example, [Match] Name=eth0 [Network] Address=192.168.1.100/24 Gateway=192.168.1.1 DNS=8.8.8.8. For DHCP, simply use DHCP=yes in the [Network] section. After making changes, restart the service with systemctl restart systemd-networkd.

</details>

<details>
<summary><b>What are Linux namespaces and how are they used?</b></summary>

Linux namespaces are a kernel feature that isolate and virtualize system resources for processes, forming the foundation of container technologies like Docker. The main namespace types include: PID (process isolation), NET (network interfaces), MNT (filesystem mount points), UTS (hostname), IPC (inter-process communication), USER (user and group IDs), and CGROUP (control groups). They can be manipulated using the unshare command to create new namespaces or nsenter to enter existing ones. For example, unshare --net bash creates a shell in a new network namespace. Namespaces enable containerization by allowing processes to have their own isolated view of system resources without full virtualization overhead. This isolation provides security benefits while allowing efficient resource sharing of the underlying kernel.

</details>

<details>
<summary><b>How do you implement disk encryption in Linux?</b></summary>

Disk encryption in Linux protects data from unauthorized access if physical security is compromised. For full disk encryption, use LUKS (Linux Unified Key Setup) with the cryptsetup utility. During installation, most distributions offer encryption options, or you can encrypt post-installation with commands like cryptsetup luksFormat /dev/sdb1 to create an encrypted container and cryptsetup luksOpen /dev/sdb1 cryptname to open it. For home directory encryption, use eCryptfs with ecryptfs-migrate-home --user username. For individual files or directories, use VeraCrypt or gpg for file-based encryption. Encrypted volumes can be automatically mounted at boot by adding entries to /etc/crypttab and /etc/fstab. Key management considerations include using strong passphrases, key files on separate media, or TPM modules where available. Always maintain backups of encryption headers and recovery keys.

</details>

<details>
<summary><b>What is systemd-journald and how do you use it for system logging?</b></summary>

Systemd-journald is a system service that collects and stores logging data in a structured, indexed journal format. Unlike traditional syslog, it captures metadata like systemd unit, priority, and timestamps in a binary format. Access logs with journalctl using various filters: journalctl -u service-name for specific services, journalctl -b for current boot, journalctl -p err for error-level messages, or journalctl -f to follow new entries. For persistent storage across reboots, create /var/log/journal/ directory. Configure journald through /etc/systemd/journald.conf, where you can set options like storage method (volatile, persistent, auto), maximum sizes, and retention periods. Journald can forward logs to traditional syslog daemons for compatibility with existing tools. The journal's structured format enables more powerful querying and analysis compared to plain text logs.

</details>

<details>
<summary><b>How do you manage system time and NTP in Linux?</b></summary>

Proper time synchronization is crucial for logs, authentication, and distributed systems. Modern Linux distributions use systemd-timesyncd or chronyd as NTP clients. Check the current time with timedatectl status. Set the timezone with timedatectl set-timezone Region/City. Enable NTP synchronization with timedatectl set-ntp true. For more advanced setups, install chrony (apt install chrony or dnf install chrony), configure NTP servers in /etc/chrony/chrony.conf or /etc/chrony.conf, and restart the service with systemctl restart chronyd. Monitor synchronization status with chronyc tracking and sources with chronyc sources. For systems requiring precise time, consider hardware options like GPS-disciplined oscillators. In isolated networks, set up an internal NTP server hierarchy to distribute time accurately.

</details>

<details>
<summary><b>What is Linux resource management with cgroups?</b></summary>

Control Groups (cgroups) provide a mechanism to limit, account for, and isolate resource usage of process groups in Linux. Modern systems use cgroups v2, managed through systemd. Cgroups control CPU, memory, disk I/O, and network resources. Create a systemd slice with a unit file in /etc/systemd/system/custom.slice containing resource limits. Manage running services with commands like systemctl set-property service-name CPUQuota=20% or systemctl set-property service-name MemoryLimit=1G. For container environments, Docker and Kubernetes use cgroups to enforce resource limits with parameters like --memory and --cpus. View resource controller settings with systemd-cgls to display the hierarchy and systemd-cgtop to monitor resource usage. Cgroups are essential for multi-tenant systems and prevent resource starvation by enforcing fair allocation.

</details>

<details>
<summary><b>What is Linux Traffic Control (tc) and how is it used?</b></summary>

Linux Traffic Control (tc) is a powerful framework for managing network traffic through Quality of Service (QoS) policies, traffic shaping, and bandwidth allocation. It uses the concept of queueing disciplines (qdiscs) to control how packets are sent and received. Common use cases include limiting bandwidth with tc qdisc add dev eth0 root tbf rate 1mbit burst 32kbit latency 400ms, prioritizing traffic types with Hierarchical Token Bucket (HTB) classes, implementing fair queuing with Stochastic Fairness Queuing (SFQ), and reducing latency with Controlled Delay (CoDel) for bufferbloat mitigation. Traffic can be classified using filters based on IP addresses, ports, or other criteria. TC is particularly useful for WAN links, ensuring critical services get priority, preventing a single user from consuming all bandwidth, and simulating network conditions for testing.

</details>

<details>
<summary><b>How do you implement high availability for Linux servers?</b></summary>

High availability (HA) in Linux ensures systems remain operational despite component failures. Common implementations use Pacemaker and Corosync for cluster management. Install with apt install pacemaker corosync or dnf install pacemaker corosync, configure cluster nodes in /etc/corosync/corosync.conf, and define resources like virtual IPs, services, and failover policies. For database HA, solutions include MySQL/MariaDB with Galera Cluster, PostgreSQL with replication and Patroni, or MongoDB replica sets. Load balancing with HAProxy or Nginx provides service distribution and failover. Storage can be replicated using DRBD or shared using clustered filesystems like GFS2 or OCFS2. Implement fencing mechanisms to handle split-brain scenarios. Monitor the cluster with pcs status or tools like Nagios/Prometheus. Testing is crucial—regularly simulate failures to verify failover works correctly. Document recovery procedures for when automatic failover isn't possible.

</details>

### 🔴 Advanced

<details>
<summary><b>How do you implement Linux network bonding and teaming?</b></summary>

Network bonding and teaming in Linux combine multiple physical network interfaces into a single logical interface to provide increased bandwidth, redundancy, or both. While they serve similar purposes, they use different implementations - bonding is the traditional approach built into the kernel, while teaming (introduced in RHEL 7) offers a more modern implementation with improved performance and flexibility.

To implement bonding, first install the required package with apt install ifenslave or yum install bonding-tools. Create a configuration in /etc/network/interfaces (Debian/Ubuntu) or /etc/sysconfig/network-scripts/ (RHEL/CentOS) defining the bond interface, slave interfaces, and bonding mode. Common modes include mode 0 (round-robin), mode 1 (active-backup), mode 4 (802.3ad/LACP), and mode 6 (balance-alb). For example, a mode 1 active-backup configuration provides failover redundancy, while mode 4 with LACP provides both increased bandwidth and redundancy when supported by your network switch.

For network teaming, install the teamd package (apt install teamd or yum install teamd) and create a configuration using either NetworkManager or the native configuration files. Teaming offers runner types that correspond to bonding modes, such as "activebackup" (similar to bond mode 1) or "lacp" (similar to bond mode 4), but with improved handling of link monitoring and failover.

Both implementations require switch configuration for modes that involve link aggregation (like LACP). After configuration, verify your setup with commands like cat /proc/net/bonding/bond0 for bonding or teamdctl team0 state for teaming. Monitor interface status with tools like ip -s link show to verify that traffic is properly distributed across the physical interfaces according to your selected mode.

</details>

<details>
<summary><b>How do you configure and troubleshoot IPtables firewall?</b></summary>

IPtables is a powerful packet filtering framework in Linux that serves as a firewall by controlling incoming and outgoing network traffic. It operates by processing packets through chains (INPUT, OUTPUT, FORWARD) within tables (filter, nat, mangle, raw), with each chain containing rules that determine the fate of matching packets. Configuration involves defining these rules with specific criteria and actions.

Basic configuration starts with setting default policies using iptables -P INPUT DROP to deny all incoming traffic by default, and then explicitly allowing necessary connections with rules like iptables -A INPUT -p tcp --dport 22 -j ACCEPT for SSH. For a complete firewall, you'll need rules to allow established connections (-m state --state ESTABLISHED,RELATED), loopback interface traffic, and specific services while blocking everything else.

Common troubleshooting approaches include: temporarily disabling the firewall (iptables -F) to determine if it's causing an issue; using iptables -L -v -n to view current rules with packet counters; adding logging rules (-j LOG) before DROP rules to see which traffic is being blocked; and testing connectivity from both inside and outside the network. Stateful rules often cause subtle issues, particularly with protocols like FTP that use dynamic ports.

For persistence across reboots, save rules with iptables-save > /etc/iptables/rules.v4 and restore them at boot through distribution-specific methods like netfilter-persistent or custom service files. For complex environments, consider tools like ufw (Uncomplicated Firewall) or firewalld that provide higher-level abstractions over iptables, making management simpler while still leveraging iptables' underlying power.

</details>

<details>
<summary><b>How do you implement and manage SELinux policies?</b></summary>

SELinux (Security-Enhanced Linux) provides Mandatory Access Control by defining fine-grained permissions through security policies. Implementing and managing these policies involves understanding several key components: security contexts (user:role:type:level), policy types (targeted, strict, mls), and enforcement modes (enforcing, permissive, disabled).

Effective management starts with setting the appropriate mode in /etc/selinux/config. For most production systems, running in enforcing mode provides security benefits while permissive mode is useful during troubleshooting or policy development. Monitor SELinux status with sestatus and view alerts with ausearch -m AVC or through /var/log/audit/audit.log.

When deploying applications, properly label files and ports using commands like semanage fcontext -a -t httpd_sys_content_t "/var/www/html(/.*)?" and restorecon -Rv /var/www/html to apply contexts. For network connections, manage port labels with semanage port -a -t http_port_t -p tcp 8080 to allow services to use non-standard ports.

Custom policy modules are essential for applications without pre-defined policies. Generate these through an iterative process: run the application in permissive mode, gather AVC denial messages, convert them to policy modules using audit2allow -a -M mymodule, review the generated policy, and install it with semodule -i mymodule.pp. For production, refine these auto-generated policies to follow the principle of least privilege.

Best practices include thoroughly testing applications with SELinux enabled before deployment, using tools like sealert for guided troubleshooting, maintaining documentation of custom policies, and resisting the temptation to globally disable SELinux when encountering issues. Proper SELinux implementation significantly improves system security by containing breaches and preventing privilege escalation.

</details>

<details>
<summary><b>How do you manage and monitor system logs effectively?</b></summary>

Effective log management in Linux combines proper configuration, centralization, rotation, analysis, and monitoring to extract maximum value from system logs while managing storage requirements. The foundation starts with configuring appropriate logging levels in /etc/rsyslog.conf or through the Journal in systemd-based systems, ensuring critical events are captured without generating excessive noise.

Log rotation is essential to prevent logs from consuming all available disk space. Configure logrotate to compress, rotate, and eventually delete old logs based on size or time thresholds. A typical configuration in /etc/logrotate.d/ might rotate logs weekly, keep four weeks of history, and compress older files. For critical logs, configure secure archiving to immutable storage for compliance and security forensics.

For monitoring and analysis, combine automated and manual approaches. Deploy log monitoring tools like Logwatch for daily summaries, use Fail2ban to detect and respond to suspicious activity patterns, and set up log aggregation with ELK (Elasticsearch, Logstash, Kibana) or Graylog for centralized analysis across multiple systems. Configure alerts for critical events using tools like Nagios or Prometheus with Alertmanager.

In larger environments, implement log shipping from all servers to a central log server using rsyslog's forwarding capabilities or specialized agents like Filebeat. This centralization facilitates cross-system correlation, simplifies backups, and protects logs from tampering on compromised systems. For security-sensitive environments, consider implementing log signing and verification to detect log tampering.

Best practices include establishing baseline patterns to identify abnormal activity, implementing consistent timestamp formats (preferably UTC) across systems, maintaining proper permissions on log files, creating documented procedures for log review during incidents, and regularly testing that logging is functioning correctly, particularly for security-critical events.

</details>

<details>
<summary><b>How do you implement and manage RAID in Linux?</b></summary>

RAID (Redundant Array of Independent Disks) in Linux provides data redundancy, improved performance, or both, depending on the RAID level implemented. Linux offers both hardware RAID (managed by dedicated controllers) and software RAID through the md (multiple device) driver, with management primarily through the mdadm utility.

Implementation begins with planning the appropriate RAID level based on requirements: RAID 0 (striping) for performance without redundancy, RAID 1 (mirroring) for redundancy, RAID 5 (striping with distributed parity) for balanced performance and redundancy, RAID 6 (dual parity) for enhanced fault tolerance, or RAID 10 (mirrored stripes) for both high performance and redundancy.

For software RAID creation, use mdadm with appropriate options: mdadm --create /dev/md0 --level=5 --raid-devices=3 /dev/sda1 /dev/sdb1 /dev/sdc1. After creation, format the array with a filesystem (mkfs.ext4 /dev/md0), configure it in /etc/fstab for automatic mounting, and ensure the RAID configuration is saved to /etc/mdadm/mdadm.conf with mdadm --detail --scan >> /etc/mdadm/mdadm.conf.

Ongoing management involves regular monitoring with cat /proc/mdstat or mdadm --detail /dev/md0 to check array status. Configure email alerts for RAID events by setting up the mdadm monitoring daemon. Implement SMART monitoring on the underlying disks with smartmontools to detect drive problems before they cause array failures.

For failed disk replacement, first identify the failed disk, then remove it from the array with mdadm /dev/md0 --fail /dev/sdb1 --remove /dev/sdb1, physically replace the drive, partition the new disk identically to the original, and add it back with mdadm /dev/md0 --add /dev/sdb1. The array will automatically rebuild, a process you can monitor through /proc/mdstat.

Perform regular scrubbing operations with echo check > /sys/block/md0/md/sync_action to verify data consistency and detect silent errors. For complete data protection, combine RAID with a robust backup strategy, as RAID is not a substitute for backups.

</details>

<details>
<summary><b>How do you manage and troubleshoot systemd services?</b></summary>

Systemd is the init system and service manager in most modern Linux distributions, providing a standardized interface for managing services, monitoring processes, and controlling system startup. Effective management starts with understanding unit files located in /etc/systemd/system/ or /usr/lib/systemd/system/, which define service behavior, dependencies, and startup conditions.

Basic service management involves commands like systemctl start|stop|restart|status service_name for immediate control and systemctl enable|disable service_name to configure automatic startup at boot. For more detailed information, systemctl show service_name displays all properties of a service, while systemctl list-dependencies service_name reveals service relationships.

Troubleshooting begins with examining service status and logs. The command systemctl status service_name provides the service state, recent log entries, and basic configuration details. For more comprehensive logging, use journalctl -u service_name to view all logs for a specific service, with options like -f for real-time following, --since "2023-01-01" for time filtering, or -p err to focus on errors.

When services fail to start, check for configuration errors with systemd-analyze verify unit_file.service. Common issues include incorrect file permissions, missing executables, unsatisfied dependencies, or resource constraints. For resource-related problems, examine the service's resource usage with systemd-cgtop to identify potential memory leaks or CPU bottlenecks.

For persistent issues, create override configurations instead of modifying original unit files: systemctl edit service_name creates a drop-in directory in /etc/systemd/system/ where you can add or override specific settings without changing the original file. After any configuration changes, run systemctl daemon-reload to apply them.

Advanced troubleshooting might involve running services in debug mode by temporarily modifying the service's ExecStart line, using environment variables to enable verbose logging, or directly executing the service binary from the command line to observe its behavior outside of systemd's management.

</details>

<details>
<summary><b>How do you configure and optimize Linux for database servers?</b></summary>

Optimizing Linux for database workloads requires a systematic approach addressing kernel parameters, memory management, storage configuration, and process scheduling to provide the performance, stability, and reliability that database systems demand.

Start with kernel parameter tuning in /etc/sysctl.conf: set vm.swappiness=10 to reduce swapping (critical for database performance), adjust vm.dirty_ratio and vm.dirty_background_ratio to optimize write flushing behavior, and increase fs.file-max and fs.nr_open to handle high connection counts. For network-intensive database clusters, tune TCP parameters like net.core.somaxconn and net.ipv4.tcp_max_syn_backlog to manage connection queues effectively.

Memory management is crucial for databases, which rely heavily on caching. Configure huge pages for database engines that support them (particularly beneficial for Oracle and PostgreSQL) by setting appropriate values in /etc/sysctl.conf and adjusting the database configuration to use them. For MySQL/MariaDB, allocate approximately 70-80% of available RAM to the buffer pool, leaving sufficient memory for the operating system and other processes.

Storage configuration significantly impacts database performance. Use the appropriate filesystem (XFS is often preferred for databases due to its scalability and performance characteristics) with optimized mount options like noatime,nodiratime to reduce unnecessary metadata updates. For I/O-intensive workloads, implement storage with appropriate RAID levels (RAID 10 is commonly recommended for balanced performance and redundancy) and consider separate volumes for data, logs, and temporary files to prevent I/O contention.

Process scheduling and limits require attention: adjust resource limits in /etc/security/limits.conf to ensure the database can create sufficient files and processes. Consider using CPU pinning with taskset or cgroups to dedicate specific cores to the database process, reducing context switching and cache thrashing. For multi-socket NUMA systems, ensure proper memory allocation across nodes with numactl or database-specific NUMA settings.

Finally, implement appropriate monitoring with tools like Prometheus, Grafana, or database-specific monitoring solutions to identify bottlenecks and validate optimizations. Remember that database optimization is iterative—establish performance baselines, make one change at a time, measure the impact, and adjust accordingly.

</details>

<details>
<summary><b>How do you implement and maintain LVM (Logical Volume Management)?</b></summary>

Logical Volume Management (LVM) in Linux provides flexible disk space management through a layer of abstraction between physical storage devices and filesystems. Implementation and maintenance involve understanding its three-level hierarchy: Physical Volumes (PVs), Volume Groups (VGs), and Logical Volumes (LVs).

Initial setup begins with creating Physical Volumes from disks or partitions using pvcreate /dev/sdb /dev/sdc. These PVs are then combined into a Volume Group with vgcreate myvg /dev/sdb /dev/sdc, creating a pool of storage. From this pool, create Logical Volumes with lvcreate -L 100G -n data myvg for fixed sizes or lvcreate -l 80%VG -n data myvg for percentage-based allocation. Finally, create filesystems on these LVs and mount them like regular partitions.

The true power of LVM lies in its flexibility for ongoing maintenance. Extend Volume Groups by adding new physical devices with vgextend myvg /dev/sdd. Grow Logical Volumes with lvextend -L +50G /dev/myvg/data followed by filesystem resizing using resize2fs for ext4 or xfs_growfs for XFS. Most modern filesystems support online resizing, eliminating downtime for capacity expansion.

For more advanced management, implement LVM snapshots to create point-in-time copies for backups or testing: lvcreate -L 5G -s -n data_snapshot /dev/myvg/data. Use logical volume mirroring for redundancy within LVM: lvconvert --type raid1 -m1 /dev/myvg/data. For storage migration, move data between physical volumes with pvmove /dev/sdb /dev/sdd to facilitate hardware replacements without service interruption.

Proper maintenance includes regular monitoring of space usage with vgs, lvs, and pvs commands. Create alerts for when Volume Groups or Logical Volumes approach capacity thresholds. Implement periodic checks of the LVM metadata with vgscan and pvscan. For critical systems, maintain backups of the LVM configuration with vgcfgbackup to facilitate disaster recovery.

Advanced features like thin provisioning can optimize storage utilization by overcommitting space, but require careful monitoring to prevent actual space exhaustion. Consider implementing automated space reclamation for thin pools to maintain performance over time.

</details>

<details>
<summary><b>What is Linux Containers (LXC) and how do they differ from Docker?</b></summary>

Linux Containers (LXC) is a lightweight virtualization technology that enables multiple isolated Linux systems (containers) to run on a single host using the host's kernel. LXC leverages Linux kernel features like namespaces (for isolation of resources like processes, network, and filesystems) and control groups (cgroups for resource limitation and accounting) to create these isolated environments without the overhead of traditional virtual machines.

The key differences between LXC and Docker lie in their design philosophy and intended use cases. LXC functions more like traditional virtual machines, typically running complete operating systems with init systems and multiple processes. It's designed for long-running, general-purpose system containers that behave similarly to VMs but with lower overhead. Docker, on the other hand, is optimized for application containers, encouraging a single-process-per-container model focused on application portability and microservices architecture.

From a technical perspective, Docker initially used LXC as its container runtime but later developed its own runtime (containerd). Docker adds several layers of abstraction and tooling on top of basic container functionality, including a layered filesystem (overlay or aufs), a standardized image format, a registry system for sharing images, and declarative application definitions through Dockerfiles. These additions make Docker more user-friendly and better suited for application deployment pipelines.

Management interfaces also differ significantly. LXC uses commands like lxc-create, lxc-start, and configuration files for container definition. Modern LXC often uses LXD as a management layer, providing REST API and improved user experience. Docker uses a unified CLI with commands like docker build, docker run, and docker-compose for multi-container applications, along with Dockerfiles for image definitions.

In DevOps workflows, LXC is often chosen when VM-like behavior is needed with minimal overhead, such as for testing environment isolation or when multiple processes need to run together in the traditional way. Docker excels in microservices architectures, CI/CD pipelines, and scenarios where application portability and standardized deployment are priorities. Many organizations use both technologies for different aspects of their infrastructure.

</details>

<details>
<summary><b>How do you implement and manage KVM virtualization?</b></summary>

KVM (Kernel-based Virtual Machine) is Linux's built-in hypervisor that transforms the kernel into a Type-1 hypervisor, allowing you to run multiple virtual machines efficiently. Implementation begins with verifying hardware virtualization support (grep -E '(vmx|svm)' /proc/cpuinfo) and installing necessary packages (apt install qemu-kvm libvirt-daemon-system virtinst or equivalent).

Management of KVM environments typically involves several layers: libvirt provides the API and daemon for VM management, QEMU handles hardware emulation, and tools like virsh (command-line) or virt-manager (GUI) provide the interface for administrators. For production environments, consider higher-level management platforms like Proxmox VE, oVirt, or OpenStack to simplify large-scale VM administration.

Creating virtual machines can be done through virt-manager's GUI or with command-line tools like virt-install. For example: virt-install --name vm1 --memory 2048 --vcpus 2 --disk size=20 --cdrom ubuntu.iso creates a basic VM with defined resources. For automated deployments, combine virt-install with cloud-init and templates to provision VMs programmatically.

Storage management is critical for performance. KVM supports various storage backends including files (qcow2, raw), logical volumes (LVM), and storage pools (managed through libvirt). The qcow2 format offers features like snapshots and thin provisioning but with some performance overhead; raw images provide better performance for I/O-intensive workloads. For production, consider dedicated storage solutions with virtio drivers for optimal performance.

Networking can be configured in multiple ways: the default NAT network (managed by libvirt), bridged networking for direct network access, or more advanced configurations like Open vSwitch integration. For complex environments, implement SDN (Software-Defined Networking) solutions to manage network connectivity and security between VMs.

Performance optimization involves tuning both host and guest settings: enable hugepages for memory-intensive workloads, use virtio drivers for disks and network interfaces, consider CPU pinning for latency-sensitive applications, and implement NUMA awareness for multi-socket systems. Regular maintenance should include monitoring VM resource usage, managing snapshots, planning capacity, and implementing backup strategies specific to virtualized environments.

</details>

<details>
<summary><b>How do you implement and configure Linux kernel hardening?</b></summary>

Kernel hardening in Linux involves implementing various security measures to protect against exploits, vulnerabilities, and unauthorized access at the kernel level. A comprehensive approach includes modifying kernel parameters, implementing security modules, restricting access to kernel interfaces, and maintaining regular updates.

Start with kernel parameter hardening by configuring /etc/sysctl.conf with security-focused settings: enable address space layout randomization with kernel.randomize_va_space=2, protect against symlink attacks with fs.protected_symlinks=1 and fs.protected_hardlinks=1, disable uncommon protocols with kernel.modules_disabled=1 to prevent runtime module loading, and enable exec-shield protection with kernel.exec-shield=1. Restrict kernel pointer exposure with kernel.kptr_restrict=2 and dmesg access with kernel.dmesg_restrict=1 to prevent information leakage.

Implement Mandatory Access Control through SELinux or AppArmor to enforce security policies beyond traditional discretionary access controls. Enable and configure these systems in enforcing mode for production environments after thorough testing. For SELinux, use the targeted policy for most environments, while AppArmor profiles should be carefully developed for each critical application.

Mitigate kernel exploits by configuring additional security features: enable seccomp filtering to restrict system calls available to processes, configure kernel module signing to prevent loading of unauthorized modules, implement user namespaces carefully (or disable if not needed), and restrict access to /proc and /sys by mounting with restrictive options.

Regularly update and maintain the kernel with security patches, ideally through your distribution's security update channel. Consider using automated tools like Lynis or OpenSCAP to audit kernel security settings and identify potential vulnerabilities or misconfigurations. For highly sensitive environments, compile a custom kernel with only needed features and drivers, reducing the attack surface.

Monitor kernel security events through auditd and configure alerts for potential security violations. Implement file integrity monitoring to detect unauthorized changes to critical kernel files and modules. Document all kernel hardening measures applied to systems and maintain a regular review process to ensure configurations remain appropriate as security threats evolve.

</details>

<details>
<summary><b>How do you troubleshoot Linux boot problems?</b></summary>

Troubleshooting Linux boot problems requires a systematic approach to identify issues in the multi-stage boot process, from firmware initialization through kernel loading to service startup. The methodology varies depending on where in the boot sequence the failure occurs.

For systems that won't boot at all, start by checking hardware: verify power connections, RAM seating, and listen for beep codes or check firmware error messages. If hardware checks out, examine the bootloader stage by accessing the GRUB menu (hold Shift during boot for most distributions). From GRUB, modify kernel parameters by pressing 'e', adding options like nomodeset for graphics issues or single for single-user mode. For emergency access, boot from a live USB and chroot into the installed system.

When the system boots partially but fails during kernel initialization, analyze kernel logs with journalctl -b -1 (from a rescue environment) to identify failing drivers or hardware. Look for kernel panic messages or hardware initialization failures. For initramfs issues, regenerate it with update-initramfs -u or the distribution-equivalent command after mounting the system's partitions from a rescue environment.

For failures during the systemd initialization phase, examine systemd logs with journalctl -xb from emergency mode or a chroot environment. Use systemctl list-units --failed to identify specific failed services. Common culprits include filesystem mounting problems (check /etc/fstab for errors), network configuration issues, or incorrect service dependencies.

Filesystem corruption often causes boot failures and requires running fsck on the relevant partitions from a rescue environment. For storage device problems, check drive health with SMART tools and examine /var/log/syslog or dmesg output for I/O errors. Boot performance issues can be analyzed with systemd-analyze and systemd-analyze blame to identify slow-starting services.

When making changes to fix boot issues, always create backups of configuration files before modification, document all changes made, and consider the implications for system security and stability. After resolving the issue, review logs to understand the root cause and implement preventive measures to avoid recurrence.

</details>

<details>
<summary><b>How do you manage Linux kernel modules?</b></summary>

Linux kernel modules are loadable code components that extend the kernel's functionality without requiring a full kernel recompilation or system reboot. Managing these modules effectively involves loading, unloading, configuring, blacklisting, and securing them according to system requirements.

The primary tools for module management include lsmod (lists currently loaded modules), modinfo (displays detailed information about a module), modprobe (intelligently loads modules with dependencies), insmod (loads a single module without resolving dependencies), and rmmod (removes modules). For most operations, modprobe is preferred due to its dependency handling and configuration awareness.

Loading modules can be done temporarily with modprobe module_name or permanently by adding the module name to /etc/modules or creating a file in /etc/modules-load.d/. Module parameters, which customize behavior, can be passed at load time (modprobe module_name parameter=value) or set permanently in configuration files under /etc/modprobe.d/ with lines like options module_name parameter=value.

Blacklisting prevents modules from loading automatically, useful for problematic hardware drivers or security purposes. Create a file in /etc/modprobe.d/ (like blacklist.conf) containing lines such as blacklist module_name. For more complete prevention, use install module_name /bin/false which prevents even explicit loading attempts.

For security, consider signing modules if your kernel enforces module signing, or completely disable module loading after boot with kernel.modules_disabled=1 in sysctl for highly secure environments. Review loaded modules regularly for unexpected entries, especially on security-sensitive systems.

Debugging module issues involves checking kernel logs with dmesg immediately after loading/unloading, examining module dependencies with modprobe --show-depends module_name, and verifying module parameters with systool -v -m module_name. For performance optimization, unload unnecessary modules to reduce memory usage and potential attack surface, particularly on resource-constrained or security-focused systems.

</details>


<details>
<summary><b>How do you configure and manage syslog in Linux?</b></summary>

Syslog is the standard logging system in Linux, responsible for collecting, filtering, and storing system and application messages. Effective management involves proper configuration of log sources, destinations, filters, and rotation policies to ensure comprehensive logging while maintaining system performance and storage efficiency.

Configuration starts with setting up the syslog daemon, typically rsyslog (/etc/rsyslog.conf) or syslog-ng (/etc/syslog-ng/syslog-ng.conf). The basic configuration syntax includes selectors (facility.priority) and actions (destinations). For example, kern.warning /var/log/kern.log routes kernel warnings to a specific log file. Create modular configurations by placing additional rules in the /etc/rsyslog.d/ directory to keep the main configuration clean and maintainable.

For structured logging, configure templates in rsyslog to format log messages consistently, potentially in JSON or other machine-parsable formats. This facilitates integration with log analysis tools. Configure remote logging by adding network destinations (@192.168.1.100:514 for UDP or @@192.168.1.100:514 for TCP) to send logs to a central server, providing backup and centralized analysis capabilities.

Security considerations include configuring TLS encryption for remote logging, implementing rate limiting to prevent log flooding attacks, setting appropriate file permissions on log files, and configuring input filters to validate message sources. For high-security environments, consider implementing log signing to detect tampering.

Log rotation is essential for managing disk space and maintaining system performance. Configure logrotate through /etc/logrotate.d/ to compress, rotate, and eventually remove old logs based on size or time thresholds. Include appropriate postrotate scripts to signal the syslog daemon to reopen log files after rotation.

Performance optimization involves balancing comprehensive logging with system impact. Use in-memory queues for high-volume logging, configure appropriate buffer sizes, and consider asynchronous processing for non-critical logs. For distributed systems, implement log aggregation with tools like Logstash, Fluentd, or rsyslog's own queuing features to ensure log delivery even during network interruptions.

</details>


<details>
<summary><b>How do you implement and manage High Availability clustering in Linux?</b></summary>

High Availability (HA) clustering in Linux provides continuous service operation by eliminating single points of failure. Implementation involves combining specialized software, configuration, monitoring, and failover mechanisms to ensure services remain available despite component failures.

The foundation of most Linux HA clusters is a cluster resource manager like Pacemaker, working alongside a messaging layer like Corosync that handles node communication and membership. Installation begins with setting up these components (apt install pacemaker corosync or equivalent) and configuring the cluster communication in /etc/corosync/corosync.conf, defining node addresses, transport mechanism (typically UDP multicast or unicast), and authentication.

After establishing the cluster communication layer, configure Pacemaker to manage resources. Define resources for services (Apache, MySQL, etc.), virtual IP addresses, filesystems, and any other components that should be highly available. Use resource agents (standardized scripts that start, stop, and monitor services) to integrate applications with the cluster. Configure constraints to define resource placement policies, ensuring co-location of related resources and proper start/stop ordering.

Fencing is critical in HA clusters to prevent split-brain conditions. Configure STONITH (Shoot The Other Node In The Head) devices or mechanisms that can forcibly power off failed nodes. Options include IPMI controllers, PDUs (Power Distribution Units), hypervisor APIs, or dedicated fencing hardware. Test fencing thoroughly, as improper configuration can lead to both nodes being fenced during communication failures.

For storage in HA environments, implement shared storage solutions like SAN/NAS with cluster filesystems (GFS2, OCFS2) or replicated block devices (DRBD). Configure appropriate mount options and filesystem checks to prevent corruption during failover. For database servers, consider database-specific replication mechanisms (like MySQL Galera Cluster or PostgreSQL streaming replication) that provide better data consistency guarantees than generic solutions.

Ongoing management involves monitoring cluster health through tools like pcs status or crm_mon, configuring notifications for cluster events, regular testing of failover scenarios, and maintaining thorough documentation of the cluster configuration and recovery procedures. Implement backup strategies that account for the distributed nature of cluster data, and establish maintenance procedures that allow for patching and updates without service disruption.

</details>

<details>
<summary><b>How do you implement and manage Linux Virtual Server (LVS) for load balancing?</b></summary>

Linux Virtual Server (LVS) is a highly scalable and high-performance load balancing solution built into the Linux kernel through the IPVS (IP Virtual Server) module. Implementation involves configuring a load balancer (director) that distributes client requests across multiple real servers while maintaining session persistence and high availability.

Setup begins with installing the ipvsadm package (apt install ipvsadm or yum install ipvsadm) on the director node. Configure the virtual IP address (VIP) that clients will connect to, ensuring it's properly bound to a network interface or configured as a floating IP with tools like keepalived for high availability. Use ipvsadm to define virtual services and the associated real servers, specifying the load balancing algorithm and connection forwarding method.

LVS supports three packet-forwarding methods, each with different network requirements: Direct Routing (DR), where real servers process and respond to packets directly; Network Address Translation (NAT), where the director performs address translation for incoming and outgoing traffic; and IP Tunneling (IPIP), where the director encapsulates packets and forwards them to geographically distributed real servers. DR mode offers the best performance but requires additional network configuration on real servers to handle the VIP correctly.

Several load balancing algorithms are available to distribute traffic optimally: round-robin for equal distribution, weighted round-robin for servers with different capacities, least-connection for balancing based on current connections, weighted least-connection for heterogeneous servers, and locality-based least-connection for optimizing cache hit ratios. Choose the algorithm that best matches your application characteristics and server capabilities.

For high availability of the director itself, implement Keepalived alongside LVS. Keepalived provides VRRP (Virtual Router Redundancy Protocol) functionality to manage floating IPs, health checking of real servers, and automatic failover between director nodes. Configure synchronization of connection tables between redundant directors to maintain session persistence during failover.

Maintenance and monitoring involve regularly checking the status of virtual services and real servers using ipvsadm -L -n, configuring comprehensive health checks to detect and remove failed servers from the pool, implementing proper logging for troubleshooting, and developing procedures for adding or removing servers without disrupting active connections. For complex environments, consider implementing a management layer above the basic LVS functionality to simplify configuration and provide better visibility into the load balancing system.

</details>

---

## 🖥️ Operating Systems

### Operating System - Self Assessment

<details>
<summary><b>What is an operating system?</b></summary>

From the book "Operating Systems: Three Easy Pieces":

"responsible for making it easy to run programs (even allowing you to seemingly run many at the same time), allowing programs to share memory, enabling programs to interact with devices, and other fun stuff like that".

</details>

### Operating System - Process

<details>
<summary><b>Can you explain what is a process?</b></summary>

A process is a running program. A program is one or more instructions and the program (or process) is executed by the operating system.

</details>

<details>
<summary><b>If you had to design an API for processes in an operating system, what would this API look like?</b></summary>

It would support the following:

* Create - allow to create new processes
* Delete - allow to remove/destroy processes
* State - allow to check the state of the process, whether it's running, stopped, waiting, etc.
* Stop - allow to stop a running process

</details>

<details>
<summary><b>How a process is created?</b></summary>

* The OS is reading program's code and any additional relevant data
* Program's code is loaded into the memory or more specifically, into the address space of the process.
* Memory is allocated for program's stack (aka run-time stack). The stack also initialized by the OS with data like argv, argc and parameters to main()
* Memory is allocated for program's heap which is required for dynamically allocated data like the data structures linked lists and hash tables
* I/O initialization tasks are performed, like in Unix/Linux based systems, where each process has 3 file descriptors (input, output and error)
* OS is running the program, starting from main()

</details>

<details>
<summary><b>True or False? The loading of the program into the memory is done eagerly (all at once)?</b></summary>

False. It was true in the past but today's operating systems perform lazy loading, which means only the relevant pieces required for the process to run are loaded first.

</details>

<details>
<summary><b>What are different states of a process?</b></summary>

* Running - it's executing instructions
* Ready - it's ready to run, but for different reasons it's on hold
* Blocked - it's waiting for some operation to complete, for example I/O disk request

</details>

<details>
<summary><b>What are some reasons for a process to become blocked?</b></summary>

- I/O operations (e.g. Reading from a disk)
  - Waiting for a packet from a network

</details>

<details>
<summary><b>What is Inter Process Communication (IPC)?</b></summary>

Inter-process communication (IPC) refers to the mechanisms provided by an operating system that allow processes to manage shared data.

</details>

<details>
<summary><b>What is "time sharing"?</b></summary>

Even when using a system with one physical CPU, it's possible to allow multiple users to work on it and run programs. This is possible with time sharing, where computing resources are shared in a way it seems to the user, the system has multiple CPUs, but in fact it's simply one CPU shared by applying multiprogramming and multi-tasking.

</details>

<details>
<summary><b>What is "space sharing"?</b></summary>

Somewhat the opposite of time sharing. While in time sharing a resource is used for a while by one entity and then the same resource can be used by another resource, in space sharing the space is shared by multiple entities but in a way where it's not being transferred between them.<br>
It's used by one entity, until this entity decides to get rid of it. Take for example storage. In storage, a file is yours, until you decide to delete it.

</details>

<details>
<summary><b>What component determines which process runs at a given moment in time?</b></summary>

CPU scheduler

</details>

### Operating System - Memory

<details>
<summary><b>What is "virtual memory" and what purpose does serve?</b></summary>

Virtual memory combines your computer's RAM with temporary space on your hard disk. When RAM runs low, virtual memory helps to move data from RAM to a space called a paging file. Moving data to paging file can free up the RAM, so your computer can complete its work. In general, the more RAM your computer has, the faster the programs run.
https://www.minitool.com/lib/virtual-memory.html

</details>

<details>
<summary><b>What is demand paging?</b></summary>

Demand paging is a memory management technique where pages are loaded into physical memory only when accessed by a process. It optimizes memory usage by loading pages on demand, reducing startup latency and space overhead. However, it introduces some latency when accessing pages for the first time. Overall, it’s a cost-effective approach for managing memory resources in operating systems.

</details>

<details>
<summary><b>What is copy-on-write?</b></summary>

Copy-on-write (COW) is a resource management concept, with the goal to reduce unnecessary copying of information. It is a concept, which is implemented for instance within the POSIX fork syscall, which creates a duplicate process of the calling process.

The idea:
1. If resources are shared between 2 or more entities (for example shared memory segments between 2 processes), the resources don't need to be copied for every entity, but rather every entity has a READ operation access permission on the shared resource. (the shared segments are marked as read-only) 
(Think of every entity having a pointer to the location of the shared resource, which can be dereferenced to read its value)
2. If one entity would perform a WRITE operation on a shared resource, a problem would arise, since the resource also would be permanently changed for ALL other entities sharing it.
(Think of a process modifying some variables on the stack, or allocatingy some data dynamically on the heap, these changes to the shared resource would also apply for ALL other processes, this is definitely an undesirable behaviour)
3. As a solution only, if a WRITE operation is about to be performed on a shared resource, this resource gets COPIED first and then the changes are applied.

</details>

<details>
<summary><b>What is a kernel, and what does it do?</b></summary>

The kernel is part of the operating system and is responsible for tasks like:

  * Allocating memory
  * Schedule processes
  * Control CPU

</details>

<details>
<summary><b>True or False? Some pieces of the code in the kernel are loaded into protected areas of the memory so applications can't overwrite them?</b></summary>

True

</details>

<details>
<summary><b>What is cache? What is buffer?</b></summary>

Cache: Cache is usually used when processes are reading and writing to the disk to make the process faster, by making similar data used by different programs easily accessible.
Buffer: Reserved place in RAM, which is used to hold data for temporary purposes.

</details>

---

## 🔮 Virtualization

<details>
<summary><b>What is Virtualization?</b></summary>

Virtualization uses software to create an abstraction layer over computer hardware, that allows the hardware elements of a single computer - processors, memory, storage and more - to be divided into multiple virtual computers, commonly called virtual machines (VMs).

</details>

<details>
<summary><b>What is a hypervisor?</b></summary>

Red Hat: "A hypervisor is software that creates and runs virtual machines (VMs). A hypervisor, sometimes called a virtual machine monitor (VMM), isolates the hypervisor operating system and resources from the virtual machines and enables the creation and management of those VMs."

Read more [here](https://www.redhat.com/en/topics/virtualization/what-is-a-hypervisor)

</details>

<details>
<summary><b>What types of hypervisors are there?</b></summary>

Hosted hypervisors and bare-metal hypervisors.

</details>

<details>
<summary><b>What are the advantages and disadvantages of bare-metal hypervisor over a hosted hypervisor?</b></summary>

Due to having its own drivers and a direct access to hardware components, a baremetal hypervisor will often have better performances along with stability and scalability.

On the other hand, there will probably be some limitation regarding loading (any) drivers so a hosted hypervisor will usually benefit from having a better hardware compatibility.

</details>

<details>
<summary><b>What types of virtualization are there?</b></summary>

Operating system virtualization
Network functions virtualization
Desktop virtualization

</details>

<details>
<summary><b>Is containerization a type of Virtualization?</b></summary>

Yes, it's a operating-system-level virtualization, where the kernel is shared and allows to use multiple isolated user-spaces instances.

</details>

<details>
<summary><b>How the introduction of virtual machines changed the industry and the way applications were deployed?</b></summary>

The introduction of virtual machines allowed companies to deploy multiple business applications on the same hardware, while each application is separated from each other in secured way, where each is running on its own separate operating system.

</details>

<details>
<summary><b>What are containers, and how do they relate to DevOps?</b></summary>

*(No answer provided in source)*

</details>

<details>
<summary><b>Explain the importance of container orchestration tools like Kubernetes in DevOps</b></summary>

*(No answer provided in source)*

</details>

<details>
<summary><b>How do you ensure the security of Docker containers in a DevOps pipeline?</b></summary>

*(No answer provided in source)*

</details>

### Virtual Machines

<details>
<summary><b>Do we need virtual machines in the age of containers? Are they still relevant?</b></summary>

Yes, virtual machines are still relevant even in the age of containers. While containers provide a lightweight and portable alternative to virtual machines, they do have certain limitations. Virtual machines still matter because they offer isolation and security, can run different operating systems, and are good for legacy apps. Containers limitations for example are sharing the host kernel.

</details>

---

## 🌐 Networking

### 🟢 Beginner

<details>
<summary><b>What is a network?</b></summary>

A network is a group of interconnected devices that communicate to share resources and information. It can be wired or wireless.

</details>

<details>
<summary><b>What is the difference between IPv4 and IPv6?</b></summary>

IPv4: 32-bit addressing, supports 4.3 billion addresses.
IPv6: 128-bit addressing, supports an enormous number of addresses, improving scalability and security.

</details>

<details>
<summary><b>What are private and public IP addresses?</b></summary>

Private IPs: Used within local networks (e.g., 192.168.x.x).
Public IPs: Used on the internet and assigned by ISPs.

</details>

<details>
<summary><b>What is a subnet mask?</b></summary>

A subnet mask divides an IP address into network and host portions, determining which part identifies the network and which part identifies the device.

</details>

<details>
<summary><b>What is DNS, and why is it important?</b></summary>

The Domain Name System (DNS) translates domain names (e.g., google.com) into IP addresses, making it easier to access websites.

</details>

<details>
<summary><b>What is SSH, and why is it used?</b></summary>

SSH (Secure Shell) is a protocol used for secure remote access to servers using encrypted communication.

</details>

<details>
<summary><b>What is port forwarding?</b></summary>

Port forwarding redirects network traffic from one port to another, often used to expose internal services externally.

</details>

### 🟡 Intermediate

<details>
<summary><b>What is OSI Model and its layers?</b></summary>

The OSI model has 7 layers: Physical, Data Link, Network, Transport, Session, Presentation, Application.

</details>

<details>
<summary><b>What is BGP (Border Gateway Protocol)?</b></summary>

BGP is a routing protocol used for exchanging routing information between networks on the internet.

</details>

<details>
<summary><b>What is network segmentation?</b></summary>

It is dividing a network into smaller parts to improve security and performance.

</details>

### 🔴 Advanced

<details>
<summary><b>What is an ephemeral port, and how is it used?</b></summary>

Ephemeral ports (e.g., 49152-65535) are temporary ports used by client applications for outbound connections.

</details>

### 📌 Additional Questions

<details>
<summary><b>What is an IP address?</b></summary>

An Internet Protocol address (IP address) is a numerical label assigned to each device connected to a computer network that uses the Internet Protocol for communication.An IP address serves two main functions: host or network interface identification and location addressing.

</details>

<details>
<summary><b>What is the difference between TCP and UDP?</b></summary>

TCP establishes a connection between the client and the server to guarantee the order of the packages, on the other hand, UDP does not establish a connection between the client and server and doesn't handle package orders. This makes UDP more lightweight than TCP and a perfect candidate for services like streaming.

[Penguintutor.com](http://www.penguintutor.com/linux/basic-network-reference) provides a good explanation.

</details>

<details>
<summary><b>In general, what do you need in order to communicate?</b></summary>

- A common language (for the two ends to understand)
  - A way to address who you want to communicate with
  - A Connection (so the content of the communication can reach the recipients)

</details>

<details>
<summary><b>What is TCP/IP?</b></summary>

A set of protocols that define how two or more devices can communicate with each other.

To learn more about TCP/IP, read [here](http://www.penguintutor.com/linux/basic-network-reference)

</details>

<details>
<summary><b>What is Ethernet?</b></summary>

Ethernet simply refers to the most common type of Local Area Network (LAN) used today. A LAN—in contrast to a WAN (Wide Area Network), which spans a larger geographical area—is a connected network of computers in a small area, like your office, college campus, or even home.

</details>

<details>
<summary><b>What is a MAC address? What is it used for?</b></summary>

A MAC address is a unique identification number or code used to identify individual devices on the network.

Packets that are sent on the ethernet are always coming from a MAC address and sent to a MAC address. If a network adapter is receiving a packet, it is comparing the packet’s destination MAC address to the adapter’s own MAC address.

</details>

<details>
<summary><b>When is this MAC address used?: ff:ff:ff:ff:ff:ff?</b></summary>

When a device sends a packet to the broadcast MAC address (FF:FF:FF:FF:FF:FF​), it is delivered to all stations on the local network. Ethernet broadcasts are used to resolve IP addresses to MAC addresses (by ARP) at the data link layer.

</details>

<details>
<summary><b>Explain the subnet mask and give an example</b></summary>

A Subnet mask is a 32-bit number that masks an IP address and divides the IP addresses into network addresses and host addresses. Subnet Mask is made by setting network bits to all "1"s and setting host bits to all "0"s. Within a given network, out of the total usable host addresses, two are always reserved for specific purposes and cannot be allocated to any host. These are the first address, which is reserved as a network address (a.k.a network ID), and the last address used for network broadcast.

[Example](https://github.com/philemonnwanne/projects/tree/main/exercises/exe-09)

</details>

<details>
<summary><b>What is a private IP address? In which scenarios/system designs, one should use it?</b></summary>

Private IP addresses are assigned to the hosts in the same network to communicate with one another. As the name "private" suggests, the devices having the private IP addresses assigned can't be reached by the devices from any external network. For example, if I am living in a hostel and I want my hostel mates to join the game server I have hosted, I will ask them to join via my server's private IP address, since the network is local to the hostel.

</details>

<details>
<summary><b>What is a public IP address? In which scenarios/system designs, one should use it?</b></summary>

A public IP address is a public-facing IP address. In the event that you were hosting a game server that you want your friends to join, you will give your friends your public IP address to allow their computers to identify and locate your network and server in order for the connection to take place. One time that you would not need to use a public-facing IP address is in the event that you were playing with friends who were connected to the same network as you, in that case, you would use a private IP address. In order for someone to be able to connect to your server that is located internally, you will have to set up a port forward to tell your router to allow traffic from the public domain into your network and vice versa.

</details>

<details>
<summary><b>Explain the OSI model. What layers there are? What each layer is responsible for?</b></summary>

- Application: user end (HTTP is here)
- Presentation: establishes context between application-layer entities (Encryption is here)
- Session: establishes, manages, and terminates the connections
- Transport: transfers variable-length data sequences from a source to a destination host (TCP & UDP are here)
- Network: transfers datagrams from one network to another (IP is here)
- Data link: provides a link between two directly connected nodes (MAC is here)
- Physical: the electrical and physical spec of the data connection (Bits are here)

You can read more about the OSI model in [penguintutor.com](http://www.penguintutor.com/linux/basic-network-reference)

</details>

<details>
<summary><b>For each of the following determines to which OSI layer it belongs: * Error correction * Packets routing * Cables and electrical signals * MAC address * IP address * Terminate connections * 3 way handshake</b></summary>

* Error correction - Data link
  * Packets routing - Network
  * Cables and electrical signals - Physical
  * MAC address - Data link
  * IP address - Network
  * Terminate connections - Session
  * 3-way handshake - Transport

</details>

<details>
<summary><b>What delivery schemes are you familiar with?</b></summary>

Unicast: One-to-one communication where there is one sender and one receiver.

Broadcast: Sending a message to everyone in the network. The address ff:ff:ff:ff:ff:ff is used for broadcasting.
           Two common protocols which use broadcast are ARP and DHCP.

Multicast: Sending a message to a group of subscribers. It can be one-to-many or many-to-many.

</details>

<details>
<summary><b>Describe the following network devices and the difference between them: * router * switch * hub</b></summary>

A router, switch, and hub are all network devices used to connect devices in a local area network (LAN). However, each device operates differently and has its specific use cases. Here is a brief description of each device and the differences between them:

1. Router: a network device that connects multiple network segments together. It operates at the network layer (Layer 3) of the OSI model and uses routing protocols to direct data between networks. Routers use IP addresses to identify devices and route data packets to the correct destination.
2. Switch: a network device that connects multiple devices on a LAN. It operates at the data link layer (Layer 2) of the OSI model and uses MAC addresses to identify devices and direct data packets to the correct destination. Switches allow devices on the same network to communicate with each other more efficiently and can prevent data collisions that can occur when multiple devices send data simultaneously.
3. Hub: a network device that connects multiple devices through a single cable and is used to connect multiple devices without segmenting a network. However, unlike a switch, it operates at the physical layer (Layer 1) of the OSI model and simply broadcasts data packets to all devices connected to it, regardless of whether the device is the intended recipient or not. This means that data collisions can occur, and the network's efficiency can suffer as a result. Hubs are generally not used in modern network setups, as switches are more efficient and provide better network performance.

</details>

<details>
<summary><b>What is a "Collision Domain"?</b></summary>

A collision domain is a network segment in which devices can potentially interfere with each other by attempting to transmit data at the same time. When two devices transmit data at the same time, it can cause a collision, resulting in lost or corrupted data. In a collision domain, all devices share the same bandwidth, and any device can potentially interfere with the transmission of data by other devices.

</details>

<details>
<summary><b>What is a "Broadcast Domain"?</b></summary>

A broadcast domain is a network segment in which all devices can communicate with each other by sending broadcast messages. A broadcast message is a message that is sent to all devices in a network rather than a specific device. In a broadcast domain, all devices can receive and process broadcast messages, regardless of whether the message was intended for them or not.

</details>

<details>
<summary><b>three computers connected to a switch. How many collision domains are there? How many broadcast domains?</b></summary>

Three collision domains and one broadcast domain

</details>

<details>
<summary><b>How does a router work?</b></summary>

A router is a physical or virtual appliance that passes information between two or more packet-switched computer networks. A router inspects a given data packet's destination Internet Protocol address (IP address), calculates the best way for it to reach its destination, and then forwards it accordingly.

</details>

<details>
<summary><b>What is NAT?</b></summary>

Network Address Translation (NAT) is a process in which one or more local IP addresses are translated into one or more Global IP address and vice versa in order to provide Internet access to the local hosts.

</details>

<details>
<summary><b>What is TCP? How does it work? What is the 3-way handshake?</b></summary>

TCP 3-way handshake or three-way handshake is a process that is used in a TCP/IP network to make a connection between server and client.

A three-way handshake is primarily used to create a TCP socket connection. It works when:

- A client node sends an SYN data packet over an IP network to a server on the same or an external network. The objective of this packet is to ask/infer if the server is open for new connections.
- The target server must have open ports that can accept and initiate new connections. When the server receives the SYN packet from the client node, it responds and returns a confirmation receipt – the ACK packet or SYN/ACK packet.
- The client node receives the SYN/ACK from the server and responds with an ACK packet.

</details>

<details>
<summary><b>What is round-trip delay or round-trip time?</b></summary>

From [wikipedia](https://en.wikipedia.org/wiki/Round-trip_delay): "the length of time it takes for a signal to be sent plus the length of time it takes for an acknowledgment of that signal to be received"

Bonus question: what is the RTT of LAN?

</details>

<details>
<summary><b>How does an SSL handshake work?</b></summary>

SSL handshake is a process that establishes a secure connection between a client and a server.

1. The client sends a Client Hello message to the server, which includes the client's version of the SSL/TLS protocol, a list of the cryptographic algorithms supported by the client, and a random value.
2. The server responds with a Server Hello message, which includes the server's version of the SSL/TLS protocol, a random value, and a session ID.
3. The server sends a Certificate message, which contains the server's certificate.
4. The server sends a Server Hello Done message, which indicates that the server is done sending messages for the Server Hello phase.
5. The client sends a Client Key Exchange message, which contains the client's public key.
6. The client sends a Change Cipher Spec message, which notifies the server that the client is about to send a message encrypted with the new cipher spec.
7. The client sends an Encrypted Handshake Message, which contains the pre-master secret encrypted with the server's public key.
8. The server sends a Change Cipher Spec message, which notifies the client that the server is about to send a message encrypted with the new cipher spec.
9. The server sends an Encrypted Handshake Message, which contains the pre-master secret encrypted with the client's public key.
10. The client and server can now exchange application data.

</details>

<details>
<summary><b>What TCP/IP protocols are you familiar with?</b></summary>

*(No answer provided in source)*

</details>

<details>
<summary><b>Explain the "default gateway"</b></summary>

A default gateway serves as an access point or IP router that a networked computer uses to send information to a computer in another network or the internet.

</details>

<details>
<summary><b>What is ARP? How does it work?</b></summary>

ARP stands for Address Resolution Protocol. When you try to ping an IP address on your local network, say 192.168.1.1, your system has to turn the IP address 192.168.1.1 into a MAC address. This involves using ARP to resolve the address, hence its name.

Systems keep an ARP look-up table where they store information about what IP addresses are associated with what MAC addresses. When trying to send a packet to an IP address, the system will first consult this table to see if it already knows the MAC address. If there is a value cached, ARP is not used.

</details>

<details>
<summary><b>What is TTL? What does it help to prevent?</b></summary>

- TTL (Time to Live) is a value in an IP (Internet Protocol) packet that determines how many hops or routers a packet can travel before it is discarded. Each time a packet is forwarded by a router, the TTL value is decreased by one. When the TTL value reaches zero, the packet is dropped, and an ICMP (Internet Control Message Protocol) message is sent back to the sender indicating that the packet has expired.
- TTL is used to prevent packets from circulating indefinitely in the network, which can cause congestion and degrade network performance.
- It also helps to prevent packets from being trapped in routing loops, where packets continuously travel between the same set of routers without ever reaching their destination.
- In addition, TTL can be used to help detect and prevent IP spoofing attacks, where an attacker attempts to impersonate another device on the network by using a false or fake IP address. By limiting the number of hops that a packet can travel, TTL can help prevent packets from being routed to destinations that are not legitimate.

</details>

<details>
<summary><b>What is DHCP? How does it work?</b></summary>

It stands for Dynamic Host Configuration Protocol and allocates IP addresses, subnet masks, and gateways to hosts. This is how it works:

* A host upon entering a network broadcasts a message in search of a DHCP server (DHCP DISCOVER)
* An offer message is sent back by the DHCP server as a packet containing lease time, subnet mask, IP addresses, etc (DHCP OFFER)
* Depending on which offer is accepted, the client sends back a reply broadcast letting all DHCP servers know (DHCP REQUEST)
* The server sends an acknowledgment (DHCP ACK)

Read more [here](https://linuxjourney.com/lesson/dhcp-overview)

</details>

<details>
<summary><b>Can you have two DHCP servers on the same network? How does it work?</b></summary>

It is possible to have two DHCP servers on the same network, however, it is not recommended, and it is important to configure them carefully to prevent conflicts and configuration problems.
- When two DHCP servers are configured on the same network, there is a risk that both servers will assign IP addresses and other network configuration settings to the same device, which can cause conflicts and connectivity issues. Additionally, if the DHCP servers are configured with different network settings or options, devices on the network may receive conflicting or inconsistent configuration settings.
- However, in some cases, it may be necessary to have two DHCP servers on the same network, such as in large networks where one DHCP server may not be able to handle all the requests. In such cases, DHCP servers can be configured to serve different IP address ranges or different subnets, so they do not interfere with each other.

</details>

<details>
<summary><b>What is a socket? Where can you see the list of sockets in your system?</b></summary>

- A socket is a software endpoint that enables two-way communication between processes over a network. Sockets provide a standardized interface for network communication, allowing applications to send and receive data across a network. To view the list of open sockets on a Linux system: 
***netstat -an***
- This command displays a list of all open sockets, along with their protocol, local address, foreign address, and state.

</details>

<details>
<summary><b>What is IPv6? Why should we consider using it if we have IPv4?</b></summary>

- IPv6 (Internet Protocol version 6) is the latest version of the Internet Protocol (IP), which is used to identify and communicate with devices on a network. IPv6 addresses are 128-bit addresses and are expressed in hexadecimal notation, such as 2001:0db8:85a3:0000:0000:8a2e:0370:7334.

There are several reasons why we should consider using IPv6 over IPv4:

1. Address space: IPv4 has a limited address space, which has been exhausted in many parts of the world. IPv6 provides a much larger address space, allowing for trillions of unique IP addresses.
2. Security: IPv6 includes built-in support for IPsec, which provides end-to-end encryption and authentication for network traffic.
3. Performance: IPv6 includes features that can help to improve network performance, such as multicast routing, which allows a single packet to be sent to multiple destinations simultaneously.
4. Simplified network configuration: IPv6 includes features that can simplify network configuration, such as stateless autoconfiguration, which allows devices to automatically configure their own IPv6 addresses without the need for a DHCP server.
5. Better mobility support: IPv6 includes features that can improve mobility support, such as Mobile IPv6, which allows devices to maintain their IPv6 addresses as they move between different networks.

</details>

<details>
<summary><b>What is VLAN?</b></summary>

- A VLAN (Virtual Local Area Network) is a logical network that groups together a set of devices on a physical network, regardless of their physical location. VLANs are created by configuring network switches to assign a specific VLAN ID to frames sent by devices connected to a specific port or group of ports on the switch.

</details>

<details>
<summary><b>What is MTU?</b></summary>

MTU stands for Maximum Transmission Unit. It's the size of the largest PDU (protocol Data Unit) that can be sent in a single transaction.

</details>

<details>
<summary><b>What happens if you send a packet that is bigger than the MTU?</b></summary>

With the IPv4 protocol, the router can fragment the PDU and then send all the fragmented PDU through the transaction.
	
With IPv6 protocol, it issues an error to the user's computer.

</details>

<details>
<summary><b>True or False? Ping is using UDP because it doesn't care about reliable connection?</b></summary>

False. Ping is actually using ICMP (Internet Control Message Protocol) which is a network protocol used to send diagnostic messages and control messages related to network communication.

</details>

<details>
<summary><b>What is ICMP? What is it used for?</b></summary>

- ICMP stands for Internet Control Message Protocol. It is a protocol used for diagnostic and control purposes in IP networks. It is a part of the Internet Protocol suite, operating at the network layer.

ICMP messages are used for a variety of purposes, including:
1. Error reporting: ICMP messages are used to report errors that occur in the network, such as a packet that could not be delivered to its destination.
2. Ping: ICMP is used to send ping messages, which are used to test whether a host or network is reachable and to measure the round-trip time for packets.
3. Path MTU discovery: ICMP is used to discover the Maximum Transmission Unit (MTU) of a path, which is the largest packet size that can be transmitted without fragmentation.
4. Traceroute: ICMP is used by the traceroute utility to trace the path that packets take through the network.
5. Router discovery: ICMP is used to discover the routers in a network.

</details>

<details>
<summary><b>Which port number is used in each of the following protocols?: * SSH * SMTP * HTTP * DNS * HTTPS * FTP * SFTP?</b></summary>

* SSH - 22
  * SMTP - 25
  * HTTP - 80
  * DNS - 53
  * HTTPS - 443
  * FTP - 21
  * SFTP - 22

</details>

<details>
<summary><b>Which factors affect network performance?</b></summary>

Several factors can affect network performance, including:

1. Bandwidth: The available bandwidth of a network connection can significantly impact its performance. Networks with limited bandwidth can experience slow data transfer rates, high latency, and poor responsiveness.
2. Latency: Latency refers to the delay that occurs when data is transmitted from one point in a network to another. High latency can result in slow network performance, especially for real-time applications like video conferencing and online gaming.
3. Network congestion: When too many devices are using a network at the same time, network congestion can occur, leading to slow data transfer rates and poor network performance.
4. Packet loss: Packet loss occurs when packets of data are dropped during transmission. This can result in slower network speeds and lower overall network performance.
5. Network topology: The physical layout of a network, including the placement of switches, routers, and other network devices, can impact network performance.
6. Network protocol: Different network protocols have different performance characteristics, which can impact network performance. For example, TCP is a reliable protocol that can guarantee the delivery of data, but it can also result in slower performance due to the overhead required for error checking and retransmission.
7. Network security: Security measures such as firewalls and encryption can impact network performance, especially if they require significant processing power or introduce additional latency.
8. Distance: The physical distance between devices on a network can impact network performance, especially for wireless networks where signal strength and interference can affect connectivity and data transfer rates.

</details>

#### Control Plane and Data Plane

<details>
<summary><b>What does "control plane" refer to?</b></summary>

The control plane is a part of the network that decides how to route and forward packets to a different location.

</details>

<details>
<summary><b>What does "data plane" refer to?</b></summary>

The data plane is a part of the network that actually forwards the data/packets.

</details>

<details>
<summary><b>What does "management plane" refer to?</b></summary>

It refers to monitoring and management functions.

</details>

<details>
<summary><b>To which plane (data, control, ...) does creating routing tables belong to?</b></summary>

Control Plane.

</details>

<details>
<summary><b>Explain OSPF</b></summary>

OSPF (Open Shortest Path First) is a routing protocol that can be implemented on various types of routers. In general, OSPF is supported on most modern routers, including those from vendors such as Cisco, Juniper, and Huawei. The protocol is designed to work with IP-based networks, including both IPv4 and IPv6. Also, it uses a hierarchical network design, where routers are grouped into areas, with each area having its own topology map and routing table. This design helps to reduce the amount of routing information that needs to be exchanged between routers and improve network scalability.

The OSPF 4 Types of routers are:
  * Internal Router
  * Area Border Routers
  * Autonomous Systems Boundary Routers
  * Backbone Routers

  Learn more about OSPF router types: https://www.educba.com/ospf-router-types/

</details>

<details>
<summary><b>What is latency?</b></summary>

Latency is the time taken for information to reach its destination from the source.

</details>

<details>
<summary><b>What is bandwidth?</b></summary>

Bandwidth is the capacity of a communication channel to measure how much data the latter can handle over a specific time period. More bandwidth would imply more traffic handling and thus more data transfer.

</details>

<details>
<summary><b>What is throughput?</b></summary>

Throughput refers to the measurement of the real amount of data transferred over a certain period of time across any transmission channel.

</details>

<details>
<summary><b>When performing a search query, what is more important, latency or throughput? And how to ensure that we manage global infrastructure?</b></summary>

Latency. To have good latency, a search query should be forwarded to the closest data center.

</details>

<details>
<summary><b>When uploading a video, what is more important, latency or throughput? And how to assure that?</b></summary>

Throughput. To have good throughput, the upload stream should be routed to an underutilized link.

</details>

<details>
<summary><b>What other considerations (except latency and throughput) are there when forwarding requests?</b></summary>

* Keep caches updated (which means the request could be forwarded not to the closest data center)

</details>

<details>
<summary><b>Explain Spine & Leaf</b></summary>

"Spine & Leaf" is a networking topology commonly used in data center environments to connect multiple switches and manage network traffic efficiently. It is also known as "spine-leaf" architecture or "leaf-spine" topology. This design provides high bandwidth, low latency, and scalability, making it ideal for modern data centers handling large volumes of data and traffic.

Within a Spine & Leaf network there are two main tipology of switches:

* Spine Switches: Spine switches are high-performance switches arranged in a spine layer. These switches act as the core of the network and are typically interconnected with each leaf switch. Each spine switch is connected to all the leaf switches in the data center.
* Leaf Switches: Leaf switches are connected to end devices like servers, storage arrays, and other networking equipment. Each leaf switch is connected to every spine switch in the data center. This creates a non-blocking, full-mesh connectivity between leaf and spine switches, ensuring any leaf switch can communicate with any other leaf switch with maximum throughput.

The Spine & Leaf architecture has become increasingly popular in data centers due to its ability to handle the demands of modern cloud computing, virtualization, and big data applications, providing a scalable, high-performance, and reliable network infrastructure

</details>

<details>
<summary><b>What is Network Congestion? What can cause it?</b></summary>

Network congestion occurs when there is too much data to transmit on a network and it doesn't have enough capacity to handle the demand. </br>
This can lead to increased latency and packet loss. The causes can be multiple, such as high network usage, large file transfers, malware, hardware issues, or network design problems. </br>
To prevent network congestion, it's important to monitor your network usage and implement strategies to limit or manage the demand.

</details>

<details>
<summary><b>Give examples of protocols found in the application layer</b></summary>

* Hypertext Transfer Protocol (HTTP) - used for the webpages on the internet
* Simple Mail Transfer Protocol (SMTP) - email transmission
* Telecommunications Network - (TELNET) - terminal emulation to allow a client access to a telnet server
* File Transfer Protocol (FTP) - facilitates the transfer of files between any two machines
* Domain Name System (DNS) - domain name translation
* Dynamic Host Configuration Protocol (DHCP) - allocates IP addresses, subnet masks, and gateways to hosts
* Simple Network Management Protocol (SNMP) - gathers data on devices on the network

</details>

<details>
<summary><b>Give examples of protocols found in the Network Layer</b></summary>

* Internet Protocol (IP) - assists in routing packets from one machine to another
* Internet Control Message Protocol (ICMP) - lets one know what is going such as error messages and debugging information

</details>

---

### 📌 Additional Questions

<details>
<summary><b>What is HTTP?</b></summary>

[Avinetworks](https://avinetworks.com/glossary/layer-7/): HTTP stands for Hypertext Transfer Protocol. HTTP uses TCP port 80 to enable internet communication. It is part of the Application Layer (L7) in OSI Model.

</details>

<details>
<summary><b>Describe HTTP request lifecycle</b></summary>

* Resolve host by request to DNS resolver
* Client SYN
* Server SYN+ACK
* Client SYN
* HTTP request
* HTTP response

</details>

<details>
<summary><b>True or False? HTTP is stateful?</b></summary>

False. It doesn't maintain state for incoming request.

</details>

<details>
<summary><b>What HTTP method types are there?</b></summary>

* GET
* POST
* HEAD
* PUT
* DELETE
* CONNECT
* OPTIONS
* TRACE

</details>

<details>
<summary><b>What HTTP response codes are there?</b></summary>

* 1xx - informational
* 2xx - Success
* 3xx - Redirect
* 4xx - Error, client fault
* 5xx - Error, server fault

</details>

<details>
<summary><b>What is HTTPS?</b></summary>

HTTPS is a secure version of the HTTP protocol used to transfer data between a web browser and a web server. It encrypts the communication using SSL/TLS encryption to ensure that the data is private and secure.

Learn more: https://www.cloudflare.com/learning/ssl/why-is-http-not-secure/

</details>

<details>
<summary><b>Explain HTTP Cookies</b></summary>

HTTP is stateless. To share state, we can use Cookies.

TODO: explain what is actually a Cookie

</details>

<details>
<summary><b>You get "504 Gateway Timeout" error from an HTTP server. What does it mean?</b></summary>

The server didn't receive a response from another server it communicates with in a timely manner.

</details>

<details>
<summary><b>What is a proxy?</b></summary>

A proxy is a server that acts as a middleman between a client device and a destination server. It can help improve privacy, security, and performance by hiding the client's IP address, filtering content, and caching frequently accessed data. 
  - Proxies can be used for load balancing, distributing traffic across multiple servers to help prevent server overload and improve website or application performance. They can also be used for data analysis, as they can log requests and traffic, providing useful insights into user behavior and preferences.

</details>

<details>
<summary><b>What is a reverse proxy?</b></summary>

A reverse proxy is a type of proxy server that sits between a client and a server, but it is used to manage traffic going in the opposite direction of a traditional forward proxy. In a forward proxy, the client sends requests to the proxy server, which then forwards them to the destination server. However, in a reverse proxy, the client sends requests to the destination server, but the requests are intercepted by the reverse proxy before they reach the server. 
  - They're commonly used to improve web server performance, provide high availability and fault tolerance, and enhance security by preventing direct access to the back-end server. They are often used in large-scale web applications and high-traffic websites to manage and distribute requests to multiple servers, resulting in improved scalability and reliability.

</details>


#### Load Balancers

<details>
<summary><b>What is a load balancer?</b></summary>

A load balancer accepts (or denies) incoming network traffic from a client, and based on some criteria (application related, network, etc.) it distributes those communications out to servers (at least one).

</details>

<details>
<summary><b>Why to use a load balancer?</b></summary>

* Scalability - using a load balancer, you can possibly add more servers in the backend to handle more requests/traffic from the clients, as opposed to using one server.
* Redundancy - if one server in the backend dies, the load balancer will keep forwarding the traffic/requests to the second server so users won't even notice one of the servers in the backend is down.

</details>


<details>
<summary><b>What is an Application Load Balancer?</b></summary>

*(No answer provided in source)*

</details>

<details>
<summary><b>Can you perform load balancing without using a dedicated load balancer instance?</b></summary>

Yes, you can use DNS for performing load balancing.

</details>


#### Load Balancers - Sticky Sessions

<details>
<summary><b>What are sticky sessions? What are their pros and cons?</b></summary>

Recommended read:
  * [Red Hat Article](https://access.redhat.com/solutions/900933)

Cons:
  * Can cause uneven load on instance (since requests routed to the same instances)
Pros:
  * Ensures in-proc sessions are not lost when a new request is created

</details>

<details>
<summary><b>Name one use case for using sticky sessions</b></summary>

You would like to make sure the user doesn't lose the current session data.

</details>

<details>
<summary><b>What sticky sessions use for enabling the "stickiness"?</b></summary>

Cookies. There are application based cookies and duration based cookies.

</details>

#### Random

<details>
<summary><b>What is faster than RAM?</b></summary>

CPU cache.
[Source](https://www.enterprisestorageforum.com/hardware/cache-memory/)

</details>

<details>
<summary><b>What is a memory leak?</b></summary>

A memory leak is a programming error that occurs when a program fails to release memory that is no longer needed, causing the program to consume increasing amounts of memory over time.

The leaks can lead to a variety of problems, including system crashes, performance degradation, and instability. Usually occurring after failed maintenance on older systems and compatibility with new components over time.

</details>

---

## 📊 Monitoring, Logging & Observability

### 🟢 Beginner

<details>
<summary><b>What is Prometheus, and why is it used?</b></summary>

Prometheus is an open-source monitoring and alerting system used to collect metrics from applications and infrastructure. It is widely used because of its pull-based model, powerful query language (PromQL), and time-series database capabilities.

Example Use Case:

Monitoring CPU, memory, and network usage
Collecting application performance metrics
Alerting on high error rates or latency

</details>

<details>
<summary><b>How does Prometheus collect data?</b></summary>

Prometheus pulls metrics from target endpoints exposed via HTTP at /metrics. The targets can be defined in a static configuration or discovered dynamically (e.g., Kubernetes service discovery).

Example scrape configuration (prometheus.yml):

scrape_configs:
  - job_name: 'node_exporter'
    static_configs:
      - targets: ['localhost:9100']

</details>

<details>
<summary><b>What is PromQL?</b></summary>

PromQL (Prometheus Query Language) is used to query and analyze metrics stored in Prometheus. It enables users to create alerts, dashboards, and graphs.

Example Queries:

CPU usage:

node_cpu_seconds_total{mode="user"} / sum(node_cpu_seconds_total) * 100
Request rate:

rate(http_requests_total[5m])

</details>

<details>
<summary><b>What are Prometheus exporters?</b></summary>

Exporters are agents that collect and expose metrics from various applications and systems.

Common Exporters:

Node Exporter (system metrics)
Blackbox Exporter (network probes)
MySQL Exporter (database metrics)

</details>

<details>
<summary><b>How do you set up an alert in Prometheus?</b></summary>

Alerts are configured in alerting_rules.yml and evaluated by the Alertmanager.

Example Rule:

groups:
  - name: instance_down
    rules:
      - alert: InstanceDown
        expr: up == 0
        for: 5m
        labels:
          severity: critical
        annotations:
          description: "Instance {{ $labels.instance }} is down."
Grafana Questions

</details>

<details>
<summary><b>What is Grafana?</b></summary>

Grafana is an open-source analytics and visualization tool used to create interactive dashboards for monitoring data from Prometheus, ELK, and other sources.

</details>

<details>
<summary><b>How do you connect Grafana to Prometheus?</b></summary>

Login to Grafana (http://localhost:3000).
Navigate to "Configuration" → "Data Sources".
Select Prometheus as the data source.
Enter Prometheus URL (http://localhost:9090).
Click Save & Test.

</details>

<details>
<summary><b>What are Grafana Panels?</b></summary>

Panels are visual components in Grafana used to display data in various formats:

Graph Panel: Time-series data visualization
Single Stat Panel: Displays a single numeric value
Table Panel: Tabular data display

</details>

<details>
<summary><b>How do you create alerts in Grafana?</b></summary>

Select a panel.
Click "Edit" → "Alert".
Define a condition using PromQL queries.
Set the evaluation interval (e.g., every 1m).
Configure the alert notification (Slack, Email, etc.).

</details>

<details>
<summary><b>How do you configure a Grafana dashboard using JSON?</b></summary>

Export and import dashboards using JSON files.

Example JSON snippet:

{
  "panels": [
    {
      "type": "graph",
      "title": "CPU Usage",
      "targets": [
        { "expr": "node_cpu_seconds_total", "format": "time_series" }
      ]
    }
  ]
}
ELK Stack Questions (Elasticsearch, Logstash, Kibana)

</details>

<details>
<summary><b>What is the ELK Stack?</b></summary>

The ELK Stack consists of:

Elasticsearch (search and analytics engine)
Logstash (log processing pipeline)
Kibana (visualization tool)

</details>

<details>
<summary><b>What is the role of Elasticsearch in ELK?</b></summary>

Elasticsearch is a NoSQL, distributed search engine used to store, search, and analyze log data.

</details>

<details>
<summary><b>How does Logstash work?</b></summary>

Logstash processes logs using a pipeline:

Input: Reads logs (from files, databases, Kafka, etc.)
Filter: Transforms logs (parse JSON, remove sensitive data)
Output: Sends logs to Elasticsearch or other storage
Example Logstash Configuration:

input { file { path => "/var/log/syslog" } }
filter { grok { match => { "message" => "%{SYSLOGTIMESTAMP:timestamp}" } } }
output { elasticsearch { hosts => ["localhost:9200"] } }

</details>

<details>
<summary><b>What is Kibana used for?</b></summary>

Kibana is used to visualize and explore log data stored in Elasticsearch. It provides features like:

Dashboards: Custom data visualizations
Discover: Search raw logs
Alerts: Set up log-based alerts

</details>

<details>
<summary><b>How do you install the ELK stack?</b></summary>

Install Elasticsearch, Logstash, and Kibana:

# Install Elasticsearch
sudo apt install elasticsearch

# Install Logstash
sudo apt install logstash

# Install Kibana
sudo apt install kibana
Start services:

sudo systemctl start elasticsearch logstash kibana

</details>

<details>
<summary><b>What is an Index in Elasticsearch?</b></summary>

An index in Elasticsearch is like a database table that stores documents.

Example:

curl -X PUT "localhost:9200/logs"

</details>

<details>
<summary><b>How do you send logs from Logstash to Elasticsearch?</b></summary>

Define an output plugin in Logstash configuration:

output {
  elasticsearch {
    hosts => ["http://localhost:9200"]
    index => "logs-%{+YYYY.MM.dd}"
  }
}

</details>

<details>
<summary><b>What is a Kibana Visualization?</b></summary>

A Kibana Visualization is a graph, chart, or table displaying log data.

Example Visualizations:

Bar Chart (Logs per hour)
Pie Chart (Error types distribution)
Line Chart (CPU usage over time)

</details>

<details>
<summary><b>What is Filebeat?</b></summary>

Filebeat is a lightweight log shipper that forwards logs to Logstash or Elasticsearch.

Example Filebeat Configuration:

filebeat.inputs:
  - type: log
    paths:
      - "/var/log/syslog"
output.elasticsearch:
  hosts: ["localhost:9200"]

</details>

<details>
<summary><b>What is the difference between Logstash and Filebeat?</b></summary>

Logstash: Heavyweight, processes logs with complex transformations
Filebeat: Lightweight, only forwards logs with minimal processing

</details>

### 🟡 Intermediate

<details>
<summary><b>What is the difference between Pull and Push monitoring models?</b></summary>

Pull Model (Prometheus) → The monitoring system requests data from targets at regular intervals.
Push Model (StatsD, InfluxDB) → The target system sends data to a central monitoring system.
Prometheus uses a pull model because it provides better control over scraping intervals, avoids data duplication, and reduces unnecessary load on monitored systems. However, in some cases (e.g., short-lived jobs), Prometheus Pushgateway can be used to support push-based metrics.

</details>


<details>
<summary><b>What is Thanos, and how does it complement Prometheus?</b></summary>

Thanos extends Prometheus for scalability, long-term storage, and high availability. It:

Provides deduplication across multiple Prometheus instances.
Enables object storage support (e.g., S3, GCS).
Allows querying across multiple Prometheus servers via a single query layer.
Thanos is useful in multi-cluster environments where Prometheus instances are spread across multiple regions or clouds.

</details>

<details>
<summary><b>How do you handle Prometheus high availability (HA)?</b></summary>

Prometheus is a single-node system by design, but HA can be achieved by:

Running multiple Prometheus replicas (scraping the same targets).
Using Thanos or Cortex for deduplication and query federation.
Storing time-series data externally (e.g., in S3, Bigtable).
Grafana Questions

</details>

<details>
<summary><b>What are Grafana Loki and Promtail?</b></summary>

Loki is Grafana's log aggregation system, similar to Elasticsearch but optimized for Kubernetes and microservices.
Promtail is the log collection agent for pushing logs to Loki.
Promtail collects logs from /var/log and forwards them to Loki.

</details>

<details>
<summary><b>How can you monitor Kubernetes with Grafana?</b></summary>

Use kube-prometheus-stack, which includes:

Prometheus Operator (for Kubernetes metrics).
Grafana dashboards for cluster monitoring.
Node Exporter and Kube-State-Metrics for detailed node/pod-level metrics.
ELK Stack Questions (Elasticsearch, Logstash, Kibana)

</details>

<details>
<summary><b>What is an Elasticsearch Shard, and why is it important?</b></summary>

An Elasticsearch shard is a subdivision of an index. Each index is split into shards to allow parallel processing and redundancy.

Primary Shards: Store original data.
Replica Shards: Duplicates of primary shards for fault tolerance.
Example:

curl -X PUT "localhost:9200/logs?pretty" -H 'Content-Type: application/json' -d'
{
  "settings": { "number_of_shards": 3, "number_of_replicas": 2 }
}'
This creates an index with 3 primary and 2 replica shards.

</details>

<details>
<summary><b>What is Index Lifecycle Management (ILM) in Elasticsearch?</b></summary>

ILM automates index retention policies, ensuring efficient storage use. Stages include:

Hot Phase: Frequent reads/writes.
Warm Phase: Less frequent queries.
Cold Phase: Rarely accessed data.
Delete Phase: Data deletion.
ILM is useful for managing log retention in ELK stacks.

</details>

<details>
<summary><b>How do you configure Logstash pipelines?</b></summary>

Logstash uses a pipeline of input → filter → output.

Example logstash.conf:

input {
  beats {
    port => 5044
  }
}
filter {
  grok { match => { "message" => "%{TIMESTAMP_ISO8601:timestamp}" } }
}
output {
  elasticsearch { hosts => ["localhost:9200"] }
}
This pipeline processes logs from Filebeat → Logstash → Elasticsearch.

</details>



<details>
<summary><b>What is Beats in the ELK stack?</b></summary>

Beats are lightweight data shippers for sending logs, metrics, and security data to ELK.

Filebeat: Log shipping.
Metricbeat: System metrics.
Packetbeat: Network monitoring.

</details>


<details>
<summary><b>How do you integrate Prometheus and ELK Stack?</b></summary>

Use Metricbeat to collect system metrics and send them to Elasticsearch, while Prometheus Node Exporter collects Prometheus-compatible metrics.

</details>

<details>
<summary><b>What is a Slow Query in Elasticsearch?</b></summary>

A slow query is a query that takes too long to execute, often due to large data scans or missing indexes. Enable slow query logs to debug:

PUT _settings
{
  "index.search.slowlog.threshold.query.warn": "2s"
}

</details>

### 🔴 Advanced


<details>
<summary><b>How does Prometheus handle stale or missing metrics?</b></summary>

Stale markers: Prometheus marks time-series data as stale if a target stops reporting metrics.
Absent function (absent()): Used in PromQL to detect missing metrics.
Dead Man’s Switch: A constant alert (e.g., ALWAYS_ON) ensures the alerting system is functional.
Example:

absent(up{job="my_service"})
Triggers an alert if up{job="my_service"} is missing.

</details>

<details>
<summary><b>What is Prometheus WAL (Write-Ahead Log) and its purpose?</b></summary>

The Write-Ahead Log (WAL) in Prometheus:

Stores data on disk before committing it to TSDB (Time-Series Database).
Reduces data loss during crashes.
WAL files are stored in /data/wal/ and help recover metrics quickly after a restart.

</details>

<details>
<summary><b>What are Histogram and Summary metrics in Prometheus?</b></summary>

Both are used for measuring latency and response time:

Histogram: Buckets data into predefined ranges, allowing percentiles to be calculated later.
Summary: Precomputes percentiles but cannot be aggregated across instances.
Example (Histogram metric):

histogram_quantile(0.95, rate(http_request_duration_seconds_bucket[5m]))
This calculates the 95th percentile response time.

</details>

<details>
<summary><b>How do you secure Prometheus endpoints?</b></summary>

Enable authentication & TLS via a reverse proxy (Nginx, Traefik).
Use RBAC (Role-Based Access Control) in Kubernetes for limiting access.
Set up network policies to restrict Prometheus access.
Example: Using basic auth with Nginx:

server {
  listen 9090;
  location / {
    auth_basic "Restricted";
    auth_basic_user_file /etc/nginx/.htpasswd;
  }
}
Grafana Questions

</details>

<details>
<summary><b>How do you monitor Prometheus itself using Grafana?</b></summary>

Enable the built-in Prometheus self-metrics endpoint (/metrics).
Use dashboards to monitor scrape latency, TSDB memory usage, query duration.
Use the Prometheus Federation API to get meta-metrics.

</details>

<details>
<summary><b>What are Grafana Annotations and how are they useful?</b></summary>

Annotations mark events (deployments, incidents, downtimes) on Grafana graphs for better visualization.
Example: Mark a Kubernetes deployment event in Grafana.

</details>


<details>
<summary><b>What is Alerting in Grafana and how does it work?</b></summary>

Grafana alerts monitor query conditions.
Alert states: OK, Pending, Alerting, No Data.
Notification channels: Slack, PagerDuty, Email, Webhooks.
Example Grafana alert condition:

avg(http_requests_total) > 1000 → Sends an alert if requests exceed 1000.

</details>

<details>
<summary><b>How does Loki compare with Elasticsearch for logging?</b></summary>

Feature	Loki	Elasticsearch
Storage	Compressed logs	Full-text index
Querying	Label-based	Query DSL
Performance	Faster (optimized for Kubernetes)	Heavy resource usage
Loki is recommended for lightweight, Kubernetes-native logging, while Elasticsearch is better for complex log analysis.

ELK Stack Questions

</details>

<details>
<summary><b>What is the Hot-Warm-Cold architecture in Elasticsearch?</b></summary>

This strategy optimizes storage cost:

Hot Nodes → Store recent, frequently queried data.
Warm Nodes → Store older logs with infrequent access.
Cold Nodes → Store archived logs for long-term retention.

</details>

<details>
<summary><b>How do you reduce indexing pressure in Elasticsearch?</b></summary>

Use ILM (Index Lifecycle Management).
Optimize shard count (Avoid too many small shards).
Increase refresh intervals (index.refresh_interval: 30s).

</details>

<details>
<summary><b>How does Logstash manage backpressure?</b></summary>

Persistent Queues → Buffer data before sending to Elasticsearch.
Dead Letter Queue (DLQ) → Stores failed events for reprocessing.
Example:

queue.type: persisted
queue.max_bytes: 1gb

</details>

<details>
<summary><b>What are Query Caching strategies in Elasticsearch?</b></summary>

Request cache: Stores query results.
Shard request cache: Caches aggregations and filters.
Doc value cache: Optimizes sorting and aggregations.

</details>

<details>
<summary><b>How do you integrate Prometheus with Elasticsearch?</b></summary>

Use Metricbeat to push Prometheus data into Elasticsearch.
Use Grafana to visualize both Prometheus & ELK logs.
Example Metricbeat configuration:

metricbeat.modules:
  - module: prometheus
    metricsets: ["collector"]
    host: "localhost:9090"

</details>

<details>
<summary><b>How do you optimize Elasticsearch queries for performance?</b></summary>

Use filters (term, match_phrase) instead of full-text search.
Avoid wildcard (*) searches.
Use doc_values for sorting and aggregations.

</details>

<details>
<summary><b>How do you implement centralized logging in Kubernetes?</b></summary>

Use Fluentd/Filebeat to collect logs.
Send logs to Elasticsearch or Loki.
Monitor logs via Kibana or Grafana dashboards.
Example Fluentd configuration:

<match kubernetes.**>
  @type elasticsearch
  host elasticsearch
  logstash_format true
</match>

</details>

<details>
<summary><b>What are the best practices for log retention and compliance?</b></summary>

Use ILM to delete old logs automatically.
Encrypt sensitive logs (xpack.security).
Mask PII data before indexing logs.
Set audit logs for security compliance.

</details>

### 📌 Additional Questions

<details>
<summary><b>In what scenarios it might be better to NOT use Prometheus?</b></summary>

From Prometheus documentation: "if you need 100% accuracy, such as for per-request billing".

</details>

<details>
<summary><b>Describe Prometheus architecture and components</b></summary>

The Prometheus architecture consists of four major components:

    1. Prometheus Server: The Prometheus server is responsible for collecting and storing metrics data. It has a simple built-in storage layer that allows it to store time-series data in a time-ordered database.

    2. Client Libraries: Prometheus provides a range of client libraries that enable applications to expose their metrics data in a format that can be ingested by the Prometheus server. These libraries are available for a range of programming languages, including Java, Python, and Go.

    3. Exporters: Exporters are software components that expose existing metrics from third-party systems and make them available for ingestion by the Prometheus server. Prometheus provides exporters for a range of popular technologies, including MySQL, PostgreSQL, and Apache.

    4. Alertmanager: The Alertmanager component is responsible for processing alerts generated by the Prometheus server. It can handle alerts from multiple sources and provides a range of features for deduplicating, grouping, and routing alerts to appropriate channels.

Overall, the Prometheus architecture is designed to be highly scalable and resilient. The server and client libraries can be deployed in a distributed fashion to support monitoring across large-scale, highly dynamic environments

</details>


<details>
<summary><b>What is an Alert?</b></summary>

In Prometheus, an alert is a notification triggered when a specific condition or threshold is met. Alerts can be configured to trigger when certain metrics cross a certain threshold or when specific events occur. Once an alert is triggered, it can be routed to various channels, such as email, pager, or chat, to notify relevant teams or individuals to take appropriate action. Alerts are a critical component of any monitoring system, as they allow teams to proactively detect and respond to issues before they impact users or cause system downtime.

</details>

<details>
<summary><b>What is an Instance? What is a Job?</b></summary>

In Prometheus, an instance refers to a single target that is being monitored. For example, a single server or service. A job is a set of instances that perform the same function, such as a set of web servers serving the same application. Jobs allow you to define and manage a group of targets together.

In essence, an instance is an individual target that Prometheus collects metrics from, while a job is a collection of similar instances that can be managed as a group.

</details>

<details>
<summary><b>What core metrics types Prometheus supports?</b></summary>

Prometheus supports several types of metrics, including:

    1. Counter: A monotonically increasing value used for tracking counts of events or samples. Examples include the number of requests processed or the total number of errors encountered.

    2. Gauge: A value that can go up or down, such as CPU usage or memory usage. Unlike counters, gauge values can be arbitrary, meaning they can go up and down based on changes in the system being monitored.

    3. Histogram: A set of observations or events that are divided into buckets based on their value. Histograms help in analyzing the distribution of a metric, such as request latencies or response sizes.

    4. Summary: A summary is similar to a histogram, but instead of buckets, it provides a set of quantiles for the observed values. Summaries are useful for monitoring the distribution of request latencies or response sizes over time.

Prometheus also supports various functions and operators for aggregating and manipulating metrics, such as sum, max, min, and rate. These features make it a powerful tool for monitoring and alerting on system metrics.

</details>


<details>
<summary><b>Which Prometheus best practices?</b></summary>

Here are three of them:

    1. Label carefully: Careful and consistent labeling of metrics is crucial for effective querying and alerting. Labels should be clear, concise, and include all relevant information about the metric.

    2. Keep metrics simple: The metrics exposed by exporters should be simple and focus on a single aspect of the system being monitored. This helps avoid confusion and ensures that the metrics are easily understandable by all members of the team.

    3. Use alerting sparingly: While alerting is a powerful feature of Prometheus, it should be used sparingly and only for the most critical issues. Setting up too many alerts can lead to alert fatigue and result in important alerts being ignored. It is recommended to set up only the most important alerts and adjust the thresholds over time based on the actual frequency of alerts.

</details>

<details>
<summary><b>How to get total requests in a given period of time?</b></summary>

To get the total requests in a given period of time using Prometheus, you can use the *sum* function along with the *rate* function. Here is an example query that will give you the total number of requests in the last hour:

```
sum(rate(http_requests_total[1h]))
```
In this query, *http_requests_total* is the name of the metric that tracks the total number of HTTP requests, and the *rate* function calculates the per-second rate of requests over the last hour. The *sum* function then adds up all of the requests to give you the total number of requests in the last hour.

You can adjust the time range by changing the duration in the *rate* function. For example, if you wanted to get the total number of requests in the last day, you could change the function to *rate(http_requests_total[1d])*.

</details>

<details>
<summary><b>How do you join two metrics?</b></summary>

In Prometheus, joining two metrics can be achieved using the *join()* function. The *join()* function combines two or more time series based on their label values. It takes two mandatory arguments: *on* and *table*. The on argument specifies the labels to join *on* and the *table* argument specifies the time series to join.

Here's an example of how to join two metrics using the *join()* function:

```
sum_series(
  join(
    on(service, instance) request_count_total,
    on(service, instance) error_count_total,
  )
)
```
In this example, the *join()* function combines the *request_count_total* and *error_count_total* time series based on their *service* and *instance* label values. The *sum_series()* function then calculates the sum of the resulting time series

</details>

<details>
<summary><b>How to write a query that returns the value of a label?</b></summary>

To write a query that returns the value of a label in Prometheus, you can use the *label_values* function. The *label_values* function takes two arguments: the name of the label and the name of the metric.

For example, if you have a metric called *http_requests_total* with a label called *method*, and you want to return all the values of the *method* label, you can use the following query:

```
label_values(http_requests_total, method)
```

This will return a list of all the values for the *method* label in the *http_requests_total* metric. You can then use this list in further queries or to filter your data.

</details>


<details>
<summary><b>How do you monitor and troubleshoot applications in a DevOps environment?</b></summary>

*(No answer provided in source)*

</details>

<details>
<summary><b>Explain the concept of "Log Aggregation" in DevOps</b></summary>

*(No answer provided in source)*

</details>

---

## 💾 Storage

<details>
<summary><b>What types of storage are there?</b></summary>

* File
  * Block
  * Object

</details>

<details>
<summary><b>Explain Object Storage</b></summary>

- Data is divided to self-contained objects
- Objects can contain metadata

</details>

<details>
<summary><b>What are the pros and cons of object storage?</b></summary>

Pros:
  - Usually with object storage, you pay for what you use as opposed to other storage types where you pay for the storage space you allocate
  - Scalable storage: Object storage mostly based on a model where what you use, is what you get and you can add storage as need
Cons:
  - Usually performs slower than other types of storage
  - No granular modification: to change an object, you have re-create it

</details>

<details>
<summary><b>What are some use cases for using object storage?</b></summary>

*(No answer provided in source)*

</details>

<details>
<summary><b>Explain File Storage</b></summary>

- File Storage used for storing data in files, in a hierarchical structure
- Some of the devices for file storage: hard drive, flash drive, cloud-based file storage
- Files usually organized in directories

</details>

<details>
<summary><b>What are the pros and cons of File Storage?</b></summary>

Pros:
- Users have full control of their own files and can run variety of operations on the files: delete, read, write and move.
- Security mechanism allows for users to have a better control at things such as file locking

</details>

<details>
<summary><b>What are some examples of file storage?</b></summary>

Local filesystem
Dropbox
Google Drive

</details>

<details>
<summary><b>What types of storage devices are there?</b></summary>

*(No answer provided in source)*

</details>

<details>
<summary><b>Explain IOPS</b></summary>

*(No answer provided in source)*

</details>

<details>
<summary><b>Explain storage throughput</b></summary>

*(No answer provided in source)*

</details>

<details>
<summary><b>What is a filesystem?</b></summary>

A file system is a way for computers and other electronic devices to organize and store data files. It provides a structure that helps to organize data into files and directories, making it easier to find and manage information. A file system is crucial for providing a way to store and manage data in an organized manner.

Commonly used filed systems:
  Windows:
  * NTFS
  * exFAT

  Mac OS:
  * HFS+
  *APFS

</details>

<details>
<summary><b>Explain Dark Data</b></summary>

*(No answer provided in source)*

</details>

<details>
<summary><b>Explain MBR</b></summary>

*(No answer provided in source)*

</details>

---

## 🕸️ Distributed Systems

<details>
<summary><b>Explain Distributed Computing (or Distributed System)</b></summary>

According to Martin Kleppmann:

"Many processes running on many machines...only message-passing via an unreliable network with variable delays, and the system may suffer from partial failures, unreliable clocks, and process pauses."

Another definition: "Systems that are physically separated, but logically connected"

</details>

<details>
<summary><b>What can cause a system to fail?</b></summary>

* Network
* CPU
* Memory
* Disk

</details>

<details>
<summary><b>Do you know what is "CAP theorem"? (aka as Brewer's theorem)?</b></summary>

According to the CAP theorem, it's not possible for a distributed data store to provide more than two of the following at the same time:

* Availability: Every request receives a response (it doesn't has to be the most recent data)
* Consistency: Every request receives a response with the latest/most recent data
* Partition tolerance: Even if some the data is lost/dropped, the system keeps running

</details>

<details>
<summary><b>What are the problems with the following design? How to improve it?<br> <img src="images/distributed/distributed_design_standby.png" width="500x;" height="350px;"/>?</b></summary>

1. The transition can take time. In other words, noticeable downtime.
2. Standby server is a waste of resources - if first application server is running then the standby does nothing

</details>

<details>
<summary><b>What are the problems with the following design? How to improve it?<br> <img src="images/distributed/distributed_design_lb.png" width="700x;" height="350px;"/>?</b></summary>

Issues:
If load balancer dies , we lose the ability to communicate with the application.

Ways to improve:
* Add another load balancer
* Use DNS A record for both load balancers
* Use message queue

</details>

<details>
<summary><b>What is "Shared-Nothing" architecture?</b></summary>

It's an architecture in which data is and retrieved from a single, non-shared, source usually exclusively connected to one node as opposed to architectures where the request can get to one of many nodes and the data will be retrieved from one shared location (storage, memory, ...).

</details>

<details>
<summary><b>Explain the Sidecar Pattern (Or sidecar proxy)</b></summary>

*(No answer provided in source)*

</details>

<details>
<summary><b>How do you ensure data consistency in a distributed microservices architecture?</b></summary>

*(No answer provided in source)*

</details>

---

## 🏛️ System Design

<details>
<summary><b>Explain what a "single point of failure" is</b></summary>

A "single point of failure", in a system or organization, if it were to fail would cause the entire system to fail or significantly disrupt it's operation. In other words, it is a vulnerability where there
is no backup in place to compensate for the failure.

</details>

<details>
<summary><b>What is CDN?</b></summary>

CDN (Content Delivery Network) responsible for distributing content geographically. Part of it, is what is known as edge locations, aka cache proxies, that allows users to get their content quickly due to cache features and geographical distribution.

</details>

<details>
<summary><b>Explain "Loose Coupling"</b></summary>

In "Loose Coupling", components of a system communicate with each other with a little understanding of each other's internal workings. This improves scalability and ease of modification in complex systems.

</details>

<details>
<summary><b>What is a message queue? When is it used?</b></summary>

It is a communication mechanism used in distributed systems to enable asynchronous communication between different components. It is generally used when the systems use a microservices approach.

</details>


<details>
<summary><b>What is the role of configuration management in DevOps?</b></summary>

*(No answer provided in source)*

</details>


<details>
<summary><b>How does "Self-Healing Infrastructure" work in a DevOps environment?</b></summary>

*(No answer provided in source)*

</details>

<details>
<summary><b>How do you handle data migration in a DevOps environment?</b></summary>

*(No answer provided in source)*

</details>

<details>
<summary><b>Benefits of Observability in Microservices Architecture</b></summary>

*(No answer provided in source)*

</details>

<details>
<summary><b>How to Achieve High Availability and Fault Tolerance in a DevOps Architecture?</b></summary>

*(No answer provided in source)*

</details>

<details>
<summary><b>What Are the Key Considerations for Creating a Disaster Recovery Plan in a DevOps Environment?</b></summary>

*(No answer provided in source)*

</details>

### Scalability

<details>
<summary><b>Explain Scalability</b></summary>

The ability easily grow in size and capacity based on demand and usage.

</details>

<details>
<summary><b>Explain Elasticity</b></summary>

The ability to grow but also to reduce based on what is required

</details>

<details>
<summary><b>Explain Disaster Recovery</b></summary>

Disaster recovery is the process of restoring critical business systems and data after a disruptive event. The goal is to minimize the impact and resume normal business activities quickly. This involves creating a plan, testing it, backing up critical data, and storing it in safe locations. In case of a disaster, the plan is then executed, backups are restored, and systems are hopefully brought back online. The recovery process may take hours or days depending on the damages of infrastructure. This makes business planning important, as a well-designed and tested disaster recovery plan can minimize the impact of a disaster and keep operations going.

</details>

<details>
<summary><b>Explain Fault Tolerance and High Availability</b></summary>

Fault Tolerance - The ability to self-heal and return to normal capacity. Also the ability to withstand a failure and remain functional.

High Availability - Being able to access a resource (in some use cases, using different platforms)

</details>

<details>
<summary><b>What is the difference between high availability and Disaster Recovery?</b></summary>

[wintellect.com](https://www.wintellect.com/high-availability-vs-disaster-recovery): "High availability, simply put, is eliminating single points of failure and disaster recovery is the process of getting a system back to an operational state when a system is rendered inoperative. In essence, disaster recovery picks up when high availability fails, so HA first."

</details>

<details>
<summary><b>Explain Vertical Scaling</b></summary>

Vertical Scaling is the process of adding resources to increase power of existing servers. For example, adding more CPUs, adding more RAM, etc.

</details>

<details>
<summary><b>What are the disadvantages of Vertical Scaling?</b></summary>

With vertical scaling alone, the component still remains a single point of failure.
In addition, it has hardware limit where if you don't have more resources, you might not be able to scale vertically.

</details>

<details>
<summary><b>Which type of cloud services usually support vertical scaling?</b></summary>

Databases, cache. It's common mostly for non-distributed systems.

</details>

<details>
<summary><b>Explain Horizontal Scaling</b></summary>

Horizontal Scaling is the process of adding more resources that will be able handle requests as one unit

</details>

<details>
<summary><b>What is the disadvantage of Horizontal Scaling? What is often required in order to perform Horizontal Scaling?</b></summary>

A load balancer. You can add more resources, but if you would like them to be part of the process, you have to serve them the requests/responses.
Also, data inconsistency is a concern with horizontal scaling.

</details>

<details>
<summary><b>Explain in which use cases will you use vertical scaling and in which use cases you will use horizontal scaling</b></summary>

*(No answer provided in source)*

</details>

<details>
<summary><b>Explain Resiliency and what ways are there to make a system more resilient</b></summary>

*(No answer provided in source)*

</details>

<details>
<summary><b>Explain "Consistent Hashing"</b></summary>

*(No answer provided in source)*

</details>

<details>
<summary><b>How would you update each of the services in the following drawing without having app (foo.com) downtime?<br> <img src="images/design/cdn-no-downtime.png" width="300x;" height="400px;"/>?</b></summary>

*(No answer provided in source)*

</details>

<details>
<summary><b>What is the problem with the following architecture and how would you fix it?<br> <img src="images/design/producers_consumers_issue.png" width="400x;" height="300px;"/>?</b></summary>

The load on the producers or consumers may be high which will then cause them to hang or crash.<br>
Instead of working in "push mode", the consumers can pull tasks only when they are ready to handle them. It can be fixed by using a streaming platform like Kafka, Kinesis, etc. This platform will make sure to handle the high load/traffic and pass tasks/messages to consumers only when the ready to get them.

<img src="images/design/producers_consumers_fix.png" width="300x;" height="200px;"/>

</details>

<details>
<summary><b>Users report that there is huge spike in process time when adding little bit more data to process as an input. What might be the problem?<br> <img src="images/design/input-process-output.png" width="300x;" height="200px;"/></b></summary>

*(No answer provided in source)*

</details>

<details>
<summary><b>How would you scale the architecture from the previous question to hundreds of users?</b></summary>

*(No answer provided in source)*

</details>

### Cache

<details>
<summary><b>What is "cache"? In which cases would you use it?</b></summary>

*(No answer provided in source)*

</details>

<details>
<summary><b>What is "distributed cache"?</b></summary>

*(No answer provided in source)*

</details>

<details>
<summary><b>Explain the following cache policies: * FIFO * LIFO * LRU</b></summary>

Read about it [here](https://en.wikipedia.org/wiki/Cache_replacement_policies)

</details>

<details>
<summary><b>Why not writing everything to cache instead of a database/datastore?</b></summary>

Caching and databases serve different purposes and are optimized for different use cases.

Caching is used to speed up read operations by storing frequently accessed data in memory or on a fast storage medium. By keeping data close to the application, caching reduces the latency and overhead of accessing data from a slower, more distant storage system such as a database or disk.

On the other hand, databases are optimized for storing and managing persistent data. Databases are designed to handle concurrent read and write operations, enforce consistency and integrity constraints, and provide features such as indexing and querying.

</details>

### Migrations

<details>
<summary><b>How you prepare for a migration? (or plan a migration)?</b></summary>

You can mention:

roll-back & roll-forward
cut over
dress rehearsals
DNS redirection

</details>


### Design a system

<details>
<summary><b>How would you build a URL shortener?</b></summary>

*(No answer provided in source)*

</details>

---

## 🧪 Testing

<details>
<summary><b>Explain white-box testing</b></summary>

*(No answer provided in source)*

</details>

<details>
<summary><b>Explain black-box testing</b></summary>

*(No answer provided in source)*

</details>

<details>
<summary><b>What are unit tests?</b></summary>

Unit test are a software testing technique that involves systimatically breaking down a system and testing each individual part of the assembly. These tests are automated and can be run repeatedly to allow developers to catch edge case scenarios or bugs quickly while developing.

The main objective of unit tests are to verify each function is producing proper outputs given a set of inputs.

</details>

<details>
<summary><b>What types of tests would you run to test a web application?</b></summary>

*(No answer provided in source)*

</details>

<details>
<summary><b>What is A/B testing?</b></summary>

*(No answer provided in source)*

</details>

<details>
<summary><b>What is network simulation and how do you perform it?</b></summary>

*(No answer provided in source)*

</details>

<details>
<summary><b>What types of performances tests are you familiar with?</b></summary>

*(No answer provided in source)*

</details>

<details>
<summary><b>Explain the following types of tests: * Load Testing * Stress Testing * Capacity Testing * Volume Testing * Endurance Testing</b></summary>

*(No answer provided in source)*

</details>

<details>
<summary><b>Explain the concept of "Continuous Testing" in the context of DevOps</b></summary>

*(No answer provided in source)*

</details>

<details>
<summary><b>What is "IaC Testing," and how does it ensure the reliability of infrastructure deployments in DevOps?</b></summary>

*(No answer provided in source)*

</details>

### Extract

<details>
<summary><b>Extract all the numbers</b></summary>

- "\d+"

</details>

<details>
<summary><b>Extract the first word of each line</b></summary>

- "^\w+"
Bonus: extract the last word of each line

  - "\w+(?=\W*$)" (in most cases, depends on line formatting)

</details>

<details>
<summary><b>Extract all the IP addresses</b></summary>

- "\b(?:\d{1,3}\ .){3}\d{1,3}\b" IPV4:(This format looks for 1 to 3 digit sequence 3 times)

</details>

<details>
<summary><b>Extract dates in the format of yyyy-mm-dd or yyyy-dd-mm</b></summary>

*(No answer provided in source)*

</details>

<details>
<summary><b>Extract email addresses</b></summary>

- "\b[A-Za-z0-9._%+-]+@[A-Za-z0-9.-]+\ .[A-Za-z]{2,}\b"

</details>

### Replace

<details>
<summary><b>Replace tabs with four spaces</b></summary>

*(No answer provided in source)*

</details>

<details>
<summary><b>Replace 'red' with 'green'</b></summary>

*(No answer provided in source)*

</details>

---

## 🔧 Hardware

<details>
<summary><b>What is a CPU?</b></summary>

A central processing unit (CPU) performs basic arithmetic, logic, controlling, and input/output (I/O) operations specified by the instructions in the program. This contrasts with external components such as main memory and I/O circuitry, and specialized processors such as graphics processing units (GPUs).

</details>

<details>
<summary><b>What is RAM?</b></summary>

RAM (Random Access Memory) is the hardware in a computing device where the operating system (OS), application programs and data in current use are kept so they can be quickly reached by the device's processor. RAM is the main memory in a computer. It is much faster to read from and write to than other kinds of storage, such as a hard disk drive (HDD), solid-state drive (SSD) or optical drive.

</details>

<details>
<summary><b>What is a GPU?</b></summary>

A GPU, or Graphics Processing Unit, is a specialized electronic circuit designed to expedite image and video processing for display on a computer screen.

</details>

<details>
<summary><b>What is an embedded system?</b></summary>

An embedded system is a computer system - a combination of a computer processor, computer memory, and input/output peripheral devices—that has a dedicated function within a larger mechanical or electronic system. It is embedded as part of a complete device often including electrical or electronic hardware and mechanical parts.

</details>

<details>
<summary><b>Can you give an example of an embedded system?</b></summary>

A common example of an embedded system is a microwave oven's digital control panel, which is managed by a microcontroller.

When committed to a certain goal, Raspberry Pi can serve as an embedded system.

</details>

<details>
<summary><b>What are some considerations DevOps teams should keep in mind when selecting hardware for their job?</b></summary>

<br>

Choosing the right DevOps hardware is essential for ensuring streamlined CI/CD pipelines, timely feedback loops, and consistent service availability. Here's a distilled guide on what DevOps teams should consider:

1. **Understanding Workloads**:
    - **CPU**: Consider the need for multi-core or high-frequency CPUs based on your tasks.
    - **RAM**: Enough memory is vital for activities like large-scale coding or intensive automation.
    - **Storage**: Evaluate storage speed and capacity. SSDs might be preferable for swift operations.

2. **Expandability**:
    - **Horizontal Growth**: Check if you can boost capacity by adding more devices.
    - **Vertical Growth**: Determine if upgrades (like RAM, CPU) to individual machines are feasible.

3. **Connectivity Considerations**:
    - **Data Transfer**: Ensure high-speed network connections for activities like code retrieval and data transfers.
    - **Speed**: Aim for low-latency networks, particularly important for distributed tasks.
    - **Backup Routes**: Think about having backup network routes to avoid downtimes.

4. **Consistent Uptime**:
    - Plan for hardware backups like RAID configurations, backup power sources, or alternate network connections to ensure continuous service.

5. **System Compatibility**:
    - Make sure your hardware aligns with your software, operating system, and intended platforms.

6. **Power Efficiency**:
    - Hardware that uses energy efficiently can reduce costs in long-term, especially in large setups.

7. **Safety Measures**:
    - Explore hardware-level security features, such as TPM, to enhance protection.

8. **Overseeing & Control**:
    - Tools like ILOM can be beneficial for remote handling.
    - Make sure the hardware can be seamlessly monitored for health and performance.

9. **Budgeting**:
    - Consider both initial expenses and long-term costs when budgeting.

10. **Support & Community**:
    - Choose hardware from reputable vendors known for reliable support.
    - Check for available drivers, updates, and community discussions around the hardware.

11. **Planning Ahead**:
    - Opt for hardware that can cater to both present and upcoming requirements.

12. **Operational Environment**:
    - **Temperature Control**: Ensure cooling systems to manage heat from high-performance units.
    - **Space Management**: Assess hardware size considering available rack space.
    - **Reliable Power**: Factor in consistent and backup power sources.

13. **Cloud Coordination**:
    - If you're leaning towards a hybrid cloud setup, focus on how local hardware will mesh with cloud resources.

14. **Life Span of Hardware**:
    - Be aware of the hardware's expected duration and when you might need replacements or upgrades.

15. **Optimized for Virtualization**:
    - If utilizing virtual machines or containers, ensure the hardware is compatible and optimized for such workloads.

16. **Adaptability**:
    - Modular hardware allows individual component replacements, offering more flexibility.

17. **Avoiding Single Vendor Dependency**:
    - Try to prevent reliance on a single vendor unless there are clear advantages.

18. **Eco-Friendly Choices**:
    - Prioritize sustainably produced hardware that's energy-efficient and environmentally responsible.

In essence, DevOps teams should choose hardware that is compatible with their tasks, versatile, gives good performance, and stays within their budget. Furthermore, long-term considerations such as maintenance, potential upgrades, and compatibility with impending technological shifts must be prioritized.

</details>

<details>
<summary><b>What is the role of hardware in disaster recovery planning and implementation?</b></summary>

<br>

Hardware is critical in disaster recovery (DR) solutions. While the broader scope of DR includes things like standard procedures, norms, and human roles, it's the hardware that keeps business processes running smoothly. Here's an outline of how hardware works with DR:

1. **Storing Data and Ensuring Its Duplication**:
    - **Backup Equipment**: Devices like tape storage, backup servers, and external HDDs keep essential data stored safely at a different location.
    - **Disk Arrays**: Systems such as RAID offer a safety net. If one disk crashes, the others compensate.

2. **Alternate Systems for Recovery**:
    - **Backup Servers**: These step in when the main servers falter, maintaining service flow.
    - **Traffic Distributors**: Devices like load balancers share traffic across servers. If a server crashes, they reroute users to operational ones.

3. **Alternate Operation Hubs**:
    - **Ready-to-use Centers**: Locations equipped and primed to take charge immediately when the main center fails.
    - **Basic Facilities**: Locations with necessary equipment but lacking recent data, taking longer to activate.
    - **Semi-prepped Facilities**: Locations somewhat prepared with select systems and data, taking a moderate duration to activate.

4. **Power Backup Mechanisms**:
    - **Instant Power Backup**: Devices like UPS offer power during brief outages, ensuring no abrupt shutdowns.
    - **Long-term Power Solutions**: Generators keep vital systems operational during extended power losses.

5. **Networking Equipment**:
    - **Backup Internet Connections**: Having alternatives ensures connectivity even if one provider faces issues.
    - **Secure Connection Tools**: Devices ensuring safe remote access, especially crucial during DR situations.

6. **On-site Physical Setup**:
    - **Organized Housing**: Structures like racks to neatly store and manage hardware.
    - **Emergency Temperature Control**: Backup cooling mechanisms to counter server overheating in HVAC malfunctions.

7. **Alternate Communication Channels**:
    - **Orbit-based Phones**: Handy when regular communication methods falter.
    - **Direct Communication Devices**: Devices like radios useful when primary systems are down.

8. **Protection Mechanisms**:
    - **Electronic Barriers & Alert Systems**: Devices like firewalls and intrusion detection keep DR systems safeguarded.
    - **Physical Entry Control**: Systems controlling entry and monitoring, ensuring only cleared personnel have access.

9. **Uniformity and Compatibility in Hardware**:
    - It's simpler to manage and replace equipment in emergencies if hardware configurations are consistent and compatible.

10. **Equipment for Trials and Upkeep**:
    - DR drills might use specific equipment to ensure the primary systems remain unaffected. This verifies the equipment's readiness and capacity to manage real crises.

In summary, while software and human interventions are important in disaster recovery operations, it is the hardware that provides the underlying support. It is critical for efficient disaster recovery plans to keep this hardware resilient, duplicated, and routinely assessed.

</details>

<details>
<summary><b>What is a RAID?</b></summary>

RAID is an acronym that stands for "Redundant Array of Independent Disks." It is a technique that combines numerous hard drives into a single device known as an array in order to improve performance, expand storage capacity, and/or offer redundancy to prevent data loss. RAID levels (for example, RAID 0, RAID 1, and RAID 5) provide varied benefits in terms of performance, redundancy, and storage efficiency.

</details>

<details>
<summary><b>What is a microcontroller?</b></summary>

A microcontroller is a small integrated circuit that controls certain tasks in an embedded system. It typically includes a CPU, memory, and input/output peripherals.

</details>

<details>
<summary><b>What is a Network Interface Controller or NIC?</b></summary>

A Network Interface Controller (NIC) is a piece of hardware that connects a computer to a network and allows it to communicate with other devices.

</details>

<details>
<summary><b>What is a DMA?</b></summary>

Direct memory access (DMA) is a feature of computer systems that allows certain hardware subsystems to access main system memory independently of the central processing unit (CPU).DMA enables devices to share and receive data from the main memory in a computer. It does this while still allowing the CPU to perform other tasks.

</details>

<details>
<summary><b>What is a Real-Time Operating Systems?</b></summary>

A real-time operating system (RTOS) is an operating system (OS) for real-time computing applications that processes data and events that have critically defined time constraints. An RTOS is distinct from a time-sharing operating system, such as Unix, which manages the sharing of system resources with a scheduler, data buffers, or fixed task prioritization in a multitasking or multiprogramming environment. Processing time requirements need to be fully understood and bound rather than just kept as a minimum. All processing must occur within the defined constraints. Real-time operating systems are event-driven and preemptive, meaning the OS can monitor the relevant priority of competing tasks, and make changes to the task priority. Event-driven systems switch between tasks based on their priorities, while time-sharing systems switch the task based on clock interrupts.

</details>

<details>
<summary><b>List of interrupt types</b></summary>

There are six classes of interrupts possible:
* External
* Machine check
* I/O
* Program
* Restart
* Supervisor call (SVC)

</details>

---

## 🧩 Miscellaneous (API, YAML, Firmware)

<details>
<summary><b>What happens when you type in a URL in an address bar in a browser?</b></summary>

1. The browser searches for the record of the domain name IP address in the DNS in the following order:
  * Browser cache
  * Operating system cache
  * The DNS server configured on the user's system (can be ISP DNS, public DNS, ...)
2. If it couldn't find a DNS record locally, a full DNS resolution is started.
3. It connects to the server using the TCP protocol
4. The browser sends an HTTP request to the server
5. The server sends an HTTP response back to the browser
6. The browser renders the response (e.g. HTML)
7. The browser then sends subsequent requests as needed to the server to get the embedded links, javascript, images in the HTML and then steps 3 to 5 are repeated.

TODO: add more details!

</details>


<details>
<summary><b>How do you handle configuration drift in a DevOps environment?</b></summary>

*(No answer provided in source)*

</details>

<details>
<summary><b>How do you manage secrets and sensitive data in a DevOps environment?</b></summary>

*(No answer provided in source)*

</details>

<details>
<summary><b>Explain the concept of "Environment Drift" and its impact on DevOps environments</b></summary>

*(No answer provided in source)*

</details>


### API

<details>
<summary><b>Explain what is an API</b></summary>

I like this definition from [blog.christianposta.com](https://blog.christianposta.com/microservices/api-gateways-are-going-through-an-identity-crisis):

"An explicitly and purposefully defined interface designed to be invoked over a network that enables software developers to get programmatic access to data and functionality within an organization in a controlled and comfortable way."

</details>


<details>
<summary><b>What is an API gateway?</b></summary>

An API gateway is like the gatekeeper that controls how different parts talk to each other and how information is exchanged between them.

The API gateway provides a single point of entry for all clients, and it can perform several tasks, including routing requests to the appropriate backend service, load balancing, security and authentication, rate limiting, caching, and monitoring.

By using an API gateway, organizations can simplify the management of their APIs, ensure consistent security and governance, and improve the performance and scalability of their backend services. They are also commonly used in microservices architectures, where there are many small, independent services that need to be accessed by different clients.

</details>

<details>
<summary><b>What are the advantages of using/implementing an API gateway?</b></summary>

Advantages:

  - Simplifies API management: Provides a single entry point for all requests, which simplifies the management and monitoring of multiple APIs.
  - Improves security: Able to implement security features like authentication, authorization, and encryption to protect the backend services from unauthorized access.
  - Enhances scalability: Can handle traffic spikes and distribute requests to backend services in a way that maximizes resource utilization and improves overall system performance.
  - Enables service composition: Can combine different backend services into a single API, providing more granular control over the services that clients can access.
  - Facilitates integration with external systems:  Can be used to expose internal services to external partners or customers, making it easier to integrate with external systems and enabling new business models.

</details>

<details>
<summary><b>What is a Payload in API?</b></summary>

*(No answer provided in source)*

</details>

<details>
<summary><b>What is Automation? How it's related or different from Orchestration?</b></summary>

Automation is the act of automating tasks to reduce human intervention or interaction in regards to IT technology and systems.<br>
While automation focuses on a task level, Orchestration is the process of automating processes and/or workflows which consists of multiple tasks that usually across multiple systems.

</details>

<details>
<summary><b>Tell me about interesting bugs you've found and also fixed</b></summary>

*(No answer provided in source)*

</details>

<details>
<summary><b>What is a Debugger and how it works?</b></summary>

*(No answer provided in source)*

</details>

<details>
<summary><b>What services an application might have?</b></summary>

* Authorization
  * Logging
  * Authentication
  * Ordering
  * Front-end
  * Back-end
  ...

</details>

<details>
<summary><b>What is Metadata?</b></summary>

Data about data. Basically, it describes the type of information that an underlying data will hold.

</details>

<details>
<summary><b>You can use one of the following formats: JSON, YAML, XML. Which one would you use? Why?</b></summary>

I can't answer this for you :)

</details>

### YAML

<details>
<summary><b>What is YAML?</b></summary>

Data serialization language used by many technologies today like Kubernetes, Ansible, etc.

</details>

### Firmware

<details>
<summary><b>Explain what is a firmware</b></summary>

[Wikipedia](https://en.wikipedia.org/wiki/Firmware): "In computing, firmware is a specific class of computer software that provides the low-level control for a device's specific hardware. Firmware, such as the BIOS of a personal computer, may contain basic functions of a device, and may provide hardware abstraction services to higher-level software such as operating systems."

</details>

---

## 💬 Questions To Ask Interviewers

<details>
<summary><b>What do you like about working here?</b></summary>

*(No answer provided in source)*

</details>

<details>
<summary><b>How does the company promote personal growth?</b></summary>

*(No answer provided in source)*

</details>

<details>
<summary><b>What is the current level of technical debt you are dealing with?</b></summary>

Be careful when asking this question - all companies, regardless of size, have some level of tech debt.
Phrase the question in the light that all companies have the deal with this, but you want to see the current
pain points they are dealing with <br>

This is a great way to figure how managers deal with unplanned work, and how good they are at
setting expectations with projects.

</details>

<details>
<summary><b>Why I should NOT join you? (or 'what you don't like about working here?')?</b></summary>

*(No answer provided in source)*

</details>

<details>
<summary><b>What was your favorite project you've worked on?</b></summary>

This can give you insights in some of the cool projects a company is working on, and if
you would enjoy working on projects like these. This is also a good way to see if
the managers are allowing employees to learn and grow with projects outside of the
normal work you'd do.

</details>

<details>
<summary><b>If you could change one thing about your day to day, what would it be?</b></summary>

Similar to the tech debt question, this helps you identify any pain points with the company.
Additionally, it can be a great way to show how you'd be an asset to the team.<br>

For Example, if they mention they have problem X, and you've solved that in the past,
you can show how you'd be able to mitigate that problem.

</details>

<details>
<summary><b>Let's say that we agree and you hire me to this position, after X months, what do you expect that I have achieved?</b></summary>

Not only this will tell you what is expected from you, it will also provide big hint on the type of work you are going to do in the first months of your job.

</details>

---


