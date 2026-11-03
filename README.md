
<div align="center">

# Mohamed Munavver Mohamed Naafeel

### Software Engineer | Full-Stack Developer | Independent Product Builder

Building software from concept to production, with a focus on real-time systems, full-stack engineering, and practical user experiences.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/naafeel001)
[![Portfolio Project](https://img.shields.io/badge/Play304-Live_Project-D4A63A?style=for-the-badge&logo=googlechrome&logoColor=black)](https://play304.com.lk)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:naafeelmohamed@gmail.com)

Sri Lanka | Software Engineering | Web & Mobile Development

</div>

---

## About Me

I'm a Software Engineer Intern at **Zulacart Pvt Ltd** and a BSc (Hons) Computing Science undergraduate specializing in Software Engineering at **Kingston University London**, through ESOFT Metro Campus.

Alongside software engineering, I contribute to project management and UI/UX design, gaining experience across technical development, product planning, and user experience.

I enjoy building complete software products, from designing the architecture and implementing backend systems to developing responsive interfaces, testing, and deploying applications.

My main areas of interest are:

- Full-stack application development
- Real-time systems and WebSocket communication
- Backend architecture and database design
- Cloud infrastructure and deployment
- UI/UX and product engineering
- Multiplayer game systems and live operations

I am particularly interested in solving engineering problems that involve reliability, data consistency, scalability, and user experience.

---

## Featured Project

<div align="center">

# Play304

### Real-Time Multiplayer Card Game

A traditional partnership card game, rebuilt as a modern online multiplayer experience.

[![Live Application](https://img.shields.io/badge/PLAY_NOW-play304.com.lk-D4A63A?style=for-the-badge&logo=googlechrome&logoColor=black)](https://play304.com.lk)
![Platform](https://img.shields.io/badge/Platform-Web%20%2F%20PWA-15253D?style=flat-square)
![Development](https://img.shields.io/badge/Development-Independent-15253D?style=flat-square)
![Status](https://img.shields.io/badge/Status-Live-20805C?style=flat-square)

</div>

### Project Overview

Play304 is a real-time multiplayer application that brings the traditional 304 card game to the web.

I independently developed the project, working across game logic, frontend development, backend architecture, real-time communication, player progression, UI/UX, and production deployment.

The application goes beyond basic gameplay, combining a server-authoritative multiplayer engine with matchmaking, persistent player accounts, competitive ranking, social features, and an administrative LiveOps platform.

### Core Features

| System | Implementation |
|---|---|
| Real-Time Multiplayer | Four-player partnership gameplay using WebSockets |
| Quick Match | Online matchmaking with AI fallback |
| Ranked 2v2 | Elo-based MMR, competitive tiers, and leaderboards |
| Private Rooms | Room creation, joining, and spectator-safe views |
| Game Engine | Bidding, trump, trick resolution, special rules, and scoring |
| AI Opponents | Medium and Hard bots with strategic decision-making |
| Player Accounts | Guest authentication, Google sign-in, and persistent profiles |
| Progression | XP, levels, achievements, and missions |
| Live-Service Systems | Seasons, season-pass rewards, cosmetics, and virtual currencies |
| Social Features | Friends, invitations, clubs, blocking, and notifications |
| Reliability | Reconnection, match recovery, and AFK handling |
| Owner Console | Player moderation, announcements, maintenance, and LiveOps management |

### Technology Stack

**Frontend**

React 19, TypeScript, React Router 7, Zustand, Tailwind CSS 4, Motion, Vite 6

**Backend**

Cloudflare Workers, TypeScript, WebSockets, Zod

**Real-Time Infrastructure**

Cloudflare Durable Objects, SQLite-backed room persistence, WebSocket session management

**Database and Authentication**

Supabase PostgreSQL, Supabase Auth, Google OAuth, backend-for-frontend authentication

**Development and Testing**

pnpm Workspaces, Vitest, SQLite integration testing, Wrangler, Git, GitHub

### System Architecture

```text
                    PLAY304
                       |
              React / TypeScript
                  Web / PWA
                       |
                       v
              Cloudflare Workers
               Gateway / BFF
                       |
          +------------+------------+
          |                         |
          v                         v
     Game Services             Account Services
          |                         |
          v                         v
     Durable Objects           Supabase PostgreSQL
          |                         |
     WebSocket Rooms           Authentication
     Game State                Player Profiles
     Match Recovery            Ranking / Progression
     Bots / Matchmaking        Social / Economy
          |                         |
          +------------+------------+
                       |
                       v
             Live-Service Platform
                       |
                 Owner Console
```

### Engineering Highlights

**Server-Authoritative Gameplay**

Implemented a centralized game engine responsible for validating player actions, enforcing game rules, and maintaining authoritative match state.

Player-specific projections prevent unauthorized access to hidden cards and other private gameplay information.

**Real-Time Communication**

Developed WebSocket-based multiplayer communication with room coordination, synchronized state updates, reconnection, and persistent game sessions.

**Reliable State Recovery**

Implemented persistent room state, command idempotency, reconnect handling, and recovery mechanisms designed to handle duplicate requests and interrupted connections.

**Competitive Systems**

Developed Ranked matchmaking using Elo-based MMR, competitive tiers, leaderboards, and persistent progression.

**Live-Service Architecture**

Built configurable systems for missions, achievements, rewards, virtual currencies, cosmetics, clubs, and seasonal content.

**Secure Player Identity**

Integrated guest authentication and Google OAuth with server-side session handling, authorization checks, and protected account operations.

### Owner Console and LiveOps

Play304 also includes a dedicated administrative platform for managing the game beyond development.

Its capabilities include:

- Player search and account moderation
- Room and completed-match monitoring
- Operational activity overview
- Maintenance controls and announcements
- Season configuration and publication
- LiveOps content management and rollback
- Economy and club operations
- Administrative authorization and audit records

The Owner Console is a separate, restricted management interface designed to support ongoing game operations.

### Project Status

Play304 is currently available as a browser-based application with Progressive Web App support.

The web version includes the core multiplayer experience, persistent player systems, and LiveOps infrastructure.

Native mobile distribution and real-money monetization integrations remain future development areas.

**Live Application:** https://play304.com.lk

---

## Professional Experience

### Zulacart Pvt Ltd

**Software Engineer Intern**

Gaining practical experience in full-stack software engineering, including frontend development, backend APIs, database-driven applications, and software testing.

Areas of work include:

- REST API development and integration
- Backend application development
- Database design and management
- Responsive web application development
- Authentication and authorization
- Testing, debugging, and application maintenance
- Software development lifecycle practices

**Project Manager — Part-Time**

Contributing to project planning and coordination across software and business initiatives.

Focus areas:

- Requirements gathering and clarification
- Project planning and progress tracking
- Cross-functional coordination
- Stakeholder communication
- Task management and delivery support

**UI/UX Designer — Part-Time**

Contributing to user-focused interface design and usability improvements.

Focus areas:

- Interface design
- User flows and interaction design
- Responsive layouts
- UI consistency and visual design
- Usability analysis and improvements

---

## Technical Skills

### Languages

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C#](https://img.shields.io/badge/C%23-68217A?style=flat-square&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square)

### Frontend

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white)
![Material UI](https://img.shields.io/badge/Material_UI-007FFF?style=flat-square&logo=mui&logoColor=white)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jquery&logoColor=white)

### Backend and APIs

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![Cloudflare Workers](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=cloudflareworkers&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-Real_Time-23466C?style=flat-square)
![REST API](https://img.shields.io/badge/REST_API-005571?style=flat-square)

### Databases

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=black)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logoColor=white)

### Mobile Development

![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![PWA](https://img.shields.io/badge/Progressive_Web_Apps-5A0FC8?style=flat-square&logo=pwa&logoColor=white)

### Development Tools

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)

---

## Other Projects

### Velvet Vogue — E-Commerce Platform

A full-stack e-commerce application built as an academic software engineering project.

**Features:** Authentication, product and category management, shopping cart, order processing, and administration.

**Stack:** PHP, MySQL, Bootstrap, JavaScript, jQuery, AJAX

[View Repository](https://github.com/Naafeel/velvet-vogue)

### Doctor Channelling System

A Java-based appointment management system developed using object-oriented programming principles.

**Features:** Doctor management, patient management, appointment scheduling, and data management.

**Stack:** Java, OOP

[View Repository](https://github.com/Naafeel/DoctorChannelingSystem)

### FreshMartCity — Online Grocery System

A database-driven grocery application supporting customer and product management workflows.

**Features:** Product browsing, authentication, cart management, order processing, and database integration.

**Stack:** PHP, MySQL, HTML, CSS, Bootstrap, JavaScript

[View Repository](https://github.com/Naafeel/FreshMartCity)

---

## Internship Training Projects

The following applications were developed as structured training projects and are separate from Zulacart's private production systems.

| Project | Technologies | Repository |
|---|---|---|
| Product & Order Management System | Laravel, PHP, MySQL, Blade | [View](https://github.com/Naafeel/laravel-product-order-management-system) |
| E-Commerce REST API | Node.js, Express, PostgreSQL, JWT | [View](https://github.com/Naafeel/zulacart-node-api) |
| E-Commerce Admin Dashboard | React, Material UI, REST APIs | [View](https://github.com/Naafeel/react-mui-ecommerce-admin-dashboard) |
| Mini E-Commerce Mobile Application | React Native, JavaScript, REST APIs | [View](https://github.com/Naafeel/Mini-Ecommerce-Full-Stack-System) |

These projects strengthened my practical knowledge of authentication, API development, CRUD operations, database integration, responsive interfaces, and application testing.

---

## Education

### BSc (Hons) Computing Science — Software Engineering

**Kingston University London**  
Via ESOFT Metro Campus

Expected completion: **2027**

### Pearson BTEC Higher National Diploma in Computing — Software Engineering

**London Metropolitan University**  
Via ESOFT Metro Campus

Completed: **January 2026**

### Level 3 Diploma in Information Technology

**London Metropolitan University / ESOFT Metro Campus**

Completed: **June 2025**

**Academic Achievements**

- 10 Distinctions and 1 Merit
- Top Performer Award
- Gold Medal

---

## Current Focus

My current areas of development and professional growth include:

- Building and operating Play304
- Cloud-native backend architecture
- Distributed and real-time systems
- System design and application scalability
- Secure authentication and authorization
- Testing and production reliability
- Mobile and cross-platform development
- DevOps and release engineering
- Data structures and algorithms
- Software product development

---

## GitHub Activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Naafeel&show_icons=true&theme=github_dark&hide_border=true" alt="GitHub Statistics" height="170" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Naafeel&layout=compact&theme=github_dark&hide_border=true" alt="Most Used Languages" height="170" />

<img src="https://streak-stats.demolab.com?user=Naafeel&theme=github-dark-blue&hide_border=true" alt="GitHub Contribution Streak" />

</div>

---

## Connect

I'm interested in software engineering, full-stack development, real-time systems, and opportunities to collaborate on meaningful technology projects.

<div align="center">

[LinkedIn](https://www.linkedin.com/in/naafeel001) |
[GitHub](https://github.com/Naafeel) |
[Play304](https://play304.com.lk) |
[Email](mailto:naafeelmohamed@gmail.com)

</div>

---

<div align="center">

<em>Building software with a focus on engineering quality, usability, and real-world impact.</em>

</div>
