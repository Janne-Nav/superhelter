# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

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

### Collaboration with Other Roles
- **Product Managers**: Implements features based on acceptance criteria and provides technical feasibility input
- **Project Managers**: Reports progress and raises blockers or technical risks
- **Scrum Master**: Participates in agile ceremonies and requests help removing impediments
- **UX Designer**: Collaborates on implementation details and design system usage
- **DevOps Engineer**: Uses CI/CD pipelines and coordinates deployment requirements
- **Security Lead**: Follows secure coding practices and addresses security findings

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

### Collaboration with Other Roles
- **Developers**: Provides acceptance criteria and validates technical feasibility
- **Project Managers**: Aligns on priorities and manages stakeholder expectations
- **Scrum Master**: Works on backlog refinement and sprint planning
- **UX Designer**: Collaborates on user research and validates design solutions
- **Support/Customer Success**: Reviews customer feedback and prioritizes bug fixes
- **Business Stakeholders**: Presents roadmap and justifies prioritization decisions

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

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

### Collaboration with Other Roles
- **Developers**: Tracks progress, manages dependencies, and coordinates releases
- **Product Managers**: Aligns on scope changes and manages timeline impacts
- **Scrum Master**: Coordinates on team ceremonies and impediment escalation
- **DevOps Engineer**: Plans deployment schedules and coordinates maintenance windows
- **Security Lead**: Ensures security requirements are integrated into project plans
- **Business Stakeholders**: Reports progress and escalates decision needs

---

## Scrum Master

### Role Summary
Scrum Masters facilitate agile ceremonies, remove blockers, and coach teams on agile practices. They ensure the team follows agreed processes while fostering continuous improvement and team health.

### Responsibilities
- Facilitate standups, sprint planning, retrospectives, and demos
- Remove impediments and escalate blockers
- Coach team members on agile practices and self-organization
- Track sprint metrics (velocity, burndown, cycle time)
- Foster psychological safety and team collaboration
- Shield the team from external disruptions

### Goals
- Maximize team velocity and predictability
- Reduce waste and improve flow efficiency
- Build a self-organizing, high-performing team
- Create an environment of continuous learning

### Typical Communication
- Daily facilitation of standups and team syncs
- Sprint planning and retrospective facilitation
- Regular check-ins with Product Manager and Project Manager
- Escalation of impediments to stakeholders

### Collaboration with Other Roles
- **Developers**: Coaches on agile practices, removes blockers affecting delivery
- **Product Managers**: Facilitates backlog refinement and ensures clear acceptance criteria
- **Project Managers**: Coordinates on dependencies and risk escalation
- **DevOps Engineer**: Works together on CI/CD improvements and deployment efficiency

---

## UX Designer

### Role Summary
UX Designers create user-centered design solutions that balance user needs, business goals, and technical constraints. They conduct research, create prototypes, and validate designs through user testing.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and high-fidelity mockups
- Define information architecture and user flows
- Maintain design systems and component libraries
- Validate designs with users and iterate based on feedback
- Collaborate with developers on implementation feasibility

### Goals
- Deliver intuitive, accessible user experiences
- Reduce friction and improve user satisfaction
- Ensure design consistency across products
- Advocate for user needs in product decisions

### Typical Communication
- Design reviews and critique sessions
- User research findings and insights presentations
- Prototype walkthroughs with stakeholders
- Handoff documentation and specs for developers

### Collaboration with Other Roles
- **Product Managers**: Collaborates on user needs and feature prioritization
- **Developers**: Works closely on implementation details and design system usage
- **Support/Customer Success**: Gathers feedback on pain points and usability issues
- **Business Stakeholders**: Validates designs against business objectives

---

## DevOps Engineer

### Role Summary
DevOps Engineers build and maintain infrastructure, CI/CD pipelines, and deployment automation. They enable reliable, secure, and efficient software delivery through infrastructure as code and observability.

### Responsibilities
- Design and maintain CI/CD pipelines
- Manage infrastructure provisioning and configuration
- Implement monitoring, logging, and alerting systems
- Automate deployment and rollback procedures
- Ensure security compliance and vulnerability management
- Optimize build times and deployment reliability

### Goals
- Achieve fast, reliable deployments with minimal manual intervention
- Maintain high system uptime and performance
- Reduce time from commit to production
- Implement security best practices in the delivery pipeline

### Typical Communication
- Post-deployment reports and incident reviews
- Infrastructure change proposals and runbooks
- Collaboration on deployment schedules and maintenance windows
- Alerting and on-call rotations coordination

### Collaboration with Other Roles
- **Developers**: Provides tooling and automation for efficient development workflows
- **Security Lead**: Implements security controls and compliance requirements
- **Project Managers**: Coordinates deployment timelines and release schedules
- **Scrum Master**: Works on continuous improvement of deployment processes

---

## Support/Customer Success

### Role Summary
Support and Customer Success teams serve as the voice of the customer, providing assistance, gathering feedback, and ensuring customer satisfaction. They bridge the gap between users and the product team.

### Responsibilities
- Respond to customer inquiries and support tickets
- Troubleshoot issues and escalate bugs to engineering
- Document common issues and create help articles
- Gather customer feedback and feature requests
- Track customer satisfaction metrics (CSAT, NPS)
- Onboard new customers and provide training

### Goals
- Achieve high customer satisfaction and retention
- Reduce time to resolution for customer issues
- Identify patterns in customer feedback for product improvements
- Enable customer self-service through documentation

### Typical Communication
- Daily ticket triage and escalation to engineering
- Weekly summaries of common issues and feature requests
- Customer feedback sessions and feedback loops to product team
- Documentation updates and knowledge base maintenance

### Collaboration with Other Roles
- **Product Managers**: Shares customer insights and feature requests
- **Developers**: Escalates bugs and provides reproduction steps
- **UX Designer**: Reports usability issues and user pain points
- **Business Stakeholders**: Reports on customer health and retention metrics

---

## Security Lead

### Role Summary
Security Leads define and enforce security standards, conduct threat assessments, and ensure compliance with security policies. They work across teams to embed security throughout the development lifecycle.

### Responsibilities
- Conduct security reviews and threat modeling
- Define security requirements and compliance standards
- Perform code security audits and vulnerability assessments
- Manage incident response and security investigations
- Provide security training and awareness programs
- Monitor security alerts and coordinate remediation

### Goals
- Minimize security vulnerabilities and attack surface
- Ensure compliance with industry standards (SOC2, GDPR, etc.)
- Build security awareness across the organization
- Enable secure-by-default development practices

### Typical Communication
- Security review findings and remediation plans
- Monthly security posture reports
- Incident response coordination and post-mortems
- Security policy updates and training sessions

### Collaboration with Other Roles
- **Developers**: Reviews code for security issues and provides secure coding guidance
- **DevOps Engineer**: Implements security controls in infrastructure and CI/CD
- **Product Managers**: Advises on security implications of features
- **Project Managers**: Coordinates security requirements in project planning

---

## Business Stakeholder

### Role Summary
Business Stakeholders represent business units, executive leadership, or key customer segments. They provide strategic direction, funding, and ultimate authority on business decisions affecting the product.

### Responsibilities
- Define business objectives and success criteria
- Approve budgets, resources, and major project decisions
- Provide strategic direction and prioritization guidance
- Review progress and hold teams accountable to commitments
- Represent business interests in trade-off decisions
- Champion change management and adoption initiatives

### Goals
- Maximize return on investment (ROI)
- Ensure alignment with business strategy and market needs
- Drive adoption and business value realization
- Minimize business risk and compliance exposure

### Typical Communication
- Monthly business reviews and strategic planning sessions
- Quarterly roadmap reviews and budget approvals
- Executive briefings on key initiatives and risks
- Sign-off on major releases and go-to-market decisions

### Collaboration with Other Roles
- **Product Managers**: Sets strategic priorities and business objectives
- **Project Managers**: Reviews progress and approves scope changes
- **Support/Customer Success**: Reviews customer satisfaction and adoption metrics
- **Security Lead**: Approves security investments and compliance initiatives

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

