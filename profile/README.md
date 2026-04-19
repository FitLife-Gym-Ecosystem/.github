# 🏋️‍♂️ FitLife - Enterprise Smart Gym Ecosystem

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Architecture: Decoupled](https://img.shields.io/badge/Architecture-Decoupled_Client_Server-blue.svg)]()
[![Status: Active Development](https://img.shields.io/badge/Status-Active-success.svg)]()

> A Next-Generation Gym Management Ecosystem powered by AI (Google Gemini), automated secure payments (VNPay), and high-performance operations designed for scalability.

## 🌟 The Vision & Business Value
Traditional gym management software often struggles with peak-hour bottlenecks and lacks true personalization. **FitLife** is architected to solve these real-world enterprise challenges:
- **Zero-Friction Operations:** Eliminates front-desk queues with a `<100ms` Smart Check-in system and automated IoT-ready locker assignments.
- **Hyper-Personalization at Scale:** Leverages LLM (Google Gemini AI) to act as a virtual NASM-certified coach, generating zero-shot JSON workout and nutrition plans for thousands of members without manual intervention.
- **Financial Integrity:** 100% cashless transactions secured by HMAC SHA-512 checksum algorithms.

## 🏗️ System Architecture
As the foundational step towards a Microservices architecture, FitLife is currently deployed as a highly decoupled N-tier ecosystem. 

<img width="1690" height="1049" alt="system_architecture" src="https://github.com/user-attachments/assets/47114fe3-c98a-4462-a5a8-ff515c0e7246" />

## 📦 Ecosystem Repositories
To ensure independent scaling, maintainability, and clean CI/CD pipelines in the future, the source code is split into dedicated repositories:

| Module | Tech Stack | Responsibility | Repository Link |
| :--- | :--- | :--- | :--- |
| **🧠 Core Backend API** | Java 17, Spring Boot 3, MySQL 8, Redis | Business logic, Security, DB Transactions, API Contracts | [FitLife-Backend](https://github.com/FitLife-Gym-Ecosystem/fitlife-backend) |
| **🎨 Web Client (Admin/User)** | ReactJS (Vite), TailwindCSS, Zustand | UI/UX, State Management, API Consumption | [FitLife-Frontend](https://github.com/FitLife-Gym-Ecosystem/fitlife-frontend) |

*(Future Scope: Real-time Notification Service & Data Analytics Service will be introduced in Phase 2).*

## 🚀 Live Demo & API Documentation
- **Web Application:** `[Link Vercel/Frontend Live Demo - Pending Sprint 4]`
- **API Swagger UI (OpenAPI 3.0):** `[Link Render/Backend Swagger - Pending Sprint 4]`

## 👨‍💻 Chief Architect & Lead Developer
This ecosystem is designed and developed by **Le Quang Huy**.

Driven by the ambition to evolve into a **Solution Architect**, I built FitLife to translate academic software engineering principles into a robust, market-ready enterprise product.


📫 **Connect with me:**
- **Developer Profile:** [github.com/lqhuy03](https://github.com/lqhuy03)
- **LinkedIn:** https://www.linkedin.com/in/huy-le-java/
