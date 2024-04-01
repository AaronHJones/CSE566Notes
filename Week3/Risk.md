# Risk Management
RE  $\rightarrow$ Risk Exposure <br />
AE  $\rightarrow$ Adverse Event <br />
C   $\rightarrow$ Consequences  <br />
P   $\rightarrow$ Probability   <br />
<mark>**RE = P(AE) * C**</mark>
## Risk Identification
### Definitions
<mark>**Risk**</mark> is the combination of the probability of an abnormal event or failure and the consequences of that event or failure to a projects success or systems performance.<br />
<mark>**Risk Assessment**</mark> is the process and procedures of identifying, characterizing, quantifying, and evaluating risks and their significance.<br />
<marK>**Risk Management**</mark> is any technique used either to minimize the probability of an adverse event or to mitigate its consequences with good engineering design, good operating practices, and/or preventative maintenance.<br />

## Motivation for Risk Management
- The key to a successful software project is to "take the **right** risks at the **right** time". <br />
    - Avoiding all risks at all times is not good
    - Taking too many risks is bad
- Risk management is **critical** when balancing quality, cycle time, and cost considerations.

## Hierarchy for Managing Risks
<mark>**Stage 1: Crisis Reaction**</mark>
- In this stage, there is no risk management.
- There is a "fire fighting" attitude if a risk occurs.

<mark>**Stage 2: Risk Management**</mark>
- **Prevention**: measures taken to prevent the risk from occurring.
- **Recovery**: a plan made to deal with the consequences that occur due to the risk.

<mark>**Stage3: Elimination of the root causes of the risk**</mark>

## Software Engineering Institute (SEI) Model for Continuous Risk Management
Step 1: Identify Risk<br/>
Step 2: Analyze and prioritize risk<br/>
Step 3: Mitigate risk<br/>
Step 4: Monitor risk<br/>

# Risk Identification
## Step 1: Identify the Risks
Effective risk management involves the capability to discern difference between <mark>**risk**</mark> and <mark>**uncertainty**</mark>. <br/>
- Risk implies <mark>**structure**</mark>, lending itself to analysis:
    - Capable of estimating the probability of occurrence
    - Capable of estimating the magnitude of consequences
    - Risk involves dealing with "known unknowns".
- Uncertainty resists analysis:
    - Unable to characterize the possible course of events
    - Unable to estimate the probability of occurrence
    - Uncertainty involves dealing with "unknown unknowns"

### Risk Identification Approaches
- Periodic risk assessments
- Continuous risk identification and communication:
    - An agenda item for team meetings

#### **Periodic Risk Assessments**
- Held at the beginning of the project, monthly, and at key milestones
- Might utilize a risk checklist similar to SEI taxonomy-based questionnaire
- Important to review project "lessons learned"

#### **Continuous Risk Identification and Communication**
- Identified risks must be communicated at scheduled project status meetings
- Everyone should be able to report risks without concern
    - Be on alert
    - Report what you see

# Risk Assessment
## Step 2: Analyze Risks
- Determine the probability of the risk occurring (qualitatively or quantitatively)

- Assess the consequences of the risk
- Determine the overall risk $\Rightarrow$ RE = P(adv. event) * consequences
### Qualitative Probability Assessment
- The SEI qualitative probability assessments consist of:
    - Very likely
    - Probable
    - Improbable
    - Impossible

### Assess Impact of Risk
**Assess the impact of the risk with respect to...**
- Product performance
- Project
    - Cost
    - Schedule
- Product life cycle support

### Assessing Impact Qualitatively
- The degree of impact must be assessed for **each** of the impact areas
- The SEI qualitative impact assessments consist of:
    - Catastrophic
    - Critical
    - Marginal

### Determine Overall Risk for Each Risk Item
- The overall risk of each item is the product of its probability of occurrence and its potential impact.
- Risks should be ordered in terms of decreasing impact

### SEI Risk Magnitude Matrix
| Prob/Sev. | Very Likely | Prob. | Improb. | Imposs. |
| ---       | ---         | ---   | ---     | ---     | 
| Catastr   | High        | High  | Med     | None    |
| Critical  | High        | Med   | Low     | None    |
| Marg      | Med         | Low   | Low     | None    |

### Quantitative Probability Assessment
The probability of a risk item should be expressed quantitatively as a number **between 0 and 100**

### Assessing Impact Quantitatively
- The degree of impact must be assessed for **each** of the impact areas.
- The degree of impact should be expressed in terms of dollars.

> <br />
> <b>note</b>: If a process is critical, hiring an expert may be the best idea
> <br />
> <br />

### Project Risk List
- The decision to mitigate a risk is based on its impact on Management Reserve
- When a risk becomes reality, it is no long a risk. Move its impact into Estimate at Complete (EAC)
- Some mitigation costs are part of the project budget. Some should be allocated for MR.

**Total Risk Exposure** &Rightarrow; Total RE = $\Sigma_{RE}$

**Track RE vs MR throughout the project**

# Risk Mitigation
## Step 3: Mitigate Risk
- Once the project risks have been identified and analyzed, the set of risks to be managed must be selected
- Select those risks to manage where the benefits outweigh the costs.
    - Leverage risks
    - Insurance deductible analogy (reduce consequences of adverse event happening)

### Risk Tradeoffs
- Interrelationships may exist among risks (job to avoid heart attack => could twist ankle)
- Actions taken to reduce one risk may increase another
- Be careful during risk management to ensure that these
interrelationships are understood

### Risk Mitigation Approaches
- Reduce the probability of the risk occurring
- Reduce the potential impact of the risk, should it occur (contingency planning => invoked upon AE):
    - Monitor risk and invoke a predetermined response, should the need arise.
    - Requires the definition of quantitative metrics for assessing the risk
    - Requires the definition of thresholds for the metrics which trigger the response
    - Requires the definition of cost-effective contingency responses

### Example
- Consider the risk associated with loss of key personnel
- Risk mitigation approaches might consist of:
    - Selecting personnel for the project who are unlikely to leave the project
    - Cross-training to minimize the impact should a loss occur
    - Developing a contingency plan involving hiring consultants

# Monitor Risk
## Step 4: Track Status of Risks and Actions
- Monitor risk exposure over time
- Monitor risk exposure and management reserve
- Assess the impact of risk actions
- Software risks are rolled up to the project level