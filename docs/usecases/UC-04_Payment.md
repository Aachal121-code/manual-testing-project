# Use case: UC-04 - Payment

**Use case ID:** UC-04   
**Name:** Verify payment flow using valid and invalid card details      
**Actor:** Customer    
**Preconditions:** 
- User is logged in successfully.  
- User has at least one product in the cart.  
- User has valid card details and sufficient account balance. 

**Basic Flow:** 
1. User logs in with valid credentials.  
2. Adds products to the cart.  
3. Clicks on the **Checkout / Payment** button.  
4. Selects **Pay with Card** option.  
5. Enters valid card credentials and OTP.  
6. Confirms the order.  

**Alternate Flow:**
- Total amount mismatch — show message *“Total does not match cart items.”*  
- Invalid card credentials or invalid OTP — show error *“Card credentials are invalid.”*  

**Exceptional flow:**
- Server down or network issue — show *“Service Unavailable.”*  
- Bank server timeout.  
- User session expires before completing payment. 

**PostCondition:** 
- User enters valid card details and OTP.  
- Payment is processed successfully and order is confirmed.  
- Confirmation message and receipt are displayed.