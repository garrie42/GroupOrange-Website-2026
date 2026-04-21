---
layout: page
title: Deliverables
---

# Project Deliverables

This section presents the key artifacts created during the PatientPath project across both the Feasibility and Design phases.
Each deliverable provides a visual representation of a different aspect of the system design, workflow improvement, project structure, or risk analysis.

---

## Feasibility Deliverables

These artifacts were developed during the Feasibility phase to establish the problem space, propose the solution, and evaluate early project risks and competitive positioning.

### Current Process Flow

The current healthcare record transfer process often relies on manual coordination and fax-based communication between providers.
This process can result in delayed information exchange, missing documents, and additional administrative work for healthcare staff.

The diagram below illustrates the typical workflow involved in transferring patient records between a primary care provider and a specialist.

<img src="assets/img/current-process-flow.png" style="width:100%; max-width:900px;">

---

### Solution Process Flow

PatientPath replaces fax-based communication with a secure digital platform that allows providers to share and access medical records instantly.

The solution workflow demonstrates how PatientPath simplifies the referral process by enabling providers to securely grant access to patient records and track document transfers in real time.

<img src="assets/img/solution-process-flow.png" style="width:100%; max-width:900px;">

---

### Major Functional Components Diagram (MFCD)

The Major Functional Components Diagram (MFCD) illustrates the architectural structure of the PatientPath system.

This diagram highlights the major system layers, including:

- Presentation Layer (user interfaces such as provider dashboards and patient portals)
- Application Layer (core services such as record management and authentication)
- Data Layer (secure storage of medical records, audit logs, and system data)

Together, these components form the core architecture required to support secure medical document exchange.

<img src="assets/img/mfcd.png" style="width:100%; max-width:900px;">

---

### Competition Matrix

The competition matrix compares PatientPath with existing healthcare communication approaches such as fax-based record transfer and traditional electronic health record (EHR) systems.

This comparison highlights how PatientPath focuses specifically on secure interoperability and cross-organization communication, addressing gaps that exist in many current solutions.

<img src="assets/img/competition-matrix.png" style="width:100%; max-width:900px;">

---

### Risk Assessment Matrix

The risk matrix identifies potential project risks and evaluates them based on two factors:

- Likelihood of occurrence
- Potential impact on the project

This analysis helps the team identify which risks require mitigation strategies and ensures that technical, legal, and customer-related concerns are considered during the development process.

<img src="assets/img/risk-matrix.png" style="width:100%; max-width:900px;">

---

## Design Deliverables

These artifacts were developed during the Design phase to define the technical structure, feature set, user workflows, database, algorithms, interfaces, and development plan for PatientPath.

### Feature Table

The feature table enumerates each PatientPath feature along with its description, associated UI screen, underlying database or API dependency, and mapped user story.
Due to its size, the feature table is presented across three sections covering user-facing core features, user-facing visibility and security features, and system and architecture components.

<img src="assets/img/feature-table-1.png" style="width:100%; max-width:900px; margin-bottom: 12px;">
<img src="assets/img/feature-table-2.png" style="width:100%; max-width:900px; margin-bottom: 12px;">
<img src="assets/img/feature-table-3.png" style="width:100%; max-width:900px;">

---

### Work Breakdown Structure (WBS)

The Work Breakdown Structure decomposes the PatientPath project into its major phases and sub-tasks, providing a hierarchical view of the work required to deliver the full system.

<img src="assets/img/wbs-diagram.png" style="width:100%; max-width:900px;">

---

### Database Schema

The database schema defines the structure of the PatientPath data layer, including entities, relationships, primary and foreign keys, and supporting tables for referrals, users, records, audit logs, and role-based access control.

<img src="assets/img/database-schema.png" style="width:100%; max-width:900px;">

---

### Algorithms

The algorithms deliverable captures seven core logic flows within PatientPath, including CRUD operations and the step-by-step sequences that drive key workflows such as referral creation, record upload, consent management, access control, and audit logging.

<img src="assets/img/algorithms-1.png" style="width:100%; max-width:900px; margin-bottom: 12px;">
<img src="assets/img/algorithms-2.png" style="width:100%; max-width:900px; margin-bottom: 12px;">
<img src="assets/img/algorithms-3.png" style="width:100%; max-width:900px; margin-bottom: 12px;">
<img src="assets/img/algorithms-4.png" style="width:100%; max-width:900px; margin-bottom: 12px;">
<img src="assets/img/algorithms-5.png" style="width:100%; max-width:900px; margin-bottom: 12px;">
<img src="assets/img/algorithms-6.png" style="width:100%; max-width:900px; margin-bottom: 12px;">
<img src="assets/img/algorithms-7.png" style="width:100%; max-width:900px;">

---

### UI/UX Mockups

The UI/UX mockups illustrate the intended user experience for PatientPath's primary workflows. Each mockup represents a key screen that users interact with during referral, record exchange, and account management tasks.

<div style="display:grid; grid-template-columns:repeat(auto-fit, minmax(280px, 1fr)); gap:16px; max-width:900px;">
  <img src="assets/img/ui-mockup-1.png" style="width:100%; border:1px solid #e5e7eb; border-radius:8px;">
  <img src="assets/img/ui-mockup-2.png" style="width:100%; border:1px solid #e5e7eb; border-radius:8px;">
  <img src="assets/img/ui-mockup-3.png" style="width:100%; border:1px solid #e5e7eb; border-radius:8px;">
  <img src="assets/img/ui-mockup-4.png" style="width:100%; border:1px solid #e5e7eb; border-radius:8px;">
</div>

<!--
  To add more mockups, duplicate an <img> line above and increment the number
  (ui-mockup-5.png, ui-mockup-6.png, etc.). To remove unused ones, delete
  the corresponding <img> lines.
-->

---

### Sprint Plan

The sprint plan lays out the development roadmap for PatientPath across multiple sprints. Each sprint delivers a working feature by combining UI, logic, and data components together rather than isolating them by layer.

<img src="assets/img/sprint-plan-1.png" style="width:100%; max-width:1100px; margin-bottom: 12px;">
<img src="assets/img/sprint-plan-2.png" style="width:100%; max-width:1100px;">

---

### External Interface APIs

The external interface APIs table documents each third-party or system-level API that PatientPath integrates with, including its purpose, expected inputs, and expected outputs.

<img src="assets/img/external-apis.png" style="width:100%; max-width:900px;">

---

### Development Tools & Dependencies

This deliverable lists the frameworks, libraries, databases, and supporting tools used to develop PatientPath, along with the role each plays in the overall system. Due to its size, the breakdown is presented across six sections.

<img src="assets/img/dev-tools-1.png" style="width:100%; max-width:900px; margin-bottom: 12px;">
<img src="assets/img/dev-tools-2.png" style="width:100%; max-width:900px; margin-bottom: 12px;">
<img src="assets/img/dev-tools-3.png" style="width:100%; max-width:900px; margin-bottom: 12px;">
<img src="assets/img/dev-tools-4.png" style="width:100%; max-width:900px; margin-bottom: 12px;">
<img src="assets/img/dev-tools-5.png" style="width:100%; max-width:900px; margin-bottom: 12px;">
<img src="assets/img/dev-tools-6.png" style="width:100%; max-width:900px;">
