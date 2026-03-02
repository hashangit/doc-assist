---
name: status-report
description: Create a Project Status Report for regular progress updates. Use when user asks for "status report", "progress report", "weekly report", "project update", or "status update".
---

# Status Report

Create regular project progress updates.

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
- Save to `doc-assist/project-management/status-report.md`
- Confirm the save location with the user

## Template

```markdown
# Project Status Report: [Project Name]

## Report Information
- **Reporting Period:** [Start Date] - [End Date]
- **Report Date:** [Date]
- **Prepared By:** [Name]

## Executive Summary
[2-3 sentences summarizing overall status and key points]

## Overall Status
| Area | Status | Trend |
|------|--------|-------|
| **Schedule** | 🟢 On Track / 🟡 At Risk / 🔴 Off Track | ↗️ ➡️ ↘️ |
| **Budget** | 🟢 On Track / 🟡 At Risk / 🔴 Off Track | ↗️ ➡️ ↘️ |
| **Scope** | 🟢 On Track / 🟡 At Risk / 🔴 Off Track | ↗️ ➡️ ↘️ |
| **Quality** | 🟢 On Track / 🟡 At Risk / 🔴 Off Track | ↗️ ➡️ ↘️ |
| **Overall** | 🟢 On Track / 🟡 At Risk / 🔴 Off Track | ↗️ ➡️ ↘️ |

## Key Accomplishments This Period
- ✅ [Accomplishment 1]
- ✅ [Accomplishment 2]
- ✅ [Accomplishment 3]

## Planned vs. Actual
| Milestone/Deliverable | Planned Date | Actual/Forecast | Status |
|-----------------------|--------------|-----------------|--------|
| [Item 1] | [Date] | [Date] | [Status] |

## Upcoming Activities (Next Period)
- [ ] [Activity 1] - Due: [Date]
- [ ] [Activity 2] - Due: [Date]

## Risks & Issues
### Top Risks
| Risk | Impact | Mitigation | Status |
|------|--------|------------|--------|
| [Risk 1] | [H/M/L] | [Plan] | [Status] |

### Active Issues
| Issue | Owner | Due Date | Status |
|-------|-------|----------|--------|
| [Issue 1] | [Name] | [Date] | [Open/In Progress] |

## Budget Status
| Category | Budget | Spent | Remaining | % Used |
|----------|--------|-------|-----------|--------|
| [Category] | $[X] | $[X] | $[X] | [%] |
| **Total** | **$[X]** | **$[X]** | **$[X]** | **[%]** |

## Decisions Needed
| Decision | Options | Owner | Due Date |
|----------|---------|-------|----------|
| [Decision needed] | [Options] | [Name] | [Date] |

## Help Needed
[What support is needed from leadership/stakeholders]
```
