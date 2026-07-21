
# Test Cases

## Feature: Character Inventory System

---

## TC-001: Open Inventory

**Priority:** High

**Type:** Functional Testing

### Preconditions:
- Game is launched
- Player account is active

### Steps:
1. Start the game
2. Enter the game world
3. Press the inventory button

### Expected Result:
Inventory window opens successfully.

### Actual Result:
To be filled during execution.

### Status:
Not Executed

---

## TC-002: Add Item to Inventory

**Priority:** High

**Type:** Functional Testing

### Preconditions:
- Player is able to collect items

### Steps:
1. Find an available item
2. Pick up the item
3. Open inventory

### Expected Result:
The collected item appears in the inventory.

### Actual Result:
To be filled during execution.

### Status:
Not Executed

---

## TC-003: Remove Item from Inventory

**Priority:** Medium

**Type:** Functional Testing

### Steps:
1. Open inventory
2. Select an item
3. Remove the item

### Expected Result:
The selected item is removed from inventory.

### Actual Result:
To be filled during execution.

### Status:
Not Executed

---

## TC-004: Use Item from Inventory

**Priority:** High

**Type:** Functional Testing

### Steps:
1. Open inventory
2. Select usable item
3. Click "Use"

### Expected Result:
The item effect is applied and inventory updates correctly.

### Actual Result:
To be filled during execution.

### Status:
Not Executed

---

## TC-005: Inventory Capacity Limit

**Priority:** High

**Type:** Negative Testing

### Steps:
1. Fill inventory to maximum capacity
2. Try adding another item

### Expected Result:
System prevents adding items and displays an appropriate message.

### Actual Result:
To be filled during execution.

### Status:
Not Executed

---

## TC-006: Inventory Data Persistence

**Priority:** High

**Type:** Regression Testing

### Steps:
1. Add an item to inventory
2. Save the game
3. Restart the game
4. Open inventory

### Expected Result:
Previously saved items remain available.

### Actual Result:
To be filled during execution.

### Status:
Not Executed

---

# Test Summary

Total Test Cases: 6

Functional Tests: 4

Negative Tests: 1

Regression Tests: 1
