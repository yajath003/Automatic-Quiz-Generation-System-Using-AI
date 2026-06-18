# Automatic Quiz Generation and Evaluation System using Large Language Models with Distractor Optimization

## Overview

The Automatic Quiz Generation and Evaluation System is an AI-powered educational platform that automatically generates high-quality multiple-choice quizzes from educational resources such as PDF documents, DOCX files, text files, and manually entered content.

The system leverages Large Language Models (LLMs) to generate relevant questions, correct answers, and optimized distractors while evaluating quiz quality using multiple performance metrics.

This project aims to reduce the manual effort involved in quiz preparation and provide intelligent assessment tools for teachers, students, and educational institutions.

---

## Features

### User Management
- User Registration
- Secure Login Authentication
- Password Hashing
- Session Management
- Role-Based Access Control

### Resource Processing
- PDF Upload Support
- DOCX Upload Support
- TXT File Upload Support
- Manual Text Input
- Text Extraction and Cleaning

### Intelligent Quiz Generation
- Topic Detection
- Automatic MCQ Generation
- Correct Answer Generation
- Distractor Generation
- Difficulty-Aware Questions

### Distractor Optimization
- Semantic Similarity Analysis
- Duplicate Option Removal
- Relevance Filtering
- Plausibility Validation

### Evaluation Engine
- Relevance Score
- Diversity Score
- Duplicate Rate Analysis
- Distractor Quality Evaluation
- Difficulty Assessment

### Dashboard & Reports
- Quiz Statistics
- User Activity Monitoring
- Performance Reports
- Generated Quiz History

---

## System Workflow

1. User uploads educational content
2. Text is extracted and processed
3. Important topics are identified
4. LLM generates questions and answers
5. Distractors are generated and optimized
6. Duplicate questions are removed
7. Evaluation metrics are calculated
8. Final quiz is displayed to the user
9. Reports are stored in the database

---

## Technologies Used

### Programming Languages
- Python
- HTML
- CSS
- JavaScript

### Backend
- Flask
- Flask-WTF
- Flask-Login
- SQLAlchemy

### Frontend
- HTML5
- CSS3
- Bootstrap
- JavaScript

### Database
- SQLite
- MySQL (Supported)

### Artificial Intelligence
- Large Language Models (LLMs)
- OpenRouter API
- Ollama (Initial Development)

### Text Processing
- Natural Language Processing (NLP)
- PDF Parsing
- Text Extraction
- Topic Detection

### Development Tools
- Git
- GitHub
- Visual Studio Code

---

## Project Architecture

```text
User
  |
  v
Frontend (HTML/CSS/Bootstrap)
  |
  v
Flask Backend
  |
  +---------------------+
  |                     |
  v                     v
Database           OpenRouter API
(SQLAlchemy)             |
                          v
                   Quiz Generation
                          |
                          v
                Distractor Optimization
                          |
                          v
                    Evaluation Engine
                          |
                          v
                     Final Quiz
```

---

## Database Tables

### Users
- User ID
- Username
- Email
- Password Hash
- Role

### Resources
- Resource ID
- File Name
- Upload Date
- User ID

### Topics
- Topic ID
- Topic Name
- Resource ID

### Questions
- Question ID
- Question Text
- Correct Answer
- Distractors

### Attempts
- Attempt ID
- User ID
- Score

### Reports
- Evaluation Metrics
- Quiz Statistics

---

## Installation

### Clone Repository

```bash
git clone https://github.com/yajath003/project-name.git
cd project-name
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

Windows:

```bash
venv\Scripts\activate
```

Linux/Mac:

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Configure Environment Variables

Create a `.env` file:

```env
OPENROUTER_API_KEY=your_api_key
SECRET_KEY=your_secret_key
```

### Run Application

```bash
python main.py
```

---

## Testing

The system was tested using:

- Unit Testing
- Integration Testing
- System Testing
- User Acceptance Testing
- Performance Testing

---

## Research Contribution

This project explores the application of Large Language Models in educational assessment systems and focuses on:

- Automatic Question Generation
- Distractor Optimization
- Quiz Evaluation Metrics
- Educational AI Applications

---

## Future Enhancements

- Multi-Language Quiz Generation
- Bloom's Taxonomy Integration
- Personalized Assessments
- Classroom Management Features
- Advanced Analytics Dashboard
- Offline Model Deployment

---

## Project Team

- K. Yajath
- B. Lavanya
- K. Gyanendra
- T. Venkatesh

### Guide

Ch. Sravanthi Sowdanya  
Assistant Professor  
Department of CSE (AI & ML)

---

## License

This project was developed as part of the B.Tech Final Year Project at ANITS and is intended for educational and research purposes.
