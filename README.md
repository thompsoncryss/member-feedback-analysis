Member Feedback Analysis — Preventative Scan Case Study
This repository contains the data preparation, categorization, and insights generated from a member feedback dataset as part of the Preventative Scan case study. The goal of this project is to transform raw qualitative feedback into structured themes, severity scoring, and actionable operational recommendations.

Repository Contents
File	Description
analysis.ipynb	Python notebook used to load, clean, and prepare the feedback dataset. Includes CSV parsing fixes and extraction of the feedback_text column.
feedback_only.csv	Extracted feedback text used for categorization.
categorized_feedback.txt	AI‑assisted categorization output including category labels and severity scores.
memo.pdf or memo.md	Final memo summarizing insights, category patterns, severity trends, and recommendations.
README.md	Overview of the project, structure, and instructions.

Project Summary
The dataset contains member feedback related to scheduling, support, scan experience, and results communication. Each feedback item was categorized into one of the following themes:

Customer Support

App Issues

Lab Delays

Positive Feedback

Other

Each comment was also assigned a severity score from 1–5 (1 = minor, 5 = critical).

The analysis highlights that the most urgent issues relate to:

Delayed or missing responses from Customer Support

Scheduling and booking errors within the app

At the same time, members consistently praise:

Staff professionalism

Scan quality

Comfort during the appointment

This indicates that the core clinical experience is strong, while operational processes around communication and scheduling need improvement.

How to Use This Repository
Open analysis.ipynb

View the data cleaning steps

See how the CSV was parsed and prepared

Understand how the feedback text was extracted

Review categorized_feedback.txt

Contains categorized comments

Includes severity scoring

Used to generate insights and recommendations

Read memo.pdf or memo.md

Provides a polished summary of findings

Includes category counts, severity patterns, and recommendations

Key Insights (High‑Level)
Customer Support delays are the highest‑severity issue

App/Scheduling issues cause missed appointments and frustration

Positive feedback is strong and consistent

Lab delays are low‑frequency but noticeable

Minor operational friction exists (e.g., directions, facility access)

Recommendations (High‑Level)
Strengthen Customer Support response SLAs

Improve scheduling and app reliability

Add proactive communication for lab result delays

Enhance wayfinding and facility instructions

Author
Cryss  
Operations & Analytics
Preventative Scan Case Study — April 2026
