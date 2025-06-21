This file represents the initial backlog of user stories, technical tasks, and bugs for the project. All items follow INVEST principles (Independent, Negotiable, Valuable, Estimable, Small, Testable).

---

## 🔹 User Stories

### 🧑‍💼 US001 - User Registration
**As** a new user,  
**I want** to register an account,  
**So that** I can access personalized content.

- Priority: High
- Story Points: 5
- Acceptance Criteria:
  - [ ] Email and password input
  - [ ] Success message upon registration
  - [ ] Backend validation

---

### 📩 US002 - Login & Session
**As** a registered user,  
**I want** to log into my account,  
**So that** I can manage my profile and view data securely.

- Priority: High
- Story Points: 3
- Acceptance Criteria:
  - [ ] Authentication token generated
  - [ ] Session maintained for 24 hours

---

### 📊 US003 - Dashboard Overview
**As** a user,  
**I want** to see a dashboard summary,  
**So that** I can quickly view my key metrics.

- Priority: Medium
- Story Points: 8
- Acceptance Criteria:
  - [ ] Metrics displayed dynamically
  - [ ] Responsive design for mobile

---

## ⚙️ Technical Tasks

### 🛠 TT001 - Set Up CI/CD
**Description:** Create automated pipelines for testing and deployment using GitHub Actions.

- Priority: High
- Story Points: 3

---

### 📁 TT002 - Database Schema Design
**Description:** Design schema for user data, including accounts, sessions, and settings.

- Priority: High
- Story Points: 5

---

## 🐞 Bugs

### 🐛 BUG001 - Login Failure with Special Characters
**Description:** Users cannot log in if their password contains `&` or `%`.

- Priority: Medium
- Story Points: 2
- Status: Open
