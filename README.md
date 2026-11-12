# Rochtetak — Connected Healthcare Ecosystem Demo

Rochtetak is a self-initiated, bilingual (Arabic/English) healthcare technology product concept for the MENA region. This repository contains an interactive multi-role product demo based on the supplied Master Product Roadmap, MVP Roadmap, and Business Model.

## Open the demo
The GitHub Pages entry point is `index.html`. Once Pages is enabled from `main / (root)`, the site is served at:

`https://husseinhmh.github.io/rochettak/`

## What the demo covers
- Product landing experience and ecosystem overview
- Role switching across Doctor, Patient, Secretary, Pharmacy, Lab/Radiology, Hospital, Insurance, Super Admin, and Partner/Advertiser
- Doctor workspace: appointments, patient directory, prescription drafting, visit workflow, profile, messaging and analytics
- Patient journey: doctor discovery, appointment booking, health record, family members, messages, pharmacy orders and marketplace
- Pharmacy workflow: prescription intake and order status changes
- Lab/radiology workflow: request scheduling and result-status simulation
- Hospital operations: departments, staff, service and operating-room overview
- Insurance: claims review and approval/rejection simulation
- Marketplace: sample products, cart and mock checkout
- Payments: subscription tiers, appointment commissions and future RochettakPay concept
- Content and ads: doctor/patient feeds, advertiser campaign submission and moderation
- Admin: user/role governance and doctor verification queue
- AI copilot: guided platform support and workflow explanations; simulated OCR/document extraction and AI-assisted documentation concepts

## AI implementation status
The assistant currently uses a scripted demo knowledge base. It is not connected to a live LLM or medical knowledge service. OCR and voice/document workflows are represented as demonstrations only. No AI diagnosis, medication selection, dosage calculation or autonomous prescribing is provided.

## Technical status
This is a static front-end product prototype. Demo state is held in browser memory and is not a persistent database. There is no production authentication, backend API, real-time messaging, payment gateway, pharmacy inventory integration, lab/radiology integration, insurance network, or hospital information system connection.

## Safety and privacy
All names, records, operational metrics, claims, prescriptions, and transactions are fictional. Do not enter real patient information. This prototype is not for clinical use and does not make HIPAA, local privacy-law, or medical-device compliance claims.

## Product documents
- `docs/DEMO-COVERAGE.md` — roadmap-to-demo coverage and implementation boundaries
- `docs/AI-SCOPE.md` — AI use cases, demo behavior and clinical guardrails
- `docs/PORTFOLIO-CASE-STUDY.md` — accurate portfolio narrative and validation plan
