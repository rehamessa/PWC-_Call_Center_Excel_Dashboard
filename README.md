# 📞 PWC Call Center Analytics Dashboard

An interactive **Excel + Power BI** dashboard analyzing ~5,000 inbound call records across 4 analytical views — built to support data-driven decisions in workforce management, service quality, and customer satisfaction.

- **Dataset:** [PWC Call Centre Data — Kaggle](https://www.kaggle.com/datasets/gayatriwagadre/pwc-call-centre-analysis?resource=download)
- **Tools:** Microsoft Excel (Pivot Tables, Slicers, Charts, VBA) · Power BI (DAX, Conditional Formatting)

---

## 🗂️ Dataset Fields

| Field | Description |
|-------|-------------|
| Call ID | Unique identifier per call |
| Agent | Agent name handling the call |
| Date | Call date |
| Time | Call time (hour-level) |
| Topic | Call category / reason |
| Answered (Y/N) | Whether the call was answered |
| Resolved (Y/N) | Whether the issue was resolved |
| Speed of Answer (sec) | Wait time before agent picks up |
| Avg Talk Duration | Handle time per call |
| Satisfaction Rating | Customer rating (1–5) |

---

## 📐 KPI Definitions

| Metric Name | Definition | Calculation |
|-------------|------------|-------------|
| Offered Contacts | Total number of inbound calls presented to the contact center. | Count of Offered Calls |
| Answered Contacts (PCA) | Total number answered by an agent. | Count of Answered Calls |
| Answer Rate (PCA %) | Percentage of offered calls answered by agents. | Answered Calls ÷ Offered Calls |
| Abandonment Rate % | Percentage of callers who disconnected before reaching an agent. | Abandoned Calls ÷ Offered Calls |
| Average Handle Time (AHT) | Average time spent handling a customer interaction. | Total Talk Time ÷ Answered Calls |
| Average Waiting Time (ASA) | Average time clients wait before an agent answers. | Average Speed of Answer |
| Answered Within Threshold | Number of calls answered within 30 seconds. | Count of Answered Calls with Wait Time ≤ 30 sec |
| Service Level (SLA %) | Percentage of calls answered within the 30-second target. | Calls Within Threshold ÷ Offered Calls |
| Resolution Rate % | Percentage of answered contacts successfully resolved. | Resolved Calls ÷ Answered Calls |
| CSAT Top 2 Box % | Percentage of surveys rated 4 or 5. | (Rating 4 + Rating 5) ÷ Total Surveys |
| DSAT Bottom Box % | Percentage of surveys rated 1. | Rating 1 ÷ Total Surveys |
| Average Satisfaction Score | Average customer satisfaction score. | Average of All Ratings |

---

![Customer statisfaction]([Images/View3_Customer_Experience.png](https://github.com/rehamessa/PWC-_Call_Center_Excel_Dashboard/blob/main/Images/CSAT.png)

![Customer statisfaction]([Images/View3_Customer_Experience.png](https://github.com/rehamessa/PWC-_Call_Center_Excel_Dashboard/blob/main/Images/CSAT.png))




---
