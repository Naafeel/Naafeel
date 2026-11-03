
<div align="center">

# Mohamed Munavver Mohamed Naafeel

### Software Engineer | Full-Stack Developer | Independent Product Builder

Designing, building, and deploying software products with a focus on real-time systems, backend architecture, and practical user experiences.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/naafeel001)
[![Play304](https://img.shields.io/badge/Play304-Live_Project-CDA34F?style=for-the-badge&logo=googlechrome&logoColor=black)](https://play304.com.lk)
[![GitHub](https://img.shields.io/badge/GitHub-Naafeel-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Naafeel)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:naafeelmohamed@gmail.com)

**Sri Lanka | Full-Stack Engineering | Cloud & Real-Time Systems**

</div>

---

## About Me

I'm a Software Engineer Intern at **Zulacart Pvt Ltd** and a BSc (Hons) Computing Science undergraduate specializing in Software Engineering at **Kingston University London**, through ESOFT Metro Campus.

Alongside software engineering, I contribute to project management and UI/UX design, gaining experience across technical development, product planning, and user experience.

I enjoy building complete software products, from designing architecture and implementing backend systems to developing responsive interfaces, testing, deployment, and production maintenance.

My work includes independently developing a real-time multiplayer gaming platform and building production business applications used for daily operational and financial workflows.

My primary areas of interest include:

- Full-stack web and application development
- Backend architecture and database engineering
- Real-time systems and WebSocket communication
- Cloud infrastructure and deployment
- Secure authentication and authorization
- Software architecture and system design
- UI/UX and product engineering
- Production reliability and performance optimization

I am particularly interested in engineering challenges involving data consistency, transactional reliability, scalability, security, and real-world user experience.

---

# Featured Projects

## 01. Play304

<div align="center">

### Real-Time Multiplayer Card Game & Live-Service Platform

A traditional partnership card game, rebuilt as a modern online multiplayer experience.

[![Live Application](https://img.shields.io/badge/PLAY_NOW-play304.com.lk-CDA34F?style=for-the-badge&logo=googlechrome&logoColor=black)](https://play304.com.lk)

![Platform](https://img.shields.io/badge/Platform-Web%20%2F%20PWA-15253D?style=flat-square)
![Development](https://img.shields.io/badge/Development-Independent-15253D?style=flat-square)
![Status](https://img.shields.io/badge/Status-Live-20805C?style=flat-square)

</div>

### Project Overview

Play304 is a real-time multiplayer application that brings the traditional 304 card game to the web.

I independently designed, developed, and deployed the application, working across game logic, frontend development, backend architecture, real-time communication, player progression, UI/UX, and production deployment.

The application goes beyond basic gameplay, combining a server-authoritative multiplayer engine with persistent player accounts, matchmaking, competitive ranking, social features, and a dedicated administrative LiveOps platform.

The architecture focuses on secure game-state management, hidden-information protection, reliable session recovery, and scalable cloud-based services.

### Core Features

| System | Implementation |
|---|---|
| Real-Time Multiplayer | Four-player partnership gameplay using WebSockets |
| Quick Match | Online matchmaking with AI fallback |
| Ranked 2v2 | Elo-based MMR, competitive tiers, and leaderboards |
| Private Rooms | Room creation, joining, and spectator-safe gameplay |
| Game Engine | Bidding, trump, trick resolution, special rules, and scoring |
| AI Opponents | Medium and Hard bots with strategic decision-making |
| Player Accounts | Guest authentication, Google sign-in, and persistent profiles |
| Player Progression | XP, levels, achievements, and missions |
| Live-Service Systems | Seasons, rewards, cosmetics, and virtual currencies |
| Social Features | Friends, invitations, clubs, blocking, and notifications |
| Reliability | Reconnection, match recovery, and AFK handling |
| Owner Console | Moderation, announcements, maintenance, and LiveOps management |

### Technology Stack

**Frontend**

React 19, TypeScript, React Router 7, Zustand, Tailwind CSS 4, Motion, Vite 6

**Backend**

Cloudflare Workers, TypeScript, WebSockets, Zod

**Real-Time Infrastructure**

Cloudflare Durable Objects, SQLite-backed persistence, WebSocket session management

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

Implemented a centralized game engine responsible for validating player actions, enforcing rules, and maintaining authoritative match state.

Player-specific state projections protect hidden cards and prevent unauthorized access to private gameplay information.

**Real-Time Communication**

Developed WebSocket-based multiplayer communication with room coordination, synchronized updates, persistent session state, and reconnection.

**Reliable State Recovery**

Implemented persistent room state, command idempotency, reconnect handling, and recovery mechanisms to handle duplicate requests and interrupted connections.

**Competitive Systems**

Developed Ranked matchmaking using Elo-based MMR, competitive tiers, leaderboards, and persistent progression.

**Live-Service Architecture**

Built configurable systems for missions, achievements, rewards, virtual currencies, cosmetics, clubs, and seasonal content.

**Secure Player Identity**

Integrated guest authentication and Google OAuth with server-side session handling, authorization checks, and protected account operations.

### Owner Console and LiveOps

Play304 includes a dedicated administrative platform for managing the game beyond development.

Key capabilities include:

- Player search and account moderation
- Room and completed-match monitoring
- Operational activity overview
- Maintenance controls and announcements
- Season configuration and publication
- LiveOps content management and rollback
- Economy and club operations
- Administrative authorization and audit records

The Owner Console is a restricted management interface designed to support ongoing game operations.

### Project Status

Play304 is currently available as a browser-based application with Progressive Web App support.

The web version includes the core multiplayer experience, persistent player systems, competitive features, and LiveOps infrastructure.

Native mobile distribution and real-money monetization integrations remain future development areas.

**Live Application:** https://play304.com.lk

---

## 02. HS Deals Operations

<div align="center">

### Production Business Operations Platform

**HS Deals & Offline.lk**

A dual-workspace business management system for sales, repairs, customized gift orders, purchasing, payments, expenses, operational workflows, and financial reporting.

![Status](https://img.shields.io/badge/Status-Production-20805C?style=flat-square)
![Platform](https://img.shields.io/badge/Platform-Web_Application-15253D?style=flat-square)
![Access](https://img.shields.io/badge/Access-Private_Internal_System-15253D?style=flat-square)

</div>

### Project Overview

HS Deals Operations is a production business management platform developed for two connected business workflows:

**HS Deals**

Laptop and PC sales, repairs, services, customer payments, operational expenses, and profitability tracking.

**Offline.lk**

Customized gift orders, material purchasing, supplier coordination, production tasks, payments, refunds, expenses, and financial reporting.

The platform uses a shared customer model while maintaining operational separation between both businesses through role-based authorization, workspace permissions, and Supabase Row Level Security.

I developed the application across frontend architecture, database design, transactional workflows, authentication, authorization, reporting, production deployment, performance optimization, and ongoing real-world issue resolution.

The project emphasizes financial accuracy, operational traceability, secure data access, and workflows designed around actual business requirements.

### Core Features

| System | Implementation |
|---|---|
| Dual Workspaces | Separate HS Deals and Offline.lk environments with shared authentication |
| Role-Based Access | Admin and Staff roles, workspace assignments, permission overrides, and RLS |
| Offline.lk Orders | Custom gift orders with configurable products, suppliers, quantities, and pricing |
| Buying List | Supplier-grouped purchasing, partial purchases, remaining quantities, and order references |
| Work & Tasks | Office and outsourced production queues with status and actual-cost tracking |
| HS Deals Sales | Laptop, PC, accessory, and service sales with payment and profit tracking |
| HS Deals Repairs | Repair intake, technician workflow, parts costs, payments, and delivery tracking |
| Payments | Advance payments, balances, overpayments, and controlled corrections |
| Returns & Refunds | Partial and full refunds with preserved payment history |
| Expenses | Order-specific and general business expense management |
| Financial Reporting | Revenue, costs, refunds, gross profit, net profit, and outstanding balances |
| Catalog Management | Products, suppliers, categories, options, recipes, and safe archiving |
| Customer Management | Shared customer records, phone validation, and normalized duplicate lookup |
| Admin Console | Invitations, roles, workspace access, settings, and activity logs |
| Audit & History | Historical snapshots, activity tracking, and financial traceability |
| Responsive UX | Desktop and mobile workflows with optimized forms and search |

### Offline.lk Operational Workflow

```text
WhatsApp Customer Order
        |
        v
Create Order
        |
        v
Choose Categories & Materials
        |
        +----------------------------+
        |                            |
        v                            v
Purchase Requirements          Office / Outsourced Work
        |                            |
        v                            v
Supplier Buying List           Work & Task Queue
        |                            |
        v                            v
Partial / Full Purchase        Status + Actual Cost
        |                            |
        +-------------+--------------+
                      |
                      v
              Order Completion
                      |
                      v
        Payments / Refunds / Expenses
                      |
                      v
           Profit & Financial Reports
```

### Engineering Highlights

**Transactional Order Creation**

Implemented atomic PostgreSQL RPC-based order creation covering order headers, category sections, items, purchase requirements, and initial payments.

This approach reduces the risk of partially created orders and inconsistent operational records.

**Database Security and Authorization**

Implemented Supabase Authentication with active-user verification, workspace-based authorization, Row Level Security policies, role permissions, and Admin/Staff access enforcement.

Access controls are applied across operational and financial data.

**Historical Data Integrity**

Designed catalog and operational workflows to preserve historical snapshots.

Products, suppliers, and materials can be archived or safely removed from active workflows without destroying historical order, purchasing, or accounting information.

**Financial Accuracy**

Separated selling prices, estimated costs, actual incurred costs, customer payments, refunds, and business expenses into distinct financial concepts.

Profit calculations use actual costs and applicable expenses, while payments are tracked separately as cash collection.

**Production Performance Optimization**

Optimized frequently used workflows such as:

- Buying List updates
- Actual-cost entry
- Production status changes
- Modal and form submissions
- Product searching
- Operational record updates

Techniques include lean Supabase queries, targeted state updates, optimistic UI, request deduplication, and reduced unnecessary refetching.

**Responsive Operational UX**

Designed workflows around real user tasks, including:

- Fast product searching
- Modal-based order configuration
- Responsive desktop and mobile interfaces
- Branded confirmation dialogs
- Clear validation and feedback
- Efficient order and purchasing forms

**Production Reliability**

Resolved real-world issues involving:

- Database query cardinality
- Phone number normalization
- Duplicate customer identification
- Safe material removal
- Payment correction
- Refund consistency
- Missing-cost detection
- Supplier dependency protection
- Historical data preservation

Changes were implemented with attention to existing production data and operational continuity.

### Technology Stack

**Frontend**

Next.js App Router, React, TypeScript, Tailwind CSS, React Hook Form, Zod, Lucide, Sonner, Recharts

**Backend and Database**

Supabase PostgreSQL, Supabase Auth, Row Level Security, PostgreSQL RPC functions, database triggers

**Deployment and Tooling**

Vercel, Git, GitHub, Supabase CLI, ESLint, TypeScript, production build validation

### Project Status

HS Deals Operations is deployed and actively used as an internal production operations system.

The platform supports real business workflows across sales, repairs, custom orders, purchasing, production, payments, expenses, and financial reporting.

Because the application manages private customer, financial, business, and administrative information, the production system and source repository are not publicly linked.

---

# Professional Experience

## Zulacart Pvt Ltd

### Software Engineer Intern

Gaining practical experience in full-stack software engineering, including frontend development, backend APIs, database-driven applications, and software testing.

**Areas of Work**

- REST API development and integration
- Backend application development
- Database design and management
- Responsive web application development
- Authentication and authorization
- Testing, debugging, and application maintenance
- Software development lifecycle practices

### Project Manager — Part-Time

Contributing to project planning and coordination across software and business initiatives.

**Focus Areas**

- Requirements gathering and clarification
- Project planning and progress tracking
- Cross-functional coordination
- Stakeholder communication
- Task management and delivery support

### UI/UX Designer — Part-Time

Contributing to user-focused interface design and usability improvements.

**Focus Areas**

- Interface design
- User flows and interaction design
- Responsive layouts
- UI consistency and visual design
- Usability analysis and improvements

---

# Technical Skills

## Programming Languages

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C#](https://img.shields.io/badge/C%23-68217A?style=flat-square&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square)

## Frontend Development

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white)
![Material UI](https://img.shields.io/badge/Material_UI-007FFF?style=flat-square&logo=mui&logoColor=white)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jquery&logoColor=white)

## Backend and APIs

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![Cloudflare Workers](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=cloudflareworkers&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-Real_Time-23466C?style=flat-square)
![REST API](https://img.shields.io/badge/REST_API-005571?style=flat-square)

## Databases and Backend Services

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=black)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logoColor=white)

## Cloud, Deployment, and Testing

![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logoColor=white)

## Mobile Development

![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![PWA](https://img.shields.io/badge/Progressive_Web_Apps-5A0FC8?style=flat-square&logo=pwa&logoColor=white)

---

# Other Projects

## Velvet Vogue — E-Commerce Platform

A full-stack e-commerce application developed as an academic software engineering project.

**Features**

- Customer authentication
- Product and category management
- Shopping cart
- Order processing
- Administrative management
- Database-driven workflows

**Technologies:** PHP, MySQL, Bootstrap, JavaScript, jQuery, AJAX

[View Repository](https://github.com/Naafeel/velvet-vogue)

---

## Doctor Channelling System

A Java-based appointment management system developed using object-oriented programming principles.

**Features**

- Doctor management
- Patient management
- Appointment scheduling
- Data management
- Console-based workflows

**Technologies:** Java, OOP

[View Repository](https://github.com/Naafeel/DoctorChannelingSystem)

---

## FreshMartCity — Online Grocery System

A database-driven grocery application supporting customer and product management workflows.

**Features**

- Product browsing
- Customer authentication
- Shopping cart
- Product management
- Order processing
- Database integration

**Technologies:** PHP, MySQL, HTML, CSS, Bootstrap, JavaScript

[View Repository](https://github.com/Naafeel/FreshMartCity)

---

# Internship Training Projects

The following applications were developed as structured training projects and are separate from Zulacart's private production systems.

| Project | Technologies | Repository |
|---|---|---|
| Product & Order Management System | Laravel, PHP, MySQL, Blade | [View](https://github.com/Naafeel/laravel-product-order-management-system) |
| E-Commerce REST API | Node.js, Express, PostgreSQL, JWT | [View](https://github.com/Naafeel/zulacart-node-api) |
| E-Commerce Admin Dashboard | React, Material UI, REST APIs | [View](https://github.com/Naafeel/react-mui-ecommerce-admin-dashboard) |
| Mini E-Commerce Mobile Application | React Native, JavaScript, REST APIs | [View](https://github.com/Naafeel/Mini-Ecommerce-Full-Stack-System) |

These projects strengthened my experience with authentication, REST APIs, CRUD workflows, database integration, responsive interfaces, mobile development, testing, and application design.

---

# Education

## BSc (Hons) Computing Science — Software Engineering

**Kingston University London**

Via ESOFT Metro Campus

**Expected completion:** 2027

---

## Pearson BTEC Higher National Diploma in Computing — Software Engineering

**London Metropolitan University**

Via ESOFT Metro Campus

**Completed:** January 2026

---

## Level 3 Diploma in Information Technology

**London Metropolitan University / ESOFT Metro Campus**

**Completed:** June 2025

**Academic Achievements**

- 10 Distinctions
- 1 Merit
- Top Performer Award
- Gold Medal

---

# Engineering Interests

I am interested in building software that solves practical problems and continues to operate reliably beyond initial deployment.

My current focus includes:

- Production full-stack application development
- Cloud-native backend architecture
- Distributed and real-time systems
- Database transactions and data integrity
- Secure authentication and authorization
- System design and application scalability
- Performance optimization
- Production reliability and testing
- Mobile and cross-platform engineering
- DevOps and release management
- Software product development

---

# GitHub Activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Naafeel&show_icons=true&theme=github_dark&hide_border=true" alt="GitHub Statistics" height="170" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Naafeel&layout=compact&theme=github_dark&hide_border=true" alt="Most Used Languages" height="170" />

<img src="https://streak-stats.demolab.com?user=Naafeel&theme=github-dark-blue&hide_border=true" alt="GitHub Contribution Streak" />

</div>

---

# Connect

I'm interested in software engineering opportunities, technical collaborations, and building meaningful software products.

<div align="center">

[LinkedIn](https://www.linkedin.com/in/naafeel001) |
[GitHub](https://github.com/Naafeel) |
[Play304](https://play304.com.lk) |
[Email](mailto:naafeelmohamed@gmail.com)

</div>

---

<div align="center">

*Building software with a focus on engineering quality, reliability, usability, and real-world impact.*

</div>
