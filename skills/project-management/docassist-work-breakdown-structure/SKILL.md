---
name: work-breakdown-structure
description: Create a Work Breakdown Structure (WBS) that hierarchically decomposes project work into manageable work packages. Use when user asks for "WBS", "work breakdown structure", "work packages", "project decomposition", or "task hierarchy".
---

# Work Breakdown Structure (WBS)

Create a hierarchical decomposition of project work.

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
- Save to `doc-assist/project-management/work-breakdown-structure.md`
- Use kebab-case for filenames
- Confirm the save location with the user

**If changes needed:**
- Iterate on the content based on feedback
- Show updated version
- Repeat confirmation step

## Template

```markdown
# Work Breakdown Structure: [Project Name]

## WBS Overview
- **Project:** [Name]
- **Version:** [Number]
- **Date:** [Date]

## WBS Dictionary

### 1.0 [Project Name]
#### 1.1 [Phase/Component]
##### 1.1.1 [Deliverable]
###### 1.1.1.1 [Work Package]

---

## WBS Structure

## 1.0 [Project Name]

### 1.1 [Phase 1: e.g., Planning]
| WBS # | Work Package | Description | Owner | Est. Hours |
|-------|--------------|-------------|-------|------------|
| 1.1.1 | [Task 1] | [Description] | [Name] | [Hours] |
| 1.1.2 | [Task 2] | [Description] | [Name] | [Hours] |

### 1.2 [Phase 2: e.g., Design]
| WBS # | Work Package | Description | Owner | Est. Hours |
|-------|--------------|-------------|-------|------------|
| 1.2.1 | [Task 1] | [Description] | [Name] | [Hours] |

### 1.3 [Phase 3: e.g., Development]
| WBS # | Work Package | Description | Owner | Est. Hours |
|-------|--------------|-------------|-------|------------|

### 1.4 [Phase 4: e.g., Testing]
...

### 1.5 [Phase 5: e.g., Deployment]
...

### 1.6 [Phase 6: e.g., Closure]
...

---

## WBS Summary
| Phase | Work Packages | Total Hours |
|-------|---------------|-------------|
| 1.1 Planning | [#] | [Hours] |
| **Total** | **[#]** | **[Hours]** |
```
