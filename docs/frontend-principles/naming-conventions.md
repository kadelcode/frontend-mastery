<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

**Table of Contents** _generated with [DocToc](https://github.com/thlorenz/doctoc)_

- [Naming Conventions](#naming-conventions)
  - [Purpose](#purpose)
- [Folder Naming](#folder-naming)
- [File Naming](#file-naming)
  - [React Components](#react-components)
  - [Utility Files](#utility-files)
- [Variable Naming](#variable-naming)
- [Function Naming](#function-naming)
- [React Hooks](#react-hooks)
- [Constants](#constants)
- [Interfaces](#interfaces)
- [Types](#types)
- [Booleans](#booleans)
- [Summary](#summary)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Naming Conventions

## Purpose

This document defines naming conventions used throughout the Frontend Mastery repository.

---

# Folder Naming

Use:

```txt
kebab-case
```

Examples:

```txt
auth-flow-ui
pricing-section
dashboard-layout
```

---

# File Naming

## React Components

Use:

```txt
PascalCase
```

Examples:

```txt
Button.tsx
Navbar.tsx
DashboardCard.tsx
```

---

## Utility Files

Use:

```txt
camelCase
```

Examples:

```txt
formatCurrency.ts
calculateDiscount.ts
```

---

# Variable Naming

Use:

```txt
camelCase
```

Examples:

```ts
const userProfile;
const isLoading;
const fetchProducts;
```

---

# Function Naming

Use:

```txt
camelCase
```

Examples:

```ts
function fetchUserData() {}
function validateForm() {}
function calculateTotal() {}
```

---

# React Hooks

Use:

```txt
useSomething
```

Examples:

```ts
useAuth();
useTheme();
useModal();
```

---

# Constants

Use:

```txt
UPPER_SNAKE_CASE
```

Examples:

```ts
MAX_RETRY_COUNT;
DEFAULT_PAGE_SIZE;
API_TIMEOUT;
```

---

# Interfaces

Use:

```txt
PascalCase
```

Examples:

```ts
interface User {}
interface Product {}
interface ApiResponse {}
```

---

# Types

Use:

```txt
PascalCase
```

Examples:

```ts
type UserRole = "admin" | "user";
type ThemeMode = "light" | "dark";
```

---

# Booleans

Prefix with:

```txt
is
has
can
should
```

Examples:

```ts
isLoading;
hasPermission;
canEdit;
shouldRender;
```

---

# Summary

| Item       | Convention       |
| ---------- | ---------------- |
| Folders    | kebab-case       |
| Components | PascalCase       |
| Hooks      | useSomething     |
| Variables  | camelCase        |
| Functions  | camelCase        |
| Constants  | UPPER_SNAKE_CASE |
| Interfaces | PascalCase       |
| Types      | PascalCase       |
