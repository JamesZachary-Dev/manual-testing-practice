# The Internet (Herokuapp) - Login Test Cases

## TC-HI-LOGIN-001
**Title:** Login with valid credentials redirects to /secure  
**Precondition:** None

**Test Data:**
- Username: tomsmith
- Password: SuperSecretPassword!

**Steps:**
1. Navigate to https://the-internet.herokuapp.com/login
2. Enter username: tomsmith
3. Enter password: SuperSecretPassword!
4. Click "Login"

**Expected Result:**
- User is redirected to /secure
- Secure Area page content is displayed (welcome message and logout instructions)
- A success flash/banner message is displayed (green)


---

## TC-HI-LOGIN-002
**Title:** Login fails with invalid username  
**Precondition:** None

**Steps:**
1. Navigate to login page
2. Enter username: invaliduser
3. Enter password: SuperSecretPassword!
4. Click "Login"

**Expected Result:**
- User remains on /login
- A red flash banner appears displaying the message: "Your username is invalid!"
- Banner includes an icon indicating error status
- Banner includes a close button allowing the message to be dismissed


---

## TC-HI-LOGIN-003
**Title:** Login fails with invalid password  
**Precondition:** None

**Steps:**
1. Navigate to login page
2. Enter username: tomsmith
3. Enter password: wrongpassword
4. Click "Login"

**Expected Result:**
- User remains on /login
- A red flash banner appears displaying the message: "Your password is invalid!"
- Banner includes an error icon
- Banner includes a close button allowing the message to be dismissed


---

## TC-HI-LOGIN-004
**Title:** Login fails with empty username and password  
**Precondition:** None

**Steps:**
1. Navigate to login page
2. Leave username empty
3. Leave password empty
4. Click "Login"

**Expected Result:**
- User remains on /login
- An error flash/banner message is displayed indicating username is invalid


---

## TC-HI-LOGIN-005
**Title:** Logout returns user to login page  
**Precondition:** User is logged in and on /secure

**Steps:**
1. Click "Logout"

**Expected Result:**
- User is redirected to /login
- A logout confirmation flash/banner message is displayed
