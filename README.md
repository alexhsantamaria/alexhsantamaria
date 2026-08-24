# Alex H. Santamaría-Alcántara

**Supply Chain & Operations | Artificial Intelligence | Operations Research | Decision Intelligence | Sustainable Operations**

[ORCID](https://orcid.org/0009-0009-9243-014X) · [LinkedIn](https://www.linkedin.com/in/alexhsantamaria)

---

## About Me

Supply Chain and Operations professional with experience in logistics, inventory management, international trade, risk management, operational transformation, and supply chain decision-making.

My research interests focus on the application of **artificial intelligence, machine learning, operations research, behavioral operations, and decision intelligence to supply chain management**.

I am particularly interested in understanding how organizations transform demand signals, forecasts, information, human knowledge, organizational coordination, operational constraints, risk, and uncertainty into supply chain decisions — and how those decisions generate economic, operational, service, risk, resource, and environmental consequences.

My long-term research objective is to contribute to the development of **AI-enabled, human-aware, coordinated, and sustainable decision-support systems** capable of improving supply chain performance while reducing waste, risk, and unnecessary resource consumption.

---

## Research Interests

* Artificial Intelligence in Supply Chain
* Machine Learning
* Operations Research
* Decision Intelligence
* Probabilistic Demand Forecasting
* Inventory Optimization
* Behavioral Operations
* Human-AI Decision-Making
* Supply Chain Risk Management
* Supply Chain Resilience
* Cross-Functional Coordination
* Organizational Fragmentation
* Information Sharing
* Prescriptive Analytics
* Logistics Waste
* Inventory Obsolescence
* Circular Economy
* Sustainable Supply Chains

---

# Current Research Direction

## Working Research Framework: Supply Chain Decision Formation and Waste

> **Research status**
>
> This repository presents an evolving research direction and a working conceptual synthesis informed by existing literature in supply chain planning, forecasting, behavioral operations, inventory management, organizational coordination, artificial intelligence, operations research, risk, and sustainability.
>
> The ideas, constructs, relationships, terminology, and diagrams presented here should **not currently be interpreted as a validated or claimed-original theoretical framework**.
>
> Any potential theoretical or methodological contribution must first be supported by systematic literature review, comparison with prior research, formal conceptual development, and empirical validation.

---

## Core Research Premise

A central premise of this research direction is that **inventory and supply chain decisions are not determined by forecasts alone**.

Instead, decisions emerge from the interaction of multiple dimensions that may differ significantly between organizations.

```text
┌────────────────────────────────────────────────────────────┐
│                    MARKET & DEMAND                         │
├────────────────────────────────────────────────────────────┤
│ Demand                                                     │
│ Volatility                                                 │
│ Seasonality                                                │
│ Promotions                                                 │
│ Market signals                                             │
│ Demand uncertainty                                         │
└────────────────────────────┬───────────────────────────────┘
                             │
                             ▼
┌────────────────────────────────────────────────────────────┐
│                ANALYTICS & INFORMATION                     │
├────────────────────────────────────────────────────────────┤
│ Forecasts                                                  │
│ Probabilistic forecasting                                  │
│ Machine learning                                           │
│ Information quality                                        │
│ Data availability                                          │
│ Information sharing                                        │
│ Visibility                                                 │
│ Model accuracy and uncertainty                             │
└────────────────────────────┬───────────────────────────────┘
                             │
                             ▼
┌────────────────────────────────────────────────────────────┐
│                 HUMAN & BEHAVIORAL FACTORS                 │
├────────────────────────────────────────────────────────────┤
│ Knowledge                                                  │
│ Experience                                                 │
│ Judgment                                                   │
│ Intuition                                                  │
│ Cognitive biases                                           │
│ Emotions                                                   │
│ Risk perception                                            │
│ Previous experiences                                       │
│ Decision-maker capabilities                                │
│ Trust in models and data                                   │
└────────────────────────────┬───────────────────────────────┘
                             │
                             ▼
┌────────────────────────────────────────────────────────────┐
│              ORGANIZATION & COORDINATION                   │
├────────────────────────────────────────────────────────────┤
│ Cross-functional coordination                              │
│ Organizational fragmentation                               │
│ Functional silos                                           │
│ Information sharing                                        │
│ Goal alignment                                             │
│ Incentives                                                 │
│ Governance                                                 │
│ Decision rights                                            │
│ Communication quality                                      │
│ Process integration                                        │
│ System integration                                         │
│ Organizational culture                                     │
└────────────────────────────┬───────────────────────────────┘
                             │
                             ▼
┌────────────────────────────────────────────────────────────┐
│             OPERATIONAL & STRATEGIC CONDITIONS             │
├────────────────────────────────────────────────────────────┤
│ Supplier reliability                                       │
│ Lead times                                                 │
│ Minimum order quantities                                   │
│ Capacity                                                   │
│ Storage constraints                                        │
│ Financial constraints                                      │
│ Working capital                                            │
│ Service-level objectives                                   │
│ Risk appetite                                              │
│ Business strategy                                          │
│ Product characteristics                                    │
│ Regulatory constraints                                     │
└────────────────────────────┬───────────────────────────────┘
                             │
                             ▼
                  ┌──────────────────────┐
                  │ SUPPLY CHAIN /       │
                  │ INVENTORY DECISION   │
                  └──────────┬───────────┘
                             │
                             ▼
                  ┌──────────────────────┐
                  │  INVENTORY OUTCOME   │
                  └──────────┬───────────┘
                             │
                ┌────────────┴─────────────┐
                │                          │
                ▼                          ▼
        EXCESS INVENTORY                STOCKOUT
                │                          │
                ▼                          ▼
        Holding costs                 Lost sales
        Working capital               Service loss
        Obsolescence                  Expedites
        Returns                       Emergency actions
        Redistribution                Customer impact
        Disposal                      Production disruption
                │                          │
                └────────────┬─────────────┘
                             │
                             ▼
                    LOGISTICS WASTE
                             │
                             ▼
              ┌──────────────────────────┐
              │  TOTAL DECISION IMPACT   │
              ├──────────────────────────┤
              │ Economic Impact          │
              │ Environmental Impact     │
              │ Service Impact           │
              │ Operational Impact       │
              │ Risk Exposure            │
              └──────────────────────────┘
```

---

# Decision Formation

A working conceptual representation is:

$$
InventoryDecision_{j,t}
=
f_j(
D_t,
F_t,
I_t,
H_t,
C_t,
O_t,
S_t,
K_t,
R_t
)
$$

where the dimensions provisionally represent:

* $D_t$ = Demand and uncertainty
* $F_t$ = Forecasts and analytics
* $I_t$ = Information and visibility
* $H_t$ = Human and behavioral factors
* $C_t$ = Coordination and integration
* $O_t$ = Organizational factors
* $S_t$ = Supply conditions
* $K_t$ = Capabilities and constraints
* $R_t$ = Risk and strategy

The subscript $j$ represents the organization.

A proposition to investigate is:

$$
f_{CompanyA} \neq f_{CompanyB}
$$

Organizations receiving similar demand signals may reach substantially different decisions because they differ in their:

* information systems,
* analytical maturity,
* decision processes,
* human experience,
* behavioral biases,
* organizational structures,
* coordination mechanisms,
* incentives,
* governance,
* financial capacity,
* operational capabilities,
* risk tolerance,
* suppliers,
* markets,
* and strategic priorities.

This leads to a fundamental research question:

> **Why do organizations facing similar information make different supply chain decisions, and which characteristics of their decision processes generate or prevent operational and logistics waste?**

---

# Coordination & Organizational Fragmentation

Cross-functional coordination is a specific area of interest within this research direction.

Supply chain decisions typically require interaction among multiple functions:

```text
Sales
   +
Marketing
   +
Finance
   +
Procurement
   +
Planning
   +
Operations
   +
Logistics
   +
Suppliers
   +
Management
```

Functional specialization can create valuable expertise.

However, fragmented decision-making may also create:

```text
Different Information
        +
Different Objectives
        +
Different Incentives
        +
Different Interpretations
        +
Delayed Communication
        ↓
Potential Decision Distortion
```

### Working Hypothesis — Not Yet Validated

One relationship to investigate is:

```text
High Organizational Fragmentation
                +
Low Cross-Functional Coordination
                ↓
Information Loss / Delay
                ↓
Goal Misalignment
                ↓
Local Optimization
                ↓
Decision Distortion
                ↓
Higher Supply Chain Risk
                ↓
Inventory & Operational Waste
```

A related hypothesis is that **coordination quality may moderate the relationship between organizational fragmentation and supply chain decision quality**.

This proposition requires theoretical development and empirical validation.

---

# Human & Behavioral Factors

Supply chain decisions are not purely mathematical.

Existing research in behavioral forecasting and operations shows that quantitative recommendations may be interpreted, adjusted, accepted, rejected, or overridden through human judgment.

Potential factors include:

* knowledge,
* experience,
* intuition,
* managerial judgment,
* fear of stockouts,
* overconfidence,
* optimism,
* recency effects,
* loss aversion,
* previous disruptions,
* organizational pressure,
* individual risk perception,
* and trust in analytical models.

This creates a research intersection between:

```text
Operations Research
        +
Artificial Intelligence
        +
Behavioral Operations
        +
Organizational Decision-Making
        +
Supply Chain Management
```

---

# Human + AI Decision-Making

The objective of this research direction is **not to assume that artificial intelligence should replace human decision-makers**.

A potentially more valuable question is:

> **How can artificial intelligence, operations research, organizational knowledge, human judgment, and coordination be combined to improve supply chain decisions?**

Conceptually:

```text
DATA
  +
ANALYTICS
  +
AI
  +
HUMAN KNOWLEDGE
  +
COORDINATION
  +
ORGANIZATIONAL CONTEXT
  +
OPERATIONAL CONSTRAINTS
       ↓
BETTER DECISION FORMATION
       ↓
BETTER SUPPLY CHAIN DECISIONS
```

---

# Decision Consequences

This research direction seeks to study decisions beyond traditional inventory KPIs.

A decision may simultaneously affect several dimensions.

### Economic Impact

* Inventory holding cost
* Working capital
* Obsolescence
* Lost sales
* Expedite costs
* Returns
* Disposal costs
* Margin
* Cost-to-serve

### Operational Impact

* Inventory availability
* Capacity utilization
* Lead time
* Productivity
* Network utilization
* Emergency interventions

### Service Impact

* Fill rate
* OTIF
* Stock availability
* Customer satisfaction
* Service continuity

### Risk Impact

* Stockout exposure
* Supplier dependence
* Disruption vulnerability
* Recovery requirements
* Operational resilience

### Environmental & Resource Impact

* Unnecessary production
* Excess transportation
* Storage requirements
* Product disposal
* Packaging waste
* Reverse logistics
* Resource consumption
* Greenhouse-gas emissions

---

# Working Research Questions

1. How are inventory decisions actually formed inside organizations?

2. How do demand uncertainty, forecasting models, and human judgment interact?

3. Why can organizations facing similar demand signals make different inventory decisions?

4. How does organizational fragmentation affect supply chain decision-making?

5. How does cross-functional coordination influence decision quality?

6. Can coordination moderate risks associated with organizational fragmentation?

7. How do incentives and functional KPIs influence inventory decisions?

8. How do cognitive biases and emotions affect supply chain decisions?

9. Which decision factors are most strongly associated with excess inventory, stockouts, obsolescence, and logistics waste?

10. How can the economic consequences of supply chain decisions be quantified?

11. How can the environmental and resource consequences of those decisions be quantified?

12. Can artificial intelligence identify patterns associated with poor supply chain decisions?

13. Can AI-enabled decision-support systems integrate quantitative evidence with valuable human knowledge?

14. How can inventory optimization simultaneously consider cost, service, risk, waste, and environmental impact?

15. To what extent are these relationships organization-specific, industry-specific, or generalizable?

---

# Potential Research Contribution — Under Investigation

No individual construct in this repository is currently claimed as original.

Forecasting, inventory optimization, behavioral decision-making, information sharing, coordination, S&OP, supply chain risk, sustainability, artificial intelligence, machine learning, and reinforcement learning all have established research traditions.

The research opportunity being investigated is whether these streams can be meaningfully integrated into a theoretically grounded and empirically validated model explaining:

```text
DECISION INPUTS
      ↓
DECISION FORMATION
      ↓
SUPPLY CHAIN DECISION
      ↓
OPERATIONAL OUTCOME
      ↓
LOGISTICS / RESOURCE WASTE
      ↓
TOTAL DECISION IMPACT
```

where a provisional representation of total impact is:

$$
TotalDecisionImpact
===================

Economic
+
Environmental
+
Service
+
Operational
+
Risk
$$

Determining whether this integration represents a meaningful research gap requires a **systematic literature review, comparison with existing frameworks, and empirical validation**.

---

# Long-Term Research Objective

The long-term objective is to investigate whether a rigorous framework can be developed and empirically validated to explain the relationship between:

$$
DecisionInputs
\rightarrow
DecisionFormation
\rightarrow
SupplyChainDecision
\rightarrow
OperationalOutcome
\rightarrow
Waste
\rightarrow
Impact
$$

The ultimate research question is therefore not only:

> **How can supply chains forecast better?**

but rather:

> **How can organizations make better supply chain decisions by combining artificial intelligence, human knowledge, coordination, operations research, organizational capabilities, and sustainability?**

---

# Current Research Projects

## 1. Working Research Framework: Supply Chain Decision Formation and Waste

Development of an evolving conceptual synthesis to understand how supply chain decisions are formed and how decision processes may propagate into operational, economic, service, risk, resource, and environmental outcomes.

## 2. Inventory Decision Formation

Research into interactions among forecasting, information, human judgment, organizational structure, coordination, incentives, capabilities, and operational constraints.

## 3. AI for Inventory Optimization

Exploration of machine learning, probabilistic forecasting, reinforcement learning, operations research, and prescriptive analytics for inventory decision support.

## 4. Organizational Fragmentation & Coordination

Study of how functional silos, information fragmentation, conflicting objectives, governance, and coordination mechanisms may affect supply chain decisions.

## 5. Sustainable Supply Chain Decision Intelligence

Investigation of decision models that simultaneously incorporate economic, operational, risk, service, resource-waste, and environmental variables.

---

# Research Methods & Technologies

* Python
* SQL
* Machine Learning
* Probabilistic Forecasting
* Operations Research
* Mathematical Optimization
* Reinforcement Learning
* Simulation
* Prescriptive Analytics
* Supply Chain Analytics
* Decision Modeling
* Power BI

---

# Foundational Literature

The following publications represent part of the literature informing this evolving research direction.

**This is not yet a systematic or exhaustive literature review.**

## Information, Forecasting & Bullwhip Effect

**Lee, H. L., Padmanabhan, V., & Whang, S. (1997).**
Information distortion in a supply chain: The bullwhip effect.
*Management Science, 43*(4), 546–558.
https://doi.org/10.1287/mnsc.43.4.546

**Chen, F., Drezner, Z., Ryan, J. K., & Simchi-Levi, D. (2000).**
Quantifying the bullwhip effect in a simple supply chain: The impact of forecasting, lead times, and information.
*Management Science, 46*(3), 436–443.
https://doi.org/10.1287/mnsc.46.3.436.12069

## Human Judgment & Behavioral Forecasting

**Arvan, M., Fahimnia, B., Reisi, M., & Siemsen, E. (2019).**
Integrating human judgement into quantitative forecasting methods: A review.
*Omega, 86*, 237–252.
https://doi.org/10.1016/j.omega.2018.07.012

**Perera, H. N., Hurley, J., Fahimnia, B., & Reisi, M. (2019).**
The human factor in supply chain forecasting: A systematic review.
*European Journal of Operational Research, 274*(2), 574–600.
https://doi.org/10.1016/j.ejor.2018.10.028

## Cross-Functional Coordination & Supply Chain Planning

**Oliva, R., & Watson, N. (2011).**
Cross-functional alignment in supply chain planning: A case study of sales and operations planning.
*Journal of Operations Management, 29*(5), 434–448.
https://doi.org/10.1016/j.jom.2010.11.012

**Goh, S. H., & Eldridge, S. (2019).**
Sales and Operations Planning: The effect of coordination mechanisms on supply chain performance.
*International Journal of Production Economics, 214*, 80–94.
https://doi.org/10.1016/j.ijpe.2019.03.027

## AI, Machine Learning & Inventory Decisions

**Boute, R. N., Gijsbrechts, J., van Jaarsveld, W., & Vanvuchelen, N. (2022).**
Deep reinforcement learning for inventory control: A roadmap.
*European Journal of Operational Research, 298*(2), 401–412.
https://doi.org/10.1016/j.ejor.2021.07.016

**van der Haar, J. F., Wellens, A. P., Boute, R. N., & Basten, R. J. I. (2024).**
Supervised learning for integrated forecasting and inventory control.
*European Journal of Operational Research, 319*(2), 573–586.
https://doi.org/10.1016/j.ejor.2024.07.004

---

# Research Integrity

This repository represents an **evolving research agenda**.

Concepts, terminology, hypotheses, diagrams, variables, and relationships presented here are provisional and may be revised substantially as the literature review and empirical research progress.

Where concepts originate from or substantially overlap with established academic literature, appropriate attribution should be provided.

No claim of theoretical, methodological, or terminological novelty should be inferred unless supported by:

* systematic literature review,
* explicit comparison with prior frameworks,
* theoretical justification,
* empirical validation,
* and appropriate academic peer review.

---

# Collaboration Interests

I am interested in collaborating with researchers and practitioners working on:

* AI-enabled supply chain decision-making
* Human-AI collaboration
* Behavioral operations
* Forecasting and inventory integration
* Inventory optimization
* Cross-functional coordination
* Organizational decision-making
* Supply chain risk and resilience
* Inventory waste and obsolescence
* Circular economy
* Sustainable operations
* Prescriptive analytics
* Economic and environmental impacts of supply chain decisions

---

# Academic Identity

**Author:** Alex H. Santamaría-Alcántara
**ORCID:** [0009-0009-9243-014X](https://orcid.org/0009-0009-9243-014X)

---

> **Researching how information, human knowledge, organizational coordination, artificial intelligence, and operations research can contribute to better supply chain decisions — with less waste, lower risk, stronger service, and greater economic and environmental sustainability.**
