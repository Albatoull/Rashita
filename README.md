# Rashita
### Medication Management System

<p align="center">
  <img src="assets/rashita-cover.png" width="800">
</p>

## Overview

**Rashita** is a medication management system designed as part of the **CSC343 Software Engineering** course at King Saud University.

The project focuses on designing a mobile healthcare solution that helps users manage their medications, receive medication reminders, check potential drug interactions, locate nearby pharmacies, and manage medicine orders.

The project covers the software engineering design process, including requirements analysis, use case modeling, system architecture, UML diagrams, test design, and user interface prototyping.

> **Note:** Rashita is a conceptual software engineering project. The system was designed and prototyped but was not fully implemented as a functional mobile application.

---

## Key Features

- **Medication Reminders**  
  Schedule medication reminders and receive notifications at the appropriate time.

- **Drug Interaction Checker**  
  Check potential interactions between multiple medications and display interaction severity and details.

- **Nearby Pharmacy Locator**  
  Use location services to find nearby pharmacies through list and map views.

- **Medicine Ordering**  
  Submit medicine orders, upload prescriptions, and provide notes to the pharmacist.

- **Order Management**  
  Track, modify, or cancel medicine orders depending on their processing status.

- **Account Management**  
  Create, update, and manage user account information.

---

## My Contribution

As part of the project team, I contributed to several stages of the software engineering process:

- Participated in writing the project report.
- Contributed to the **Use Case Diagram**.
- Worked on functional requirements **REQ-1 to REQ-5**.
- Worked on non-functional requirements **REQ-5, REQ-7, and REQ-9**.
- Designed selected user interfaces.
- Developed **System Sequence Diagrams**.
- Developed **Sequence Diagrams**.
- Contributed to the **Class Diagram**.
- Created the **Object Diagram**.
- Created the **State Diagram**.

---

## Software Engineering Process

The project followed a structured software engineering design process covering requirements analysis, system modeling, architecture design, testing, and UI prototyping.

### Requirements Analysis

The requirements phase included:

- Functional Requirements
- Non-Functional Requirements
- Stakeholders and Actors
- Customer Requirements
- Use Cases
- Detailed Use Cases

### System Modeling

Several UML and interaction models were created to represent the structure and behavior of the proposed system:

- Use Case Diagram
- Class Diagram
- Object Diagram
- System Sequence Diagrams
- Sequence Diagrams
- Collaboration Diagram
- State Diagram
- Architectural Diagram

### Test Design

Test cases were designed for the system's main services, including:

- Nearby Pharmacy Locator
- Medicine Reminder System
- Drug Interaction Checker
- Order Management
- Medicine Ordering

Both **Unit Testing** and **Integration Testing** scenarios were included in the project.

### User Interface Design

A mobile application prototype was designed to demonstrate the proposed user experience and system functionality.

---

## System Architecture

Rashita was designed using a combination of:

- Layered Architecture
- Client–Server Architecture
- Microservices-style modularity

The proposed architecture separates the user interface, application services, and data layer.

Core services include:

- Medicine Reminder Service
- Drug Interaction Service
- Pharmacy Locator Service
- Medicine Ordering Service

These services interact with a shared database containing user profiles, prescriptions, reminder settings, interaction information, and pharmacy data.

<p align="center">
  <img src="assets/architecture.png" width="700">
</p>

---

## System Design

### Use Case Diagram

The use case model represents the main interactions between the patient and the Rashita system.

<p align="center">
  <img src="assets/use-case-diagram.png" width="650">
</p>

### Class Diagram

The class diagram represents the main system classes, their attributes, operations, and relationships.

<p align="center">
  <img src="assets/class-diagram.png" width="700">
</p>

### Sequence Diagram

Sequence diagrams were developed for major system interactions, including:

- Searching for nearby pharmacies
- Sending medication reminders
- Checking drug interactions
- Sending medicine orders

<p align="center">
  <img src="assets/sequence-diagram.png" width="700">
</p>

---

## Testing

The project included both unit and integration test design for the main system services.

### Unit Testing

Unit testing scenarios focused on individual system functions, including:

- Retrieving the user's location
- Triggering medication reminders
- Managing active orders
- Detecting drug interactions
- Processing medicine orders

### Integration Testing

Integration testing scenarios focused on communication between system components, including:

- Location services and pharmacy data
- Medication schedules and notifications
- Orders and the user database
- Drug interaction checking and report sharing
- Prescription processing and order tracking

---

## UI Prototype

The mobile prototype includes interfaces for:

- Login and Sign Up
- Home Dashboard
- Medication Schedule
- Add Medicine
- Medicine Ordering
- Drug Interaction Checker
- Nearby Pharmacies — List View
- Nearby Pharmacies — Map View

<p align="center">
  <img src="assets/ui-home.png" width="200">
  <img src="assets/ui-pharmacies.png" width="200">
  <img src="assets/ui-map.png" width="200">
</p>

<p align="center">
  <img src="assets/ui-interaction-1.png" width="200">
  <img src="assets/ui-interaction-2.png" width="200">
  <img src="assets/ui-interaction-3.png" width="200">
</p>

---

## Tools

- Canva
- Figma
- Visual Paradigm
- UML

---

## Project Type

Software Engineering Course Project  
CSC343 — Software Engineering  
King Saud University  
2025

---

## About This Repository

This repository serves as a portfolio showcase of the Rashita software engineering project.

It presents selected requirements, system models, architecture diagrams, testing work, and user interface designs to demonstrate the project's software engineering process and design methodology.
