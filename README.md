# German Dagil

Software engineer in Warsaw. I build across backend, frontend and deployment, tutor programming part-time and study aerospace engineering.

[Portfolio](https://germandagil.dev/) · [Email](mailto:dagilgerman@gmail.com) · [Telegram](https://t.me/quanperfect) · Discord: `quanperfect`

Open to software engineering internships and full-time hybrid or remote roles.

## Selected projects

### QuanTutor

I built and maintain QuanTutor for my own tutoring work, my tutor friends and our students. It's a production workspace used by **42+ students** for collaborative whiteboards and code rooms, messaging, file sharing, lessons, homework and financial tracking.

**[Try the demo](https://demo.quantutor.eu)** · [Details & screenshots](https://germandagil.dev/#qt-project) · [Architecture](https://germandagil.dev/#qt-design) · [Production status](https://quantutor.betteruptime.com)

[![QuanTutor uptime](https://uptime.betterstack.com/status-badges/v3/monitor/2p2ev.svg)](https://quantutor.betteruptime.com)

- **Frontend:** React and Next.js with TypeScript.
- **Services:** a Python/FastAPI domain API, Go services for files, messaging and code execution, TypeScript services for live collaboration and Java/Spring Boot notifications. A Python scheduler handles reminders and background maintenance.
- **Authentication and permissions:** custom authentication with session management and Zanzibar-style relationship-based authorization through SpiceDB over gRPC.
- **Data and storage:** PostgreSQL, Redis, RabbitMQ and self-hosted MinIO S3. Amazon SES handles email delivery.
- **Deployment:** Docker Compose on a Linux VPS, managed through Dokploy with Traefik for HTTPS and WebSockets.

An authenticated API load test with k6 measured **163 requests/s with 215 ms p95 latency**. This measures that API workload; live collaboration and code execution need separate tests.

The main application repository is private; the [scheduler microservice](https://github.com/quanperfect/quantutor-scheduler-microservice) is public. You can explore the platform through the demo and architecture notes.

### Concurrent Task Executor

Built a C++20 task executor with a fixed worker pool, synchronized FIFO queue, move-only tasks, typed futures, exception propagation and graceful draining shutdown. Validated lifecycle races with ThreadSanitizer and failure injection.

Benchmarked 10,000-task synthetic CPU workloads across 1–22 workers, achieving **10.9x median speedup** over direct sequential execution and **171k tasks/s at 22 workers**. Analyzed task granularity, executor overhead and queue-lock contention.

### FACEIT Analytics Fullstack Platform

Built and deployed a CS2 analytics platform that aggregated FACEIT match data into player statistics and performance views using FastAPI, React and PostgreSQL. Redis caching and API rate-limit handling reduced repeated-query latency from over 1 s to around 20 ms and minimized unnecessary upstream requests. The deployment is now archived.

### Game development experiments

Small Unity and Unreal projects for fun, including a car physics experiment with Ackermann steering and a manual gearbox.

## What I use

### Languages

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-336791?style=flat-square)
![Java](https://img.shields.io/badge/-Java-ED8B00?style=flat-square)

### Backend & data

![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Spring Boot](https://img.shields.io/badge/-Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/-SQLAlchemy-FCA121?style=flat-square&logo=sqlalchemy&logoColor=black)
![Pydantic](https://img.shields.io/badge/-Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/-RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![SpiceDB](https://img.shields.io/badge/-SpiceDB-8447FF?style=flat-square)

### Frontend

![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/-Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

### Tools & deployment

![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![CI/CD](https://img.shields.io/badge/-CI%2FCD-2088FF?style=flat-square)
![Codex](https://img.shields.io/badge/-Codex-222222?style=flat-square)
![Traefik](https://img.shields.io/badge/-Traefik-24A1C1?style=flat-square&logo=traefikproxy&logoColor=white)
![Dokploy](https://img.shields.io/badge/-Dokploy-000000?style=flat-square)
![MinIO S3](https://img.shields.io/badge/-MinIO_S3-C72E49?style=flat-square&logo=minio&logoColor=white)
![Amazon SES](https://img.shields.io/badge/-Amazon_SES-FF9900?style=flat-square)

### Testing

![Pytest](https://img.shields.io/badge/-Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![GoogleTest](https://img.shields.io/badge/-GoogleTest-4285F4?style=flat-square)
![ThreadSanitizer](https://img.shields.io/badge/-ThreadSanitizer-00599C?style=flat-square)
![k6](https://img.shields.io/badge/-k6-7D64FF?style=flat-square&logo=k6&logoColor=white)

## Why aerospace engineering

I studied computer science at ITMO before moving countries and changing universities. I chose aerospace engineering at Warsaw University of Technology to explore my interest in aircraft. Software engineering is my career focus, with aerospace and simulation continuing alongside it.

**Warsaw University of Technology** · B.Sc. Aerospace Engineering · October 2022–September 2027, expected

- **Students’ Space Association, Robotics Division (2025–2026):** worked with a team of 10+ members to develop Python control software for a custom Raspberry Pi rover.
- **[BAE Systems DEMON UAV](https://github.com/quanperfect/demon-uav-flight-dynamics-simulation):** MATLAB/Simulink work on lateral-directional flight dynamics.
- **[Boeing 767 rudder system](https://github.com/quanperfect/boeing-767-rudder-system-simulation):** group coursework on a simplified rudder system, with MATLAB/Simulink models, equations and simulation plots.

Previously: B.Sc. Computer Science at ITMO University, September 2020–October 2022 (**incomplete**).

![MATLAB / Simulink](https://img.shields.io/badge/-MATLAB_%2F_Simulink-0076A8?style=flat-square)
![LaTeX](https://img.shields.io/badge/-LaTeX-008080?style=flat-square&logo=latex&logoColor=white)
