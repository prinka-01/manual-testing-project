# E-Commerce Test Cases

## TC_001 - Valid Login Functionality

| Field | Details |
|--------|---------|
| Project | E-Commerce |
| Test Case ID | TC_001 |
| Module | Login |
| Type | SILO |
| Test Scenario | Valid Login Functionality |
| Description | Verify that the registered user is able to successfully log in using valid credentials |
| Browser | Chrome |
| Expected Result | User is redirected to the homepage |
| Actual Result | User is able to login and is directed to the homepage |
| Status | Pass |

### Test Steps
1. Launch URL: https://www.automationexercise.com/
2. Click on **Sign In**
3. Enter valid username and valid password
4. Click on **Log in** button

---

## TC_002 - Invalid Password

| Field | Details |
|--------|---------|
| Project | E-Commerce |
| Test Case ID | TC_002 |
| Module | Login |
| Type | SILO |
| Test Scenario | Invalid Password |
| Description | Verify that the user is not able to login when an invalid password is entered |
| Browser | Chrome |
| Expected Result | User gets an error message: "Your email or password is incorrect!" |
| Actual Result | User gets an error message: "Invalid Username or Password" |
| Status | Pass |

### Test Steps
1. Launch URL: https://www.automationexercise.com/
2. Click on **Sign In**
3. Enter valid username and invalid password
4. Click on **Log in** button

---

## TC_003 - Invalid Username

| Field | Details |
|--------|---------|
| Project | E-Commerce |
| Test Case ID | TC_003 |
| Module | Login |
| Type | SILO |
| Test Scenario | Invalid Username |
| Description | Verify that the user is not able to login when an invalid username is entered |
| Browser | Chrome |
| Expected Result | User gets an error message: "Your email or password is incorrect!" |
| Actual Result | User gets an error message: "Invalid Username or Password" |
| Status | Pass |

### Test Steps
1. Launch URL: https://www.automationexercise.com/
2. Click on **Sign In**
3. Enter invalid username and valid password
4. Click on **Log in** button

---

## TC_004 - Empty Fields

| Field | Details |
|--------|---------|
| Project | E-Commerce |
| Test Case ID | TC_004 |
| Module | Login |
| Type | SILO |
| Test Scenario | Empty Fields |
| Description | Verify that the user is not able to login when username or password field is empty |
| Browser | Chrome |
| Expected Result | User is unable to click on login button |
| Actual Result | User gets an error message: "Please fill in this field" |
| Status | Pass |

### Test Steps
1. Launch URL: https://www.automationexercise.com/
2. Click on **Sign In**
3. Keep username and/or password field empty
4. Click on **Log in** button

---

## TC_005 - Product Listing Page (PLP)

| Field | Details |
|--------|---------|
| Project | E-Commerce |
| Test Case ID | TC_005 |
| Module | Products Tab |
| Type | SILO |
| Test Scenario | PLP |
| Description | Verify that the user is able to filter Categories → Women → Dresses |
| Browser | Chrome |
| Expected Result | A filtered list of products appears |
| Actual Result | A filtered list of products appears |
| Status | Pass |

### Test Steps
1. Navigate to https://www.automationexercise.com/
2. Click on the **Products** tab
3. Filter by **Women → Dresses**

---

## TC_006 - Product Detail Page (PDP)

| Field | Details |
|--------|---------|
| Project | E-Commerce |
| Test Case ID | TC_006 |
| Module | Products Tab |
| Type | SILO |
| Test Scenario | PDP |
| Description | Verify that the user can open Rose Pink Embroidered Maxi Dress and validate product details |
| Browser | Chrome |
| Expected Result | User is landed on the product detail page |
| Actual Result | Product name, category, price, availability, condition, and brand validated |
| Status | Pass |

### Test Steps
1. Click on the **Products** tab
2. Filter by **Women → Dresses**
3. Click **View Product** for **Rose Pink Embroidered Maxi Dress**
4. Validate product name, category, price, availability, condition, and brand

---

## TC_007 - Search Product

| Field | Details |
|--------|---------|
| Project | E-Commerce |
| Test Case ID | TC_007 |
| Module | Products Tab |
| Type | SILO |
| Test Scenario | Search Product |
| Description | Verify that the user can search for a product |
| Browser | Chrome |
| Expected Result | User is able to search and view relevant products |
| Actual Result | A filtered list of products appears |
| Status | Pass |

### Test Steps
1. Click on the **Products** tab
2. Enter **"maxi dress"** in the search box
3. Click the **Search** button
4. Verify **Searched Products** is displayed
5. Verify relevant products are shown

---

## TC_008 - Add Products to Cart

| Field | Details |
|--------|---------|
| Project | E-Commerce |
| Test Case ID | TC_008 |
| Module | Add to Cart |
| Type | P2P |
| Test Scenario | Products Added to Cart |
| Description | Verify that the user can add products to cart and validate pricing |
| Browser | Chrome |
| Expected Result | Blue Shirt and Men Tshirt are added to the cart |
| Actual Result | Blue Shirt of price 500 and Men Tshirt of price 400 added to the cart |
| Status | Pass |

### Test Steps
1. Click on the **Products** tab
2. Hover over the first product and click **Add to Cart**
3. Click **Continue Shopping**
4. Hover over the second product and click **Add to Cart**
5. Click **View Cart**
6. Verify both products are added
7. Verify price, quantity, and total

---

## TC_009 - Remove Products from Cart

| Field | Details |
|--------|---------|
| Project | E-Commerce |
| Test Case ID | TC_009 |
| Module | Add to Cart |
| Type | SILO |
| Test Scenario | Remove Products from Cart |
| Description | Verify that the user can remove products from the cart |
| Browser | Chrome |
| Expected Result | User is able to remove products from the cart |
| Actual Result | User is able to remove products from the cart |
| Status | Pass |

### Test Steps
1. Click on the **Products** tab
2. Hover over a product and click **Add to Cart**
3. Click **View Cart**
4. Verify product details
5. Click the **X** button corresponding to the product
6. Verify the product is removed

---

## TC_010 - Place Order After Login

| Field | Details |
|--------|---------|
| Project | E-Commerce |
| Test Case ID | TC_010 |
| Module | Place Order |
| Type | E2E |
| Test Scenario | Login Before Checkout |
| Description | Verify that the user can place an order successfully after logging in |
| Browser | Chrome |
| Expected Result | User is able to place an order and order ID is generated |
| Actual Result | User is able to place an order and order ID is generated |
| Status | Pass |

### Test Steps
1. Click on the **Products** tab
2. Add the first product to the cart
3. Click **Continue Shopping**
4. Add the second product to the cart
5. Click **View Cart**
6. Verify both products are added
7. Verify prices, quantity, and total
8. Click **Proceed to Checkout**
9. Click **Register/Login**
10. Login with valid credentials
11. Verify address details and order summary
12. Enter comments
13. Click **Place Order**
14. Enter payment details:
    - Name on Card
    - Card Number
    - CVC
    - Expiration Date
15. Click **Pay and Confirm Order**
16. Verify success message:
    > "Your order has been placed successfully!"

---
