# Claude Guidelines – Multi-Stack Development Standards

A structured collection of guidelines, best practices, and architecture patterns for different tech stacks. Each stack is maintained in a separate branch to keep concerns isolated and documentation focused.

The goal of this repository is to provide consistent development standards across projects — making it easier to onboard developers, maintain code quality, and scale systems.

---

## Repository Structure

Each branch represents a specific tech stack and contains detailed documentation, examples, and recommended patterns.

| Branch | Stack | Description |
|--------|-------|-------------|
| [`docs-nestjs`](https://github.com/sahilgupta-28/claude-guidelines/tree/docs-nestjs) | NestJS + PostgreSQL + Prisma | Backend API architecture with DTO validation, guards, repository pattern, Swagger docs, and Jest testing |
| [`docs-nextjs`](https://github.com/sahilgupta-28/claude-guidelines/tree/docs-nextjs) | Next.js (App Router) + Prisma + Zod | Full-stack architecture using Server Components, Server Actions, API routes, and security best practices |
| [`docs-reactjs`](https://github.com/sahilgupta-28/claude-guidelines/tree/docs-reactjs) | React (Client-side) + Zod | SPA architecture with API abstraction, validation, testing (RTL/MSW), and browser security |
| [`docs-nodejs`](https://github.com/sahilgupta-28/claude-guidelines/tree/docs-nodejs) | Node.js (Express/Fastify) + Prisma + Zod | Layered backend architecture with middleware validation and integration testing |
| [`docs-fastapi`](https://github.com/sahilgupta-28/claude-guidelines/tree/docs-fastapi) | FastAPI + SQLAlchemy + Pydantic | Async Python backend with dependency injection, migrations, and testing setup |

---

## Purpose

- Standardize development practices across multiple stacks
- Provide ready-to-follow architecture patterns
- Improve code quality and maintainability
- Reduce onboarding time for new developers
- Act as a reference for real-world production setups

---

## How to Use

**1. Clone the repository:**

```bash
git clone https://github.com/sahilgupta-28/claude-guidelines.git
cd claude-guidelines
```

**2. Switch to the required stack branch:**

```bash
git checkout docs-nestjs
```

**3. Follow the documentation inside each branch.**

Each branch contains:

- Folder structure
- Coding guidelines
- Best practices
- Testing strategy
- Security considerations

---

## Suggested Workflow

- Use these guidelines as a base when starting a new project
- Adapt patterns based on project requirements
- Keep consistency across teams and services
- Contribute improvements back to this repo

---

## Contribution

Contributions are welcome. You can:

- Improve documentation clarity
- Add new stack guidelines
- Enhance best practices
- Fix inconsistencies

**Steps:**

1. Fork the repo
2. Create a new branch
3. Make your changes
4. Open a pull request


