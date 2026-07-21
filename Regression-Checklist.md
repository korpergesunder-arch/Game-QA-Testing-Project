# Regression Checklist

## Game QA Testing Project

## Feature: Character Inventory System

Purpose:
Verify that existing inventory functionality works correctly after new changes or bug fixes.

---

# Inventory Opening

| ID | Check | Expected Result | Status |
|---|---|---|---|
| REG-001 | Open inventory from game menu | Inventory opens successfully | Not Tested |
| REG-002 | Close inventory window | Inventory closes correctly | Not Tested |
| REG-003 | Open inventory multiple times | No crashes or UI issues occur | Not Tested |

---

# Item Management

| ID | Check | Expected Result | Status |
|---|---|---|---|
| REG-004 | Add item to inventory | Item appears correctly | Not Tested |
| REG-005 | Remove item from inventory | Item disappears correctly | Not Tested |
| REG-006 | Use item from inventory | Item function works correctly | Not Tested |

---

# Inventory Capacity

| ID | Check | Expected Result | Status |
|---|---|---|---|
| REG-007 | Fill inventory completely | All slots are displayed correctly | Not Tested |
| REG-008 | Add item when inventory is full | Warning message appears | Not Tested |

---

# Data Saving

| ID | Check | Expected Result | Status |
|---|---|---|---|
| REG-009 | Save game with items | Items are saved correctly | Not Tested |
| REG-010 | Restart game after saving | Inventory data remains available | Not Tested |

---

# Error Handling

| ID | Check | Expected Result | Status |
|---|---|---|---|
| REG-011 | Perform invalid action | System handles action correctly | Not Tested |
| REG-012 | Disconnect during save process | No data corruption occurs | Not Tested |

---

# Regression Summary

Total checks: 12

Areas covered:

- Inventory UI
- Item management
- Capacity handling
- Data persistence
- Error handling
