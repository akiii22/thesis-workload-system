# thesis-workload-system

# ThesisFlow

A web-based workload and contribution management system designed for thesis and capstone student groups.

## Overview

Thesis and capstone projects require students to divide responsibilities, coordinate deadlines, and keep track of each member's progress.

In practice, this information is often scattered across group chats, documents, spreadsheets, and verbal agreements. This can make it difficult to understand workload distribution, track responsibilities, and maintain a clear record of contributions.

**ThesisFlow** aims to provide a centralized system where student groups can organize their work, monitor progress, and gain better visibility into their workload and contributions.

> **Project status:** Early development — currently in the planning and requirements phase.

---

## Problem

Thesis and capstone groups can experience:

* Unclear task responsibilities
* Uneven workload distribution
* Inconsistent progress updates
* Missed or approaching deadlines
* Difficulty tracking contributions
* Project information scattered across multiple tools

ThesisFlow aims to address these problems by making responsibilities, progress, workload, and contribution history more visible to the entire team.

---

## Planned Features

The initial MVP is planned to include:

* User registration and authentication
* Thesis/capstone project creation
* Project member management
* Task creation and assignment
* Task progress tracking
* Deadlines
* Workload visibility
* Contribution/activity history
* Project and member dashboards

Features will be added based on the project's requirements and validation rather than adding functionality unnecessarily.

---

## Planned Technology Stack

### Frontend

* React
* TypeScript
* React Router
* TanStack Query

### Backend

* Node.js
* Express.js
* REST API

### Database

* PostgreSQL

### Development & Deployment

* Git / GitHub
* AWS

The technology stack may change during development if a different approach better supports the project requirements.

---

## Project Documentation

Project planning and technical documentation will be maintained inside the `docs` directory.

```text
docs/
└── problem-definition.md
```

Additional documentation will be added as the project progresses.

---

## Development Roadmap

### Phase 1 — Product Discovery

* [x] Define the problem
* [x] Identify target users
* [x] Document current workflow
* [x] Define initial MVP
* [x] Define project scope

### Phase 2 — Requirements & Design

* [ ] Define user roles
* [ ] Define functional requirements
* [ ] Define user stories
* [ ] Design system workflows
* [ ] Design database / ERD
* [ ] Define system architecture

### Phase 3 — Backend

* [ ] Initialize Express application
* [ ] Configure PostgreSQL
* [ ] Implement authentication
* [ ] Implement authorization
* [ ] Implement project management
* [ ] Implement task management
* [ ] Implement workload tracking
* [ ] Implement contribution history

### Phase 4 — Frontend

* [ ] Initialize React application
* [ ] Implement routing
* [ ] Implement authentication UI
* [ ] Implement project management UI
* [ ] Implement task management UI
* [ ] Implement workload views
* [ ] Implement dashboards

### Phase 5 — Infrastructure

* [ ] Configure production environment
* [ ] Deploy application
* [ ] Configure AWS infrastructure

### Phase 6 — Testing & Improvement

* [ ] Manual testing
* [ ] Error handling
* [ ] Performance improvements
* [ ] Security review
* [ ] User feedback
* [ ] Documentation

---

## Project Structure

The project structure will evolve as development progresses.

```text
thesisflow/
├── docs/
│   └── problem-definition.md
├── README.md
└── ...
```

---

## Development Philosophy

This project is being developed as a real-world software project rather than a tutorial application.

The development process will prioritize:

* Solving a real problem
* Clear requirements before implementation
* Simple solutions before unnecessary complexity
* Meaningful use of technologies
* Maintainable architecture
* Proper Git workflow
* Documentation throughout development

---

## Status

The project is currently in the product discovery and requirements phase.
