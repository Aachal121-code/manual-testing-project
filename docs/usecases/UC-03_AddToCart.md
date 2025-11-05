# Use Case: UC-03 - Add to Cart and remove 

**Use case ID:** UC-03    
**Name:** Add one or more items to the cart and remove it from the cart   
**Actor:** Customer    
**Preconditions:**
- User is logged in successfully
- Inventory page is loaded and products are visible
- Application server is up and running

**Basic Flow:** 
1. User logged in with valid credentials  
2. System redirected to the inventory page and products are visible  
3. User clicks on "Add to cart" from the product listing 
4. User can check updated cart icon  
5. User can remove products from cart by clicking on `Remove` button 
6. User can check updated cart icon again 

**Alternate Flow:**
- `Add to Cart` button is not working 
- Cart icon is not updating to users selection
- `Remove` button is not responding and doesn't updating `Cart.html`  

**Exceptional Flow:**
- Server down or network issue -> show "Service Unavailable" message.    
- Session timeout before loading products.

**Postcondition:**
- User can add selected items to the cart successfully
- selected items are removed from the cart successfully