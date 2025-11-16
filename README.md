# Dynamic-Compliance-Till
Zero-Error Age Verification Till Safeguard (Challenge 25 Enhancement)

This project provides a proof-of-concept for a low-cost, software-based enhancement to Point-of-Sale (POS) systems, designed specifically to eliminate human calculation error during age-restricted sales under the UK's Challenge 25 policy.

The core goal is to provide retail staff with an auditable, zero-doubt mechanism for verifying age after the customer's physical ID (e.g., Passport or Driving Licence) has been presented.

The Problem Solved

Staff diligence often fails at the point of mental calculation. In a high-pressure environment (busy bar, rush hour), asking staff to calculate if a date of birth (DOB) is 18 years, 0 months, and 0 days old is a major risk factor for non-compliance.

The Dual-Layer Solution

This system enforces compliance through two immediate, visual checks, guaranteeing accuracy for every transaction:

Layer 1: The Visual Cutoff Date Display (Pre-Input)

The till screen dynamically and prominently displays the single required cutoff birth date for that day. This date changes precisely at midnight and serves as the primary visual reference for staff.

Example: "To be 18 today, the person must be born on or before: 16 November 2007"

Layer 2: The Digital Verification Verdict (Post-Input)

After the staff member manually inputs the DOB from the physical ID, the system performs the precise calculation and instantly displays a large, unmistakable verdict:

🟢 GREEN LIGHT: APPROVED (DOB meets or precedes the cutoff date)

🔴 RED LIGHT: FAILED (DOB is after the cutoff date)

This digital check eliminates all mental math and provides a clear audit trail.


Implementation Details

The core functionality is implemented using simple JavaScript, making it framework-agnostic and easy to integrate into any existing POS infrastructure (Epos Now, Tevalis, etc.). The accompanying index.html file provides a fully functional, self-contained demonstration of this logic.

Setup & Demo

To view the interactive till screen demo, simply open the index.html file in any modern web browser.
