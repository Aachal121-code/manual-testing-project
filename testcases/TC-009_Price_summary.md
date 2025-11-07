# TC-009 — Price, Item Total & Tax Calculation

**ID:** TC-009  

**Title:** Verify product price & total calculation during checkout  

**Preconditions:**  
- User has added at least **2 items** to the cart  
- Items appear on checkout summary page  

**Steps:**  
1. Go to the **Cart** page  
2. Click **Checkout**  
3. Enter valid user details and continue  
4. On **Checkout: Overview** page, verify:  
   - individual item prices  
   - item total  
   - tax  
   - final total  

**Expected Result:**  
- Item total = correct sum of item prices  
- Prices must display in proper currency format (e.g., `$59.98`)  
- Final total = Item total + Tax  

**Actual Result:**  
- Item total appears as **$59.980000000000004**  
- Floating-point precision bug observed  
- Total not formatted correctly  

**Status:**  Fail  

**Evidence:**  evidence/screenshots/TC-009-Fail.png