# Test Cases – Swag Labs (E‑commerce)

| ID | Title | Pre‑Condition | Steps | Expected Result | Status |
|---|---|---|---|---|---|
| TC-001 | Login with valid credentials | On login page | Enter `standard_user` + `secret_sauce` → Click **Login** | User lands on Products page | Pass |
| TC-002 | Add item to cart from list | Logged in on Products | Click **Add to cart** for any product | Cart badge increments to 1; button changes to **Remove** | Pass |
| TC-003 | Add second distinct item | At least 1 item already in cart | Click **Add to cart** on another product | Cart badge increments by 1 (e.g., 2) | **Fail** (see BUG-001) |
| TC-004 | Remove item from Products list | Item already added | Click **Remove** | Item removed; badge decrements by 1 | Pass |
| TC-005 | Open Cart page | 1+ items in cart | Click cart icon | Cart page lists items with price, qty, and **Remove** | Pass |
| TC-006 | Remove item from Cart | Item present in cart | Click **Remove** on cart line item | Item removed; totals update; badge decrements | Pass |
| TC-007 | Proceed to Checkout | On Cart page with 1+ items | Click **Checkout** | Navigates to **Checkout: Your Information** page | Pass |
| TC-008 | Submit empty Checkout form | On Checkout Info page | Click **Continue** with empty fields | Inline errors show for required fields | Pass (see screenshot) |
| TC-009 | Validate required error dismissal | Errors visible | Type valid First/Last/Zip | Errors clear when fields valid | Not executed |
| TC-010 | Cancel from Checkout | On Checkout Info page | Click **Cancel** | Returns to Cart page without data loss | Not executed |
| TC-011 | Price format on Cart page | On Cart page | Observe price formatting | Prices show two decimals with currency | Pass |
| TC-012 | Badge updates after cart removal on Products | Item in cart | From Products, click **Remove** | Badge decrements accordingly | Pass |
