# Doc Assist

> Your intelligent guide for creating Product Management, Marketing, and Project Management documents with Claude Code.

A collection of Claude Code skills that help you create professional documents with structured templates, best practices, and expert guidance.

## Quick Start

### Primary Command

```
/docassist
```

This is your main entry point. Use it when you need help choosing the right document or understanding what document fits your situation.

### Examples

```
/docassist I'm starting a new project, what documents do I need?
/docassist Help me create a project charter
/docassist I need to write a status report
/docassist What's the difference between a PRD and a Product Brief?
```

## Installation

### Option 1: Copy to Claude Code Skills Directory

```bash
# Clone the repository
git clone https://github.com/hashangit/doc-assist.git

# Copy all skills to your Claude Code skills directory
cp -r doc-assist/skills/* ~/.claude/skills/
cp -r doc-assist/commands/* ~/.claude/commands/
```

### Option 2: Use as a Claude Code Plugin

Add to your `~/.claude/settings.json`:

```json
{
  "skills": {
    "paths": ["/path/to/doc-assist/skills"]
  },
  "commands": {
    "paths": ["/path/to/doc-assist/commands"]
  }
}
```

## Document Creation Workflow

Every document goes through a structured 5-stage workflow to ensure quality and fit:

```
┌─────────────────┐    ┌──────────────────┐    ┌─────────────────┐
│  1. DISCOVERY   │───▶│ 2. BRAINSTORMING │───▶│ 3. GENERATION   │
│  /docassist     │    │  /docassist-     │    │  /docassist-    │
│                 │    │  brainstorm      │    │  {document}     │
└─────────────────┘    └──────────────────┘    └─────────────────┘
                                                      │
                                                      ▼
┌─────────────────┐    ┌──────────────────┐    ┌─────────────────┐
│  5. SAVE        │◀───│ 4. HUMANIZATION  │◀───│ Document Ready  │
│  .md file       │    │  (optional)      │    │                 │
└─────────────────┘    └──────────────────┘    └─────────────────┘
```

### Stage 1: Document Discovery

Use `/docassist` to identify the right document for your situation.

- Browse the decision tree to find the right document type
- Understand which documents apply to your scenario
- Get recommendations based on your role or project phase

### Stage 2: Requirements Gathering

**`/docassist-brainstorm` runs automatically** to understand your exact needs:

- **Context** - What's the situation? What's at stake?
- **Purpose** - What outcome do you want?
- **Audience** - Who will read this? What do they care about?
- **Scope** - How detailed? What's in/out?
- **Specifics** - Names, dates, metrics, constraints

You'll be asked one question at a time to refine the requirements.

### Stage 3: Document Generation

After confirming the approach, the specific document skill generates your document using proven templates.

### Stage 4: Humanization (Optional)

You'll be asked: **"Would you like me to humanize this document?"**

If yes, the `document-humanizer` skill:
- Makes the text sound natural and conversational
- Removes AI-generated boilerplate
- Adds human texture and thought flow
- Ensures the document feels like a real person wrote it

### Stage 5: Final Approval & Save

Before saving: **"Does this document meet your expectations? Should I save it?"**

- If yes → Saved to the appropriate folder
- If no → Iterate based on feedback

### Save Locations

| Category | Folder |
|----------|--------|
| Project Management | `doc-assist/project-management/` |
| Product Management | `doc-assist/product-management/` |
| Marketing | `doc-assist/marketing/` |
| Bridge | `doc-assist/bridge/` |

## Available Commands

### Meta & Workflow Skills

| Command | Purpose |
|---------|---------|
| `/docassist` | Main entry point - get help choosing the right document |
| `/docassist-brainstorm` | Requirements gathering - runs automatically before generation |

### Project Management Documents

| Command | Document | Purpose |
|---------|----------|---------|
| `/docassist-project-charter` | Project Charter | Formal authorization, objectives, scope |
| `/docassist-business-case` | Business Case | Investment justification, ROI analysis |
| `/docassist-stakeholder-register` | Stakeholder Register | Map stakeholders, roles, influence |
| `/docassist-work-breakdown-structure` | WBS | Hierarchical decomposition of work |
| `/docassist-project-schedule` | Project Schedule | Timeline, dependencies, milestones |
| `/docassist-risk-register` | Risk Register | Track risks, likelihood, impact, mitigation |
| `/docassist-raci-matrix` | RACI Matrix | Clarify roles (Responsible, Accountable, Consulted, Informed) |
| `/docassist-communication-plan` | Communication Plan | Who needs what info, when, how |
| `/docassist-status-report` | Status Report | Regular progress updates |
| `/docassist-issue-log` | Issue Log | Track problems and resolution status |
| `/docassist-change-request` | Change Request | Formal requests to modify scope/schedule/budget |
| `/docassist-lessons-learned` | Lessons Learned | What went well, what didn't, recommendations |
| `/docassist-project-closure-report` | Closure Report | Final status, deliverables, handoff |

### Product Strategy Documents

| Command | Document | Purpose |
|---------|----------|---------|
| `/docassist-product-vision` | Product Vision | Long-term direction (3-5 years) |
| `/docassist-product-strategy` | Product Strategy | How to achieve vision, competitive differentiation |
| `/docassist-product-roadmap` | Product Roadmap | Timeline of features/releases, priorities |
| `/docassist-okrs` | OKRs | Measurable goals and success metrics |

### Product Discovery Documents

| Command | Document | Purpose |
|---------|----------|---------|
| `/docassist-prd` | PRD | Detailed feature specifications |
| `/docassist-user-stories` | User Stories | Requirements in "As a... I want... So that..." format |
| `/docassist-jobs-to-be-done` | JTBD | Customer motivations and desired outcomes |
| `/docassist-user-personas` | User Personas | Archetypes of target users |
| `/docassist-customer-journey-map` | Journey Map | End-to-end experience across touchpoints |

### Product Research Documents

| Command | Document | Purpose |
|---------|----------|---------|
| `/docassist-market-research` | Market Research | Competitive analysis, market size, trends |
| `/docassist-user-research-report` | User Research | Interview findings, survey results, insights |
| `/docassist-opportunity-assessment` | Opportunity Assessment | Business case for pursuing a feature/product |

### Marketing Positioning Documents

| Command | Document | Purpose |
|---------|----------|---------|
| `/docassist-positioning-statement` | Positioning Statement | Market position, key benefits |
| `/docassist-messaging-framework` | Messaging Framework | Key messages by audience |
| `/docassist-value-proposition-canvas` | Value Prop Canvas | Customer pains/gains mapped to features |
| `/docassist-brand-guidelines` | Brand Guidelines | Visual identity, voice, tone |

### Marketing Content Documents

| Command | Document | Purpose |
|---------|----------|---------|
| `/docassist-content-strategy` | Content Strategy | Content pillars, channels, editorial calendar |
| `/docassist-campaign-brief` | Campaign Brief | Goals, audience, channels, budget, timeline |
| `/docassist-competitor-battlecard` | Competitor Battlecard | Feature comparisons, objection handling |
| `/docassist-case-study-brief` | Case Study Brief | Customer success story structure |

### Marketing Launch Documents

| Command | Document | Purpose |
|---------|----------|---------|
| `/docassist-gtm-strategy` | GTM Strategy | Launch plan, pricing, channels |
| `/docassist-launch-checklist` | Launch Checklist | Cross-functional readiness checklist |
| `/docassist-product-datasheet` | Product Datasheet | Feature summary, specs, use cases |
| `/docassist-sales-enablement-kit` | Sales Enablement Kit | Pitch decks, objection handling, demo scripts |

### Bridge Documents (Cross-Functional)

| Command | Document | PM Use | Marketing Use |
|---------|----------|--------|---------------|
| `/docassist-product-brief` | Product Brief | Feature summary for stakeholders | Messaging foundation |
| `/docassist-release-notes` | Release Notes | Communicate shipped value | Market new features |
| `/docassist-faq-help-center` | FAQ/Help Center | User education | SEO content |
| `/docassist-product-demo-script` | Demo Script | Stakeholder alignment | Sales/marketing demos |

## Common Workflows

### Starting a New Project

```
1. /docassist-project-charter - Get authorization
2. /docassist-business-case - Justify investment
3. /docassist-stakeholder-register - Map people
4. /docassist-work-breakdown-structure - Break down work
5. /docassist-project-schedule - Create timeline
6. /docassist-risk-register - Identify risks
7. /docassist-raci-matrix - Clarify roles
```

### Running a Project

```
Weekly:
- /docassist-status-report - Progress updates
- /docassist-issue-log - Track problems

As Needed:
- /docassist-change-request - Modify scope
- /docassist-risk-register - Update risks
```

### Closing a Project

```
1. /docassist-lessons-learned - Document learnings
2. /docassist-project-closure-report - Final documentation
```

### New Feature Launch

```
1. /docassist-product-brief - Align stakeholders
2. /docassist-prd - Define requirements
3. /docassist-positioning-statement - Define market position
4. /docassist-gtm-strategy - Launch plan
5. /docassist-launch-checklist - Readiness check
6. /docassist-release-notes - Announce features
```

### Sales Enablement

```
1. /docassist-product-datasheet - Feature summary
2. /docassist-competitor-battlecard - Competitive intel
3. /docassist-product-demo-script - Demo guidance
4. /docassist-sales-enablement-kit - Full sales kit
```

## By Role

### Project Manager

**Most Used:**
- `/docassist-project-charter` - Authorization
- `/docassist-status-report` - Progress updates
- `/docassist-risk-register` - Risk tracking
- `/docassist-issue-log` - Problem tracking

### Product Manager

**Most Used:**
- `/docassist-prd` - Feature specifications
- `/docassist-product-roadmap` - Timeline & priorities
- `/docassist-product-brief` - Feature summary
- `/docassist-user-stories` - Requirements

### Product Marketing Manager

**Most Used:**
- `/docassist-positioning-statement` - Market position
- `/docassist-gtm-strategy` - Launch plan
- `/docassist-messaging-framework` - Key messages
- `/docassist-sales-enablement-kit` - Sales support

### Content Marketer

**Most Used:**
- `/docassist-content-strategy` - Content planning
- `/docassist-campaign-brief` - Campaign planning
- `/docassist-case-study-brief` - Customer stories

### Sales Enablement

**Most Used:**
- `/docassist-sales-enablement-kit` - Full kit
- `/docassist-product-datasheet` - Feature summary
- `/docassist-competitor-battlecard` - Competitive intel
- `/docassist-product-demo-script` - Demo guidance

### UX Researcher

**Most Used:**
- `/docassist-user-personas` - User archetypes
- `/docassist-customer-journey-map` - Experience mapping
- `/docassist-user-research-report` - Research findings

## Tips

1. **Start with `/docassist`** when you're unsure which document you need
2. **Answer brainstorming questions thoughtfully** - they ensure the document fits your exact needs
3. **Use humanization** for stakeholder-facing documents to make them feel more personal
4. **Chain documents** - many workflows use multiple documents in sequence
5. **Be specific** about your situation for better recommendations

## File Structure

```
doc-assist/
├── README.md
├── commands/
│   └── docassist.md              # Claude command definition
└── skills/
    ├── docassist/                # Meta skill (entry point)
    ├── docassist-brainstorm/     # Requirements gathering
    │
    ├── project-management/
    │   ├── docassist-project-charter/
    │   ├── docassist-business-case/
    │   ├── docassist-stakeholder-register/
    │   ├── docassist-work-breakdown-structure/
    │   ├── docassist-project-schedule/
    │   ├── docassist-risk-register/
    │   ├── docassist-raci-matrix/
    │   ├── docassist-communication-plan/
    │   ├── docassist-status-report/
    │   ├── docassist-issue-log/
    │   ├── docassist-change-request/
    │   ├── docassist-lessons-learned/
    │   └── docassist-project-closure-report/
    │
    ├── product-strategy/
    │   ├── docassist-product-vision/
    │   ├── docassist-product-strategy/
    │   ├── docassist-product-roadmap/
    │   └── docassist-okrs/
    │
    ├── product-discovery/
    │   ├── docassist-prd/
    │   ├── docassist-user-stories/
    │   ├── docassist-jobs-to-be-done/
    │   ├── docassist-user-personas/
    │   └── docassist-customer-journey-map/
    │
    ├── product-research/
    │   ├── docassist-market-research/
    │   ├── docassist-user-research-report/
    │   └── docassist-opportunity-assessment/
    │
    ├── marketing-positioning/
    │   ├── docassist-positioning-statement/
    │   ├── docassist-messaging-framework/
    │   ├── docassist-value-proposition-canvas/
    │   └── docassist-brand-guidelines/
    │
    ├── marketing-content/
    │   ├── docassist-content-strategy/
    │   ├── docassist-campaign-brief/
    │   ├── docassist-competitor-battlecard/
    │   └── docassist-case-study-brief/
    │
    ├── marketing-launch/
    │   ├── docassist-gtm-strategy/
    │   ├── docassist-launch-checklist/
    │   ├── docassist-product-datasheet/
    │   └── docassist-sales-enablement-kit/
    │
    └── bridge/
        ├── docassist-product-brief/
        ├── docassist-release-notes/
        ├── docassist-faq-help-center/
        └── docassist-product-demo-script/
```

## Contributing

Contributions are welcome! To add or improve documents:

1. Fork the repository
2. Make your changes to the relevant SKILL.md
3. Submit a pull request

## License

MIT
