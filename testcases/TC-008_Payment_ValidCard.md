# Test Case: TC-008 — Payment Functionality

**Test Case ID:** TC-008  
**Title:** Verify that the user can complete payment using valid card details  

**Preconditions:**  
- User is logged in successfully (refer to TC-001).  
- User has at least one item in the cart.  
- User proceeds to checkout page (`/checkout-step-one.html`).  

**Test Steps:**  
1. Navigate to the Checkout page.  
2. Verify that the payment option is available.  
3. Attempt to proceed with payment using valid card credentials (if available).  

**Expected Result:**  
- User should be able to select a payment method (e.g., card).  
- After entering valid details, payment should process successfully, and a confirmation message should appear.  

**Actual Result:**  
- Payment option not available on the checkout page.  
- User unable to proceed beyond checkout step.  

**Status:**  Blocked  

**Reason:**  
- Payment functionality is not implemented on the site.  

**Evidence:**  
- evidence/screenshots/TC-008-blocked.png
