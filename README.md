# Tap & Connect V3 — amended MVP

This version uses **Tal Singh** as the customer-facing name.

Workflow:
1. Customer pitch
2. Build order with dropdowns/autofill
3. Generate editable order confirmation request
4. Customer uses a one-click mail link to prepare a confirmation reply accepting the order details and referenced terms
5. Tal records the customer's confirmation
6. Payment is taken manually by bank transfer/cash/card
7. Tal personally verifies the payment
8. V3 generates an editable payment confirmation or paid-in-full receipt with the estimated turnaround

Changes in this build:
- "SLA" renamed to **Estimated turnaround**
- Terms version/reference is recorded with each order
- Customer confirmation text explicitly references the terms supplied
- Part-payment and paid-in-full receipts are distinct
- Order history records confirmations and verified payments
- Customer-facing alias/signature changed to **Tal Singh**
- PWA files included for Add to Home Screen / basic offline shell

Important:
- The current one-click confirmation is a mailto link; the customer still presses Send in their mail app.
- Customer data is stored only in that browser/device. Export a backup after real transactions.
- This MVP intentionally does not require UTR, VAT number, company number, or HMRC registration details.
