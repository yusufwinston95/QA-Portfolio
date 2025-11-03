# Test Summary – Swag Labs (E‑commerce)

**Tester:** Yusuf Winston  
**Test Type:** Manual – Functional & UI  
**Session Date(s):** 2024–2025 (portfolio capture)  
**Environment:** macOS + Chrome (desktop viewport)

## Scope
Covered login, add/remove cart items, cart view, checkout information validation, and general UI/UX observations on the Products and Checkout pages.

## Execution
- **Test Cases Authored:** 12
- **Tests Executed:** 9
- **Pass:** 7
- **Fail:** 1 (functional)
- **Not Executed:** 2 (timeboxed)
- **Bugs/Observations Logged:** 3 (1 functional, 1 UX, 1 informational validation record)

## Key Findings
- **Cart badge count** did not increment after adding a second product (see BUG-001).  
- Checkout validation behaves as expected for empty submission (VAL-001).
- Desktop layout on Checkout page could be improved for usability (UI-001).

## Recommendations
- Investigate cart badge update logic for multiple-item adds.
- Review responsive container widths on Checkout page.
- Extend negative test coverage on form validation (field-specific messages, zip formats).

## Attachments
- Screenshots located in `/screenshots`.
