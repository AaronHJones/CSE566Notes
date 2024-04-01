# SW Tracking Activities
## Monitoring Progress
#### SW dev teams must track their progress against their plan.
- If sw subcontracting is used, supplier activities must also be tracked against the subcontract management plan.
- Tracking is necessary to detect problems early.

#### Without tracking there is no control

#### Items to track include:
- Schedule
- Budget
- Quality - more difficult b/c quality has to be defined
- Risk

## Project Review "Reports"
#### The sw task lead has the responsibility of communicating project status to senior management

#### Typical information in this report include:
- Presentation of sw metrics
    - Performance to plan
    - Risk indicators
- Analysis of metrics
- Risks to the project
- Planned corrective actions

### Project Review Reporting Guidelines
#### Provide information **consistently**
#### Suggest candidate solutions when raising problems
- Control the solution space
#### Communicate major accomplishments
- Recognize team accomplishments
- Invite senior management to celebrations
#### Filter status information
- Do not present too detailed info that senior management cannot have an impact on

### Monitoring Project Status
In order to monitor the status of the project, the software task lead must obtain info from many sources
#### Subjective data
- "Management by walking around"
- Personal inquiry of status
- Individual team member status reports
- Project meetings
#### Hard Data
- **Quantitative project metrics**

### Individual Status Reports
#### Possible information to include:
- Issues requiring immediate attention
- Activities performed during reporting period
- Planned activities for the next reporting period
- General issues
- Agile considerations

### Project meetings
#### Meetings should be held periodically and at a fixed time
#### They should contribute to the atmosphere of order and control
#### Key itemsFrom the meeting should be recorded:
- Project progress and future plans
- Action items
#### Agile stand-up meetings

### Possible project meeting agenda
#### General project info
- Review of progress
- Updates to plan
- Discussion of key issues
#### Individual status reports
#### Agile stand-up agenda:
- What did I work on yesterday?
- What am i working on today?
- What issues are blocking me?

### Monitoring Project Schedule Progress
#### Project schedule progress is tracked by comparing the tasks completed against the plan
#### Visibility into schedule progress is obtained via analysis of:
- Milestone completion
- Task completion (partial task completion is OK as long as it can be objectively measured)
    - Gantt char (can be expanded to multiple levels)
    - Critical path
    - BCWP and BCWS

### Project Milestones
#### MS correspond to significant events on the project
#### Types of milestones:
- Delivery of work product
- Reviews and meetings
#### Milestones are binary:
- A milestone is either fully met or not fully met

### Monitor milestone completion
### Monitor task progress
### Binary quality gates at the inch-pebble level

# Tracking
BCWP => Budgeted cost of work __Performed__<br />
BCWS => Budgeted cost of work __Scheduled__<br />
ACWP => Actual cost of work __Performed__

### SV (Schedule Variance)
- SV = Work performed - work scheduled
pos = ahead of schedule<br />
neg = behind schedule

### SW Performance Index (SPI):
SPI = BCWP / BCWS
- Value of 100% indicates that work is on schedule

### Cost Variance (CV)
CV = BCWP - ACWP

### Cost Performance Index (CPI)
CPI = BCWP / ACWP
CPI < 0.95 indicates conditions that warrant risk management

### Estimate at Completion (EAC)
EAC = ACWP + ((BAC - BCWP) / CPI)

### To Complete Performance Index (TCPI)
TCPI = (BAC - BCWP) / (EAC - ACWP)
- Should be compared against the cumulative "to date" CPI

## Tracking SW Quality
Harder to track because it's harder to quantify<br />

### Orthogonal Defect Classification
Type, When, Root Cause, Severity

### Possible Corrective Actions for Projects
Use float<br />
Rearrange tasks<br />
Acquire needed skills / perform training<br />
Re-prioritize requirements<br />
Re-allocate req to increments<br />
Re-negotiate scope and re-baseline<br />
Acquire tools<br />
Improve the dev process<br />