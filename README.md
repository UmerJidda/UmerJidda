# Hey, I'm Umer Jidda 👋

Cloud Security Engineer building security automation and detection engineering systems across AWS and GCP — with active R&D into Azure and Kubernetes security.

Currently at **AnkerCloud**, engineering security and migration automation that compresses multi-day cloud workflows into minutes. Built **Cloud Threat Detection Lab**, a production-quality detection engineering platform spanning AWS telemetry collection through incident response. Designing **CERIP**, a graph-based enterprise risk intelligence platform on Neo4j and MITRE ATT&CK.

---

## What I'm Building

**At AnkerCloud**
- Cloud security assessment automation across AWS and GCP (Prowler, ScoutSuite, AWS Config, Security Hub)
- AWS Well-Architected Framework Review (FTR) automation
- Migration security engineering — pre/post-migration assessments across large-scale cloud migrations
- Terraform IaC generation and infrastructure discovery tooling
- IaC and application security scanning pipelines (SonarQube, Semgrep, Trivy, Checkov)
- **In R&D:** porting Lens automation capabilities to Azure (current 3–6 month KPI)

**Flagship Projects**

- 🔍 [**Cloud-Threat-Detection-Response-Platform**](https://github.com/UmerJidda/Cloud-Threat-Detection-Response-Platform) — Production-quality detection engineering platform: 14 MITRE ATT&CK-mapped Splunk detections across 9 tactics, automated AWS telemetry collection (CloudTrail, GuardDuty, SecurityHub, IAM), alert enrichment, and a complete incident-response playbook library (triage → investigation → containment → recovery).
- 🕸️ [**CERIP**](https://github.com/UmerJidda/CERIP) — Continuous Enterprise Risk Intelligence Platform: graph-based security platform correlating cloud assets, IAM relationships, CI/CD pipelines, and attack paths using Neo4j and MITRE ATT&CK.
- ☸️ [**Production K8s DevSecOps Pipeline**](https://github.com/UmerJidda/production-k8s-devsecops-pipeline) — Kubernetes-native CI/CD pipeline with integrated security scanning and policy enforcement. *(Active build — Kubernetes security focus.)*
- [**GCP Security Audit Tool**](https://github.com/UmerJidda/gcp-security-audit-tool) — Automated GCP security posture assessment tooling
- [**AWS Prowler Audit**](https://github.com/UmerJidda/aws-prowler-audit) — Structured AWS security auditing with Prowler
- [**DevSecOps Secure Pipeline**](https://github.com/UmerJidda/devsecops-secure-pipeline) — Terraform-based CI/CD pipeline with integrated security scanning

---

## Stack

```
Cloud         AWS (CloudTrail, GuardDuty, Security Hub, IAM, Config)  ·  GCP  ·  Azure 
Infra         Terraform  ·  Docker  ·  Kubernetes  ·  GitHub Actions  ·  Linux
Detection     Splunk  ·  SPL  ·  MITRE ATT&CK  ·  Detection-as-Code  ·  Alert Enrichment
Security      Prowler  ·  ScoutSuite  ·  Semgrep  ·  Trivy  ·  Checkov  ·  pip-audit
Dev           Python  ·  boto3  ·  FastAPI  ·  Bash  ·  SQL  ·  REST APIs
Data          Neo4j  ·  PostgreSQL
Frameworks    MITRE ATT&CK  ·  STRIDE  ·  CIS Controls  ·  ISO 27001  ·  NIST CSF
```

---

## 6–12 Month Roadmap

**Detection Engineering**
- [ ] Cloud Threat Detection Lab Phase 6 — automated response (Lambda-based IAM key revocation, EC2 isolation) triggered via Splunk Adaptive Response
- [ ] CI/CD pipeline running detection validation on every PR to prevent regressions
- [ ] Threat intelligence enrichment (IP reputation) integrated into alert pipeline

**Cloud Security**
- [ ] AWS Certified Security Specialty (SCS-C02)
- [ ] Azure security automation R&D — extending Lens automation capabilities to Azure (current AnkerCloud KPI)
- [ ] Extend GCP audit tooling with Cloud Asset Inventory integration and CIS Benchmark mapping

**Kubernetes & Red Team**
- [ ] Complete Production K8s DevSecOps Pipeline — policy-gate enforcement, image scanning
- [ ] Kubernetes security — RBAC hardening, admission control, cluster attack surface
- [ ] Red team fundamentals — building toward offensive security depth alongside detection engineering

**Security Architecture**
- [ ] CERIP Phase 1 — functional attack path enumeration across 10 MITRE ATT&CK-aligned patterns (Neo4j/Cypher)
- [ ] CERIP risk scoring: Likelihood × Impact × Reachability with Architecture Decision Records per component

---

## Certifications

- AWS Certified Solutions Architect – Associate (SAA-C03)
- EC-Council Certified Ethical Hacker v12 (CEH)
- EC-Council Certified Network Defender v2 (CND)
- TryHackMe DevSecOps 

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-umer--jidda-blue?style=flat&logo=linkedin)](https://linkedin.com/in/umer-jidda)
