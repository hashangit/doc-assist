---
name: release-notes
description: Create Release Notes to communicate shipped value to users. Use when user asks for "release notes", "changelog", "what's new", or "version notes".
---

# Release Notes

Communicate shipped value to users and for marketing.

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
### Step 3: Preview for User
### Step 4: Confirm and Save
**Save to:** `doc-assist/bridge/release-notes-v[X.Y].md`

## Template

```markdown
# [Product Name] - Release Notes
## Version [X.Y.Z] - [Date]

---

## Highlights

### [Major Feature Name]
[Brief description of the feature and its value - 2-3 sentences]

**Who it's for:** [Target users]
**Why it matters:** [Business/user value]

---

## New Features

### [Feature 1]
[Description of what it does and why it's useful]

### [Feature 2]
[Description of what it does and why it's useful]

---

## Improvements

- **[Area 1]**: [What's better and by how much]
- **[Area 2]**: [What's better and by how much]
- **[Area 3]**: [What's better and by how much]

---

## Bug Fixes

- Fixed [issue description] that affected [user impact]
- Fixed [issue description] that affected [user impact]
- Fixed [issue description] that affected [user impact]

---

## Deprecations

### [Feature Being Deprecated]
- **What's changing:** [Description]
- **When:** [Date]
- **Migration path:** [What users should do]
- **Why:** [Reason for deprecation]

---

## Known Issues

| Issue | Impact | Workaround | Fix ETA |
|-------|--------|------------|---------|
| [Issue] | [What's affected] | [How to work around] | [When] |

---

## Coming Soon

### [Upcoming Feature]
[Teaser description - build anticipation]

---

## How to Update

### Cloud
[Automatically updated / No action required]

### Self-Hosted
```bash
[Update commands]
```

---

## Feedback

Have questions or feedback? [Contact us / Join community / Submit issue]

---

## Release Versions by Audience

### For Customers (Marketing-focused)
```markdown
# What's New in [Product Name]

We're excited to share our latest updates! Here's what's new:

## New: [Feature Name]
[Value-focused description - how it helps customers]

## Improved: [Area]
[How it's better now]

## Fixed: [Issue]
[What was fixed]

[Call to action - try it now / learn more]
```

### For Internal Teams (Detailed)
[Use the full structure above]

### For Developers (Technical)
```markdown
# [Product] [Version] - [Date]

## API Changes
- [Breaking changes]
- [New endpoints]
- [Deprecated endpoints]

## SDK Updates
- [Language]: [Changes]

## Infrastructure
- [Changes to infrastructure]
```
```
