# Innovation Is a Story: Philippine Tech Startup Narrative Simulator

## Part 1: Value Proposition

### 1. Transformed Concept
The static 5-stage innovation journey and the 6 key stakeholder archetypes (**Visionary**, **Builder**, **Helper**, **User**, **Opponent**, **System**) presented in the context of Philippine tech startups (local infrastructure constraints, community dynamics, and regulatory friction). Previously, these concepts existed as static cards (`#journey` and `#people`) that described forces in isolation rather than demonstrating how they push and pull against each other.

### 2. Target Component Type
- **Type:** Decision Tree / Interactive Scenario Evaluator

### 3. User Goal Statement
> *"When a visitor interacts with this component, they will be able to select a local Philippine challenge and assemble key ecosystem archetypes so that they can better understand how real-world non-linear pivots, regulatory friction, and community interventions actively shape an innovation narrative before launch."*

## Part 2: Interaction Logic (Input – Process – Output)

### 1. User Inputs
* **Foundational Problem (Dropdown Select):**
  * `Cash-heavy logistics / Last-mile delivery`
  * `Fragmented rural healthcare access`
  * `SME access to micro-lending`
* **Lead Archetype Focus (Radio Pills):**
  * **Visionary** (*Idea-first*)
  * **Builder** (*Tech/Product-first*)
  * **Helper** (*Community/Grant-first*)
* **Primary Ecosystem Obstacle (Dropdown Select):**
  * `System: Outdated Regulatory Red Tape`
  * `Opponent: Incumbent Monopolies`
  * `System: Unstable Connectivity & Infrastructure`

### 2. Processing Engine
1. Matches the selected inputs against a mapped lookup matrix containing 9 contextual Philippine startup case archetypes.
2. Determines the narrative turning point (**The Friction**) and the adaptive pivot (**The Evolution**) based on the archetype choice.
3. Assigns dynamic readiness scores across three vectors:
   * **Community Alignment**
   * **Tech Feasibility**
   * **Regulatory Resilience**

### 3. Output & Dynamic Feedback
1. **Interactive Story Card:** Generates a custom 3-stage mini-narrative:
   * **Stage 1:** The Genesis
   * **Stage 2:** The Friction Point
   * **Stage 3:** The Pivot
2. **Impact Meters:** 3 progress bars illustrating how the selected role and systemic friction balance each other out.
3. **Ecosystem Takeaway Badge:** An actionable research quote framing how narrative friction altered the venture's final trajectory.

## Part 3: Technical Scope & Error Handling

* **Validation Boundaries:** All three dropdown/radio fields require a chosen value before running evaluation.
* **Error States:** If a user clicks **"Trace the Story"** without choosing an archetype or obstacle, a CSS shake animation triggers on unselected form elements accompanied by an inline warning:  
  `"Select your ecosystem elements to map the narrative."`
* **External Dependencies:** Pure Vanilla JavaScript / HTML5 / CSS3 (zero external library dependencies, lightweight embed).

## Part 4: Layout and UI Wireframe

```text
+---------------------------------------------------------------------------------+
|  [Eyebrow] SIMULATE THE JOURNEY                                                 |
|  Interactive Narrative Builder: How Philippine Startups Evolve                  |
+---------------------------------------------------------------------------------+
|  1. The Everyday Problem:                                                       |
|     [ Cash-Heavy Last-Mile Logistics in Peri-Urban Areas         v ]            |
|                                                                                 |
|  2. Who Takes the Lead?                                                         |
|     (o) The Visionary      ( ) The Builder      ( ) The Helper                  |
|                                                                                 |
|  3. The Inevitable Friction:                                                    |
|     [ Systemic Barrier: Fragmented Inter-island Infrastructure   v ]            |
|                                                                                 |
|                     [ Trace the Innovation Story ]                              |
+---------------------------------------------------------------------------------+
|  --- THE RESULTING NARRATIVE ARC ---                                            |
|                                                                                 |
|  [Stage 1: Genesis] -> [Stage 2: The Obstacle] -> [Stage 3: The Pivot]          |
|                                                                                 |
|  "The app attempted automated hub-routing, but driver connectivity              |
|   dropped in regional corridors. Rather than forcing a pure-digital             |
|   model, community co-ops were integrated as local dispatch centers."           |
|                                                                                 |
|  Tension Dynamics:                                                              |
|  Community Buy-in: [==========   ] 80%                                          |
|  Regulatory Risk:  [=====        ] 45%                                          |
|                                                                                 |
|  Takeaway: "Innovation does not move in a straight line. It evolves."           |
+---------------------------------------------------------------------------------+
```

## Part 5: AI Prompt Blueprint & Implementation Guidelines

* **Role & Task:** Professional front-end web developer building a self-contained interactive component using clean HTML, modern CSS, and Vanilla JavaScript that embeds directly into an existing webpage.
* **Academic Context & Objective:** The host page, *'Innovation Is a Story'*, explores how startups evolve through non-linear friction, local contexts, and diverse human roles within the Philippine startup ecosystem.
* **Responsive Design:** Mobile- and desktop-friendly layout with accessible labels, hover/focus states, and ARIA attributes.
* **Mount Point:** Ready to paste directly before the `#research` or `#philippines` section in `index.html`.
philippine_startup_narrative_simulator.md
Displaying philippine_startup_narrative_simulator.md.