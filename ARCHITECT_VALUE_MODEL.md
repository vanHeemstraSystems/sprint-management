# Architect Value Model – Sprint Execution Layer

> *“Measure value delivered, not tasks completed.”*
> This document keeps your sprint execution aligned with your architectural practice.

See parent: [`sprint-planning-management / ARCHITECT_VALUE_MODEL.md`](https://github.com/vanHeemstraSystems/sprint-planning-management/blob/main/ARCHITECT_VALUE_MODEL.md)

-----

## Purpose of This Document

At the Sprint layer (active execution), the key question is:

> **“Is the work I am doing today creating architectural value — or am I busy without being effective?”**

-----

## Daily Practice Check (2 minutes, each morning)

```
Today's date: ___________

1. What is the single biggest architectural pain point I can address today?
   _______________________________________________

2. My planned tasks today — what is the architect_value_type of each?
   - Task 1: _________________________ → type: ___________
   - Task 2: _________________________ → type: ___________
   - Task 3: _________________________ → type: ___________

3. Am I working on tasks, or on problems?
   ( ) Problems — I know the pain point each task addresses
   ( ) Tasks    — I'm working from a list without checking the pain point

4. Is there anything on my list today that I should decline, delegate, or defer?
   _______________________________________________
```

-----

## Sprint Execution — Architect Value Type Labels

Apply one of these labels to every task and issue during the sprint:

|Label            |When to Use                                                               |
|-----------------|--------------------------------------------------------------------------|
|`judgment`       |You are deciding architecture, reviewing trade-offs, advising on direction|
|`execution`      |You are implementing a defined solution                                   |
|`knowledge-build`|You are learning or researching to deepen your expertise                  |
|`relationship`   |You are investing in a stakeholder relationship                           |
|`admin`          |Necessary overhead — meetings, documentation, process                     |
|`misaligned`     |This should not be here — flag for retrospective                          |

-----

## Sprint Review Questions (end of sprint)

**Value delivered:**

- What Core Pain Point did I solve this sprint?
- Did I work on tasks or on problems?
- Were my architectural recommendations acted on?

**Practice health:**

- What % of completed work was `judgment` vs `execution`?
- Did I produce any ADRs or lasting architectural artifacts?
- Was I consulted before or after key decisions during this sprint?
- Did I add anything new to `note-management` from this sprint’s learning?

**Retrospective trigger:**

- Was there anything `misaligned` in this sprint? How did it get there?
- What would I decline or reframe if offered again?

-----

## Sprint Retrospective — Architect Practice Addition

Add these questions to your standard sprint retrospective:

|Question                                |Answer                        |
|----------------------------------------|------------------------------|
|% of sprint that was `judgment` work    |___%                          |
|% of sprint that was `execution` work   |___%                          |
|Were recommendations acted on?          |Yes / Partially / No          |
|ADRs produced this sprint               |___                           |
|Consulted before or after key decisions?|Before / After / Not consulted|
|Items that were `misaligned`            |List:                         |
|One thing to change next sprint         |                              |

-----

## Links Across the Hierarchy

|Direction|Level          |Document                                                                                                                         |
|---------|---------------|---------------------------------------------------------------------------------------------------------------------------------|
|↑ Up     |Sprint Planning|[`ARCHITECT_VALUE_MODEL.md`](https://github.com/vanHeemstraSystems/sprint-planning-management/blob/main/ARCHITECT_VALUE_MODEL.md)|
|↓ Down   |Task Execution |[`ARCHITECT_VALUE_MODEL.md`](https://github.com/vanHeemstraSystems/task-management/blob/main/ARCHITECT_VALUE_MODEL.md)           |
