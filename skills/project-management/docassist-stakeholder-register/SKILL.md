---
name: stakeholder-register
description: Create a Stakeholder Register that maps all project stakeholders with their interests, influence, and engagement strategies. Use when user asks for "stakeholder register", "stakeholder analysis", "stakeholder map", or "stakeholder management".
---

# Stakeholder Register

Create a comprehensive map of all project stakeholders.

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
- Save to `doc-assist/project-management/stakeholder-register.md`
- Use kebab-case for filenames
- Confirm the save location with the user

**If changes needed:**
- Iterate on the content based on feedback
- Show updated version
- Repeat confirmation step

## Template

```markdown
# Stakeholder Register: [Project Name]

## Stakeholder Summary
- **Total Stakeholders:** [Number]
- **Last Updated:** [Date]

## Stakeholder Details

### [Stakeholder Name/Group]

| Attribute | Details |
|-----------|---------|
| **Role/Title** | [Position] |
| **Organization** | [Company/Department] |
| **Contact** | [Email/Phone] |

**Interest:** [High/Medium/Low]
**Influence:** [High/Medium/Low]
**Support Level:** [Champion/Supporter/Neutral/Critic/Opponent]

**Key Concerns:**
- [Concern 1]
- [Concern 2]

**Communication Needs:**
- **Format:** [Report, meeting, email]
- **Frequency:** [Daily, weekly, monthly]
- **Content:** [What they need to know]

**Engagement Strategy:**
[How to manage this stakeholder]

---

## Stakeholder Matrix

| | Low Influence | High Influence |
|--|---------------|----------------|
| **High Interest** | Keep Informed | Manage Closely |
| **Low Interest** | Monitor | Keep Satisfied |

### Manage Closely
[Stakeholders with high influence + high interest]

### Keep Satisfied
[Stakeholders with high influence + low interest]

### Keep Informed
[Stakeholders with low influence + high interest]

### Monitor
[Stakeholders with low influence + low interest]
```
