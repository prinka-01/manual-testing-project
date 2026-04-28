# Requirements Traceability Matrix (RTM)

## Overview
This document maps business requirements to corresponding test cases to ensure complete test coverage.

---

## RTM Table

| Req ID | Requirement Description | Module | Scenario Name | Test Case ID | Test Description | Priority | Test Status | Remarks |
|--------|------------------------|--------|---------------|--------------|------------------|----------|-------------|---------|
| R1 | User should be able to log in with valid credentials | Login | Valid Login functionality | TC_01 | Verify successful login with valid username & password | High | Pass | Working as expected |
| R2 | System should prevent login with invalid password | Login | Invalid Password | TC_02 | Verify error message for invalid password | High | Pass | Error message differs slightly |
| R3 | System should prevent login with invalid username | Login | Invalid username | TC_03 | Verify error message for invalid username | High | Pass | Error message differs slightly |
| R4 | System should validate mandatory login fields | Login | Empty Fields | TC_04 | Verify validation when fields are empty | High | Pass | Browser validation message shown |
| R5 | User should be able to filter products by category | Products Tab | PLP | TC_05 | Verify filtering Women → Dresses | Medium | Pass | Filter works correctly |
| R6 | User should be able to view product details | Products Tab | PDP | TC_06 | Verify product detail page and attributes | Medium | Pass | All product details validated |
| R7 | User should be able to search products | Products Tab | Search Product | TC_07 | Verify search functionality with keyword | Medium | Pass | Results displayed correctly |
| R8 | User should be able to add products to cart | Add to Cart | Products added to cart | TC_08 | Verify adding multiple products to cart | High | Pass | Prices and totals correct |
| R9 | User should be able to remove products from cart | Add to Cart | Remove Products from cart | TC_09 | Verify removing products from cart | High | Pass | Removal works correctly |
| R10 | User should be able to place an order after login | Place Order | Login before checkout | TC_10 | Verify complete checkout flow with login and payment | High | Pass | Defect logged earlier for order ID not generated; fixed by dev and closed after retest |

---

## Defect Summary

- 🐞 **Defect ID:** BUG_01  
- **Description:** Order ID was not generated after successful order placement  
- **Status:** Closed  
- **Resolution:** Issue fixed by development team and successfully verified in retesting  

---

## Summary

- ✅ All test cases are passing  
- ⚠️ Minor mismatch in error messages for invalid login scenarios  
- 🐞 One defect identified and resolved  

---

## Coverage

**Total Requirements:** 10  
**Total Test Cases:** 10  
**Coverage:** 100%  
