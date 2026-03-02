---
description: Your intelligent guide for creating PM, Marketing, and Project Management documents. Use when you need help choosing or creating any business document.
argument-hint: Optional document type or scenario (e.g., "project charter", "launch feature", "status report")
---

# Doc Assist

Your intelligent guide for choosing and creating the right business document.

## Workflow

```
┌─────────────────┐    ┌──────────────────┐    ┌─────────────────┐
│  1. DISCOVERY   │───▶│ 2. REQUIREMENTS  │───▶│ 3. GENERATION   │
│  Find the right │    │  Gather details  │    │  Create doc     │
│  document       │    │  via brainstorm  │    │  from template  │
└─────────────────┘    └──────────────────┘    └─────────────────┘
                                                      │
                                                      ▼
┌─────────────────┐    ┌──────────────────┐    ┌─────────────────┐
│  5. SAVE        │◀───│ 4. HUMANIZATION  │◀───│ Document Ready  │
│  Write .md file │    │  Polish & refine │    │  for review     │
└─────────────────┘    └──────────────────┘    └─────────────────┘
```

---

## Phase 1: Discovery

**Goal:** Identify the right document for the user's situation.

**Actions:**
1. Understand what the user is trying to accomplish
2. Use the decision tree below to identify the document type
3. Confirm with user: "You need a [document]. Should I help you create it?"

**Decision Tree:**

| If user is... | Use document category... |
|---------------|--------------------------|
| Starting/running/closing a project | Project Management |
| Setting product direction | Product Strategy |
| Defining what to build | Product Discovery |
| Researching/validating | Product Research |
| Positioning in market | Marketing Positioning |
| Planning content/campaigns | Marketing Content |
| Launching product | Marketing Launch |
| Cross-functional needs | Bridge Documents |

---

## Phase 2: Requirements Gathering

**Goal:** Understand the specific needs before generating.

<HARD-GATE>
You MUST invoke the `/docassist-brainstorm` skill before generating any document.
Do NOT skip this step regardless of how simple the request seems.
</HARD-GATE>

**Actions:**
1. Invoke `/docassist-brainstorm` to gather requirements
2. Understand: context, purpose, audience, scope, specifics
3. Confirm approach with user before proceeding

---

## Phase 3: Document Generation

**Goal:** Create the document using proven templates.

**Actions:**
1. Invoke the specific document skill (e.g., `/docassist-project-charter`)
2. Generate content based on gathered requirements
3. Display complete document for review

---

## Phase 4: Humanization (Optional)

**Goal:** Make the document feel natural and human-written.

**Actions:**
1. Ask: "Would you like me to humanize this document?"
2. If yes, apply natural language patterns
3. Remove AI-generated boilerplate
4. Show polished version for approval

---

## Phase 5: Save

**Goal:** Persist the approved document.

**Actions:**
1. Ask: "Does this meet your expectations? Should I save it?"
2. If yes, save to appropriate folder:
   - Project Management → `doc-assist/project-management/`
   - Product Management → `doc-assist/product-management/`
   - Marketing → `doc-assist/marketing/`
   - Bridge → `doc-assist/bridge/`

---

## Quick Reference

### By Scenario

| Scenario | Start With |
|----------|------------|
| Starting a new project | `/docassist-project-charter` |
| Running a project | `/docassist-status-report` |
| Launching a feature | `/docassist-product-brief` → `/docassist-prd` → `/docassist-gtm-strategy` |
| Sales enablement | `/docassist-sales-enablement-kit` |
| User research | `/docassist-user-personas` |

### By Role

| Role | Most Used Commands |
|------|-------------------|
| Project Manager | `/docassist-project-charter`, `/docassist-status-report`, `/docassist-risk-register` |
| Product Manager | `/docassist-prd`, `/docassist-product-roadmap`, `/docassist-product-brief` |
| Product Marketing | `/docassist-positioning-statement`, `/docassist-gtm-strategy` |
| UX Researcher | `/docassist-user-personas`, `/docassist-user-research-report` |

### All Available Commands

**Project Management:** `/docassist-project-charter`, `/docassist-business-case`, `/docassist-stakeholder-register`, `/docassist-work-breakdown-structure`, `/docassist-project-schedule`, `/docassist-risk-register`, `/docassist-raci-matrix`, `/docassist-communication-plan`, `/docassist-status-report`, `/docassist-issue-log`, `/docassist-change-request`, `/docassist-lessons-learned`, `/docassist-project-closure-report`

**Product Strategy:** `/docassist-product-vision`, `/docassist-product-strategy`, `/docassist-product-roadmap`, `/docassist-okrs`

**Product Discovery:** `/docassist-prd`, `/docassist-user-stories`, `/docassist-jobs-to-be-done`, `/docassist-user-personas`, `/docassist-customer-journey-map`

**Product Research:** `/docassist-market-research`, `/docassist-user-research-report`, `/docassist-opportunity-assessment`

**Marketing Positioning:** `/docassist-positioning-statement`, `/docassist-messaging-framework`, `/docassist-value-proposition-canvas`, `/docassist-brand-guidelines`

**Marketing Content:** `/docassist-content-strategy`, `/docassist-campaign-brief`, `/docassist-competitor-battlecard`, `/docassist-case-study-brief`

**Marketing Launch:** `/docassist-gtm-strategy`, `/docassist-launch-checklist`, `/docassist-product-datasheet`, `/docassist-sales-enablement-kit`

**Bridge:** `/docassist-product-brief`, `/docassist-release-notes`, `/docassist-faq-help-center`, `/docassist-product-demo-script`

---

## Delegation

For detailed decision trees, templates, and document-specific guidance, invoke the `docassist` skill.

```
Use the docassist skill for comprehensive document selection and creation guidance.
```
