---
layout: essay
type: essay
title: "Estimating the Unknown"
# All dates must be YYYY-MM-DD format!
date: 2025-12-15
published: true
labels:
  - Software Engineering
---

# Estimating the Unknown: Tracking Effort in a Software Project

---

## Introduction

In software development, it is easy to underestimate how much time a task will actually take. Features that seem simple at first often involve more work once testing, styling, and integration are considered. While working on Mānoa RoomieMatch, a roommate matching web application built by a six-person team, I was responsible for many user-facing features such as profile pages, navigation updates, and interface cleanup.

Throughout the project, I estimated my effort in advance and tracked my actual time spent on both coding and non-coding work. Although my estimates were often inaccurate, the process helped me better understand where time is truly spent in a real software project.

---

## How I Made My Effort Estimates

Once a student creates their lifestyle and housing profile, the system stores their preferences and makes them available for matching.

### User Flow
1. **Login and Profile Setup:**  
   Students log in using UH email authentication and complete a structured lifestyle questionnaire. Preferences include sleep schedule, cleanliness level, social habits, noise tolerance, personality, study style, daily routines, and housing goals.

2. **Match Browsing:**  
   Students browse potential roommates filtered by preferences such as major, budget, dorm choice, lifestyle habits, and shared interests.

3. **AI Compatibility Evaluation:**  
   The system uses AI to:
   - Analyze two profiles  
   - Generate a compatibility score  
   - Provide strengths, conflicts, and suggestions  
   - Create tailored “first message” templates to contact matches  

4. **Notifications (optional stretch):**  
   Students can receive notifications when new profiles appear that meet their criteria.

5. **Admin Functions:**  
   Admins can:
   - Flag inappropriate content  
   - Create new lifestyle categories  
   - Manage and review profiles  
   - Adjust system presets (e.g., default survey questions)

---

## Some mockup page ideas

### Landing Page
- Explanation of the platform  
- “Start Matching” call-to-action  
- Summary of AI features  

### User Home Page
- Overview of user’s profile  
- Compatibility highlights  
- Quick access to matches  
- Notifications  

### Profile Setup Page
- Multi-step lifestyle survey  
- Progress indicator  
- Save-as-you-go  

### Browse Matches Page
- List or grid of potential roommates  
- Match percentages  
- Preview of key traits  
- “View Details” button  

### Match Details Page
- Side-by-side comparison  
- AI-generated compatibility report  
- Suggested conversation prompts  

### Admin Home Page
- Manage users  
- Moderate flagged content  
- Add/edit lifestyle categories  

---

## Use case ideas

### 1. New student signs up and sets up their profile
- Student visits the landing page  
- Reads about how RoomieMatch works  
- Logs in using UH authentication  
- Completes the lifestyle survey  
- Arrives at their home page  
- Reviews recommended matches  
- Learns how compatibility scoring works  

### 2. Student searches for compatible roommates
- Logs in  
- Navigates to “Browse Matches”  
- Filters by dorm, budget, lifestyle traits  
- Selects a high-scoring match  
- Reads AI-generated compatibility explanation  
- Uses AI message template to reach out  

### 3. Admin monitors and manages the platform
- Admin logs in  
- Goes to Admin Home Page  
- Reviews flagged profiles  
- Updates lifestyle categories  
- Manages user accounts  

---

## Beyond the basics

After building the core features, the following advanced options can enhance the platform:

### Dorm Recommendation System
AI suggests UH dorms based on:
- Noise preference  
- Budget  
- Room type (double, suite, apartment)  
- AC vs. non-AC  

### Advanced Matching Insights
Allow users to see:
- Compatibility heatmaps  
- “Potential conflict alerts”  
- Personalized compromise suggestions  

### Roommate Agreement Generator
AI produces a personalized roommate contract covering:
- Cleaning schedule  
- Guest rules  
- Quiet hours  
- Shared spaces  
- Privacy expectations  

### Schedule Compatibility Sync
Sync UH class schedules to identify:
- Overlapping free hours  
- Morning vs. night routines  
- Shared optimal times for bathroom/kitchen  

### Household Planner
Shared tools for:
- Chore rotation  
- Expense tracking  
- Grocery list coordination  
