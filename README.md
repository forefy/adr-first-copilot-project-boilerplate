# ADR-First Development Boilerplate

A **specification-first development foundation** that can be forked and adapted for any software project. This boilerplate establishes architectural discipline through ADR-first development practices, embedding industry best practices synthesis into project decision-making.

> **What is an ADR?** An **Architecture Decision Record (ADR)** is a document that captures important architectural decisions made during a project, along with their context, consequences, and reasoning. ADRs help teams maintain a clear audit trail of why specific technical choices were made.

## What This Provides

✅ **ADR-First Process** - All architectural decisions documented before implementation  
✅ **Living Architecture Diagram** - Mermaid UML diagram that evolves with each ADR decision  
✅ **Industry Pattern Analysis Framework** - Systematic extraction of patterns from industry references  
✅ **Copilot Instructions Integration** - AI coding assistants follow documented architectural guidance  
✅ **Trade-off Documentation** - Explicit capture of architectural trade-offs and reasoning  
✅ **Decision Traceability** - Clear audit trail of why specific architectural choices were made  

## Why ADR-First Development?

Projects succeed when architectural decisions are **explicit, well-reasoned, and consistently applied** throughout development. This boilerplate provides:

- **Engineering Discipline** - Prevents architectural drift through documented decision-making
- **Industry Pattern Learning** - Systematic analysis of proven approaches from reference projects  
- **Team Alignment** - Single source of truth for architectural decisions
- **AI Assistant Guidance** - Clear instructions for AI coding tools to follow project patterns
- **Scalable Process** - Works for teams of any size and projects of any complexity

## Getting Started

### 1. Fork This Repository
```bash
git clone <your-fork-url>
cd your-project
```

### 2. Customize for Your Project
1. **Update Vision**: Edit `.github/copilot-instructions.md` with your specific project vision
2. **Create Foundational ADRs**: Document your core architectural decisions using the provided template

### 3. Start Making Architectural Decisions
```bash
# Copy the template for your first project-specific ADR
cp docs/adr/adr-000-template.md docs/adr/adr-002-your-decision.md
# Edit and document your architectural choice
# Update docs/index.md with the new ADR entry
```

## Repository Structure

```
.github/
  copilot-instructions.md     # AI assistant guidance and project vision
docs/
  index.md                    # ADR catalog and tracking
  architecture.md             # Living system architecture diagram (Mermaid UML)
  adr/
    adr-000-template.md      # Standard format for all ADRs
    adr-001-adr-first-development.md  # Foundational process ADR
```

## Core Development Workflow

1. **Identify Architectural Decision** → Create ADR with industry pattern analysis
2. **Research Existing Patterns** → Analyze proven approaches from similar projects
3. **Document Trade-offs** → Capture what you gain vs lose with each option
4. **Make Informed Decision** → Choose approach with clear reasoning
5. **Implement with Alignment** → Follow documented architectural guidelines
6. **Update Documentation** → Maintain ADR registry and cross-references

## Architecture Decision Records (ADRs)

Each ADR follows a structured format with:
- **Industry Pattern Analysis Table** - Systematic comparison of industry patterns
- **Options Considered** - Multiple approaches with explicit trade-offs
- **Architecture Diagrams** - Visual representation of the decision
- **Implementation Rollout** - Phased approach to changes
- **Trade-off Insights** - What architectural principle is being modeled

See [ADR Template](docs/adr/adr-000-template.md) for the complete format.

## AI Coding Assistant Integration

The `.github/copilot-instructions.md` file provides explicit guidance for AI coding assistants to:
- Follow documented architectural patterns
- Respect ADR decisions as single source of truth
- Stop at checkpoints before major changes
- Check alignment against project vision
- Output conflict reports when proposals differ from accepted ADRs

## Common Architecture Themes

When creating ADRs for your project, consider these architectural dimensions:

1. **Application Architecture** - MVC, hexagonal, microservices, monolith patterns
2. **Data Management** - Database selection, caching strategies, state management
3. **API Design** - REST vs GraphQL, event-driven patterns, integration approaches
4. **Security & Auth** - Authentication methods, authorization patterns, security layers
5. **Testing Strategy** - Unit, integration, e2e testing approaches and tools
6. **Deployment** - Infrastructure patterns, CI/CD, environment management
7. **Observability** - Monitoring, logging, metrics, and debugging strategies
8. **Performance** - Optimization strategies, caching, scaling patterns
9. **Configuration** - Environment handling, feature flags, secrets management
10. **Dependencies** - Third-party integration patterns, vendor lock-in avoidance

## Examples of ADR Decisions

- **ADR-002**: Technology Stack Selection (React vs Vue vs Angular)
- **ADR-003**: Database Architecture (PostgreSQL vs MongoDB vs hybrid approach)  
- **ADR-004**: API Design Pattern (REST with OpenAPI vs GraphQL federation)
- **ADR-005**: Authentication Strategy (OAuth2 + JWT vs session-based vs magic links)
- **ADR-006**: Testing Architecture (Jest + Testing Library vs Cypress + Playwright)

## Contributing

This is a boilerplate template designed to be forked and adapted. If you have improvements to the **process itself** (not project-specific content), please contribute back:

1. Fork the original boilerplate repository
2. Create an ADR for your proposed process improvement
3. Submit a pull request with your enhancement

## License

This boilerplate is provided under MIT License. Fork freely and adapt for your projects.

---

**Ready to start?** Fork this repository and begin documenting your architectural decisions. Your future self (and your team) will thank you for the clarity and discipline.