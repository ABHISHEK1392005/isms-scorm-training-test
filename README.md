# SecureWise ISMS Cyber Security Challenge

A gamified cybersecurity learning course developed as part of the SecureWise Phase 2 internship.

The project focuses on basic Information Security Management System (ISMS) concepts and turns them into short, interactive workplace scenarios. The final course will be delivered as a SCORM 1.2 package so that it can be launched from an LMS and track learner progress, score, completion status, and resume state.

## About the Project

The course is designed for general employees and new joiners who need a practical understanding of everyday information-security practices.

Instead of presenting the content only as theory, the course uses missions and workplace situations where the learner has to make a decision and receives immediate feedback.

The planned course duration is 15–25 minutes.

## Course Information

| Item | Details |
|------|---------|
| Course | ISMS Cyber Security Challenge Level 1 |
| Audience | General employees and new joiners |
| Format | Browser-based gamified learning course |
| Technology | React, Vite, JavaScript, CSS |
| LMS Standard | SCORM 1.2 |
| Course Type | Single SCO |
| Maximum Score | 100 |
| Passing Score | 80 |
| Missions | 5 |
| Estimated Duration | 15–25 minutes |

## Missions

### 1. Protect the Information

CIA triad and data classification.

### 2. Spot the Phishing Attack

Email threats and suspicious links.

### 3. Secure Your Digital Identity

Passwords and multi-factor authentication (MFA).

### 4. Handle a Security Incident

Incident recognition and reporting.

### 5. Become an ISMS Champion

Integrated final assessment.

Each mission has a maximum score of 20 points, giving a total possible score of 100.

## Learning Approach

Each mission is designed around:

1. A measurable learning objective
2. A short concept explanation
3. An interactive workplace scenario
4. A learner decision
5. Immediate feedback
6. Attempt and mission-state recording
7. Score update

## SCORM 1.2

The final course will communicate with the LMS through the SCORM 1.2 runtime API.

The course will track:

- Lesson status
- Score
- Current mission / resume location
- Suspend data
- Progress commits
- Session termination

The learner's saved state will be restored when the course is relaunched.

## Project Structure

The project will be developed gradually according to the Phase 2 implementation plan.

```text
securewise-isms-scorm-game/
├── docs/
│   ├── 01-research/
│   ├── 02-design/
│   ├── test-report.md
│   └── defect-log.md
├── public/
│   └── media/
├── src/
│   ├── components/
│   ├── missions/
│   ├── questions/
│   ├── gamification/
│   ├── scorm/
│   ├── state/
│   └── App.jsx
├── tests/
├── imsmanifest.xml
├── package.json
├── vite.config.js
└── README.md
