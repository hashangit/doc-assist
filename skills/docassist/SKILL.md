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

## Complete Document Creation Flow

```dot
digraph doc_flow {
    "User needs a document" [shape=doublecircle];
    "Invoke /docassist" [shape=box];
    "Know exact document type?" [shape=diamond];
    "Use decision tree" [shape=box];
    "Document identified" [shape=box];
    "Invoke /docassist-brainstorm" [shape=box];
    "Gather requirements" [shape=box];
    "Confirm approach" [shape=box];
    "User approves approach?" [shape=diamond];
    "Generate document" [shape=box];
    "Show document" [shape=box];
    "Humanize?" [shape=diamond];
    "Apply humanizer skill" [shape=box];
    "Final approval?" [shape=diamond];
    "Save to .md file" [shape=doublecircle];

    "User needs a document" -> "Invoke /docassist";
    "Invoke /docassist" -> "Know exact document type?";
    "Know exact document type?" -> "Document identified" [label="yes"];
    "Know exact document type?" -> "Use decision tree" [label="no"];
    "Use decision tree" -> "Document identified";
    "Document identified" -> "Invoke /docassist-brainstorm";
    "Invoke /docassist-brainstorm" -> "Gather requirements";
    "Gather requirements" -> "Confirm approach";
    "Confirm approach" -> "User approves approach?";
    "User approves approach?" -> "Gather requirements" [label="no, revise"];
    "User approves approach?" -> "Generate document" [label="yes"];
    "Generate document" -> "Show document";
    "Show document" -> "Humanize?";
    "Humanize?" -> "Apply humanizer skill" [label="yes"];
    "Humanize?" -> "Final approval?" [label="no"];
    "Apply humanizer skill" -> "Final approval?";
    "Final approval?" -> "Generate document" [label="no, revise"];
    "Final approval?" -> "Save to .md file" [label="yes"];
}
```

## Workflow Stages

### Stage 1: Document Discovery

Use the decision tree below to identify the right document, or confirm if user already knows.

### Stage 2: Requirements Gathering

**ALWAYS invoke /docassist-brainstorm after identifying the document.**

The brainstorming skill will:
- Understand context and situation
- Identify purpose and desired outcomes
- Define audience and their concerns
- Clarify scope and depth
- Gather specific details (names, dates, metrics)
- Confirm approach before generation

<HARD-GATE>
Do NOT generate any document until /docassist-brainstorm completes and user approves the approach.
</HARD-GATE>

### Stage 3: Document Generation

After approval, invoke the specific document skill to generate content.

### Stage 4: Humanization Offer

After showing the generated document, always ask:

> "Would you like me to humanize this document? I can make it sound more natural, less AI-generated, and more like something a real person wrote."

**If yes:** Invoke `document-humanizer` skill to polish.

### Stage 5: Final Approval & Save

Before saving, always ask:

> "Does this document meet your expectations? Should I save it?"

**If confirmed:** Save to appropriate folder with kebab-case filename.

**If changes needed:** Iterate based on feedback.

## Red Flags

These thoughts mean STOP—you're rationalizing:

| Thought | Reality |
|---------|---------|
| "I'll just write a quick status update" | Status Reports have structure. Use `/docassist-status-report`. |
| "This PRD is simple, I don't need the skill" | Simple docs become complex. Use `/docassist-prd`. |
| "I know what a project charter looks like" | Templates evolve. Use `/docassist-project-charter`. |
| "Let me just draft something first" | Draft without structure = rework. Use the skill. |
| "The user didn't specify a document type" | That's exactly when to use `/docassist`. |
| "I'll figure out the format as I go" | Skills provide proven formats. Use them. |
| "This is just a quick meeting summary" | That might be a Status Report or Lessons Learned. Check. |
| "I remember the template from before" | Templates get updated. Use the current skill. |
| "The user gave me all the info" | Info ≠ understanding. Use `/docassist-brainstorm`. |
| "I can skip brainstorming for simple docs" | Simple requests hide complex needs. Always discover. |

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
- User invokes the skill directly: "/docassist-risk-register"

**Note:** Even with direct invocation, /docassist-brainstorm must run for requirements gathering.

## Document Priority

When multiple documents could apply, use this order:

1. **Foundational documents first** (charters, strategies) - these set direction
2. **Planning documents second** (roadmaps, WBS, schedules) - these define scope
3. **Execution documents third** (status reports, issue logs) - these track progress
4. **Closure documents last** (lessons learned, closure reports) - these capture learnings

"I need to launch a feature" → Start with `/docassist-product-brief`, then `/docassist-prd`, then `/docassist-gtm-strategy`.

## Quick Decision Tree

```
What are you trying to do?

├── Manage a project?
│   └──→ Project Management Documents
│       ├── /docassist-project-charter - Authorization document
│       ├── /docassist-business-case - Investment justification
│       ├── /docassist-stakeholder-register - Map stakeholders
│       ├── /docassist-work-breakdown-structure - Break down work
│       ├── /docassist-project-schedule - Timeline & milestones
│       ├── /docassist-risk-register - Track risks
│       ├── /docassist-raci-matrix - Clarify roles
│       ├── /docassist-communication-plan - Information flow
│       ├── /docassist-status-report - Progress updates
│       ├── /docassist-issue-log - Track problems
│       ├── /docassist-change-request - Scope changes
│       ├── /docassist-lessons-learned - Document learnings
│       └── /docassist-project-closure-report - Final documentation
│
├── Define product direction?
│   └──→ Product Strategy Documents
│       ├── /docassist-product-vision - 3-5 year direction
│       ├── /docassist-product-strategy - How to win
│       ├── /docassist-product-roadmap - Timeline/priorities
│       └── /docassist-okrs - Measurable goals
│
├── Specify what to build?
│   └──→ Product Discovery Documents
│       ├── /docassist-prd - Feature specifications
│       ├── /docassist-user-stories - Requirements
│       ├── /docassist-jobs-to-be-done - Customer motivations
│       ├── /docassist-user-personas - User archetypes
│       └── /docassist-customer-journey-map - Experience mapping
│
├── Research and validate?
│   └──→ Product Research Documents
│       ├── /docassist-market-research - Competitive/size/trends
│       ├── /docassist-user-research-report - Interview/survey findings
│       └── /docassist-opportunity-assessment - Business case
│
├── Define market position?
│   └──→ Marketing Positioning Documents
│       ├── /docassist-positioning-statement - Market position
│       ├── /docassist-messaging-framework - Key messages
│       ├── /docassist-value-proposition-canvas - Pains/gains
│       └── /docassist-brand-guidelines - Voice/visual identity
│
├── Plan content or campaigns?
│   └──→ Marketing Content Documents
│       ├── /docassist-content-strategy - Pillars/calendar
│       ├── /docassist-campaign-brief - Marketing campaign
│       ├── /docassist-competitor-battlecard - Sales enablement
│       └── /docassist-case-study-brief - Customer story
│
├── Launch product?
│   └──→ Marketing Launch Documents
│       ├── /docassist-gtm-strategy - Launch plan
│       ├── /docassist-launch-checklist - Readiness
│       ├── /docassist-product-datasheet - Feature summary
│       └── /docassist-sales-enablement-kit - Pitch/demo/FAQ
│
└── Create cross-functional docs?
    └──→ Bridge Documents
        ├── /docassist-product-brief - Feature summary
        ├── /docassist-release-notes - Shipped value
        ├── /docassist-faq-help-center - User education
        └── /docassist-product-demo-script - Product demos
```

## By Scenario

### "I'm starting a new project"
| Phase | Document | Command |
|-------|----------|---------|
| Get authorization | Project Charter | `/docassist-project-charter` |
| Justify investment | Business Case | `/docassist-business-case` |
| Map stakeholders | Stakeholder Register | `/docassist-stakeholder-register` |
| Break down work | WBS | `/docassist-work-breakdown-structure` |
| Create timeline | Project Schedule | `/docassist-project-schedule` |
| Identify risks | Risk Register | `/docassist-risk-register` |
| Clarify roles | RACI Matrix | `/docassist-raci-matrix` |

### "I'm running a project"
| Need | Document | Command |
|------|----------|---------|
| Report progress | Status Report | `/docassist-status-report` |
| Track problems | Issue Log | `/docassist-issue-log` |
| Request changes | Change Request | `/docassist-change-request` |
| Plan communications | Communication Plan | `/docassist-communication-plan` |

### "I'm closing a project"
| Need | Document | Command |
|------|----------|---------|
| Document learnings | Lessons Learned | `/docassist-lessons-learned` |
| Final report | Closure Report | `/docassist-project-closure-report` |

### "I'm starting a new product/feature"
| Stage | Document | Command |
|-------|----------|---------|
| Validate opportunity | Market Research | `/docassist-market-research` |
| Build business case | Opportunity Assessment | `/docassist-opportunity-assessment` |
| Align stakeholders | Product Brief | `/docassist-product-brief` |
| Understand users | User Personas | `/docassist-user-personas` |
| Define requirements | PRD | `/docassist-prd` |
| Set timeline | Product Roadmap | `/docassist-product-roadmap` |

### "I'm preparing for launch"
| Timing | Document | Command |
|--------|----------|---------|
| 3-6 months before | GTM Strategy | `/docassist-gtm-strategy` |
| 3-6 months before | Positioning Statement | `/docassist-positioning-statement` |
| 2-3 months before | Messaging Framework | `/docassist-messaging-framework` |
| 1-2 months before | Sales Enablement Kit | `/docassist-sales-enablement-kit` |
| 2-4 weeks before | Launch Checklist | `/docassist-launch-checklist` |
| Launch day | Release Notes | `/docassist-release-notes` |

## By Role

| Role | Go-To Commands |
|------|---------------|
| **Project Manager** | `/docassist-project-charter`, `/docassist-status-report`, `/docassist-risk-register` |
| **Product Manager** | `/docassist-prd`, `/docassist-product-roadmap`, `/docassist-product-brief` |
| **Product Marketing** | `/docassist-positioning-statement`, `/docassist-gtm-strategy` |
| **Content Marketer** | `/docassist-content-strategy`, `/docassist-campaign-brief` |
| **Sales Enablement** | `/docassist-sales-enablement-kit`, `/docassist-competitor-battlecard` |
| **UX Researcher** | `/docassist-user-personas`, `/docassist-user-research-report` |

## All Available Documents

### Project Management
| Command | Document | Purpose |
|---------|----------|---------|
| `/docassist-project-charter` | Project Charter | Formal authorization |
| `/docassist-business-case` | Business Case | Investment justification |
| `/docassist-stakeholder-register` | Stakeholder Register | Map stakeholders |
| `/docassist-work-breakdown-structure` | WBS | Break down work |
| `/docassist-project-schedule` | Project Schedule | Timeline & milestones |
| `/docassist-risk-register` | Risk Register | Track risks |
| `/docassist-raci-matrix` | RACI Matrix | Clarify roles |
| `/docassist-communication-plan` | Communication Plan | Information flow |
| `/docassist-status-report` | Status Report | Progress updates |
| `/docassist-issue-log` | Issue Log | Track problems |
| `/docassist-change-request` | Change Request | Scope changes |
| `/docassist-lessons-learned` | Lessons Learned | Document learnings |
| `/docassist-project-closure-report` | Closure Report | Final documentation |

### Product Strategy
| Command | Document | Purpose |
|---------|----------|---------|
| `/docassist-product-vision` | Product Vision | 3-5 year direction |
| `/docassist-product-strategy` | Product Strategy | How to win |
| `/docassist-product-roadmap` | Product Roadmap | Timeline/priorities |
| `/docassist-okrs` | OKRs | Measurable goals |

### Product Discovery
| Command | Document | Purpose |
|---------|----------|---------|
| `/docassist-prd` | PRD | Feature specifications |
| `/docassist-user-stories` | User Stories | Requirements |
| `/docassist-jobs-to-be-done` | JTBD | Customer motivations |
| `/docassist-user-personas` | User Personas | User archetypes |
| `/docassist-customer-journey-map` | Journey Map | Experience mapping |

### Product Research
| Command | Document | Purpose |
|---------|----------|---------|
| `/docassist-market-research` | Market Research | Competitive analysis |
| `/docassist-user-research-report` | User Research | Interview findings |
| `/docassist-opportunity-assessment` | Opportunity Assessment | Business case |

### Marketing Positioning
| Command | Document | Purpose |
|---------|----------|---------|
| `/docassist-positioning-statement` | Positioning | Market position |
| `/docassist-messaging-framework` | Messaging | Key messages |
| `/docassist-value-proposition-canvas` | Value Prop | Pains/gains |
| `/docassist-brand-guidelines` | Brand | Voice/visual identity |

### Marketing Content
| Command | Document | Purpose |
|---------|----------|---------|
| `/docassist-content-strategy` | Content Strategy | Pillars/calendar |
| `/docassist-campaign-brief` | Campaign Brief | Marketing campaign |
| `/docassist-competitor-battlecard` | Battlecard | Sales enablement |
| `/docassist-case-study-brief` | Case Study | Customer story |

### Marketing Launch
| Command | Document | Purpose |
|---------|----------|---------|
| `/docassist-gtm-strategy` | GTM Strategy | Launch plan |
| `/docassist-launch-checklist` | Launch Checklist | Readiness |
| `/docassist-product-datasheet` | Datasheet | Feature summary |
| `/docassist-sales-enablement-kit` | Sales Kit | Pitch/demo/FAQ |

### Bridge (Cross-Functional)
| Command | Document | Purpose |
|---------|----------|---------|
| `/docassist-product-brief` | Product Brief | Feature summary |
| `/docassist-release-notes` | Release Notes | Shipped value |
| `/docassist-faq-help-center` | FAQ/Help Center | User education |
| `/docassist-product-demo-script` | Demo Script | Product demos |

## Save Locations

| Category | Folder |
|----------|--------|
| Project Management | `doc-assist/project-management/` |
| Product Management | `doc-assist/product-management/` |
| Marketing | `doc-assist/marketing/` |
| Bridge | `doc-assist/bridge/` |

## Examples

### Correct Usage

```
User: I need a status report for my project
You: I'll help you create a status report. Let me first understand your specific needs.
[Invokes /docassist-brainstorm to gather requirements]
[After approval, invokes /docassist-status-report to generate]
[Shows document]
Would you like me to humanize this document?
[If yes, applies humanizer]
Does this meet your expectations? Should I save it?
[Saves to doc-assist/project-management/status-report.md]
```

```
User: I'm not sure what document I need for launching a feature
You: Let me help you find the right document.
[Uses decision tree to identify needed documents]
Based on your launch phase, you'll want to start with a GTM Strategy.
[Invokes /docassist-brainstorm for requirements gathering]
[Continues with full workflow]
```

### Incorrect Usage (Don't Do This)

```
User: I need a status report
You: Here's a status report template...
❌ WRONG - Skipped /docassist-brainstorm requirements gathering
```

```
User: Create a PRD for my new feature
You: [Generates PRD immediately]
❌ WRONG - Must gather requirements first via /docassist-brainstorm
```

```
User: This looks good, save it
You: [Saves without offering humanization]
❌ WRONG - Must offer humanization before final save
```
