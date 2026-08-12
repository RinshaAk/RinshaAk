<div align="center">

# Fathima Rinsha

### Software Developer · Full-Stack Web Development

Building web applications, backend systems, and production-oriented software with modern JavaScript technologies.

I enjoy solving real-world problems, designing application architecture, and turning ideas into reliable products.

<br />

<a href="https://github.com/fathimarinsha794">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

<a href="https://www.linkedin.com/in/rinshaak">
<img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>

<a href="https://fathima-rinsha-ak.vercel.app/">
<img src="https://img.shields.io/badge/Portfolio-111111?style=for-the-badge&logo=vercel&logoColor=white" />
</a>

</div>

---

## About

I'm a Software Developer focused on building full-stack web applications across the frontend, backend, database, and deployment layers.

My primary experience is with the JavaScript ecosystem, particularly React, Node.js, Express, and MongoDB.

I enjoy working on systems that involve authentication, APIs, databases, real-time communication, third-party integrations, and cloud deployment.

Currently, I'm focused on building more production-ready applications and strengthening my knowledge of system design, backend architecture, cloud infrastructure, and application security.

* Full-stack web development
* REST API development
* Authentication & authorization
* Role-based access control
* Database design
* Real-time applications
* Third-party API integrations
* Cloud deployment
* SaaS application development
* Open-source development

---

# Tech Stack

### Languages

<p>
<img src="https://skillicons.dev/icons?i=javascript,typescript,html,css,python" />
</p>

### Frontend

<p>
<img src="https://skillicons.dev/icons?i=react,nextjs,redux,tailwind,vite" />
</p>

### Backend

<p>
<img src="https://skillicons.dev/icons?i=nodejs,express" />
</p>

### Database

<p>
<img src="https://skillicons.dev/icons?i=mongodb" />
</p>

### DevOps & Tools

<p>
<img src="https://skillicons.dev/icons?i=git,github,docker,aws,vercel,postman,vscode,npm" />
</p>

### Technologies

`TypeScript` `JWT` `OAuth` `REST APIs` `Socket.IO` `WebRTC` `Razorpay` `Better Auth` `Mongoose`

---

# Current Project

## Adlynx

### SaaS Marketing Analytics & Lead Management Platform

**Adlynx** is a SaaS platform designed for digital marketing agencies to manage multiple clients, advertising reports, campaign performance, leads, follow-ups, AI-generated insights, and subscriptions from one centralized platform.

The platform is designed around a multi-tenant architecture where agencies can manage multiple clients while keeping client data isolated and secure.

### Core Capabilities

* Multi-agency and multi-client management
* Role-based access control
* Agency, Client, and Admin workflows
* Client invitation and management
* Meta Ads report processing
* Google Ads report processing
* CSV and Excel report uploads
* Campaign performance analytics
* Lead management
* Lead status tracking
* Follow-up management
* Lead history
* Activity logging
* AI-generated campaign summaries
* Subscription and billing management
* Razorpay integration
* Razorpay webhook verification
* Admin monitoring
* Authentication with Better Auth

### Architecture

```text
Agency
   │
   ├── Clients
   │      ├── Client Users
   │      ├── Leads
   │      └── Campaign Reports
   │
   ├── Subscriptions
   │
   └── Activity Logs
```

### Campaign Reporting Flow

```text
Meta Ads / Google Ads
        ↓
   CSV / Excel Report
        ↓
     Adlynx Upload
        ↓
   File Validation
        ↓
   Data Processing
        ↓
 Metric Calculation
        ↓
     Dashboard
        ↓
   AI Performance Summary
```

### Lead Management

```text
New
 ↓
Contacted
 ↓
Interested
 ↓
Qualified
 ↓
Converted
```

The system also supports remarks, follow-up dates, lead history, and campaign-source tracking.

### AI Insights

Adlynx processes selected campaign metrics through an AI provider to generate understandable campaign summaries instead of presenting clients with raw numbers alone.

```text
Campaign Metrics
       ↓
   Data Sanitization
       ↓
      AI Model
       ↓
 Response Validation
       ↓
   Campaign Summary
```

The system also includes a fallback mechanism when the AI provider is unavailable.

### Billing

The SaaS platform includes subscription management with Razorpay.

```text
Agency
  ↓
Choose Plan
  ↓
Razorpay Checkout
  ↓
Payment
  ↓
Webhook
  ↓
Backend Verification
  ↓
Subscription Activation
```

Webhook signatures are verified before subscription-related events are processed.

### Backend Architecture

```text
Request
   ↓
Route
   ↓
Controller
   ↓
Validation
   ↓
Service
   ↓
Database
```

The backend follows a modular architecture separating routes, controllers, services, validation, and models.

### Tech Stack

`Next.js` `React` `TypeScript` `Tailwind CSS`

`Node.js` `Express.js` `MongoDB` `Mongoose`

`Better Auth` `Joi` `Razorpay`

`Gemini AI` `Docker` `AWS` `Turborepo` `pnpm`

### Deployment

```text
Internet
   ↓
adlynx.online
   ↓
Next.js Frontend
   ↓
API
   ↓
Node.js / Express Backend
   ↓
MongoDB
```

### Current Focus

I'm currently working on:

* Production readiness
* Backend architecture
* Application security
* API validation
* Role-based authorization
* Multi-tenant data isolation
* Error handling
* Deployment
* Performance
* Scalability
* Maintainability

---

# Completed Projects

## Learnify

### Learning Management System

Learnify is a full-stack Learning Management System designed for students, instructors, and administrators.

### Features

* Student, Instructor, and Admin workflows
* Course creation and enrollment
* JWT authentication
* Google OAuth
* OTP verification
* Role-based authorization
* Razorpay payments
* Certificate generation
* Real-time notifications
* Real-time chat
* WebRTC live classes
* Video, audio, and screen sharing
* Responsive interface

### Tech Stack

`React` `Redux` `Tailwind CSS` `Node.js` `Express.js` `MongoDB`

`Socket.IO` `WebRTC` `JWT` `OAuth` `Razorpay`

**Live:**
https://single-project-learnify.vercel.app/

---

## FoodSnap AI

### AI-Powered Food Analysis Application

FoodSnap AI is a web application that analyzes uploaded food images and provides nutrition-related information.

### Features

* Food image upload
* AI-powered food analysis
* Nutrition information
* Authentication
* User dashboard
* Cloud image storage

### Tech Stack

`React` `Express.js` `MongoDB` `Cloudinary`

---

## Personal Portfolio

### Developer Portfolio

A personal portfolio website showcasing my projects, technical skills, and development work.

### Tech Stack

`React` `JavaScript` `Vercel`

**Live:**
https://fathima-rinsha-ak.vercel.app/

---

# Currently Learning

I'm continuously improving my knowledge in:

* TypeScript
* Next.js
* Advanced React
* Backend Architecture
* System Design
* Docker
* AWS
* Data Structures & Algorithms
* Cloud Infrastructure
* Application Security

I prefer learning by building real applications, debugging problems, deploying projects, and improving existing systems.

---

# Engineering Interests

* Full-stack architecture
* Backend engineering
* REST API design
* SaaS architecture
* Multi-tenant applications
* Authentication & authorization
* Database architecture
* Real-time systems
* Cloud infrastructure
* Application security
* System design
* Open-source software

---

# GitHub Statistics

<div align="center">

<img
src="https://github-readme-stats.vercel.app/api?username=fathimarinsha794&show_icons=true&hide_border=true&theme=tokyonight&count_private=true"
alt="GitHub Statistics"
/>

<br />
<br />

<img
src="https://github-readme-streak-stats.herokuapp.com/?user=fathimarinsha794&theme=tokyonight&hide_border=true"
alt="GitHub Streak"
/>

</div>

---

# Most Used Languages

<div align="center">

<img
src="https://github-readme-stats.vercel.app/api/top-langs/?username=fathimarinsha794&layout=compact&hide_border=true&theme=tokyonight"
alt="Most Used Languages"
/>

</div>

---

# Let's Connect

<div align="center">

<a href="https://www.linkedin.com/in/rinshaak">
<img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>

<a href="https://fathima-rinsha-ak.vercel.app/">
<img src="https://img.shields.io/badge/Portfolio-Visit-111111?style=for-the-badge&logo=vercel&logoColor=white" />
</a>

<a href="https://github.com/fathimarinsha794">
<img src="https://img.shields.io/badge/GitHub-Profile-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

</div>

<br />

<div align="center">

**Build • Learn • Improve**

</div>
