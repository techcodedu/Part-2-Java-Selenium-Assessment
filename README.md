# Part-2-Java-Selenium-Assessment

### Instructions:
#### Overview
The main website for this assessment is https://www.saucedemo.com/. You will need to use Java programming language and the Selenium WebDriver API to complete this assessment.

#### Requirements
* Java Development Kit (JDK) installed :heavy_check_mark:
* Integrated Development Environment (IDE) of your choice :heavy_check_mark:
* Selenium WebDriver API installed :heavy_check_mark:

#### Instructions
* Open the project in your preferred IDE.
* Create a Java project in your IDE for the assessment.
* Create a project file for each test case.
* Write Java code to automate each test case.
* Execute the test cases and verify that they pass.
* If any test case fails, debug the code and fix the issue.
* Submit your completed Java project files for each test case as your assessment submission.


### Test Case 1: Verify the Login Page Elements

- Open the URL https://www.saucedemo.com/
- Verify that the correct URL is loaded
- Verify the existence of the Username field
- Verify the existence of the Password field
- Verify the existence of the Login button

### Test Case 2: Verify successful Login with Valid Credentials

- Open the URL https://www.saucedemo.com/
- Enter valid username in the Username field
- Enter valid password in the Password field
- Click on the Login button
- Verify that user is logged in successfully and is redirected to the Products page

### Test Case 3: Verify unsuccessful Login with Invalid Credentials

- Open the URL https://www.saucedemo.com/
- Enter invalid username in the Username field
- Enter invalid password in the Password field
- Click on the Login button
- Verify that the error message is displayed

### Test Case 4: Verify that user is able to add item to cart

- Login with valid credentials
- Click on the Add to Cart button for the first available item
- Verify that the item is added to the cart
- Verify that the Cart icon in the top right corner of the page is updated with the number of items in the cart

### Test Case 5: Verify that user is able to remove item from cart

- Login with valid credentials
- Click on the Add to Cart button for the first available item
- Click on the Cart icon in the top right corner of the page
- Click on the Remove button for the item
- Verify that the item is removed from the cart
- Verify that the Cart icon in the top right corner of the page is updated with the correct number of items in the cart

### Test Case 6: Verify that user is able to checkout with valid details

- Login with valid credentials
- Click on the Add to Cart button for the first available item
- Click on the Cart icon in the top right corner of the page
- Click on the Checkout button
- Enter the necessary personal and payment details in the checkout page
- Click on the Finish button
- Verify that the order confirmation page is displayed

### Test Case 7: Verify that user is unable to checkout without filling all mandatory details

- Login with valid credentials
- Click on the Add to Cart button for the first available item
- Click on the Cart icon in the top right corner of the page
- Click on the Checkout button
- Enter only the First Name in the checkout page
- Click on the Continue button
- Verify that the error message is displayed

### Test Case 8: Verify that user is able to logout successfully

- Login with valid credentials
- Click on the Menu button on the top left corner of the page
- Click on the Logout button
- Verify that user is logged out successfully and is redirected to the Login page

### Test Case 9: Verify that user is able to select a value from the dropdown list

- Login with valid credentials
- Click on the Sort dropdown on the Products page
- Select a value from the dropdown list
- Verify that the items are sorted correctly
