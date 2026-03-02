---
name: docassist
description: Your intelligent guide for creating Product Management, Marketing, and Project Management documents. Use as the primary entry point via /docassist to get help choosing the right document. Triggers on "which document", "what document should I use", "help me choose document", "document for [scenario]", or when unsure which document skill to use.
---

# Doc Assist

Your intelligent guide for choosing and creating the right business document.

<EXTREMELY-IMPORTANT>
If you think there is even a 1% chance a document skill might apply to what you're doing, you ABSOLUTELY MUST invoke /docassist first.

IF A DOCUMENT NEEDS TO BE CREATED, YOU DO NOT HAVE A CHOICE. USE THE RIGHT SKILL.

This is not negotiable. This is not optional. You cannot rationalize your way out of this.
</EXTREMELY-IMPORTANT>

## The Rule

**Invoke /docassist BEFORE creating any business document.** Even a 1% chance you need a document means you should check. If you're unsure which document, use /docassist to find out.

```dot
digraph doc_flow {
    "User mentions document need" [shape=doublecircle];
    "Know exactly which document?" [shape=diamond];
    "Invoke /docassist" [shape=box];
    "Invoke specific document skill" [shape=box];
    "Announce: 'Using [skill] to create [document]'" [shape=box];
    "Follow document workflow" [shape=box];
    "Document created" [shape=doublecircle];

    "User mentions document need" -> "Know exactly which document?";
    "Know exactly which document?" -> "Invoke specific document skill" [label="yes"];
    "Know exactly which document?" -> "Invoke /docassist" [label="no or unsure"];
    "Invoke /docassist" -> "Invoke specific document skill";
    "Invoke specific document skill" -> "Announce: 'Using [skill] to create [document]'";
    "Announce: 'Using [skill] to create [document]'" -> "Follow document workflow";
    "Follow document workflow" -> "Document created";
}
```

## Red Flags

These thoughts mean STOP—you're rationalizing:

| Thought | Reality |
|---------|---------|
| "I'll just write a quick status update" | Status Reports have structure. Use `/status-report`. |
| "This PRD is simple, I don't need the skill" | Simple docs become complex. Use `/prd`. |
| "I know what a project charter looks like" | Templates evolve. Use `/project-charter`. |
| "Let me just draft something first" | Draft without structure = rework. Use the skill. |
| "The user didn't specify a document type" | That's exactly when to use `/docassist`. |
| "I'll figure out the format as I go" | Skills provide proven formats. Use them. |
| "This is just a quick meeting summary" | That might be a Status Report or Lessons Learned. Check. |
| "I remember the template from before" | Templates get updated. Use the current skill. |

## When to Use /docassist vs Direct Skill Invocation

### Use /docassist First When:
- User asks "what document should I create?"
- User describes a situation but doesn't name a document
- You're unsure which document fits the need
- Multiple documents could apply
- User says "help me document this"
- User asks about document differences ("PRD vs Product Brief?")

### Go Directly to Specific Skill When:
- User explicitly names the document: "Create a PRD for..."
- Context makes it 100% clear which document is needed
- User invokes the skill directly: "/risk-register"

## Document Priority

When multiple documents could apply, use this order:

1. **Foundational documents first** (charters, strategies) - these set direction
2. **Planning documents second** (roadmaps, WBS, schedules) - these define scope
3. **Execution documents third** (status reports, issue logs) - these track progress
4. **Closure documents last** (lessons learned, closure reports) - these capture learnings

"I need to launch a feature" → Start with `/product-brief`, then `/prd`, then `/gtm-strategy`.

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

All document skills follow this workflow. Do not skip steps.

### Step 1: Setup Directory Structure
Create the `doc-assist/` folder structure if it doesn't exist:
```
doc-assist/
├── project-management/
├── product-management/
├── marketing/
└── bridge/
```

### Step 2: Generate Document
Using the skill's template, create content based on user input and context.

### Step 3: Preview for User
Display the complete document in a code block for review.

### Step 4: Confirm and Save
Ask: **"Does this document meet your expectations? Should I save it?"**

**If confirmed:** Save to the appropriate folder with kebab-case filename.

**If changes needed:** Iterate based on feedback, then repeat Step 3.

### Save Locations

| Category | Folder |
|----------|--------|
| Project Management | `doc-assist/project-management/` |
| Product Management | `doc-assist/product-management/` |
| Marketing | `doc-assist/marketing/` |
| Bridge | `doc-assist/bridge/` |

## Examples

### Correct Usage

```
User: I need to track risks for my project
You: I'll use /risk-register to create a Risk Register for tracking project risks.
[Invokes skill, follows workflow]
```

```
User: I'm not sure what document I need for launching a feature
You: Let me help you find the right document with /docassist.
[Uses decision tree to identify needed documents]
Based on your launch phase, you need: /gtm-strategy, /positioning-statement, /launch-checklist
```

### Incorrect Usage (Don't Do This)

```
User: I need a status report
You: Here's a quick status report template I'll write up...
❌ WRONG - Should invoke /status-report skill
```

```
User: Help me document this project
You: What kind of documentation do you need?
❌ WRONG - Should invoke /docassist to guide the discovery
```
