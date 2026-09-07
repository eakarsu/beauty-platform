# Feature status — Salon, spa & beauty operations

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 164 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 5 | 0 | Native records/view |
| Work items & projects | records | 0 | 0 | Native records/view |
| Contacts & parties | records | 0 | 0 | Native records/view |
| Tasks | records | 1 | 0 | Native records/view |
| Calendar | records | 4 | 0 | Native records/view |
| Deadlines & reminders | records | 1 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 1 | 0 | Native records/view |
| Time tracking | records | 1 | 0 | Native records/view |
| Messages & communications | records | 2 | 0 | Native records/view |
| Reports & analytics | report | 4 | 0 | Native records/view |
| Activity & audit trail | audit | 0 | 0 | Native records/view |
| Provider connections | integration | 1 | 0 | Provider request records only |
| AI Stylist Matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Service Duration Prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Product Recommendation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rebooking Automation | records | 1 | 0 | Native records/view |
| Waitlist Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Stylists | records | 1 | 0 | Native records/view |
| Services | records | 4 | 0 | Native records/view |
| Bookings | records | 1 | 0 | Native records/view |
| Products | records | 2 | 0 | Native records/view |
| Waitlist | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Schedules | records | 1 | 0 | Native records/view |
| Reviews | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Promotions | records | 1 | 0 | Native records/view |
| Inventory | records | 4 | 0 | AI question-and-answer workspace; records available as context |
| Loyalty | records | 4 | 0 | Native records/view |
| Giftcards | records | 1 | 0 | Native records/view |
| Expenses | records | 1 | 0 | Native records/view |
| Performance | records | 1 | 0 | Native records/view |
| Tips | records | 2 | 0 | Native records/view |
| Checkin | records | 1 | 0 | Native records/view |
| Memberships | records | 2 | 0 | Native records/view |
| Suppliers | records | 1 | 0 | Native records/view |
| Payroll | records | 1 | 0 | Native records/view |
| Booking calendar | records | 1 | 0 | Native records/view |
| Commissions | records | 3 | 0 | Native records/view |
| Rebook queue | records | 1 | 0 | Native records/view |
| Service demand forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Stylist workload balance | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Appointment conflict detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Commission optimization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Retail recommend | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| smart service bundling | records | 1 | 0 | Native records/view |
| stylist skill tagging matching | records | 1 | 0 | Native records/view |
| dynamic service pricing | records | 1 | 0 | Native records/view |
| client lifetime value scoring | records | 1 | 0 | Native records/view |
| inventory management automation | records | 1 | 0 | Native records/view |
| waitlist fulfillment ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| servicedemandforecast busytime prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| stylistworkloadbalance | records | 1 | 0 | Native records/view |
| commissionoptimization | records | 1 | 0 | Native records/view |
| retailrecommend product to add to service | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| appointmentconflictdetection | records | 1 | 0 | Native records/view |
| noshow prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| public online booking widget api | records | 1 | 0 | Native records/view |
| automated reminder smsemail communication | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| supplier reorder automation | records | 1 | 0 | Native records/view |
| staff absence coverage planning | records | 1 | 0 | Native records/view |
| payment processor integration | integration | 1 | 0 | Provider request records only |
| pos hardware integration | integration | 1 | 0 | Provider request records only |
| Flash Design Generator | integration | 1 | 0 | AI question-and-answer workspace; records available as context |
| Consent Form Customizer | records | 1 | 0 | Native records/view |
| Aftercare Personalizer | records | 1 | 0 | Native records/view |
| Social Media Caption Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Style Matcher | records | 1 | 0 | Native records/view |
| Portfolio Style Classifier | records | 1 | 0 | Native records/view |
| Demand Forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Message Drafter | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Artists | records | 1 | 0 | Native records/view |
| Appointments | records | 2 | 0 | Native records/view |
| Consent | records | 1 | 0 | Native records/view |
| Consultations | records | 1 | 0 | Native records/view |
| Sterilization | records | 1 | 0 | Native records/view |
| Walkins | records | 1 | 0 | Native records/view |
| Gifts | records | 1 | 0 | Native records/view |
| Cleaning | records | 1 | 0 | Native records/view |
| Flash | records | 1 | 0 | Native records/view |
| Aftercare | records | 1 | 0 | Native records/view |
| Healing | records | 1 | 0 | Native records/view |
| Artist performance | records | 1 | 0 | Native records/view |
| Smart booking | records | 1 | 0 | Native records/view |
| healing outcome prediction by artist style location to | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| portfolio style classification auto tagging artist work | records | 1 | 0 | Native records/view |
| demand forecasting to optimize artist scheduling for peak | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| social proof automation generating before after post sequences | records | 1 | 0 | Native records/view |
| osha bloodborne pathogen compliance dashboard with audit ready logs | records | 1 | 0 | Native records/view |
| ai driven portfolio style classification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| demand forecasting for peak hours | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| ai infection risk scoring | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| integrations with payment processing square stripe | integration | 1 | 0 | Provider request records only |
| formal health safety compliance tracking module blood borne | records | 1 | 0 | Native records/view |
| portfolio gallery storefront for public viewing | records | 1 | 0 | Native records/view |
| multi location multi studio support | records | 1 | 0 | Native records/view |
| webhooks or notifications | integration | 1 | 0 | Provider request records only |
| sms email reminder infrastructure | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Chat Assistant | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Smart Scheduling | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Client Insights | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Revenue Predictor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| No-Show Prediction | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Style Recommendations | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Voice Receptionist | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Social Media Content | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Upsell Suggestions | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Client Reactivation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sentiment Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Symptom Checker | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Mental Health Companion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Skin Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Sleep Coach | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Posture Corrector | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Product Recommender | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Loyalty Program Manager | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| 5 Ways AI is Transforming the Beauty Industry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cash drawer | records | 1 | 0 | Native records/view |
| Purchasing | records | 1 | 0 | Native records/view |
| AI Review & Knowledge | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Platform Overview | records | 1 | 0 | Native records/view |
| All Salons | records | 1 | 0 | Native records/view |
| Platform Revenue | records | 1 | 0 | Native records/view |
| Subscriptions | records | 1 | 0 | Native records/view |
| Room Turnover | records | 1 | 0 | Native records/view |
| Point of Sale | records | 1 | 0 | Native records/view |
| Staff | records | 3 | 0 | Native records/view |
| Gift Cards | records | 2 | 0 | Native records/view |
| Marketing | records | 1 | 0 | Native records/view |
| Marketplace Leads | records | 1 | 0 | Native records/view |
| Sales CRM | records | 1 | 0 | Native records/view |
| Marketplace | records | 1 | 0 | Native records/view |
| Subscription | records | 1 | 0 | Native records/view |
| My Schedule | records | 1 | 0 | Native records/view |
| My Clients | records | 1 | 0 | Native records/view |
| My Earnings | records | 1 | 0 | Native records/view |
| My Settings | records | 1 | 0 | Native records/view |
| Book Appointment | records | 1 | 0 | Native records/view |
| My Appointments | records | 1 | 0 | Native records/view |
| My Profile | records | 1 | 0 | Native records/view |
| Payment Methods | records | 1 | 0 | Native records/view |
| My Rewards | records | 1 | 0 | Native records/view |
| Blog | records | 1 | 0 | Native records/view |
| Payments | records | 2 | 0 | Native records/view |
| Booking Assistant | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Staff Match | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Service Recommendations | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Schedule Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Review Response | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reactivation Message | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Revenue Forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Waitlist Intelligence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Kiosk checkin | records | 1 | 0 | Native records/view |
| Lapsed ad spend | records | 1 | 0 | Native records/view |
| Therapist compatibility | records | 1 | 0 | Native records/view |
| Pos hardware | records | 1 | 0 | Native records/view |
| Packages | records | 1 | 0 | Native records/view |
| Campaigns | records | 1 | 0 | Native records/view |
| Retail | records | 1 | 0 | Native records/view |
| Referrals | records | 1 | 0 | Native records/view |
| Time Off | records | 1 | 0 | Native records/view |
| Gallery | records | 1 | 0 | Native records/view |
| Locations | records | 1 | 0 | Native records/view |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 164 feature pages were visited in the browser; 162 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 58 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

58 original AI entries are now grouped into **8 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).
