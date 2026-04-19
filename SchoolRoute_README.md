# SchoolRoute — UX Case Study

### Bus Routes & Carpooling App for Parents and Students

![Platform](https://img.shields.io/badge/Platform-iOS%20%2B%20Responsive%20Web-E53935)
![Tools](https://img.shields.io/badge/Tools-Figma-4CAF7D)
![Status](https://img.shields.io/badge/Status-Hi--fi%20Complete-brightgreen)
![Duration](https://img.shields.io/badge/Duration-January%20–%20March%202026-E53935)

---

## Overview

SchoolRoute is a mobile app and responsive website designed to help parents and students easily find school bus routes, stops, and schedules in one place. The platform also enables users to search for, join, or create trusted carpooling groups within their community — making daily school commutes safer, more organized, and collaborative.

**Project duration:** January 2026 – March 2026
**Role:** Lead UX Designer and UX Researcher — responsible for the end-to-end experience across both mobile and responsive web.

---

## The Problem

Parents and students struggle to access clear, centralized information about school bus routes and stop locations. Existing information is scattered, outdated, or difficult to understand — and there is no reliable platform to coordinate safe, trusted carpooling within a school community.

### Four core pain points identified through research:

| # | Pain Point | Design Response |
|---|---|---|
| 1 | Unclear bus information | Map-based interface with clearly labeled routes and real-time updates |
| 2 | Safety concerns | Verified profiles, trusted carpool groups, and safety notifications |
| 3 | Poor carpooling communication | Built-in carpool search and group management feature |
| 4 | Time pressure & busy schedules | Clean minimal interface with saved routes and one-tap access |

---

## The Goal

Design a user-friendly mobile app and responsive website that provides accurate bus route and stop information while enabling parents and students to easily search, create, and manage trusted carpooling groups for safer and more organized school commutes.

---

## Design Process

### Empathize

Conducted user interviews and distributed surveys focusing on school transportation challenges. Initially assumed users mainly needed clearer bus schedules — research revealed that safety concerns, real-time updates, and trusted carpool coordination were equally important. Parents prioritized reliability and security while students valued speed and simplicity.

**Personas developed:**

| Persona | Age | Role | Core Need |
|---|---|---|---|
| Aisha Khan | 38 | Working mother, Marketing Manager | Reliable bus info + trusted carpool coordination |
| Daniel Chen | 17 | High school basketball athlete | Flexible carpools for early practice & late training |

**Aisha's problem statement:**
> Aisha Khan is a 38-year-old working mother of two school-aged children who needs reliable, centralized bus route information and trusted carpool coordination, because unclear schedules and safety concerns increase her daily stress and reduce her confidence in the commute system.

**Daniel's problem statement:**
> Daniel Chen is a 17-year-old high school athlete who needs flexible and reliable carpool options because early morning practices and late evening training sessions do not align with regular school bus schedules.

### Define

**Core insight from research:** Working parents value trust, reliability, and speed over extra features. Safety transparency and real-time clarity are more important than complex functionality. Student athletes need flexibility and coordination — transportation solutions must adapt to changing practice times.

**How Might We statements:**
- How might we help parents verify the safety of carpool group members?
- How might we make bus route information accessible in one tap?
- How might we help students find carpools that match non-standard schedules?
- How might we reduce morning commute stress for time-constrained families?

### Ideate

Competitive research across transport and school communication apps. Key finding: no existing app combines bus route tracking, verified parent carpooling, and child safety notifications in a single free product designed specifically for school communities.

**Sitemap structure:**

```
schoolroute.com
├── Home
├── Sign in / Sign up
│   └── Role selection → Create account
├── Dashboard
│   ├── Bus routes
│   │   ├── Route search
│   │   ├── Route detail
│   │   └── Route saved
│   ├── Carpool
│   │   ├── Join group
│   │   ├── Create group
│   │   └── Group detail
│   ├── Notifications
│   └── Profile
│       └── Settings
└── About
```

### Prototype
- Lo-fi wireframes across all core flows
- Hi-fi prototype with full design system in Figma
- Responsive website at 3 breakpoints (desktop, tablet, mobile)
- Red and white color palette — trustworthy, clean, action-oriented

### Test

**Moderated usability study — 5 participants — March 2026**

Identified and prioritized issues across P0 (critical), P1 (important), and P2 (roadmap) categories.

---

## Usability Testing Results

### P0 — Critical (must fix before launch)

**1. Safety & trust in carpooling**
- 3 of 5 parents hesitated or abandoned the carpool flow due to safety concerns
- P1 asked "Is this school-verified?" — P3 abandoned the task entirely
- **Fix:** Add verified parent badge to member profiles + tooltip explaining public vs private information

**2. Carpool feature discovery**
- 2 of 3 parent participants failed to reach the carpool section without assistance
- P3 used the search bar instead of the nav tab — P1 tapped Routes expecting carpool to be there
- **Fix:** Add a prominent "Find a Carpool" shortcut card on the Home Dashboard

### P1 — Important improvements

**3. Stop list readability**
- Users missed the stop list because its visual hierarchy was too low
- P3 said the font was too small to read comfortably
- **Fix:** Increase font size and weight — auto-highlight nearest stop based on location

**4. Form input clarity**
- Users skipped or misused form fields with no placeholder text
- P2 skipped the description field — P5 unsure whether to type or pick departure time
- **Fix:** Add placeholder hint text + replace time input with a time-picker widget

### Strengths — Preserve

- Clean minimal visual design consistently praised by tech-comfortable users
- P4: "This is like Moovit but for school" — P5: "I like that it's not cluttered"
- Map interface described as straightforward across multiple participants

---

## Key Screens

### Mobile App

| Flow | Screens |
|---|---|
| Onboarding | Splash · Role selection · Sign up · School setup |
| Home dashboard | Overview · Quick actions · Carpool shortcut |
| Bus routes | Route search · Route detail & stops · Saved routes |
| Carpool | Carpool home · Create group · Join group · Group detail |
| Safety | Notifications · Arrival confirmations |
| Profile | Settings · Child profiles · Notification preferences |

### Responsive Website

Landing page · Sign in · Role selection · Sign up · Dashboard · Bus routes · Route detail · Carpool home · Create group · Group detail · Notifications · Profile · Settings · About

---

## Key Design Decisions

**1. Role selection at onboarding**
Parents and students have fundamentally different needs. Selecting a role at the start tailors the entire experience — parents see safety and coordination features first, students see route planning and schedules first.

**2. Verified parent model for carpooling**
Safety is the primary concern for any child transport app. Following the P0 usability finding, carpool groups display verified parent badges and clear privacy controls — showing exactly what information is visible to other members before joining.

**3. Carpool shortcut on home dashboard**
Direct response to the P0 discovery finding. A prominent "Find a Carpool" card on the home screen means the feature is reachable in one tap without relying on navigation label recognition.

**4. Clean minimal interface**
Deliberately low information density — consistent with usability testing feedback that praised the uncluttered layout. No elements added without a clear user need.

---

## Color Palette

| Role | Hex | Usage |
|---|---|---|
| Primary red | `#E53935` | Buttons, active states, headings |
| Dark charcoal | `#212121` | Primary text |
| Light grey | `#F5F5F5` | Backgrounds, surfaces |
| Success green | `#4CAF7D` | Confirmed arrivals, joined groups |
| Warning amber | `#FF9800` | Schedule alerts, delays |

**Typography:** Inter — clean, accessible, works well at all sizes for maps and schedules

---

## Tools Used

- **Figma** — wireframing, hi-fi design, prototyping, sitemap
- **UX Research** — user interviews, surveys, personas, journey maps, usability research plan
- **Usability Testing** — moderated sessions with 5 participants, prioritized insights

---

## View Prototype

[View SchoolRoute Mobile Prototype on Figma](https://www.figma.com/design/JK1dXCaxqiAorFOaO6VcoE/Project-1-School-Route-app?node-id=47-59&embed-host=share)

[View SchoolRoute Website Prototype on Figma](https://www.figma.com/design/JK1dXCaxqiAorFOaO6VcoE/Project-1-School-Route-app?node-id=119-2011&embed-host=share)

---

## Designer

**Yasir Afaque**
MTech in Engineering — National Kaohsiung Normal University, Taiwan
Google UX Design Professional Certificate — 2026
MOE Taiwan Scholarship Recipient

[Portfolio](https://github.com/Yasir164) · [LinkedIn](https://www.linkedin.com/in/yasir-afaque-9472751a1/) · [Figma](https://www.figma.com/team_invite/redeem/eJNiDvaHPvUX0hwoBgawoZ?t=lSJO0qMrZdWV7MR0-21)

