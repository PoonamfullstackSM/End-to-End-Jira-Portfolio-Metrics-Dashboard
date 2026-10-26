# Packers & Movers Agile Project – Jira & Scrum Practice 🚚

A hands-on Agile project demonstrating how Jira can help a Scrum Team organize, estimate, plan, track, and inspect work for a Packers & Movers service platform. The project covers epics, user stories, backlog refinement, Planning Poker, bug tracking, custom fields, and sprint reporting.

## 🎯 Project Overview

The goal is to turn product needs into manageable work items and use Jira to support collaboration, transparency, sprint planning, and continuous improvement.

Key activities:

- Organize work using epics, user stories, and subtasks.
- Define acceptance criteria and refine the backlog.
- Estimate work using story points and Planning Poker.
- Track bugs with saved filters.
- Record business-value assessments with a custom field.
- Review sprint progress using velocity and burndown charts.

## 🗂️ Project Artifacts

### 1. Epics, User Stories & Subtasks

The backlog includes epics such as Product Management, Login/Registration, and Home Page. Example stories cover service selection, photo uploads, inventory, email login, registration, and customer-facing features.

One example story covers an administrator uploading Packers & Movers service types so users can browse services. Its acceptance criteria include required service fields, an upload action, a success message, visibility on the home page, and non-functional checks for browser compatibility, security, and performance.

Example subtasks include UI development, API development, database creation, integration, unit and end-to-end testing, deployment, documentation, and user acceptance testing.

### 2. Backlog Refinement & Sprint Planning

Jira is used to clarify requirements, discuss dependencies, and prepare backlog items for upcoming sprints. The screenshots show example estimates of 13, 8, 5, and 3 story points.

During Sprint Planning, the team considers the Sprint Goal, capacity, complexity, and dependencies when selecting work. Estimates support discussion and forecasting; they are not fixed performance targets.

### 3. Estimation Using Scrumpy Planning Poker

The Scrumpy Planning Poker app supports collaborative story-point estimation. Team members vote, review results, and discuss differences to build a shared understanding of the work.

### 4. Custom Field – Business Value

A Jira single-choice custom field named Business value is configured with options numbered 1 through 5.

The team should define each value and apply the scale consistently. The field supports prioritization discussions but does not determine priority on its own.

### 5. Bug Filter

A saved Jira filter named Bug filter uses these criteria:

- Space: Packers and Movers
- Assignee: Poonam
- Type: Bug
- Sprint: CKERSPA Sprint 2

One displayed example is “On resetting password confirmation mail is not going to the user.”

Saved filters help focus attention on work matching the selected criteria.

### 6. Pie Chart Gadget for Bug Filter

A Jira pie-chart gadget visualizes the Business value field for filtered issues.

The screenshot shows 2 total issues: one with value `5` and one with no value (`None`). This makes the distribution visible and highlights an issue whose field value may need review.

### 7. Velocity Chart

| Sprint           | Commitment | Completed |
| ---------------- | ---------- | --------- |
| CKERSPA Sprint 1 | 21         | 21        |
| CKERSPA Sprint 2 | 8          | 8         |

The average completed work across these two sprints is 14.5 story points per sprint.

Interpretation: The change from 21 to 8 points is a reason to inspect the context, not proof of lower productivity. The team can discuss capacity, complexity, availability, and the work selected.

Since only two sprints are shown, the average is an early reference point—not a reliable long-term forecast.

### 8. Burndown Chart

The burndown chart shows remaining work declining from approximately 21 story points to zero during the displayed sprint. Flat sections indicate periods when the remaining-work line did not change.

The team can investigate whether blockers, dependencies, work not yet reaching completion, or delayed chart updates explain these periods, then adapt its plan to support progress toward the Sprint Goal.

### 9. Metric Interpretation & Inspect and Adapt

The accompanying Metric Interpretation Report describes this cycle:

1. Inspect: Review the charts without jumping to conclusions.
2. Understand: Discuss the context behind changes or flat periods.
3. Adapt: Agree on actions, such as improving dependency coordination, splitting work into smaller pieces, or clarifying completion criteria.
4. Follow up: Check whether the actions help in later sprints.

The Sprint Review focuses on the product outcome and stakeholder feedback. The Sprint Retrospective focuses on how the Sprint went and what the Scrum Team can improve.

> Key principle: Velocity supports forecasting, while burndown visualizes remaining work. Use metrics for team learning and realistic planning—not to compare teams or pressure Developers to increase story points.

## 🔄 Scrum and Jira Workflow

1. Organize epics, user stories, and subtasks.
2. Add descriptions and acceptance criteria.
3. Refine backlog items and discuss value, priority, and dependencies.
4. Estimate collaboratively using Planning Poker.
5. Select work during Sprint Planning.
6. Track bugs using saved Jira filters.
7. Visualize issue data with dashboard gadgets.
8. Inspect sprint results using velocity and burndown charts.
9. Discuss findings and agree on improvements.

## 🛠️ Tools & Practices

- Jira: Backlog, sprint planning, work-item tracking, custom fields, filters, dashboards, and reports.
- Scrumpy Planning Poker: Collaborative estimation.
- Epics, user stories, and subtasks: Work organization and decomposition.
- Acceptance criteria: Clarifying expected behavior.
- Business Value field: Recording a value assessment.
- Velocity and burndown charts: Supporting inspection and forecasting.

## 📁 Repository Structure

Keep these artifacts alongside this README, using the same filenames.

```
.
├── Burndown Chart.jpg
├── Created Bug Filter.jpg
├── Created custom field- Business Value.PNG
├── Epics and user stories.PNG
├── Estimation using Scrumpy Planning Poker.PNG
├── Metric Interpretation Report.pdf
├── Refined Product Backlogs.jpg
├── Subtasks under user story.PNG
├── User Story & Acceptance Criteria.PNG
├── Using Pie Chart Gadget for Bug Filter.jpg
├── Velocity Chart.PNG
└── README.md
```

## 👩‍💻 My Role

Scrum Master / Agile Project Practitioner

Through this hands-on project, I practiced:

- Organizing epics, stories, and subtasks in Jira.
- Writing user stories and acceptance criteria.
- Supporting backlog refinement and sprint planning.
- Facilitating estimation with Planning Poker.
- Configuring a Business Value field and bug filter.
- Visualizing issue data with a dashboard gadget.
- Interpreting sprint charts to support team discussions and improvement.

## 📌 Project Outcome

The artifacts connect the main stages of Agile work:

Epics → User Stories → Acceptance Criteria & Subtasks → Backlog Refinement → Sprint Planning → Bug Tracking → Sprint Metrics → Inspect and Adapt

The project demonstrates practical familiarity with Jira and Scrum activities, and how work-item data and sprint reports can support transparency, shared understanding, and continuous improvement.

## 📚 Key Learnings

- Decomposing product capabilities into manageable work items.
- Clarifying requirements through acceptance criteria.
- Using Planning Poker for collaborative estimation.
- Preparing backlog items for sprint planning.
- Making work visible through filters and dashboards.
- Interpreting sprint metrics carefully and in context.
- Turning observations into practical improvement actions.

## ⚠️ Project Note

This is a hands-on portfolio and practice project based on the supplied Jira screenshots and metric report. It represents a simulated Packers & Movers project and a limited set of work items and sprint results. The two-sprint velocity average should not be treated as a reliable long-term forecast.
