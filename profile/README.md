# SmarterDoc AI

**SmarterDoc AI** is an intelligent healthcare platform designed to help patients, families, and physicians connect with the right medical specialists — clearly, fairly, and transparently.

[▶ Watch our demo video](https://www.youtube.com/watch?v=TZyxbZrWwQk&t=4s)

Our mission is to build **trustworthy, evidence-based healthcare navigation** by combining verified medical data, transparent ranking factors, and seamless appointment workflows.

---

## Overview

SmarterDoc helps users:

* **Find the right doctor** by condition, insurance, and location
* **Understand rankings** based on experience, publications, and patient access
* **View verified sources** such as NPI Registry, PubMed, and conference profiles
* **Estimate procedure costs** using regional benchmarks
* **Book or simulate appointments** with guided assistance

The platform bridges structured healthcare data with modern AI-powered recommendations to make finding care **more transparent, data-driven, and personal**.

---

## Architecture

| Layer              | Description                                             | Technology                               |
| ------------------ | ------------------------------------------------------- | ---------------------------------------- |
| **Frontend**       | Web application for search, visualization, and booking  | Next.js 14, Tailwind CSS, TypeScript     |
| **Backend**        | API and data services for search, ranking, and analysis | FastAPI, Python 3.11+, Docker            |
| **Infrastructure** | Cloud deployment and CI/CD automation                   | Google Cloud Run, Docker, GitHub Actions |
| **Data & AI**      | Healthcare data processing, retrieval, and analysis     | BigQuery, Vertex AI, Elastic, Fivetran   |

---

## Live Deployments

**Frontend:**
[https://smarterdoc-frontend-1094971678787.us-central1.run.app](https://smarterdoc-frontend-1094971678787.us-central1.run.app)

**Backend:**
[https://smarterdoc-backend-1094971678787.us-central1.run.app](https://smarterdoc-backend-1094971678787.us-central1.run.app)

---

## Key Features

* **AI-Recommended Specialists** — discover doctors tailored to patient needs
* **Real-Time Search** — filter by specialty, insurance, and proximity
* **Interactive Map Visualization** — view nearby providers instantly
* **Transparent Profiles** — verified from public healthcare databases
* **Appointment Flow** — from selection to booking confirmation
* **Responsive UI** — optimized for desktop and mobile

---

## Repositories

* [**smarterdoc-frontend**](https://github.com/SmarterDoc-AI-Accelerate-2025/smarterdoc-frontend) — Next.js application (UI/UX, maps, booking flow)
* [**smarterdoc-backend**](https://github.com/SmarterDoc-AI-Accelerate-2025/smarterdoc-backend) — FastAPI service with indexing, retrieval, and analytics tools

---

## Development & Deployment

Both frontend and backend can be deployed independently or together using Docker and Google Cloud Run.

* CI/CD managed via **GitHub Actions**
* Environment variables configured through `.env` files
* Backend includes tools for **NPI Registry data extraction** and analysis

For local setup and deployment instructions, see each repository’s README.

---

## Data Sources & Disclaimer

SmarterDoc uses publicly available healthcare information (such as NPI Registry and PubMed) strictly for demonstration and educational purposes.
Profile images are either stock photos or AI-generated placeholders and do not depict actual medical professionals.

---

## Team

We’re a multidisciplinary group of engineers and designers dedicated to improving healthcare access through technology.
SmarterDoc AI continues to evolve — our long-term goal is to make **data-driven, transparent healthcare navigation** accessible to everyone.
