# 🌬️ CleanAir Collective

**Indoor Air Quality as a Service**

Real-time air quality monitoring, AI-driven ventilation insights, and automated compliance reporting — delivered as a simple subscription for offices, schools, and co-working spaces.



---

## 🧐 The Problem

People spend **90% of their time indoors**, yet most buildings have zero visibility into air quality. Poor indoor air causes headaches, fatigue, reduced cognitive performance, and long-term health issues — costing European businesses an estimated **€20B annually** in lost productivity.

## 💡 The Solution

CleanAir Collective is a subscription-based platform that combines **affordable IoT sensors** with an **AI-powered dashboard** to give facility managers, school administrators, and office operators full visibility and control over their indoor environment.

### How It Works

1. **Install** — Plug in pre-configured CleanAir Node sensors (WiFi, 2-min setup)
2. **Monitor** — View real-time CO₂, PM2.5, VOC, temperature & humidity on a live dashboard
3. **Act** — Receive AI-generated ventilation recommendations and automated alerts

---

## 🔧 Hardware — CleanAir Node

| Spec | Details |
|---|---|
| CO₂ | NDIR sensor, 0–5,000 ppm ±30 ppm |
| PM2.5 / PM10 | Laser scattering, 0–500 μg/m³ |
| VOC (TVOC) | Metal oxide, 0–60,000 ppb |
| Temperature | -10°C to 60°C ±0.3°C |
| Humidity | 0–100% RH ±2% |
| Connectivity | WiFi 802.11 b/g/n + BLE 5.0 |
| Power | USB-C, 5V 1A (< 2W idle) |
| Size | 95 × 95 × 28 mm, 120g |
| Enclosure | Recycled ABS, IP20, magnetic mount |
| Data Rate | Every 30 sec, local buffer 72h |

---

## ✨ Platform Features

- **Real-Time Dashboard** — Multi-zone floor maps, historical trends, comparative analytics
- **AI Ventilation Engine** — ML-powered recommendations based on occupancy, weather, and building data
- **Smart Alerts** — Slack, email, SMS, and webhook notifications with escalation workflows
- **Health Impact Scoring** — Proprietary 0–100 score correlating air quality with cognitive/wellness effects
- **HVAC Integration** — API connections to Siemens, Honeywell, Johnson Controls BMS
- **ESG & Compliance Reports** — Auto-generated reports for CSRD, WELL, LEED, and BREEAM
- **Occupancy Correlation** — Cross-reference air quality with room booking and people counter data
- **Multi-Site Management** — Central portal for organizations with multiple locations

---

## 🎯 Target Customers

| Segment | Use Case |
|---|---|
| 🏢 Corporate Offices | Productivity, sick day reduction, CSRD compliance |
| 🏫 Schools & Universities | Student health, EU IAQ guidelines compliance |
| 💻 Co-Working Spaces | Brand differentiation, member retention |
| 🏥 Healthcare Facilities | Airborne pathogen risk reduction |
| 🏛️ Government Buildings | EU Green Deal mandates, public health |

---

## 💰 Pricing

| Plan | Price | Sensors | Key Features |
|---|---|---|---|
| **Starter** | €29/mo per sensor | 1–5 | Dashboard, email alerts, 30-day history |
| **Professional** | €22/mo per sensor | 6–50 | AI engine, Health Scoring, ESG reports, 12-month history |
| **Enterprise** | Custom | 50+ | BMS integration, full API, SLA, unlimited retention |

Sensors are **rented, not sold** — we handle shipping, calibration, maintenance, and replacements.

---

## 💵 Revenue Model

| Stream | Share | Description |
|---|---|---|
| SaaS Subscriptions | 65% | Monthly per-sensor fees for platform access |
| Hardware Rental | 20% | ~€45 BOM, rented at €8–12/mo, pays back in 4–5 months |
| Data Licensing | 10% | Anonymized IAQ data for urban planners, HVAC manufacturers, insurers |
| Certification Consulting | 5% | WELL / LEED / BREEAM consulting using CleanAir data |

---

## 📈 Market Opportunity

- **TAM** — €4.6B global IAQ monitoring market by 2028
- **SAM** — €1.2B EU offices + schools
- **SOM** — €18M CEE region, Year 3
- **CAGR** — 12%+ annually

### Key Drivers

- 🇪🇺 **EU CSRD Mandate** — mandatory sustainability reporting from 2025
- 📜 **WELL Building Standard** — 30% YoY growth in Europe
- 🦠 **Post-Pandemic Awareness** — 68% of workers consider air quality when choosing a workplace
- 🏙️ **Smart City Funding** — EU Horizon Europe grants for IAQ pilots

---

## 🛠️ Tech Stack

| Layer | Technologies |
|---|---|
| Firmware | ESP32, FreeRTOS, OTA updates, edge processing |
| Cloud Backend | AWS IoT Core, Lambda, DynamoDB, TimescaleDB |
| Frontend | React, TypeScript, D3.js, PWA |
| AI / ML | Python, scikit-learn, TensorFlow Lite (on-device) |
| Integrations | REST API, MQTT, BACnet (BMS), Slack & Teams webhooks |
| Security | TLS 1.3, AES-256 at rest, GDPR compliant, SOC 2 roadmap |

---

## 🗺️ Roadmap

| Phase | Timeline | Milestones |
|---|---|---|
| **Validation** | Month 1–3 | 20 sensor prototypes, 3 free pilots in Bratislava |
| **Beta Launch** | Month 4–6 | Dashboard v1, 10 paying customers (SK + CZ), grant applications |
| **Growth** | Month 7–9 | AI engine release, custom PCB, expand to AT + PL, 50 customers |
| **Scale** | Month 10–12 | Enterprise tier, BMS integration, B2G sales, €420K ARR |
| **Expansion** | Month 13–18 | DE + NL + Nordics, data licensing, €1.2M ARR, Series A ready |

---


---

## 📂 Project Structure

```
cleanair-collective/
├── firmware/          # ESP32 sensor firmware
├── backend/           # AWS Lambda functions & API
├── dashboard/         # React frontend application
├── ai-engine/         # ML models & training scripts
├── docs/              # Documentation & specs
├── hardware/          # PCB schematics & BOM
└── README.md
```


---

## 📄 License

This project is licensed under the MIT License

---

<p align="center">
  <strong>CleanAir Collective</strong> — Because the air you breathe at work shouldn't be an afterthought.
</p>
