# 🧾 IAM Deep Dive & Labs

## 🎯 Purpose
A complete identity and access management (IAM) security toolkit — from fundamentals to advanced misconfiguration attack paths, detection, and hands-on simulation.

IAM is the beating heart of modern security. This repo teaches you how to configure it, break it, and defend it.

## 🔐 Topics Covered

### 🔰 IAM Fundamentals
- AuthN vs AuthZ
- IAM models (RBAC, ABAC, PBAC)
- Users, groups, roles, tokens
- Cross-cloud IAM comparison (AWS, Azure, GCP)

### 🚨 Advanced IAM Attacks
- Role assumption abuse
- Wildcard + trust policy pitfalls
- Access path chaining
- Token forgery or misuse

### 🧪 Labs
- Simulate RBAC in local apps
- Simulate misconfigured cloud IAM (LocalStack)
- JWT scope-based escalation
- IAM policy static analysis script

### 🛡️ IAM Hardening
- Least privilege policies with Terraform
- Role-based access boundaries
- SCPs and permission boundaries
- IAM environment isolation (dev vs prod)

### 📉 Detection & Defense
- CloudTrail + SIEM logic
- Detection of anomalous login/access patterns
- Common weak IAM configs

## ✅ To Do
- [ ] Add support for Okta/Auth0 delegated roles
- [ ] Build IAM misconfig CTF challenge mode
- [ ] Add integration with Sigma or OSQuery for detection

## 📂 Use Cases
- Red + blue team IAM training
- Interview prep for security engineering
- Cloud security auditing drills
- Detection engineering prototyping

## 📄 License
MIT
