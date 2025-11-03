# Test Cases – Uber iPhone (Manual UI/Smoke)

| ID | Title | Preconditions | Steps | Expected Result | Status |
|---|---|---|---|---|---|
| MTC-001 | App launches successfully | App installed | Tap Uber icon | Splash → Home map renders without crash | Pass |
| MTC-002 | Home navigation bar visible | On Home | Observe header/actions | "Where to?" field and Later button visible | Pass |
| MTC-003 | Bottom nav renders | On Home | Observe bottom bar | Home, Services, Activity, Account items visible and tappable | Pass |
| MTC-004 | Open Account screen | On Home | Tap **Account** | Account/profile screen opens | Pass |
| MTC-005 | Account modules visible | On Account | Observe | Help, Wallet, Inbox, Safety modules visible | Pass |
| MTC-006 | Return to Home from Account | On Account | Tap **Home** in bottom nav | Home screen opens | Pass |
| MTC-007 | Enter destination from Home | On Home | Tap **Where to?** → enter destination | Ride options sheet appears | Pass |
| MTC-008 | Ride options list renders | On ride sheet | Scroll content | Options like UberX, Priority, XL appear with ETA and price | Pass |
| MTC-009 | Price formatting | On ride sheet | Observe pricing | Price shows currency + two decimals, discounts strike-through original | Pass |
| MTC-010 | Primary CTA appears | On ride sheet | Observe bottom sheet | Payment method + "Choose UberX" CTA visible and tappable | Pass |
| MTC-011 | Accessibility contrast quick check | Any | Observe dark-mode text/labels | Text maintains sufficient contrast to be readable | Observe |
| MTC-012 | Icons/labels not clipped | Any | Rotate device (if allowed) | Labels remain fully visible; no overlap | N/E |
| MTC-013 | Required permissions prompt | First launch fresh | Reinstall → open | Location prompt displayed with standard iOS buttons | N/E |
| MTC-014 | Error for missing destination | On Home | Tap **Where to?** then **Cancel/Back** → try request | App prevents request without destination; shows message | N/E |
| MTC-015 | Wallet entry opens | On Account | Tap **Wallet** | Wallet screen opens (or login/verification prompt) | N/E |
| MTC-016 | Inbox entry opens | On Account | Tap **Inbox** | Inbox or message list appears | N/E |

Legend: **Pass** = verified via provided screenshots; **N/E** = Not Executed during this capture; **Observe** = qualitative check.
