# Roles and Personas

(Existing content preserved above this header in the original file.)

## Additional Recommended Roles

This section adds recommended personas to improve clarity of responsibility and cross-functional collaboration.

### Change Manager
- Responsibilities:
  - Plan and coordinate organizational change activities related to projects (communications, training, adoption).
  - Create change-impact analyses and stakeholder engagement plans.
  - Track readiness metrics and post-rollout adoption signals.
- Interactions with existing roles:
  - Project Manager: aligns rollout schedule and resource impacts.
  - Product Owner: ensures feature communication aligns with product priorities.
  - Communications Lead / Stakeholders: coordinates messaging and training.
- Why this matters / improvement:
  - Ensures smoother adoption of changes, reduces operational disruption, and clarifies who handles organizational impacts beyond delivery.

### Scrum Master / Agile Facilitator
- Responsibilities:
  - Facilitate Agile ceremonies (standups, sprint planning, retrospectives).
  - Remove impediments and protect team focus.
  - Coach the team on Agile practices and continuous improvement.
- Interactions with existing roles:
  - Team Leads / Developers: supports delivery flow and impediment removal.
  - Product Owner: helps refine backlog and coordinates priorities.
  - Project Manager: surfaces risks/velocity impacts to planning.
- Why this matters / improvement:
  - Improves team throughput and predictability, embeds process improvements, and reduces friction in cross-team delivery.

### Quality Assurance (QA) Specialist
- Responsibilities:
  - Define test strategies, acceptance criteria, and test plans.
  - Coordinate manual and automated testing and track test coverage.
  - Verify releases against acceptance criteria and maintain regression suites.
- Interactions with existing roles:
  - Developers: plan integration of tests and triage issues.
  - Product Owner: validate acceptance criteria and prioritize defects.
  - Release Manager / DevOps: coordinate release gating and environments.
- Why this matters / improvement:
  - Raises product quality, clarifies testing ownership, and reduces post-release defects.

### DevOps Engineer
- Responsibilities:
  - Design and maintain CI/CD pipelines, infrastructure-as-code, and monitoring.
  - Automate build, deployment, and rollback processes.
  - Maintain production reliability and observability practices.
- Interactions with existing roles:
  - Developers: integrate CI/CD and deployment patterns.
  - QA Specialist: provide environments and automation hooks for testing.
  - Release Manager: coordinate release automation and deployment windows.
- Why this matters / improvement:
  - Speeds safe delivery, reduces manual release steps, and improves incident response.

### User Researcher
- Responsibilities:
  - Plan and run user research and usability studies.
  - Synthesize findings into actionable insights and user needs.
  - Validate assumptions and measure feature impact with qualitative feedback.
- Interactions with existing roles:
  - Product Owner & UX Designer: inform prioritization and design decisions.
  - Project Manager: share research timelines and dependencies for planning.
- Why this matters / improvement:
  - Anchors product decisions in user evidence, reducing rework and aligning features with real user needs.

## How these roles integrate into existing processes

- Clear handoffs: Each role's responsibilities include explicit handoffs to existing roles (Project Manager, Product Owner, Team Leads) so the process docs show who does what at each stage.
- Decision points: Documented interactions define when a role must be consulted (e.g., Change Manager before large rollouts, QA signoff before release).
- Onboarding and staffing: The new template (docs/templates/persona-role-template.md) makes it easier to add future roles consistently.

(End of additions)
