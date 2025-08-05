# 🚀 Salesforce Basics Notes(05/08/25)

📘 A structured summary of key Salesforce concepts, tools, and best practices—compiled from lectures and personal learning.  
🧠 Maintained by **Apurva** as part of my technical documentation journey.

---

## 📌 Table of Contents

1. [CRM & Salesforce Overview](#crm--salesforce-overview)
2. [Objects in Salesforce](#objects-in-salesforce)
3. [Users, Profiles, Roles](#users-profiles-roles)
4. [Automation Tools](#automation-tools)
5. [Configuration vs Customization](#configuration-vs-customization)
6. [Reports & Dashboards](#reports--dashboards)
7. [Summary](#summary)

---

## 🌐 CRM & Salesforce Overview

- **CRM (Customer Relationship Management)**: A system to manage customer interactions, improve relationships, and drive growth.
- **Salesforce**: A leading cloud-based CRM platform offering tools for sales, service, marketing, and app development.

---

## 📦 Objects in Salesforce

### 🔹 Standard Objects
Predefined by Salesforce:
- `Account`, `Contact`, `Lead`, `Opportunity`, `Case`

### 🔸 Custom Objects
Created by users to meet specific needs:
- Use **CamelCase** naming (e.g., `TaskItem__c`, `StudentProfile__c`)
- Fully customizable: fields, relationships, layouts

### 🧩 Object Types
| Type             | Description                                  |
|------------------|----------------------------------------------|
| Standard Objects | Built-in (e.g., `Account`, `Contact`)        |
| Custom Objects   | User-defined (e.g., `TaskItem__c`)           |
| External Objects | Linked to external data sources              |

---

## 👤 Users, Profiles, Roles

### 🧑‍💼 Users
- Individuals with login access to Salesforce

### 🛡️ Profiles
- Define **what users can do**
- Control object access, field-level security, tab visibility

### 🏢 Roles
- Define **what users can see**
- Control record-level visibility via role hierarchy

### 🧩 Permission Sets
- Extend access beyond profile limits
- Users can have multiple permission sets

---

## ⚙️ Automation Tools

| Tool             | Type      | Use Case                          |
|------------------|-----------|-----------------------------------|
| **Flow Builder** | No-code   | Modern automation (recommended)   |
| **Workflow Rules** | No-code | Legacy automation (simple tasks)  |
| **Apex Triggers** | Pro-code | Advanced logic and integrations   |

### 🔄 Flow Builder
- Record-triggered, scheduled, and screen flows
- Looping, branching, decision logic
- Fast and flexible

### 🔧 Apex Triggers
- Written in Apex code
- Ideal for complex logic, cross-object updates, and recursion

---

## 🛠️ Configuration vs Customization

| Aspect            | Configuration 🧩         | Customization 🔧         |
|-------------------|--------------------------|--------------------------|
| Skill Level       | Admin-friendly (no code) | Developer-level (code)   |
| Tools Used        | UI, fields, layouts       | Apex, LWC, APIs          |
| Examples          | Validation rules, reports | Triggers, custom UI      |

---

## 📊 Reports & Dashboards

### 📋 Reports
- Tabular data with filters, summaries, and charts
- Used for analysis and tracking

### 📈 Dashboards
- Visual display of multiple reports
- Includes charts, metrics, tables

---

## ✅ Summary

This document covers:
- CRM fundamentals
- Salesforce objects (standard & custom)
- User access (profiles, roles, permission sets)
- Automation tools (Flow, Workflow, Apex)
- Configuration vs Customization
- Reports and Dashboards

---

📌 *Maintained by Apurva — documenting my Salesforce learning journey.*
