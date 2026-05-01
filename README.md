# OpenCode CLI Developer Guide — Knowledge Assessment Quiz

**Document:** Developer_Guide_OpenCode_CLI_v5.docx  
**Date:** {{DATE}}  
**Candidate Name:** _________________________________  
**Team Lead:** _________________________________  
**Time Allowed:** 45 minutes  
**Total Points:** 120 points (MCQ: 80 pts | Essay: 40 pts)

---

## Section A — Multiple Choice Questions (10 questions × 8 pts each = 80 pts)

**Instructions:** Circle the correct answer for each question.

---

### Question 1
What is the primary purpose of the **AGENTS.md** file in an OpenCode CLI project?

A. It stores user authentication credentials for the CLI tool.  
B. It is a project configuration file automatically loaded by OpenCode CLI that defines tech stack, conventions, and constraints.  
C. It contains the compiled build output of the project.  
D. It is a log file for recording all AI-generated code changes.

---

### Question 2
Which of the following best describes the **Flat-Pack Approach**?

A. A method for packaging Node.js applications into a single executable file.  
B. A UI design pattern where all components are rendered on a single flat page.  
C. Decomposing the entire project into the smallest possible self-contained units before any code is generated or modified.  
D. A database normalization technique for reducing table redundancy.

---

### Question 3
According to the **Greek Sculptor approach**, what should the first prompt to OpenCode CLI contain?

A. Detailed component names, prop names, and exact function call order.  
B. Full file structure and naming conventions for every module.  
C. The outcome and intent (goal and constraints only), letting OpenCode CLI choose the shape.  
D. A step-by-step implementation guide with pseudocode for every function.

---

### Question 4
The **Strangler Fig Strategy** mandates that:

A. All legacy code must be refactored in a single sprint.  
B. New pages and major changes to existing legacy pages must be built using the approved flat-pack tech stack, not the legacy stack.  
C. Legacy databases should be replaced with NoSQL alternatives immediately.  
D. Developers should avoid touching any legacy code until a full system rewrite is approved.

---

### Question 5
What is the recommended **check-in cadence** for developers working with the consulting lead?

A. Daily stand-up meetings only.  
B. Hourly updates via Slack.  
C. Structured updates every 3 hours during active development days.  
D. Weekly summary emails every Friday afternoon.

---

### Question 6
Which of the following is **NOT** part of the **four mandatory developer gates**?

A. Instruct — the developer writes the prompt.  
B. Automate — the developer sets up CI/CD pipelines for every task.  
C. Review — every line of AI-generated code is read and understood by the developer.  
D. Publish — only the developer triggers deployment or release.

---

### Question 7
In the **COSMIC document workflow**, what is the correct order of steps?

A. Prototype → Build → Align → Set up  
B. Align → Prototype → Set up → Build  
C. Prototype → Align → Set up → Initialise → Build  
D. Set up → Prototype → Build → Align

---

### Question 8
According to the **Prompt Template** recommended in the guide, which of the following sections should **NOT** be included?

A. Context — describing the feature, module, or bug.  
B. Cost Estimate — calculating the dollar cost of running the AI prompt.  
C. Constraints — files, functions, or APIs that must not be changed.  
D. Expected Output — files to create or modify, function signatures, return types.

---

### Question 9
What is the **Alpine.js Flat-Pack Rule**?

A. Each Alpine.js component must be wrapped in a React wrapper for compatibility.  
B. Each Alpine.js component is a single, self-contained `x-data` block; components must not share state globally.  
C. Alpine.js components should always store state in `localStorage` for persistence.  
D. All Alpine.js components must be written in a single file called `alpine-flat-pack.js`.

---

### Question 10
Which storage method is **explicitly forbidden** for JWT tokens according to the authentication standards?

A. httpOnly cookies.  
B. In-memory state.  
C. localStorage.  
D. Secure, encrypted session storage managed by the backend.

---

## Section B — Essay Questions (2 questions × 20 pts each = 40 pts)

**Instructions:** Answer each question in 150–300 words. Be specific and reference concepts from the guide where possible.

---

### Essay Question 1 (20 pts)

**Explain the "Think → Plan → Build" workflow and why it is critical for complex tasks. Describe how a developer should apply the two-step reasoning approach when debugging a performance issue, using a specific example from the guide's Appendix A.**

**_____________________________________________________________________________**

**_____________________________________________________________________________**

**_____________________________________________________________________________**

**_____________________________________________________________________________**

**_____________________________________________________________________________**

**_____________________________________________________________________________**

**_____________________________________________________________________________**

**_____________________________________________________________________________**

---

### Essay Question 2 (20 pts)

**Describe the role of STYLE.md in a project and how it interacts with AGENTS.md and OpenCode CLI. Include at least three specific design standards (e.g., spacing, colour tokens, or interaction rules) and explain why enforcing these through STYLE.md produces better UI output than ad-hoc prompting.**

**_____________________________________________________________________________**

**_____________________________________________________________________________**

**_____________________________________________________________________________**

**_____________________________________________________________________________**

**_____________________________________________________________________________**

**_____________________________________________________________________________**

**_____________________________________________________________________________**

**_____________________________________________________________________________**

---

## Answer Key — For Assessor Use Only

| Q# | Correct Answer |
|----|----------------|
| 1  | B |
| 2  | C |
| 3  | C |
| 4  | B |
| 5  | C |
| 6  | B |
| 7  | C |
| 8  | B |
| 9  | B |
| 10 | C |

**Essay Rubric (per question):**
- **18–20 pts:** Excellent understanding; specific references to guide; clear, structured reasoning.
- **14–17 pts:** Good understanding; some references; minor gaps in explanation.
- **10–13 pts:** Basic understanding; vague or generic answer; few specific references.
- **5–9 pts:** Limited understanding; significant misinterpretations of the guide.
- **0–4 pts:** Little to no relevant content; off-topic or unanswered.

---

## Score Summary Sheet

| Section | Max Points | Points Earned | Percentage |
|---------|------------|---------------|------------|
| Multiple Choice (10 × 8 pts) | 80 | _________ | _________ % |
| Essay 1 | 20 | _________ | _________ % |
| Essay 2 | 20 | _________ | _________ % |
| **TOTAL** | **120** | **_________** | **_________ %** |

---

## Final Assessment Report for Team Lead

**To:** Team Lead  
**From:** _________________________________ (Assessor)  
**Re:** Knowledge Assessment — OpenCode CLI Developer Guide v5  
**Date:** {{DATE}}

### Candidate Information
- **Name:** _________________________________
- **Assessment Date:** _________________________________
- **Document Version:** Developer_Guide_OpenCode_CLI_v5.docx

### Overall Score

| Metric | Result |
|--------|--------|
| Total Points Earned | _________ / 120 |
| Overall Percentage | _________ % |
| Grade | _________ |

### Grading Scale
- **A (90–100%):** Exceptional mastery of the guide. Ready to lead OpenCode CLI workflows independently.
- **B (80–89%):** Strong understanding. Minor gaps; ready to work with light supervision.
- **C (70–79%):** Adequate understanding. Review recommended in weaker areas before independent work.
- **D (60–69%):** Below expectations. Requires structured re-study and reassessment.
- **F (< 60%):** Does not meet minimum competency. Mandatory retraining required.

### Section Breakdown

| Section | Score | Notes |
|---------|-------|-------|
| MCQ Section | _________ / 80 | |
| Essay 1 — Think→Plan→Build | _________ / 20 | |
| Essay 2 — STYLE.md & Design Standards | _________ / 20 | |

### Assessor Comments

_____________________________________________________________________________

_____________________________________________________________________________

_____________________________________________________________________________

### Recommendation

☐ **Pass** — Candidate demonstrates sufficient knowledge to proceed with OpenCode CLI development tasks.  
☐ **Pass with Review** — Candidate passes but should revisit specific topics: _________________________________  
☐ **Reassessment Required** — Candidate should re-study the guide and retake this assessment within ____ days.

---

**Assessor Signature:** _________________________________  
**Date:** _________________________________

---

*This report was generated from the Developer_Guide_OpenCode_CLI_v5.docx knowledge assessment. All scores and recommendations are based on the official guide content.*
