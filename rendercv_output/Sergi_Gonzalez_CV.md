# Sergi Gonzalez's CV

- Email: [sergigp85@gmail.com](mailto:sergigp85@gmail.com)
- Location: Barcelona, Spain
- LinkedIn: [sergigp](https://linkedin.com/in/sergigp)
- GitHub: [sergigp](https://github.com/sergigp)


# Summary
Product-minded engineer and team lead with 15+ years building software for startups and scale-ups, remote since 2018. Believes that software architecture and tools depend on context and product strategy. Grew two teams from scratch, built a chat platform serving 130K+ concurrent users at Letgo, co-founded a startup, and led an international team at Coralogix. Works spec-first with AI coding agents. Looking for remote senior backend or team lead roles from January 2027.

# Skills
**Languages:** Rust, Scala, TypeScript

**Backend & Architecture:** Distributed systems, event-driven architecture, microservices, DDD/CQRS, Kafka, gRPC

**Infrastructure & Observability:** Kubernetes, AWS, Terraform, Prometheus, Grafana

**Data:** MySQL, PostgreSQL, Elasticsearch, DynamoDB

**AI-assisted development:** Claude Code, Codex, spec-driven development

**Frontend (working knowledge):** Angular, React

# Experience
## **Sabbatical and personal projects**

**Jan 2026 – present**

Career break

- Planned break after Coralogix, including parental leave.

- Built [Yarrtube](https://github.com/sergigp/yarrtube), an open-source self-hosted YouTube synchronizer (Rust, React, TypeScript), spec-first with Claude Code and OpenSpec. 140+ GitHub stars.

- Currently building [Superthree](https://github.com/sergigp/superthree), a self-hosted TV channel for kids where parents schedule what plays (TypeScript).



## **Software Engineer, Data Usage Team**

**May 2025 – Dec 2025**

Coralogix -- Remote

*B2B observability SaaS that grew from about 100 to 500+ employees between 2022 and 2025. Moved to the team that meters each customer's platform usage and enforces quotas.*

- Helped replace the legacy JavaScript quota blocker with a new Rust service that warns customers approaching their quota and blocks ingestion within minutes of them exceeding it.

- Added per-data-type blocking rules (logs, metrics, traces) and quota sharing between data types.

- Built customer-facing usage dashboards on usage data aggregated from Kafka into ClickHouse.



## **Team Lead, Dashboards Team**

**Apr 2022 – May 2025**

Coralogix -- Remote

*Promoted shortly after joining the company to found and lead the dashboards team, acting as its engineering manager.*

- Built custom dashboards, a Grafana-like product that became the platform's native alternative to Grafana for customers and replaced it company-wide for internal service monitoring.

- Grew the team from 1 to 6 engineers, mostly frontend (Angular), owning hiring and performance management.

- Delivered the home dashboard and took over Explore, the product's highest-traffic page (log exploration).

- First frontend team at the company to adopt end-to-end testing (Playwright); other teams followed.

- Main contributor to the team's backend (Scala) and infrastructure (Kubernetes), hands-on in the Angular frontend.



## **Co-Founder**

**Nov 2020 – Jan 2022**

Cassette -- Remote

*Bootstrapped startup founded with three former Letgo colleagues. Desktop and mobile app for asynchronous meetings over voice notes, aimed at replacing daily stand-ups.*

- Built the backend (Scala) and the desktop app (Electron, TypeScript), and ran the AWS infrastructure, including voice-note transcription with Amazon Transcribe.

- Reached about 100 sign-ups and 5 teams running daily stand-ups on it, steered by regular user interviews.

- Pitched investors and wound the company down after 14 months without funding or product-market fit.



## **Staff Engineer, Platform Team**

**Aug 2018 – Oct 2020**

Letgo -- Remote

*B2C second-hand marketplace for the US market that raised about $1 billion and grew to 300+ employees. Proposed the platform backend team to the CTO and moved into it, as one of three engineers.*

- Built the PHP and Scala libraries that every backend team used to publish and consume domain events, standardizing how 40 engineers integrated their services.

- Introduced service quality tracking across backend teams, covering SLAs, downtime and test coverage.

- Built a company-wide domain event explorer, used by backend teams for debugging and by customer care.

- Moved the company's event backbone from SNS and SQS to Kafka.

- Ran backend recruiting with the platform team, hiring 20+ engineers across both Letgo roles.



## **Team Lead, Chat Team**

**Oct 2015 – Aug 2018**

Letgo -- Barcelona

- Built the new real-time chat in Scala and Akka (WebSockets, MariaDB), which peaked at 130K+ concurrent users and handled over 4 billion messages.

- Migrated from the PHP chat with zero downtime, running both in parallel for months and keeping them in sync through domain events over SQS.

- Scaled it with Akka Cluster and archived older messages to DynamoDB as volume grew.

- Led the company-wide move to an event-driven microservices architecture. Every backend team adopted domain events (SNS, SQS) and owned its own database, built from projections.

- Grew the team from 1 to a cross-functional squad of 8 and began co-leading hiring for the backend department.



## **Earlier roles – Software Engineer**

**2010 – 2015**

Akamon (2014–15), Atrápalo (2011–14) and others



# Talks
- Microservices Anti-Patterns, Bilbostack 2020 ([slides, ES](https://es.slideshare.net/sergigp/otra-charla-de-microservicicios-bilbostack2020))

- From Polling to Real Time, BCN Software Crafters 2017 ([slides, EN](https://es.slideshare.net/sergigp/from-polling-to-real-time-scala-akka-and-websockets-from-scratch-66626441))

- DDD as an Implementation Detail, PHP Barcelona 2015 ([slides, EN](https://es.slideshare.net/sergigp/php-barcelona-monthly-talk-feb-2015))

# Education
## **Universitat Autònoma de Barcelona (UAB)**, BSc in Computer Science
2010



# Languages
Catalan and Spanish (native), English (fluent; led an international team in English, 2022–2025)
