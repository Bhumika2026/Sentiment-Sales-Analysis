# Softpro Analytics – Sentiment & Sales Insights

## Project Overview

Softpro Analytics – Sentiment & Sales Insights is an AI-powered web application designed to analyze student-counselor interactions and transform them into actionable business insights.

The system integrates audio call transcripts with CRM logs and applies Speech-to-Text Transcription, Natural Language Processing (NLP), Sentiment Analysis, and Interactive Data Visualization to help counselors and management make data-driven decisions.

The platform automates the complete workflow:

Audio → Transcript → Sentiment Analysis → Insights → Recommendations

## Problem Statement

Educational institutions handle large volumes of counselor-student interactions daily. Analyzing these conversations manually is time-consuming and often results in missed opportunities to identify student concerns, objections, and conversion barriers.

Challenges addressed by the system:

* Manual analysis of student calls is slow and inefficient.
* No centralized platform exists for combining CRM logs and call insights.
* Counselors often rely on intuition instead of data-driven recommendations.
* Negative feedback can go unnoticed without automated sentiment tracking.

## Objectives

* Automate counselor call analysis.
* Convert audio conversations into structured text.
* Detect student sentiment automatically.
* Integrate transcripts with CRM data.
* Generate actionable recommendations.
* Provide interactive dashboards for management.
* Improve student engagement and conversion rates.

## Technology Stack

### Programming Language

* Python

### Frameworks & Libraries

* Streamlit
* Pandas
* NumPy
* Scikit-learn
* Hugging Face Transformers
* OpenAI Whisper
* Vosk
* Plotly

### Optional Database

* SQLite
* MySQL

### Development Tools

* Visual Studio Code
* Git & GitHub

## System Workflow

### 1. Data Collection

* Student-Counselor Audio Calls (MP3/WAV)
* CRM Student Logs (CSV)

### 2. Audio Transcription

Audio recordings are automatically converted into text using:

* OpenAI Whisper
* Vosk (Offline Alternative)

### 3. CRM Integration

Generated transcripts are merged with student information such as:

* Student Name
* Academic Year
* Technology Stack
* Location
* Counselor Remarks

### 4. Sentiment Analysis

The system classifies conversations into:

* Positive
* Neutral
* Negative

using:

* Hugging Face Transformer Models
* TF-IDF + Logistic Regression

### 5. Analytics & Visualization

Interactive dashboards provide:

* Sentiment Distribution
* Location-wise Analysis
* Technology-wise Analysis
* Trend Analysis
* Keyword Extraction
* Word Clouds

### 6. Recommendation Engine

The system identifies recurring objections such as:

* Fees
* Timing
* Placement

and generates actionable recommendations for counselors.

## Key Features

### Student Management

Manage student profiles and interaction logs.

### Audio Upload & Transcription

Convert student counseling calls into text automatically.

### CRM Log Integration

Combine structured CRM data with conversation insights.

### Sentiment Analysis Engine

Classify and analyze student sentiment.

### Interactive Dashboard

Visualize data using:

* Pie Charts
* Bar Charts
* Line Charts
* Word Clouds

### Recommendations Engine

Generate AI-assisted suggestions based on student feedback.

### Report Export

Export insights and reports in CSV/PDF format.

## Dashboard Features

### Sentiment Overview

* Positive Sentiment %
* Neutral Sentiment %
* Negative Sentiment %

### Location Analysis

* Sentiment Comparison by Location
* Performance Insights

### Technology Stack Analysis

* Python
* Java
* MERN
* AI/ML

### Trend Analysis

* Monthly Sentiment Trends
* Performance Tracking

### Keyword Analysis

* Frequently Used Positive Keywords
* Frequently Used Negative Keywords
* Word Cloud Visualization

## Business Impact

The system helps:

### Counselors

* Understand student concerns quickly.
* Improve communication strategies.
* Increase conversion opportunities.

### Trainers

* Identify technology-specific concerns.
* Improve training offerings.

### Management

* Monitor sentiment trends.
* Track counseling effectiveness.
* Make data-driven decisions.

## Challenges Solved

* Speech-to-text accuracy issues.
* Large-scale data processing.
* Context-specific sentiment classification.
* CRM-transcript integration.
* Dashboard usability for non-technical users.
* Performance optimization for large datasets.

## Future Enhancements

* Multilingual Support
* Real-Time CRM Integration
* Voice Emotion Detection
* Mobile-Friendly Dashboard
* AI-Powered Personalized Counselor Scripts
* Cloud Deployment & Scalability Improvements

## Project Outcome

Softpro Analytics successfully demonstrates how Artificial Intelligence, Natural Language Processing, and Data Analytics can transform raw student interactions into actionable insights. The system reduces manual effort, improves counseling effectiveness, and supports better decision-making through automation and intelligent recommendations.

## Author

Bhumika Maurya

Aspiring Data Analyst

Skills: Python | SQL | Power BI | Excel | Data Analytics | NLP | Machine Learning
