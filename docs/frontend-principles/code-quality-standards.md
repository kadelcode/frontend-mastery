<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [Code Quality Standards](#code-quality-standards)
  - [Purpose](#purpose)
- [Tooling](#tooling)
  - [ESLint](#eslint)
  - [Prettier](#prettier)
  - [EditorConfig](#editorconfig)
- [General Principles](#general-principles)
  - [Readability First](#readability-first)
  - [Consistency Over Preference](#consistency-over-preference)
  - [Small, Focused Components](#small-focused-components)
  - [Reusability](#reusability)
  - [Maintainability](#maintainability)
- [Quality Checklist](#quality-checklist)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Code Quality Standards

## Purpose

This document defines the code quality and consistency standards for the Frontend Mastery workspace.

The objective is to ensure:

- maintainable code
- consistent formatting
- predictable project structure
- scalable frontend architecture

---

# Tooling

## ESLint

ESLint is used to:

- identify code issues
- enforce best practices
- improve maintainability
- reduce bugs

All code should pass lint checks before being merged.

---

## Prettier

Prettier is used to:

- enforce consistent formatting
- eliminate formatting debates
- improve readability

Formatting should be applied automatically whenever possible.

---

## EditorConfig

EditorConfig ensures consistency across editors and operating systems.

This includes:

- indentation
- line ending
- character encoding
- whitespace handling

---

# General Principles

## Readability First

Code should prioritize readability over cleverness.

---

## Consistency Over Preference

Project conventions should take precedence over personal preferences.

---

## Small, Focused Components

Components should have a single responsibility whenever possible.

---

## Reusability

Reusable patterns should be extracted and shared when appropriate.

---

## Maintainability

Code should be easy to understand, modify, and extend.

---

# Quality Checklist

Before merging:

- lint passes
- formatting passes
- naming conventions are followed
- no unused code exists
- documentation is updated if necessary
