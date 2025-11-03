# Bug Report Log – Swag Labs (E‑commerce)

All bugs were captured with environment: macOS (desktop), Chrome (version unknown).

---

## BUG-001 – Cart badge count incorrect after adding multiple products
**Severity:** Medium  
**Area:** Products / Header Cart Badge  
**Preconditions:** Logged in, 0 items in cart  
**Steps to Reproduce:**
1. From Products page, click **Add to cart** on Product A.
2. Click **Add to cart** on Product B (a different product).
3. Observe the cart icon badge value.
**Expected Result:** Badge shows `2` (reflects two items).
**Actual Result:** Badge shows `1` (count does not increment correctly after second add).  
**Evidence:** `screenshots/products-with-two-items-badge-incorrect.png` (user provided screenshot shows "1").  
**Notes:** May be UI state or event handling issue; verify network and cart state.

---

## UI-001 – Checkout information page has excessive whitespace (usability)
**Severity:** Low (UX)  
**Area:** Checkout – Your Information  
**Description:** Form container appears centered with large surrounding whitespace, making the page feel incomplete or misaligned on desktop.  
**Expected:** Reasonable spacing around form; content density consistent with other pages.  
**Actual:** Very sparse layout; CTA buttons appear far from form.  
**Evidence:** `screenshots/checkout-your-information-empty.png`  
**Recommendation:** Review responsive layout breakpoints and container width.

---

## VAL-001 – Required field validation triggers with empty submission (baseline)
**Severity:** Info (Expected Behavior Verified)  
**Area:** Checkout – Validation  
**Description:** Submitting empty form displays inline error and banner: “Error: First Name is required.”  
**Evidence:** `screenshots/checkout-validation-required.png`  
**Action:** None (documented as baseline for regression).

