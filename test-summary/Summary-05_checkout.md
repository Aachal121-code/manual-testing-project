# Test Summary – Checkout  (Run Date: 08-11-2025)  

Total Test Cases: 2  
Passed: 1  
Failed: 1  

Failures:
- **TC-009 – Price, Item Total & Tax Calculation**  
  Item total is calculated incorrectly due to floating-point precision issues  
  (e.g., `$59.980000000000004` instead of `$59.98`).  
  *(See BUG-004)*  

Observations
- Checkout information page loads successfully.  
- User can enter First Name, Last Name, and Zip Code without issues.  
- Navigation between **Cart → Checkout → Overview → Finish** works smoothly.  
- The order confirmation message “THANK YOU FOR YOUR ORDER” displays correctly.  
- Price calculation logic has a formatting/precision issue on the **Overview** page.  

Recommendations
- Fix floating-point calculation to ensure correct currency formatting.  
- Round final amounts using proper monetary formatting (e.g., 2 decimal places).  
- Add validation for empty fields in the checkout information form.   
- Add a success/toast message when user completes checkout.  

Tester: Aachal Bhonde