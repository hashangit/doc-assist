---
name: communication-plan
description: Create a Communication Plan that defines how information flows across the project. Use when user asks for "communication plan", "communications matrix", "meeting cadence", or "escalation path".
---

# Communication Plan

Define how information flows across the project.

## Document Creation Workflow

### Step 1: Setup Directory Structure
Create the doc-assist folder structure in the project root if it doesn't exist:
```
doc-assist/
├── project-management/
├── product-management/
├── marketing/
└── bridge/
```

### Step 2: Generate Document
Using the template below, create the document with appropriate content based on user input and context.

### Step 3: Preview for User
Display the complete document content to the user in a code block for review.

### Step 4: Confirm and Save
Ask the user: "Does this document meet your expectations? Should I save it?"

**If confirmed:**
- Save to `doc-assist/project-management/communication-plan.md`
- Confirm the save location with the user

## Template

```markdown
# Communication Plan: [Project Name]

## Communication Objectives
1. [Objective 1: e.g., Keep stakeholders informed of progress]
2. [Objective 2: e.g., Escalate issues promptly]

## Communication Matrix

| Communication | Audience | Owner | Format | Frequency | Purpose |
|---------------|----------|-------|--------|-----------|---------|
| Status Report | Project Team | PM | Email/Slack | Weekly | Progress update |
| Steering Committee | Sponsors, Leads | PM | Presentation | Monthly | Governance |
| Team Standup | Team Members | Scrum Master | Meeting | Daily | Sync |
| Risk Review | PM, Leads | PM | Meeting | Bi-weekly | Risk assessment |

## Meeting Cadence

### Daily Standup
- **Time:** [Time]
- **Duration:** 15 minutes
- **Attendees:** [Who]
- **Format:** [What, So What, Now What / Three Questions]

### Weekly Team Meeting
- **Time:** [Day/Time]
- **Duration:** [Minutes]
- **Attendees:** [Who]
- **Agenda:**
  1. Review action items
  2. Progress update
  3. Blockers/discussion
  4. Next week priorities

### Monthly Steering Committee
- **Time:** [Day/Time]
- **Duration:** [Minutes]
- **Attendees:** [Who]
- **Agenda:**
  1. Executive summary
  2. Key metrics
  3. Risks and issues
  4. Decisions needed

## Escalation Path
1. **Level 1:** Team Lead → [Contact, timeline]
2. **Level 2:** Project Manager → [Contact, timeline]
3. **Level 3:** Sponsor → [Contact, timeline]

## Communication Channels
| Channel | Use For | Response Time |
|---------|---------|---------------|
| Slack | Quick questions, updates | Same day |
| Email | Formal communication, decisions | 24 hours |
| Meeting | Complex discussions, decisions | Scheduled |
| Phone/Urgent | Critical issues | Immediate |
```
