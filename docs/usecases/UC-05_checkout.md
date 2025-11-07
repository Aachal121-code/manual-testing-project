# Use Case: UC-05 — Checkout Process

**Use Case ID:** UC-05  
**Name:** Verify the checkout process until order completion  
**Actor:** Customer  

**Preconditions:**  
- User is logged in  
- User has at least one product added to the cart  

**Basic Flow:**  
1. User clicks the Cart icon.  
2. User clicks the **Checkout** button.  
3. User enters First Name, Last Name, Zip Code.  
4. User clicks **Continue**.  
5. User reviews order summary.  
6. User clicks **Finish**.  

**Alternate Flow:**  
- User leaves required fields empty → system shows validation errors.  
- Wrong Zip Code format → show specific error message.  

**Exceptional Flow:**  
- Server down → show “Service Unavailable”.  
- Session expired → redirect to login page.  

**Postcondition:**  
- Order is completed successfully.  
- User sees **"THANK YOU FOR YOUR ORDER"** page.
