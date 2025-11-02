#  Use Case : UC-01_Login/Logout

**Use Case ID:** UC-01  
**Name:** Login and Logout  
**Actor:** Registered User (Customer)  
**Preconditions:** Internet available,User account exists (username/password). 
**Basic Flow:**
1. User opens https://www.saucedemo.com 
2. User enter username and password
3. user clicks "Login"
4. system validate credentials and redirects to the inventory page
5. user clicks "Logout" and returns to Login page

**Alternate Flow :** 
- Invalid credentials -> show "Username and Password do not match" error.

**Exception Flow :** 
- Server down -> show "service unavailable" message.

**Postcondition :**
- User is logged in and can access the inventory
- After Logout the session ends.