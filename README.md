# 🌿 HEXABYTE - Ayurvedic Nutrient & Diet Management Software

<div align="center">

![HEXABYTE Logo](https://img.shields.io/badge/HEXABYTE-Ayurvedic%20Nutrition%20Platform-green?style=for-the-badge&logo=leaf)

**Smart India Hackathon 2025 | Problem Statement ID: SIH25024**

*Comprehensive Cloud-Based Practice Management & Nutrient Analysis Software for Ayurvedic Dietitians*

[![Team Hexabyte](https://img.shields.io/badge/Team-Hexabyte-blue?style=flat-square)](https://github.com/arunpranav-at/SIH25024-Hexabyte-Prototype)
[![SIH 2025](https://img.shields.io/badge/SIH-2025-orange?style=flat-square)](https://sih.gov.in)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)
[![Node.js](https://img.shields.io/badge/Node.js-18%2B-green?style=flat-square&logo=node.js)](https://nodejs.org)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0%2B-blue?style=flat-square&logo=typescript)](https://www.typescriptlang.org)
[![React](https://img.shields.io/badge/React-18%2B-blue?style=flat-square&logo=react)](https://reactjs.org)

</div>

---

## 🎯 Project Overview

HEXABYTE is a revolutionary cloud-first, multi-tenant practice management and nutrient analysis platform specifically designed for Ayurvedic dietitians. Our platform bridges the gap between traditional Ayurvedic principles and modern digital healthcare solutions, providing a comprehensive ecosystem for practitioners, patients, and healthcare administrators.

### 🌟 Key Highlights

- **🔬 Intelligent Food Analysis**: Advanced food scanning and nutrient mapping with AI/ML
- **📊 Ayurvedic Knowledge Integration**: Neo4j-powered knowledge graph for traditional wisdom
- **🏥 Healthcare Integration**: ABHA-linked health records and HPR-verified practitioners
- **📱 Multi-Platform Support**: React Native mobile apps and React web applications
- **⚡ Microservices Architecture**: Scalable, maintainable, and robust backend services
- **🔐 Enterprise Security**: Comprehensive security with encryption and audit trails

---

## 🏆 Team Information

**Team ID**: SIH71816  
**Team Name**: Hexabyte  
**Institution**: Chennai Institute of Technology

## 🔍 Problem Statement

**ID**: SIH25024  
**Title**: Comprehensive Cloud-Based Practice Management & Nutrient Analysis Software for Ayurvedic Dietitians, Tailored for Ayurveda-Focused Diet Plans  
**Theme**: MedTech / BioTech / HealthTech  
**Category**: Software

### 🎯 Challenges Addressed

- **Manual Process Inefficiency**: Eliminating handwritten diet charts and time-consuming nutrient calculations
- **Lack of Standardization**: Creating digital standardized records for Ayurvedic practices
- **Credential Verification**: Implementing HPR-based practitioner authentication
- **Patient Adherence**: Improving treatment compliance through digital engagement
- **Multi-Center Management**: Enabling seamless record sharing across healthcare centers
- **Analytics Gap**: Providing comprehensive insights into patient outcomes and treatment effectiveness

---

## 💡 Solution Overview

HEXABYTE delivers a comprehensive digital transformation for Ayurvedic nutrition practice through eight core modules:

### 🔧 Core Features

1. **🥗 Nutrition Data Service**
   - Comprehensive food database with USDA and Indian Nutrient DB integration
   - Real-time food scanning and nutrient analysis
   - Standardized nutrition metrics per 100g and serving sizes

2. **📋 Personalized Diet Planning**
   - AI-powered diet chart generation based on Ayurvedic principles
   - Dosha-specific recommendations (Vata, Pitta, Kapha)
   - Seasonal adjustments and constitution-based planning

3. **📊 Advanced Analytics Dashboard**
   - Patient progress tracking and outcome analytics
   - Practitioner performance insights
   - Clinic operational dashboards

4. **🔔 Smart Notifications**
   - Automated appointment and medication reminders
   - Multi-channel communication (SMS, Email, Push)
   - Practitioner-patient interaction platform

5. **🏥 ABHA-Linked Health Records**
   - Secure, interoperable patient data management
   - Government health account integration
   - Comprehensive medical history tracking

6. **💬 Virtual Consultations**
   - Video/audio/chat-based teleconsultations
   - Secure communication channels
   - Appointment scheduling and management

7. **✅ Verified Practitioner Network**
   - HPR ID-based authenticity verification
   - Professional credential management
   - Quality assurance protocols

8. **🍽️ Personalized Food Recommendations**
   - Practitioner-approved food suggestions
   - Integration with food delivery platforms
   - Customized meal planning

---

### 🌐 Frontend Architecture

- **📱 Mobile Applications**: React Native with TypeScript
  - Cross-platform iOS/Android support
  - Offline-first data synchronization
  - Biometric authentication support

- **💻 Web Applications**: Next.js with TypeScript
  - Server-side rendering for optimal performance
  - Progressive Web App (PWA) capabilities
  - Responsive design for all devices

- **⚙️ Admin Dashboards**: React with Material-UI
  - Real-time data visualization
  - Advanced filtering and search capabilities
  - Role-based access control

### ⚙️ Backend Architecture

- **🚪 API Gateway**: Node.js with Express/NestJS
  - JWT-based authentication
  - Rate limiting and request validation
  - API versioning and documentation

- **🔐 Authentication Service**: 
  - Multi-factor authentication
  - RBAC (Role-Based Access Control)
  - OAuth 2.0 integration

### 🗄️ Data Layer

| Database | Use Case | Technology |
|----------|----------|------------|
| **PostgreSQL** | Nutrition data, user management, transactions | Relational ACID compliance |
| **MongoDB** | Patient records, documents, flexible schemas | Document-based NoSQL |
| **Neo4j** | Ayurvedic knowledge graph, relationships | Graph database |
| **Redis** | Caching, session management, rate limiting | In-memory data store |

### 🔌 External Integrations

- **USDA Food Database**: Comprehensive nutrition data
- **Indian Nutrient Database**: Localized food information
- **Google Gemini API**: AI-powered recommendations
- **ABHA Integration**: Government health records
- **HPR Verification**: Practitioner authentication
- **Communication APIs**: Twilio, SendGrid, FCM

---

## 📱 Features

### 👨‍⚕️ For Practitioners

- **📊 Comprehensive Dashboard**: Patient management, appointment scheduling, analytics
- **📝 Digital Prescriptions**: Ayurvedic diet chart generation with customizable templates
- **🔍 Patient Insights**: Progress tracking, adherence monitoring, outcome analysis
- **📚 Knowledge Base**: Integrated Ayurvedic principles and modern nutrition science
- **💬 Teleconsultation**: Secure video/audio consultations with recording capabilities
- **📈 Practice Analytics**: Revenue tracking, patient demographics, treatment efficacy

### 👥 For Patients

- **📱 Personal Health App**: Comprehensive health profile management
- **🥗 Food Scanning**: AI-powered food recognition and nutritional analysis
- **📋 Custom Diet Plans**: Personalized Ayurvedic meal plans based on constitution
- **⏰ Smart Reminders**: Medication, meal, and appointment notifications
- **📊 Progress Tracking**: Visual progress reports and goal achievement metrics
- **💬 Direct Communication**: Secure messaging with healthcare providers

### 🏥 For Administrators

- **📈 Business Intelligence**: Multi-location analytics and performance metrics
- **👥 User Management**: Practitioner verification, patient enrollment, access control
- **💰 Financial Management**: Billing, revenue tracking, subscription management
- **🔧 System Configuration**: Platform settings, integration management
- **📊 Compliance Monitoring**: HIPAA, ABHA compliance tracking
- **🛠️ Technical Administration**: System health, performance monitoring

---

## 🗂️ Project Structure

```
SIH25024-Hexabyte-Prototype/
├── 📁 backend/                    # Backend services
│   ├── 📁 api-gateway/           # Main API gateway service
│   │   ├── src/
│   │   │   ├── index.ts          # Gateway entry point
│   │   │   ├── config/           # Configuration files
│   │   │   └── routes/           # Route definitions
│   │   ├── package.json
│   │   └── tsconfig.json
│   │
│   ├── 📁 auth-service/          # Authentication & authorization
│   │   ├── src/
│   │   │   ├── controller/       # Auth controllers
│   │   │   ├── models/           # User models (Admin, Doctor, Patient)
│   │   │   ├── routes/           # Auth routes
│   │   │   ├── services/         # Auth business logic
│   │   │   └── strategies/       # Authentication strategies
│   │   └── package.json
│   │
│   └── 📁 nutritional-analysis-service/  # Food & nutrition analysis
│       ├── src/
│       │   ├── controller/       # Food analysis controllers
│       │   └── routes/           # Nutrition API routes
│       └── package.json
│
├── 📁 frontend/                   # Frontend applications
│   ├── src/
│   │   ├── 📁 app/               # Next.js app directory
│   │   │   ├── page.tsx          # Home page
│   │   │   ├── layout.tsx        # Root layout
│   │   │   ├── 📁 admin/         # Admin dashboard pages
│   │   │   ├── 📁 auth/          # Authentication pages
│   │   │   ├── 📁 doctor/        # Practitioner portal
│   │   │   └── 📁 user/          # Patient portal
│   │   │
│   │   ├── 📁 components/        # Reusable UI components
│   │   │   ├── 📁 common/        # Shared components
│   │   │   └── 📁 ui/            # UI library components
│   │   │
│   │   ├── 📁 contexts/          # React contexts
│   │   ├── 📁 lib/               # Utility libraries
│   │   │   ├── 📁 api/           # API client functions
│   │   │   ├── data.ts           # Data utilities
│   │   │   └── utils.ts          # Helper functions
│   │   │
│   │   └── 📁 types/             # TypeScript type definitions
│   │
│   ├── 📁 public/                # Static assets
│   ├── package.json
│   ├── next.config.ts
│   └── tsconfig.json
│
├── 📁 docs/                      # Documentation
├── 📁 scripts/                   # Build and deployment scripts
├── 📁 tests/                     # Test suites
├── .gitignore
├── LICENSE
└── README.md
```

---

## 🚀 Getting Started

### 📋 Prerequisites

Before setting up the project, ensure you have the following installed:

- **Node.js**: Version 18.0 or higher
- **Python**: Version 3.9 or higher (for ML services)
- **Docker**: Latest stable version
- **Git**: Version control
- **PostgreSQL**: Version 14+ (for local development)
- **MongoDB**: Version 5+ (for document storage)
- **Redis**: Version 6+ (for caching)

### 🔧 Environment Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/arunpranav-at/SIH25024-Hexabyte-Prototype.git
   cd SIH25024-Hexabyte-Prototype
   ```

2. **Install Dependencies**
   ```bash
   # Install backend dependencies
   cd backend/api-gateway && npm install
   cd ../auth-service && npm install
   cd ../nutritional-analysis-service && npm install
   
   # Install frontend dependencies
   cd ../../frontend && npm install
   ```

### 🚀 Running the Application

1. **Start Backend Services**
   ```bash
   # Terminal 1: API Gateway
   cd backend/api-gateway
   npm run dev
   
   # Terminal 2: Auth Service
   cd backend/auth-service
   npm run dev
   
   # Terminal 3: Nutrition Service
   cd backend/nutritional-analysis-service
   npm run dev
   ```

2. **Start Frontend Application**
   ```bash
   # Terminal 4: Frontend
   cd frontend
   npm run dev
   ```
