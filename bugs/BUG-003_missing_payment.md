# BUG-005 — Payment Option Missing on Checkout Page

**Title:** Payment method not available on Checkout page  

**Environment:**  
- Browser: Chrome 
- OS: Windows 11
- Application: https://www.saucedemo.com  

**Preconditions:**  
- User logged in successfully  
- At least one product added to cart  
- Navigated to the Checkout page  

**Steps to Reproduce:**  
1. Log in with valid credentials.  
2. Add any product to the cart.  
3. Click on the **Cart** icon → Proceed to **Checkout**.  
4. Observe the page layout and available actions.  

**Actual Result:**  
- No payment options are displayed (e.g., Card, UPI, Cash, etc.).  
- User cannot complete the checkout flow.  

**Expected Result:**  
- User should be able to select a **payment method** and complete the transaction successfully.  

**Severity:**  High  
**Priority:**  Medium  
**Status:**  Open  

**Attachments:**  
- evidence/screenshots/BUG-003.png
