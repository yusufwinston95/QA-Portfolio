# Test Cases – Ride‑Sharing (iPhone)

| ID | Title | Pre‑Condition | Steps | Expected Result | Status |
|---|---|---|---|---|---|
| MTC-001 | App launches successfully | App installed | Tap app icon | Splash → Home screen loads without crash | Pending |
| MTC-002 | Location permission prompt | First launch | Observe iOS permission prompt | User sees prompt with Allow While Using / Don’t Allow | Pending |
| MTC-003 | Open main menu/profile | On Home | Tap menu/profile icon | Menu opens; items visible (Payments, Rides, Help, Settings) | Pending |
| MTC-004 | Start ride request (mock) | Location enabled | Enter destination → Tap **Request** | App shows driver search/estimate UI | Pending |
| MTC-005 | Cancel ride request | During search | Tap **Cancel** | Request cancels; user returned to Home | Pending |
| MTC-006 | Error messaging for missing destination | On Home | Tap **Request** without destination | Inline or toast error displayed | Pending |
| MTC-007 | Accessibility basic checks | Any screen | Attempt VoiceOver / dynamic type | Critical labels accessible; no clipped text | Pending |
