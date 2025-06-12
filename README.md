# GoalTracker

## Pitch

Imagine combining the personal accountability of goal tracking with the excitement of fantasy football. GoalTracker is a web and mobile application designed to help people and groups set, track, and achieve their goals in a fun, motivating way.

### Key Features:
- Set personal goals and track progress over time  
- Create or join groups to pursue goals together  
- Host goal-based competitions with real stakes  

A standout feature is **Goal Challenges**, where users can pledge money toward their goals. Friends or group members can compete in achieving their goals, and the winners split the pledged pool. Whether it’s fitness, studying, habits, or productivity — it’s goal setting you can win.

---

## ERD

![ERD Diagram](https://github.com/user-attachments/assets/f7220962-a547-49b2-84b5-4bd01e984953)

---

## System Flow

![systemdiagram](https://github.com/user-attachments/assets/795e8c59-0938-4120-9431-02f74f1ff7b9)

---

## Tech Stack Overview

### Frontend (Web-first, Cross-Platform with Expo)
- **React Native + Expo** – Unified development for web, iOS, and Android  
- **TypeScript** – Strongly typed JavaScript for safer development  
- **NativeWind (Tailwind CSS)** – Utility-first styling for React Native components  
- **React Navigation** – Navigation and routing between screens  

### Backend (Supabase)
- **Supabase Auth** – User authentication and session management  
- **Supabase Postgres Database** – Stores users, goals, groups, challenges, and progress updates  
- **Supabase Realtime** – Real-time syncing of data across users  

### Payments
- **Venmo (manual)** – Users input their Venmo handles and settle challenges directly  

### Deployment
- **Vercel** – Hosting the web version of the application (Next.js compatible via Expo Web)  

---

## Project Timeline

| Date       | Day    | Goal                                                   |
|------------|--------|--------------------------------------------------------|
| May 31     | Day 1  | Finalize idea, sketch ERD & system diagram, set up Supabase |
| June 1     | Day 2  | Add user signup/login + Venmo username to profile      |
| June 2     | Day 3  | Implement create/view/edit goals                       |
| June 3     | Day 4  | Create groups and join them                            |
| June 4     | Day 5  | Build Challenge creation + join flow                   |
| June 5     | Day 6  | Add progress update functionality                      |
| June 6     | Day 7  | Build challenge summary with winners                   |
| June 7     | Day 8  | Add profile page (Venmo display)                       |
| June 8     | Day 9  | Add Realtime                                           |
| June 9     | Day 10 | Polish UI and styling                                  |
| June 10    | Day 11 | Test flows end-to-end                                  |
| June 11    | Day 12 | Fix bugs, finalize data structure                      |
| June 12    | Day 13 | Prepare demo/presentation                              |
| June 13–16 | Day 14 | Present project                                        |
