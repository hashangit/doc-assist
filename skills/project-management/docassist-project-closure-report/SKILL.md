---
name: project-closure-report
description: Create a Project Closure Report to formally close a project with final status and deliverables. Use when user asks for "closure report", "project closeout", "final report", or "project completion".
---

# Project Closure Report

Final project documentation.

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
- Save to `doc-assist/project-management/project-closure-report.md`
- Confirm the save location with the user

## Template

```markdown
# Project Closure Report: [Project Name]

## Executive Summary
[Brief overview of project outcomes and closure status]

## Project Information
- **Project Name:** [Name]
- **Project Manager:** [Name]
- **Sponsor:** [Name]
- **Start Date:** [Date]
- **Original End Date:** [Date]
- **Actual End Date:** [Date]

## Objectives Achievement

| Objective | Target | Actual | Status |
|-----------|--------|--------|--------|
| [Objective 1] | [Target] | [Result] | ✅ Met / ⚠️ Partial / ❌ Not Met |

## Scope Delivery

### Delivered
- [Deliverable 1] - [Status]
- [Deliverable 2] - [Status]

### Not Delivered
- [Item] - [Reason]

### Scope Changes
| CR # | Change | Impact | Status |
|------|--------|--------|--------|
| CR-001 | [Description] | [Schedule/Budget] | Approved |

## Schedule Performance
- **Planned Duration:** [Days]
- **Actual Duration:** [Days]
- **Variance:** [+/- Days]
- **Variance Reason:** [Explanation]

## Budget Performance
| Category | Budget | Actual | Variance |
|----------|--------|--------|----------|
| Labor | $[X] | $[X] | $[X] |
| Other | $[X] | $[X] | $[X] |
| **Total** | **$[X]** | **$[X]** | **$[X]** |

## Quality Metrics
| Metric | Target | Actual | Status |
|--------|--------|--------|--------|
| [Metric] | [Target] | [Result] | [Status] |

## Risks Summary
- **Total Risks Identified:** [Number]
- **Risks That Occurred:** [Number]
- **Risk Management Effectiveness:** [Effective/Partially Effective/Ineffective]

## Outstanding Items
| Item | Type | Owner | Resolution Plan |
|------|------|-------|-----------------|
| [Item] | [Issue/Defect/Action] | [Name] | [Plan] |

## Transition Plan

### Handoff Items
| Item | Recipient | Date | Status |
|------|-----------|------|--------|
| [Item] | [Team/Person] | [Date] | [Status] |

### Ongoing Support
[What support is needed post-project]

## Lessons Learned Summary
[Link to full Lessons Learned document - key highlights]

## Team Recognition
[Acknowledge team contributions]

## Recommendations
1. [Recommendation 1]
2. [Recommendation 2]

## Sign-Off
| Role | Name | Signature | Date |
|------|------|-----------|------|
| Project Manager | [Name] | | |
| Sponsor | [Name] | | |

## Attachments
- [ ] Final project schedule
- [ ] Final budget report
- [ ] Lessons learned document
- [ ] Transition documentation
```
