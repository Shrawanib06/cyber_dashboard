# Global Cyber Threat Dashboard

A multi-page Power BI dashboard for exploring global cyberattack trends, vulnerabilities, financial impact, and incident response performance from **2015–2024**.

## Overview

This dashboard analyzes ~3,000 recorded cyber incidents across 10 countries, providing a 360° view of attack patterns, exploited vulnerabilities, defense mechanism effectiveness, and country-level financial/user impact.

**Headline metrics:**
| Metric | Value |
|---|---|
| Total Attacks | 3,000 |
| Total Financial Loss | 151K (Million $) |
| Total Affected Users | 2bn |
| Average Resolution Time | 36 hours |

## Pages

### 1. Global Cyber Threat Dashboard
Landing/summary page with KPI cards (attacks, financial loss, affected users, resolution time), a world map of attack distribution by country, and breakdowns of total attacks by **Attack Type** and **Target Industry**.

### 2. Attack Trends & Vulnerabilities
Trend analysis of attacks by year and type (2016–2024), vulnerability distribution (Zero-day, Social Engineering, Unpatched Software, Weak Passwords), defense mechanism usage per attack type, financial loss by attack type, and attack source distribution (Hacker Group, Insider, Nation-state, Unknown). Includes filters for Year, Country, Attack Type, and Target Industry.

### 3. Defense, Mitigation & Incident Response
Focuses on response performance: incident resolution time trend over years, average resolution time by vulnerability type, a Vulnerability vs. Defense Mechanism matrix, and financial loss grouped by defense mechanism used (Antivirus, VPN, Encryption, AI-based Detection, Firewall). Filterable by Attack Type, Country, Year, Defense Mechanism, and Vulnerability Type.

### 4. Impact & Comparative Analysis
Country-level comparison of financial impact (e.g., UK vs. China loss totals), a full country-by-year financial loss matrix (2015–2024), an attack impact scatter plot (financial loss vs. affected users), and a detailed incident-level table (country, year, attack type, target industry, financial loss, affected users).

## Data Dimensions

- **Attack Types:** DDoS, Phishing, SQL Injection, Ransomware, Malware, Man-in-the-Middle
- **Vulnerability Types:** Zero-day, Social Engineering, Unpatched Software, Weak Passwords
- **Defense Mechanisms:** AI-based Detection, Antivirus, Encryption, Firewall, VPN
- **Target Industries:** IT, Banking, Healthcare, Retail, Education, Government, Telecommunications
- **Countries:** UK, Germany, Brazil, Australia, Japan, France, USA, Russia, India, China
- **Attack Sources:** Hacker Group, Insider, Nation-state, Unknown
- **Time Range:** 2015–2024

## Filters / Slicers

Common slicers available across pages: **Year, Country, Attack Type, Target Industry, Defense Mechanism, Security Vulnerability Type.** Cross-page navigation icons are available in the top-right corner of each page.

## Tech Stack

- **Tool:** Microsoft Power BI
- **Visuals:** KPI cards, line/area charts, clustered bar/column charts, pie/donut charts, scatter plots, matrix tables, map visual (Bing Maps)

## Getting Started

1. Open the `.pbix` file in Power BI Desktop.
2. Refresh the data source if connected to a live dataset.
3. Use the slicers on each page to filter by year, country, attack type, or industry.
4. Navigate between pages using the icons in the top-right corner.

## Notes

- Financial loss figures are expressed in millions (USD) unless otherwise noted.
- Map visual attribution: © Microsoft Bing / Microsoft Corporation.
- Resolution time is measured in hours.

<img width="1178" height="660" alt="1766766947652" src="https://github.com/user-attachments/assets/63343729-380e-41c6-aa6e-2ed6fde7b403" />

<img width="1182" height="666" alt="1766766945621" src="https://github.com/user-attachments/assets/37fc1ac6-af15-41d0-bbb0-92e5a7dfe964" />

<img width="1177" height="661" alt="1766766946760" src="https://github.com/user-attachments/assets/ca4a7b2c-c097-4d00-a491-2e28b8b40cc2" />

<img width="1177" height="660" alt="1766766945895" src="https://github.com/user-attachments/assets/ae325835-bb96-42fd-9825-9da59098b3a2" />



