# Allan Dominguez

**Backend Software Engineer | Python, Django, PostgreSQL | AWS, Distributed Systems**

---

## Professional Summary

Backend Software Engineer with 5+ years of experience building scalable, high-availability systems using Python, Django, and PostgreSQL. Proven track record of improving system performance, reliability, and developer productivity in distributed architectures. Experienced in API design, domain-driven design, and cloud-based deployment on AWS. Uses AI tooling to optimise day-to-day development while staying close to design and implementation.

---

## Skills

| Languages | Python, TypeScript, Java, C#, Go (familiar) |
| :---- | :---- |
| Backend | Django, REST APIs, PostgreSQL, SQLAlchemy, Pytest, Microservices |
| Frontend | React, TypeScript, HTML, CSS |
| Cloud & DevOps | AWS (EC2, RDS, CloudWatch), Docker, CI/CD (Buildkite, TeamCity), Terraform (familiar) |
| Practices | Domain-Driven Design, Clean Architecture, TDD, Distributed Systems, AI-Assisted Development |

---

## Experience

| **Career Break** | *January 2025 – Present* |
| :---- | ----: |

*Family Responsibilities, Career Reassessment & Professional Development*

**Family Responsibilities (January – October 2025)**

- Following redundancy from Iress in a company-wide restructure, made a deliberate decision to put family first, supporting my family through health challenges.
- Scaled back the job search to focus on caregiving and family responsibilities, applying selectively.

**Transition & Career Reassessment (November 2025 – May 2026)**

- Reassessed career direction and professional goals as personal circumstances became more manageable, and committed to refreshing and broadening my technical skills.
- Studied system design (consistency and availability trade-offs, caching and scalability patterns, practice designs such as rate limiters and notification systems) and data structures and algorithms, including a year-long NeetCode subscription.
- Built an authentication service with native Django REST Framework (custom user model, JWT access and refresh tokens) for an earlier React Native app, deepening my Django and full-stack TypeScript skills.

**Professional Development & Job Search (June 2026 – Present)**

- Project "Still": Designed and built a privacy-first daily photo journal for Android using React Native (TypeScript) and Expo; shipped the core capture-to-calendar flow end-to-end as a personal-use alpha build running on-device (see Projects).
- Adopted AI-assisted development (Claude Code) and built a custom workflow around it: project instructions, persistent memory, reusable skills and guardrail hooks, plus a streamlined job-application workflow, while directing the architecture and reviewing every change.
- Currently upskilling in Go to deepen my backend knowledge in a more modern stack.

---

| **Iress, Sydney — Software Engineer (Backend)** | *August 2019 – December 2024* |
| :---- | ----: |

**CRM Backend Engineer**

- Owned end-to-end backend development for a Django-based CRM platform, delivering scalable APIs supporting critical business workflows
- Refactored backend services using domain-driven design, improving modularity, testability, and development velocity
- Designed and optimised PostgreSQL schemas, improving query performance and data integrity under production load
- Built and maintained backend services within a distributed architecture, supporting reliable inter-service communication
- Deployed and operated services on AWS (EC2, RDS, CloudWatch) with CI/CD pipelines to ensure reliability and observability
- Developed locally using Docker, running the containerised CRM service alongside PostgreSQL; helped refine and debug the platform team's compose setup for wider developer use, including macOS compatibility

**Lead Backend Engineer (MFE projects)**

- Led backend development for micro-frontend initiatives, enabling scalable integration with React-based frontends
- Refactored core APIs using domain-driven design, improving maintainability and extensibility
- Collaborated cross-functionally with frontend engineers to deliver cohesive end-to-end features across micro-frontend architecture
- Mentored engineers on backend design and code quality through reviews and technical guidance

**Site Reliability Engineer**

- Diagnosed and resolved production incidents, restoring stability for business-critical systems
- Used observability tooling (Datadog, CloudWatch) to identify and resolve performance bottlenecks
- Led incident response and coordinated cross-team efforts during outages
- *Key achievement:*
  - Reduced reporting system execution time from 8+ hours to under 2 hours by tracing the regression to a redundant per-entity data lookup and fixing it with transaction-scoped caching

**Facilitated Team's Social Contract**

- Initiated and led team-wide engineering standards alignment, reducing code review friction and improving development consistency
- Authored technical guidelines for Python/Django development practices

---

| **Adobe, Sydney — Technical Consulting Intern** | *July 2018 – December 2018* |
| :---- | ----: |

**AEM Analytics Dashboard Developer**

- Gathered requirements and delivered a data-driven analytics dashboard, enabling clients to visualise and act on backend data insights
- Collaborated closely with consulting team to interface with Adobe AEM's API to retrieve and visualise the analytics data using Chart.js
- *Achievements:*
  - Owned, delivered, and presented dashboard directly to client and consulting team
  - Scaled dashboard into a reusable solution, enabling adoption across multiple client implementations

---

## Projects

### Still — daily photo journal *(Alpha — in active development)*

- Privacy-first Android photo journal in React Native (TypeScript) and Expo. Local-first: SQLite for metadata, on-device storage for photos, and no account or network required by default
- Shipped the core capture-to-calendar loop end-to-end as a personal-use alpha on a physical device: photo capture with EXIF location, calendar thumbnails, day notes, and photo delete/replace
- Designed a tiered backup architecture for a later phase: Google Drive OAuth snapshots (Tier 2) and an optional self-hosted Go sync service via Docker (Tier 3)
- GitHub Actions CI (ESLint, TypeScript type-checking, Jest) gates every PR, with pre-commit secrets scanning via gitleaks. Independently managed release engineering: self-managed Android signing keystore, ABI-restricted release build (~60% smaller APK), and SemVer from the start
- Used Claude Code for scaffolding, refactors, and review passes, while designing the architecture and data model myself and reviewing every change

### Additional Projects

- Mobile application published on Google Play Store (Team Lead)
- Data visualisation dashboard using JavaScript and Google Visualization API

---

## Education

### Bachelor of Information Technology (Software Technology)

| Macquarie University, Sydney | *August 2014 – December 2017* |
| :---- | ----: |
| California State University (CSULB), Long Beach, USA | *August 2016 – December 2016* |

---

## Referees

Contact details available upon request.
