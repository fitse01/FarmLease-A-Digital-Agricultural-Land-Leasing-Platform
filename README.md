
# FarmLease: A Digital Agricultural Land Leasing Platform

![FarmLease Banner](https://via.placeholder.com/800x200?text=FarmLease)  
*A full-stack digital platform for transparent and efficient agricultural land leasing in Ethiopia.*

## 📋 Project Overview

**FarmLease** is a comprehensive web-based platform designed to modernize agricultural land leasing by connecting verified farming clusters with investors. 

The system addresses key challenges in Ethiopia’s agricultural sector such as informal agreements, lack of transparency, and limited access to verified land data by providing a secure, cluster-based, AI-enhanced digital solution.

Developed as a final year Bachelor’s project at **Adama Science and Technology University**, Department of Computer Science and Engineering.

## ✨ Key Features

### Core Modules
- **Authentication & RBAC** – Secure login with role-based access (Investor, Farmer, Cluster Representative, Admin)
- **Cluster & Land Management** – Registration and verification of farming clusters with geospatial data (maps & coordinates)
- **Proposal & Negotiation** – Submit proposals, negotiate terms, and communicate via built-in messaging
- **Digital Agreements** – Automated agreement generation with simulated digital signing
- **Payment Verification** – Receipt upload and verification system compliant with national financial regulations
- **AI-Powered Tools** – Intelligent chatbot for recommendations and AI-based cost, yield & ROI prediction
- **Communication System** – In-app messaging and meeting scheduler
- **Admin Dashboard** – Oversight, audit logs, and verification management

## 🛠️ Tech Stack

- **Frontend**: React.js / Next.js
- **Backend**: Django or Node.js
- **Database**: PostgreSQL (with PostGIS for geospatial data)
- **AI/ML**: Python (Scikit-learn / TensorFlow)
- **Maps**: Leaflet.js or Google Maps
- **Others**: JWT Authentication, RBAC, RESTful APIs

## 📁 Project Structure


farmlease/
├── frontend/          # Next.js or React frontend
├── backend/           # Django or Node.js backend
├── ai-models/         # AI prediction and chatbot models
├── docs/              # Documentation & SRS
├── database/          # Schema and migrations
└── README.md


## 🚀 Getting Started

### Prerequisites
- Node.js & npm/yarn
- Python 3.10+ (if using Django)
- PostgreSQL

### Installation

```bash
# Clone the repository
git clone https://github.com/fitse01/farmlease.git
cd farmlease

```

## 📌 MVP Scope

This repository currently focuses on the **Minimum Viable Product (MVP)** including:
- User authentication & roles
- Cluster registration & verification
- Proposal submission & negotiation
- Digital agreement workflow
- Receipt-based payment verification
- Basic AI chatbot and yield prediction

## 👥 Team Members

- Kiya Kebe
- Henok Asefa
- Fitsum Tafese
- Bereket Wolde
- Firomsa Assefa
- Feleke Birhanu

**Advisor**: Mr. Melkamu Abetu

## 📄 Documentation

- Full SRS and Project Report available in the `/docs` folder
- System Design, Use Cases, and Architecture diagrams included

## 📬 Contributing

This is an academic project. Contributions are welcome for improvements and future enhancements.

## 📜 License

This project is developed for academic purposes under the supervision of Adama Science and Technology University.

---

**Made with ❤️ for sustainable agricultural development in Ethiopia.**

