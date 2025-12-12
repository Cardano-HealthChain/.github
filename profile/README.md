# Welcome to the HealthChain Venture

**Powered by the Cardano blockchain, HealthChain gives you full control over your medical records—securely stored, shared only with your consent, and supported by real-time health alerts that keep your community safe.**

---
![HealthChain App](https://github.com/Cardano-HealthChain/.github/blob/main/profile/healthchain.png)

![HealthChain App](https://github.com/Cardano-HealthChain/.github/blob/main/profile/healthchain1.png)

![HealthChain App](https://github.com/Cardano-HealthChain/.github/blob/main/profile/healthchain2.png)


### About Our Project

HealthChain is a mobile-first platform designed to solve critical health infrastructure gaps, particularly in developing regions. Our mission is to build a secure, low-cost digital ecosystem that addresses:

* **Lack of Records:** Replacing unreliable paper records with a consistent, user-owned digital health history.
* **Poor Emergency Response:** Providing a reliable, real-time tool for health authorities to issue alerts during outbreaks.
* **Low Data Reliability:** Creating a trustworthy, auditable data layer for public health decisions.

### Our Strategic Goals

Our development is guided by three core principles:

1.  **Empowerment:** To shift health record ownership from institutions to the individual user.
2.  **Efficiency:** To provide a reliable, real-time mechanism for public health officials to issue alerts and track aggregated data.
3.  **Sustainability:** To leverage low-cost, secure blockchain infrastructure (Cardano) suitable for regions with limited economic or technical constraints.

### Our Technology Stack

HealthChain is a multi-disciplinary system built on a modern, decentralized stack:

* **Blockchain:** **Cardano**
* **Identity Layer:** **Atala PRISM** (for Decentralized Identifiers and Verifiable Credentials)
* **Smart Contracts:** **Aiken** (for on-chain permissioning and governance)
* **Frontend:** **Next.js, TypeScript, & Tailwind** (as a Mobile-first PWA)
* **AI Assistant:** **Gemini API** with Google Search grounding (for the HealthChain Assistant)

### Repository Guide

Our work is organized into several dedicated repositories. Here’s a guide to finding what you need:

* **`frontend-pwa`**: The primary user-facing application. This includes the **Resident PWA**, the **Clinic Web App**, and the **Health Authority Dashboard**.
* **`api-service`**: The backend API gateway and off-chain services. This handles data encryption, off-chain storage, and the push notification service for alerts.
* **`aiken-contracts`**: All Cardano smart contracts. This includes the Clinic DID Registry and the core VC Permissioning scripts.
* **`ml-assistant`**: The service handler for the "HealthChain Assistant" AI chatbot, managing integration with the Gemini API.
* **`product-docs`**: The central source of truth for the project, containing our Product Requirements Document (PRD), MVP plans, and high-level architecture.

### Project Status

**Current Phase: Concept & MVP Development**

We are actively building the Minimum Viable Product (MVP) and are focused on validating the core user journey: a Resident owning their record, a Clinic writing to it, and an Authority issuing an alert.

