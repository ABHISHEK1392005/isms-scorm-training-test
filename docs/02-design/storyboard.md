# ISMS Cyber Security Challenge Level 1

## Screen-by-Screen Storyboard

### 1. Welcome Screen

Purpose:

Introduce the course and allow the learner to start or resume the course.

Learner sees:

- Course branding
- Course title: ISMS Cyber Security Challenge Level 1
- Short course description
- Estimated duration: 15–25 minutes
- Start Course button
- Resume Course button when saved progress exists

Learner action:

Select Start Course for a new attempt or Resume Course to continue saved progress.

State:

The course checks whether saved learner state exists before deciding whether to show a new or resume flow.

Next screen:

Mission Dashboard.

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

Next screen:

Selected available mission introduction.

### 3. Mission Introduction

Purpose:

Prepare the learner for the selected mission.

Learner sees:

- Mission number and title
- One measurable learning objective
- Short explanation of the topic
- What the learner will practice
- Continue button

Learner action:

Continue to the learning screen.

State:

The current mission is recorded, but mission completion is not awarded by visiting the introduction screen.

Next screen:

Learning Screen.

### 4. Learning Screen

Purpose:

Explain the security concept in short, clear language before the learner makes a decision.

Learner sees:

- Mission objective
- Short lesson content
- Key points
- Optional example
- Continue button
- Accessibility-friendly navigation

Learner action:

Read the lesson and continue to the challenge.

State:

Learning content is viewed without awarding mission completion or additional points.

Next screen:

Mission-specific Challenge Screen.

### 5. Challenge Screen

Purpose:

Present an interactive workplace decision based on the mission objective.

Learner sees:

- Fictional workplace situation
- Clear instruction
- Question or task
- Available choices
- Submit or Continue control

Interaction types used across the course:

- Multiple-choice decision
- Multi-select
- Information classification
- Ordered-response decision
- Branching decision
- Phishing indicator selection

Learner action:

Choose or perform the required action.

State:

The selected answer or interaction result is recorded for the current attempt.

Next screen:

Feedback Screen.

### 6. Feedback Screen

Purpose:

Explain the result immediately after the learner decision.

Correct response:

- Show that the decision was correct
- Explain why it is safe
- Show the points earned for the interaction

Incorrect response:

- Explain why the choice was unsafe or incomplete
- Explain the safer behavior
- Show the resulting score according to the defined retry policy

Retry:

If the challenge allows retry, the learner can retry according to the documented retry policy. Retries must not create duplicate points.

State:

The recorded answer, attempt result, and earned score are updated according to the scoring and retry rules.

Next screen:

Mission-specific next challenge or Mission Result when all required mission activities are complete.

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

Mission completion is recorded only after the required mission activity is actually completed.

Points:

The mission score cannot exceed 20 points.

Next screen:

Next available mission or Mission 5 final assessment when applicable.

### 8. Mission-to-Mission Navigation

Purpose:

Move the learner through the required five-mission journey.

Flow:

M1 → M2 → M3 → M4 → M5

The dashboard and mission result screens show which missions are completed and which mission is currently available.

Learners cannot normally skip a required incomplete mission through the standard navigation.

---

## 9. Mission 1 — Protect the Information

Purpose:

Teach the learner to classify workplace information and recognize confidentiality, integrity, and availability requirements.

Scenario:

A fictional employee, Riya Sharma, is preparing documents for a workplace project. The learner is shown different examples such as a public company announcement, an internal project schedule, and a document containing sensitive employee information.

The learner must decide how the information should be handled and identify which CIA property is relevant in different workplace situations.

Learner action:

The learner:

- Classifies information according to the training policy.
- Identifies confidentiality, integrity, or availability requirements.
- Submits the selected classification or CIA answer.

Interaction type:

- Classification
- Multiple-choice decision

Classification interaction:

The learner assigns fictional documents to Public, Internal, or Confidential using card selection.

A keyboard-accessible alternative must be provided for the classification interaction.

Feedback:

Correct:

Explain why the selected classification or CIA property matches the situation.

Incorrect:

Explain why the selected classification or CIA property is not appropriate and describe the safer or correct handling.

Points:

Mission maximum: 20 points.

Points are awarded according to the approved question bank. The mission score cannot exceed 20 points.

State change:

Recorded answers, earned points, attempt information, and mission completion state are updated.

Next screen:

Mission 1 Result → Mission 2 Introduction.

---

## 10. Mission 2 — Spot the Phishing Attack

Purpose:

Teach the learner to identify phishing indicators and select a safe response.

Scenario:

A fictional employee receives an unexpected email claiming that their account will be suspended unless they verify it immediately. The email contains an unfamiliar sender address, an urgent message, and a suspicious link.

Learner action:

The learner identifies all suspicious indicators and selects the safe response.

Interaction type:

- Multi-select phishing indicator selection
- Scenario decision

Multi-select interaction:

The learner selects all applicable phishing indicators from the message.

Possible indicators include:

- Suspicious sender
- Urgent request
- Suspicious link
- Unexpected request for account information
- Unexpected attachment when present

The learner must be able to complete the interaction using the keyboard.

Feedback:

Correct:

Explain each selected phishing indicator and why independent verification or approved reporting is safer than clicking or responding.

Incorrect:

Identify the missed or incorrectly selected indicator and explain the safer behavior.

Points:

Mission maximum: 20 points.

Points are awarded according to the approved question bank. Retry must not create duplicate points.

State change:

Selected indicators, answer result, earned points, and mission completion state are recorded.

Next screen:

Mission 2 Result → Mission 3 Introduction.

---

## 11. Mission 3 — Secure Your Digital Identity

Purpose:

Teach the learner to apply secure password and authentication practices, including appropriate use of multi-factor authentication.

Scenario:

A fictional employee receives an unexpected authentication approval request while not signing in. At the same time, a coworker asks for the employee's password because urgent access is needed.

Learner action:

The learner must decide how to respond to the unexpected authentication request and how to handle the password-sharing request.

Interaction type:

- Scenario decision
- Multiple-choice decision

Feedback:

Correct:

Explain that credentials should not be shared and unexpected authentication requests should not be approved. The learner is directed to use the approved access and reporting process.

Incorrect:

Explain the security risk of password sharing or approving an unexpected authentication request and describe the safer behavior.

Points:

Mission maximum: 20 points.

Points are awarded according to the approved question bank and cannot exceed the mission maximum.

State change:

The learner's recorded decisions, score, and mission completion state are updated.

Next screen:

Mission 3 Result → Mission 4 Introduction.

---

## 12. Mission 4 — Handle a Security Incident

Purpose:

Teach the learner to recognize a potential security incident, take safe immediate actions, preserve relevant evidence, and report through the correct channel.

Scenario:

A fictional employee notices unusual activity on a work account that they did not perform. The learner must decide what to do immediately and what action should happen next.

Learner action:

The learner follows the safest incident-response sequence.

Interaction type:

- Branching decision sequence
- Ordered-response interaction

Branching interaction:

The learner makes a decision at each stage.

Example flow:

1. Recognize the suspicious activity.
2. Avoid destroying or altering relevant evidence.
3. Follow the approved incident reporting process.
4. Provide the relevant information to the authorized response team.

An unsafe decision may lead to an explanatory feedback branch before the learner continues according to the retry policy.

Ordered-response interaction:

The learner arranges the required response actions in the appropriate order.

A keyboard-accessible alternative must be provided for any drag-and-drop implementation.

Feedback:

Correct:

Explain why the selected response sequence protects the organization and supports investigation.

Incorrect:

Explain the unsafe or incomplete action and show the safer response sequence.

Points:

Mission maximum: 20 points.

Points are awarded according to the approved question bank and cannot exceed the mission maximum.

State change:

The selected decisions, response sequence, score, and mission completion state are recorded.

Next screen:

Mission 4 Result → Mission 5 Introduction.

---

## 13. Mission 5 — Become an ISMS Champion

Purpose:

Apply concepts from Missions 1 to 4 to integrated workplace security decisions.

Mission 5 is the fifth and final assessed stage of the course and serves as the integrated final assessment.

There is no separate sixth assessment after Mission 5.

Scenario:

A fictional employee is preparing for an important workday and encounters several security-related situations:

- An email contains a suspicious link and urgent request.
- A document contains sensitive information.
- An unexpected authentication request appears.
- Suspicious account activity is noticed.

The learner must apply the concepts learned in the previous missions to decide how each situation should be handled.

Learner action:

The learner makes a series of integrated security decisions and submits Mission 5 as the final assessment.

Interaction types:

Mission 5 may use:

- Scenario decision
- Multi-select
- Classification
- Ordered-response
- Branching decision

Feedback:

Correct:

Explain how the decision applies the security concepts taught in the previous missions.

Incorrect:

Explain the security weakness in the selected decision and describe the safer behavior.

Points:

Mission maximum: 20 points.

Mission 5 contributes the final 20 points available in the 100-point course.

The Mission 5 score cannot exceed 20 points.

There is no separate assessment score after Mission 5.

State change:

When the learner submits Mission 5:

- Mission 5 answers are recorded.
- Mission 5 score is recorded.
- Mission 5 assessment submission state becomes true.
- All completed mission states are retained.
- Earned badges are retained.
- The final course result is calculated from the recorded learner state.

Next screen:

Final Results Screen.

---

## 14. Final Results Screen

Purpose:

Show the final learner outcome after Mission 5, which is the integrated final assessment.

Learner sees:

- Final score out of 100
- Pass or fail result
- Completed mission summary
- Earned badges
- Review option
- Exit action

Rules:

- Score of 80 or above passes.
- Score below 80 fails after Mission 5 is submitted.
- Completion requires all five required missions and submission of Mission 5.
- Mission 5 is the final assessment.
- There is no separate assessment after Mission 5.
- The final result is calculated from the recorded learner answers and mission scores.
- The Final Results screen displays the result but does not award additional points.

State:

The final score, completion status, pass or fail result, completed missions, and earned badges are retained as part of the learner state.

Next screen:

Exit Screen / Exit Action.

---

## 15. Exit Screen / Exit Action

Purpose:

End the learner session safely.

Learner sees:

- Final result and completion status when the course is completed
- Saved-progress message when the course is unfinished
- Exit or Close Course action

State:

Before exit, the current learner state is saved for later SCORM integration.

If the course is unfinished, the learner state remains resumable.

If Mission 5 has been submitted and the course requirements are satisfied, the final recorded score and completion result are retained for SCORM reporting.

Next screen:

Course session ends.

---

## 16. Complete Screen Flow

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
Mission 2
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
Mission 3
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
Mission 4
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
Mission 5 — Integrated Final Assessment
↓
Final Results
↓
Exit

---

## 17. State and Tracking Notes

Course UI state will maintain:

- Current mission
- Completed missions
- Recorded answers
- Mission scores
- Earned badges
- Mission 5 assessment submission state

Mission completion is based on actual required learner actions rather than simply visiting screens.

Mission scores cannot exceed 20 points.

The total course score cannot exceed 100 points.

Retry behavior will follow the documented retry policy and must not create duplicate points.

Mission 5 assessment submission represents the final assessment submission for the course.

The course will not create a separate sixth assessment state or additional assessment score.

The later SCORM layer will communicate required tracking information such as status, score, location, and serialized learner state to the LMS.

The storyboard defines the learner experience and state changes that the implementation must support. It does not define implementation code.
