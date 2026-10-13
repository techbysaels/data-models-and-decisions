# 🧩 Data, Models, and Decisions

## Introduction to the Portfolio

This repository explores a practical question that sits at the center of applied AI: **how should data, models, automation, and human expertise work together to improve a real process?**

The cases cover retail, supply chains, transportation, agriculture, software development, accounting, restaurants, and infrastructure. Some rely on computer vision and sensor fusion. Others are better served by rule-based automation, optimization, or a combination of several approaches. Across all of them, the technology is only one part of the system.

A recurring theme is that a strong AI use case begins with the process rather than the model. The business objective needs to be clear, the required data must be obtainable and reliable, the output must fit the workflow, and people still need defined responsibilities for validation, exceptions, safety, and final decisions.

This portfolio therefore focuses less on asking *“Where can we add AI?”* and more on asking *“What decision are we trying to improve, what information is required, and what role should automation actually play?”*

## 📚 Documents and Use Cases

| Document | Use case(s) | Main question explored | Role of data, models, and people |
| --- | --- | --- | --- |
| [Li-Fung-case.md](https://github.com/techbysaels/data-models-and-decisions/blob/ea07fbfc2ea70c463785e48575a9be996dd5acdf/Li-Fung-case.md) | **AI-enabled digital supply chain transformation** | How can a global supply-chain platform use digital tools, forecasting, scenario analysis, and AI-assisted workflows to improve speed and decision-making? Will the technology work without a well-defined business objective? | Market, product, supplier, factory, cost, capacity, and production data support predictions and planning. Designers, merchandisers, analysts, and supply-chain teams remain responsible for interpreting the information and acting on it. However, if the solution is not directed to an objective, the business may not obtain benefits from the investment. |
| [Amazon-Go-case.md](https://github.com/techbysaels/data-models-and-decisions/blob/ea07fbfc2ea70c463785e48575a9be996dd5acdf/Amazon-Go-case.md) | **Checkout-free retail with computer vision and sensor fusion** | How can a store remove the traditional checkout while still creating an accurate transaction for each shopper? Should we focus on the use of technology to solve the problem or should we focus on solving the problem itself? | Cameras, distance information, customer-entry data, product information, pose estimation, object recognition, and location tracking are combined to answer the operational question: *who took what?* Customers interact with a simple front end while the AI operates in the background. However, using AI could hide a more efficient solution for the same problem. |
| [NAuto case.md](https://github.com/techbysaels/data-models-and-decisions/blob/ea07fbfc2ea70c463785e48575a9be996dd5acdf/NAuto-case.md) | **AI-enabled fleet safety and driver-risk monitoring** | How can a system detect risky driving behavior early enough to prevent incidents rather than simply review them afterward? | On-device models analyze behavior and context in real time, while cloud systems support model refinement and broader risk analysis. Drivers receive immediate alerts; supervisors use video and contextual evidence for coaching, investigation, and claims decisions. |
| [Cinema case](https://github.com/techbysaels/data-models-and-decisions/blob/ea07fbfc2ea70c463785e48575a9be996dd5acdf/Cinema-case.md) | **Rule-based cinema automation, loyalty, and personalization** | How can a traditional cinema process evolve from manual ticketing into a connected digital service? | Seat availability, purchases, loyalty status, and QR access are handled through rules, while customer-history data can support recommendations, promotions, and location-specific movie allocation. Employees shift from repetitive cashier work toward service-oriented activities. |
| [ML-enhanced-processes.md](https://github.com/techbysaels/data-models-and-decisions/blob/ea07fbfc2ea70c463785e48575a9be996dd5acdf/ML-enhanced-processes.md) | **Crop disease and pest detection** | How can image models and environmental sensing help farmers identify problems earlier and focus expert attention where it is needed most? | Drone, equipment, smartphone, and environmental sensor data can support screening. Agronomists or farmers remain responsible for confirming diagnoses and selecting treatment. |
| [ML-enhanced-processes.md](https://github.com/techbysaels/data-models-and-decisions/blob/ea07fbfc2ea70c463785e48575a9be996dd5acdf/ML-enhanced-processes.md) | **Adaptive traffic signal optimization** | How can real-time traffic information improve signal timing when static schedules do not match current conditions? | Cameras, connected infrastructure, and traffic sensors provide real-time demand information. The model can adapt timing recommendations, while safety requirements and operational controls constrain how much authority should be automated. |
| [ML-enhanced-processes.md](https://github.com/techbysaels/data-models-and-decisions/blob/ea07fbfc2ea70c463785e48575a9be996dd5acdf/ML-enhanced-processes.md) | **ML-enabled infrastructure inspection** | How can computer vision reduce the time and effort required to identify road, bridge, and structural defects? | Images and 3D measurements from cameras, drones, lasers, and inspection vehicles can identify and classify defects. Engineers still confirm important findings, assess structural consequences, and prioritize repairs. |
| [Taxonomy-and-human-in-the-loop.md](https://github.com/techbysaels/data-models-and-decisions/blob/ea07fbfc2ea70c463785e48575a9be996dd5acdf/Taxonomy-and-human-in-the-loop.md) | **Low-code / no-code software services** | When should software-building workflows use rule-based automation versus ML-enabled assistance? | Templates and predefined components support deterministic work, while ML or generative AI can assist with code and workflow generation. Developers still own architecture, security, integration, review, and production readiness. |
| [Taxonomy-and-human-in-the-loop.md](https://github.com/techbysaels/data-models-and-decisions/blob/ea07fbfc2ea70c463785e48575a9be996dd5acdf/Taxonomy-and-human-in-the-loop.md)  | **Accounting automation** | Which financial tasks can be automated safely, and when should ML be introduced? | Structured work such as payroll, invoices, matching, and categorization fits rule-based automation. ML can help with anomalies and unfamiliar transactions, but accountants remain responsible for exceptions, compliance, and consequential decisions. |
| [Taxonomy-and-human-in-the-loop.md](https://github.com/techbysaels/data-models-and-decisions/blob/ea07fbfc2ea70c463785e48575a9be996dd5acdf/Taxonomy-and-human-in-the-loop.md) | **Intelligent restaurant operations** | How can rule-based automation, sensing, forecasting, optimization, and personalization work together in one operating process? | Order data, kitchen sensors, demand signals, inventory, customer history, and operational constraints can drive multiple forms of automation. Chefs, food-safety specialists, employees, and managers remain responsible for quality, exceptions, context, and strategic choices. |
| [Taxonomy-proposal-infrastructure-defect.md](https://github.com/techbysaels/data-models-and-decisions/blob/ea07fbfc2ea70c463785e48575a9be996dd5acdf/Taxonomy-proposal-infrastructure-defects.md) | **Transportation infrastructure defect monitoring — portfolio recommendation** | Which AI process design is most appropriate for defect detection, and where should expert review remain mandatory? | The document argues for ML-enabled monitoring and sensing rather than pure rules or fully autonomous action. The model performs repetitive detection; engineers retain responsibility for high-impact structural decisions. |

## 🔄 From Data to Models to Decisions

The cases can be read as different versions of the same operating architecture:

**Data** captures what is happening in the environment. It may come from cameras, telematics, customer transactions, supplier systems, inspection equipment, environmental sensors, loyalty programs, or structured business records.

**Models and rules** transform that information into a useful signal. Depending on the process, this may mean recognizing an object, predicting a risk, identifying an anomaly, optimizing a sequence, recommending an item, or simply enforcing a deterministic business rule.

**Decisions** are where business value—or business risk—actually appears. A recommendation only becomes meaningful when someone or something acts on it: a driver corrects behavior, an engineer prioritizes an inspection, a cinema reallocates screens, a farmer investigates a crop sector, or a supply-chain team changes a production plan.

This distinction matters because model performance alone does not define a successful system. A technically strong prediction that arrives too late, lacks the right context, or is assigned to the wrong decision-maker may provide little operational value.

## 🤝 Human-in-the-Loop Is Part of the Architecture

The documents repeatedly show that human involvement should be designed intentionally rather than added as a generic safety layer.

In the infrastructure cases, engineers confirm critical defects and determine repair priorities. In Nauto, drivers receive immediate alerts while supervisors investigate patterns and incidents. In accounting, models can flag unusual transactions but accountants decide how those exceptions should be handled. In restaurants, managers can override forecasts when they know about local events or circumstances the system cannot see.

The useful question is therefore not simply whether a process should be automated. It is **which part should be automated, what evidence should be presented to people, and who remains accountable for the final action**.

## 🏗️ Choosing the Right Type of Automation

One of the strongest lessons across the portfolio is that not every problem needs the same technical approach.

- **Rule-based automation** works well when inputs are structured, outcomes are deterministic, and the process can be expressed clearly. Cinema seat availability, invoice processing, and parts of restaurant order routing fit this pattern.

- **ML-enabled automation** becomes useful when the system needs to infer patterns from data rather than follow explicit rules. Examples include anomaly detection, code assistance, customer recommendations, and demand forecasting.

- **ML-enabled monitoring and sensing** is a better fit when the environment itself must be observed continuously. Infrastructure inspection, crop monitoring, fleet safety, and checkout-free retail all depend on turning sensor or image data into operational signals.

- **Optimization** is relevant when the core problem is choosing among many feasible actions under competing constraints, such as traffic timing, kitchen scheduling, inventory allocation, or operational planning.

- **Personalization** becomes valuable when the desired output depends on an individual customer's history or preferences, as shown in cinema promotions and restaurant recommendations.

The technology choice should follow the process objective—not the other way around.

## 📌 Portfolio Takeaways

Several themes recur across very different industries.

- **Start with the decision.** A model is useful only when its output improves a real process or decision.

- **Data availability can determine feasibility.** Amazon Go demonstrates that obtaining representative training data can require years of operational investment. Li & Fung raises a similar question around access to heterogeneous supply-chain data.

- **Real-time systems need different architectures from analytical systems.** Nauto's split between edge processing and cloud-based refinement illustrates why latency and operational context affect model design.

- **Automation should move experts toward higher-value work.** Crop specialists, engineers, accountants, developers, cinema employees, and fleet supervisors are not removed from the process; their attention shifts from repetitive execution toward validation, investigation, planning, and exceptions.

- **Safety and liability affect the level of autonomy.** Infrastructure inspection and traffic management are good examples of cases where a model can improve monitoring without automatically being given authority over every action.

- **Digital transformation is not a strategy by itself.** The cross-case debrief makes an important point: technology should be justified by process outcomes and performance rather than adopted because it is technically impressive.

## 🗂️ Repository Perspective

Taken together, these documents show a progression from simple automation to intelligent decision systems.

The portfolio begins with processes that can be described with deterministic rules, moves into systems that learn from historical data, and then reaches applications where sensors, real-time inference, optimization, and expert judgment operate together.

That progression is useful because it reflects how machine learning is actually deployed in organizations. The hardest part is rarely choosing an algorithm in isolation. The more difficult engineering work is deciding what data must exist, how the model fits the process, what should happen when the model is uncertain or wrong, and how people remain able to understand and control the system.

That is the central idea behind **Data, Models, and Decisions**.
