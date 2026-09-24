# Enterprise File Monitoring System

## Overview

An enterprise monitoring solution designed to monitor application storage utilization, identify threshold breaches, and provide automated notifications for operational teams.

This case study focuses on backend service implementation, monitoring workflow, data processing, and notification automation.

---

## Role

**Backend Developer**

Responsibilities:

- Developed and maintained backend services
- Implemented monitoring workflow
- Designed data processing logic
- Integrated notification mechanism
- Troubleshot and resolved application issues
- Improved system reliability and maintainability

---

## Technical Stack

### Backend
- C#
- .NET
- Background Service

### Database
- MongoDB

### Integration
- Email Notification
- REST API

### Tools
- Git
- Docker
- Logging Framework

---

## System Features

### Storage Utilization Monitoring

The system periodically monitors application storage utilization and evaluates usage levels based on predefined thresholds.

---

### Automated Notification

When storage utilization reaches the configured threshold, the system automatically generates notifications for the responsible team to perform further action.

---

### Monitoring Workflow

1. Scheduled monitoring process starts
2. System retrieves storage utilization data
3. Utilization percentage is calculated and validated
4. Threshold conditions are evaluated
5. Notification is generated when required

---

## Architecture

```
Application
     |
     |
Monitoring Service
     |
     |
Database
     |
     |
Notification Service
     |
     |
Email Notification
```

---

## Key Challenges

- Building a reliable automated monitoring process
- Managing notification workflow efficiently
- Handling background service execution
- Maintaining data consistency during processing

---

## Result

Implemented a structured monitoring workflow that improves operational visibility, reduces manual monitoring activities, and enables faster response to storage utilization issues.

---

## Note

This repository contains documentation and a case study only. Source code and internal implementation details are not publicly available due to confidentiality and intellectual property restrictions.
