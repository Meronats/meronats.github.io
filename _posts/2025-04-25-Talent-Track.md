---
layout: posts
title: "Talent Track"
date: 2025-04-25 10:00:00 +0000
categories: 
  - work
tagline: "Simplifying recruitment for college soccer coaches"
tags:
  - Collaboration
description: A fullstack application that automates soccer recruitment by parsing player emails and organizing recruit data in one place.
highlight_home: true
header:
  teaser: https://media1.thehungryjpeg.com/thumbs2/ori_3808969_3rfvd35fbfuaau2l9p351o4phtuv51t57v58e91k_monogram-tt-logo-design.jpg
  caption: Talent Track Project
---


Soccer Recruiting Application  


[GitHub Repository](https://github.com/Meronats/TalentTrack)


# About the Project
Created Talent Track to help soccer coaches manage recruit emails in a more organized and efficient way. Coaches often receive dozens of emails a day from students, each formatted differently and hard to track. Our app makes the process smoother by automatically parsing emails and showing player information in a clean dashboard.

---

## The Problem

- Current method is completely manual
- Disorganized and hard to manage
- Coaches can’t remotely access info
- Potential recruits often fall through the cracks

---

## Solution

- Create an automated recruiting application
- Parse recruit emails using AI
- Store player data in a structured database
- Build an easy-to-use interface for coaches

---

## Tech Stack
- **Frontend**: React  
- **Backend**: Python, Flask  
- **Database**: PostgreSQL  
- **Parsing & AI**: GPT-3.5 Turbo  
- **Cloud**: AWS  
- **Containerization**: Docker  

---

## Application Flow

1. 📩 **Email is forwarded to TalentTrack inbox**  
   ↳ The coach forwards recruit emails to a dedicated inbox.

2. 🛠️ **Inbox is parsed every 24 hours**  
   ↳ Our backend checks the inbox and extracts relevant info (GPA, grad year, position, etc.).

3. 🗃️ **Parsed data is stored in a database**  
   ↳ The extracted details are saved securely in PostgreSQL.

4. 🖥️ **View player dashboard in user interface**  
   ↳ The coach can log into the app and view/update player info through a simple React-based UI.

---

## 🧠 What I Learned
This project helped me grow in both frontend and backend development. I gained hands-on experience working with email parsing, AI integration, cloud deployment, and teamwork under deadlines. I also learned how important clean UI and data structure are when building tools meant for real users.

---

## Impact
Talent Track helps coaches focus more on making the right recruiting decisions instead of drowning in unorganized emails. It brings clarity, automation, and structure to a process that really needed it.
