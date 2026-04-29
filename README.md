#  AI Multi-Factor Major Recommendation System

An intelligent decision-support system that helps students choose the most suitable university major based on a combination of **logical, emotional, psychological, and market factors**.

---

## Overview

Choosing a university major is a complex decision that involves more than just grades.
This system provides **personalized recommendations** by analyzing multiple dimensions of a student’s profile.

The system integrates:

* Academic performance (GPA)
* Skills and abilities
* Personality type (MBTI)
* Emotional preferences
* Market demand

---

## Objectives

* Provide **Top 3 major recommendations** for each student
* Combine **multi-factor decision making**
* Offer **clear explanations** for recommendations
* Handle **invalid or conflicting inputs**
* Store **student profiles and feedback** for improvement

---

## System Features

### Multi-Factor Scoring

Each major is evaluated using a weighted scoring model:

* 40% Logical (academic & skills)
* 30% Emotional (interest & engagement)
* 20% Psychological (MBTI compatibility)
* 10% Market Demand

---

### Top 3 Recommendations

* Displays the best three majors ranked by score
* Shows compatibility level (e.g., High / Medium Match)

---

### Explainable AI

* Provides a clear explanation for the top recommendation
* Improves **transparency and trust**

---

### Input Validation & Robustness

* Detects inconsistent inputs (e.g., high GPA + low skills)
* Prevents:

  * Saving student profile
  * Generating recommendations
  * Saving feedback
* Requires user to fix inputs first

---

### 💾 Data Storage

The system stores:

* Student profiles
* Final recommendations
* User feedback

All data is saved in Excel files.

---

## User Interface

The system is built using **Streamlit** and provides an interactive interface where users can:

1. Enter student information
2. Select GPA and skill levels
3. Complete personality (MBTI)
4. Generate recommendations
5. View detailed scoring table
6. Choose a final major
7. Save feedback

---

## Project Structure

```
AI_Major_Recommendation_System/
│
├── app.py
├── main.py
├── README.md
│
├── code/
│   ├── data/
│   │   ├── majors_dataset.xlsx
│   │   └── student_dataset_30.xlsx
│   │
│   └── outputs/
│       ├── final_recommendations_with_feedback.xlsx
│       ├── recommendation_feedback.xlsx
│       └── new_students_profiles.xlsx
│
├── Images/
├── ppt/
└── report/
```

---

## How to Run

1. Install dependencies:

```bash
pip install -r requirements.txt
```

2. Run the application:

```bash
streamlit run app.py
```

3. Open in browser:

```
http://localhost:8501
```

---

## Example Output

* Top 3 recommended majors
* Explanation for best match
* Detailed scoring table for all majors
* Saved feedback and profiles

---

##  Future Work

* Integrate **machine learning models** for improved accuracy
* Use **real-world datasets**
* Expand majors and career paths
* Deploy as a **cloud-based system** for universities

---

## Final Note

This system is not just about choosing a major…
it’s about understanding the person behind the decision.

---

## 👩‍💻 Author

Arwa Alshaikh
Farah Alnaqib
Maysoon Idris

Artificial Intelligence Project – CS3081
