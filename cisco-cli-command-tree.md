# Cisco CLI Overview

This document covers Cisco IOS command modes, the command tree, and common CLI commands used for device navigation and basic configuration.

---

## Command Help

**`?`**
- Displays available commands
- Can be used at any level of the CLI
- Helps discover valid commands and syntax

---

## Cisco IOS Command Tree

Cisco IOS uses a hierarchical command structure known as a **command tree**.  
Each mode provides a different level of access.

---

## 1. User EXEC Mode (`>`)

- Limited access mode
- Used for basic monitoring commands
- Configuration changes are not allowed

**Common Command**
- `enable` → Elevates to Privileged EXEC Mode

**Prompt**
```text
Router>
