# Awesome-Business-Rules-Management-System

# Top Business Rules Management System (BRMS) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Decision Automation, Rule Authoring & Business Logic Governance*  
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Business Rules Management Systems (BRMS)**. These tools enable organizations to author, test, deploy, and govern business rules and decision logic — separating volatile business policies from application code for faster change and greater transparency.

**Examples** include Red Hat Decision Manager, FICO Blaze Advisor, Pega Decisioning, IBM ODM, Drools, DecisionRules.io, OpenRules, FlexRule, Corticon, and TIBCO BusinessEvents (the category leaders).

**Open-source emphasis**: This section is expanded with active projects for self-hosting, custom rule authoring, and transparent decision governance — ideal for developers, business analysts, and enterprises building vendor-independent decision automation. The open-source BRMS ecosystem is anchored by **Drools** (now under Apache incubator) and a growing set of modern engines offering Excel-based authoring, visual decision graphs, and cross-platform embedded execution.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Red Hat Decision Manager](https://www.redhat.com/en/technologies/jboss-middleware/decision-manager)**  
  Enterprise business rules management system built on Drools and Kogito. Provides a centralized repository for business rules, decision tables, and DMN models with governance, versioning, and deployment tooling. Formerly JBoss Enterprise BRMS .

- **[FICO Blaze Advisor](https://www.fico.com/en/products/fico-blaze-advisor-decision-rules-management-system)**  
  Enterprise decision rules management system for authoring, testing, and deploying business rules. Widely used in financial services for credit, fraud, and compliance decisions.

- **[Pega Decisioning](https://www.pega.com/products/decisioning)**  
  AI-powered decisioning platform combining business rules with predictive analytics and adaptive learning for next-best-action and customer decision management.

- **[IBM ODM](https://www.ibm.com/products/operational-decision-manager)**  
  Operational Decision Manager for automating and governing business rule-based decisions. Supports decision tables, rule flows, and decision models with enterprise governance .

- **[DecisionRules.io](https://www.decisionrules.io/)**  
  Cloud-based decision rules engine and management platform with a visual rule editor, decision tables, and API-first deployment for real-time decision automation.

- **[OpenRules](https://openrules.com/)**  
  Business rules and decision management system with Excel-based rule authoring. Provides decision tables, rule engine, and deployment tools for Java-based enterprise applications.

- **[FlexRule](https://www.flexrule.com/)**  
  Decision automation platform with a visual rule designer, decision model and notation (DMN) support, and deployment options for enterprise rule-based systems.

- **[Corticon](https://www.progress.com/corticon)**  
  Decision automation platform (Progress Software) with a model-driven approach to business rules. No-code rule authoring with decision tables, rule flows, and testing capabilities.

- **[TIBCO BusinessEvents](https://www.tibco.com/products/tibco-businessevents)**  
  Event-driven business rules engine for real-time decisioning. Combines complex event processing with rule-based decision automation.

## Open-Source GitHub Projects

- **[Drools](https://github.com/apache/incubator-kie-drools)**  
  The most mature and widely adopted open-source BRMS, now under Apache incubator as part of the KIE (Knowledge Is Everything) project . Forward and backward chaining inference-based rules engine using an enhanced Rete algorithm implementation. Supports Java Rules Engine API (JSR 94). Current stable release 10.1.0 (July 2025) . Components include Drools Expert (rule engine), Drools Guvnor (business rules manager), Drools Fusion (complex event processing), and OptaPlanner (planning optimization). Apache-2.0 licensed with active development .

- **[ZEN Engine (GoRules)](https://github.com/gorules/zen)**  
  Cross-platform open-source Business Rules Engine written in Rust with native bindings for Node.js, Python, Go, Java, C#, Kotlin (JVM), Kotlin (Android), and Swift (iOS) . Decisions evaluate in microseconds and run identically on every platform, stored as portable JSON (JDM — JSON Decision Model). Version 2.0 introduces policy documents with typed data models, static type checking, and hardened runtime . The related **GoRules BRMS** provides a self-hosted management system with versioning, audit logs, and multi-workspace organization .

- **[OpenL Tablets](https://github.com/openl-tablets/openl-tablets)**  
  Open-source Business Rules Management System that lets business analysts create, test, and manage decision logic using familiar Excel spreadsheets, then deploy them as high-performance REST APIs . Features type-safe validation, compile-time error checking, hot reload for zero-downtime updates, Git integration for version control, and auto-generated OpenAPI documentation. Excel rules compile to native Java bytecode for maximum performance. Used in insurance, banking, healthcare, and retail for premium calculation, credit decisions, and dynamic pricing . Actively maintained with Docker Compose quick-start .

- **[Ordo](https://github.com/Pama-Lee/Ordo)**  
  Open-source decision platform built in Rust with sub-microsecond rule execution via JIT compilation (Cranelift) . Features visual flow editor and decision table authoring, full platform workspace with org/project management, release center with staged rollouts and rollback, decision contracts with typed schemas, and fact catalog governance. Runs everywhere: HTTP, gRPC, WASM, and CLI. Single binary or hosted platform deployment .

- **[ZEN Engine (phenixrizen fork)](https://github.com/phenixrizen/zen)**  
  Community-maintained fork of gorules/zen that accepts contributions (upstream does not) . Adds first-class `databaseNode` for reference data lookup from decision graphs, `zen-database-sqlite` handler with bundled SQLite, decision-level `$params` for static parameters, and fixes for timezone handling and fractional number truncation. Same MIT license as upstream.

- **[Easy Rules](https://github.com/j-easy/easy-rules)**  
  Lightweight, POJO-based rules engine for Java. Simple but powerful with annotation-based rule definitions, rule composition (composite, unit, activation, conditional), and support for MVEL and SpEL expressions. Ideal for applications needing simple rule evaluation without the complexity of full BRMS platforms .

- **[NxBRE](https://github.com/ddossot/NxBRE)**  
  .NET lightweight business rules engine (Rule Based Engine) with forward-chaining inference engine and XML-driven flow control engine. Supports RuleML 0.9 Naf Datalog and Visio 2003 modeling. Suitable for .NET applications needing embedded rule evaluation .

- **[json-rules-engine](https://github.com/CacheControl/json-rules-engine)**  
  Lightweight forward-chaining rules engine for JavaScript and TypeScript projects. Rules defined as JSON with flexible conditions and events. Suitable for Node.js applications needing simple business rule evaluation without external dependencies .

- **[Node-rules](https://github.com/mithunsatheesh/node-rules)**  
  Lightweight forward chaining rule engine for JavaScript and TypeScript. Simple API for defining rules with conditions and consequences. Actively maintained .

### Additional Strong Open-Source Options

- **OpenRules** — Java-based business rules engine with Excel-based authoring and decision table support .
- **InfoSapient** — Pure Java open-source rules engine for expressing, executing, and maintaining business rules within a company. Uses multiple design patterns (MVC, Visitor, Strategy, Facade, Factory Method, Observer, Iterator) .
- **JLisa** — Java framework for building business rules implementing JSR94 Rule Engine API .
- **Mandarax** — Pure Java rule engine supporting multiple fact types and rule reflection, databases, EJB, and XML standard (RuleML 0.8) with backward chaining .
- **Evrete** — Lightweight and intuitive Java rule engine .
- **ice (Java规则引擎)** — Lightweight, high-performance abstract orchestration solution for complex/flexibly changing business rules with visual operation pages. Go-based .
- **Kumi** — Declarative rules-and-calculation DSL for Ruby that statically analyzes and compiles business logic .
- **Power Flows DMN** — Powerful decisions and rules engine for Java with DMN support .

**Frameworks for building custom BRMS solutions**: Combine **Drools** for a mature, enterprise-proven rule engine with backward chaining and complex event processing capabilities . Use **OpenL Tablets** for Excel-based rule authoring that business analysts can own and maintain without developer intervention . Deploy **ZEN Engine** for cross-platform, embedded decision evaluation with microsecond latency and native bindings for every major language . Leverage **Ordo** for a modern Rust-based decision platform with visual authoring, governance features, and sub-microsecond JIT-compiled execution . For simple Java applications, **Easy Rules** provides POJO-based rule evaluation without BRMS complexity. Note that enterprise BRMS platforms with centralized rule repositories, multi-environment deployment workflows, and regulatory audit trails remain primarily commercial territory; open-source stacks provide strong rule engines, Excel-based authoring, and embedded decision evaluation that require integration for complete business rules governance.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Business rules management tools must comply with applicable regulations, internal governance policies, and audit requirements.
- Self-hosted open-source solutions require proper infrastructure, rule versioning discipline, and ongoing maintenance. Rule engines are not a substitute for business analyst review and testing.
- The open-source ecosystem provides strong rule engines, Excel-based authoring, and embedded decision evaluation, but full enterprise BRMS platforms with centralized governance, multi-environment deployment workflows, and regulatory audit trails remain primarily commercial offerings.

---

**Made for business analysts, decision architects, developers, and enterprise automation teams.**  
Let's make business rules management more open, transparent, and adaptable.
