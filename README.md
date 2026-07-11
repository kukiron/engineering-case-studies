# Engineering Case Study - Modernizing the Ittihad Engineering Website

## Overview

**Project:** [Ittihad Engineering](https://ittihad.engineering)

**Role:** Sole developer and long-term technical owner

I originally developed the Ittihad Engineering website a couple of years ago,
and later led its complete redesign and production release. Rather than
patching individual issues, I decided to treat the project as an opportunity to
redesign the product holistically while evolving the existing production
codebase.

The redesign focused on improving user experience, frontend architecture,
performance, content architecture, and long-term maintainability while keeping
the site aligned with the company's industrial engineering identity.

## The Challenge

Although the original website successfully established the company's
online presence, it had naturally accumulated design inconsistencies,
duplicated patterns, and opportunities for technical improvement.

The redesign focused on:

- Modernizing the visual design
- Improving information hierarchy
- Building reusable frontend architecture
- Strengthening engineering documentation and release workflows

## My Responsibilities

- Frontend architecture
- UI implementation
- Component design
- Information architecture
- Content refinement
- Performance optimisation
- Image delivery pipeline
- Production release
- Engineering documentation

## Key Engineering Decisions

### Reusable Component Architecture

Refactored the application around reusable UI primitives and shared
layouts to reduce duplication and improve consistency.

### Design System

Established shared styling conventions covering typography, spacing,
cards, buttons, sections, and responsive layouts.

### Build-time Image Pipeline

Implemented a build-time metadata pipeline for S3-hosted images using
Sharp and Next.js image optimisation.

### Styling Strategy

Used CSS Modules for component ownership and Tailwind CSS for
lightweight layout utilities.

### Content-driven Structure

Moved business content into typed data structures where practical.

### Production Readiness

Documented release workflows, styling conventions, redesign guidelines,
and image management.

## Outcome

- Modern professional design
- Improved information hierarchy
- Cleaner frontend architecture
- Reusable components
- Better image handling
- Better long-term maintainability

## Lessons Learned

The biggest improvements came from engineering judgement rather than
individual features. Establishing clear conventions, reusable
components, and maintainable architecture proved more valuable than
isolated UI changes.

## Technologies

- React
- Next.js
- TypeScript
- CSS Modules
- Tailwind CSS
- Sharp
- AWS S3
- Netlify

## Links

- [Live website](https://ittihad.engineering)
- [GitHub Profile](https://github.com/kukiron)
- [LinkedIn](https://linkedin.com/in/kukiron)
