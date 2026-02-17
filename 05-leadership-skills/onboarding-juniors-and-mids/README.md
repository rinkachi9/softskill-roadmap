# Onboarding Juniors and Mids: A Guide for Mentors

A great onboarding experience is the single best investment you can make in a new team member. It's not just an IT checklist; it's a deliberate process designed to make a new engineer feel **Welcome, Confident, and Productive** as quickly as possible.

This guide provides a structured framework for onboarding new junior and mid-level developers, turning their initial uncertainty into long-term engagement and productivity.

---

## 1. The Core Pillars of Successful Onboarding

-   **Structure:** Don't improvise. A clear, written 30/60/90-day plan shows you are invested in their success and tells them exactly what to expect.
-   **Mentorship:** Assign a dedicated "buddy" or mentor who is **not** their manager. This gives them a safe person to ask "stupid" questions without feeling judged.
-   **Psychological Safety:** Explicitly state that questions are expected and welcome. The biggest blocker for a new hire is the fear of looking incompetent.
-   **Early Wins:** Momentum is everything. Engineer small, quick successes to build their confidence and help them learn the development workflow from end to end.

---

## 2. Phase 1: Pre-Week & Day 1 - Make Them Feel Welcome

The goal of this phase is to handle all logistics and create a warm, welcoming environment so they can focus on learning, not troubleshooting their laptop.

### Before They Start (Pre-boarding Checklist)

-   [ ] **Hardware:** Laptop and all accessories have been ordered and are confirmed to arrive on or before Day 1.
-   [ ] **Accounts:** All essential accounts have been created (Git, Slack/Teams, Jira, AWS, etc.).
-   [ ] **Access:** They have been granted access to the necessary code repositories and internal documentation.
-   [ ] **Calendar:** Key meetings have been added to their calendar (team stand-ups, 1:1s, planning sessions).
-   [ ] **Welcome Email:** A welcome email has been sent from the team a few days before they start.

### The First Day

-   **Share the Plan:** Walk them through their written 30/60/90-day plan.
-   **Introductions:** Introduce them to the immediate team and key collaborators in other departments.
-   **Buddy Handoff:** Formally introduce them to their mentor/buddy. The buddy's first responsibility is to help them get their local development environment set up.
-   **Goal for Day 1:** Successfully clone the main repository, install all dependencies, and run the application and its test suite locally. **No coding is required.** A successful day is one with zero frustration.

---

## 3. Phase 2: The First Week - Build Confidence & Learn the Process

The goal of the first week is to guide them through a complete development cycle on a low-risk task. The code itself is not the point; learning the *process* is.

-   **Assign the First Task:** This should be a small, well-defined, and unambiguous "win."
    -   **Good examples:** Fixing a typo in documentation, updating a minor dependency version, fixing a tiny bug with a known solution and good test coverage.
    -   **Bad examples:** A complex feature, a bug with no clear cause, anything without tests.
-   **The Goal of the First PR:** To learn the team's workflow:
    1.  How to create a branch.
    2.  How to make a change.
    3.  How to run the tests.
    4.  How to open a Pull Request.
    5.  How to participate in a code review.
    6.  How to merge their change.
-   **Schedule Pair Programming:** Set aside at least one 60-90 minute pair programming session with their buddy. Use this to transfer knowledge about the codebase or walk through a tricky part of the setup.
-   **Conduct a Codebase Tour:** Use architecture diagrams (like the C4 model) to explain the system. Show them where the different parts of the code live and explain the "why" behind the structure.
-   **Goal for Week 1:** Successfully merge their first pull request.

---

## 4. Phase 3: The First Month - Become Productive

The goal of the first month is to transition from heavily guided work to independent completion of a meaningful task.

-   **Assign Their First "Real" Task:**
    -   This should be a small, self-contained feature or a well-understood bug.
    -   The ticket should have a very clear definition of "done."
    -   If possible, break the work down into sub-tasks within the ticket to provide a clear path.
-   **Integrate into Team Rituals:**
    -   Encourage them to share their progress in stand-ups.
    -   Have them shadow the on-call rotation to learn about operational issues.
    -   After they complete their first real task, have them demo it to the team or stakeholders.
-   **Establish Strong Feedback Loops:**
    -   **Manager 1:1s (Weekly):** Focus on their experience. Ask questions like: "What was the most confusing thing you encountered this week?", "What's one thing you learned?", "Are you getting what you need from your buddy?".
    -   **Buddy Check-ins (Daily):** A quick, informal "Got any blockers? Anything weird you saw?". This is for tactical, in-the-moment help.
    -   **Code Reviews:** Treat every code review as a mentoring session. (See the "Code Review as Mentoring" guide).

-   **Goal for Month 1:** Independently own and complete a non-trivial task from start to finish.

---

## 5. Onboarding Mid-Level Engineers: Key Differences

Mid-level engineers already know *how* to be a software engineer; they just don't know how to be one *at your company*. Your goal is to provide **context**.

-   **Focus on the "Why," Not the "How":** They don't need to be taught Git, but they do need to know *why* you use a specific branching strategy. They don't need to be taught a design pattern, but they do need to understand the architectural trade-offs that led to your current system design.
-   **Grant More Autonomy:** Their first task can be more ambiguous. Instead of giving them a solution to implement, give them a problem to solve and ask them to propose a solution. This is a great way to assess their skills and leverage their prior experience.
-   **Leverage Their Experience:** Actively ask for their perspective. "In your last role, how did you solve this kind of problem? It's valuable for us to hear different approaches." This shows respect and can bring fresh ideas to the team.

---

## Conclusion

Onboarding is an investment that pays dividends for years. A structured and welcoming process accelerates a new hire's productivity, builds their long-term loyalty, and strengthens your entire team by reinforcing a culture of mentorship and support. Treat your onboarding plan as a living document and solicit feedback from every new hire to improve it over time.
