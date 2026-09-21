# ISMS-SCORM-TRAINING-TEST

A browser-based gamified cybersecurity learning course focused on practical Information Security Management System (ISMS) awareness and everyday workplace security decisions.

The project transforms basic information-security concepts into short, interactive workplace scenarios where learners make decisions, receive immediate explanatory feedback, earn points and badges, and progress through five structured missions.

The final course is planned as a SCORM 1.2 package that can be launched through an LMS and support learner progress, score, completion status, and resume-state tracking.

## About the Project

The course is designed for general employees and new joiners who need a practical understanding of everyday information-security responsibilities.

Instead of presenting security concepts only as theory, the course uses:

- Short learning content
- Realistic fictional workplace scenarios
- Interactive learner decisions
- Immediate explanatory feedback
- Mission-based progression
- Scoring and retry rules
- Achievement badges
- Final integrated assessment
- Learner-state tracking

The estimated course seat time is 15–25 minutes.

## Course Information

| Item | Details |
|------|---------|
| Course | ISMS Cyber Security Challenge Level 1 |
| Audience | General employees and new joiners |
| Format | Browser-based gamified learning course |
| Technology | React, Vite, JavaScript, CSS |
| LMS Standard | SCORM 1.2 |
| Course Type | Single SCO |
| Missions | 5 |
| Maximum Score | 100 |
| Passing Score | 80 |
| Mission Maximum | 20 points |
| Estimated Duration | 15–25 minutes |

## Course Missions

### Mission 1 — Protect the Information

Focuses on the CIA triad and workplace information classification.

Learners practice recognizing confidentiality, integrity, and availability requirements and applying the course's information-classification training policy.

### Mission 2 — Spot the Phishing Attack

Focuses on identifying phishing indicators and responding safely to suspicious emails, links, attachments, and unusual requests.

### Mission 3 — Secure Your Digital Identity

Focuses on secure passwords, authentication practices, and appropriate use of multi-factor authentication (MFA).

### Mission 4 — Handle a Security Incident

Focuses on recognizing potential security incidents, taking appropriate immediate actions, preserving relevant evidence, and following the approved reporting process.

### Mission 5 — Become an ISMS Champion

Mission 5 is the fifth and final assessed stage of the course.

It acts as an integrated final assessment where learners apply concepts from Missions 1–4 to realistic workplace security decisions.

There is no separate sixth assessment after Mission 5.

## Scoring and Assessment

The course uses a deterministic 100-point scoring model.

- Five required missions
- Maximum 20 points per mission
- Maximum course score of 100 points
- Passing score of 80 points
- Final result is calculated from recorded learner answers and retained mission scores
- Mission scores cannot exceed their defined maximum
- Duplicate points cannot be awarded through retries

### Retry Policy

Missions 1–4 allow a maximum of two attempts for each assessed challenge.

The highest valid score achieved for a challenge is retained.

If a retry produces a lower score, the previously retained higher score remains.

Mission 5 is treated differently because it is the final assessment.

- Maximum of two complete Mission 5 assessment attempts
- Each attempt is treated as a complete assessment submission
- Highest valid Mission 5 score is retained
- If the learner reaches a final score of 80 or above with all five missions completed, another Mission 5 attempt is not required
- If the final score remains below 80, one additional Mission 5 attempt is available
- Retry attempts cannot create duplicate points or increase the Mission 5 score beyond 20

## Gamification

The course uses a lightweight gamification model to encourage learner engagement.

### Score

The maximum course score is 100 points.

Each mission contributes a maximum of 20 points.

### Badges

The course includes four achievement badges:

- Phishing Spotter
- Data Guardian
- Incident Responder
- ISMS Champion

The ISMS Champion badge is awarded when all required missions are completed and the retained final course score reaches at least 80.

## Learning Approach

Each mission follows a consistent learning pattern:

1. Define a measurable learning objective
2. Explain the concept using short and clear content
3. Present a workplace scenario
4. Require a learner decision
5. Provide immediate explanatory feedback
6. Record the learner attempt and mission state
7. Update the score without exceeding the mission maximum

The course uses fictional people, organizations, email addresses, and workplace data.

## Interaction Design

The course is designed to use multiple interaction patterns rather than relying only on traditional multiple-choice questions.

Current interaction designs include:

- Multiple-choice decisions
- Multi-select questions
- Information classification
- Ordered-response interactions
- Branching decisions
- Scenario-based decisions
- Phishing-indicator selection

Where interactive controls require drag-and-drop behavior, a keyboard-accessible alternative is planned.

## Assessment Question Bank

The approved question bank contains 20 assessment questions.

| Mission | Questions | Maximum Points |
|---------|-----------|----------------|
| M1 | 4 | 20 |
| M2 | 4 | 20 |
| M3 | 4 | 20 |
| M4 | 4 | 20 |
| M5 | 4 | 20 |
| **Total** | **20** | **100** |

Each question is mapped to a learning objective using the following structure:

- M1-O1 → Mission 1 questions
- M2-O1 → Mission 2 questions
- M3-O1 → Mission 3 questions
- M4-O1 → Mission 4 questions
- M5-O1 → Mission 5 questions

The question bank also records interaction configuration, answer handling, attempt policy, difficulty, explanations, and source references.

## Learning Objectives

### M1-O1

Classify workplace information and recognize confidentiality, integrity, and availability requirements in common situations.

### M2-O1

Identify common phishing indicators and select a safe response to suspicious emails, links, attachments, or requests.

### M3-O1

Apply secure password and authentication practices, including appropriate use of multi-factor authentication.

### M4-O1

Recognize a potential security incident, choose appropriate immediate actions, preserve relevant evidence, and follow the correct reporting path.

### M5-O1

Apply concepts learned in the previous missions to realistic workplace security decisions.

## Course State

The course is designed to maintain learner state including:

- Current mission
- Completed missions
- Recorded answers
- Mission scores
- Attempt counts
- Retained scores
- Earned badges
- Mission 5 assessment submission state

Progress is based on completing required learner activities rather than simply visiting screens.

The state model is designed to support future SCORM resume functionality.

## SCORM 1.2

The final course will communicate with an LMS through the SCORM 1.2 runtime API.

The planned SCORM layer will support tracking of:

- Lesson status
- Score
- Current mission / resume location
- Suspend data
- Progress commits
- Session termination

The learner's saved state will be restored when the course is relaunched.

The SCORM communication layer will remain separate from the learning content, game mechanics, and learner-state logic.

## Project Structure

The project is being developed incrementally according to the Phase 2 implementation plan.

```text
isms-scorm-training-test/
├── docs/
│   ├── 01-research/
│   ├── 02-design/
│   │   ├── course-outline.md
│   │   ├── storyboard.md
│   │   └── learning-objective-mapping.md
│   ├── test-report.md
│   └── defect-log.md
├── public/
│   └── media/
├── src/
│   ├── components/
│   ├── missions/
│   ├── questions/
│   │   └── question-bank.json
│   ├── gamification/
│   ├── scorm/
│   ├── state/
│   └── App.jsx
├── tests/
├── imsmanifest.xml
├── package.json
├── vite.config.js
└── README.md
