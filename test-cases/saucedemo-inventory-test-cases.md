# SauceDemo - Inventory Page Test Cases

## TC-INVENTORY-001
**Title:** Inventory page displays 6 products after successful login  
**Precondition:** User is logged in (standard_user / secret_sauce)

**Steps:**
1. Log in to https://www.saucedemo.com/
2. Navigate to the Inventory page (default post-login)
3. Count products displayed

**Expected Result:**
- Exactly 6 products are displayed


---

## TC-INVENTORY-002
**Title:** Default sort option is Name (A-Z)  
**Precondition:** User is logged in

**Steps:**
1. Go to Inventory page
2. Observe the sort dropdown

**Expected Result:**
- Sort dropdown default selection is "Name (A-Z)"


---

## TC-INVENTORY-003
**Title:** Sort dropdown contains all expected options  
**Precondition:** User is logged in

**Steps:**
1. Go to Inventory page
2. Open the sort dropdown

**Expected Result:**
Dropdown contains:
- Name (A-Z)
- Name (Z-A)
- Price (low to high)
- Price (high to low)


---

## TC-INVENTORY-004
**Title:** Products are ordered correctly under Name (A-Z)  
**Precondition:** User is logged in

**Steps:**
1. Go to Inventory page
2. Ensure sort is set to "Name (A-Z)"
3. Observe product name order (top to bottom)

**Expected Result:**
Products are listed in alphabetical order:
1. Sauce Labs Backpack
2. Sauce Labs Bike Light
3. Sauce Labs Bolt T-Shirt
4. Sauce Labs Fleece Jacket
5. Sauce Labs Onesie
6. Test.allTheThings() T-Shirt (Red)
