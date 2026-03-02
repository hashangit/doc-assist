---
name: lessons-learned
description: Create a Lessons Learned document to capture project learnings for future reference. Use when user asks for "lessons learned", "project retrospective", "post-mortem", or "learnings".
---

# Lessons Learned

Document learnings for future projects.

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
- Save to `doc-assist/project-management/lessons-learned.md`
- Confirm the save location with the user

## Template

```markdown
# Lessons Learned: [Project Name]

## Document Information
- **Project:** [Name]
- **Project Manager:** [Name]
- **Date:** [Date]
- **Participants:** [Names]

## Executive Summary
[Key takeaways in 2-3 sentences]

## What Went Well

### Success 1: [Title]
- **Description:** [What happened]
- **Why it worked:** [Root cause of success]
- **Recommendation:** [How to replicate]

### Success 2: [Title]
...

## What Could Be Improved

### Challenge 1: [Title]
- **Description:** [What happened]
- **Impact:** [Effect on project]
- **Root Cause:** [Why it happened]
- **Recommendation:** [How to avoid in future]

### Challenge 2: [Title]
...

## By Category

### Project Management
| Lesson | Category | Recommendation |
|--------|----------|----------------|
| [Lesson] | Planning/Execution/Communication | [Action] |

### Technical
| Lesson | Category | Recommendation |
|--------|----------|----------------|
| [Lesson] | Architecture/Tools/Process | [Action] |

### Team & Resources
| Lesson | Category | Recommendation |
|--------|----------|----------------|
| [Lesson] | Staffing/Skills/Culture | [Action] |

## Process Improvements
1. [Improvement 1]
2. [Improvement 2]
3. [Improvement 3]

## What We Would Do Differently
1. [Action 1]
2. [Action 2]
3. [Action 3]

## Best Practices Identified
1. [Best practice 1]
2. [Best practice 2]

## Action Items for Future Projects
| Action | Owner | Priority |
|--------|-------|----------|
| [Action] | [Team/Role] | [H/M/L] |
```
