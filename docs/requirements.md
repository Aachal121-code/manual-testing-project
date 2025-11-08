# Software Requirements – Saucedemo Website Testing Project

## 1. Introduction
This document defines the functional and non-functional requirements for testing the Saucedemo e-commerce demo website.  
The purpose is to identify what features should be validated and what behaviour is expected from the system.

---

## 2. Scope
The scope of this QA project includes:
- Login & Logout  
- Product Listing  
- Add to Cart  
- Cart Operations  
- Checkout  
- Price Calculations  
- Error Handling & UI behaviour  

Out of scope:
- Payment processing (not available on demo site)  
- API testing  
- Performance & load testing  

---

## 3. Functional Requirements (FR)

### **FR-01: User Authentication**
- System must allow login using valid username and password.
- System must show an error message for invalid credentials.
- Logout functionality must redirect to the login page.

### **FR-02: Product Listing**
- User must see a list of available products after login.
- Products must display: **Name, Price, Image**.
- Sorting dropdown should allow sorting by price or name.

### **FR-03: Product Details**
- Clicking a product image should open the product detail page.

### **FR-04: Add to Cart**
- User must be able to add one or more items to the cart.
- Cart icon should update based on number of items added.

### **FR-05: Cart Page**
- User must be able to remove items from the cart.
- Item details and price must be displayed correctly.

### **FR-06: Checkout**
- User must fill First Name, Last Name, and Zip Code.
- System must navigate to Overview page.
- Order must complete with “Thank you for your order” message.

### **FR-07: Price Calculation**
- Item Total must be sum of all product prices.
- Tax must be calculated correctly.
- Total must be displayed correctly without rounding errors.

---

## 4. Non-Functional Requirements (NFR)

### **NFR-01: Usability**
- Interface should be simple and easy to navigate.
- Buttons and links should be clearly visible.

### **NFR-02: Performance**
- Pages should load within 3 seconds on normal network.

### **NFR-03: Compatibility**
- Website must work on latest Chrome & Firefox.

### **NFR-04: Reliability**
- Website should not crash during checkout navigation.

### **NFR-05: Security**
- User must not access inventory or cart without authentication.

---

## 5. Assumptions
- Payment system is not implemented in the demo site.
- Product list is static and controlled by the website.

---

## 6. Risks
- dosen't showing clear error message (UX unclear).
- Floating-point price mismatch (observed bug).
- Filter/sorting options may fail due to UI issues.
- False positives due to unstable demo environment.

---

**Prepared By:** Aachal Bhonde  
**Date:** 04-11-2025
