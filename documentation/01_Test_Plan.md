# Test Plan
Manual Testing – AutomationExercise E-Commerce Website

## 1. Introduction

### 1.1 Purpose
The purpose of this test plan is to define the strategy, scope, and approach for manual testing of the AutomationExercise e-commerce web application.  
The goal of the testing effort is to identify functional defects, validation issues, and potential business risks before a hypothetical production release.

### 1.2 Scope
This testing effort focuses on the core user functionality of the application, including authentication, product browsing, cart functionality, checkout flow, payment submission, and contact forms.

The testing approach emphasizes manual functional testing and exploratory validation testing.

---

## 2. Application Overview

AutomationExercise is a demo e-commerce platform designed for testing practice.  
The platform allows users to browse products, create accounts, add items to a cart, and simulate checkout and payment processes.

The website under test can be accessed at:

https://automationexercise.com

---

## 3. Modules In Scope

The following application modules are included in the testing scope:

- User Registration and Account Creation
- User Login / Authentication
- Product Browsing and Product Details
- Cart Management
- Checkout Process
- Payment Submission
- Contact Us Form
- Account Deletion

---

## 4. Testing Approach

The testing strategy for this project includes:

- Manual Functional Testing
- Black-Box Testing
- Exploratory Testing
- Input Validation Testing

The application will be tested from an end-user perspective without direct access to backend code or system architecture.

---

## 5. Business-Critical Flows

The following flows are considered critical to the business functionality of the application:

- User Account Registration
- User Login
- Product Selection and Add to Cart
- Checkout Process
- Payment Submission

Failure in any of these flows would result in severe user experience issues and potential revenue loss for the business.

---

## 6. Risk Analysis

Initial exploratory testing identified potential risk areas within the application:

- Weak input validation across multiple forms
- Checkout flow allowing progression without validated shipping information
- Payment form accepting invalid data formats
- Contact form accepting incomplete or invalid input

These areas represent potential business risks and will be a focus during test case execution.
