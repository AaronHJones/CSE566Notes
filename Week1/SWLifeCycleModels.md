# Software Lifecycle Models
### SW Development Process Models
- A sw dev process model defines the steps that must be taken in developing the product.
- Each step must be a well-defined activity with entry and exit criteria.
- Intermediate work products are typically generated as a consequence of many steps.
- Metrics may also be gathered during each step.

### Major life cycle models
- Waterfall
- Incremental
- Time Box
- Extreme
- Agile

## Waterfall Model
- Documentation driven
    - this model produces a lot of documentation
    - req, design, code, test where documentation is created for each step
- Proceeds through a sequence of phases
    - Requirements
    - Design
    - Code
    - Test
- A phase must be fully completed before the next phase may begin
- Advantages
    - Easy to plan
    - Easy to track

- Disadvantages
    - Hard to accommodate changes
    - Cannot begin until all of the requirements are defined
        - Tends to take too long

## Incremental Model
- Constructs the sw as a series of builds:
    - Sequential (Occurs in separate increments or sequences)
    - Concurrent (Occurs with multiple increments being built at the same time)
- Each build contains a set of capabilities of the end product
>Example (Sequential Incremental<br />
>Build 1 => features 1 - 3; Build 2 => features 4 & 5; etc... <br />
>Build 2 will add regression testing to ensure build 1 works with new added features<br />

>Example (Concurrent Incremental)<br />
>Increment 1 can still be in test when increment 2 is in coding<br />
>The testing phase in incremental development happens at the end of each increment so changes are flexible and are easier to make. Changes during the waterfall model can be costly and time-consuming<br />
>If no changes will occur. Seq Inc still includes regression testing. Defects can be found earlier and fixed before they become harder to fix.
### Incremental Advantages
- Dev can begin without knowing all the req's
- Easier to accommodate changes
- Customers may get earlier releases
### Incremental Disadvantages
- Rework

## Time Box Model <br />
SW dev that provides an agile approach where change or rework is a primary focus
- Team continuously identifies and prioritizes work to be done
- Work is organized into a time box (usually 2-4 week interval):
    - In each time box a few requirements or use cases are implemented
    - Risk based strategies can be used to determine the order of implementation
- Produces a documented, tested executable at the conclusion of each time box
### Advantages
- Do not need to know all the req's in advance
- Easy to accommodate changes
- Deliver fast
### Disadvantages
- Risk of rework (architecture is important)

## Extreme Programming
### Characterized by:
- Pair programming
- Collective ownership
- Continuous testing
- Small releases
- On-site customer
- Continuous integration
- Refactoring
- Metaphor approach to documentation