# RiderSaarthi AI – Income Protection for Delivery Partners 🏍️

## 🧠 What is this project?

RiderSaarthi AI is a **mobile-first AI-powered parametric insurance platform** for Swiggy/Zomato delivery partners in Hyderabad.  
It protects delivery partners from **income loss caused by external disruptions** like heavy rain 🌧️, traffic jams 🚦, or app downtime 📱.

---

## 🚀 Phase 1 Features (Prototype)

| Plan | Weekly Cost | Max Daily Coverage | Notes |
|------|------------|-----------------|-------|
| 🟢 Low Cover | ₹20/week | ₹200/day | Simulates claim payout screen |
| 🟡 Medium Cover | ₹30/week | ₹350/day | Shows weather-triggered claim |
| 🔴 High Cover | ₹50/week | ₹500/day | Simulates AI-verified payout |

Other features included:

* Plan-specific claim simulation  
* Weather-triggered claim flow  
* Fraud / Flagged claim visualization  
* Step-wise flow: **Subscription → Claim → Payout → Fraud/Flagged screen**  

> ⚠️ Note: Phase 1 prototype is static. No login/authentication or backend yet.

---

## 🔄 How it works

1. User selects a weekly plan (Low / Medium / High)  
2. Prototype simulates monitoring of conditions (rain, traffic, app downtime)  
3. If disruption occurs → **Claim screen** appears  
4. Payout displayed according to plan:  
   * Low → ₹200  
   * Medium → ₹350  
   * High → ₹500  
5. Fraud / Flagged claims screen shows **AI anomaly detection concept**

---

## 🚨 Fraud Detection Concept

* Detect unusual claim patterns  
* Check multiple claims from same zone within short time  
* Flag suspicious claims for manual verification  

> Phase 1 shows simulation only. Full AI integration planned for Phase 2.

---

## 💻 How to Run Prototype Locally

1. Open **terminal / command prompt**  
2. Navigate to project folder:

```bash

cd rider-saarthi-guide-main

Install dependencies:

npm install

Start local development server:

npm run dev

Open browser at → http://localhost:5173 (check terminal for actual port)

Click through: Subscription → Claim → Payout → Fraud / Flagged Claim screen

Each plan displays different payout for realistic simulation.

🛠️ Tech Stack

React, Vite, Tailwind CSS, shadcn UI

Interactive frontend only (no backend yet)

Future Phase: Node.js / Express, database, AI integration for claims

🎥 Demo Video

[Add your publicly accessible YouTube/Drive video link here]

Shows project & persona

Scrolls through README

Demonstrates interactive prototype flow

Explains fraud detection concept

### Phase 1 Goal
Build interactive frontend prototype showing subscription, claim, payout, and fraud detection simulation.
