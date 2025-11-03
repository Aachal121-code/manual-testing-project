# bug-001 - Error message for invalid login is unclear

**Title:** Invalid login does not showing clear error message     
**Environment:** Chrome 116 / Windows 10 / Saucedemo      
**Steps to Reproduce:**   
1. Open https://www.saucedemo.com
2. Enter username `wrong_user` and password `wrong_pass`
3. Click Login


**Expected Result:** Show specific error: "Username and password do not match any user in this service".    
**Actual Result:** Page reloads but dosen't showing clear error message (UX unclear).    
**Severity:** Minor (UI/UX issue)     
**Priority:** Medium  
**Attachments:** evidence/screenshots/Bug-001.png     