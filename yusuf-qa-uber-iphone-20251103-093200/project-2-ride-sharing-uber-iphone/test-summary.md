# Test Summary – Uber iPhone

**Tester:** Yusuf Winston  
**Device:** iPhone (fill model + iOS)  
**Test Type:** Manual – UI/Smoke, exploratory  
**Session Evidence:** 3 screenshots (Home, Account, Ride options)

## Coverage
- Navigation: Home ↔ Account
- Destination entry and ride options modal
- Pricing/CTA visibility
- Quick accessibility/contrast observations (dark mode)

## Results
- **Cases Authored:** 16
- **Executed (from evidence):** 10 Pass / 1 Observe
- **Not Executed:** 5 (permissions, rotation, wallet, inbox, error path)

## Highlights
- Primary ride-selection flow appears functional from UI perspective.
- Pricing discount presentation verified.
- Minor **UX/accessibility** observations recorded for future review.

## Next Recommendations
- Execute permission prompts and denied-permission states.
- Validate VoiceOver reading order and focus on ride options.
- Add negative tests (poor network, cancelled request).
