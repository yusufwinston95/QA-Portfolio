# Bug & Observation Log – Uber iPhone

> Notes are written from screenshots; severity reflects user impact. Items marked "Observation" are UX/accessibility notes rather than confirmed defects.

---

## OBS-001 – Contrast risk on dark mode (text vs background)
**Type:** Observation (Accessibility)  
**Area:** Global UI (dark theme)  
**Description:** Some gray text on black background (bottom nav labels, secondary descriptions) may approach WCAG contrast limits on certain devices.  
**Expected:** Text meets WCAG AA contrast for body text.  
**Evidence:** `screenshots/home.png`, `screenshots/account.png`  
**Recommendation:** Run automated contrast checks; adjust color tokens if needed.

---

## OBS-002 – Tight clustering near profile rating badges
**Type:** Observation (Visual spacing)  
**Area:** Account header  
**Description:** Rating and "Verified" badges align closely to the profile avatar and name; spacing may appear crowded on smaller iPhones.  
**Expected:** Adequate padding/margins between badges and avatar.  
**Evidence:** `screenshots/account.png`

---

## OBS-003 – Ride options sheet vertical density
**Type:** Observation (Readability)  
**Area:** Ride selection sheet  
**Description:** Multiple elements (ETA, passengers, price, discount) compete for space; ensure voiceover reading order and hit targets meet HIG.  
**Expected:** Clear hierarchy; accessible hit areas; sensible VO order.  
**Evidence:** `screenshots/ride-options.png`

---

## VAL-001 – Price discount display verified
**Type:** Validation (expected behavior)  
**Area:** Ride selection sheet  
**Description:** Discounted price shows with strikethrough original; green down-arrow indicator communicates lower-than-usual pricing.  
**Evidence:** `screenshots/ride-options.png`
