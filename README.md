# Accessibility Baseline & Repository Architecture Audit

## Project Overview

This project audits a real public-facing service website for accessibility and uses the findings to create a maintainable full-stack project foundation.

## Objectives

- Perform a Lighthouse accessibility audit.
- Perform keyboard-only navigation testing.
- Identify five accessibility or architecture issues.
- Document evidence and remediation priorities.
- Create a monorepo-style project structure.
- Define clear client, server, documentation, and testing boundaries.

## Repository Structure

```text
accessibility-baseline-audit/
├── client/
│   └── README.md
├── server/
│   └── README.md
├── docs/
│   ├── accessibility-audit.md
│   └── architecture.md
├── tests/
│   └── README.md
└── README.md

Architecture

User
  ↓
Accessible Client
  ↓
API Request
  ↓
Server Validation
  ↓
Business Logic
  ↓
API Response
  ↓
Accessible UI Update

Accessibility Focus

The project focuses on:

Keyboard accessibility

Visible focus indicators

Accessible forms

Alternative text

Semantic HTML

Logical navigation

Clear error messages


Documentation

Detailed audit findings are available in:

docs/accessibility-audit.md

docs/architecture.md


Testing

The tests/ directory is reserved for:

Accessibility tests

Integration tests

API tests


Local Setup

Prerequisites

Git

Node.js

npm

Modern web browser


Clone Repository

git clone <repository-url>
cd accessibility-baseline-audit

First Vertical Feature Slice

The first feature will demonstrate an accessible public-service form communicating with a server API.

Future Improvements

Automated accessibility testing

Database integration

Authentication

API documentation

CI/CD integration

Performance monitoring


**இதெல்லாம் paste பண்ணி முடித்ததும் screenshot அனுப்பு.** 👍
