# Roadmap-to-Demo Coverage

This demo follows the user's original Rochtetak roadmap and distinguishes interactive demo flows from future integrations.

| Product area | What can be demonstrated now | Boundary |
|---|---|---|
| Ecosystem landing | Vision, product positioning, role entry points | Marketing site only |
| Doctor / clinic | Overview, appointments, patient directory, prescription draft, profile, messages, analytics | Session-only demo state |
| Patient | Doctor discovery, booking, health timeline, family profiles, pharmacy and lab entry points | Fictional records |
| Secretary | Front-desk queue and appointment coordination | No staff authentication |
| Pharmacy | Prescription intake and order status updates | No real inventory or fulfillment |
| Labs & radiology | Request scheduling and result status workflow | No diagnostic system or real result files |
| Hospital / enterprise | Department, staff, service and OR overview | Illustrative data, not HIS |
| Insurance | Claim review and approve/reject interaction | Mock claims only |
| Marketplace | Sample catalog, cart and mock checkout | No supplier or payment connection |
| Payments | Starter / Pro / Enterprise tiers and revenue model explanation | No billing or transaction processing |
| Content & ads | Doctor/patient feed concept, partner campaign submission, moderation | No ad serving or retargeting pixels |
| Admin | User governance concept, doctor verification queue, moderation | No identity or license verification |
| AI assistant | Platform FAQ and workflow guidance | Scripted responses; no live model |
| OCR / documents | Sample extraction demonstration | No real OCR engine or file storage |
| Analytics | Operational charts and funnel illustrations | All metrics are illustrative |

## Source roadmap items not yet production-implemented
- OTP, email verification, 2FA, role-based authorization and secure identity checks
- Persistent users, appointments, messages, documents and audit logs
- Real-time chat, file storage, notifications, WhatsApp Business API
- AI APIs for support, clinician-entered note structuring, OCR and speech-to-text
- Pharmacy stock integration and smart fulfillment routing
- Lab/radiology provider integration and real result delivery
- Hospital system integration, operating room scheduling and tenant-level data isolation
- Insurance eligibility, pre-authorization and settlement
- Paymob/Fawry/Stripe or RochettakPay
- Ad pixels, retargeting, advertiser billing and data licensing
- Security, accessibility, performance, load, E2E and clinical workflow testing

## Demo acceptance checklist
- [ ] Switch through all 9 demo roles
- [ ] Change language between English and Arabic; verify RTL layout
- [ ] Create an appointment and see it in the appointment queue
- [ ] Search patient and appointment lists
- [ ] Create a prescription draft and send a mock pharmacy handoff
- [ ] Update a pharmacy order status
- [ ] Create a lab request and update its status
- [ ] Approve/reject an insurance claim
- [ ] Add a product to cart and complete mock checkout
- [ ] Submit a partner campaign and approve it in moderation
- [ ] Try AI support prompts and sample document extraction
