# home-classroom
# 🏫 HOME CLASSROOM

> An immersive, AI-powered, offline-friendly virtual learning platform using Augmented Reality (AR), built with Python (Flask), MongoDB, HTML/CSS/JS, and OpenAI.

---

## 📌 Project Overview

**Home Classroom** is an offline-friendly EdTech solution that enables students to learn in local languages through AR glasses, AI tutors, and gamified modules — even in low-connectivity areas.

This project was built by a collaborative team during a hackathon and includes:

- 🔐 Secure user authentication
- 🤖 AI tutor integration (OpenAI)
- 🗃️ Offline lesson syncing and progress tracking
- 🗣️ Multilingual/local language support (via Google Translate)
- 💡 Admin and student UI interfaces
- ☁️ Deployable on AWS & Netlify

---

## ⚙️ Technologies Used

| Backend          | Frontend     | AI / APIs          | Database     |
|------------------|--------------|--------------------|--------------|
| Flask (Python)   | HTML, JS, CSS| OpenAI GPT, Google Translate | MongoDB Atlas |

---

## 🚀 Folder Structure
home-classroom/
-auth/#login,Register
-content/#lessons,Progress
-ai/#Ai tutor intergration
-utils/JWT,DB,Middleware
-app.py
-config.py
-requirements.txt
-.env.example

---frontend/
-index.html
-script.js
-style.css

Dependencies (in requirements.txt)
Flask
Flask-Cors
Flask-PyMongo
python-dotenv
PyJWT
Werkzeug
openai
googletrans==4.0.0-rc1
gunicorn
pytest

TEAM CONTRIBUTION GUIDE
CLONE THE REPO
CREATE A BRANCH
git checkout-b backend-auth or backend -ai,frontend-ui etc
commit changes
push and create a pull request

Deployement Plan
Bacckend ---Aws elastic Beanstalk or Render subject to review
Frontend ---Netlify/AWS S3
Database---- MongoDB Atlas subject to review
Acknowledgements
Built by Passionate changemakes in Tech (FutureTech)
Powered by OpenAI,MongoDB, Google Translate
Inspired by a vision for offline education
Roles & Responsibilities

Project Leads (Temi, Boma)

● Oversee progress tracking and communication
● Ensure timely delivery and cross-team alignment
● Coordinate with stakeholders and manage submission logistics

Development Team (Lead: Bello)

● Set up robust back-end (Oluwasegun, Henry, Mathias)
● Build intuitive front-end interface (Phillip, Stewart)
● Deliver scalable, offline-capable MVP

AI Team (Lead: Henry)

● Integrate AI features to enhance learning delivery or personalization
● Ensure lightweight models for offline/low-data environments

UI/UX Team (Lead: Anthony)

● Prioritize user flow for children and caregivers
● Ensure accessible, mobile-first design
● Provide wireframes, mockups, and assets early for Dev hand-off

Business Analysis & Pitch Team (Lead: Vaso)

● Craft clear, compelling pitch deck aligned with Hackathon requirements
● Coordinate visual storytelling and impact articulation with Treasure
● Ensure alignment with target user personas and solution scope
