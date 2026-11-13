<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:0f2027,100:b71c1c&height=120&text=CyberSecurity%20Incidents&fontSize=40&fontColor=ffffff&desc=Monitoring%20Dashboard&descAlignY=78&descSize=16&fontAlignY=42" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/DAX-F2C811?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Power%20Query-217346?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Power%20Automate-0066FF?style=for-the-badge&logo=powerautomate&logoColor=white" />
  <br/>
  <img src="https://img.shields.io/badge/period-Aug%202023%20→%20Nov%202023-555?style=flat-square" />
  <img src="https://img.shields.io/badge/company-Votorantim%20Cimentos-555?style=flat-square" />
  <img src="https://img.shields.io/badge/area-Information%20Security-555?style=flat-square" />
</p>

<p align="center"><img src="cover.jpg" width="85%" alt="CyberSecurity Incidents dashboard" /></p>

## 🔐 Overview

A **Power BI** report with **indicators and metrics for monitoring Information Security incidents**, giving the security team and leadership a single view of what is happening.

## 🏗️ Pipeline

```mermaid
flowchart LR
    A[Incident sources] -->|Power Automate<br/>automation & extraction| B[Raw data]
    B -->|Power Query + DAX<br/>transform & load| C[Data model]
    C --> D[Power BI<br/>Security KPIs]
```

- **Extraction:** automated with **Power Automate**
- **Transformation & loading:** **Power Query** and **DAX**
- **Output:** incident indicators and metrics for monitoring

## 🔗 Related

The incident data is also managed through the **[Cyber — IRP app](https://github.com/MatheusFelipePereira/cyber-irp-incident-response)** (Power Apps + Power Automate), which feeds this kind of visualization.

## 👥 Team

Built with César at **Votorantim Cimentos**.

---

<sub>🔒 Corporate project: security data is confidential, so this repository documents the solution only.  
👤 Part of <a href="https://github.com/MatheusFelipePereira">Matheus Felipe Pereira's portfolio</a> · <a href="https://www.linkedin.com/in/matheus-felipe-p/">LinkedIn</a></sub>
