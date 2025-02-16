# My Course Repository: Online Course Application with Assessment Feature

This repository contains the **Online Course Application** enhanced with a new **assessment feature**, developed as part of the final project for the **Developing Applications with SQL Databases and Django** course by IBM.

## Overview

This project extends the provided `onlinecourse` app by implementing an assessment feature, allowing users to interact with quizzes and graded assessments as part of their online learning experience.

### Key Features

- **User Authentication**: Secure user registration and login functionality.
- **Course Management**: Allows users to view and enroll in courses.
- **Assessment Feature**:  
  - Integration of quiz-based assessments for enrolled courses.  
  - Grading logic implemented to evaluate user submissions.  
  - Enhanced user interface for quiz participation and result display.
- **Database Integration**: Uses **SQLite3** for local development, with the ability to adapt to other Django-supported SQL databases like PostgreSQL or MySQL for production.

---

## My Contribution

This repository started as a provided boilerplate `onlinecourse` application. I enhanced it by implementing the **assessment feature**, which includes:

1. **Database Design Enhancements**:  
   - Added models for questions, choices, and submissions to support the assessment functionality.
   - Designed and integrated these models based on the provided ER diagram.

2. **Backend Logic**:  
   - Developed views and serializers to handle assessment workflows.  
   - Implemented grading logic to evaluate user submissions dynamically.

3. **Frontend Development**:  
   - Created templates for displaying quizzes and results.  
   - Improved the UI for seamless interaction between users and the assessment feature.

4. **Deployment**:  
   - Deployed the application on IBM Cloud Foundry.  
   - Configured the app for production-grade database support and ensured stability during deployment.

---

## ER Diagram

The following ER diagram represents the updated database schema after integrating the assessment feature:  
![ER Diagram](https://github.com/ibm-developer-skills-network/final-cloud-app-with-database/blob/master/static/media/course_images/onlinecourse_app_er.png)

---

## Setting Up Locally

### Prerequisites
- Python 3.x
- Django 3.x
- SQLite3 (or any Django-supported database)

### Steps to Run Locally
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repo>.git
   ```
2. Navigate to the project directory:
   ```bash
   cd <your-repo>
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Apply database migrations:
   ```bash
   python manage.py migrate
   ```
5. Run the development server:
   ```bash
   python manage.py runserver
   ```
6. Open your browser and go to `http://127.0.0.1:8000` to explore the application.

---

## Deployment

This project is deployed on **IBM Cloud Foundry**. You can view the live version of the app here: [Live App Link](#).

---

## Future Work

- Enhance quiz customization for course instructors.  
- Add support for real-time analytics of quiz performance.  
- Enable support for multiple languages in quizzes and course material.  

---
