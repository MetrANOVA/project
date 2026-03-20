# MetrANOVA Project Repository

This repository is the central home for MetrANOVA GitHub organization-wide:
- Issue tracking
- Project documentation
- Shared utilities and project-management artifacts

## Purpose

Use this repository to coordinate cross-repo work, especially high-level planning and execution tracking.  
When work spans multiple repositories or teams, track it here first.

## Issue Management Principles

- Prefer creating an issue over delaying work because process details are missing.
- Keep issue creation lightweight to lower barrier to entry.
- Use issue types consistently so work is easy to find, filter, and report.
- Use Epic issues where they add planning value; not every issue must belong to an Epic.

## Issue Types

Use GitHub's standard issue type field for all issues when possible.

Supported types:
- Epic
- Task
- Feature
- Bug

Guideline:
- Ideally, every issue has a type assigned.

## Epic Issues

Epic issues represent a large body of work and must have a clear, closeable end state.

### Where to Create Epic Issues

Create all Epic issues in this repository:
- https://github.com/metranova/project

### What a Good Epic Includes

Each Epic should include:
- User story framing
- Scope
- Dependencies
- Definition of Done (DoD)
- Start date
- Due date

### Epic Quality Standard

Avoid vague Epics that can remain open indefinitely.  
An Epic should define a concrete outcome so it can be completed and closed.

## Non-Epic Issues

Non-Epic issues can be created:
- In the target implementation repository, when that is clearer for execution
- In this repository as a fallback, when no better location exists

### Relationship to Epics

When a non-Epic issue is part of an Epic:
- Set the Epic as the parent using GitHub's standard Relationship field

Note:
- Not all issues are required to belong to an Epic.

## Scheduling Guidance

### Required Scheduling

- Epic issues must include:
  - Start date
  - Due date

### Optional Scheduling

- Task, Feature, and Bug issues do not require start/due dates by default
- Add dates when it is useful, especially when deadlines are fixed
  - Example: workshop submission deadlines

## Recommended Epic Template

Use this structure when creating Epic descriptions:

1. User Story  
2. Epic Description  
3. In Scope  
4. Out of Scope  
5. Dependencies  
6. Definition of Done  
7. Start Date  
8. Due Date

## Quick Checklist

Before submitting an issue:
- Issue type selected
- Repo placement is appropriate
- If Epic: includes scope, dependencies, DoD, start date, due date
- If non-Epic under Epic: parent relationship is set
- Description is clear enough for someone outside the originating team

## Summary

This repository is the project-management anchor for MetrANOVA org-wide work.  
Use Epics here for high-level coordination, keep issues actionable and closeable, and prioritize clarity over process overhead.
