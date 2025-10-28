# Multi-Framework Ticket Web App — TicketApp

This repository contains **three separate implementations** of the TicketApp, a ticket management web application. Each version is built with a different frontend framework: **React, Vue.js, and Twig (PHP + Twig)**. All versions share the **same layout, features, and functionality** for a consistent user experience.

---

## Table of Contents

- [Overview](#overview)  
- [Features](#features)  
- [Framework Implementations](#framework-implementations)  
- [Test Credentials](#test-credentials)  
- [License](#license)  

---

## Overview

TicketApp is a **full-featured ticket management system** that demonstrates mastery of frontend frameworks, state management, form logic, UI consistency, and responsive design.  

Core requirements:

- Landing page with hero section, wavy SVG, decorative circles, and CTA buttons  
- Authentication (Login/Signup) with inline validation and toast/snackbar messages  
- Dashboard with ticket statistics  
- Full ticket CRUD (Create, Read, Update, Delete) with validation and feedback  
- Responsive design, accessible HTML, and consistent layout across frameworks  

---

## Features

- **Landing Page** with max-width 1440px, centered content, wavy hero background, decorative circles, and cards for feature highlights  
- **Authentication**: Simulated using localStorage or PHP session, with error handling and redirection  
- **Dashboard**: Shows total, open, and resolved tickets with navigation links  
- **Ticket Management**: Full CRUD with validation, success/error messages, and status color coding  
- **Responsive & Accessible**: Mobile, tablet, and desktop layouts; semantic HTML; alt text; focus states  

---

## Framework Implementations

Each implementation is a **complete and separate project**:

| Framework | Directory | Setup & Usage |
|-----------|-----------|---------------|
| **React + TypeScript** | [GITHUB`https://github.com/Avan-Kel/HNG-FE-GRADE-2-REACT.git/`] vercel(https://hng-fe-grade-2-react-git-main-promises-projects-3ed1ac1b.vercel.app) | `php -S localhost:8000 -t public` |
-----
| **Twig (PHP)** | [GITHUB`https://github.com/Avan-Kel/HNG-FE-GRADE-2-TWIG.git/`](https://hng-fe-grade-2-twig-production.up.railway.app) | `npm install && npm run dev` |
| **Vue 3 + TypeScript** | [GITHUB`https://github.com/Avan-Kel/HNG-FE-GRADE-2-VUE.git/`](vue-ticket-app) | `npm install && npm run dev` |


> Each directory contains a dedicated `README.md` with detailed setup instructions, folder structure, and usage examples.  

---

## Test Credentials

Use these test credentials across all implementations for quick testing:

```txt
Email: test@example.com
Password: Test1234
