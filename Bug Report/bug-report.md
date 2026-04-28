# 🐞 Bug Report

## 1. Bug Information
- **Bug ID:** BUG_01  
- **Title:** Order ID not generated after successful order placement  
- **Module:** Place Order / Checkout  
- **Severity:** High  
- **Priority:** High  
- **Status:** Closed  

---

## 2. Environment
- **Application URL:** https://www.automationexercise.com/  
- **Browser:** Google Chrome  
- **Device:** Desktop  

---

## 3. Description
After completing the checkout process and making a successful payment, the system does not generate or display an Order ID. This prevents users from tracking or confirming their order.

---

## 4. Preconditions
- User is registered and logged in  
- Products are added to the cart  

---

## 5. Steps to Reproduce
1. Navigate to the website  
2. Click on **Products**  
3. Add products to the cart  
4. Click **View Cart**  
5. Click **Proceed to Checkout**  
6. Login (if not already logged in)  
7. Click **Place Order**  
8. Enter valid payment details  
9. Click **Pay and Confirm Order**  

---

## 6. Expected Result
- System should generate and display a unique **Order ID**  
- Confirmation message should include order details  

---

## 7. Actual Result
- Order is placed successfully  
- Confirmation message is displayed  
- ❌ **Order ID is not generated or displayed**  

---

## 8. Attachments
- Screenshots:

---

## 9. Impact
- Users cannot track or reference their order  
- Reduces trust and usability of the checkout system  

---

## 10. Root Cause (Post-Fix)
- Issue in backend service responsible for generating Order ID  

---

## 11. Resolution
- Fixed by development team  
- Order ID generation logic corrected  

---

## 12. Retest Status
- Retested after fix  
- ✅ Order ID successfully generated and displayed  
- Bug marked as **Closed**  

---

## 13. Reported By
- QA Tester: _Priyanka_  
- Date: _20/04/2026_  
