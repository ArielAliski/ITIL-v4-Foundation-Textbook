# ITIL Foundation: A Complete Learning Textbook
### Your Practical Guide to IT Service Management — Refreshed and Ready to Implement

---

> **Who this book is for:** This textbook is written for someone who has previously studied ITIL Foundation and needs a clear, structured refresher — not just theory, but real guidance on how to apply these concepts at work.
>
> **How to use this book:** Read it chapter by chapter as a refresher, or jump directly to a concept you want to revisit. Each chapter ends with an *Implementation in Practice* section so you can immediately connect theory to your daily work.

---

## Table of Contents

1. Chapter 1: What is ITIL and Why It Matters
2. Chapter 2: Key Concepts of Service Management
3. Chapter 3: The Four Dimensions of Service Management
4. Chapter 4: The ITIL Service Value System (SVS)
5. Chapter 5: The Seven Guiding Principles
6. Chapter 6: The Service Value Chain
7. Chapter 7: Continual Improvement
8. Chapter 8: ITIL Management Practices — The 34 Practices
9. Chapter 9: Deep Dive — The Key Practices You Must Know
10. Chapter 10: Implementing ITIL at the Foundational Level
11. Chapter 11: ITIL in Projects — A Practical Bridge
12. Chapter 12: Common Mistakes and How to Avoid Them
13. Quick Reference Cheat Sheet

---

# Chapter 1: What is ITIL and Why It Matters

---

## 1.1 The Short Answer

ITIL stands for **Information Technology Infrastructure Library**. It is a framework — a set of best practices — for managing IT services so that they actually deliver value to businesses and their customers.

Think of ITIL not as a rigid rulebook, but as a **body of professional wisdom** accumulated from thousands of organizations around the world. It tells you: *here is what tends to work when you are trying to run IT services well.*

The version you studied and this book covers is **ITIL 4**, which was released in 2019. ITIL 4 is a significant evolution from ITIL v3. Where ITIL v3 was very process-focused and somewhat rigid, ITIL 4 is more holistic, flexible, and designed to work alongside modern approaches like Agile, DevOps, and Lean.

---

## 1.2 Why Do Organizations Use ITIL?

Without a framework, IT departments tend to operate in chaos. Consider these common problems:

- Every team handles incidents differently, so resolution times are unpredictable
- New systems are deployed without proper testing or change controls, causing outages
- Users never know who to contact or what to expect when something breaks
- IT focuses on technology rather than on what the business actually needs

ITIL solves these problems by giving organizations a **common language**, **shared practices**, and a **system of thinking** that aligns IT with business value.

**The core promise of ITIL is this:** *IT exists to create value for the business. Everything IT does should contribute to that value.*

---

## 1.3 ITIL 4 vs. ITIL v3 — What Changed?

If you studied ITIL v3 at some point, here is the key difference:

| Aspect | ITIL v3 | ITIL 4 |
|---|---|---|
| Core focus | Processes and lifecycle | Value, systems, and practices |
| Structure | Service Lifecycle (5 phases) | Service Value System (SVS) |
| Terminology | Processes | Practices |
| Approach | Prescriptive | Flexible and principles-based |
| Modern alignment | Limited | Built for Agile, DevOps, Lean |

ITIL 4 does not throw away what ITIL v3 taught us. It **builds on it** and puts it in a more modern context. If you remember processes like Incident Management or Change Management from v3, they still exist in ITIL 4 — but now they are called **practices**, and they sit within a broader framework called the **Service Value System**.

---

## 1.4 The ITIL Certification Path (Context for Foundation)

The ITIL 4 certification scheme has several levels:

```
ITIL 4 Foundation
        |
    ITIL 4 Managing Professional (MP)
    ITIL 4 Strategic Leader (SL)
        |
    ITIL 4 Master
```

**Foundation** is the entry point. It gives you:

- The vocabulary and concepts
- An understanding of the framework as a whole
- A shared language to communicate with other ITIL practitioners

Foundation does **not** make you an ITIL implementer on its own. But it gives you the conceptual map that all higher levels build upon — and it is entirely sufficient to start improving IT service delivery in your organization.

---

# Chapter 2: Key Concepts of Service Management

---

## 2.1 Why Definitions Matter in ITIL

ITIL has very specific definitions for common words. This might feel pedantic at first, but precision in language is what allows teams across an organization — and across organizations worldwide — to communicate without confusion.

In this chapter, we will walk through the foundational vocabulary of ITIL 4.

---

## 2.2 Service

**Definition:** *A means of enabling value co-creation by facilitating outcomes that customers want to achieve, without the customer having to manage specific costs and risks.*

Let us break that down into plain English.

A **service** is something you provide to a customer that:
1. Helps them achieve something they want (an outcome)
2. Without them needing to deal with the complicated or costly bits themselves

**Example:** When a bank offers online banking, you (the customer) can transfer money, check balances, and pay bills. You achieve the *outcome* you want (managing your finances) without having to buy, run, or maintain the banking infrastructure yourself. That is the service.

**The key insight:** A service is not about the technology. It is about the *value* the customer receives. ITIL constantly pushes you to think from the customer's perspective.

---

## 2.3 Value

**Definition:** *The perceived benefits, usefulness, and importance of something.*

Value is **subjective and co-created**. This is one of the most important insights in ITIL 4.

Value is not created by the service provider alone. It is created **together** — by the provider and the customer working in combination. A great IT system sitting unused creates no value. Value only emerges when the customer actually uses the service to achieve something.

This is why ITIL 4 uses the phrase **value co-creation** frequently.

**Example:** An HR self-service portal (the service) only creates value when:
- The IT team provides a well-designed, reliable system (provider's contribution)
- The employee actually uses it to submit leave requests (customer's contribution)

---

## 2.4 Utility and Warranty

These two concepts together describe what makes a service valuable. Think of them as the **two tests** every service must pass.

### Utility — "Fit for Purpose"

Utility is about **what the service does**. Does it do the job it is supposed to do?

- Does it have the features the customer needs?
- Does it remove constraints that were limiting the customer?
- Does it help the customer achieve their desired outcomes?

**Analogy:** A car is "fit for purpose" if it can drive from A to B and carry passengers. If it cannot move, it fails the utility test.

### Warranty — "Fit for Use"

Warranty is about **how well the service performs**. Does it work reliably enough to be usable?

Warranty covers four areas:
- **Availability** — Is the service available when needed?
- **Capacity** — Can it handle the workload required?
- **Continuity** — Can it recover quickly if something goes wrong?
- **Security** — Is it safe from threats and breaches?

**Analogy:** A car that *can* drive but breaks down every 10km has good utility but poor warranty. You would not rely on it.

**The rule:** A service needs **both** utility and warranty to deliver value. A service that does the right thing but breaks all the time is not valuable. A service that is rock-solid reliable but does the wrong thing is equally useless.

---

## 2.5 Outcome vs. Output

These two words are easy to confuse but critically different in ITIL.

| Term | Definition | Example |
|---|---|---|
| **Output** | A tangible or intangible deliverable produced by an activity | A report, a deployed software feature, a fixed server |
| **Outcome** | A result for a stakeholder enabled by one or more outputs | A manager makes better decisions (because of the report) |

**Why does this matter?** IT teams are tempted to measure and celebrate outputs ("we deployed 50 features this month"). But what the business cares about is outcomes ("our sales team can now process orders 30% faster").

ITIL trains you to think in outcomes. Outputs are means to an end. Outcomes are the end.

---

## 2.6 Cost

In ITIL, cost is considered from the customer's perspective.

A service affects a customer's costs in two ways:

1. **Costs removed from the customer** — The service takes over something the customer would otherwise have to do themselves (a cost they are relieved of)
2. **Costs imposed on the customer** — The price the customer pays for the service (subscription fee, licensing costs, etc.)

For value to be created, the costs removed must be perceived as greater than the costs imposed.

**Example:** A cloud email service (like Gmail for Business) removes the cost of running your own mail servers while imposing a monthly per-user fee. If the fee is reasonable, value is created.

---

## 2.7 Risk

Similar to cost, ITIL thinks about risk from the customer's perspective:

1. **Risks removed from the customer** — The service absorbs risks the customer would otherwise face (data loss, system failure, etc.)
2. **Risks imposed on the customer** — New risks introduced by using the service (vendor lock-in, data privacy concerns, service outage from the provider)

For value to be created, the risks removed must be perceived as greater than the risks imposed.

---

## 2.8 Organizations and People

ITIL defines an **organization** as a person or group of people that has its own functions with responsibilities, authorities, and relationships to achieve its objectives.

Organizations can be of any size — a single-person business or a multinational corporation.

### Key Roles in Service Relationships

**Service Provider** — The organization that provides the service.

**Service Consumer** — The organization or person that receives the service. There are three sub-roles within the consumer:

| Role | Who They Are | Example |
|---|---|---|
| **Customer** | Defines the requirements and is responsible for the outcomes | The HR Director who commissions an HR system |
| **User** | Uses the service directly | The employees who use the HR system daily |
| **Sponsor** | Authorizes the budget for the service | The CFO who approves the purchase |

> **In practice, these roles can overlap.** A small business owner might be the customer, user, and sponsor all at once.

---

## 2.9 Service Relationship

A **service relationship** exists when two organizations work together to co-create value.

Service relationships include three components:

1. **Service provision** — Activities performed by the service provider to deliver the service
2. **Service consumption** — Activities performed by the service consumer to consume the service
3. **Service relationship management** — Joint activities performed by both parties to ensure ongoing value creation

---

## 2.10 Products and Services

A **product** is a configuration of an organization's resources designed to offer value to a consumer.

A **service** is built from one or more products.

**Example:** Microsoft 365 is a product. The email service, the Teams collaboration service, and the SharePoint intranet service are all individual services built from that product.

---

# Chapter 3: The Four Dimensions of Service Management

---

## 3.1 Overview

Every service, every practice, and every system in ITIL must be viewed through four dimensions. These four dimensions ensure a **holistic approach** — meaning you cannot ignore any one of them without risking failure.

Think of the four dimensions as four different lenses you must look through when designing, delivering, or improving any service.

The four dimensions are:

1. Organizations and People
2. Information and Technology
3. Partners and Suppliers
4. Value Streams and Processes

An important note: All four dimensions are **influenced by external factors** such as political, economic, social, technological, legal, and environmental (PESTLE) factors that are outside the organization's control.

---

## 3.2 Dimension 1: Organizations and People

**What it covers:** The formal structure of the organization, roles and responsibilities, culture, leadership, and how people work together.

This dimension is often the most neglected in IT projects — teams spend vast energy on technology and processes, but forget that humans are the ones running everything.

**Key questions this dimension asks:**
- Do people have clearly defined roles and responsibilities?
- Is there a culture that supports collaboration and continuous improvement?
- Does leadership actively support good service management?
- Do teams have the right skills and competencies?

**Why it matters:** The best-designed process fails if the people running it are confused about their roles, lack the skills, or work in a culture that does not support the process.

**Real-world example:** An organization implements a formal incident management process. But if the IT team culture is "everyone handles their own incidents however they want," the process will not be followed, no matter how well it is documented.

---

## 3.3 Dimension 2: Information and Technology

**What it covers:** The information and knowledge required to manage services, and the technologies that support service delivery and management.

This includes:
- The applications and tools used to deliver services
- The data and information needed to manage and improve services
- Knowledge bases, configuration databases, and documentation
- The technology infrastructure itself (cloud, servers, networks)
- AI, automation, and machine learning capabilities

**Key questions this dimension asks:**
- What information is needed to manage this service effectively?
- Is the information accessible, accurate, and secure?
- What technology supports service delivery and management?
- Is the technology resilient and scalable enough?

**Why it matters:** Good services depend on good information. You cannot manage what you do not measure, and you cannot improve what you do not understand.

---

## 3.4 Dimension 3: Partners and Suppliers

**What it covers:** The organization's relationships with other organizations that are involved in the design, development, deployment, delivery, support, and improvement of services.

Almost no IT service is delivered entirely in-house. Organizations rely on:
- **Partners** — Organizations that work closely with you, often sharing goals and risks
- **Suppliers** — Organizations that provide goods or services under contract (e.g., cloud providers, hardware vendors, software vendors)

**Key questions this dimension asks:**
- Which activities should we do ourselves vs. outsource?
- How do we manage and monitor supplier performance?
- What are the contractual obligations on both sides?
- What risks does our reliance on external parties introduce?

**Why it matters:** A failure in your supplier can become your problem. If your cloud provider goes down, your users do not care whose fault it is — they care that the service is down.

---

## 3.5 Dimension 4: Value Streams and Processes

**What it covers:** The activities, workflows, controls, and procedures needed to achieve the organization's objectives.

A **value stream** is a series of steps an organization uses to create and deliver products and services to a service consumer.

A **process** is a set of interrelated or interacting activities that transform inputs into outputs.

**Key questions this dimension asks:**
- What steps are required to deliver this service?
- Which activities add value and which are waste?
- How do we ensure processes are efficient and effective?
- Are our workflows clearly defined and consistently followed?

**Why it matters:** Poor processes lead to inconsistency, errors, and wasted effort. Well-designed value streams ensure that every step moves the service closer to delivering value.

---

## 3.6 The PESTLE Factors

All four dimensions are affected by external forces that are largely outside the organization's control:

| Factor | Examples |
|---|---|
| **Political** | Government regulations, international trade policies |
| **Economic** | Economic downturns, currency fluctuations, market conditions |
| **Social** | Changing workforce expectations, remote work trends, user behavior |
| **Technological** | Emerging technologies, cybersecurity threats, cloud evolution |
| **Legal** | Data privacy laws (GDPR), industry regulations, compliance requirements |
| **Environmental** | Sustainability requirements, energy regulations, climate events |

These factors can create **constraints** (things you cannot avoid) or **opportunities** (things you can take advantage of).

---

## 3.7 Implementation in Practice: Using the Four Dimensions

When you start a new project or redesign a service, run through each dimension as a checklist:

**Organizations and People:**
- Have you defined who owns this service?
- Do team members know their roles?
- Is leadership aligned and supportive?

**Information and Technology:**
- What data will you need to manage this service?
- What tools do you need?
- Is your technology sufficient and secure?

**Partners and Suppliers:**
- Are you relying on any external parties?
- Have you reviewed their contracts and SLAs?
- What are your contingency plans if they fail?

**Value Streams and Processes:**
- Have you mapped the end-to-end process?
- Where are the bottlenecks or waste?
- How will you measure if the process is working?

---

# Chapter 4: The ITIL Service Value System (SVS)

---

## 4.1 What is the SVS?

The **Service Value System (SVS)** is the central model of ITIL 4. It describes how all the components and activities of an organization work together to enable value creation.

Think of the SVS as the **big picture** — the overall architecture of how IT service management works.

The SVS has five components:

1. Guiding Principles
2. Governance
3. Service Value Chain
4. Practices
5. Continual Improvement

And it has **two things on either side**:
- **Input:** Opportunity and Demand (the triggers that set things in motion)
- **Output:** Value (what the SVS produces)

---

## 4.2 The SVS in a Diagram (Text Version)

```
┌─────────────────────────────────────────────────────────────┐
│           OPPORTUNITY AND DEMAND (Input)                    │
└─────────────────────────────┬───────────────────────────────┘
                              │
┌─────────────────────────────▼───────────────────────────────┐
│                    SERVICE VALUE SYSTEM                      │
│                                                             │
│  ┌──────────────────────────────────────────────────────┐   │
│  │              GUIDING PRINCIPLES                      │   │
│  └──────────────────────────────────────────────────────┘   │
│                                                             │
│  ┌──────────────┐   ┌──────────────────────┐   ┌────────┐  │
│  │  GOVERNANCE  │   │  SERVICE VALUE CHAIN  │   │PRACTICES│  │
│  └──────────────┘   └──────────────────────┘   └────────┘  │
│                                                             │
│  ┌──────────────────────────────────────────────────────┐   │
│  │           CONTINUAL IMPROVEMENT                      │   │
│  └──────────────────────────────────────────────────────┘   │
│                                                             │
└─────────────────────────────┬───────────────────────────────┘
                              │
┌─────────────────────────────▼───────────────────────────────┐
│                      VALUE (Output)                         │
└─────────────────────────────────────────────────────────────┘
```

---

## 4.3 Opportunity and Demand (The Inputs)

**Opportunity** represents possibilities to add value for stakeholders or otherwise improve the organization. It is about potential.

**Demand** represents the need or desire for products and services among internal and external consumers. It is about what people are asking for.

These are the **triggers** that set the SVS in motion. Without demand or opportunity, the system has nothing to respond to.

**Example:**
- A new regulation requiring better data security = **Opportunity** (to build a better security practice) and **Demand** (for a compliance-enabling service)
- Users complaining about slow file-sharing = **Demand** (for a better solution)
- Emergence of AI tools = **Opportunity** (to automate and improve services)

---

## 4.4 Governance

**Governance** is the means by which an organization is directed and controlled.

In ITIL, governance sits above everything else. It ensures that:
- The organization's activities are aligned with its goals and values
- Policies and accountability structures are in place
- Decisions are made at the right level by the right people

Governance is the responsibility of the organization's **governing body** (the board, executive leadership, etc.). It is distinct from *management*, which is the day-to-day operation of services.

**The difference:**
- Governance = *What* we should be doing and *why* (strategic direction)
- Management = *How* we do it (operational execution)

---

## 4.5 Practices

**Practices** are sets of organizational resources designed for performing work or accomplishing an objective.

ITIL 4 defines **34 management practices** organized into three categories:

| Category | Number of Practices | Focus |
|---|---|---|
| General Management Practices | 14 | Broad organizational management |
| Service Management Practices | 17 | IT service delivery and management |
| Technical Management Practices | 3 | Technology management |

We cover all 34 practices in Chapter 8 and deep-dive the most important ones in Chapter 9.

---

## 4.6 Why the SVS is Designed This Way

The SVS is built around a key insight: **you cannot improve one component in isolation**. Real-world service management problems are almost never caused by a single broken process. They are caused by misalignment between multiple components.

**Example:** If incident resolution times are poor:
- Is it the process (Value Streams and Processes dimension)?
- Is it the tools (Information and Technology dimension)?
- Is it unclear roles (Organizations and People dimension)?
- Is it missing skills (Organizations and People dimension)?
- Is it a supplier problem (Partners and Suppliers dimension)?

The SVS encourages you to look at the whole system, not just one part.

---

# Chapter 5: The Seven Guiding Principles

---

## 5.1 What Are the Guiding Principles?

The seven guiding principles are the **core recommendations** that guide organizations in all circumstances, regardless of changes in goals, strategies, type of work, or management structure.

They are not rules you must follow rigidly. They are **principles you apply with judgment**, depending on what is appropriate for your situation.

They are also **universal** — they apply at every level, from a junior technician to a CIO, and in every type of organization.

---

## 5.2 The Seven Guiding Principles

### Principle 1: Focus on Value

**What it means:** Everything the organization does must link, directly or indirectly, to value for itself, its customers, and other stakeholders.

Before doing any activity, ask: *Who benefits from this? What value does this create?*

**In practice:**
- Before building a new feature, ask: "Which user outcome does this enable?"
- Before creating a report, ask: "Who uses this and what decision does it help them make?"
- Map every IT service back to a business outcome

**Common violation:** IT teams working on projects that no one will use because they never validated the business need.

---

### Principle 2: Start Where You Are

**What it means:** Do not start from scratch if something already exists that can be built upon. Always assess and evaluate the current state before designing something new.

**In practice:**
- When improving a process, start by documenting and evaluating what exists
- Identify what is working well and preserve it
- Look for reusable assets: tools, processes, skills, relationships

**Common violation:** Launching a brand-new ITSM tool and throwing away years of process maturity because "we want to start fresh."

**Helpful question:** "What do we already have that is useful here?"

---

### Principle 3: Progress Iteratively with Feedback

**What it means:** Do not try to do everything at once. Break work into smaller iterations. Use feedback after each iteration to improve the next one.

This principle is heavily influenced by Agile and Lean thinking.

**In practice:**
- Instead of a 12-month IT transformation, break it into 3-month sprints
- After each iteration, gather feedback: What worked? What did not?
- Adjust the next iteration based on what you learned

**Why this matters:** Large, slow projects often fail because requirements change, technology evolves, or the team loses momentum. Small, fast iterations reduce the risk of failure and allow course correction.

---

### Principle 4: Collaborate and Promote Visibility

**What it means:** Work together across boundaries — within IT teams, between IT and the business, and with external partners. Make work visible and information accessible.

**In practice:**
- Do not solve problems in silos; involve stakeholders from different teams
- Use shared dashboards so everyone can see service status
- Document decisions and share them openly
- Involve end-users in designing services that affect them

**Why it matters:** Hidden work leads to duplication, miscommunication, and poor decisions. When work is visible, problems are caught earlier and solutions are better.

---

### Principle 5: Think and Work Holistically

**What it means:** No service, practice, or component operates in isolation. Consider the end-to-end system and how your actions affect the whole.

**In practice:**
- When implementing a change, think about downstream effects
- When solving an incident, consider whether it is a symptom of a larger problem
- Connect IT strategy with business strategy

**Common violation:** A database team optimizes their database without considering the impact on the application layer, causing a bottleneck elsewhere.

---

### Principle 6: Keep It Simple and Practical

**What it means:** Use the minimum number of steps to accomplish an objective. Eliminate anything that does not add value.

**In practice:**
- Challenge every process step: "What would happen if we removed this?"
- Avoid over-engineering solutions
- Do not add complexity "just in case"
- Simplify approval chains, documentation requirements, and workflows

**A helpful test:** If you cannot explain why a step exists, it probably should not.

**Common violation:** A change management process that requires 14 approvals for a minor configuration change, causing IT to work around the process entirely.

---

### Principle 7: Optimize and Automate

**What it means:** Make things as efficient as possible before automating them. Automating a bad process just makes the bad process run faster.

**The order matters:**
1. First, understand the current process
2. Then, optimize it (simplify, eliminate waste)
3. Only then, automate the optimized version

**In practice:**
- Map your value streams and eliminate waste first
- Use automation for repetitive, low-judgment tasks (password resets, ticket routing, monitoring alerts)
- Reserve human judgment for complex, high-stakes decisions

**Common violation:** Automating a broken ticketing workflow and discovering the automation now creates 1000 incorrect tickets per hour instead of 10.

---

## 5.3 How the Principles Work Together

The guiding principles are not used in isolation. They are meant to be applied together, with judgment about which ones are most relevant in a given situation.

**Example scenario:** You are asked to redesign the incident management process.

- *Start where you are* → Review the existing process first
- *Focus on value* → Understand what "good" looks like from the user's perspective
- *Collaborate and promote visibility* → Involve the service desk team and business users
- *Progress iteratively with feedback* → Pilot the new process with one team first
- *Keep it simple and practical* → Remove unnecessary escalation steps
- *Optimize and automate* → Automate ticket routing for common issue categories
- *Think and work holistically* → Ensure the new process integrates with problem and change management

---

# Chapter 6: The Service Value Chain

---

## 6.1 What is the Service Value Chain?

The **Service Value Chain (SVC)** is the operating model that sits at the heart of the SVS. It shows how the various activities of an organization combine to create value.

Think of it as the **engine** inside the SVS. It takes inputs (demand, opportunity) and transforms them through a series of interconnected activities to produce outputs (value).

---

## 6.2 The Six Activities of the Service Value Chain

The SVC has six activities:

1. **Plan**
2. **Improve**
3. **Engage**
4. **Design and Transition**
5. **Obtain/Build**
6. **Deliver and Support**

These activities are not a linear sequence like a waterfall process. They are **interconnected** — the output of one activity can be the input of another. In real organizations, multiple value streams flow through these activities simultaneously.

---

## 6.3 Each Activity Explained

### Plan

**Purpose:** Ensure a shared understanding of the vision, current status, and improvement direction for all four dimensions and all products and services across the organization.

**What it produces:** Policies, portfolios, architectures, and plans.

**In plain English:** The "Plan" activity is about setting direction and making strategic decisions. Before you do anything, you need a plan.

**Examples of what happens in Plan:**
- Defining the IT strategy
- Creating a roadmap for service improvement
- Setting service management policies

---

### Improve

**Purpose:** Ensure continual improvement of products, services, and practices across all value chain activities and all four dimensions of service management.

**What it produces:** Improvement initiatives, initiatives outcomes, and improvement reports.

**In plain English:** The "Improve" activity runs continuously alongside everything else. It is the organizational habit of getting better over time.

**Examples of what happens in Improve:**
- Identifying root causes of recurring incidents
- Reviewing and updating processes
- Running post-implementation reviews

---

### Engage

**Purpose:** Provide a good understanding of stakeholder needs, transparency, continual engagement, and good relationships with all stakeholders.

**What it produces:** Consolidated demands and opportunities, and service performance reports.

**In plain English:** The "Engage" activity is about communication and relationships — with customers, users, partners, and stakeholders. It is how you understand what people need.

**Examples of what happens in Engage:**
- Meeting with business stakeholders to understand needs
- Managing customer complaints
- Communicating service outages
- Conducting user satisfaction surveys

---

### Design and Transition

**Purpose:** Ensure that products and services continually meet stakeholder expectations for quality, costs, and time to market.

**What it produces:** Requirements and specifications, contracts and agreements, service components, and knowledge/information.

**In plain English:** The "Design and Transition" activity covers the design of services and their transition into live operation. This is where you build the blueprint and prepare for deployment.

**Examples of what happens in Design and Transition:**
- Designing a new service architecture
- Creating a deployment plan
- Testing changes before they go live
- Training users before a new system launches

---

### Obtain/Build

**Purpose:** Ensure service components are available when and where they are needed, and meet agreed specifications.

**What it produces:** Service components.

**In plain English:** The "Obtain/Build" activity is where things are actually created or procured. If you are building software, it is written here. If you are buying hardware, it is purchased here.

**Examples of what happens in Obtain/Build:**
- Developing software
- Purchasing hardware
- Deploying a cloud environment
- Configuring systems

---

### Deliver and Support

**Purpose:** Ensure services are delivered and supported according to agreed specifications and stakeholder expectations.

**What it produces:** Services delivered to customers and users, and support task completion.

**In plain English:** The "Deliver and Support" activity is the day-to-day operation of services. This is what your service desk, operations team, and support teams are doing every single day.

**Examples of what happens in Deliver and Support:**
- Resolving incidents
- Handling service requests
- Monitoring service availability
- Supporting users with problems

---

## 6.4 Value Streams

A **value stream** is a specific combination of the SVC activities, flowing in a particular sequence to deliver a particular service or respond to a particular situation.

Think of value streams as **recipes** — they tell you which ingredients (SVC activities) to combine, and in what order, to produce a specific outcome.

**Example Value Stream — Resolving a User Incident:**

```
Engage → Deliver and Support → Improve
```

1. **Engage:** User contacts the service desk and reports an issue
2. **Deliver and Support:** The service desk diagnoses and resolves the incident
3. **Improve:** The incident is logged and analyzed for patterns; improvements are made

**Example Value Stream — Deploying a New Application:**

```
Engage → Plan → Design and Transition → Obtain/Build → Deliver and Support → Improve
```

1. **Engage:** Business team requests a new application
2. **Plan:** IT strategy team aligns the request with the portfolio
3. **Design and Transition:** Architects design the solution; a deployment plan is created
4. **Obtain/Build:** Developers build and test the application
5. **Deliver and Support:** Application is deployed and handed to operations
6. **Improve:** Post-implementation review identifies lessons learned

---

# Chapter 7: Continual Improvement

---

## 7.1 What is Continual Improvement?

**Continual Improvement** is the ITIL practice (and SVS component) that ensures the organization never stops getting better. It is embedded in the SVS as both an activity in the Service Value Chain **and** as a standalone practice.

The word "continual" is deliberate — it means improvement is always happening, not in occasional bursts. It is a **habit and culture**, not a one-time project.

---

## 7.2 The Continual Improvement Model

ITIL provides a seven-step model to guide improvement efforts. You can apply this model to any improvement initiative, large or small.

### Step 1: What is the Vision?

Start with the big picture. What is the organization trying to achieve? What do stakeholders value?

*"Where do we want to be in the long term?"*

### Step 2: Where Are We Now?

Assess the current state honestly. Use data, observation, and stakeholder feedback. Do not assume.

*"What is the current baseline?"*

### Step 3: Where Do We Want to Be?

Define measurable improvement targets. Be specific. "Better" is not a target. "Reduce average incident resolution time from 4 hours to 2 hours within 6 months" is a target.

*"What measurable improvement do we want to achieve?"*

### Step 4: How Do We Get There?

Design the improvement plan. What actions are needed? Who is responsible? What resources are required?

*"What is our plan?"*

### Step 5: Take Action

Execute the plan. Do it iteratively — do not wait until everything is perfect.

*"Do the work."*

### Step 6: Did We Get There?

Measure the results. Compare actual outcomes to the targets you set in Step 3.

*"Did we achieve what we intended?"*

### Step 7: How Do We Keep the Momentum Going?

Embed the improvements into the organization. Prevent regression. Use lessons learned to feed into the next improvement cycle.

*"How do we ensure this improvement sticks and becomes the new baseline?"*

---

## 7.3 The Continual Improvement Register

A **Continual Improvement Register (CIR)** is a documented list of improvement opportunities and initiatives. Every organization practicing ITIL should maintain one.

The CIR:
- Captures improvement ideas from anywhere in the organization
- Prioritizes them based on impact and effort
- Tracks their status and outcomes

**Think of the CIR as a living backlog of "make things better" ideas.** Anyone can contribute to it. A developer who notices a recurring error, a service desk agent who sees the same user complaint repeatedly, a manager who spots an efficiency gap — all of these can (and should) be captured in the CIR.

---

## 7.4 Improvement at Every Level

Continual Improvement does not only apply to processes. It applies to:

- **Services** — Is the service still meeting user needs?
- **Practices** — Are our processes efficient and effective?
- **Technology** — Is our tooling still appropriate?
- **People** — Are team members developing their skills?
- **Culture** — Are we becoming more collaborative and value-focused?
- **Governance** — Are our policies keeping up with the organization's evolution?

---

# Chapter 8: ITIL Management Practices — All 34

---

## 8.1 What is a Practice?

A **practice** is a set of organizational resources designed for performing work or accomplishing an objective.

The key word is *resources* — a practice is not just a process. It includes:
- People (roles, skills, culture)
- Information and technology (tools, data)
- Partners and suppliers
- Value streams and processes

This is why ITIL 4 uses "practices" rather than "processes" — it is a deliberate broadening of scope.

---

## 8.2 The Three Categories of Practices

### Category 1: General Management Practices (14)

These are practices adapted from broader business management domains for use in service management.

| # | Practice | Brief Description |
|---|---|---|
| 1 | Architecture Management | Provides a comprehensive understanding of all elements of an organization and their inter-relationships |
| 2 | Continual Improvement | Aligning the organization's practices and services with changing business needs through ongoing identification and improvement |
| 3 | Information Security Management | Protecting the organization's information, handling confidentiality, integrity, and availability |
| 4 | Knowledge Management | Maintaining and improving the effective, efficient, and convenient use of information and knowledge |
| 5 | Measurement and Reporting | Supports good decision-making and continual improvement by decreasing levels of uncertainty |
| 6 | Organizational Change Management | Ensures changes in the organization are implemented smoothly and successfully |
| 7 | Portfolio Management | Ensures the organization has the right mix of programs, projects, products, and services to execute its strategy |
| 8 | Project Management | Ensures all projects are successfully delivered |
| 9 | Relationship Management | Establishes and nurtures links between the organization and its stakeholders |
| 10 | Risk Management | Ensures the organization understands and effectively handles risks |
| 11 | Service Financial Management | Supports the organization's strategies and plans for service management by ensuring the organization's financial resources and investments are being used effectively |
| 12 | Strategy Management | Defines and pursues the organization's direction |
| 13 | Supplier Management | Ensures the organization's suppliers and their performances are managed appropriately |
| 14 | Workforce and Talent Management | Ensures the organization has the right people with the appropriate skills and knowledge |

---

### Category 2: Service Management Practices (17)

These are practices specifically developed for the service management domain.

| # | Practice | Brief Description |
|---|---|---|
| 1 | Availability Management | Ensures services deliver agreed levels of availability to meet the needs of customers and users |
| 2 | Business Analysis | Analyzes business needs and recommends solutions to business problems |
| 3 | Capacity and Performance Management | Ensures services achieve agreed and expected performance levels |
| 4 | Change Enablement | Maximizes the number of successful IT changes by ensuring risks have been properly assessed, authorizing changes to proceed, and managing the change schedule |
| 5 | Incident Management | Minimizes the negative impact of incidents by restoring normal service operation as quickly as possible |
| 6 | IT Asset Management | Plans and manages the full lifecycle of all IT assets |
| 7 | Monitoring and Event Management | Systematically observes services and service components, and records and reports selected changes of state |
| 8 | Problem Management | Reduces the likelihood and impact of incidents by identifying actual and potential causes, and managing workarounds and known errors |
| 9 | Release Management | Makes new and changed services and features available for use |
| 10 | Service Catalogue Management | Provides a single source of consistent information on all services and service offerings |
| 11 | Service Configuration Management | Ensures accurate and reliable information about the configuration of services and supporting components is available |
| 12 | Service Continuity Management | Ensures that service availability and performance is maintained at sufficient levels in the event of a disaster |
| 13 | Service Design | Designs products and services that are fit for purpose and use |
| 14 | Service Desk | Captures demand for incident resolution and service requests, and is the entry point and single point of contact for users |
| 15 | Service Level Management | Sets clear business-based targets for service levels and ensures delivery of services is properly assessed, monitored, and managed against these targets |
| 16 | Service Request Management | Supports the agreed quality of a service by handling all pre-defined, user-initiated service requests in an effective and user-friendly manner |
| 17 | Service Validation and Testing | Ensures new or changed products and services meet defined requirements |

---

### Category 3: Technical Management Practices (3)

These are practices adapted from technology management domains for use in service management.

| # | Practice | Brief Description |
|---|---|---|
| 1 | Deployment Management | Moves new or changed hardware, software, documentation, processes, or any other component to live environments |
| 2 | Infrastructure and Platform Management | Oversees the infrastructure and platforms used by an organization |
| 3 | Software Development and Management | Ensures applications meet internal and external stakeholder needs in terms of functionality, reliability, maintainability, compliance, and auditability |

---

# Chapter 9: Deep Dive — The Key Practices You Must Know

---

## 9.1 Why These Practices?

For ITIL Foundation, you need to understand **all 34 practices** at a high level, but you need **deeper knowledge** of the following practices, as they are most commonly tested and most critical for practical implementation:

1. Continual Improvement
2. Change Enablement
3. Incident Management
4. Problem Management
5. Service Desk
6. Service Level Management
7. Service Request Management
8. IT Asset Management
9. Monitoring and Event Management
10. Release Management
11. Service Configuration Management
12. Deployment Management

---

## 9.2 Change Enablement (formerly Change Management)

### Purpose
To maximize the number of successful IT changes by ensuring risks have been properly assessed, authorizing changes to proceed, and managing the change schedule.

### What is a Change?
A **change** is the addition, modification, or removal of anything that could have a direct or indirect effect on services.

### Types of Changes

**Standard Change**
- Pre-authorized, low-risk, well-understood
- Follows a documented procedure with no need for individual approval each time
- Examples: Installing standard software, resetting passwords, adding a user to a distribution list
- Fastest to process — no approval delay

**Normal Change**
- Requires individual risk assessment and authorization before implementation
- Can be major or minor
- Goes through a change schedule and change authority
- Examples: Deploying a new application, making a database architecture change

**Emergency Change**
- Must be implemented as quickly as possible to resolve a major incident or critical vulnerability
- Still requires authorization, but through a faster, streamlined process (often a small Emergency Change Advisory Board)
- Risk is accepted in exchange for speed
- Documentation is completed after implementation

### The Change Authority
The **change authority** is the person or group responsible for authorizing a change. It is not always the same for every change:
- Standard changes: Pre-authorized (no per-change authority needed)
- Normal changes: Change Manager, Change Advisory Board (CAB), or specific manager depending on risk level
- Emergency changes: Emergency CAB (E-CAB) or senior management

### Key Concept: Change Enablement vs. Change Management
The name was changed from "Change Management" to "Change Enablement" deliberately. The message is that this practice should **enable** change, not just control or police it. Overly bureaucratic change processes slow organizations down without proportional risk reduction.

### Implementation Tip
Map your changes to risk levels. Create clear criteria for what makes a change "standard" (pre-authorize those) and what requires full review. The goal is to reduce approval overhead for low-risk changes while maintaining proper governance for high-risk ones.

---

## 9.3 Incident Management

### Purpose
To minimize the negative impact of incidents by restoring normal service operation as quickly as possible.

### What is an Incident?
An **incident** is an unplanned interruption to a service or reduction in the quality of a service.

An incident is about restoring service — **not** about finding and fixing the root cause. Root cause analysis is the job of Problem Management.

**Examples of incidents:**
- Email service is unavailable
- Application response time has degraded significantly
- A user cannot log into a system
- A printer is not printing

### Incident Classification
Incidents are classified by:
- **Priority** = based on impact (how widely it affects the business) and urgency (how quickly it needs to be resolved)
- **Category** = what type of incident it is (network, application, hardware, etc.)

### The Incident Lifecycle

```
Detection → Logging → Classification → Prioritization → 
Diagnosis → Resolution → Recovery → Closure
```

### Major Incidents
A **major incident** is a high-priority incident with significant business impact. Major incidents require:
- A dedicated major incident team
- Executive communication
- Post-incident review (to learn lessons and prevent recurrence)

### Relationship to Problem Management
This is a crucial distinction:
- **Incident Management** = restore service fast (fix the symptom)
- **Problem Management** = find and eliminate root causes (fix the disease)

**Example:** 
- The database server crashes → Incident Management restarts it (service restored in 30 minutes)
- The database crashes again 3 days later → Problem Management investigates *why* it keeps crashing

---

## 9.4 Problem Management

### Purpose
To reduce the likelihood and impact of incidents by identifying actual and potential causes of incidents, and managing workarounds and known errors.

### Key Terms

**Problem:** The *cause* (or potential cause) of one or more incidents. Unlike incidents, problems are investigated systematically.

**Known Error:** A problem that has been analyzed and has either a documented root cause, a workaround, or both — but has not yet been permanently resolved.

**Workaround:** A temporary solution that reduces the impact of an incident or problem while a permanent fix is found.

### The Three Phases of Problem Management

**1. Problem Identification**
- Detecting that a problem exists
- Triggered by recurring incidents, major incident reviews, or proactive analysis
- Sources: Incident records, monitoring data, user feedback, technical teams

**2. Problem Control**
- Analyzing and understanding the problem
- Documenting known errors and workarounds
- Prioritizing which problems to work on

**3. Error Control**
- Managing known errors until they are resolved
- Deciding when (and whether) to implement a permanent fix
- Assessing the risk and cost of each fix

### Root Cause Analysis Techniques

ITIL does not mandate specific techniques, but common ones include:
- **5 Whys:** Keep asking "why?" until you reach the root cause
- **Fishbone Diagram (Ishikawa):** Maps categories of potential causes
- **Fault Tree Analysis:** Uses logic diagrams to trace failure paths

### Proactive Problem Management
Do not only react to incidents. Proactively analyze trends:
- What are the most frequent incident categories?
- Are there patterns in timing (incidents occur every Monday morning after weekend maintenance)?
- What infrastructure components have the most failures?

---

## 9.5 Service Desk

### Purpose
To capture demand for incident resolution and service requests, and to be the entry point and single point of contact (SPOC) for users.

### Why the Service Desk Matters
The service desk is the **face of IT**. For most users, their entire experience of the IT department is through the service desk. A poorly run service desk destroys user confidence, even if the underlying IT infrastructure is excellent.

### Service Desk Channels
Modern service desks offer multiple contact channels:
- Phone
- Email
- Self-service portal
- Chat (live and chatbot)
- Walk-in (for some environments)

### Service Desk Structures

**Centralized:** One service desk for the entire organization. Efficient for staffing, consistent processes.

**Local / Distributed:** Multiple service desks in different locations or business units. Better for local language, proximity, and specialized knowledge.

**Virtual:** Staff in multiple locations working as one logical team. Enabled by technology. Good for 24/7 coverage.

**Follow the Sun:** Different geographic locations handle work during their business hours, providing 24/7 coverage without overnight shifts.

### First Contact Resolution (FCR)
This is the percentage of incidents resolved by the service desk at first contact, without escalation. It is a key metric — higher FCR means better user experience and lower cost.

### Key Skills for Service Desk Staff
- Technical knowledge (obviously)
- Communication skills
- Empathy and patience
- Ability to follow processes consistently
- Documentation accuracy

---

## 9.6 Service Level Management

### Purpose
To set clear business-based targets for service levels, and to ensure delivery of services is properly assessed, monitored, and managed against these targets.

### Key Terms

**Service Level Agreement (SLA):** A documented agreement between a service provider and a customer that identifies both services required and the expected level of service.

**Operational Level Agreement (OLA):** An agreement between the service provider and another part of the same organization that supports the delivery of services.

**Underpinning Contract (UC):** A contract between the service provider and an external supplier that supports the delivery of services to customers.

**Service Level Target:** A specific measurable characteristic of a service, such as availability, throughput, frequency, response time, or quality.

### What Makes a Good SLA?
A good SLA is:
- **Relevant** — Measures what the customer actually cares about
- **Measurable** — Uses specific numbers, not vague language ("fast" is not measurable; "99.9% available" is)
- **Achievable** — Targets that can realistically be met
- **Enforceable** — Consequences and remedies for non-performance are clear
- **Reviewed regularly** — Business needs change; SLAs should reflect current needs

**Example of a poor SLA target:** "The service desk will respond to incidents quickly."

**Example of a good SLA target:** "P1 incidents will receive initial response within 15 minutes and will be resolved within 4 hours, 95% of the time."

### The Service Level Management Role
Service Level Management is responsible for:
- Negotiating SLAs with customers
- Monitoring performance against SLAs
- Producing regular service reports
- Identifying and addressing service improvement opportunities
- Managing customer expectations

---

## 9.7 Service Request Management

### Purpose
To support the agreed quality of a service by handling all pre-defined, user-initiated service requests in an effective and user-friendly manner.

### What is a Service Request?
A **service request** is a formal request from a user for something to be provided — not an incident, but a standard delivery item.

**Examples:**
- Request for a new laptop
- Request for access to a system
- Request for a password reset
- Request for software installation
- Request for information ("How do I submit expenses?")

### Difference from Incident Management

| Aspect | Incident | Service Request |
|---|---|---|
| Nature | Unplanned disruption | Planned, expected need |
| Goal | Restore service | Fulfill a standard request |
| Urgency | Often high | Usually planned and lower urgency |
| Process | Diagnosis and fix | Fulfill based on pre-defined steps |

### Service Catalogue
The **service catalogue** is the foundation of Service Request Management. It is a list of all services available to users, including:
- What the service is
- How to request it
- How long it takes to fulfill
- Who can request it
- What it costs (if applicable)

A good service catalogue sets user expectations and standardizes fulfillment.

---

## 9.8 Monitoring and Event Management

### Purpose
To systematically observe services and service components, and record and report selected changes of state identified as events.

### What is an Event?
An **event** is any change of state that has significance for the management of a service or other configuration item.

### Types of Events

**Informational:** Something happened that is normal and expected. No action required.
*Example: A scheduled backup completed successfully.*

**Warning:** Something happened that is above normal but not yet a failure. Investigation may be warranted.
*Example: CPU usage reached 80% (warning threshold is 75%, critical is 95%).*

**Exception:** Something happened that is abnormal and may require immediate action. May trigger an incident.
*Example: A server went offline.*

### Why This Practice Matters
Without monitoring, you find out about problems when users call to complain. With monitoring, you find problems before users notice — or even prevent them entirely.

**Reactive monitoring:** Alerting you when something goes wrong (the server went down).
**Proactive monitoring:** Watching trends to predict future issues (disk space is 85% full and growing at 2% per day — you have 7 days before it is full).

---

## 9.9 IT Asset Management

### Purpose
To plan and manage the full lifecycle of all IT assets to help the organization maximize value, control costs, manage risks, support decision-making about purchase, re-use, retirement, and disposal of assets, and meet regulatory and contractual requirements.

### What is an IT Asset?
Any financially valuable component that can contribute to the delivery of an IT product or service.

**Examples:**
- Hardware (servers, laptops, network switches)
- Software licenses
- Virtual machines and cloud instances
- Data (increasingly recognized as an asset)
- Contracts and warranties

### The Asset Lifecycle

```
Plan → Acquire → Deploy → Operate → Optimize → Retire/Dispose
```

### Why IT Asset Management Matters

- **Cost control:** Know what you have and avoid buying duplicates or licenses you are not using
- **License compliance:** Avoid legal and financial penalties for using software without proper licenses
- **Security:** Know all devices on your network and ensure they are patched and protected
- **Decision support:** Data to make informed decisions about refresh cycles, cloud migration, etc.

---

## 9.10 Release Management

### Purpose
To make new and changed services and features available for use.

### What is a Release?
A **release** is a version of a service or other configuration item — or a collection of changes — that is made available for use.

### Relationship to Other Practices

```
Change Enablement → Release Management → Deployment Management
(Authorize the change) → (Package and plan the release) → (Deploy to live environment)
```

- **Change Enablement:** Decides *whether* a change should be made
- **Release Management:** Plans *how* to package and make the change available
- **Deployment Management:** Actually moves the change to the live environment

### Release Types
- **Major release:** Significant new functionality (a new version of an application)
- **Minor release:** Small functional improvements or fixes
- **Emergency release:** Urgent fix (often following a major incident)

---

## 9.11 Service Configuration Management

### Purpose
To ensure that accurate and reliable information about the configuration of services, and the CIs that support them, is available when and where it is needed.

### Configuration Item (CI)
A **Configuration Item (CI)** is any component that needs to be managed in order to deliver an IT service.

**Examples of CIs:**
- Servers (hardware CIs)
- Software applications
- Network devices
- Service level agreements (yes, documents can be CIs)
- People (roles may be captured as CIs)
- Processes

### Configuration Management Database (CMDB)
The **CMDB** is the repository where CI information is stored. It captures:
- What the CI is
- Its attributes (version, location, owner)
- Its relationships to other CIs (this application runs on this server, which is in this data center)

### Why the CMDB Matters
A well-maintained CMDB is one of the most valuable assets an IT organization can have:
- Incident Management: Quickly see the infrastructure map and identify impact
- Change Enablement: Assess the downstream impact of a change
- Problem Management: Identify common components in recurring failures

**The challenge:** CMDBs are hard to maintain. They go stale quickly. This is why auto-discovery tools and automated updates are so valuable.

---

## 9.12 Deployment Management

### Purpose
To move new or changed hardware, software, documentation, processes, or any other component to live environments. It may also be involved in deploying components to other environments for testing or staging.

### Deployment Approaches

**Big Bang:** Deploy all components at once. High risk, low complexity in planning.

**Phased:** Deploy to a subset of users or locations first, then roll out progressively. Lower risk, but more complex to manage.

**Continuous Delivery:** Small, frequent deployments (often automated). Aligned with Agile/DevOps practices.

**Pull Deployment:** The new version is made available but only activated when the user or team pulls it down. Common with software updates.

### Deployment Management vs. Release Management (Common Confusion)

| Practice | Does What |
|---|---|
| Release Management | Packages changes and makes them available ("readied for deployment") |
| Deployment Management | Physically moves the changes into the live environment |

Think of Release Management as the **warehouse** that prepares a shipment, and Deployment Management as the **delivery truck** that takes it to the customer.

---

# Chapter 10: Implementing ITIL at the Foundational Level

---

## 10.1 The Most Important Principle for Implementation

Before we dive into how-to steps, let us establish the most important principle for ITIL implementation:

**ITIL is a framework, not a prescription.**

ITIL describes *what* good service management looks like. It does not tell you exactly *how* to implement it in your specific organization. You must adapt ITIL practices to your organization's size, culture, maturity, and context.

The organizations that fail at ITIL implementation are usually those that try to implement *all of ITIL, perfectly, all at once*. That approach fails every time.

The organizations that succeed start small, iterate, and build momentum.

---

## 10.2 The Foundation-Level Implementation Mindset

At the Foundation level, your implementation goal is not to become a fully ITIL-certified organization overnight. Your goal is to:

1. **Establish common language** — Get your team using the same terms and concepts
2. **Identify quick wins** — Find 2-3 practices where improvement would have immediate impact
3. **Build iterative habits** — Introduce the Continual Improvement Model as a way of working
4. **Apply the Guiding Principles** — Use them as decision-making filters in daily work

---

## 10.3 Step-by-Step: Getting Started with ITIL

### Step 1: Assess Where You Are

Use the Continual Improvement Model: *Where are we now?*

Conduct an honest assessment of your current service management maturity:

**Questions to ask:**
- Do we have a formal process for handling incidents?
- Do we track all IT changes? Do we know who approved them?
- Do we have a service catalogue? Do users know what to request and how?
- Do we know what IT assets we have and where they are?
- Do we measure and report on service performance?
- Do we conduct post-incident reviews?
- Do we have formal SLAs with our business stakeholders?

Score each area: *None / Ad-hoc / Defined / Managed / Optimizing*

---

### Step 2: Identify Your Top Priority

Based on your assessment, identify the 1-2 practices where improving would deliver the most value.

**Common first priorities:**
- **Service Desk** — If users are frustrated and don't know how to get help, this is almost always the best starting point
- **Incident Management** — If incidents are handled inconsistently and resolution times are poor
- **Change Enablement** — If uncontrolled changes are causing outages and disruptions
- **Service Request Management** — If IT spends too much time on ad-hoc requests with no standardization

---

### Step 3: Design Simple Processes First

Resist the urge to design a perfect, comprehensive process from the start.

**For Incident Management, start with:**
- A single log where all incidents are recorded
- A simple priority classification (P1, P2, P3)
- Clear ownership: who handles P1 vs. P2 vs. P3
- A basic escalation path
- A way to notify users when something is resolved

That is it. You can add more sophistication later. Getting people to use a simple process consistently is far more valuable than having a complex process that nobody follows.

---

### Step 4: Implement a Ticketing System (If You Have None)

Every ITIL practice depends on logging and tracking work. If your team is managing incidents via email and spreadsheets, this is your first practical improvement.

**Options by scale:**
- **Small team:** Even a simple shared spreadsheet with the right columns is better than nothing
- **Growing team:** Tools like Freshservice, Jira Service Management, or Zendesk
- **Enterprise:** ServiceNow, BMC Helix, or similar

**Regardless of tool:** A tool does not implement ITIL. The process and behavior must come first.

---

### Step 5: Establish a Service Catalogue

Create a simple list of all the services IT provides, including:
- Service name
- Description (what it does)
- Who can use it
- How to request it or report an issue
- What to expect (basic SLA targets)

Publish this somewhere users can find it — an intranet page, a self-service portal, or even a pinned document.

This single artifact delivers disproportionate value because it:
- Reduces confusion about what IT does
- Sets expectations
- Reduces repeat questions to the service desk
- Gives you a basis for measuring performance

---

### Step 6: Introduce a Basic Change Process

Create a simple change categorization:
- **Standard changes:** Pre-approved list of low-risk changes (publish this list so teams can act without waiting for approval)
- **Normal changes:** Anything not on the standard list requires a simple risk assessment and approval
- **Emergency changes:** Fast-track process for critical fixes

Establish a weekly or bi-weekly **Change Advisory Board (CAB)** meeting — even if it is just 30 minutes — where normal changes are reviewed.

---

### Step 7: Build a Continual Improvement Habit

At the end of every significant incident, do a short post-incident review:
- What happened?
- What was the impact?
- What was the root cause (or suspected cause)?
- What actions can we take to prevent recurrence?

Capture the resulting actions in your **Continual Improvement Register**.

Review the CIR monthly. Prioritize the top 3 improvements for the next month.

Repeat forever.

---

## 10.4 Key Implementation Mistakes to Avoid

| Mistake | Why It Fails | What to Do Instead |
|---|---|---|
| Implementing all 34 practices at once | Overwhelms teams, creates resistance, nothing done well | Pick 2-3 high-impact practices first |
| Designing processes in a meeting room without involving users | Processes that don't reflect reality | Co-design processes with the people who will use them |
| Buying an expensive ITSM tool before defining processes | The tool becomes a filing system, not a workflow | Define processes first; then select tools to support them |
| Making ITIL "the IT team's project" | Business stakeholders feel it is imposed on them | Involve business stakeholders from the start |
| Treating ITIL as a compliance exercise | "Box-ticking" without real behavior change | Connect every ITIL activity to a tangible benefit for users or the business |
| Ignoring culture | Great processes fail if the team culture does not support them | Invest in awareness, training, and leadership buy-in |

---

# Chapter 11: ITIL in Projects — A Practical Bridge

---

## 11.1 ITIL and Projects: A Common Gap

Many organizations have good project management practices (PMI, PRINCE2, Agile) but poor service management practices. The result is a common pattern:

1. A project delivers a new system ✅
2. The system goes live
3. Nobody knows who to call when it breaks ❌
4. There are no SLAs ❌
5. Changes are made without a process ❌
6. Eventually, the system becomes a support nightmare ❌

ITIL fills the gap between **project delivery** and **ongoing service operation**.

---

## 11.2 Embedding ITIL in the Project Lifecycle

Here is how to apply ITIL thinking at each stage of a typical project:

### Initiation / Planning Phase
**ITIL concepts to apply:**
- **Service Design:** Start designing how the service will be operated, not just what it will do
- **Service Level Management:** Define preliminary SLAs with stakeholders from day one
- **IT Asset Management:** Register all new assets being created or acquired
- **Four Dimensions:** Use all four dimensions as a design checklist

**Practical actions:**
- Add a "Service Operations" section to your project plan
- Define who will own the service after go-live before the project starts
- Create a preliminary service catalogue entry

---

### Build / Development Phase
**ITIL concepts to apply:**
- **Service Validation and Testing:** Plan your testing approach systematically
- **Service Configuration Management:** Start populating CMDB entries for new components
- **Change Enablement:** Manage all changes to the build environment through a change process

**Practical actions:**
- Create test cases that verify both utility (does it do the right thing) and warranty (does it perform reliably)
- Document all system dependencies for the CMDB

---

### Go-Live / Transition Phase
**ITIL concepts to apply:**
- **Release Management:** Plan the release — who gets it first, how do you roll back if something goes wrong?
- **Deployment Management:** Execute the deployment carefully
- **Organizational Change Management:** Train users, communicate the change, manage resistance

**Practical actions:**
- Create a Go/No-Go checklist
- Establish a hyper-care period (intensive support for the first weeks after go-live)
- Ensure the service desk knows about the new service and how to handle related incidents

---

### Post-Go-Live / Operations Phase
**ITIL concepts to apply:**
- **Incident Management:** Use the standard incident management process for the new service
- **Problem Management:** Track and investigate recurring issues proactively
- **Service Level Management:** Monitor and report against SLAs
- **Continual Improvement:** Conduct regular post-implementation reviews

**Practical actions:**
- Schedule a 30-day, 60-day, and 90-day post-go-live review
- Measure performance against SLAs and share reports with stakeholders
- Feed improvement ideas into the CIR

---

## 11.3 The "Service Transition" Checklist for Projects

Use this checklist when transitioning a project deliverable into live service:

- [ ] Service catalogue entry created
- [ ] SLAs defined and agreed with stakeholders
- [ ] Operational team trained and handed over
- [ ] Support documentation (runbooks) created
- [ ] CMDB updated with new CIs
- [ ] Monitoring and alerting configured
- [ ] Incident and service request categories created in the ticketing system
- [ ] Escalation paths defined
- [ ] Known issues and workarounds documented
- [ ] Hyper-care period defined (with additional support coverage)
- [ ] Post-implementation review scheduled

---

## 11.4 ITIL and Agile — They Are Compatible

A common misconception is that ITIL is "waterfall" and incompatible with Agile. ITIL 4 specifically addresses this. The guiding principles — especially *Progress iteratively with feedback* and *Keep it simple and practical* — are fundamentally aligned with Agile values.

**How they complement each other:**
- Agile delivers new features and services iteratively
- ITIL ensures those features and services are properly managed and supported
- Agile teams can use the Service Value Chain to think about the full lifecycle of what they are building
- ITIL practices provide the governance and stability that enables Agile teams to move fast safely

**Practical integration:**
- Add ITIL "service readiness" criteria to your Definition of Done
- Include operational considerations (monitoring, runbooks, SLAs) in sprint backlog items
- Use the Continual Improvement model alongside your sprint retrospectives

---

# Chapter 12: Common Mistakes and How to Avoid Them

---

## 12.1 Mistake: Confusing Incidents and Problems

**What happens:** Teams call everything an "incident" and never do root cause analysis. The same issues recur indefinitely.

**The fix:** Establish a clear distinction in your ticketing system and team culture.
- Incidents: Restore service fast
- Problems: Investigate why, find permanent fix

When an incident recurs more than once, automatically trigger a problem investigation.

---

## 12.2 Mistake: Treating the CMDB as a One-Time Project

**What happens:** The organization spends months building a comprehensive CMDB. No one maintains it. Within six months, it is dangerously out of date and no one trusts it.

**The fix:** Treat CMDB accuracy as an ongoing operational responsibility. Implement automated discovery tools. Make CMDB updates part of every change and release process.

---

## 12.3 Mistake: SLAs That No One Reads

**What happens:** Lengthy SLA documents are created, signed, and never looked at again.

**The fix:** Create short, business-focused SLAs. Report against them monthly. Share the reports with business stakeholders. When targets are missed, have a conversation about why.

---

## 12.4 Mistake: Change Management That Blocks Everything

**What happens:** Overly bureaucratic change processes result in weeks of delay for simple changes. Teams work around the process ("rogue changes").

**The fix:** Classify changes properly. Pre-authorize standard changes. Streamline the normal change process to focus only on real risk assessment. Keep the emergency change path genuinely fast.

---

## 12.5 Mistake: Implementing ITIL for ITIL's Sake

**What happens:** Teams implement every ITIL practice, create comprehensive documentation, and achieve excellent "compliance" with the framework — but service quality and user satisfaction do not improve.

**The fix:** Always connect ITIL activities to outcomes. Ask regularly: "Is this making things better for users and the business?" If not, simplify or stop.

---

## 12.6 Mistake: No Executive Sponsorship

**What happens:** ITIL implementation is driven by a motivated middle manager. Competing priorities, lack of resources, and organizational resistance eventually kill the initiative.

**The fix:** Secure genuine executive sponsorship before starting. This means a senior leader who visibly champions the initiative, attends key meetings, and ensures resources are available.

---

## 12.7 Mistake: Training Without Application

**What happens:** Teams attend ITIL Foundation training (or pass the exam) but return to work and change nothing. The knowledge stays theoretical.

**The fix:** Immediately after training, identify one real problem in your organization and apply an ITIL concept to it. Connect theory to practice as fast as possible.

---

# Quick Reference Cheat Sheet

---

## Core Definitions

| Term | Definition |
|---|---|
| Service | Means of enabling value co-creation, facilitating outcomes customers want without managing costs/risks |
| Value | Perceived benefits, usefulness, and importance of something |
| Utility | Fit for purpose — does it do what it should? |
| Warranty | Fit for use — does it perform reliably? |
| Output | Tangible or intangible deliverable of an activity |
| Outcome | Result for a stakeholder enabled by outputs |
| Risk | Possible event that could cause harm or loss |
| Incident | Unplanned interruption or reduction in quality of service |
| Problem | Cause or potential cause of one or more incidents |
| Known Error | Problem with documented root cause/workaround but not yet permanently resolved |
| Workaround | Temporary solution reducing impact while permanent fix is developed |
| Change | Addition, modification, or removal of anything that could affect services |
| Event | Any change of state significant to service management |
| CI | Configuration Item — anything managed to deliver IT services |
| CMDB | Configuration Management Database — repository of CI information |
| SLA | Service Level Agreement — agreement on service levels between provider and customer |
| OLA | Operational Level Agreement — internal agreement supporting SLA delivery |

---

## The SVS Components

| Component | What It Is |
|---|---|
| Guiding Principles | Universal recommendations for all decisions and actions |
| Governance | Direction and control of the organization |
| Service Value Chain | Operating model — six activities to create value |
| Practices | 34 sets of organizational resources for service management |
| Continual Improvement | Ongoing improvement of all aspects of the organization |

---

## The Seven Guiding Principles

1. Focus on Value
2. Start Where You Are
3. Progress Iteratively with Feedback
4. Collaborate and Promote Visibility
5. Think and Work Holistically
6. Keep It Simple and Practical
7. Optimize and Automate

---

## The Six Service Value Chain Activities

| Activity | Purpose |
|---|---|
| Plan | Set direction, strategy, and portfolio |
| Improve | Continually improve services and practices |
| Engage | Understand stakeholder needs, build relationships |
| Design and Transition | Design services and prepare for deployment |
| Obtain/Build | Create or procure service components |
| Deliver and Support | Operate services and handle incidents/requests |

---

## The Four Dimensions

1. Organizations and People
2. Information and Technology
3. Partners and Suppliers
4. Value Streams and Processes

*(All affected by PESTLE external factors)*

---

## Change Types

| Type | Description | Authorization |
|---|---|---|
| Standard | Pre-approved, low risk, documented | Pre-authorized |
| Normal | Needs individual risk assessment | Change authority / CAB |
| Emergency | Urgent fix needed immediately | E-CAB / Senior management |

---

## Incident vs. Problem vs. Service Request

| Type | What It Is | Goal |
|---|---|---|
| Incident | Unplanned disruption or degradation | Restore service fast |
| Problem | Root cause of incidents | Eliminate cause permanently |
| Service Request | Pre-defined user request | Fulfill in standard way |

---

## Event Types

| Type | Meaning | Action |
|---|---|---|
| Informational | Normal expected activity | None required |
| Warning | Above normal, not yet failure | Monitor / Investigate |
| Exception | Abnormal, action needed | May trigger incident |

---

## The Continual Improvement Model Steps

1. What is the vision?
2. Where are we now?
3. Where do we want to be?
4. How do we get there?
5. Take action
6. Did we get there?
7. How do we keep the momentum going?

---

## Key Relationships Between Practices

```
Change Enablement → Release Management → Deployment Management
      ↓                                        ↓
   CMDB (Service Configuration Management) ← Incident Management
      ↑                                        ↓
   IT Asset Management              Problem Management
```

---

## Service Consumer Roles

| Role | Who They Are |
|---|---|
| Customer | Defines requirements; responsible for outcomes |
| User | Uses the service directly |
| Sponsor | Authorizes the budget |

---

*End of ITIL Foundation Learning Textbook*

---

**Version:** ITIL 4 Foundation  
**Author:** AI ITIL Master Reference  
**Purpose:** Professional refresher and implementation guide  
**Aligned with:** ITIL 4 Foundation syllabus (Axelos)
