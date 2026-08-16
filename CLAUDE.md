# CLAUDE.md — Contemporary Dental Clinic

Client engagement under Rumiq Technologies Ltd. This file governs the whole
repo; each subfolder's own `CLAUDE.md` takes precedence for files inside it.

## Engagement

- **Client:** Contemporary Dental Clinic (dental / health & wellness vertical)
- **Owner:** Mohammed Khan (CEO, Rumiq)
- **Goal:** full digital presence build — website, brand identity, social
  media content, and YouTube content
- **Rumiq service lines:** website and app development · AI-enabled social
  media marketing (multi-modal) · SEO/AEO · brand/creative

## Data & compliance

- **Scope is marketing-only — no patient health information (PHI/PII)
  belongs in this repo.** Nothing here should ever contain real patient
  names, records, appointment data, or images without documented consent.
- If the website workstream ever adds patient-facing functionality (e.g. an
  appointment booking form, contact intake, chat widget) that could collect
  or store real patient data, stop and flag it — that would bring HIPAA (or
  applicable state health-data law) into scope and this section needs
  updating before work continues.
- **FTC marketing-claims constraints apply to all client-facing content**
  (website copy, social posts, YouTube scripts): no unsubstantiated efficacy
  or safety claims about dental treatments/procedures, no fabricated
  testimonials or reviews, clear disclosure of any paid/affiliate
  relationships. Dental advertising may also be subject to state dental
  board rules — flag anything that reads like a clinical/medical claim so
  Mohammed can confirm with the client before it ships.
- **Use only synthetic/placeholder data** (sample patient names, stock
  photos, placeholder testimonials) in prototypes and drafts. Real client
  photos/testimonials/branding assets go in only once the client supplies
  and approves them.
- **Email and WhatsApp automation folders touch real contact data** (patient/
  customer names, emails, phone numbers) even though this is "marketing-only"
  in the PHI sense — that's still PII, and outbound messaging is subject to
  consent/opt-out law (CAN-SPAM and TCPA in the US, CASL in Canada, PECR/UK
  GDPR in the UK, PDPL in the UAE — confirm which applies with Mohammed
  based on the clinic's actual audience before any send goes live). Use
  synthetic contact lists in prototypes; never real patient contact info.
- **Analytics folder may involve tracking/cookies** on the client's website —
  flag consent-banner and data-retention questions to Mohammed rather than
  assuming a regime; don't wire up real tracking without confirming what's
  allowed for this client's jurisdiction(s).
- **LinkedIn profile management is for a named individual (Dr. Sheryar
  Khan)**, not the clinic brand — treat his professional bio/content as
  personal data he must approve directly, separate from clinic-brand
  approval.

## Subfolders

| Folder | Scope |
| --- | --- |
| `Contemporary_Dental_ Website` | Website build |
| `Contemporary_Dental_Brand_Guidlines` | Brand identity: logo, colors, type, voice |
| `Contemporary_Dental_Social_Media` | Social content calendar, posts, assets |
| `Contemporary_Dental_Youtube` | YouTube scripts, thumbnails, content plan |
| `Contemporary_Dental_Analytics` | Web/marketing analytics, tracking, reporting |
| `Contemporary_Dental_Dr.Sheryar_Khan_Linkedin_Profile_Managment` | Dr. Sheryar Khan's personal LinkedIn profile/content |
| `Contemporary_Dental_Email_Marketing_Newsletter` | Email marketing campaigns, newsletter content |
| `Contemporary_Dental_WhatsApp_Automation` | WhatsApp Business messaging automation |

Stack and build/run/test commands: **[TBD]** — not yet chosen, each folder is
currently empty scaffolding. Record them here once a stack is picked.

## Approvals

No additional approval requirements beyond the workspace defaults in
`Claude Work/CLAUDE.md` — get explicit sign-off before anything publishes,
sends, or ships to the client or their audience.
