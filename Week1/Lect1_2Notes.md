# Objectives
1.1: Understand some of the history of software development.<br />
1.2: Explain current challenges facing software development.<br />
1.3: Cite common reasons why projects fail.<br />
1.4: Describe the characteristics of a successful project.<br />
1.5: Explain the advantages and disadvantages of the major software development life cycle models.<br />
1.6: Identify lean software development principles.<br />
1.7: Understand DevOps activities.<br />
1.8: Explain the 4 SCM processes.<br />

## 1.1
Software engineer first used in 1968
- IBM (OS/360), Honeywell, Univax
- Expensive and huge (room size). Used vacuum tubes
- Programmers were mathematicians, electrical engineers, and others not trained in formal computer science.
- Assembly language
- Most applications were defense, payroll, inventory focused

In 1968, people started to complain about the price of creating new applications.
- Expensive
- Difficult to manage 
- Poor reliability
- Lack of user acceptance (JCL (Job Control Language) - a language needed to assemble and run an application)
- Difficult to maintain

## 1.2
### Each of these problems still exist
- Software dev is labor intensive
- SW productivity rates for engineering are around 1 loc/hr
### Today

#### Expensive
- Hardware has gotten cheaper (off the shelf products)
- OS and other apps are much cheaper now (off the shelf). Custom software is still very expensive.

#### Difficult to manage
- SW projects are still difficult to estimate, plan, and track
- Many projects are late and over budget

#### Poor reliability
- SW defect rates are around 1 delivered defect per thousand lines of code.
- With apps spanning millions of lines of code, customers experience many defects. Customer Reported Unique Defects (CRUD)

#### User acceptance
- In old days, customers tolerated a lof of cryptic interfaces. Today, the success of a project is often a function of its GUI.

#### Difficult to maintain
- Despite advances in languages and methodologies, SW is still difficult to maintain.
- Maintenance requires both knowledge of the code as well as the application domain.

## 1.3 & 1.4
### Perspectives on successful projects
#### From perspective of the customer
- On time and on budget
- Meets requirements (works)
- Quality (performance, security, etc.)
#### From perspective of the dev org
Customer perspective applies as well as
- Profitable
- Avoid team burnout
#### Some stats
- 26% of all SW projects fail (didn't meet all perspectives)
- 46% of all SW projects experience cost and schedule overruns or significantly reduced functionality

### Symptoms of Failure
#### Early Symptoms:
- Lack of project plan
- Lack of stakeholder communication
- No external involvement of quality organizations
- Project changes are managed poorly
- Deadlines are unrealistic
- Lack of understanding of user needs
- Project's scope is ill-defined
- Project lacks appropriate skills
- Best practices are ignored

#### Fatal Symptoms:
- Excessive hard work
- High staff turnover
- Aggressive and defensive behavior
- No fun
#### Critical success factors in SW projects
- Start on the right foot
    - 70% of "dooming" acts occur before a build ever starts
    - Build the right team
    - Give the team what they need
        - Environment
        - Tools
- Maintain the momentum
    - Keep attrition low
    - Monitor quality
    - Manage the product not the people
- Track progress
    - Discussed later
- Make smart decisions
    - best practices, analytics, etc.
- Do lessons learned
    - post mortem, project retrospective, etc.