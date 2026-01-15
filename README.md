# 🧠 AI Test Factory  
**AI-driven Test & Jira Generation Platform**

This repository contains an AI-powered system that turns test creation from a manual activity into an automated, governed and traceable workflow.

It combines:
- GitHub Copilot
- Cline
- Custom MCPs
- Jira & Xray APIs
- GitHub Actions

To create **standardized test code, Jira issues and Xray artifacts** in minutes instead of hours.

---

## 🚀 What it does

The AI Test Factory allows a QA engineer to create a fully compliant test by simply answering a few guided questions.

The system:
1. Asks for:
   - Target folder
   - Class name
   - Labels
   - Jira Test ID (if exists)
2. If the Jira test exists:
   - It reads it via MCP
   - Extracts steps, data and metadata
3. If it doesn’t exist:
   - It creates the Jira Test
   - Registers it in Xray
   - Applies standards and labels
4. Generates:
   - The test class
   - The test method
   - All required annotations and metadata
5. Moves the Jira issue to “In Progress”

All artifacts are:
- Standardized
- Traceable
- Linked to Jira & Xray
- Ready for CI/CD

---

## 🧬 Why this matters

In enterprise QA:
- Test creation is slow  
- Standards drift  
- Traceability breaks  
- Automation becomes chaotic  

This system solves that by making **the AI enforce the architecture**.

QA engineers no longer decide how tests look.  
The platform does.

---

## 🏗 Architecture

This AI Test Factory is part of a larger Quality Platform:

- GitHub Copilot & Cline act as the user interface  
- MCPs connect to Jira and Xray  
- GitHub Actions orchestrate generation  
- Repositories store the governed code  

Everything is connected through APIs and webhooks.

---

## 🎯 Real-world use

This system is currently used in an enterprise ecommerce environment to:
- Generate new automated tests  
- Create and maintain Jira/Xray artifacts  
- Enforce global QA standards  
- Reduce onboarding time for new QA engineers  

---

## 🧠 What this proves

This is not a demo.  
It is a **production-grade AI-driven QA platform**.

It shows how Quality Engineering can be:
- Automated  
- Governed  
- Scalable  
- And AI-native  
