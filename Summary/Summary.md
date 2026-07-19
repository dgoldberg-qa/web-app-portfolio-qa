# Test summary report

## Project information

- **Project:** SauceDemo (https://www.saucedemo.com/)
- **Platform:** PC
- **Operating system:** Windows 11
- **Testing type:** Functional testing / Exploratory testing

## Scope

The following features were tested:

Login page
Products
Cart
Checkout

## Test artifacts

| Artifact | Count |
|-----------|------:|
| Checklist items | 64 |
| Test cases | 5 |
| Bug reports |	5 |

## Bugs summary

| Severity | Count |
|-----------|------:|
| Critical | 0 |
| Major | 4 |
| Minor | 1 |
| Trivial | 0 |

## Main findings 

- User session management issues: after session expiration, protected actions could still be performed before redirecting the user to the login page.
- User data isolation issue: cart contents were shared between different user accounts.
- Checkout validation issues, including the ability to complete an order with an empty cart.
- UI and data display issues, including incorrect product images and incorrect checkout form behavior.
- Additional testing with special test accounts revealed application-specific issues related to images, checkout and performance behavior.


## Overall assessment

The application is generally functional and allows users to complete the main shopping flow: login, browse products, add items to the cart and complete checkout.
However, several issues were found that affect user experience and data consistency, including session management, cart isolation and checkout validation problems.
The application requires additional bug fixes and regression testing before being considered fully stable.
