---
marp: true
size: 4:3
paginate: true
title: HW2 – Module 1 Preparation
---

# HW2

## Project 1 Preparation

(Due Week 4; prepares you for Project 1)

---

Use `marp` to read this document.

---

## Grading

- Total: **100%**
- Use same grading rule as HW1  

---

### Recommendation

1. Start Project early — can't cram!  
2. Ask questions if anything is unclear.
3. Need help with tools? Visit me.  
   - VSCode, Git/GitHub, Marp/Markdown, NGNIX  

HW2 is planning and setup work. You do not implement the complete Project 1 API in HW2.

---

## Assignment 1 (30%)

**Goal: Install and verify the tools you need for Project 1**

---

### 1. NGINX (10%)

- Install: `sudo apt update && sudo apt install nginx -y`
- Start it: `sudo service nginx start` (WSL) or `sudo systemctl start nginx` (native Ubuntu)
- Open `http://localhost` in a browser and confirm you see the "Welcome to nginx!" page
- [NGINX Tutorial](https://github.com/nkuase/ase230/tree/main/module1/pdf/5_Webserver_using_NGINX)

---

### 2. GitHub (10%)

- Create a GitHub account (if you don't have one) and a new repository for ASE 230.
- Push at least one file to it (VS Code Source Control, or **Add file → Upload files** on the GitHub website).
- [GitHub Tutorial](https://github.com/nkuase/ASE/blob/main/tools/ASE-onboard/pdf/3_github.pdf)


---

### 3. VS Code + Marp (10%)

- Install the **Marp for VS Code** extension (`marp-team.marp-vscode`).
- Create a `.md` file starting with:
  ```yaml
  ---
  marp: true
  theme: default
  paginate: true
  ---
  ```
- Write a few slides separated by `---`, then export to PDF (Command Palette → **Marp: Export Slide Deck...**).
- [Marp Tutorial](https://github.com/nkuase/ASE/blob/main/tools/ASE-onboard/pdf/2_marp.pdf)

---

## Assignment 2 (20%)

**Goal: Read "project1" in the Canvas/Project Submissions

- Be sure to understand the requirements and expectations of the project1. 
- You will get clear understanding of the project1 when you read the examples.

---

## Assignment 3 (20%)

**Goal: Choose REST APIs to implement**

- Pick at least **10 REST APIs** (at least 2 **Bearer token** APIs).  
- Must use **MySQL + CRUD**.  
- You may change anything later (with explanation).  
- Project 1 requires you to implement **all 10 planned APIs**, so choose carefully.
  Keeping 1–2 extra backup ideas in mind can help if some plans need to change.
- List your 10 endpoints in the **Planned API Endpoints** table in `plan.md`
  (see the format example already in `plan.md`, and `submission_example/` in
  `project1.zip` for a filled-in example).
- Leave the "Implemented On" column blank for now — in Project 1 you'll fill
  in the actual date you finish each endpoint, so it's clear whether your
  plan was actually followed.

---

## Assignment 4 (30%)

**Goal: Plan Schedule for Project 1**

1. Check deadlines (HW2/HW3/Midterm 1/Project 1).  
2. Set **your own deadlines** + milestones.  
3. Use `plan.md` as the template; fill in your own dates and milestones.
4. You can use `hw2_plan.md` in the submission_example of project1.zip as the example for this section.

---

### Warning!

**Be sure to use `Canvas/Information/ASE 230 Schedule` for scheduling.**
**`plan.md` is a required part of HW2.** If it is missing from your submission, this assignment will be graded as 0.

---

## Submission Checklist

Submit these files on Canvas:

1. `HW2_rubric.md`
   - Complete the self-grading checklist.
2. `plan.md` (fill in the provided template — see `hw2_plan.md` in the `submission_example` of `project1.zip` for a completed example)
   - Record the Canvas deadline and your earlier personal target date.
   - Add milestones for API design, implementation/testing, and tutorial/deployment work.
   - List your 10 planned endpoints in the Planned API Endpoints table, marking at least 2 as Bearer-token protected.
   - **Required.** If `plan.md` is missing, Assignment 4 (30%) is scored as 0%.

Keep a copy of `plan.md`; Project 1 requires it in the `plan/` directory.
