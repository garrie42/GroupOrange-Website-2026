---
layout: page
title: Glossary
---

# Glossary

This glossary defines technical terms and acronyms used throughout the PatientPath project.

---

**PCP — Primary Care Provider**  
A healthcare professional who serves as a patient's main point of contact for general medical care and referrals to specialists.

**EHR — Electronic Health Records**  
Digital systems used by healthcare organizations to store and manage patient medical records.

**HIPAA — Health Insurance Portability and Accountability Act**  
A United States law that establishes standards for protecting sensitive patient health information.

**FHIR — Fast Healthcare Interoperability Resources**  
A healthcare data standard developed by HL7 that enables electronic health records and healthcare systems to exchange data efficiently. PatientPath targets FHIR R4 for interoperability.

**RBAC — Role-Based Access Control**  
A security model that restricts system access based on a user's role within an organization.

**HL7 — Health Level Seven**  
An international standards organization that develops frameworks for the exchange and integration of healthcare information.

**AES-256 — Advanced Encryption Standard (256-bit key)**  
A symmetric encryption algorithm widely used to protect sensitive data at rest. PatientPath uses AES-256 to encrypt stored medical records and audit logs.

**API — Application Programming Interface**  
A defined set of rules that allows software systems to communicate with each other. PatientPath exposes internal APIs and consumes external APIs to support interoperability.

**API Gateway**  
A centralized entry point that manages, authenticates, and routes requests to the appropriate backend services within the PatientPath system.

**CRUD — Create, Read, Update, Delete**  
The four basic operations that can be performed on records stored in a database. PatientPath's CRUD analysis maps each user action to the corresponding database operation.

**ER Diagram — Entity-Relationship Diagram**  
A visual representation of the entities in a database and the relationships between them. PatientPath's ER diagram documents the structure of the data layer.

**IAM — Identity and Access Management**  
A framework of policies and technologies that ensures the right users have the right access to system resources. PatientPath uses IAM to manage provider, patient, and administrator accounts.

**MFA — Multi-Factor Authentication**  
An authentication method that requires users to verify their identity through two or more independent credentials, such as a password combined with a time-based code.

**PostgreSQL**  
An open-source relational database management system used in PatientPath to store patient records, referrals, user accounts, permissions, and audit data.

**Sprint**  
A time-boxed development iteration in an Agile workflow during which a working feature is planned, built, and delivered. PatientPath's development is organized into multiple sprints, each combining UI, logic, and data work.

**TLS 1.3 — Transport Layer Security (version 1.3)**  
A cryptographic protocol that secures data in transit between clients and servers. PatientPath uses TLS 1.3 to protect all network communication.

**TOTP — Time-based One-Time Password**  
A temporary authentication code generated from a shared secret and the current time, typically used as a second factor in MFA.

**UI / UX — User Interface / User Experience**  
UI refers to the visual elements users interact with in a system. UX refers to the overall experience and ease of use of the system. PatientPath's UI/UX mockups illustrate both the visual design and the intended user flow.

**WBS — Work Breakdown Structure**  
A hierarchical decomposition of a project into its phases, deliverables, and sub-tasks. PatientPath's WBS organizes the scope of work required to build and deliver the system.
