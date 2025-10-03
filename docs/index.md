# Architecture Decision Catalog

This catalog tracks all architectural decisions for software projects using this ADR-first development boilerplate. Each ADR includes embedded industry pattern analysis of existing patterns from industry references.

## 🏗️ System Architecture Overview

📋 **[System Architecture Diagram](architecture.md)** - Living bird's-eye view of the current system architecture, automatically updated as ADRs accumulate architectural decisions.

> **⚠️ Important:** The system architecture diagram MUST be updated whenever an ADR impacts system design, technology stack, or component relationships.

## Decision Tracking

### Status Legend
- 🟡 **Proposed**: Under consideration, needs approval
- 🟢 **Accepted**: Approved and ready for implementation  
- 🔴 **Deprecated**: No longer valid, replaced by newer decision
- 🔵 **Superseded**: Replaced by specific ADR reference

---

## Architecture Decision Records (ADRs)

| ID | Title | Status | Date | Tags | Quick Summary |
|----|-------|--------|------|------|---------------|
| [000](adr/adr-000-template.md) | ADR Template | 🟢 Accepted | 2025-09-17 | template | Standard format for all ADRs with embedded industry pattern analysis |
| [001](adr/adr-001-adr-first-development.md) | ADR-First Development and Documentation-Driven Architecture | 🟢 Accepted | 2025-09-19 | architecture, process, documentation, copilot, governance | Establishes ADR-first development with embedded industry pattern analysis as foundational process for development guidance and industry pattern synthesis |

---

## Quick Reference

### Current Phase
**Foundational Boilerplate** - Template ready for forking and adaptation to new projects

### Next ADRs (Project-Specific Examples)
- Technology Stack and Framework Selection
- Project Structure and Module Organization
- Development Tooling and Workflow Setup
- Core Architectural Patterns and Abstractions

### Common Architecture Themes to Consider
1. Application architecture pattern (MVC, hexagonal, microservices, monolith)
2. Data management strategy (databases, caching, state management)
3. API design and integration patterns (REST, GraphQL, event-driven)
4. Security and authentication approaches
5. Testing strategy and quality assurance
6. Deployment and infrastructure patterns
7. Monitoring, logging, and observability
8. Configuration management and environment handling
9. Error handling and resilience patterns
10. Performance optimization strategies
11. Third-party integrations and dependency management
12. Documentation and knowledge sharing practices

---

*This catalog is automatically updated as new ADRs are created during the development process. Fork this repository and adapt it for your specific project needs.*