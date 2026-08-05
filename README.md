<<<<<<< HEAD
# EduVate - AI-Powered E-Learning Platform

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Python 3.10](https://img.shields.io/badge/Python-3.10%2B-blue)](https://www.python.org/)
[![Django 4.2](https://img.shields.io/badge/Django-4.2-brightgreen)](https://www.djangoproject.com/)
[![PostgreSQL 15](https://img.shields.io/badge/PostgreSQL-15-blue)](https://www.postgresql.org/)
[![Code Style: Black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

![EduVate Platform Demo](docs/assets/eduvate-demo.gif)

An intelligent e-learning platform leveraging AI and gamification to deliver personalized learning experiences. Developed as a Software Engineering Capstone Project.

## 📌 Table of Contents
- [Key Features](#-key-features)
- [Technology Stack](#-technology-stack)
- [Installation](#-installation)
- [Configuration](#-configuration)
- [API Documentation](#-api-documentation)
- [Contributing](#-contributing)
- [License](#-license)
- [Acknowledgements](#-acknowledgements)
- [Contact](#-contact)

## 🌟 Key Features

### 🧠 AI-Driven Learning
- **Adaptive Learning Paths**  
  Machine learning models (Scikit-learn) analyze student performance to recommend personalized content
- **Smart Quiz Generation**  
  NLP-powered question generation using Hugging Face transformers
- **Predictive Analytics**  
  Early identification of at-risk students using regression models

### 🎮 Gamification System
- Dynamic leaderboards with Elo rating system
- Achievement badges (Bronze, Silver, Gold tiers)
- XP points system with daily challenges
- Progress visualization using D3.js charts

### 🛠️ Core Functionality
- Multi-role access control (Student/Instructor/Admin)
- Course management system with rich text editor
- Real-time discussion forums with WebSocket integration
- Automated certificate generation (PDF/PNG)
- Comprehensive analytics dashboard

## 🚀 Technology Stack

| Component          | Technologies                                                                 |
|--------------------|------------------------------------------------------------------------------|
| **Frontend**       | HTML5, CSS3, JavaScript                                                     |
| **Backend**        | Python 3.10, Django 4.2, Django REST Framework                              |
| **Database**       | PostgreSQL 15                                                               |
| **AI/ML**          | Scikit-learn 1.3, Hugging Face Transformers, spaCy 3.7                      |
| **DevOps**         | Docker 24.0                                                                 |
| **Security**       | JWT Authentication, OWASP ZAP, Let's Encrypt SSL                            |

## 📥 Installation

### Prerequisites
<!-- - Python 3.10+
- PostgreSQL 15
- Node.js 18.x
- Redis 7.x

```bash
Clone repository
git clone https://github.com/yourusername/eduvate.git
cd eduvate

# Create virtual environment
python -m venv venv
source venv/bin/activate  # Linux/MacOS
# venv\Scripts\activate  # Windows

# Install dependencies
pip install -r requirements.txt

# Install frontend dependencies
cd frontend
npm install
npm run build
cd ..

# Database setup
sudo -u postgres psql -c "CREATE DATABASE eduvate;"
sudo -u postgres psql -c "CREATE USER eduvate_user WITH PASSWORD 'strongpassword';"
sudo -u postgres psql -c "GRANT ALL PRIVILEGES ON DATABASE eduvate TO eduvate_user;"

# Run migrations
python manage.py migrate

# Create superuser
python manage.py createsuperuser

# Start development server
python manage.py runserver

exiting code section
``` -->

## ⚙️ Configuration

<!-- Create .env file from template:
```bash
cp .env.example .env
```
Example environment variables:
```bash
DEBUG=False
SECRET_KEY=your-secret-key
DATABASE_URL=postgres://eduvate_user:strongpassword@localhost:5432/eduvate
REDIS_URL=redis://localhost:6379/0
HUGGINGFACE_API_KEY=your-hf-key
OPENAI_API_KEY=your-openai-key
``` -->

## 📚 API Documentation

<!-- Explore our REST API endpoints using the Postman Collection.
Key endpoints include:

Endpoint	Method	Description
/api/courses/	GET	List all courses
/api/learning-path/	POST	Generate personalized path
/api/quizzes/generate/	POST	Create AI-generated quiz
/api/analytics/	GET	Get user performance metrics
Full documentation available in API.md. -->


## 🤝 Contributing

We welcome contributions! Please follow these steps:

Fork the repository

Create a feature branch (git checkout -b feature/amazing-feature)

Commit changes (git commit -m 'Add amazing feature')

Push to branch (git push origin feature/amazing-feature)

Open a Pull Request

See CONTRIBUTING.md for detailed guidelines.


## 📄 License

Distributed under the MIT License. See LICENSE for more information.

## 🙏 Acknowledgements


## 📧 Contact
Md Mahfuzur Rahman Shanto
<!-- 📧 mahfuz917.swe@gmail.com -->
<!-- 💼 LinkedIn Profile
🌐  Personal Portfolio -->

Proudly developed as part of SE 331 - Software Engineering Design Capstone (February 2025)
Team Members:
  1. Md Mahfuzur Rahman Shanto (221-35-917 E1)
  2. Md Fahim Abdullah Danial (221-35-864 D1)
  3. Nazmul Huda Shanto (221-35-1034 E1)
  4. Orgho Utshob (221-35-1000 E1)


=======
# spc-academy
I am creating a full stack website for our ed tech platformusing HTML, CSS, python, Django, Postgre SQL, js
>>>>>>> 0d8f8f740102f8cb8de379b802ec554f897c24ac
