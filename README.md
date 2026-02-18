# 🚀 AI-Powered Multi-Agent Development Strategy Prompt

I want you to help me **design the best possible development strategy** for this application by leveraging a **multi-agent system** that acts like a full development team.

Inside the `#file:.docs` folder, you will find documentation and reference materials about the project.

This multi-agent system must be **project-agnostic**:

* It must work for projects with or without existing designs.
* It must adapt to different architectures (MVVM, MVC, Clean Architecture, microservices, etc.).
* It must handle both frontend and backend, business logic, UX/UI, testing, and documentation.
* Agents must collaborate like a team, with clear responsibilities, boundaries, and communication rules.

---

## 1️⃣ Project Analysis & Strategic Planning

Before any implementation:

* **Analyze the project thoroughly** using the `#file:.docs` references.
* Identify:

  * Key modules, domains, or features
  * Business rules and workflows
  * Technical constraints
  * Potential integration points
  * Required architectural patterns (MVVM, MVC, microservices, etc.)
* Define a **modular architecture**:

  * Clear domain separation
  * Layered responsibilities (UI, state, business, data)
  * Scalable folder structure
  * Dependency flow rules
  * Testing strategy
* Define **project-wide development rules**:

  * Naming conventions
  * Coding standards
  * State management strategy
  * API consumption and mocking rules
  * CI/CD flow recommendations

> The goal is to ensure that the multi-agent system can operate efficiently within the structure and that future modules can be integrated without friction.

---

## 2️⃣ Multi-Agent Architecture & Responsibilities

Design a **team of AI agents** that covers all aspects of project development. Each agent must have:

* **Clear purpose**
* **Defined scope and boundaries**
* **Inputs, outputs, and constraints**
* **Rules of engagement**
* **Conflict prevention and resolution rules**

### 🔹 Core Agent Categories

#### 1. **Business Logic Agents**

* One per major domain/module.
* Responsibilities:

  * Enforce business rules
  * Validate use cases
  * Ensure data integrity
  * Guarantee domain consistency
  * Coordinate with API/Data agents for accurate responses

#### 2. **Visual Fidelity / Design Agents**

* One per major UI section or, in projects without design:

  * Responsible for generating **UI mockups, components, and layouts**
  * Maintain design consistency
  * Ensure usability, accessibility, and responsiveness
* For projects with Figma or designs:

  * Validate against design tokens and visual specifications
* For projects without designs:

  * Suggest UX flows, wireframes, and UI layouts
  * Propose reusable components and design systems

#### 3. **UX / User Flow Agents**

* Responsible for creating intuitive user flows, navigation patterns, and feature interaction sequences.
* Ensure:

  * Feature usability
  * Consistency across modules
  * Accessibility and readability

#### 4. **API & Data Agents**

* Handle backend endpoints, mock services, and data simulations.
* Responsibilities:

  * Generate structured mock APIs with realistic responses
  * Simulate error cases, latencies, and status codes
  * Ensure compatibility with ViewModels, services, or UI layers
  * Transition from mocks to real APIs smoothly

#### 5. **Architecture & Governance Agents**

* Ensure all agents adhere to the project architecture.
* Responsibilities:

  * Maintain separation of concerns
  * Enforce coding standards and patterns
  * Monitor dependencies and module boundaries
  * Detect logic or UI leaks across layers

#### 6. **Testing & QA Agents**

* Define automated tests, unit tests, integration tests, and UI tests.
* Validate business logic, API responses, and UI/UX compliance.
* Identify edge cases and error flows

#### 7. **Performance & Optimization Agents**

* Monitor render efficiency, state updates, and memory usage.
* Propose refactors or optimizations without breaking functionality.
* Suggest efficient data handling, caching, and lazy loading strategies.

#### 8. **Documentation & Knowledge Agents**

* Maintain project documentation automatically.
* Responsibilities:

  * Generate feature docs, API docs, and architectural diagrams
  * Keep design system and coding guidelines up to date
  * Track agent responsibilities and outputs

---

## 3️⃣ Workflow Planning

* Define **feature implementation workflows** for the agents:

  * From requirement → UX → Design → Business logic → API → Integration → Testing → Documentation
* Specify **parallel vs sequential execution** rules for agents.
* Provide a **coordination strategy** to avoid conflicts:

  * Communication between agents
  * Versioning and merging of outputs
  * Handling overlapping responsibilities
* Define **rules for incremental execution**:

  * Work module by module
  * Integrate design incrementally when available
  * Update mocks and flows iteratively

---

## 4️⃣ Mock API / Data Strategy

* No hardcoded data in UI or ViewModels.
* Mocking rules:

  * Simulate realistic API routes and responses
  * Include status codes, delays, and error cases
  * Keep mocks isolated in a data layer
  * Enable easy replacement with real endpoints
  * Support different layers (ViewModels, Services, State Management)

---

## 5️⃣ Copilot Operational Playbook

Generate a **production-ready Markdown file** that includes:

1. **Agent List**

   * Name, purpose, scope, and boundaries
   * When to activate
   * Example prompts and workflows

2. **Feature Development Guide**

   * Step-by-step guide starting with the first module (e.g., Portal do Operador)
   * Full implementation sequence per agent
   * Integration rules between agents
   * UI/UX flow, mocks, and business logic

3. **Agent Coordination**

   * How agents communicate
   * How conflicts are resolved
   * How to execute agents sequentially or in parallel

4. **Mock API Integration**

   * Folder structure for mocks
   * How ViewModels/services consume mocks
   * How to swap mocks for real endpoints

5. **Documentation Flow**

   * How Documentation agents track all features, agents, APIs, and design

---

## 6️⃣ Output Requirements

The output must:

* Be **structured, detailed, and actionable**
* Be immediately usable for project planning and implementation
* Avoid generic explanations
* Serve as a **complete multi-agent operating manual**
* Be adaptable to any project scenario:

  * With or without Figma/design
  * Any architecture
  * Any scale
* Include examples, prompts, and workflows for Copilot usage
