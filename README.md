# German Dagil

Full-stack Software Engineer who loves diving deep into projects and polishing every detail, especially on the backend side.

## What I use

### Languages
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![LaTeX](https://img.shields.io/badge/-LaTeX-008080?style=flat-square&logo=latex&logoColor=white)
![MATLAB](https://img.shields.io/badge/-MATLAB-0076A8?style=flat-square&logo=mathworks&logoColor=white)

### Backend
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/-SQLAlchemy-FCA121?style=flat-square&logo=sqlalchemy&logoColor=black)
![Pydantic](https://img.shields.io/badge/-Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/-RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)

### Frontend
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)

### Cloud & DevOps
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/-Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![MinIO](https://img.shields.io/badge/-MinIO-C72E49?style=flat-square&logo=minio&logoColor=white)

<br>

## What I'm building right now

### Personal tutoring platform
I really enjoy my part-time work as a programming tutor, so I decided to make life easier for myself and my students (and parents) - a platform for lesson scheduling, homework tracking, payment management, teaching materials. Future plans include live whiteboard and proper code sharing collaboration, plus automated code testing, exploring WebRTC for calls. Currently in beta testing.

**Why it's private:** The code handles real student data (even with just a small amount of users), so I'm keeping it private until the production release, I feel like it's a wise approach.

**Details:**
- Custom rolled OAuth2 authentication following OWASP guidelines
- Monolith architecture with FastAPI + a few attached microservices  
- Detailed API error handling that helps the frontend show very useful error messages + strict Pydantic validation
- Self-deployed MinIO (S3-compatible) for homework and lesson file uploads
- AWS SES for emails, Telegram notifications using Aiogram

### Other projects worth mentioning
- **FACEIT CS2 Analytics** - stats website for me and friends to track our Counter-Strike games results. Way easier than navigating Faceit's site when looking at stats of multiple players. Currently rewriting for their new API and fixing some rushed architecture decisions.
- **Game dev experiments** - small Unity/Unreal projects for fun. Best one so far: realistic car physics with proper Ackermann steering and manual gearbox.

<br>

## Why aerospace engineering

Had to change universities when moving countries. Didn't want to repeat the same Computer Science curriculum that I already studied in my previous university, so picked my second passion - aircrafts. Turns out it's probably more of a hobby than a career path for me, but it's been fun and educational.

**Warsaw University of Technology** (2022-2026)
- Aerospace Engineering, focusing on computational stuff
- Students Space Association, Robotics Division (2025) - Software Engineer
- MATLAB/Simulink simulations:
  - BAE Systems DEMON UAV lateral-directional behavior
  - Boeing 767 rudder control system modeling
