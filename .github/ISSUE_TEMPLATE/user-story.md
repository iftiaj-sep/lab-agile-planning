---
name: User Story
about: User's story purpose
title: ''
labels: ''
assignees: ''

---

📘 User Stories & Epics — Agile Notes
🧾 What is a User Story?
A User Story represents a small piece of business value that a team can deliver in a “done” increment.

User stories ≠ requirements — they are more holistic, focusing on:

Who it's for

What is needed

Why it matters (business value)

✍️ User Story Format
"As a [role], I need [functionality], so that [business value]."

Example:

As a marketing manager, I need a list of customer emails so I can notify them of promotions.

🧠 Include These in a Good User Story
Description – Who, what, and why (value).

Assumptions & Details – Pre-decisions (e.g., using a relational DB).

Acceptance Criteria – Definition of Done (DoD), written in Gherkin syntax.

✅ Gherkin Syntax for Acceptance Criteria
Helps describe system behavior clearly:

Given: The precondition (e.g., "Given 100 customers in DB, 90 opted in")

When: The trigger or action (e.g., "When I request a customer email list")

Then: The testable outcome (e.g., "Then I should see a list of 90 emails")

🗣️ This syntax is understood by developers, testers, and stakeholders alike.

🧩 INVEST: Attributes of a Well-Formed User Story
Acronym by Bill Wake:

Letter	Meaning	Explanation
I	Independent	Stories should be movable in backlog and ideally not depend on others.
N	Negotiable	Not fixed in scope—can be refined or reprioritized.
V	Valuable	Must deliver business/customer value.
E	Estimable	Must be clear enough to estimate size/effort.
S	Small	Should fit within one sprint.
T	Testable	Should have clear criteria to determine if it’s done.

🧱 What is an Epic?
An Epic is:

A large user story that cannot be completed in a single sprint.

Used to capture big ideas or broad features.

Broken down into smaller stories for sprint planning.

📌 Use an Epic when:

The item is too big to estimate or finish in one sprint.

A new request sounds small but spans multiple sprints.

🧠 Key Takeaways
A user story is a short, clear description of a user need and business value.

Add acceptance criteria using Gherkin to reduce miscommunication.

Ensure user stories follow the INVEST model.

Use Epics to capture large-scale features and break them down for sprints.
