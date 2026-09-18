---
marp: true
size: 4:3
---

# Project 1 Plan

**Submission Deadline:** [October 23, 2026]

Planning anchors: HW2 is due in Week 4, Project 1 starts in Week 5, HW3 Q&A
is in Week 7, Midterm 1 is in Week 8, and Project 1 is due in Week 9.
Canvas is the official source for exact deadlines.

---

## Your Project 1 Submission Date

1. **When (Plan):**  Ovtober 23, 2026
2. **When (Actual):** TBD  
3. **Comment:** Plan to finish before the deadlin to leave some time for testing

---

## Planned API Endpoints

List the 10 REST API endpoints you plan to implement for Project 1. Mark
Bearer-token-protected endpoints with `*` (at least 2 required). Leave
"Implemented On" blank for now — in Project 1 you will fill in the actual
date you finished each endpoint, as proof that your implementation followed
your plan.

Example format:

```txt
* means Bearer token required
GET /students → Get all students
GET /students/1 → Get student by ID
POST /students → Create new student
PUT /students/1 → Update student
DELETE /students/1 → Delete student *
```

| # | Endpoint | Description | Bearer | Implemented On |
|---|----------|--------------|:---:|---|
| 1 |GET /decks|Get all Commander decks  |  |  |
| 2 | GET /decks/{id} | Get one deck by ID | | |
| 3 | POST /decks | Create a new deck | | |
| 4 | PUT /decks/{id} | Update a deck | | |
| 5 | DELETE /decks/{id} | Delete a deck | **X** | |
| 6 | GET /cards | Get all cards | | |
| 7 | GET /cards/{id} | Get one card by ID | | |
| 8 | POST /cards | Add a new card | | |
| 9 | PUT /cards/{id} | Update a card | | |
| 10 | DELETE /cards/{id} | Delete a card | **X** | |

---

## Project 1 Milestones

### Milestone 1: API and Database Design

1. **What:** Finalize all 10 endpoints planned in HW2 (2 of them Bearer-token protected); design the MySQL table(s).
2. **When (Plan):**  Septebmer 27, 2026
3. **When (Actual):** TBD  
4. **Comment:** Create the decks and cards database tables and finalize the API design

---

### Milestone 2: PHP/MySQL Implementation and Tests

1. **What:** Implement CRUD endpoints and create cURL plus HTML/JavaScript tests.
2. **When (Plan):**  October 9, 2026
3. **When (Actual):** TBD  
4. **Comment:** Build and test all API endpoints before the midterm checkpoint

---

### Milestone 3: Tutorial and NGINX Deployment

1. **What:** Complete tutorial slides, test NGINX deployment, and organize `code/`, `presentation/`, and `plan/`.
2. **When (Plan):**  October 18, 2026
3. **When (Actual):** TBD  
4. **Comment:** Finish deployment, presentation, and final project organization

---
