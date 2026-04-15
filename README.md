# Member Feedback Analysis — Preventative Scan Case Study

This repository contains the data preparation, categorization, and insights generated from a 500‑entry member feedback dataset as part of the Preventative Scan case study. The goal of this project is to transform raw qualitative feedback into structured themes, severity scoring, and actionable operational recommendations.

---

## Repository Contents

| File | Description |
|------|-------------|
| **analysis.ipynb** | Python notebook used to load, clean, and prepare the feedback dataset. Includes CSV parsing fixes and extraction of the `feedback_text` column. |
| **feedback_only.csv** | Extracted feedback text used for categorization. |
| **categorized_feedback.txt** | AI‑assisted categorization output for all 500 entries, including category labels and severity scores. |
| **memo.md** | Final memo summarizing insights, category patterns, severity trends, and recommendations based on the full dataset. |
| **README.md** | Overview of the project, structure, and instructions. |

---

## Project Summary

The dataset contains **500 member feedback entries** related to scheduling, support, scan experience, billing, digital tools, and results communication. Each feedback item was categorized into one of the following themes:

- **App Issues**  
- **Customer Support**  
- **Billing**  
- **Lab Delays**  
- **Confusion About Results**  
- **Other**  
- **Positive Feedback**

Each comment was also assigned a **severity score from 1–5**  
(1 = minor, 5 = critical).

The analysis reveals a clear pattern:

- The **clinical experience is consistently excellent**, with members praising scan quality, staff professionalism, and the value of early detection.
- The **operational experience is inconsistent**, with recurring issues in scheduling, digital tools, communication, and billing policies.

---

## How to Use This Repository

### 1. Open `analysis.ipynb`
- View the data cleaning steps  
- See how the CSV was parsed and prepared  
- Understand how the feedback text was extracted  

### 2. Review `categorized_feedback.txt`
- Contains all 500 categorized comments  
- Includes severity scoring  
- Used to generate insights and recommendations  

### 3. Read `memo.md`
- Provides a polished summary of findings  
- Includes category patterns, severity trends, and recommendations  
- Reflects the full dataset  

---

## Key Insights (High‑Level)

- **Positive Feedback** is the largest category, with consistently low severity (1–2).  
  Members frequently describe the scan as “life‑changing,” “comprehensive,” and “worth every penny.”

- **App Issues** and **Customer Support** represent the majority of negative experiences.  
  These often carry severity **4–5**, especially when booking fails, appointments disappear, or members cannot get timely responses.

- **Billing** and **Lab Delays** are smaller in volume but high in intensity.  
  Complaints often involve unexpected fees, rigid policies, or results taking significantly longer than promised.

- **Confusion About Results** reflects inconsistent prep instructions, rushed reviews, or conflicting information across channels.

- **Operational friction** (e.g., directions, parking, cold facilities, impersonal interactions) appears frequently enough to impact perceived value.

---

## Recommendations (High‑Level)

- **Stabilize and simplify digital booking and portal flows**  
  Reduce crashes, errors, and mismatches between displayed and actual availability.

- **Improve communication SLAs for results and support**  
  Set clear response time expectations and proactively communicate delays.

- **Humanize and clarify billing policies**  
  Ensure charges match quotes and allow flexibility for emergencies.

- **Standardize prep instructions and results communication**  
  Align website, email, and phone guidance to reduce confusion.

- **Continue investing in clinical excellence**  
  Members consistently praise the medical team — this is a core differentiator.

---

## Author

**Cryss**  
Operations & Analytics  
