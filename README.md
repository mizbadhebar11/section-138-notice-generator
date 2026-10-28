# Section 138 Notice Generator

A free, browser-based tool that drafts a statutory demand notice for a dishonoured cheque under Section 138 of the Negotiable Instruments Act, 1881, and calculates the key deadlines.

**Live demo:** https://mizbadhebar11.github.io/section-138-notice-generator/
<img width="1272" height="720" alt="Screenshot 2026-10-28 at 2 17 11 PM" src="https://github.com/user-attachments/assets/fb1d4894-4dee-41b3-9d43-6d329b543d54" />

## What it does
- Takes cheque, party, and dishonour details through a simple form.
- Generates a draft notice with the amount in Indian-style words.
- Calculates: cheque validity (3 months), last day to send the notice (30 days from the return memo), the drawer's 15-day payment window, and the complaint filing window (1 month).
- Flags a late presentation or a late notice.
- Copy the notice or print it.

## Privacy
Everything runs in your browser. No data is sent to a server or stored.

## Run locally
Open `index.html` in any browser. No install or build step.

## Limits
- Draft generator only. Not legal advice. A qualified advocate should review the notice before it is sent.
- Dates assume receipt of the notice on the notice date. Adjust if you know the actual date of receipt.
- Sample data in the app is fictional.

## Roadmap
- Section 141 (companies) variant
- Hindi version
- Limitation calculators for other statutes

## Contributing
Issues and suggestions from lawyers are welcome.

## Licence
MIT
