# Test Summary - Product Listing   (Run date : 5-11-25)

Total test cases: 2   
passed: 1  
Failed: 1   

Failures:
- TC-005 - Clicking on the `filter icon` does not open the dropdown, even though the hand cursor appears. (see BUG-002)

Obervation:
- Product list loads correctly after user login.
- All products display with **Name, Price, and Image**, but image quality varies.
- The **sorting/filter dropdown** is present, Clicking on the `filter icon` does not open the dropdown, even though the hand cursor appears.
- Product details page opens when clicking an image  

Recommandations:  
- Improve clarity of **filter/sorting dropdown** by adding:
   - Highlighted active state  
   - Loading indicator  
   - Clear UI change to show filter applied
- fix click Event on filter dropdown menu

Tester: Aachal Bhonde  