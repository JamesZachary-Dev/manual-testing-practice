# SauceDemo - Login Test Cases

## TC-LOGIN-001
**Title:** Login with valid credentials  
**Precondition:** User account exists  

**Steps:**
1. Navigate to https://www.saucedemo.com/
2. Enter valid username
3. Enter valid password
4. Click "Login"

**Expected Result:**
User is redirected to the inventory page.


---

## TC-LOGIN-002
**Title:** Login with invalid password  
**Precondition:** User account exists  

**Steps:**
1. Navigate to login page
2. Enter valid username
3. Enter incorrect password
4. Click "Login"

**Expected Result:**
Error message is displayed.


---

## TC-LOGIN-003
**Title:** Login with empty username  
**Precondition:** None  

**Steps:**
1. Navigate to login page
2. Leave username field empty
3. Enter valid password
4. Click "Login"

**Expected Result:**
Validation error message is displayed.


---

## TC-LOGIN-004
**Title:** Login with empty password  
**Precondition:** None  

**Steps:**
1. Navigate to login page
2. Enter valid username
3. Leave password field empty
4. Click "Login"

**Expected Result:**
Validation error message is displayed.


---

## TC-LOGIN-005
**Title:** Login with empty username / password  
**Precondition:** None  

**Steps:**
1. Navigate to login page
2. Leave username field empty
3. Leave password field empty
4. Click "Login"

*Expected Result:**
- Error banner appears displaying: "Epic sadface: Username is required"
- Username field is highlighted
- Two (X)s appear to the rightside of both fields
- User stays on the login page


---

## TC-LOGIN-006
**Title:** Login with empty password  
**Precondition:** None  

**Steps:**
1. Navigate to https://www.saucedemo.com/
2. Enter username: standard_user
3. Leave password field empty
4. Click "Login"

*Expected Result:**
- Error banner appears displaying: "Epic sadface: Password is required"
- Username field is highlighted
- Two (X)s appear to the rightside of both fields
- User stays on the login page


