# TBS TXTV Toolkit

> A shared collection of UI foundations, reusable components, design resources, and development utilities created for selected digital experiences at **TBS Trà Vinh**.

<p align="left">
  <img alt="Status" src="https://img.shields.io/badge/status-active-91BF3E">
  <img alt="Type" src="https://img.shields.io/badge/type-toolkit-033E2B">
  <img alt="Focus" src="https://img.shields.io/badge/focus-UI%20%26%20DX-333333">
</p>

---

## Overview

**TBS TXTV Toolkit** is a curated foundation for building consistent, practical, and maintainable digital experiences across selected web applications and internal-facing products at TBS Trà Vinh.

The repository brings together reusable resources that would otherwise be recreated across individual projects — from visual foundations and UI patterns to shared assets, templates, and development utilities.

It also serves as a public showcase of the design and engineering approach used across these projects.

> This repository focuses on shared foundations and selected showcase materials.  
> Application-specific business logic and proprietary source code are maintained separately.

---

## What's Inside

The toolkit may include:

- **Design Tokens**  
  Colors, typography, spacing, sizing, radius, shadows, and other visual foundations.

- **UI Components**  
  Reusable interface patterns and common application building blocks.

- **Icons & Assets**  
  Shared icons, graphics, illustrations, and visual resources.

- **Layouts & Templates**  
  Common page structures, dashboard patterns, forms, cards, and content layouts.

- **Utilities**  
  Helpers and reusable development utilities shared between projects.

- **Guidelines**  
  Conventions for UI consistency, naming, accessibility, and implementation.

- **Showcase Examples**  
  Selected examples demonstrating how the toolkit is applied in real products.

---

## Design Direction

The visual language is built around clarity, consistency, and usability in real operational environments.

### Core principles

**Clear over decorative**  
Interfaces should communicate information quickly without unnecessary visual noise.

**Consistent by default**  
Repeated patterns should behave and look familiar across different applications.

**Built for real workflows**  
Components are designed around actual operational use cases rather than isolated UI demos.

**Reusable, not over-engineered**  
Shared foundations should reduce duplicated work while remaining easy to understand and adapt.

**Responsive where it matters**  
Layouts are designed to work effectively across common desktop, tablet, and mobile scenarios.

---

## Brand Foundation

The toolkit commonly works with the following visual palette:

| Role | Color |
| --- | --- |
| Primary Green | `#033E2B` |
| Accent Green | `#91BF3E` |
| Surface | `#FFFFFF` |
| Neutral / Text | Context dependent |

These values act as a foundation rather than a limitation. Individual applications may extend the palette based on their specific functional requirements.

---

## Repository Structure

```text
tbs-txtv-toolkit/
│
├── assets/
│   ├── icons/
│   ├── graphics/
│   └── images/
│
├── components/
│   ├── buttons/
│   ├── forms/
│   ├── navigation/
│   ├── data-display/
│   └── feedback/
│
├── foundations/
│   ├── colors/
│   ├── typography/
│   ├── spacing/
│   └── tokens/
│
├── layouts/
│
├── templates/
│
├── utils/
│
├── examples/
│
└── docs/
```

> The actual structure may evolve as the toolkit grows.

---

## Example Usage

The toolkit is intended to support different categories of web applications, including:

```text
Operations Dashboard
        │
        ├── shared colors
        ├── navigation
        ├── tables
        └── status components

Task Management
        │
        ├── forms
        ├── cards
        ├── filters
        └── progress patterns

Kaizen / Improvement Tools
        │
        ├── workflow UI
        ├── evaluation states
        ├── metrics
        └── reporting components

7S / Workplace Management
        │
        ├── audit UI
        ├── checklists
        ├── visual status
        └── dashboards
```

The goal is not to make every application look identical, but to give them a **shared visual and interaction foundation**.

---

## Development Philosophy

```text
Design once
    ↓
Build reusable
    ↓
Apply consistently
    ↓
Improve centrally
```

When a shared component or pattern improves, applications using the same foundation can benefit from that improvement without repeatedly solving the same problem.

---

## Toolkit vs. Applications

This repository acts as a **shared layer** rather than an application itself.

```text
                    ┌─────────────────────┐
                    │   TBS TXTV Toolkit  │
                    └──────────┬──────────┘
                               │
              ┌────────────────┼────────────────┐
              │                │                │
              ▼                ▼                ▼
        Web App A         Web App B         Web App C
```

Application repositories remain independent so their business logic, deployment configuration, data models, and product-specific code can evolve separately.

---

## Status

The toolkit is actively evolving alongside the applications that use it.

Expect components, conventions, and documentation to improve over time as new product requirements and reusable patterns emerge.

---

## Showcase Repository

This repository is maintained partly as a **technical and design showcase**.

Some implementation details, production systems, integrations, datasets, credentials, business processes, and application-specific source code are intentionally not included.

Publicly available materials are intended to demonstrate:

- UI/UX direction
- reusable component thinking
- design-system practices
- frontend architecture
- development standards
- product consistency across applications

---

## About the Name

**TXTV** refers to the Trà Vinh context within this toolkit.

`tbs-txtv-toolkit` is intentionally broader than a traditional UI kit: it can grow to contain not only visual components, but also shared resources, templates, utilities, documentation, and other foundations used across multiple projects.

---

## Maintainer

**Nguyễn Nhật Minh**

Design & Development

Focused on building practical digital tools, internal web applications, and reusable product foundations.

---

<p align="center">
  <strong>Build once. Reuse consistently. Improve continuously.</strong>
</p>
