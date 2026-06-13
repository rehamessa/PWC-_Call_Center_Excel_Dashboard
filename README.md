PWC-\_Call\_Center\_Excel\_Dashboard

## 📊 Project Overview
===

# 

# This dashboard transforms raw call center data into actionable insights 

# 

# \*\*Dataset:\*\* (data) \[https://www.kaggle.com/datasets/gayatriwagadre/pwc-call-centre-analysis?resource=download]

# \*\*Tool:\*\* Microsoft Excel (Pivot Tables, Slicers, Charts, VBA)  

# \*\*BI Layer:\*\* Power BI (DAX Measures, Rankings, Conditional Formatting)



\## 🗂️ Dataset Fields



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



\---

## 📐 KPI Definitions



| Metric Name | Definition | Calculation |

|-------------|------------|-------------|

| Offered Contacts | Total number of inbound calls presented to the contact center. | Count of Offered Calls |

| Answered Contacts (PCA) | Total number answered by an agent. | Count of Answered Calls |

| Answer Rate (PCA %) | Percentage of offered calls answered by agents. | Answered Calls ÷ Offered Calls |

| Abandonment Rate % | Percentage of callers who disconnected before reaching an agent. | Abandoned Calls ÷ Offered Calls |

| Average Handle Time (AHT) | Average time spent handling a customer interaction. | Total Talk Time ÷ Answered Calls |

| Average Waiting Time | Average time clients wait before an agent answers. | Average Speed of Answer |

| Answered Within Threshold | Number of calls answered within 30 seconds. | Count of Answered Calls with Average Wait Time ≤ 30 sec |

| Service Level (SLA %) | Percentage of calls answered within the target threshold of 30 seconds. | Calls Answered Within Threshold ÷ Offered Calls |

| Resolution Rate % | Percentage of answered contacts that were successfully resolved. | Resolved Calls ÷ Answered Calls |

| Customer Satisfaction (CSAT Top 2 Box %) | Percentage of customer surveys rated in the top two satisfaction categories. | (Rating 4 + Rating 5) ÷ Total Surveys |

| Customer Dissatisfaction (DSAT Bottom Box %) | Percentage of customer surveys rated in the lowest satisfaction category. | Rating 1 ÷ Total Surveys |

| Average Satisfaction Score | Average score provided by customers across all surveys. | Average Satisfaction Scores |

### View 1: OverView

(Overview)\[]



