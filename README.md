# Contribution #1: Fix client-python codes to conform Pylint Rules

**Contribution Number:** 1
**Student:** Kenneth Charumuka
**Issue:** https://github.com/apache/gravitino/issues/3560
**Status:** Phase I Complete

---

## Why I Chose This Issue

I chose this issue because the acceptance criteria are completely unambiguous —
fix the Pylint violations and the disabled rules pass clean. As a CS grad
student at Yeshiva University who writes Python daily, this is a natural fit
for my first open source contribution. The issue involves real code quality
improvements rather than just documentation, which makes it a stronger
portfolio signal.

Apache Gravitino is an actively maintained Apache Software Foundation project
with responsive maintainers and a clear contribution process. The scope is
well-bounded across a specific set of ten Pylint rules flagged with `TODO-fix`
in the project's `pylintrc`, which means I can make meaningful progress in
a focused, incremental way without risk of scope creep.

---

## Understanding the Issue

### Problem Description

The Gravitino Python client library has several Pylint rules currently
disabled via `TODO-fix` markers in the project's `pylintrc` file. These
violations were deferred rather than fixed, leaving the codebase with
known quality issues including broad exception catching, inconsistent
return statements, too many arguments, and protected member access.

### Expected Behavior

All ten flagged Pylint rules should pass cleanly with no violations,
allowing the `TODO-fix` suppressions in `pylintrc` to be removed.

### Current Behavior

The following Pylint rules are currently disabled in `pylintrc`:
- `missing-timeout`
- `redefined-builtin`
- `broad-exception-caught`
- `duplicate-code`
- `method-hidden`
- `no-name-in-module`
- `invalid-field-call`
- `protected-access`
- `too-many-arguments`
- `inconsistent-return-statements`

### Affected Components

The `client-python` module of the Apache Gravitino repository.

---

## Reproduction Process

### Environment Setup

_Coming in Phase II_

### Steps to Reproduce

_Coming in Phase II_

### Reproduction Evidence

_Coming in Phase II_

---

## Solution Approach

### Analysis

_Coming in Phase II_

### Proposed Solution

_Coming in Phase II_

### Implementation Plan

_Coming in Phase II_

---

## Testing Strategy

### Unit Tests

- [ ] Coming in Phase III

### Integration Tests

- [ ] Coming in Phase III

### Manual Testing

_Coming in Phase III_

---

## Implementation Notes

_Coming in Phase III_

---

## Pull Request

**PR Link:** _Coming in Phase IV_

**PR Description:** _Coming in Phase IV_

**Maintainer Feedback:** _Coming in Phase IV_

**Status:** Not yet submitted

---

## Learnings & Reflections

_Coming upon completion_

---

## Resources Used

- https://github.com/apache/gravitino/issues/3560
- https://pylint.readthedocs.io/en/stable/# su26-ai301-contribution
