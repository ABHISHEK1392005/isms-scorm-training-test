# ISMS Cyber Security Challenge Level 1

## Screen-by-Screen Storyboard

### 1. Welcome Screen

Purpose:
Introduce the course and allow the learner to start or resume the course.

Learner sees:
- SecureWise branding
- Course title: ISMS Cyber Security Challenge Level 1
- Short course description
- Estimated duration: 15–25 minutes
- Start Course button
- Resume Course button when saved progress exists

Learner action:
Select Start Course for a new attempt or Resume Course to continue saved progress.

State:
The course checks whether saved learner state exists before deciding whether to show a new or resume flow.

### 2. Mission Dashboard

Purpose:
Show the five missions and overall progress.

Learner sees:
- Five mission cards
- Mission title and short description
- Locked, available, or completed state
- Mission score
- Overall score
- Overall progress
- Earned badges

Learner action:
Select the currently available mission.

State:
Dashboard reflects recorded learner state and does not award progress merely because a screen was visited.

### 3. Mission Introduction

Purpose:
Prepare the learner for the mission.

Learner sees:
- Mission number and title
- One measurable learning objective
- Short explanation of the topic
- What the learner will practice
- Continue button

Learner action:
Continue to the learning screen.

### 4. Learning Screen

Purpose:
Explain the security concept in short, clear language.

Learner sees:
- Mission objective
- Short lesson content
- Key points
- Optional example
- Continue button
- Accessibility-friendly navigation

Learner action:
Read the lesson and continue to the challenge.

### 5. Challenge Screen

Purpose:
Present an interactive workplace decision.

Learner sees:
- Fictional workplace situation
- Clear instruction
- Question or task
- Available choices
- Submit or Continue control

Interaction examples:
- Multiple-choice decision
- Information classification
- Phishing indicator selection
- Incident-response decision

Learner action:
Choose or perform the required action.

State:
The selected answer is recorded for the current attempt.

### 6. Feedback Screen

Purpose:
Explain the result immediately after the learner decision.

Correct response:
- Show that the decision was correct
- Explain why it is safe
- Show earned points

Incorrect response:
- Explain why the choice was unsafe or incomplete
- Explain the safer behavior
- Show the resulting score according to the retry policy

Retry:
If the challenge allows retry, the learner can retry without receiving duplicate points.

### 7. Mission Result Screen

Purpose:
Show the result of the completed mission.

Learner sees:
- Mission score out of 20
- Completion state
- Relevant badge if earned
- Short review message
- Continue button

State:
Mission completion is recorded only after the required activity is actually completed.

### 8. Mission-to-Mission Navigation

Purpose:
Move the learner through the required five-mission journey.

Flow:

M1 → M2 → M3 → M4 → M5

The dashboard and mission result screens show which missions are completed and which mission is currently available.

### 9. Final Assessment Screen

Purpose:
Assess the learner's ability to apply course concepts to realistic workplace decisions.

Learner sees:
- Final assessment instructions
- Scenario-based questions
- Available choices
- Submit Assessment control

Rules:
- Assessment questions come from the approved question bank.
- Score remains between 0 and 100.
- Every assessed question has feedback or a review explanation.
- Mandatory activities cannot be bypassed through normal navigation.

### 10. Final Results Screen

Purpose:
Show the final learner outcome.

Learner sees:
- Final score out of 100
- Pass or fail result
- Completed mission summary
- Earned badges
- Review option
- Exit action

Rules:
- Score of 80 or above passes.
- Score below 80 fails after final submission.
- Completion requires all required missions and final assessment submission.
- Result is calculated from recorded learner answers.

### 11. Exit Screen / Exit Action

Purpose:
End the learner session safely.

Learner sees:
- Final status or saved-progress message
- Exit or Close Course action

State:
Before exit, the current learner state is saved for later SCORM integration. If the course is unfinished, the state must remain resumable.

### 12. Complete Screen Flow

Welcome
↓
Mission Dashboard
↓
Mission Introduction
↓
Learning Screen
↓
Challenge
↓
Feedback
↓
Mission Result
↓
Next Mission
↓
Mission Introduction
↓
Learning Screen
↓
Challenge
↓
Feedback
↓
Mission Result
↓
Repeat through Mission 5
↓
Final Assessment
↓
Final Results
↓
Exit

### 13. State and Tracking Notes

Course UI state will maintain the current mission, completed missions, answers, mission scores, badges, and assessment state.

The later SCORM layer will communicate required tracking information such as status, score, location, and serialized learner state to the LMS.

The storyboard defines the learner experience and state changes that the implementation must support. It does not define implementation code.
