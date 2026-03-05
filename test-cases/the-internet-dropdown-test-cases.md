# The Internet (Herokuapp) - Dropdown Test Cases

## TC-HI-DROP-001
**Title:** Dropdown displays available options  
**Precondition:** None

**Steps:**
1. Navigate to https://the-internet.herokuapp.com/dropdown
2. Click the dropdown menu

**Expected Result:**
Dropdown displays the following options:
- Please select an option
- Option 1
- Option 2


---

## TC-HI-DROP-002
**Title:** Default dropdown state shows placeholder option  
**Precondition:** None

**Steps:**
1. Navigate to dropdown page
2. Observe the dropdown without making a selection

**Expected Result:**
- Dropdown displays "Please select an option"
- No selectable option is preselected


---

## TC-HI-DROP-003
**Title:** User can select Option 1  
**Precondition:** None

**Steps:**
1. Navigate to dropdown page
2. Open dropdown
3. Select "Option 1"

**Expected Result:**
- "Option 1" becomes the selected value


---

## TC-HI-DROP-004
**Title:** User can select Option 2  
**Precondition:** None

**Steps:**
1. Navigate to dropdown page
2. Open dropdown
3. Select "Option 2"

**Expected Result:**
- "Option 2" becomes the selected value


---

## TC-HI-DROP-005
**Title:** Placeholder option cannot be reselected after a choice is made  
**Precondition:** User has selected Option 1 or Option 2

**Steps:**
1. Select "Option 1"
2. Open dropdown again

**Expected Result:**
- Placeholder option "Please select an option" cannot be selected again
