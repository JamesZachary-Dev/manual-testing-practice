# SauceDemo - Cart Test Cases

## TC-CART-001
**Title:** Add single item updates button to Remove and shows cart badge  
**Precondition:** User is logged in

**Steps:**
1. Go to Inventory page
2. Click "Add to cart" for any item

**Expected Result:**
- The clicked item button changes from "Add to cart" to "Remove"
- Cart badge appears and displays "1"


---

## TC-CART-002
**Title:** Remove single item clears cart badge  
**Precondition:** User is logged in and has 1 item in cart

**Steps:**
1. On Inventory page, click "Remove" for the item that was added

**Expected Result:**
- Item button changes back to "Add to cart"
- Cart badge disappears


---

## TC-CART-003
**Title:** Cart badge increments with multiple items  
**Precondition:** User is logged in

**Steps:**
1. Add 2 different items to cart

**Expected Result:**
- Cart badge displays "2"


---

## TC-CART-004
**Title:** Cart page shows items added from inventory  
**Precondition:** User is logged in and has at least 1 item in cart

**Steps:**
1. Click cart icon to open cart page

**Expected Result:**
- Cart page lists the same item(s) that were added
- Item name and price are visible


---

## TC-CART-005
**Title:** Cart state persists after page refresh  
**Precondition:** User is logged in and has at least 1 item in cart

**Steps:**
1. Add 1 item to cart
2. Refresh the browser page

**Expected Result:**
- Cart badge still reflects the correct number of items
- The previously added item still shows "Remove" on the inventory page
