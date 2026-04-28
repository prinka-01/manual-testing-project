# E-Commerce Testing Scenarios

## Authentication Module

- Verify successful login with valid credentials.
- Verify login fails with invalid password.
- Verify login fails with invalid username.
- Verify login fails when both username and password are invalid.
- Verify login validation when username field is empty.
- Verify login validation when password field is empty.
- Verify logout functionality.
- Verify user can navigate to the signup page.

---

## Product Listing Page (PLP)

- Verify all products are displayed on the Products page.
- Verify user can filter products by category.
- Verify user can filter products by sub-category.
- Verify filtered products match the selected category.
- Verify product details are displayed correctly in the product listing.
- Verify pagination functionality on the Products page.
- Verify sorting functionality if available.

---

## Product Detail Page (PDP)

- Verify user can navigate to the product detail page.
- Verify product name is displayed correctly.
- Verify product price is displayed correctly.
- Verify product availability status is displayed.
- Verify product condition is displayed.
- Verify product brand is displayed.
- Verify product category is displayed.
- Verify quantity can be updated before adding to cart.

---

## Search Functionality

- Verify search results are displayed for a valid product keyword.
- Verify partial product name search works correctly.
- Verify search is case-insensitive.
- Verify no results message appears for invalid search keywords.
- Verify search results are relevant to the entered keyword.

---

## Shopping Cart

- Verify user can add a single product to the cart.
- Verify user can add multiple products to the cart.
- Verify cart displays correct product details.
- Verify cart displays correct product prices.
- Verify cart calculates total price accurately.
- Verify product quantity is updated correctly.
- Verify user can remove a product from the cart.
- Verify cart is empty after removing all products.

---

## Checkout Process

- Verify user can proceed to checkout from the cart.
- Verify login prompt appears for unauthenticated users.
- Verify registered user can complete checkout successfully.
- Verify delivery address is displayed correctly.
- Verify billing address is displayed correctly.
- Verify order summary is accurate.
- Verify comments can be added before placing the order.

---

## Payment Module

- Verify payment succeeds with valid card details.
- Verify payment fails with invalid card number.
- Verify payment fails with expired card.
- Verify payment fails with invalid CVV.
- Verify order confirmation message is displayed after successful payment.
- Verify order ID is generated after successful purchase.

---

## Order Management

- Verify order details are visible after placing an order.
- Verify user can download the invoice.
- Verify order is listed in purchase history.
- Verify confirmation email is sent after successful order placement.

---

## Negative Test Scenarios

- Verify application handles invalid inputs gracefully.
- Verify mandatory field validations are displayed.
- Verify system prevents duplicate order submissions.
- Verify session timeout behavior during checkout.
- Verify cart data persists after page refresh.

---

## Cross-Browser Testing

- Verify application functionality on Chrome.
- Verify application functionality on Firefox.
- Verify application functionality on Edge.
- Verify responsive design on mobile devices.

---

## End-to-End Scenarios

- Verify complete user journey from login to order placement.
- Verify guest user registration followed by purchase.
- Verify product search, add to cart, checkout, and payment flow.
- Verify returning user can place an order successfully.

---
