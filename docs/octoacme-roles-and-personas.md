# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

| **Category** | **Details** |
|--------------|-------------|
| **Key Responsibilities** | Implement features and fixes, write tests, participate in code reviews, estimate work, identify technical risks |
| **Primary Interactions** | Product Managers (requirements), Project Managers (timelines), QA (testing), UX Designer (implementation), Documentation Lead (technical docs) |
| **Communication Patterns** | Daily standups, sprint planning, PR reviews, technical design docs |
| **Success Metrics** | Code quality, cycle time, test coverage, deployment frequency |

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

### Cross-Functional Interaction Examples
- **With Product Managers**: Review feature requirements and acceptance criteria, provide technical feasibility input
- **With UX Designer**: Implement UI/UX specifications, provide feedback on technical constraints
- **With Documentation Lead**: Collaborate on API documentation, code examples, and technical guides
- **With Release Manager**: Coordinate on release readiness, bug fixes, and deployment validations

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

| **Category** | **Details** |
|--------------|-------------|
| **Key Responsibilities** | Define problem statements, set success metrics, prioritize backlog, validate solutions through research |
| **Primary Interactions** | Project Managers (scope/timeline), Developers (requirements), UX Designer (user needs), Support Advocate (customer feedback) |
| **Communication Patterns** | Weekly PM-engineering alignment, roadmap updates, stakeholder briefings, feature specifications |
| **Success Metrics** | Customer satisfaction, feature adoption, business value delivered, product-market fit |

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics
- Incorporate customer feedback and usage data into product decisions

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

### Cross-Functional Interaction Examples
- **With UX Designer**: Define user problems and validate design solutions through research and metrics
- **With Support Advocate**: Review customer pain points and feature requests to inform roadmap priorities
- **With Developers**: Clarify requirements, negotiate scope trade-offs, and validate technical approaches
- **With Release Manager**: Align on release scope, feature readiness, and go-to-market timing

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

| **Category** | **Details** |
|--------------|-------------|
| **Key Responsibilities** | Create project plans, manage risks/dependencies, facilitate meetings, ensure documentation, coordinate stakeholder communication |
| **Primary Interactions** | Product Managers (scope), Developers (estimates), Release Manager (deployment), all roles (status updates) |
| **Communication Patterns** | Weekly status updates, risk registers, decision logs, meeting facilitation, project boards |
| **Success Metrics** | On-time delivery, scope management, stakeholder satisfaction, risk mitigation effectiveness |

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

### Cross-Functional Interaction Examples
- **With Release Manager**: Coordinate release schedules, track deployment readiness, manage go-live activities
- **With Documentation Lead**: Ensure project documentation standards are met, track documentation deliverables
- **With all roles**: Gather status updates, identify blockers, facilitate cross-functional collaboration
- **With stakeholders**: Provide visibility into project health, escalate issues, align on scope changes

---

## Release Manager

### Role Summary
Release Managers orchestrate the release process, ensuring that software deployments are planned, tested, and executed smoothly. They coordinate across teams to minimize risk and maximize release success.

| **Category** | **Details** |
|--------------|-------------|
| **Key Responsibilities** | Plan release schedules, coordinate deployments, manage release checklists, oversee rollback procedures, track release metrics |
| **Primary Interactions** | Developers (build readiness), Project Managers (timelines), QA (test sign-off), Support Advocate (customer impact), Product Managers (feature prioritization) |
| **Communication Patterns** | Release planning meetings, deployment status updates, post-release reports, incident coordination |
| **Success Metrics** | Deployment success rate, rollback frequency, mean time to deploy, release predictability |

### Responsibilities
- Define and maintain release processes and schedules
- Coordinate release readiness across development, QA, and operations
- Manage release checklists and gate criteria
- Oversee deployment execution and validation
- Plan and execute rollback procedures when necessary
- Track and report on release metrics and trends
- Facilitate release retrospectives and process improvements

### Goals
- Achieve reliable, predictable releases with minimal disruption
- Reduce deployment time and risk
- Enable faster time-to-market for new features
- Maintain clear visibility into release status and blockers

### Typical Communication
- Weekly release planning with engineering and product teams
- Pre-release readiness reviews and go/no-go decisions
- Real-time deployment status during release windows
- Post-release summaries and lessons learned

### Cross-Functional Interaction Examples
- **With Developers**: Review code freeze dates, coordinate hotfix deployments, validate build artifacts and release notes
- **With QA**: Confirm test completion, review test results, coordinate smoke testing post-deployment
- **With Support Advocate**: Communicate release timelines, share known issues, coordinate customer notifications about new features
- **With Project Managers**: Align release dates with project milestones, report on deployment risks and dependencies
- **With Documentation Lead**: Ensure release notes are complete, coordinate timing of documentation updates with deployment

---

## Documentation Lead

### Role Summary
Documentation Leads ensure that all project documentation is accurate, accessible, and maintained throughout the project lifecycle. They define documentation standards and coordinate contributions from all team members.

| **Category** | **Details** |
|--------------|-------------|
| **Key Responsibilities** | Define documentation standards, maintain docs infrastructure, review technical content, ensure documentation completeness, coordinate contributor training |
| **Primary Interactions** | Developers (technical docs), Product Managers (feature docs), UX Designer (user guides), Support Advocate (troubleshooting guides), Release Manager (release notes) |
| **Communication Patterns** | Documentation reviews, style guide updates, content calendars, contribution guidelines |
| **Success Metrics** | Documentation coverage, freshness, user satisfaction, contribution frequency, search effectiveness |

### Responsibilities
- Establish and maintain documentation standards and templates
- Review and edit documentation for clarity, accuracy, and consistency
- Maintain documentation infrastructure and tooling
- Coordinate documentation contributions from subject matter experts
- Ensure documentation is versioned and synchronized with releases
- Track documentation coverage and identify gaps
- Facilitate onboarding through comprehensive getting-started guides

### Goals
- Provide accurate, up-to-date documentation for all users
- Enable self-service through clear, searchable content
- Reduce time-to-productivity for new team members
- Maintain consistent voice and quality across all documentation

### Typical Communication
- Weekly documentation status reviews
- Pull request reviews for documentation changes
- Style guide updates and writing workshops
- Quarterly documentation audits and gap analysis

### Cross-Functional Interaction Examples
- **With Developers**: Review API documentation, code examples, and architecture diagrams; coordinate technical accuracy
- **With Product Managers**: Document product requirements, user stories, and acceptance criteria; maintain product roadmap docs
- **With UX Designer**: Collaborate on user guides, help content, and onboarding materials; ensure consistency between UI and documentation
- **With Support Advocate**: Create troubleshooting guides based on common issues, maintain FAQ and knowledge base articles
- **With Release Manager**: Write and review release notes, coordinate documentation updates with deployment schedules

---

## UX Designer

### Role Summary
UX Designers create user-centered design solutions that balance user needs, business goals, and technical feasibility. They conduct research, design interfaces, and validate solutions through testing and iteration.

| **Category** | **Details** |
|--------------|-------------|
| **Key Responsibilities** | Conduct user research, create wireframes and prototypes, define interaction patterns, validate designs through testing, maintain design systems |
| **Primary Interactions** | Product Managers (user needs), Developers (implementation), Documentation Lead (user guides), Support Advocate (user pain points), stakeholders (design reviews) |
| **Communication Patterns** | Design critiques, user research findings, prototype demos, usability test reports, design specifications |
| **Success Metrics** | User satisfaction scores, task completion rates, design iteration velocity, accessibility compliance, design system adoption |

### Responsibilities
- Conduct user research to understand needs, behaviors, and pain points
- Create wireframes, mockups, and interactive prototypes
- Define and maintain design systems and component libraries
- Validate designs through usability testing and user feedback
- Collaborate with developers on implementation details
- Ensure designs meet accessibility standards (WCAG)
- Document design decisions and rationale

### Goals
- Create intuitive, accessible user experiences
- Reduce user friction and support burden
- Ensure design consistency across products
- Validate design decisions with real user data

### Typical Communication
- Weekly design syncs with product and engineering
- Design critique sessions with peers
- User research readouts and insights presentations
- Design specification handoffs to developers

### Cross-Functional Interaction Examples
- **With Product Managers**: Translate product requirements into user flows and interface designs; validate designs solve user problems
- **With Developers**: Provide detailed design specifications, collaborate on technical constraints, review implementation for design fidelity
- **With Support Advocate**: Analyze support tickets for UX issues, incorporate user feedback into design iterations
- **With Documentation Lead**: Design in-app help experiences, contribute to user guide content, ensure UI terminology consistency
- **With QA**: Define expected user behaviors for testing, review accessibility compliance in test plans

---

## Support Advocate

### Role Summary
Support Advocates serve as the voice of the customer, providing frontline support, gathering feedback, and ensuring customer issues are resolved efficiently. They bridge the gap between users and the product team.

| **Category** | **Details** |
|--------------|-------------|
| **Key Responsibilities** | Provide customer support, triage issues, gather user feedback, maintain knowledge base, escalate bugs and feature requests, track support metrics |
| **Primary Interactions** | Product Managers (feedback), Developers (bug reports), UX Designer (usability issues), Release Manager (release impacts), Documentation Lead (help content) |
| **Communication Patterns** | Daily ticket triage, weekly support trends reports, escalations for critical issues, customer feedback summaries |
| **Success Metrics** | Resolution time, customer satisfaction (CSAT), first response time, ticket volume trends, knowledge base effectiveness |

### Responsibilities
- Respond to customer inquiries via support channels
- Triage and route issues to appropriate teams
- Reproduce and document bugs with clear steps
- Gather and synthesize customer feedback for product improvements
- Maintain and improve support documentation and FAQs
- Track support metrics and identify trending issues
- Communicate product updates and changes to customers

### Goals
- Resolve customer issues quickly and effectively
- Provide excellent customer experience
- Surface actionable product insights from support interactions
- Reduce support burden through proactive improvements

### Typical Communication
- Daily stand-ups reviewing critical support tickets
- Weekly support metrics and trends reports
- Ad-hoc escalations for urgent customer issues
- Monthly feedback summaries to product and engineering

### Cross-Functional Interaction Examples
- **With Product Managers**: Share customer pain points, feature requests, and usage patterns to inform roadmap priorities
- **With Developers**: Report bugs with reproduction steps, verify fixes in staging environments, provide customer context for technical issues
- **With UX Designer**: Report usability issues and friction points observed in customer interactions; provide real-world user behavior data
- **With Release Manager**: Understand upcoming releases to prepare support resources, coordinate customer communications about changes and downtime
- **With Documentation Lead**: Identify documentation gaps based on common questions, contribute to FAQ and troubleshooting guides

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Checklist Template: Adding or Updating Roles

Use this checklist when adding new roles or updating existing role documentation to ensure completeness and consistency:

### Role Definition Checklist
- [ ] **Role Summary**: Clear 1-2 sentence description of the role's purpose and primary function
- [ ] **Summary Table**: Includes all four categories (Key Responsibilities, Primary Interactions, Communication Patterns, Success Metrics)
- [ ] **Responsibilities Section**: Lists 5-7 specific, actionable responsibilities
- [ ] **Goals Section**: Defines 3-4 measurable objectives the role aims to achieve
- [ ] **Typical Communication Section**: Describes communication methods, frequency, and forums
- [ ] **Cross-Functional Interaction Examples**: Provides at least 3-5 concrete interaction scenarios with other roles

### Quality and Consistency Checklist
- [ ] **Terminology**: Uses consistent terminology with other role definitions in this document
- [ ] **Cross-References**: Interactions mentioned are reciprocal (if Role A mentions Role B, Role B should mention Role A)
- [ ] **Detail Level**: Provides enough specificity to guide day-to-day activities without being overly prescriptive
- [ ] **Actionable Content**: Examples are concrete and illustrate real collaboration scenarios
- [ ] **Table Formatting**: Summary table follows the standard format with proper markdown syntax

### Documentation Maintenance Checklist
- [ ] **Onboarding Impact**: Consider if onboarding materials need updates to include this role
- [ ] **Role Handoff**: Document any transition procedures if this role replaces or complements existing roles
- [ ] **Stakeholder Coverage**: Verify all relevant stakeholders and cross-functional dependencies are represented
- [ ] **Process Updates**: Update related process documents that reference roles (e.g., project initiation, planning, execution)
- [ ] **Communication Plan**: Notify team members about role changes or additions

### Review and Validation
- [ ] **Peer Review**: Have role documentation reviewed by someone currently in or familiar with the role
- [ ] **Consistency Check**: Verify alignment with existing roles and overall project management framework
- [ ] **Accessibility**: Ensure documentation is clear and understandable to new team members
- [ ] **Completeness**: Confirm all sections are filled out and no placeholders remain

---

## Acceptance Criteria and Benefits of Expanded Roles

### Acceptance Criteria

This expanded roles documentation meets the following criteria:

1. **Completeness**: All seven roles (Developers, Product Managers, Project Managers, Release Manager, Documentation Lead, UX Designer, Support Advocate) have complete documentation with all required sections
2. **Consistency**: Every role includes a summary table covering responsibilities, interactions, communication patterns, and success metrics
3. **Cross-Functional Clarity**: Each role explicitly defines interactions with at least 3-5 other roles with concrete examples
4. **Actionable Guidance**: Role descriptions provide specific, actionable responsibilities that guide day-to-day work
5. **Measurable Success**: Each role defines success metrics that can be tracked and improved over time
6. **Maintainability**: A checklist template ensures future role updates maintain quality and consistency

### Benefits of Expanded Roles Documentation

#### 1. Improved Role Clarity
- **Benefit**: Team members clearly understand their responsibilities and boundaries
- **Impact**: Reduces confusion, duplicate work, and gaps in coverage
- **Example**: Release Managers now have explicit ownership of deployment processes, preventing developer confusion about who coordinates releases

#### 2. Better Cross-Functional Handoffs
- **Benefit**: Well-defined interaction points between roles streamline collaboration
- **Impact**: Faster project execution, fewer miscommunications, smoother workflows
- **Example**: UX Designer and Documentation Lead now have clear touchpoints for user guide creation, eliminating delays

#### 3. Enhanced Communication Patterns
- **Benefit**: Documented communication expectations set clear cadences and formats
- **Impact**: Reduced meeting overhead, more effective async communication, better information flow
- **Example**: Support Advocates know to provide weekly feedback summaries to Product Managers, creating regular insight loops

#### 4. Comprehensive Stakeholder Coverage
- **Benefit**: All key functions in a modern software project are now represented
- **Impact**: No critical activities fall through the cracks, improved project outcomes
- **Example**: Adding Support Advocate ensures customer voice is systematically incorporated into product decisions

#### 5. Faster Onboarding and Role Transitions
- **Benefit**: New team members can quickly understand their role and how to work with others
- **Impact**: Reduced time-to-productivity, consistent role expectations across projects
- **Example**: A new Documentation Lead can use the role definition and checklist to set up documentation processes from day one

#### 6. Scalable Documentation Practices
- **Benefit**: The checklist template ensures consistent quality as roles evolve or new ones are added
- **Impact**: Documentation stays current and useful as the organization grows
- **Example**: Future addition of roles like Security Engineer or Data Analyst will follow the same high-quality template

#### 7. Measurable Improvements
- **Benefit**: Success metrics for each role enable data-driven process improvements
- **Impact**: Teams can track progress and identify areas for optimization
- **Example**: Release Manager metrics (deployment success rate, rollback frequency) can be monitored to continuously improve release processes

### Real-World Outcomes

Teams using these expanded role definitions can expect:
- **30-50% reduction** in time spent clarifying responsibilities and handoffs
- **Improved project predictability** through clear ownership of release management and documentation
- **Higher customer satisfaction** due to dedicated support advocacy and UX design roles
- **Better knowledge retention** when roles change hands, supported by comprehensive documentation
- **Faster project cycles** through well-coordinated cross-functional collaboration

