# virtualmase / MASE Maintenance Runbook

**Operational owner:** Mason Nguyen  
**Deployment source:** GitHub repository `virtualmase/virtualmase`, branch `main`  
**Production surface:** `https://virtualmase.vercel.app/`  
**Current public routes:** `/`, `/mase.html`, `/robots.txt`, `/sitemap.xml`

## Maintenance objective

Keep the public system accurate, reachable, understandable, and proportionate to the evidence available. The site is intentionally static and does not collect lead data, handle deal files, run agents, or retain visitor inputs. Any proposal to add those capabilities requires a new security, privacy, and operating-boundary review.

## Release checklist

| Check | Standard | Owner action |
|---|---|---|
| Scope | The change belongs to virtualmase or MASE and does not collapse another property’s role. | Confirm the intended page, reader, and call to action. |
| Claims | New factual, performance, customer, availability, legal, financial, or security claims are supported and reviewable. | Remove, qualify, or document unsupported claims before publishing. |
| Contact | Phone and email links are current and intentionally public. | Test each `tel:` and `mailto:` target in source. |
| Links | Key internal and external links are live and point to the intended property. | Check homepage, MASE, GitHub, Coreweaver Labs, and AI Mastery. |
| Accessibility | Headings, labels, keyboard focus, contrast, and responsive behavior remain usable. | Perform keyboard and desktop/mobile visual review proportionate to the change. |
| Release | Git diff is clean, commit message is descriptive, and production deployment is ready. | Push to `main`, inspect deployment status, then verify public content. |
| Rollback | A safe reversal path is known before a public change. | Revert the affected commit and push the revert to `main` if necessary. |

## Operating cadence

| Cadence | Action | Output |
|---|---|---|
| Before every public update | Run the release checklist. | Commit message and validation evidence. |
| Monthly | Check main routes, contact links, key outbound links, sitemap, and any factual drift in offer language. | Short maintenance note or issue list. |
| Quarterly | Review MASE’s buyer language, scope boundary, public proof, and content relevance against actual conversations. | Decision: retain, revise, expand, or retire a message/offer. |
| On incident | Triage security, availability, public accuracy, and user impact. Contain first; document second. | Incident/decision record and rollback if needed. |

## Triage rules

Prioritize issues in this order: exposed credentials or sensitive data; broken production availability; inaccurate or harmful public claims; contact failures; critical navigation or accessibility defects; then visual or editorial refinement. Do not erase evidence of material public changes or incidents. Do not silently archive or delete a property, domain, or public record without explicit owner approval.

## Scope escalation

The static site is not a place to receive deal documents or material nonpublic information. Before enabling a contact form, calendar booking tool, CRM, analytics platform, login, AI chat, workflow upload, or third-party integration, document the data classification, vendor role, retention, authorization model, failure path, and owner approval. For MASE work, establish the client-approved environment before receiving any sensitive information.

## Rollback procedure

1. Identify the release commit associated with the issue.
2. Create a reversal commit with `git revert <commit>`; do not rewrite published history.
3. Push the reversal to `main` and confirm the production deployment is ready.
4. Verify the restored public route and record the reason for rollback.
5. Open a follow-up task only after the source of the issue is understood.

## Current known limitations

- No first-party analytics or conversion event tracking is present; early learning depends on direct conversations and self-reported referral paths.
- No contact form is present by design, so no visitor data is collected through the site.
- The MASE route is a commercial prototype, not a completed product platform or autonomous agent.
- Mobile visual review should be repeated for material visual changes before paid promotion or a significant outreach campaign.
