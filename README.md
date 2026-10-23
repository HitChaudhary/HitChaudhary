<div align="center">

# Hey, I'm Hit Chaudhary 👋

**Full-Stack MERN Developer** • React • Node.js • TypeScript • MongoDB • PostgreSQL

[![Portfolio](https://img.shields.io/badge/Portfolio-hit--chaudhary.onrender.com-14284b?style=flat-square&logo=googlechrome&logoColor=white)](https://hit-chaudhary.onrender.com/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-hit--chaudhary-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hit-chaudhary)
[![Email](https://img.shields.io/badge/Email-hitchaudhary093@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:hitchaudhary093@gmail.com)

</div>

---

## 🙋‍♂️ About Me

I'm a full-stack developer who builds secure, multi-tenant web applications, from database design and REST APIs to a polished React frontend and live deployment. I completed a MERN internship delivering 4+ client projects, and I've independently built and deployed three full-stack apps with JWT authentication and role-based access control.

- 🔭 **Currently Building:** Multi-tenant SaaS platforms and product-based applications
- 🛠️ **Core Stack:** React, Node.js, Express, TypeScript, MongoDB, PostgreSQL
- 🌱 **Learning & Refining:** python , typescript fundamentals
- 💼 **Open To:** Full-Stack / React & Node.js / Software Developer roles
- 📍 **Based in:** Idar, Gujarat, India

## 🛠️ Tech Stack

**Frontend**
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-v4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

**Backend**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![tRPC](https://img.shields.io/badge/tRPC-398CCB?style=flat-square&logo=trpc&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-Auth-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

**Tools**
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=flat-square&logo=cloudinary&logoColor=white)

---

## 🚀 Featured Projects

### 📍 [Presenso](https://github.com/HitChaudhary/Presenso-Presence-Workforce-Management-Platform)
> Multi-tenant workforce attendance with QR + GPS geofence verification

A mobile-first attendance platform that replaces costly fingerprint hardware with the phone employees already carry. Attendance is accepted only when the signed QR session, the office assignment, and the GPS geofence all agree **on the server**.

- Rotating, signed, time-bound QR sessions with server-side expiry checks
- Server-side geofence validation (Haversine distance against the office radius)
- Organization hierarchy: Super Admin → Org Admin → Office → Employee, with strict organization isolation
- Leave approval workflow, correction requests, audit trail, and CSV export
- Live presence and analytics dashboards

`React 19` `TypeScript` `Node.js` `Express` `tRPC` `PostgreSQL` `Drizzle ORM` `Tailwind CSS v4` • **[Live Demo →](https://presenso-presence-workforce-management.onrender.com/)**

---

### 🔗 [Qrfolio](https://github.com/HitChaudhary/Qrfolio)
> Dynamic QR platform for branded QR codes and a complete digital business presence

Businesses create one profile, add all their links (menu, Google Maps, Instagram, WhatsApp, reviews), and download a branded QR code. Customers scan it and land on one clean page; owners see scan and click analytics.

- Branded QR codes with the business logo, downloadable as PNG or SVG
- Scan and link-click analytics using race-safe, per-day atomic counters (no personal data stored)
- JWT auth, bcrypt, admin role checks, owner-scoped queries, Helmet, and rate limiting
- Cloudinary logo upload with file type and size validation
- User dashboard, admin panel, and a Google Review Assistant

`React 18` `TypeScript` `Node.js` `Express` `MongoDB` `JWT` `Cloudinary` `Tailwind CSS v4` • **[Live Demo →](https://qrfolio-one.vercel.app)**

---

### 🎓 [Zubi Dubi School ERP](https://github.com/HitChaudhary/zubi-dubi-school-erp)
> Multi-tenant SaaS school management platform

Each school is an isolated tenant with its own admin, teachers, and students, while a Super Admin oversees all schools on the platform.

- 4-role RBAC: Super Admin / School Admin / Teacher / Student
- Tenant isolation enforced by scoping every query to a `schoolId` taken from a verified JWT
- Assignments engine with submissions, grading, and feedback
- Live class meetings through Jitsi, Zoom, or Google Meet links
- Self-service school registration with Super Admin approval

`React` `Vite` `Node.js` `Express 5` `PostgreSQL` `Prisma` `JWT` `Tailwind CSS`

---

## 📂 More Projects

- 🛒 **[SuperMart POS](https://github.com/HitChaudhary/Supermart-POS)**: Multi-tenant point-of-sale where a Super Admin manages independent retail businesses, each with its own admin, cashiers, stock, and reports. GST billing, partial payments, and data isolation per business via `adminId` scoping. `React` `Node.js` `Express` `MongoDB` • **[Live Demo →](https://supermart-pos-zji3.vercel.app/login)**
- 🍽️ **[Restaurant & Cafe Management](https://github.com/HitChaudhary/Restaurant-Cafe-Management)**: POS for a dual-mode restaurant and self-order cafe, with a table grid, a Kanban kitchen board, and automatic GST billing. `React` `Node.js` `Express` `MongoDB` `Chart.js`
- 🏫 **[College Management System](https://github.com/HitChaudhary/college-Management)**: Digital system replacing manual college paperwork. `React` `Node.js` `Express` `MongoDB` • **[Live Demo →](https://college-management-web.vercel.app)**

---

## 📊 GitHub Stats

<div align="center">

![Hit's GitHub Stats](https://github-readme-stats.vercel.app/api?username=HitChaudhary&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=HitChaudhary&layout=compact&theme=dark&hide_border=true&bg_color=0d1117&title_color=58a6ff)

</div>

---

## 📫 Let's Connect

I'm actively looking for a full-stack developer role. If you're hiring or building something interesting, feel free to reach out.

[![Portfolio](https://img.shields.io/badge/View_Portfolio-14284b?style=for-the-badge&logo=googlechrome&logoColor=white)](https://hit-chaudhary.onrender.com/)
[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hit-chaudhary)
[![Email](https://img.shields.io/badge/Send_an_Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hitchaudhary093@gmail.com)

---

<div align="center">
<sub>Built with React, Node.js, and a lot of chai ☕</sub>
</div>
