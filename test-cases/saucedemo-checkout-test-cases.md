# SauceDemo - Checkout Flow Test Cases

## TC-CHECKOUT-001
**Title:** Error displayed when all checkout fields are empty  
**Precondition:** User has at least 1 item in cart and is on Checkout: Your Information page

**Steps:**
1. Click "Checkout"
2. Leave First Name empty
3. Leave Last Name empty
4. Leave Postal Code empty
5. Click "Continue"

**Expected Result:**
- Error banner appears displaying: "Error: First Name is required"
- All input fields show validation styling (red highlight)
- Error icons (X) appear on each field
- User remains on the checkout information page


---

## TC-CHECKOUT-002
**Title:** Successful checkout flow with valid information  
**Precondition:** User has at least 1 item in cart

**Steps:**
1. Click "Checkout"
2. Enter valid First Name
3. Enter valid Last Name
4. Enter valid Postal Code
5. Click "Continue"
6. Click "Finish"

**Expected Result:**
- Checkout Complete page appears
- Confirmation message displayed: "Thank you for your order!"
- Supporting message about dispatch is displayed
- Cart badge is cleared
- Returning to Inventory shows all items reset to "Add to cart"


---

## TC-CHECKOUT-003
**Title:** Order confirmation does not display an order number  
**Precondition:** Successful checkout completed

**Steps:**
1. Complete checkout process
2. Observe confirmation page

**Expected Result:**
- No order number is displayed on the Checkout Complete page
