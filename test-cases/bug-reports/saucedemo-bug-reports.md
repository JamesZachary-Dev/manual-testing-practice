## BUG-SD-002
**Title:** "Reset App State" clears cart badge but does not reset item button state on inventory  
**Environment:** Chrome (latest), Windows 10/11  
**Severity:** Medium  
**Priority:** Medium  

**Steps to Reproduce:**
1. Log in to https://www.saucedemo.com/ (standard_user / secret_sauce)
2. On Inventory page, click "Add to cart" on any item
3. Confirm cart badge shows "1"
4. Open the left menu
5. Click "Reset App State"
6. Observe cart badge and the item button state

**Actual Result:**
- Cart badge disappears (cart count resets)
- The previously selected item still shows "Remove" instead of reverting to "Add to cart"

**Expected Result:**
Reset App State should fully reset cart-related UI state:
- Cart badge cleared
- All item buttons revert to "Add to cart"
