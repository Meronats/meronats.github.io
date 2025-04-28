---
layout: posts
title: "CS Portfolio Hosting Application"
date: 2025-04-26 10:00:00 +0000
categories: 
  - work
tagline: "Hosting student portfolios securely and efficiently"
tags:
  - Fullstack
  - Collaboration
description: A file hosting system for Minnesota State University student portfolios with external sharing via Google Sites.
highlight_home: true
header:
  teaser: https://mankato.mnsu.edu/globalassets/brand-hub/flame_m-state_maverick/mav-words.jpg
  caption: CS Portfolio Hosting Application
---

CS Portfolio Hosting Application

<!-- Add your GitHub repo link here [GitHub Repository](#)  -->

---

# About the Project
During my time at Minnesota State University, I contributed to the development of a web application designed to securely host student portfolios for the Computer Science and Twin Cities Engineering programs. The platform plays a critical role in accreditation processes by storing portfolio artifacts and also provides a way for students to visually share their work through Google Sites integration.

---

## The Problem

- Manual portfolio submission process
- Difficulty maintaining a centralized, accessible system
- Need for secure, scalable file hosting
- Desire for a simple way for students to visually share their portfolios
- Cost concerns around building or purchasing a hosting solution

---

## Solution

- Built a secure file hosting web application using Azure Blob Storage
- Created an easy-to-use React frontend for portfolio file uploads
- Integrated SQLite with Drizzle ORM to manage portfolio metadata
- Enabled students to generate links for embedding their stored portfolio files into Google Sites for external sharing
- Conducted a research phase to evaluate buy vs build options by interviewing stakeholders and comparing potential platforms based on features and costs

---

## Tech Stack
- **Frontend**: Next.js (React-based)  
- **Backend**: Node.js (T3 Stack principles)  
- **Database**: SQLite with Drizzle ORM  
- **Cloud Storage**: Azure Blob Storage  
- **Additional Tools**: TypeScript, TailwindCSS, Google Sites

---

## Application Flow

1. 📝 **Students upload portfolio artifacts**  
   ↳ Through a secure React frontend linked to the storage system.

2. 🛠️ **Files are stored in Azure Blob Storage**  
   ↳ Large media files and documents are securely stored in the cloud.

3. 🗄️ **Metadata is saved using SQLite with Drizzle ORM**  
   ↳ Key details about each portfolio item are organized and indexed.

4. 🖥️ **Faculty access and review portfolios easily**  
   ↳ Centralized access supports accreditation reviews and evaluation.

5. 🌐 **Students share their portfolios through Google Sites**  
   ↳ Students can generate links that embed their stored files into Google Sites for easy visual sharing with employers, faculty, or peers.

---

## Research Phase: Buy vs Build
Before development began, I led a research phase to evaluate whether it would be more effective to purchase an existing solution or build a custom application. I interviewed stakeholders, analyzed technical and financial trade-offs, and researched multiple hosting options. After assessing cost, flexibility, and long-term needs, we decided that building a lightweight, secure backend file hosting system paired with Google Sites for visual display would best meet project goals.

---

## What I Learned
This project taught me how to approach technical architecture decisions pragmatically by balancing cost, technical feasibility, and user needs. I strengthened my skills in full-stack development, cloud storage integration, and working with database modeling tools like Drizzle ORM. It also deepened my understanding of stakeholder communication and early-stage project planning.

---

## Impact
The CS Portfolio Hosting Application provided a scalable, secure, and cost-effective system for hosting and managing student portfolios. It allowed faculty to easily review accreditation materials while giving students a simple, professional way to share their work publicly through Google Sites.

---

