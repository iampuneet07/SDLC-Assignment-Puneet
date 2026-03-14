# SDLC-Assignment-Puneet
# SDLC Assignment – Smart-Attend Mobile App

**Course:** SDLC & DevOps Fundamentals
**Role:** Junior Project Manager (Release Manager Roleplay)

---

# 📱 Project Overview

The **Smart-Attend Mobile App** is a university startup project designed to automate student attendance using **Geo-fencing technology**.

When a student enters the classroom area, the app detects their location and automatically marks their attendance.

This system reduces manual attendance work and improves accuracy.

---

# 🔄 Project Change (The Pivot)

Halfway through development, the **Dean introduced a new requirement**:

> The system must integrate **Biometric Face ID verification** to prevent proxy attendance.

This change required the development team to reconsider the development approach and move from a traditional model to a more flexible methodology.

---

# ⚠️ Task 1 – Waterfall Model Failure Analysis

Using the **Waterfall development model** would cause serious problems when the new biometric requirement is introduced.

### 1. Rigidity

The Waterfall model follows fixed development phases:

```
Requirements → Design → Development → Testing → Deployment
```

Once development has started, it is very difficult to go back and modify earlier phases.

Adding Face ID in the middle of development would require rewriting requirements and redesigning the system.

---

### 2. High Cost of Change

The Waterfall model depends heavily on an initial project blueprint.

Integrating **Face ID verification** would require:

* Camera access integration
* Facial recognition libraries
* Database changes
* Security updates

Making these changes mid-project increases both **cost and development time**.

---

### 3. Delayed Testing

Testing in Waterfall typically occurs at the end of the development cycle.

If Face ID integration conflicts with the **Geo-fencing attendance system**, these issues may only be discovered during final testing.

This can cause significant delays and require major rework.

---

# 🚀 Task 2 – Agile Pivot Using Scrum

To handle the new requirement efficiently, the team switches to the **Agile Scrum framework**.

Agile divides development into short cycles called **Sprints**, allowing teams to adapt quickly to changing requirements.

Each sprint lasts **two weeks**.

---

## Sprint 1 – Minimum Viable Product (MVP)

Goal: Build the core functionality of the Smart-Attend system.

Features included:

* Basic mobile app interface
* Student login using university ID
* Geo-fencing attendance detection
* Attendance notification system

Deliverable:

A working prototype that automatically marks attendance when students enter the classroom.

---

## Sprint 2 – Feature Update

Goal: Improve system security and add new features.

Features included:

* Face ID biometric verification
* Improved reporting dashboard for teachers
* Bug fixes and performance improvements

Deliverable:

A secure attendance system combining **Geo-fencing and Face ID verification**.

---

# 📊 Task 3 – Sprint Backlog

The **Sprint Backlog** contains tasks that the development team commits to completing during Sprint 1.

| Task ID | User Story                                                                       | Priority | Estimated Hours |
| ------- | -------------------------------------------------------------------------------- | -------- | --------------- |
| US01    | As a student, I want to login via university ID so I can access my profile.      | High     | 4               |
| US02    | As a teacher, I want to view a real-time list of present students.               | High     | 6               |
| US03    | As a system, I want to detect if a student is within 10 meters of the classroom. | High     | 8               |
| US04    | As a student, I want a notification when my attendance is marked.                | Medium   | 3               |
| US05    | As an admin, I want to manually override attendance for technical errors.        | Low      | 4               |

The detailed backlog is included in **`sprint-backlog.xlsx`**.

---

# ⚙️ CI/CD for Smart-Attend

The Smart-Attend system would use **CI/CD (Continuous Integration and Continuous Deployment)** to deliver updates efficiently.

### Continuous Integration (CI)

CI automatically tests new code whenever developers push updates to the repository.

Benefits include:

* Early detection of bugs
* Automated testing of new features
* Improved code quality

For example, when developers add **Face ID verification**, automated tests ensure that the Geo-fencing system and login system still work correctly.

---

### Continuous Deployment (CD)

Continuous Deployment automatically releases tested updates to users.

Benefits include:

* Faster delivery of new features
* Immediate bug fixes
* Regular system improvements

This ensures that students and teachers always use the **latest version of the Smart-Attend app**.

---

# 📂 Repository Structure

```
SDLC-Assignment-YourName
│
├── README.md
├── SmartAttend-Analysis.pdf
└── sprint-backlog.xlsx
```

---

# 📌 Conclusion

The Smart-Attend project shows how **Agile Scrum** provides flexibility when project requirements change.

Switching from the Waterfall model to Agile allows the development team to integrate new features such as **Face ID verification** without restarting the entire project.

Using **CI/CD pipelines** further improves the development process by enabling fast and reliable updates.

---

# 👨‍💻 Author

SDLC & DevOps Fundamentals Assignment
