<div align="center">

# Hi there, I'm Raman Bhardwaj 👋

<a href="https://readme-typing-svg.herokuapp.com">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=24&pause=1000&color=07A2B3&center=true&vcenter=true&width=620&lines=Full-Stack+Software+Developer;Android+%26+Mobile+Engineer+(Expo+%2F+React+Native);Microservices+%26+Cloud+Architect;Building+Resilient+Production+Systems" alt="Typing SVG" />
</a>

<p align="center">
  <a href="https://www.linkedin.com/in/raman-bhardwaj-india"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:ramanbhardwaj2005@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" /></a>
  <a href="https://play.google.com/store/apps/details?id=com.washandwow.app&hl=en_IN"><img src="https://img.shields.io/badge/Google_Play-414141?style=for-the-badge&logo=googleplay&logoColor=white" alt="Google Play" /></a>
  <a href="https://github.com/2PieRadian"><img src="https://img.shields.io/github/followers/2PieRadian?style=for-the-badge&color=07a2b3&logo=github&label=Followers" alt="GitHub Followers" /></a>
</p>

---

</div>

## About Me

I am a **Freelance Full-Stack & Mobile Software Developer** specializing in architecting resilient **event-driven microservices**, cross-platform **mobile applications with React Native & Expo**, and scalable cloud deployments.

- 📱 Built and shipped a live **Android application on Google Play Store** using Expo (React Native), Expo Router, Zustand, and Razorpay.
- ⚙️ Architected a 6-service **microservices ecosystem connected via RabbitMQ (AMQP)**, API Gateway with rate limiting, and PostgreSQL via Prisma.
- 🌐 Engineered real-time tele-health systems utilizing **WebSockets (Socket.io)** and **WebRTC** signaling alongside **AWS decoupled queue pipelines (SQS, SES, SNS)**.
- ☁️ Production deployment on **Oracle Cloud (OCI) VMs** with **Docker Compose**, **Nginx reverse proxy** (SSL/TLS termination), and automated **GitHub Actions CI/CD**.
- 🎓 B.Tech in Computer Science & Engineering (AI & ML) at ABES Engineering College (2023–2027).

---

## Featured & Live Products

### [Wash and Wow](https://washandwow.in) — On-Demand Cleaning & Laundry Ecosystem
> **Live Android App & Multi-Branch Platform** | [Play Store Link](https://play.google.com/store/apps/details?id=com.washandwow.app&hl=en_IN) • [Website](https://washandwow.in)

- **Production Android App (Expo / React Native):** Published on the **Google Play Store**. Features file-based **Expo Router**, in-app **Razorpay** checkout, **Google OAuth**, **Expo SecureStore** for token encryption, tactile **Expo Haptics**, and location-based geofencing for 8km radius branch serviceability.
- **Decoupled Microservices Backend (Node.js & Express):** Built 6 modular microservices (`auth-service`, `order-service`, `notification-service`, `operator-service`, `catalogue-service`, `user-service`) fronted by an **API Gateway** with centralized Swagger/OpenAPI documentation, JWT validation, and distributed rate limiting.
- **Asynchronous Event-Driven Messaging (RabbitMQ):** Implemented an AMQP message broker to decouple critical workflows—including order state machine transitions, automated PDF invoice generation, and customer notification dispatch.
- **Operations & Admin Dashboard (Next.js):** Engineered a multi-tenant administration portal with **TanStack Table** for complex data filtering, **Recharts** for business analytics, **jsPDF / PDFKit** for automated receipt generation, and a 5-tier RBAC system (`USER`, `DIRECTOR`, `BRANCH_ADMIN`, `WORKER`, `RIDER`).
- **Cloud Infrastructure & DevOps:** Deployed with **Docker Compose** on an **Oracle Cloud (OCI) VM** fronted by an **Nginx reverse proxy** with SSL/TLS termination, automated **GitHub Actions CI/CD**, and PostgreSQL via Prisma ORM.
- **Tech Stack:** `Expo` • `React Native` • `Node.js` • `Next.js` • `Express.js` • `RabbitMQ` • `PostgreSQL` • `Prisma` • `Docker Compose` • `Nginx` • `Oracle Cloud (OCI)`

<br/>

### [MindCurePath](https://mindcurepath.com) — Tele-Counseling & Mental Healthcare Platform
> **Scalable Full-Stack Platform** | [Website](https://mindcurepath.com)

- **Scale & Real-World Telemetry:** Architected and scaled a counseling platform serving **168+ active users** with **5.8K+ user events** and an average session engagement time of **4+ minutes**.
- **Real-Time Video Consultations (WebRTC & Socket.io):** Built a real-time signaling pipeline using **Socket.io** and **WebRTC** for peer-to-peer audio/video therapy sessions, live consultation status updates, and interactive messaging.
- **High-Concurrency Emergency Booking:** Engineered an end-to-end appointment lifecycle with an automated **emergency booking engine ($\leq$ 30 mins)**, optimizing slot concurrency, automated therapist dispatch, and review workflows.
- **Decoupled Cloud Messaging (AWS SQS, SES, SNS):** Built background worker queues leveraging **AWS SQS** with Dead-Letter Queues (DLQ), transactional emails via **AWS SES**, and instant SMS OTPs via **AWS SNS**; managed file uploads via **Amazon S3 presigned URLs**.
- **Security & Caching:** Implemented secure **JWT + Google OAuth 2.0** with **Redis** session management, distributed API rate limiting (`rate-limit-redis`), and cryptographic **Razorpay webhook signature verification (HMAC SHA256)**.
- **DevOps on Oracle VM:** Containerized services via **Docker Compose** deployed on an **Oracle Cloud (OCI) VM** with **Nginx reverse proxy**, **node-cron** automated tasks, and **GitHub Actions CI/CD**.
- **Tech Stack:** `React.js` • `Node.js` • `Socket.io` • `WebRTC` • `PostgreSQL` • `Prisma` • `Redis` • `AWS (SQS, SES, SNS, S3)` • `Razorpay` • `Docker Compose` • `Nginx` • `Oracle Cloud (OCI)`

<br/>

### [Distributed Multiplayer Chess Platform & Engine](https://github.com/2PieRadian) *(In Active Development)*
> **Core Java Game Engine • REST / WebSocket API Gateway • Scalable Multiplayer System**

- **Custom Java Chess Engine:** Architected an object-oriented, immutable board representation engine in **Java**, implementing complete legal move generation for all pieces, check/checkmate detection, and board state evaluation from first principles.
- **Engine-to-API Bridge (In Progress):** Exposing the core Java engine via high-throughput REST and **WebSocket** endpoints to stream live board evaluations, validate moves with sub-millisecond latency, and broadcast game states to web/mobile clients.
- **Distributed Multiplayer & Matchmaking (Roadmap):** Designing a scalable multiplayer matchmaking service backed by **Redis Pub/Sub** for room-based game sessions, distributed lock synchronization for atomic turn execution, and horizontal scaling.
- **Interactive Web Client (Upcoming):** Building a modern, animated interactive chess board interface with move highlighting, drag-and-drop mechanics, real-time clock timers, and game history replay.
- **Tech Stack:** `Java` • `Object-Oriented Design` • `Spring Boot / Node.js` • `WebSockets` • `Redis Pub/Sub` • `Docker`

---

## Tech Stack & Toolbox

<div align="center">

### Languages
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

### Frontend & Mobile
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![React](https://img.shields.io/badge/React.js-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-443e38?style=flat-square&logo=react&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=react-query&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![Redux](https://img.shields.io/badge/Redux-764ABC?style=flat-square&logo=redux&logoColor=white)

### Backend, Systems & Architecture
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socket.io&logoColor=white)
![WebRTC](https://img.shields.io/badge/WebRTC-333333?style=flat-square&logo=webrtc&logoColor=white)
![Microservices](https://img.shields.io/badge/Microservices_Architecture-07a2b3?style=flat-square&logo=diagram-next&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-005571?style=flat-square&logo=fastapi&logoColor=white)

### Databases & Caching
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma_ORM-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)

### Cloud, DevOps & Tools
![Oracle Cloud](https://img.shields.io/badge/Oracle_Cloud_(OCI)-F80000?style=flat-square&logo=oracle&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![AWS](https://img.shields.io/badge/AWS_(SQS/SES/SNS/S3)-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions_CI/CD-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=google-cloud&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

</div>

---

## Honors & Certifications

- **Smart India Hackathon (SIH) — Top 45** out of 348 teams (Internal Round).
- **AWS Academy Graduate** — Cloud Architecting.
- **LinkedIn Certified** — Java (Advanced Concepts for High-Performance Development).

---

## GitHub Stats

<div align="center">

<img src="https://github-readme-stats-anuraghazra1.vercel.app/api?username=2PieRadian&show_icons=true&theme=tokyonight&hide_border=true" alt="Raman's GitHub Stats" width="48%" />
<img src="https://github-readme-stats-anuraghazra1.vercel.app/api/top-langs/?username=2PieRadian&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" width="48%" />

<br/>

<img src="https://streak-stats.demolab.com/?user=2PieRadian&theme=tokyonight&hide_border=true" alt="GitHub Streak" width="97%" />

</div>

---

## Connect & Collaborate

I'm always open to discussing new opportunities, freelance contracts, tech architectures, or open-source collaborations.

- 💼 **LinkedIn:** [linkedin.com/in/raman-bhardwaj-india](https://www.linkedin.com/in/raman-bhardwaj-india)
- ✉️ **Email:** [ramanbhardwaj2005@gmail.com](mailto:ramanbhardwaj2005@gmail.com)
- 📱 **Google Play Store:** [Wash and Wow App](https://play.google.com/store/apps/details?id=com.washandwow.app&hl=en_IN)
- 🌐 **Portfolio & Projects:** [washandwow.in](https://washandwow.in) • [mindcurepath.com](https://mindcurepath.com)

<p align="center">
  <i>"Passionate about turning architectural complexity into seamless user experiences."</i>
</p>
