# Abhiram Mandyam — Technical Architecture Portfolio
> **Principal Software Engineer | Staff Developer**
> [LinkedIn](https://www.linkedin.com/in/abhiram-mandyam-8977a355/) | [GitHub](https://github.com/abhirammandyam)

## Overview
This portfolio contains detailed architectural case studies from my 16+ year career in building high-scale distributed systems, financial-grade payments infrastructure, and resilient e-commerce platforms at **Visa** and **Loblaw Digital**.

---

## 🏗️ 1. High-Concurrency Resilience: Ensuring $30M+ BFCM Stability
**Project:** Black Friday Cyber Monday (BFCM) Readiness for Canada's Largest Retailer
**Key Technologies:** GCP, OpenTelemetry, Distributed Systems, Performance Testing

### The Challenge
Ensuring 100% system availability for a multi-billion dollar retail platform during the highest traffic week of the year. Any downtime during BFCM translates to millions in lost revenue and significant brand damage.

### The Architectural Response
*   **DRI Ownership:** Served as the Designated Responsible Individual for cross-layer performance mitigation.
*   **Predictive Hardening:** Led the diagnostic efforts to identify bottlenecks across **Frontshop, BFF, and Core Helios** layers.
*   **Strategic Load Testing:** Designed suites that simulated 10x peak load to identify systemic breaking points.

### Impact
*   **Business:** Enabled **$30 Million+ in revenue** during BFCM week with zero high-severity incidents.
*   **Engineering:** Established the organization's "Resilience North Star" playbook.

---

## 💳 2. The Strangler Pivot: Modernizing Global Payments Core
**Project:**  Legacy Monolith to Microservices Transformation at **Visa**  
**Key Technologies:**  Java Spring Boot, Kubernetes, AWS, Kafka, .NET, API Gateway

### The Challenge
Migrating a mission-critical, monolithic authorization system with strict sub-second latency and zero-downtime requirements.

### The Architectural Response
*   **Strangler Pattern:** Orchestrated a piece-by-piece migration using high-availability API Gateways.
*   **Event-Driven Consistency:** Utilized **Kafka** to synchronize state between legacy and modern environments during the 18-month hybrid phase.
*   **Global Scale:** Managed dependencies across multiple distributed squads to ensure global financial compliance.

### Impact
*   **Velocity:** Enabled **5x faster feature delivery**.
*   **Scale:** Reduced sub-second authorization latency by **40%**.
*   **Uptime:** Achieved **100% uptime** during the entire migration lifecycle.

---

## 📊 3. Systemic Reliability: From Firefighting to Engineering
**Project:** Shoppers Drug Mart Observability Transformation
**Key Technologies:** OpenTelemetry, SRE Patterns, Self-Service Observability

### The Challenge
High-severity site performance issues were being handled via reactive "firefighting," relying on tribal knowledge rather than data.

### The Architectural Response
*   **Observability First:** Championed the integration of **OpenTelemetry** distributed tracing across the entire stack.
*   **Force Multiplier:** Built automated dashboards and self-service diagnostic tools for product squads.
*   **RCA to Hardening:** Transformed Root Cause Analyses (RCAs) into proactive architectural hardening initiatives.

### Impact
*   **Recovery:** Reduced Mean Time to Resolution (MTTR) by **60%**.
*   **Efficiency:** Reduced dependency on central SRE teams by **35%**.

---

## 🎨 4. Platform Leverage: Unifying Experiences via SDUI
**Project:** Server Driven UI (SDUI) Framework Adoption
**Key Technologies:** CMS Integration, Swift (iOS), Kotlin (Android), Next.js (Web)

### The Challenge
Managing inconsistent user experiences and duplicate engineering effort across diverse mobile and web clients for multiple brands.

### The Architectural Response
*   **Backend Orchestration:** Architected a unified layer that manages UI logic and component delivery from a central CMS.
*   **Canonical Patterns:** Defined standardized component contracts to decouple frontend presentation from backend business rules.
*   **Cross-Platform Consistency:** Ensured a "Technical North Star" for 10+ product squads.

### Impact
*   **Delivery:** Reduced time-to-market for new features by **50%**.
*   **Consistency:** Achieved **100% UI parity** across all digital platforms.

---

## 💳 5. Unified Payments & AI Innovation: Orchestrating the "BUY" Domain
**Project:** OneCheckout, PCPay Digital Wallet, and Agentic Ecommerce
**Key Technologies:** Global Payments, Forter, Apple/Google Pay, Google Gemini, ChatGPT, UCP

### The Challenge
Modernizing the checkout experience for Canada's largest retailer required unifying fragmented payment methods, integrating advanced fraud detection, and exploring the next frontier of conversational commerce.

### The Architectural Response
*   **Payment Orchestration:** Managed high-throughput systems interfacing with **Global Payments** and 3rd-party fraud detection (**Forter**).
*   **Unified Digital Wallet:** Architected **PCPay**, an internal wallet integrated with **OneCheckout**, providing a seamless experience across all Loblaw lines of business.
*   **Mobile-First Innovation:** Led the implementation of **Apple Pay and Google Pay**, optimizing for mobile conversion.
*   **Agentic Future:** Pioneering the integration of LLMs (**Gemini/ChatGPT**) with **Universal Commerce Protocol (UCP)** for AI-driven commerce.

### Impact
*   **Conversion:** Significant improvement in checkout success rates via unified address/payment management.
*   **Innovation:** Positioned the organization as a leader in Agentic Ecommerce.
*   **Security:** Enhanced fraud prevention through deeper vendor integration.

---

## 🛠️ Core Skills
*   **Architecture:** Distributed Systems, Microservices, Event-Driven, Cloud Modernization.
*   **Infrastructure:** AWS, GCP, Kubernetes, Docker, Kafka, CI/CD.
*   **Backend:** Java/Spring Boot, Node.js, TypeScript, C#.
*   **Leadership:** DRI, Technical Strategy, Mentorship, Cross-Team Alignment.
