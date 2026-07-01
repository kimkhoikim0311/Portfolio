# 🎬 Beta Cinema — Booking Reliability Enhancement Initiative

---

## Project Overview

### Background

Beta Cinema is an online movie ticket booking application that allows customers to select seats, make payments, and receive electronic tickets.

Through analysis of user feedback, several issues were identified in the booking and payment process, including seat reservation inconsistencies and ticket issuance failures after successful payment.

### Problem Statements

**Problem 1 (Self-locking seat defect):** Users are blocked from re-selecting their own previously chosen seats if they navigate back or exit during the checkout phase. The system retains a "Blind Lock" on the seats for 10 minutes without validating whether the returning user is the original holder.

**Problem 2 (Unissued tickets post-payment):** Users complete successful monetary deductions via third-party payment gateways (e.g., MoMo, ZaloPay), but zero ticket issuance occurs.

### Project Objective

The project is conducted with the aim of optimizing the ticket booking system within the Beta Cinema application. By re-engineering the seat-locking mechanism and asynchronous payment handling, the project targets to eliminate transactional data loss, lower customer churn rates, and maximize seat occupancy efficiency for theater operations.

---

## My Role

Business Analyst

---

## Responsibilities

- Analyze business problems and user feedback
- Identify root causes
- Define business rules and requirements
- Design business process flows
- Create system interaction diagrams
- Design data models
- Develop UAT test cases mapped to all functional requirements

---

## Key Deliverables

### Business Analysis
- Business rules
- Functional requirements
- Non-functional requirements
- Use case specification

### System Analysis
- UML Use case diagram
- UML Activity diagram
- UML Sequence diagram
- Entity relationship diagram (ERD)

### Documentation
- <a href="https://drive.google.com/file/d/1mrCOmCXlxPmVr3WBaJZbZhPYA-E-jmRv/view?usp=sharing" target="_blank">📄 Business and System Requirements Document</a>
- <a href="https://drive.google.com/file/d/1e0sQsCAoWfCl9FwLKfKt1OhhvEZ-DSMc/view?usp=sharing" target="_blank">📋 UAT Test Cases</a>

