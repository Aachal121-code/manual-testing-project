# TC-001 - Login with valid credentials

**ID:** TC-001  
**Title:** Login with valid username and password  
**Preconditions:** Account exists: username=`standard_user`, password=`secret_sauce`  
**Steps:**
1. Open "https://www.saucedemo.com"
2. Enter username `standard_user`
3. Enter password `secret_sauce`
4. Click "Login"

**Expected Result:** User is redirected to inventory page (URL contains `/inventory.html`) and products are visible.       
**Actual Result:** Inventory page load. products are visible.          
**Status:** Pass      
**Evidence:** evidence/screenshots/TC-001-pass.png    