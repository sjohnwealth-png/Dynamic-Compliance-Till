# The Dynamic Compliance Till Feature: A Human‑Centred Upgrade

This feature is designed to eliminate the single biggest failure point in age verification: staff performing mental arithmetic under pressure.

## 1. THE PAIN POINT: The 9 PM Rush (The Old Way)
🚨 The Scenario: Mental Math Meltdown

It's a festival bar, 9 PM. Four friends approach the bar demanding lagers before the headliner starts. The bartender, Sarah, is exhausted. One customer looks young, and his ID shows a 2007 birth year.

| Challenge | Impact on Staff & Business |
|---|---|
| The Calculation: | "Today is Oct 19, 2025. Is 2007 their 18th year? Did their birthday pass? I have 30 seconds..." |
| Cognitive Load: | Sarah must stop the order, break her flow, and perform complex arithmetic in a high-pressure environment. |
| The Risk: | A rushed 1-second mistake could result in a costly licensing breach and significant fines. |

**RESULT:** SLOW SERVICE, HIGH STRESS, HIGH RISK OF ERROR.

---

## 2. THE SOLUTION: Digital Certainty

Our feature is a dual safeguard, removing the guesswork entirely.

### Component A: Dynamic Compliance Panel (The Always‑On Guardian)
The display shows the required cutoff date in real-time, updated every 30 seconds from the local clock.

### Component B: Instant Verification Modal (The Confident Check)
When a physical ID is presented, staff tap the panel to launch the calculator.  
Input D/M/Y from the ID, the system instantly calculates the customer's exact age and outputs a clear, unambiguous verdict.

---

## 3. THE GAIN POINT: Total Confidence (The New Way)

✅ The Scenario: Zero‑Doubt Resolution

Sarah sees the 2007 birth year on the ID. She doesn't calculate. She simply compares the ID to the large, red cutoff date on the screen, or uses the calculator for absolute certainty.

| Action | Result for Staff & Business |
|---|---|
| Instant Comparison: | The ID shows **14 OCT 2007**. The screen says **10 OCT 2007**. The customer is immediately seen as too young. |
| ID Verification: | Sarah taps the panel, inputs the date, and receives a digital confirmation: **UNDERAGE (REFUSED)**. |
| Service Flow: | Sarah politely refuses the sale to the minor but serves the rest of the group. The transaction is complete in under 15 seconds. |

**RESULT:** FAST SERVICE, ZERO COMPLIANCE DOUBT, LICENCE IS SECURE.

---

## Value Proposition

This Dynamic Compliance Feature is a proactive investment in staff confidence and regulatory due diligence, turning a stressful calculation into a simple, confident button tap. It doesn't replace Challenge 25; it makes it foolproof.

---

## Files included in this repo (suggested)
- `bar_till_system.html` — demo/POC of the till UI and the dynamic compliance feature.
- `README.md` — this README.
- `LICENSE` — MIT (optional).

---

## Next steps / Ideas
- Add persistent sales tracking (localStorage or backend)
- Export / sync to Google Sheets or CSV for shift reporting
- Integrate with a proper payment terminal or POS API
- Add tests, CI and build pipeline if the UI gets compiled into an SPA
