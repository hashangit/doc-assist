---
name: docassist
description: Your intelligent guide for creating Product Management, Marketing, and Project Management documents. Use as the primary entry point via /docassist to get help choosing the right document. Triggers on "which document", "what document should I use", "help me choose document", "document for [scenario]", or when unsure which document skill to use.
---

# Doc Assist

Your intelligent guide for choosing and creating the right business document.

## How to Use

**Simply describe what you're trying to do and I'll guide you to the right document.**

Examples of what you can ask:
- "I'm launching a new feature, what documents do I need?"
- "Help me create a project charter"
- "I need to define our product's market position"
- "What's the best document for tracking project risks?"
- "I'm doing user research, how should I document findings?"

## Quick Decision Tree

```
What are you trying to do?

├── Manage a project?
│   └──→ Project Management Documents
│       ├── /project-charter - Authorization document
│       ├── /business-case - Investment justification
│       ├── /stakeholder-register - Map stakeholders
│       ├── /work-breakdown-structure - Break down work
│       ├── /project-schedule - Timeline & milestones
│       ├── /risk-register - Track risks
│       ├── /raci-matrix - Clarify roles
│       ├── /communication-plan - Information flow
│       ├── /status-report - Progress updates
│       ├── /issue-log - Track problems
│       ├── /change-request - Scope changes
│       ├── /lessons-learned - Document learnings
│       └── /project-closure-report - Final documentation
│
├── Define product direction?
│   └──→ Strategy Documents
│       ├── /product-vision - 3-5 year direction
│       ├── /product-strategy - How to win
│       ├── /product-roadmap - Timeline/priorities
│       └── /okrs - Measurable goals
│
├── Specify what to build?
│   └──→ Discovery Documents
│       ├── /prd - Feature specifications
│       ├── /user-stories - Requirements
│       ├── /jobs-to-be-done - Customer motivations
│       ├── /user-personas - User archetypes
│       └── /customer-journey-map - Experience mapping
│
├── Research and validate?
│   └──→ Research Documents
│       ├── /market-research - Competitive/size/trends
│       ├── /user-research-report - Interview/survey findings
│       └── /opportunity-assessment - Business case
│
├── Define market position?
│   └──→ Positioning Documents
│       ├── /positioning-statement - Market position
│       ├── /messaging-framework - Key messages
│       ├── /value-proposition-canvas - Pains/gains
│       └── /brand-guidelines - Voice/visual identity
│
├── Plan content or campaigns?
│   └──→ Content Documents
│       ├── /content-strategy - Pillars/calendar
│       ├── /campaign-brief - Marketing campaign
│       ├── /competitor-battlecard - Sales enablement
│       └── /case-study-brief - Customer story
│
├── Launch product?
│   └──→ Launch Documents
│       ├── /gtm-strategy - Launch plan
│       ├── /launch-checklist - Readiness
│       ├── /product-datasheet - Feature summary
│       └── /sales-enablement-kit - Pitch/demo/FAQ
│
└── Create cross-functional docs?
    └──→ Bridge Documents
        ├── /product-brief - Feature summary
        ├── /release-notes - Shipped value
        ├── /faq-help-center - User education
        └── /product-demo-script - Product demos
```

## By Scenario

### "I'm starting a new project"
| Phase | Document | Command |
|-------|----------|---------|
| Get authorization | Project Charter | `/project-charter` |
| Justify investment | Business Case | `/business-case` |
| Map stakeholders | Stakeholder Register | `/stakeholder-register` |
| Break down work | WBS | `/work-breakdown-structure` |
| Create timeline | Project Schedule | `/project-schedule` |
| Identify risks | Risk Register | `/risk-register` |
| Clarify roles | RACI Matrix | `/raci-matrix` |

### "I'm running a project"
| Need | Document | Command |
|------|----------|---------|
| Report progress | Status Report | `/status-report` |
| Track problems | Issue Log | `/issue-log` |
| Request changes | Change Request | `/change-request` |
| Plan communications | Communication Plan | `/communication-plan` |

### "I'm closing a project"
| Need | Document | Command |
|------|----------|---------|
| Document learnings | Lessons Learned | `/lessons-learned` |
| Final report | Closure Report | `/project-closure-report` |

### "I'm starting a new product/feature"
| Stage | Document | Command |
|-------|----------|---------|
| Validate opportunity | Market Research | `/market-research` |
| Build business case | Opportunity Assessment | `/opportunity-assessment` |
| Align stakeholders | Product Brief | `/product-brief` |
| Understand users | User Personas | `/user-personas` |
| Define requirements | PRD | `/prd` |
| Set timeline | Product Roadmap | `/product-roadmap` |

### "I'm preparing for launch"
| Timing | Document | Command |
|--------|----------|---------|
| 3-6 months before | GTM Strategy | `/gtm-strategy` |
| 3-6 months before | Positioning Statement | `/positioning-statement` |
| 2-3 months before | Messaging Framework | `/messaging-framework` |
| 1-2 months before | Sales Enablement Kit | `/sales-enablement-kit` |
| 2-4 weeks before | Launch Checklist | `/launch-checklist` |
| Launch day | Release Notes | `/release-notes` |

## By Role

| Role | Go-To Commands |
|------|---------------|
| **Project Manager** | `/project-charter`, `/status-report`, `/risk-register` |
| **Product Manager** | `/prd`, `/product-roadmap`, `/product-brief` |
| **Product Marketing** | `/positioning-statement`, `/gtm-strategy` |
| **Content Marketer** | `/content-strategy`, `/campaign-brief` |
| **Sales Enablement** | `/sales-enablement-kit`, `/competitor-battlecard` |
| **UX Researcher** | `/user-personas`, `/user-research-report` |

## All Available Documents

### Project Management
| Command | Document | Purpose |
|---------|----------|---------|
| `/project-charter` | Project Charter | Formal authorization |
| `/business-case` | Business Case | Investment justification |
| `/stakeholder-register` | Stakeholder Register | Map stakeholders |
| `/work-breakdown-structure` | WBS | Break down work |
| `/project-schedule` | Project Schedule | Timeline & milestones |
| `/risk-register` | Risk Register | Track risks |
| `/raci-matrix` | RACI Matrix | Clarify roles |
| `/communication-plan` | Communication Plan | Information flow |
| `/status-report` | Status Report | Progress updates |
| `/issue-log` | Issue Log | Track problems |
| `/change-request` | Change Request | Scope changes |
| `/lessons-learned` | Lessons Learned | Document learnings |
| `/project-closure-report` | Closure Report | Final documentation |

### Product Management
| Command | Document | Purpose |
|---------|----------|---------|
| `/product-vision` | Product Vision | 3-5 year direction |
| `/product-strategy` | Product Strategy | How to win |
| `/product-roadmap` | Product Roadmap | Timeline/priorities |
| `/okrs` | OKRs | Measurable goals |
| `/prd` | PRD | Feature specifications |
| `/user-stories` | User Stories | Requirements |
| `/jobs-to-be-done` | JTBD | Customer motivations |
| `/user-personas` | User Personas | User archetypes |
| `/customer-journey-map` | Journey Map | Experience mapping |
| `/market-research` | Market Research | Competitive analysis |
| `/user-research-report` | User Research | Interview findings |
| `/opportunity-assessment` | Opportunity Assessment | Business case |

### Marketing
| Command | Document | Purpose |
|---------|----------|---------|
| `/positioning-statement` | Positioning | Market position |
| `/messaging-framework` | Messaging | Key messages |
| `/value-proposition-canvas` | Value Prop | Pains/gains |
| `/brand-guidelines` | Brand | Voice/visual identity |
| `/content-strategy` | Content Strategy | Pillars/calendar |
| `/campaign-brief` | Campaign Brief | Marketing campaign |
| `/competitor-battlecard` | Battlecard | Sales enablement |
| `/case-study-brief` | Case Study | Customer story |
| `/gtm-strategy` | GTM Strategy | Launch plan |
| `/launch-checklist` | Launch Checklist | Readiness |
| `/product-datasheet` | Datasheet | Feature summary |
| `/sales-enablement-kit` | Sales Kit | Pitch/demo/FAQ |

### Bridge (Cross-Functional)
| Command | Document | Purpose |
|---------|----------|---------|
| `/product-brief` | Product Brief | Feature summary |
| `/release-notes` | Release Notes | Shipped value |
| `/faq-help-center` | FAQ/Help Center | User education |
| `/product-demo-script` | Demo Script | Product demos |

## Document Creation Workflow

All skills follow a consistent workflow:

### Step 1: Setup Directory Structure
Each skill creates a `doc-assist/` folder if it doesn't exist:
```
doc-assist/
├── project-management/
├── product-management/
├── marketing/
└── bridge/
```

### Step 2: Generate Document
Using the appropriate template, the skill creates content based on your input.

### Step 3: Preview for User
The document is displayed for your review.

### Step 4: Confirm and Save
You'll be asked: "Does this document meet your expectations? Should I save it?"

**If confirmed:** Document is saved to the appropriate folder with kebab-case filename.

### Save Locations

| Category | Folder |
|----------|--------|
| Project Management | `doc-assist/project-management/` |
| Product Management | `doc-assist/product-management/` |
| Marketing | `doc-assist/marketing/` |
| Bridge | `doc-assist/bridge/` |

## Quick Help

**Just tell me what you're working on:**
- "I need to write a [specific document]"
- "I'm [doing something], what document should I use?"
- "Help me with [business scenario]"
- "What's the difference between [doc A] and [doc B]?"
