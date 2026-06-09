# MediLensAI

## Personal Health Intelligence and Early Warning System

### Project Description

MediLensAI is a completely offline healthcare assistance system designed to help users understand their medical reports without requiring internet connectivity. The system uses OCR (Optical Character Recognition) to extract information from uploaded medical reports and applies AI-based risk prediction to identify potential health concerns.

The application provides personalized health recommendations, voice-based explanations, health alerts, and visual dashboards to improve health awareness and promote early detection of medical conditions.

---

## Technology Stack

| Component       | Technology             |
| --------------- | ---------------------- |
| Frontend        | HTML, CSS, JavaScript  |
| Backend         | Python Flask           |
| Database        | SQLite                 |
| OCR             | Tesseract OCR          |
| Visualization   | Chart.js               |
| Voice Assistant | Web Speech API         |
| Alert System    | Offline SMS Simulation |

---

## Key Features

### 1. Medical Report Upload

* Upload medical reports in image or PDF format.
* Store reports locally for further processing.

### 2. OCR Analysis

* Extract medical values automatically.
* Detect important parameters such as:

  * Blood Sugar
  * Hemoglobin
  * Cholesterol

### 3. Risk Prediction

* Analyze extracted report values.
* Predict health risks.
* Generate risk scores and health status.

### 4. Recommendation Engine

* Provide personalized health suggestions.
* Recommend preventive measures and lifestyle improvements.

### 5. Voice Assistant

* Read report summaries aloud.
* Improve accessibility and ease of understanding.

### 6. Alert System

* Generate health alerts based on risk levels.
* Store alert history for future reference.

### 7. Health Dashboard

* Visualize health trends.
* Display risk analytics.
* Show report history and health score.

---

## Basic Modules

### Module 1: Report Upload Module

**Purpose:** Upload and store medical reports.

**Input:**

* Blood Report
* CBC Report
* Diabetes Report

**Output:**

* Report saved successfully

---

### Module 2: OCR Analysis Module

**Purpose:** Extract medical information from reports.

**Process:**

* Image Processing
* Text Extraction
* Medical Value Identification

**Output Example:**

Blood Sugar = 245

Hemoglobin = 8.7

Cholesterol = 220

---

### Module 3: Risk Prediction Module

**Purpose:** Predict disease risks using extracted values.

**Output Example:**

Diabetes Risk: HIGH

Risk Score: 89%

---

### Module 4: Recommendation Module

**Purpose:** Generate personalized health recommendations.

**Output Example:**

* Drink more water
* Avoid sweets
* Exercise 30 minutes daily

---

### Module 5: Voice Assistant Module

**Purpose:** Read health summaries aloud.

**Example:**

"Your blood sugar level is high. Please consult a doctor."

---

### Module 6: Alert Module

**Purpose:** Generate health alerts.

**Example:**

HIGH RISK DETECTED

Medical consultation recommended.

---

### Module 7: Dashboard Module

**Purpose:** Visualize health information.

**Visualizations:**

* Bar Charts
* Line Charts
* Pie Charts

---

## System Architecture

Medical Report

↓

Report Upload

↓

OCR Analysis

↓

Risk Prediction

↓

Recommendation Engine

↓

+-------------------------+

|                         |

↓                         ↓

Voice Assistant      Alert System

↓

Dashboard Visualization

↓

SQLite Database

---



## Project Workflow

1. User uploads a medical report.
2. OCR extracts text from the report.
3. Medical values are identified.
4. Risk prediction engine analyzes the values.
5. Recommendations are generated.
6. Alerts are created for high-risk cases.
7. Voice assistant explains the results.
8. Dashboard visualizes the health insights.

---

## Advantages

* Completely Offline
* Lightweight SQLite Database
* Easy Deployment
* AI-Based Risk Prediction
* Automated Medical Report Analysis
* User-Friendly Dashboard
* Voice-Based Assistance
* Early Warning System

---

## Future Enhancements

* Tamil Voice Support
* Multi-Report Comparison
* Advanced Machine Learning Models
* Health Trend Forecasting
* Personalized Health Score
* PDF Report Analysis

---



## Conclusion

MediLensAI provides a complete offline healthcare intelligence platform that converts medical reports into meaningful health insights. By combining OCR, AI-based risk prediction, recommendations, voice assistance, alerts, and visualization, the system aims to improve health awareness and support early medical intervention.
