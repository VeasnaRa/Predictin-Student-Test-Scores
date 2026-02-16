# Predictin-Student-Test-Scores

## Project Overview
Machine learning project to predict student exam scores based on various features including study habits, demographics, and environmental factors.

**Task Type**: Regression
**Target Variable**: `exam_score` (continuous, 0-100)
**Dataset Size**: 630,000 training samples, 270,000 test samples

---

## 1. Statistical Analysis (EDA)

### Dataset Features
| Feature | Type | Description |
|---------|------|-------------|
| age | Numerical | Student age (17-24) |
| gender | Categorical | male, female, other |
| course | Categorical | b.tech, b.sc, b.com, bca, bba, ba, diploma |
| study_hours | Numerical | Daily study hours (0.08-7.91) |
| class_attendance | Numerical | Attendance percentage (0-100) |
| internet_access | Categorical | yes, no |
| sleep_hours | Numerical | Daily sleep hours (4.1-9.9) |
| sleep_quality | Categorical | poor, average, good |
| study_method | Categorical | coaching, self-study, mixed, group study, online videos |
| facility_rating | Categorical | low, medium, high |
| exam_difficulty | Categorical | easy, moderate, hard |

### Key Statistics
- **Target (exam_score)**: Mean=62.51, Std=18.92, Range=[19.6, 100.0]
- **No missing values** in the dataset

### Correlation with Target
| Feature | Correlation |
|---------|-------------|
| **study_hours** | **0.7623** (strongest predictor) |
| class_attendance | 0.3610 |
| sleep_hours | 0.1674 |
| age | 0.0105 |

---
