# virtualmase Remaster & MASE Prototype Specification

**Owner:** Mason Nguyen  
**Property:** `virtualmase.vercel.app`  
**Source:** `virtualmase/virtualmase`  
**Release class:** Reversible static-site remaster; no data collection or automated decision-making

## Decision

The current site will move from a desktop-emulation portfolio to a **clear, high-trust systems-authority site**. The remaster will preserve virtualmase’s technical identity while resolving the central conversion problem: a visitor should understand in moments who Mason is, what virtualmase builds, why the work is credible, and how to begin an appropriate conversation.

The MASE concept will be a distinct, linked prototype—**M&A AI workflow implementation with controls and human review**—rather than an unbounded autonomous-dealmaking claim.

## Existing strengths to retain

| Existing strength | How it will be retained |
|---|---|
| Founder and systems-architecture identity | Lead with a concise founder proposition and technical operating principles. |
| Multi-brand portfolio | Represent as a deliberately selected systems portfolio, not a dense registry. |
| AI Mastery principles | Surface knowledge, agents, infrastructure, observability, verification, and control as the method. |
| Technical seriousness | Retain project links, technology context, and evidence-oriented language. |
| Supplied contact details | Present linked phone and email contact paths consistently and accessibly. |

## Problems to resolve

| Problem | Remaster response |
|---|---|
| The desktop-interface motif competes with the brand message | Replace it with an editorial systems canvas: legible type, generous spacing, a subtle grid, and data-like signal markers. |
| Broad claims, many brands, and long project lists create cognitive overload | Establish a primary hierarchy: founder proposition → operating pillars → selected systems → approach → contact. |
| Service language is generic and several claims require evidence before reuse | Use modest, specific capability language and reserve performance/client claims for documented proof. |
| Contact card structure does not produce a clear commercial next step | Present a clear, low-friction inquiry action with direct contact links; do not add form collection until the intended intake/data boundary is approved. |
| No distinct route supports the MASE commercial wedge | Add a static `mase.html` prototype with a clear scope, control model, workflow examples, and inquiry path. |

## Visual direction

The remaster will use a black/ink foundation, warm-white typography, muted gray surfaces, and a restrained ultraviolet-blue accent. The style is **editorial technical—not cyberpunk, not generic SaaS, and not retro UI**. It will use a responsive grid, CSS-generated signal fields, semantic landmarks, visible focus states, and no external images or data-bearing scripts.

## Prototype hypothesis

> For legacy-minded M&A teams, a clear explanation of controlled AI workflow adoption will create more qualified conversations than a broad claim about autonomous agents or a premature software dashboard.

### Success measure

The first signal is a qualified conversation in which a practitioner identifies a specific workflow, data constraint, or adoption barrier. A page view alone is not validation.

### Boundaries

The static MASE prototype will not request deal documents, claim legal or investment competence, promise accuracy or financial outcomes, or make autonomous decisions. It will direct all substantive work to a founder-led conversation.

## Acceptance criteria

| Requirement | Acceptance check |
|---|---|
| Clear virtualmase positioning | Homepage title, lead paragraph, and primary navigation make the founder/system proposition intelligible without scrolling. |
| Clear MASE distinction | Navigation includes a dedicated MASE route with its own buyer language and explicit human-control boundaries. |
| Contact integrity | The supplied phone and four email addresses appear as working `tel:` / `mailto:` links. |
| Responsive/accessibility baseline | Semantic headings, keyboard-visible focus styles, skip link, responsive layout, and sufficient color contrast are present. |
| Reversible deployment | The work remains a static, source-controlled update; Git history provides rollback. |
| Claims discipline | No newly introduced testimonials, outcome claims, certifications, or private-client details. |

## Rollback

The deployment is linked to the GitHub `main` branch. If the remaster fails review, roll back by reverting the remaster commit and pushing the revert to `main`. The previously published contact update remains in history and can be retained independently.
