# What is Infrastructure as Code ?

## Introduction

- Master the **Principles**, **Practices**, and **Patterns**
- ***Principle***: A rule that helps you choose between potential solutions
- ***Practice***: A practice is a way of implementing something. Your should use principles to guide you in choosing the most appropriate practice for a given situation.
- ***Pattern***: A pattern is a potential solution to a problem. Each pattern is describe in a format that should help you evaluate its relevance for your problem.
- Using code to define and build infrastructure creates the opportunity to bring a wide set of tools, practices, and patterns to bear on the problem of designing and implementing systems.
- We want to build infrastructure that can continually evolve to meet changing requirements

 ### Infrastructure as Code
 - ***Infrastructure as Code*** is the practice of provisionig and managing infrastructure using code rather than command-line tools or ClickOps GUIs.
 - Infrastructure as Code is more than the mechanics of how infrastructure is defined and provisioned.


### From the Iron Age to the Cloud Age
Table 1-1. Technoloy changes in the Cloud Age
|                      | Iron Age             | Cloud Age                  |
|:-------------------- |:---------------------|:---------------------------|
| Types of resources   | Physical hardware    | Virtualized resources      |
| Types of resources   | Takes days or weeks  | Take minutes or seconds    |
| Processes            | Manual(runbook)      | Virtualized resources      |
|                      |                      |                            |

Table 1-2. Ways of working in the Iron Age and the Cloud Age
|                      |            Iron Age                      |           Cloud Age                |
|:-------------------- |:-----------------------------------------|:-----------------------------------|
| Cost of change       | High                                     | Low                                |
| Changes are          | Risk to be minimized                     | Essential to improve quality       |
| Optimize to          | Reduced opportunities to failed          | Maximize speed of improvement      |
| Delivery approach    | Large batches, test at end               | Small changes, test continually    |
| Archiectures         | Monolithic (fewer, larger moving parts)  | Microservices(more, smaller parts) |
|                      |                                          |                                    |

- **DevOps** is, first and foremost, about people,culture and ways of working. Tools and practices like Infrastructure as Code are vaiablue to the extent that they bridge gaps and improve collaboration, but they aren't enough.

![The path from the Iron Age to the Cloud Age](./Chap-01-assets/Figure-1-1.png)
Figure 1-1. The path from the Iron Age to the Cloud Age