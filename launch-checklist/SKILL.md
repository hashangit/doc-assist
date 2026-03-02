---
name: launch-checklist
description: Create a Launch Checklist for cross-functional readiness before release. Use when user asks for "launch checklist", "go-to-market checklist", "release checklist", or "launch readiness".
---

# Launch Checklist

Cross-functional readiness checklist for product launches.

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
**Save to:** `doc-assist/marketing/launch-checklist.md`

## Template

```markdown
# Launch Checklist: [Product/Feature Name]

## Launch Details
- **Product:** [Name]
- **Launch Date:** [Date]
- **Launch Type:** [Major/Minor/Patch]
- **Launch Owner:** [Name]

## Readiness Criteria
[Define what "ready to launch" means - must meet all criteria]

---

## Product

- [ ] Feature complete
- [ ] QA testing complete
- [ ] Performance testing passed
- [ ] Security review complete
- [ ] Accessibility compliance verified
- [ ] Bug count below threshold: [Current: X, Max: Y]
- [ ] Product documentation complete
- [ ] Release notes drafted

**Sign-off:** [Name] - [Date]

---

## Engineering

- [ ] Code deployed to staging
- [ ] Production deployment plan documented
- [ ] Rollback plan documented
- [ ] Monitoring/alerting configured
- [ ] Load testing passed
- [ ] Database migrations tested
- [ ] Feature flags configured

**Sign-off:** [Name] - [Date]

---

## Marketing

- [ ] Positioning finalized
- [ ] Messaging approved
- [ ] Website updates ready
- [ ] Landing page ready
- [ ] Blog post drafted
- [ ] Press release (if applicable)
- [ ] Social media content prepared
- [ ] Email campaigns ready
- [ ] Customer comms drafted
- [ ] Analyst briefing (if applicable)

**Sign-off:** [Name] - [Date]

---

## Sales

- [ ] Sales team trained
- [ ] Pitch deck ready
- [ ] Demo environment ready
- [ ] Demo script approved
- [ ] FAQ documented
- [ ] Objection handling guide ready
- [ ] Pricing approved in system
- [ ] Quote configuration ready
- [ ] CRM updated with new SKUs

**Sign-off:** [Name] - [Date]

---

## Customer Success

- [ ] Support team trained
- [ ] Knowledge base articles ready
- [ ] Support playbooks updated
- [ ] Escalation paths defined
- [ ] Customer health checks planned
- [ ] Onboarding updates ready
- [ ] Beta customer feedback reviewed

**Sign-off:** [Name] - [Date]

---

## Legal & Compliance

- [ ] Terms of service updated (if needed)
- [ ] Privacy policy updated (if needed)
- [ ] Compliance requirements met
- [ ] Contracts reviewed
- [ ] Third-party agreements in place

**Sign-off:** [Name] - [Date]

---

## Go/No-Go Decision

### Status Check
| Function | Status | Blocker |
|----------|--------|---------|
| Product | [Ready/Not Ready] | [Issue if any] |
| Engineering | [Ready/Not Ready] | [Issue if any] |
| Marketing | [Ready/Not Ready] | [Issue if any] |
| Sales | [Ready/Not Ready] | [Issue if any] |
| CS | [Ready/Not Ready] | [Issue if any] |
| Legal | [Ready/Not Ready] | [Issue if any] |

### Decision
- **Decision:** [GO / NO-GO / DELAY]
- **Date:** [Date]
- **Decision Makers:** [Names]
- **Notes:** [Any conditions or caveats]

### If Delayed
- **New Target Date:** [Date]
- **Reason:** [Why]
- **Blockers:** [What needs to be resolved]
```
