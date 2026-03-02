---
name: project-management-docs
description: Create Project Management documents for planning, executing, and controlling projects. Includes Project Charter, Business Case, Stakeholder Register, WBS, Project Schedule, Resource Plan, Budget, Risk Register, Communication Plan, RACI Matrix, Status Reports, Issue Log, Change Requests, Lessons Learned, and Closure Reports. Use when user asks for "project charter", "WBS", "risk register", "status report", "RACI", "project plan", "lessons learned", or any project management documentation.
---

# Project Management Documents

Create documents for planning, executing, and controlling projects through all phases.

## Document Types by Phase

### Initiation Phase

#### Project Charter

Formal authorization document that defines the project.

**Structure:**
```markdown
# Project Charter: [Project Name]

## Project Information
- **Project Name:** [Name]
- **Project ID:** [Identifier]
- **Sponsor:** [Name]
- **Project Manager:** [Name]
- **Date:** [Date]

## Business Justification
[Why this project is needed - link to strategic objectives]

## Project Objectives
1. [Specific, measurable objective 1]
2. [Specific, measurable objective 2]
3. [Specific, measurable objective 3]

## Scope

### In Scope
- [Deliverable 1]
- [Deliverable 2]
- [Deliverable 3]

### Out of Scope
- [Explicitly excluded item 1]
- [Explicitly excluded item 2]

## Key Deliverables
| Deliverable | Description | Due Date |
|-------------|-------------|----------|
| [Deliverable 1] | [Description] | [Date] |

## High-Level Timeline
| Phase | Duration | Key Milestones |
|-------|----------|----------------|
| [Phase 1] | [Duration] | [Milestone] |

## Budget Summary
- **Total Budget:** $[Amount]
- **Contingency:** $[Amount] ([X]%)

## Key Stakeholders
| Name | Role | Responsibility |
|------|------|----------------|
| [Name] | [Role] | [RACI designation] |

## Risks & Assumptions

### High-Level Risks
| Risk | Impact | Mitigation |
|------|--------|------------|
| [Risk 1] | [H/M/L] | [Strategy] |

### Assumptions
- [Assumption 1]
- [Assumption 2]

## Constraints
- [Constraint 1: Time, budget, resource, or technical]
- [Constraint 2]

## Success Criteria
[How will we know the project succeeded?]

## Approval
| Role | Name | Signature | Date |
|------|------|-----------|------|
| Sponsor | [Name] | | |
| Project Manager | [Name] | | |
```

#### Business Case

Justification for the project investment.

**Structure:**
```markdown
# Business Case: [Project Name]

## Executive Summary
[2-3 paragraph overview of the opportunity and recommendation]

## Problem/Opportunity Statement
### Current State
[Description of current situation]

### Desired State
[Description of future state after project]

### Gap Analysis
[What's missing between current and desired state]

## Strategic Alignment
| Business Objective | How Project Supports |
|-------------------|---------------------|
| [Objective 1] | [Explanation] |

## Options Analysis

### Option 1: [Name] (Recommended)
- **Description:** [What this option entails]
- **Pros:** [Advantages]
- **Cons:** [Disadvantages]

### Option 2: [Name]
- **Description:** [What this option entails]
- **Pros:** [Advantages]
- **Cons:** [Disadvantages]

### Option 3: Do Nothing
- **Description:** [What happens if we don't proceed]
- **Impact:** [Consequences]

## Cost-Benefit Analysis

### Costs
| Category | Year 1 | Year 2 | Year 3 | Total |
|----------|--------|--------|--------|-------|
| Development | $[X] | $[X] | $[X] | $[X] |
| Operations | $[X] | $[X] | $[X] | $[X] |
| **Total** | **$[X]** | **$[X]** | **$[X]** | **$[X]** |

### Benefits
| Benefit | Year 1 | Year 2 | Year 3 | Total |
|---------|--------|--------|--------|-------|
| Revenue increase | $[X] | $[X] | $[X] | $[X] |
| Cost savings | $[X] | $[X] | $[X] | $[X] |
| **Total** | **$[X]** | **$[X]** | **$[X]** | **$[X]** |

### ROI Calculation
- **Total Investment:** $[X]
- **Total Benefits:** $[X]
- **Net Benefit:** $[X]
- **ROI:** [X]%
- **Payback Period:** [X months/years]

## Risk Assessment
| Risk | Likelihood | Impact | Mitigation |
|------|------------|--------|------------|
| [Risk] | H/M/L | H/M/L | [Plan] |

## Implementation Timeline
[High-level timeline with key milestones]

## Recommendation
[Clear recommendation with rationale]

## Approval
| Role | Name | Decision | Date |
|------|------|----------|------|
| [Role] | [Name] | [Approved/Rejected] | [Date] |
```

#### Stakeholder Register

Map of all project stakeholders.

**Structure:**
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

---

### Planning Phase

#### Work Breakdown Structure (WBS)

Hierarchical decomposition of project work.

**Structure:**
```markdown
# Work Breakdown Structure: [Project Name]

## WBS Overview
- **Project:** [Name]
- **Version:** [Number]
- **Date:** [Date]

## WBS Dictionary

### 1.0 [Project Name]
#### 1.1 [Phase/Component]
##### 1.1.1 [Deliverable]
###### 1.1.1.1 [Work Package]

---

## WBS Structure

## 1.0 [Project Name]

### 1.1 [Phase 1: e.g., Planning]
| WBS # | Work Package | Description | Owner | Est. Hours |
|-------|--------------|-------------|-------|------------|
| 1.1.1 | [Task 1] | [Description] | [Name] | [Hours] |
| 1.1.2 | [Task 2] | [Description] | [Name] | [Hours] |

### 1.2 [Phase 2: e.g., Design]
| WBS # | Work Package | Description | Owner | Est. Hours |
|-------|--------------|-------------|-------|------------|
| 1.2.1 | [Task 1] | [Description] | [Name] | [Hours] |

### 1.3 [Phase 3: e.g., Development]
| WBS # | Work Package | Description | Owner | Est. Hours |
|-------|--------------|-------------|-------|------------|

### 1.4 [Phase 4: e.g., Testing]
...

### 1.5 [Phase 5: e.g., Deployment]
...

### 1.6 [Phase 6: e.g., Closure]
...

---

## WBS Summary
| Phase | Work Packages | Total Hours |
|-------|---------------|-------------|
| 1.1 Planning | [#] | [Hours] |
| **Total** | **[#]** | **[Hours]** |
```

#### Project Schedule

Timeline with dependencies and milestones.

**Structure:**
```markdown
# Project Schedule: [Project Name]

## Schedule Overview
- **Project Start:** [Date]
- **Project End:** [Date]
- **Total Duration:** [Days/Weeks]
- **Last Updated:** [Date]

## Key Milestones
| Milestone | Date | Status | Dependencies |
|-----------|------|--------|--------------|
| [Milestone 1] | [Date] | [On Track/At Risk/Delayed] | [Dependency] |

## Critical Path
[List of tasks on the critical path]

## Detailed Schedule

### Phase 1: [Name] ([Start Date] - [End Date])

| ID | Task | Owner | Start | End | Duration | Dependencies | Status |
|----|------|-------|-------|-----|----------|--------------|--------|
| 1.1 | [Task] | [Name] | [Date] | [Date] | [Days] | [Predecessor] | [%] |
| 1.2 | [Task] | [Name] | [Date] | [Date] | [Days] | 1.1 | [%] |

### Phase 2: [Name]
...

## Resource Loading
[How resources are allocated across timeline]

## Schedule Assumptions
- [Assumption 1]
- [Assumption 2]

## Schedule Risks
| Risk | Impact on Schedule | Mitigation |
|------|---------------------|------------|
| [Risk] | [Days impact] | [Plan] |
```

#### Risk Register

Track and manage project risks.

**Structure:**
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

#### RACI Matrix

Clarify roles and responsibilities.

**Structure:**
```markdown
# RACI Matrix: [Project Name]

## RACI Legend
- **R** = Responsible (Does the work)
- **A** = Accountable (Final decision maker - only ONE per task)
- **C** = Consulted (Provides input before decision)
- **I** = Informed (Notified after decision)

## Matrix

| Task/Deliverable | [Role 1] | [Role 2] | [Role 3] | [Role 4] | [Role 5] |
|------------------|----------|----------|----------|----------|----------|
| **Phase 1: Planning** |
| Define scope | A | R | C | I | I |
| Create schedule | C | A | R | C | I |
| Identify risks | C | A | R | C | C |
| **Phase 2: Execution** |
| [Task] | R | A | C | I | I |
| [Task] | C | I | A | R | C |
| **Phase 3: Monitoring** |
| Status reports | I | I | A | R | I |
| Issue management | C | C | A | R | C |

## RACI Rules
1. Every task has exactly ONE Accountable person
2. Minimize the number of Consulted (avoid bottlenecking)
3. Keep Informed list reasonable (avoid information overload)
4. If Responsible is a group, name the specific person

## Role Definitions
| Role | Person | Responsibilities |
|------|--------|------------------|
| [Role 1] | [Name] | [Key responsibilities] |
```

#### Communication Plan

Define how information flows.

**Structure:**
```markdown
# Communication Plan: [Project Name]

## Communication Objectives
1. [Objective 1: e.g., Keep stakeholders informed of progress]
2. [Objective 2: e.g., Escalate issues promptly]

## Communication Matrix

| Communication | Audience | Owner | Format | Frequency | Purpose |
|---------------|----------|-------|--------|-----------|---------|
| Status Report | Project Team | PM | Email/Slack | Weekly | Progress update |
| Steering Committee | Sponsors, Leads | PM | Presentation | Monthly | Governance |
| Team Standup | Team Members | Scrum Master | Meeting | Daily | Sync |
| Risk Review | PM, Leads | PM | Meeting | Bi-weekly | Risk assessment |

## Meeting Cadence

### Daily Standup
- **Time:** [Time]
- **Duration:** 15 minutes
- **Attendees:** [Who]
- **Format:** [What, So What, Now What / Three Questions]

### Weekly Team Meeting
- **Time:** [Day/Time]
- **Duration:** [Minutes]
- **Attendees:** [Who]
- **Agenda:**
  1. Review action items
  2. Progress update
  3. Blockers/discussion
  4. Next week priorities

### Monthly Steering Committee
- **Time:** [Day/Time]
- **Duration:** [Minutes]
- **Attendees:** [Who]
- **Agenda:**
  1. Executive summary
  2. Key metrics
  3. Risks and issues
  4. Decisions needed

## Escalation Path
1. **Level 1:** Team Lead → [Contact, timeline]
2. **Level 2:** Project Manager → [Contact, timeline]
3. **Level 3:** Sponsor → [Contact, timeline]

## Communication Channels
| Channel | Use For | Response Time |
|---------|---------|---------------|
| Slack | Quick questions, updates | Same day |
| Email | Formal communication, decisions | 24 hours |
| Meeting | Complex discussions, decisions | Scheduled |
| Phone/Urgent | Critical issues | Immediate |
```

---

### Execution & Control Phase

#### Status Report

Regular project progress updates.

**Structure:**
```markdown
# Project Status Report: [Project Name]

## Report Information
- **Reporting Period:** [Start Date] - [End Date]
- **Report Date:** [Date]
- **Prepared By:** [Name]

## Executive Summary
[2-3 sentences summarizing overall status and key points]

## Overall Status
| Area | Status | Trend |
|------|--------|-------|
| **Schedule** | 🟢 On Track / 🟡 At Risk / 🔴 Off Track | ↗️ ➡️ ↘️ |
| **Budget** | 🟢 On Track / 🟡 At Risk / 🔴 Off Track | ↗️ ➡️ ↘️ |
| **Scope** | 🟢 On Track / 🟡 At Risk / 🔴 Off Track | ↗️ ➡️ ↘️ |
| **Quality** | 🟢 On Track / 🟡 At Risk / 🔴 Off Track | ↗️ ➡️ ↘️ |
| **Overall** | 🟢 On Track / 🟡 At Risk / 🔴 Off Track | ↗️ ➡️ ↘️ |

## Key Accomplishments This Period
- ✅ [Accomplishment 1]
- ✅ [Accomplishment 2]
- ✅ [Accomplishment 3]

## Planned vs. Actual
| Milestone/Deliverable | Planned Date | Actual/Forecast | Status |
|-----------------------|--------------|-----------------|--------|
| [Item 1] | [Date] | [Date] | [Status] |

## Upcoming Activities (Next Period)
- [ ] [Activity 1] - Due: [Date]
- [ ] [Activity 2] - Due: [Date]
- [ ] [Activity 3] - Due: [Date]

## Risks & Issues
### Top Risks
| Risk | Impact | Mitigation | Status |
|------|--------|------------|--------|
| [Risk 1] | [H/M/L] | [Plan] | [Status] |

### Active Issues
| Issue | Owner | Due Date | Status |
|-------|-------|----------|--------|
| [Issue 1] | [Name] | [Date] | [Open/In Progress] |

## Budget Status
| Category | Budget | Spent | Remaining | % Used |
|----------|--------|-------|-----------|--------|
| [Category] | $[X] | $[X] | $[X] | [%] |
| **Total** | **$[X]** | **$[X]** | **$[X]** | **[%]** |

## Decisions Needed
| Decision | Options | Owner | Due Date |
|----------|---------|-------|----------|
| [Decision needed] | [Options] | [Name] | [Date] |

## Help Needed
[What support is needed from leadership/stakeholders]
```

#### Issue Log

Track and manage project issues.

**Structure:**
```markdown
# Issue Log: [Project Name]

## Log Information
- **Last Updated:** [Date]
- **Total Issues:** [Number]
- **Open:** [Number] | **In Progress:** [Number] | **Closed:** [Number]

## Issue Summary
| Priority | Open | In Progress | Closed |
|----------|------|-------------|--------|
| Critical | [#] | [#] | [#] |
| High | [#] | [#] | [#] |
| Medium | [#] | [#] | [#] |
| Low | [#] | [#] | [#] |

## Active Issues

### Issue #1: [Issue Title]
| Attribute | Details |
|-----------|---------|
| **ID** | ISS-[Number] |
| **Date Raised** | [Date] |
| **Raised By** | [Name] |
| **Category** | [Technical/Resource/Schedule/External] |
| **Priority** | [Critical/High/Medium/Low] |
| **Description** | [What is the problem] |
| **Impact** | [What happens if not resolved] |
| **Owner** | [Name] |
| **Assigned To** | [Name] |
| **Root Cause** | [Why this happened] |
| **Resolution** | [How it will be/was fixed] |
| **Target Date** | [Date] |
| **Status** | [Open/In Progress/Resolved/Closed] |
| **Closure Date** | [Date] |

### Issue #2: [Issue Title]
...

## Closed Issues
| ID | Issue | Resolution | Closure Date |
|----|-------|------------|--------------|
| ISS-XX | [Description] | [How resolved] | [Date] |
```

#### Change Request

Formal request to modify project scope/schedule/budget.

**Structure:**
```markdown
# Change Request: [CR-Number]

## Request Information
- **CR Number:** CR-[XXX]
- **Date Submitted:** [Date]
- **Requested By:** [Name]
- **Status:** [Submitted/Under Review/Approved/Rejected]

## Change Description
### Current State
[Description of current situation]

### Proposed Change
[Detailed description of the change]

### Reason for Change
[Why this change is needed]

## Impact Analysis

### Scope Impact
| Area | Impact | Details |
|------|--------|---------|
| Features | [+/-/None] | [Description] |
| Deliverables | [+/-/None] | [Description] |

### Schedule Impact
- **Current End Date:** [Date]
- **Proposed End Date:** [Date]
- **Variance:** [+/- Days]
- **Impact on Critical Path:** [Yes/No - Details]

### Budget Impact
| Category | Current | Proposed | Variance |
|----------|---------|----------|----------|
| Labor | $[X] | $[X] | $[X] |
| Materials | $[X] | $[X] | $[X] |
| **Total** | **$[X]** | **$[X]** | **$[X]** |

### Resource Impact
[Additional resources needed or freed up]

### Risk Impact
| New/Changed Risk | Likelihood | Impact |
|------------------|------------|--------|
| [Risk] | [H/M/L] | [H/M/L] |

### Quality Impact
[Effect on quality standards or testing]

## Alternatives Considered
1. **[Alternative 1]:** [Description] - Rejected because [reason]
2. **[Alternative 2]:** [Description] - Rejected because [reason]

## Recommendation
[PM's recommendation with rationale]

## Approval
| Role | Name | Decision | Date | Comments |
|------|------|----------|------|----------|
| Project Manager | [Name] | [Approve/Reject] | [Date] | |
| Sponsor | [Name] | [Approve/Reject] | [Date] | |
| [Other] | [Name] | [Approve/Reject] | [Date] | |
```

---

### Closure Phase

#### Lessons Learned

Document learnings for future projects.

**Structure:**
```markdown
# Lessons Learned: [Project Name]

## Document Information
- **Project:** [Name]
- **Project Manager:** [Name]
- **Date:** [Date]
- **Participants:** [Names]

## Executive Summary
[Key takeaways in 2-3 sentences]

## What Went Well

### Success 1: [Title]
- **Description:** [What happened]
- **Why it worked:** [Root cause of success]
- **Recommendation:** [How to replicate]

### Success 2: [Title]
...

## What Could Be Improved

### Challenge 1: [Title]
- **Description:** [What happened]
- **Impact:** [Effect on project]
- **Root Cause:** [Why it happened]
- **Recommendation:** [How to avoid in future]

### Challenge 2: [Title]
...

## By Category

### Project Management
| Lesson | Category | Recommendation |
|--------|----------|----------------|
| [Lesson] | Planning/Execution/Communication | [Action] |

### Technical
| Lesson | Category | Recommendation |
|--------|----------|----------------|
| [Lesson] | Architecture/Tools/Process | [Action] |

### Team & Resources
| Lesson | Category | Recommendation |
|--------|----------|----------------|
| [Lesson] | Staffing/Skills/Culture | [Action] |

## Process Improvements
1. [Improvement 1]
2. [Improvement 2]
3. [Improvement 3]

## What We Would Do Differently
1. [Action 1]
2. [Action 2]
3. [Action 3]

## Best Practices Identified
1. [Best practice 1]
2. [Best practice 2]

## Action Items for Future Projects
| Action | Owner | Priority |
|--------|-------|----------|
| [Action] | [Team/Role] | [H/M/L] |
```

#### Project Closure Report

Final project documentation.

**Structure:**
```markdown
# Project Closure Report: [Project Name]

## Executive Summary
[Brief overview of project outcomes and closure status]

## Project Information
- **Project Name:** [Name]
- **Project Manager:** [Name]
- **Sponsor:** [Name]
- **Start Date:** [Date]
- **Original End Date:** [Date]
- **Actual End Date:** [Date]

## Objectives Achievement

| Objective | Target | Actual | Status |
|-----------|--------|--------|--------|
| [Objective 1] | [Target] | [Result] | ✅ Met / ⚠️ Partial / ❌ Not Met |

## Scope Delivery

### Delivered
- [Deliverable 1] - [Status]
- [Deliverable 2] - [Status]

### Not Delivered
- [Item] - [Reason]

### Scope Changes
| CR # | Change | Impact | Status |
|------|--------|--------|--------|
| CR-001 | [Description] | [Schedule/Budget] | Approved |

## Schedule Performance
- **Planned Duration:** [Days]
- **Actual Duration:** [Days]
- **Variance:** [+/- Days]
- **Variance Reason:** [Explanation]

## Budget Performance
| Category | Budget | Actual | Variance |
|----------|--------|--------|----------|
| Labor | $[X] | $[X] | $[X] |
| Other | $[X] | $[X] | $[X] |
| **Total** | **$[X]** | **$[X]** | **$[X]** |

## Quality Metrics
| Metric | Target | Actual | Status |
|--------|--------|--------|--------|
| [Metric] | [Target] | [Result] | [Status] |

## Risks Summary
- **Total Risks Identified:** [Number]
- **Risks That Occurred:** [Number]
- **Risk Management Effectiveness:** [Effective/Partially Effective/Ineffective]

## Outstanding Items
| Item | Type | Owner | Resolution Plan |
|------|------|-------|-----------------|
| [Item] | [Issue/Defect/Action] | [Name] | [Plan] |

## Transition Plan

### Handoff Items
| Item | Recipient | Date | Status |
|------|-----------|------|--------|
| [Item] | [Team/Person] | [Date] | [Status] |

### Ongoing Support
[What support is needed post-project]

## Lessons Learned Summary
[Link to full Lessons Learned document - key highlights]

## Team Recognition
[Acknowledge team contributions]

## Recommendations
1. [Recommendation 1]
2. [Recommendation 2]

## Sign-Off
| Role | Name | Signature | Date |
|------|------|-----------|------|
| Project Manager | [Name] | | |
| Sponsor | [Name] | | |

## Attachments
- [ ] Final project schedule
- [ ] Final budget report
- [ ] Lessons learned document
- [ ] Transition documentation
```

---

## Agile/Scrum Documents

### Sprint-Level

| Document | Purpose |
|----------|---------|
| **Sprint Goal** | Objective for the sprint |
| **Sprint Backlog** | Work committed for sprint |
| **Burndown Chart** | Progress visualization |
| **Sprint Review Notes** | What was delivered |

### Program-Level

| Document | Purpose |
|----------|---------|
| **Product Backlog** | Prioritized work items |
| **Velocity Chart** | Team capacity tracking |
| **Definition of Done** | Completion criteria |

---

## Quick Reference

| Document | Phase | Update Frequency |
|----------|-------|------------------|
| Project Charter | Initiation | Once |
| Business Case | Initiation | As needed |
| Stakeholder Register | Initiation | Monthly |
| WBS | Planning | As changes occur |
| Project Schedule | Planning | Weekly |
| Risk Register | Planning/Execution | Weekly |
| RACI Matrix | Planning | As changes occur |
| Communication Plan | Planning | Quarterly |
| Status Report | Execution | Weekly |
| Issue Log | Execution | Daily/Weekly |
| Change Request | Execution | As needed |
| Lessons Learned | Closure | Once |
| Closure Report | Closure | Once |
