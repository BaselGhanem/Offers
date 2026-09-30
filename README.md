# Dar Aldawa Rewards — management prototype

Arabic, mobile-first, plain HTML/CSS/JavaScript prototype using the supplied Dar Aldawa logo and guideline colors.

## Routes
- `index.html`: pharmacy journey, reward filtering, goal selection, point balance, ledger, redemption requests.
- `admin.html`: local demo request review, fulfilment reference, validated CSV transaction imports, duplicate guard, budget sensitivity.
- `proposal.html`: public management concept, reward sources, security and implementation roadmap.
- `card.html`: two-sided proposed physical card at 85.60 × 53.98 mm; QR opens the intended GitHub Pages URL.

## Run
Serve this folder with any static HTTP server. Demo pharmacy name: `صيدلية الشراكة`. Demo PIN: `246810`.

The PIN is deliberately public demo data. There is no production authentication. localStorage holds synthetic data on one device only. Requests do not reach Dar Aldawa and no vouchers or WhatsApp messages are sent. Never upload real customer data into this public prototype.

## Proposed rules

Base rule: 1 point / JOD 125; JOD 0.50 / point. Annual participation floor: 30 earned points after JOD 100 eligible annual sales. Annual cap: 1,000 points. These are proposed policies for management review, not actual sales results or promises. Customer sales, codes, source workbooks and sales-derived aggregates are absent from this public repository. The financial model and sales calibration are delivered privately.

## Before production
Implement centralized authentication, private database, atomic ledger/reservations, row-level permissions, import idempotency, chain mapping, finance reconciliation, provider contracts, consented WhatsApp delivery and audit logs. The static prototype does not provide these controls.

The supplied anniversary logo is used unchanged. The proposed card needs the original vector/high-resolution logo and print-vendor proofing before manufacture. The QR destination is an intended deployment address; it is not proof of a live site.
