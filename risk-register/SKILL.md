---
name: risk-register
description: Create a Risk Register to track and manage project risks with likelihood, impact, and mitigation strategies. Use when user asks for "risk register", "risk log", "risk management", "risk assessment", or "risk tracking".
---

# Risk Register

Track and manage project risks.

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
- Save to `doc-assist/project-management/risk-register.md`
- Use kebab-case for filenames
- Confirm the save location with the user

**If changes needed:**
- Iterate on the content based on feedback
- Show updated version
- Repeat confirmation step

## Template

```markdown
# Risk Register: [Project Name]

## Register Information
- **Project:** [Name]
- **Last Updated:** [Date]
- **Risk Manager:** [Name]

## Risk Summary
- **Total Risks:** [Number]
- **High Priority:** [Number]
- **Medium Priority:** [Number]
- **Low Priority:** [Number]
- **Open:** [Number] | **Closed:** [Number]

## Risk Scoring Matrix

| | Low (1) | Medium (2) | High (3) |
|--|---------|------------|----------|
| **High (3) Impact** | 3 - Medium | 6 - High | 9 - Critical |
| **Medium (2) Impact** | 2 - Low | 4 - Medium | 6 - High |
| **Low (1) Impact** | 1 - Low | 2 - Low | 3 - Medium |

## Active Risks

### Risk #1: [Risk Title]
| Attribute | Details |
|-----------|---------|
| **ID** | R-[Number] |
| **Category** | [Technical/Resource/Schedule/Budget/External] |
| **Description** | [What might happen] |
| **Trigger** | [What would cause this risk] |
| **Likelihood** | [High/Medium/Low] (Score: [1-3]) |
| **Impact** | [High/Medium/Low] (Score: [1-3]) |
| **Risk Score** | [Likelihood × Impact] |
| **Priority** | [Critical/High/Medium/Low] |
| **Owner** | [Name] |
| **Mitigation Strategy** | [How to prevent/reduce] |
| **Contingency Plan** | [What to do if it happens] |
| **Status** | [Open/Mitigating/Closed] |
| **Target Date** | [When to review/resolve] |

### Risk #2: [Risk Title]
...

## Closed Risks
| ID | Risk | Closure Date | Resolution |
|----|------|--------------|------------|
| R-XX | [Description] | [Date] | [How it was resolved] |
```
