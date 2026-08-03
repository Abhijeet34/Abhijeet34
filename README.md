# Abhijeet Halder

Software engineer working on agentic workflows, developer tooling, and local-first automation.
Around six years in software engineering, currently taking an M.Tech in Software Engineering. Bangalore, India.

## What I work on

I build software systems and the tooling that ships them.
Most of my work sits in two places: full-stack products, with Flask and FastAPI behind JavaScript front ends, and the delivery pipelines around them, with Docker, Jenkins, Kubernetes, SonarQube, Prometheus and Grafana.

I care about the parts that are easy to skip and expensive to have skipped.
Verification loops. Checks that fail on real problems instead of decorating a pull request. Defaults that carry the common path, so an ordinary run needs no ceremony.

Lately I have been going deeper into AI-assisted development.
The interesting problem is not calling a bigger model.
It is giving a smaller, local one the right tools, context, and verification loop, so the harness does the work the model cannot.

> Verification matters more than confidence.

## Currently building

**Agent harnesses.**
Deterministic orchestration around models: isolated worktrees, written briefs, explicit review and fix phases, and a supervisor that can prove what actually ran.

**Local-first tooling.**
On-device speech and inference that reduce dependence on expensive cloud APIs without trading away quality.

**Delivery pipelines that mean something.**
Tests, lint, static analysis, and observability as part of the definition of done, not as a badge on a page.

## Selected work

**Cloud-native microservices platform.**
An e-commerce backend split into FastAPI services, containerized and rolled out on Kubernetes.

**Delivery pipeline for a Flask application.**
Jenkins CI/CD with SonarQube quality gates, Kubernetes rollout strategies, and Prometheus and Grafana for observability.

**Full-stack equipment-sharing application.**
A JavaScript product end to end, from data model to interface.

## How I work

Reproduce before fixing, so the reproduction becomes the regression test.
Prefer the smallest change that fully solves the problem.
Treat a check that has only ever been seen passing as untested.
Keep humans accountable for approvals, security, and consequences.

---

Reach me at abhihalder343@gmail.com

<sub>Local-first should be the baseline, not a fallback.</sub>
