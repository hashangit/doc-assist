---
name: issue-log
description: Create an Issue Log to track and manage project issues. Use when user asks for "issue log", "issue tracker", "problem log", or "issue register".
---

# Issue Log

Track and manage project issues.

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
- Save to `doc-assist/project-management/issue-log.md`
- Confirm the save location with the user

## Template

```markdown
# Issue Log: [Project Name]

## Log Information
- **Last Updated:** [Date]
- **Total Issues:** [Number]
- **Open:** [Number] | **In Progress:** [Number] | **Closed:** [Number]

## Issue Summary
| Priority | Open | In Progress | Closed |
|----------|------|-------------|--------|
| Critical | [#] | [#] | [#] |
| High | [#] | [#] | [#] |
| Medium | [#] | [#] | [#] |
| Low | [#] | [#] | [#] |

## Active Issues

### Issue #1: [Issue Title]
| Attribute | Details |
|-----------|---------|
| **ID** | ISS-[Number] |
| **Date Raised** | [Date] |
| **Raised By** | [Name] |
| **Category** | [Technical/Resource/Schedule/External] |
| **Priority** | [Critical/High/Medium/Low] |
| **Description** | [What is the problem] |
| **Impact** | [What happens if not resolved] |
| **Owner** | [Name] |
| **Assigned To** | [Name] |
| **Root Cause** | [Why this happened] |
| **Resolution** | [How it will be/was fixed] |
| **Target Date** | [Date] |
| **Status** | [Open/In Progress/Resolved/Closed] |
| **Closure Date** | [Date] |

### Issue #2: [Issue Title]
...

## Closed Issues
| ID | Issue | Resolution | Closure Date |
|----|-------|------------|--------------|
| ISS-XX | [Description] | [How resolved] | [Date] |
```
