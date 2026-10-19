# SetBud prototype

Clickable concept prototype of **SetBud**, an in-app AI support assistant that diagnoses and fixes common setup problems for non-technical WhatsApp Business users, and hands over to a human with full context when it can't.

Built for the Cheerio Product Intern assignment (Assignment A). All data is sample data; this is not a Cheerio product.

## Scenarios
- **B: Campaign not delivered** (main flow): proactive alert, diagnosis from Meta error codes, user-chosen fixes, confirm before acting, "Was this solved?"
- **B edge: number limited by Meta**: explains, makes no promises, hands over to a person
- **A: Template rejected** (user asks): suggested questions or free text, rejection reason in plain words, before/after rewrite, resubmit; billing edge case where a refund goes to a human
- **D: Contact upload failed**: one-click fix with preview, opt-in check before import
- **F: Agent hand-off view**: summary, account state, what SetBud did and didn't do, draft reply

Single static `index.html`, no build step.

Live demo: https://setbud-prototype.vercel.app/
