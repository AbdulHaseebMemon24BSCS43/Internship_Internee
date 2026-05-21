# Personalized Learning Recommendation System

This project was developed as Task 03 for the Internee.pk Internship Program.

The system recommends personalized learning modules for interns based on their previous learning patterns and course ratings using Collaborative Filtering techniques.

---

# Project Objective

The objective of this project is to build a recommendation system that suggests custom learning paths for interns by analyzing:

- Past learning behavior
- Course ratings
- Similar intern interests
- Learning engagement patterns

---

# Technologies Used

- Python
- Pandas
- Scikit-learn
- Cosine Similarity
- Collaborative Filtering

---

# Machine Learning Concept

This project uses:

## Collaborative Filtering

The system identifies interns with similar learning behavior and recommends courses that similar interns have liked.

## Cosine Similarity

Cosine similarity is used to measure similarity between interns based on course ratings.

---

# Dataset Features

The dataset contains:

| Column Name | Description |
|-------------|-------------|
| Intern_ID | Unique intern identifier |
| Course_ID | Unique course identifier |
| Course_Name | Name of learning module |
| Category | Course category |
| Difficulty | Difficulty level |
| Hours_Spent | Time spent learning |
| Rating | Intern course rating |
| Completion_Status | Course completion status |

---

# Project Workflow

1. Load dataset
2. Create user-course matrix
3. Calculate similarity between interns
4. Recommend courses based on similar users
5. Generate personalized learning paths

---

# Installation

Install required libraries:

```bash
pip install pandas scikit-learn
