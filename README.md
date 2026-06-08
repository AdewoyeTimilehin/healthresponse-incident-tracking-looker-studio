# 🚑 Real-Time Incident Tracking and Outcome Reporting

## 🏢 Company Overview

**HealthResponse Ltd** was founded in 2010 in the United Kingdom with a mission to provide fast, reliable, and efficient emergency response services. From a small local provider, HealthResponse has grown into a key player in the emergency services industry, delivering 24/7 emergency response, patient transportation, and health support services across multiple cities in the UK.

Notable milestones include the launch of its real-time incident reporting system in 2018 and recognition for excellence in emergency management.

### Core Services
| Service | Description |
|---|---|
| Emergency Medical Transport | Rapid response ambulance and medical transport services |
| Patient Monitoring | Continuous health monitoring and reporting for patients in transit |
| Incident Management | Real-time emergency response coordination for hospitals and clinics |
| Community Health Initiatives | Public health programs and emergency preparedness services |

---

## ❗ Business Challenge

HealthResponse Ltd faces significant challenges in managing and tracking emergency incidents from the moment a call is received until the outcome is fully assessed:

- **Manual Incident Logging** — Lack of integration between incident logs, dispatch systems, and patient care records causes delays in decision-making and real-time performance tracking
- **Data Inaccuracy** — Manual processes risk incomplete or incorrect data being logged, impacting the quality of incident reporting and outcomes analysis
- **Delayed Reporting** — Post-incident data aggregation delays insights into performance and patient outcomes, slowing response to emerging trends and operational inefficiencies

---

## 🎯 Project Objectives

1. **Automate Incident Logging** — Implement a system where emergency calls and incident data are logged in real time through Microsoft Forms, reducing manual data entry
2. **Create Real-Time Dashboards** — Use Looker Studio to visualize incident data, tracking response times, treatment details, and patient status in real time
3. **Enhance Data Accuracy** — Ensure all incoming data is validated and integrated seamlessly into Google Sheets via Power Automate
4. **Monitor Operational Performance** — Track KPIs such as response time, treatment effectiveness, and patient recovery rates

---

## 🔄 Workflow

```
Microsoft Forms → Power Automate → Google Sheets → Looker Studio
  (Data Collection)  (Automation)   (Central Database)  (Visualization)
```

1. **Data Collection** — Emergency incident data captured in real time through Microsoft Forms by the dispatcher team
2. **Data Automation** — Power Automate transfers data to Google Sheets instantly
3. **Data Integration** — Google Sheets serves as the central database for all incident and patient information
4. **Real-Time Visualization** — Looker Studio connects to Google Sheets, creating live dashboards
5. **Analysis & Reporting** — Decision-makers analyze trends, performance, and resource needs via the dashboard

---

## 🛠️ Tools Used

- **Microsoft Forms** — Real-time emergency incident data collection
- **Power Automate** — Automated data transfer and integration pipeline
- **Google Sheets** — Central database for incident and patient records
- **Looker Studio** — Interactive real-time dashboards and reporting

---

## 📊 Dashboard Preview

![Dashboard Preview](Dashboard.png)

> 🔗 **[View Live Looker Studio Dashboard](your-looker-studio-link-here)**

---

## 💡 Key Findings & Recommendations

> *(Update this section with your actual findings after analysis)*

- **Average response time across incidents:** ...
- **Most common incident types:** ...
- **Patient outcome trends:** ...
- **Peak incident periods identified:** ...

### Recommendations
1. Use real-time dashboard alerts to flag incidents exceeding target response times
2. Leverage trend data to pre-position resources during peak periods
3. Automate weekly performance reports for management review
4. Expand data collection fields in Microsoft Forms to capture richer patient outcome data

---

## 📁 Repository Structure

```
healthresponse-incident-tracking/
│
├── README.md
├── Dashboard.png                  ← Looker Studio dashboard screenshot
└── data/                          ← Sample/anonymised incident datasets
```

---

## 👤 Author

**Adewoye Oluwatimilehin Joseph**
[LinkedIn Profile](https://www.linkedin.com/in/adewoye-oluwatimilehin/)
