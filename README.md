# Test Case Samples

Below are some Test Case samples that I wrote while working on previous projects.

----------------
## Test 1
**Description:**
Check if the login works when a person uses a correct user/pass.

**Steps to Reproduce:**
1. Go to www.website.com/login
2. Add a correct user or pass
3. Press Login button

**Expected result:**
User should be able to login and is taken to his profile page.

**Test Data:**
User: carmina & Pass: 123456

**Actual Results**
As Expected

**Pass/Fail**
Pass

----------------
## Test 2
**Description:**
Check if forgot password functionality works as expected and an email with reset password link is sent.

**Steps to Reproduce:**
1. Go to www.website.com/login
2. Press "Forgot Password" button
3. Add an email address
4. Press "Recover" button

**Expected result:**
User should receive an email with a reset password link. That link should allow the user to create a new password.

**Test Data:**
User: carmina@email.com

**Actual Results**
As Expected

**Pass/Fail**
Pass

**Note:**
Please check the login again after running this test case.


----------------
## Test 3
**Description:**
Check if the login works when a person don't enter a user or pass.

**Steps to Reproduce:**
1. Go to www.website.com/login
2. Don't enter a value in user or pass field
4. Press Login button

**Expected result:**
User shouldn't be able to login and below the input will show the message: "Please enter a username or email address.". 

**Test Data:**
user: empty & pass: 123456 or user: carmina & pass: empty

**Actual Results**
As Expected

**Pass/Fail**
Pass

-------------------------------

## Test 4
**Description:**
Check if the search results are relevant to the search query.

**Steps to Reproduce:**
1. Go to www.website.com
2. Add a query in a search box
3. Press Search button

**Expected result:**
User should have the relative search result.

**Test Data:**
Query: Black T-Shirt

**Actual Results**
As Expected

**Pass/Fail**
Pass

---------------------------------------

## Test 5
**Description:**
Check if search give an error when you are looking for something that doesn't exist.

**Steps to Reproduce:**
1. Go to www.website.com
2. Add a query in a search box
3. Press Search button

**Expected result:**
User should see an error message.

**Test Data:**
Query: Canon D12345

**Actual Results**
User see the irrelative search result.

**Pass/Fail**
Fail

**Note:**
Please make a Bug Report.

---------------------------------------

## Test 6
**Description:**
Check if the login don't works when a person enter a special characters.

**Steps to Reproduce:**
1. Go to www.website.com/login
2. Add a special characters in user/pass fields
3. Press Login button

**Expected result:**
An error message "User does not exist. Would you like to create a new account?" must shown.

**Test Data:**
User: '123' OR '1'='1' & pass: '123' OR '1'='1'

**Actual Results**
As Expected

**Pass/Fail**
Pass

-----------------------------------
