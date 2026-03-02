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
cp -r doc-assist/* ~/.claude/skills/
```

### Option 2: Use as a Claude Code Plugin

Add to your `~/.claude/settings.json`:

```json
{
  "skills": {
    "paths": ["/path/to/doc-assist"]
  }
}
```

## Document Creation Workflow

Every document goes through a structured 5-stage workflow to ensure quality and fit:

```
┌─────────────────┐    ┌──────────────────┐    ┌─────────────────┐
│  1. DISCOVERY   │───▶│ 2. BRAINSTORMING │───▶│ 3. GENERATION   │
│  /docassist     │    │  /doc-brainstorm │    │  /specific-skill│
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

**`/doc-brainstorm` runs automatically** to understand your exact needs:

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
| `/doc-brainstorm` | Requirements gathering - runs automatically before generation |

### Project Management Documents

| Command | Document | Purpose |
|---------|----------|---------|
| `/project-charter` | Project Charter | Formal authorization, objectives, scope |
| `/business-case` | Business Case | Investment justification, ROI analysis |
| `/stakeholder-register` | Stakeholder Register | Map stakeholders, roles, influence |
| `/work-breakdown-structure` | WBS | Hierarchical decomposition of work |
| `/project-schedule` | Project Schedule | Timeline, dependencies, milestones |
| `/risk-register` | Risk Register | Track risks, likelihood, impact, mitigation |
| `/raci-matrix` | RACI Matrix | Clarify roles (Responsible, Accountable, Consulted, Informed) |
| `/communication-plan` | Communication Plan | Who needs what info, when, how |
| `/status-report` | Status Report | Regular progress updates |
| `/issue-log` | Issue Log | Track problems and resolution status |
| `/change-request` | Change Request | Formal requests to modify scope/schedule/budget |
| `/lessons-learned` | Lessons Learned | What went well, what didn't, recommendations |
| `/project-closure-report` | Closure Report | Final status, deliverables, handoff |

### Product Strategy Documents

| Command | Document | Purpose |
|---------|----------|---------|
| `/product-vision` | Product Vision | Long-term direction (3-5 years) |
| `/product-strategy` | Product Strategy | How to achieve vision, competitive differentiation |
| `/product-roadmap` | Product Roadmap | Timeline of features/releases, priorities |
| `/okrs` | OKRs | Measurable goals and success metrics |

### Product Discovery Documents

| Command | Document | Purpose |
|---------|----------|---------|
| `/prd` | PRD | Detailed feature specifications |
| `/user-stories` | User Stories | Requirements in "As a... I want... So that..." format |
| `/jobs-to-be-done` | JTBD | Customer motivations and desired outcomes |
| `/user-personas` | User Personas | Archetypes of target users |
| `/customer-journey-map` | Journey Map | End-to-end experience across touchpoints |

### Product Research Documents

| Command | Document | Purpose |
|---------|----------|---------|
| `/market-research` | Market Research | Competitive analysis, market size, trends |
| `/user-research-report` | User Research | Interview findings, survey results, insights |
| `/opportunity-assessment` | Opportunity Assessment | Business case for pursuing a feature/product |

### Marketing Positioning Documents

| Command | Document | Purpose |
|---------|----------|---------|
| `/positioning-statement` | Positioning Statement | Market position, key benefits |
| `/messaging-framework` | Messaging Framework | Key messages by audience |
| `/value-proposition-canvas` | Value Prop Canvas | Customer pains/gains mapped to features |
| `/brand-guidelines` | Brand Guidelines | Visual identity, voice, tone |

### Marketing Content Documents

| Command | Document | Purpose |
|---------|----------|---------|
| `/content-strategy` | Content Strategy | Content pillars, channels, editorial calendar |
| `/campaign-brief` | Campaign Brief | Goals, audience, channels, budget, timeline |
| `/competitor-battlecard` | Competitor Battlecard | Feature comparisons, objection handling |
| `/case-study-brief` | Case Study Brief | Customer success story structure |

### Marketing Launch Documents

| Command | Document | Purpose |
|---------|----------|---------|
| `/gtm-strategy` | GTM Strategy | Launch plan, pricing, channels |
| `/launch-checklist` | Launch Checklist | Cross-functional readiness checklist |
| `/product-datasheet` | Product Datasheet | Feature summary, specs, use cases |
| `/sales-enablement-kit` | Sales Enablement Kit | Pitch decks, objection handling, demo scripts |

### Bridge Documents (Cross-Functional)

| Command | Document | PM Use | Marketing Use |
|---------|----------|--------|---------------|
| `/product-brief` | Product Brief | Feature summary for stakeholders | Messaging foundation |
| `/release-notes` | Release Notes | Communicate shipped value | Market new features |
| `/faq-help-center` | FAQ/Help Center | User education | SEO content |
| `/product-demo-script` | Demo Script | Stakeholder alignment | Sales/marketing demos |

## Common Workflows

### Starting a New Project

```
1. /project-charter - Get authorization
2. /business-case - Justify investment
3. /stakeholder-register - Map people
4. /work-breakdown-structure - Break down work
5. /project-schedule - Create timeline
6. /risk-register - Identify risks
7. /raci-matrix - Clarify roles
```

### Running a Project

```
Weekly:
- /status-report - Progress updates
- /issue-log - Track problems

As Needed:
- /change-request - Modify scope
- /risk-register - Update risks
```

### Closing a Project

```
1. /lessons-learned - Document learnings
2. /project-closure-report - Final documentation
```

### New Feature Launch

```
1. /product-brief - Align stakeholders
2. /prd - Define requirements
3. /positioning-statement - Define market position
4. /gtm-strategy - Launch plan
5. /launch-checklist - Readiness check
6. /release-notes - Announce features
```

### Sales Enablement

```
1. /product-datasheet - Feature summary
2. /competitor-battlecard - Competitive intel
3. /product-demo-script - Demo guidance
4. /sales-enablement-kit - Full sales kit
```

## By Role

### Project Manager

**Most Used:**
- `/project-charter` - Authorization
- `/status-report` - Progress updates
- `/risk-register` - Risk tracking
- `/issue-log` - Problem tracking

### Product Manager

**Most Used:**
- `/prd` - Feature specifications
- `/product-roadmap` - Timeline & priorities
- `/product-brief` - Feature summary
- `/user-stories` - Requirements

### Product Marketing Manager

**Most Used:**
- `/positioning-statement` - Market position
- `/gtm-strategy` - Launch plan
- `/messaging-framework` - Key messages
- `/sales-enablement-kit` - Sales support

### Content Marketer

**Most Used:**
- `/content-strategy` - Content planning
- `/campaign-brief` - Campaign planning
- `/case-study-brief` - Customer stories

### Sales Enablement

**Most Used:**
- `/sales-enablement-kit` - Full kit
- `/product-datasheet` - Feature summary
- `/competitor-battlecard` - Competitive intel
- `/product-demo-script` - Demo guidance

### UX Researcher

**Most Used:**
- `/user-personas` - User archetypes
- `/customer-journey-map` - Experience mapping
- `/user-research-report` - Research findings

## Usage Examples

### Complete Document Creation Flow

```
You: /docassist I need a status report for my project

Claude: I'll help you create a status report. Let me first understand your specific needs.

[Invokes /doc-brainstorm]

Claude: What's the project name and current phase?
You: Website redesign, we're in development phase

Claude: Who's the primary audience for this status report?
      a) Executive leadership (need high-level, business impact)
      b) Engineering team (need technical details)
      c) Mixed stakeholders (need balanced approach)
You: c) Mixed stakeholders

Claude: What reporting period does this cover?
You: This week (March 1-7)

Claude: Based on our conversation:
- Document: Status Report
- Project: Website redesign, development phase
- Audience: Mixed stakeholders
- Period: March 1-7
I'll create a balanced status report. Does this sound right?
You: Yes

[Generates document using /status-report]

Claude: [Shows complete status report]

Would you like me to humanize this document? I can make it sound more natural.
You: Yes

[Applies humanizer]

Claude: [Shows humanized version]

Does this meet your expectations? Should I save it?
You: Yes, save it

Claude: Saved to doc-assist/project-management/status-report.md
```

### Quick Document Request

```
You: /prd Create a PRD for a new user dashboard feature

Claude: I'll help you create a PRD. First, let me understand your requirements.

[Invokes /doc-brainstorm and asks targeted questions]

[After confirmation, generates PRD]

[Offers humanization]

[Saves to doc-assist/product-management/prd.md]
```

## Tips

1. **Start with `/docassist`** when you're unsure which document you need
2. **Answer brainstorming questions thoughtfully** - they ensure the document fits your exact needs
3. **Use humanization** for stakeholder-facing documents to make them feel more personal
4. **Chain documents** - many workflows use multiple documents in sequence
5. **Be specific** about your situation for better recommendations

## File Structure

```
doc-assist/
├── README.md                      # This guide
├── docassist/                     # Meta-skill (main entry point)
│   └── SKILL.md
├── doc-brainstorm/                # Requirements gathering skill
│   └── SKILL.md
│
├── Project Management Skills
│   ├── project-charter/SKILL.md
│   ├── business-case/SKILL.md
│   ├── stakeholder-register/SKILL.md
│   ├── work-breakdown-structure/SKILL.md
│   ├── project-schedule/SKILL.md
│   ├── risk-register/SKILL.md
│   ├── raci-matrix/SKILL.md
│   ├── communication-plan/SKILL.md
│   ├── status-report/SKILL.md
│   ├── issue-log/SKILL.md
│   ├── change-request/SKILL.md
│   ├── lessons-learned/SKILL.md
│   └── project-closure-report/SKILL.md
│
├── Product Strategy Skills
│   ├── product-vision/SKILL.md
│   ├── product-strategy/SKILL.md
│   ├── product-roadmap/SKILL.md
│   └── okrs/SKILL.md
│
├── Product Discovery Skills
│   ├── prd/SKILL.md
│   ├── user-stories/SKILL.md
│   ├── jobs-to-be-done/SKILL.md
│   ├── user-personas/SKILL.md
│   └── customer-journey-map/SKILL.md
│
├── Product Research Skills
│   ├── market-research/SKILL.md
│   ├── user-research-report/SKILL.md
│   └── opportunity-assessment/SKILL.md
│
├── Marketing Positioning Skills
│   ├── positioning-statement/SKILL.md
│   ├── messaging-framework/SKILL.md
│   ├── value-proposition-canvas/SKILL.md
│   └── brand-guidelines/SKILL.md
│
├── Marketing Content Skills
│   ├── content-strategy/SKILL.md
│   ├── campaign-brief/SKILL.md
│   ├── competitor-battlecard/SKILL.md
│   └── case-study-brief/SKILL.md
│
├── Marketing Launch Skills
│   ├── gtm-strategy/SKILL.md
│   ├── launch-checklist/SKILL.md
│   ├── product-datasheet/SKILL.md
│   └── sales-enablement-kit/SKILL.md
│
└── Bridge Skills (Cross-Functional)
    ├── product-brief/SKILL.md
    ├── release-notes/SKILL.md
    ├── faq-help-center/SKILL.md
    └── product-demo-script/SKILL.md
```

## Contributing

Contributions are welcome! To add or improve documents:

1. Fork the repository
2. Make your changes to the relevant SKILL.md
3. Submit a pull request

## License

MIT
