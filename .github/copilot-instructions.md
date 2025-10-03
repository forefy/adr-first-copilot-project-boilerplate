# Copilot Instructions

You are a contributor inside this repository.  
Always follow these rules:

## Project Vision: ADR-First Development Boilerplate

### Mission
Provide a **specification-first development foundation** that can be forked and adapted for any software project:  
- Establish architectural discipline through ADR-first development practices
- Embed industry best practices synthesis into project decision-making
- Create reusable patterns for documentation-driven development

### Core Principles
- **Engineering Discipline First** - All architectural decisions follow documented ADR process
- **Documentation-Driven Development** - Every decision includes trade-off analysis and reasoning
- **Industry Best Practices Synthesis** - Architecture decisions reflect proven patterns with industry pattern analysis
- **Modular Architecture** - Plugin-ready, composable designs that avoid vendor lock-in
- **Decision Traceability** - Clear audit trail of architectural choices and reasoning

### Development Workflow
1. **Identify architectural decision** → create ADR with industry pattern analysis
2. **Research existing patterns** → analyze proven approaches from similar projects  
3. **Document trade-offs** → capture what you gain vs lose with each option
4. **Make informed decision** → choose approach with clear reasoning
5. **Implement with alignment** → follow documented architectural guidelines
6. **Update documentation** → maintain ADR registry and cross-references
7. **Update system architecture** → reflect changes in `/docs/architecture.md`

## Current Phase: Foundational Boilerplate

**Context:** This repository serves as a template for starting new projects with disciplined architectural practices.

**Key Insight:** Projects succeed when architectural decisions are explicit, well-reasoned, and consistently applied throughout development.

**Immediate Deliverables for New Projects:**
- Foundational ADRs with embedded industry pattern analysis:
  - Technology stack and framework selection
  - Project structure and module organization  
  - Development tooling and workflow
  - Core architectural patterns and abstractions
- Stop at checkpoint gates before major implementation phases

**Success Criteria for Project Setup:**
- Clear architectural vision documented in ADRs
- Industry pattern analysis informing technology choices
- Development discipline established through process documentation
- Trade-off insights captured for future decision reference
- Updated `/docs/index.md` with project-specific entries

## Core Discipline
- **ADR-First**: All architectural decisions follow documented ADR process with industry pattern analysis
- **System Architecture Maintenance**: Every accepted ADR must update `/docs/architecture.md` if it impacts system design, technology stack, or component relationships
- **Stop at Checkpoints** before major implementation phases
- **Check alignment** against project Vision and accepted ADRs before proceeding
- **Vision Evolution**: Update Vision section above when development reveals insights about mission, principles, or workflow
- **Conflict Resolution**: If any proposal conflicts with Vision or accepted ADRs, STOP and output a Conflict Report

## Documentation Standards
- **ADRs**: follow `/docs/adr/adr-000-template.md` format with embedded industry pattern analysis
- **Updates**: keep `/docs/index.md` current with all new ADR entries
- **Trade-off Insights**: Every ADR must explain architectural trade-offs being modeled

---

*This boilerplate provides the foundation for specification-first development. Fork this repository and adapt the Vision section above for your specific project needs.*