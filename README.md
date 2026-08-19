# UX Engineering Case Studies

Interview-ready case studies by Mirabelle Doiron about accessible implementation, design-system infrastructure, and human-owned AI workflows.

**View live case studies:** [ux-engineering-case-studies.vercel.app](https://ux-engineering-case-studies.vercel.app/case-studies-index.html)

Each story follows the same decision-focused arc:

1. Problem
2. Constraints
3. API / Contract
4. Accessibility
5. Validation
6. Impact

## Case studies

- **[Accessible invoice data](https://ux-engineering-case-studies.vercel.app/case-study-accessible-invoice.html)** — A stable data contract that preserves campaign, job, and price relationships across Outlook, mobile, and assistive technology.
- **Documentation as infrastructure** — A shared component contract connecting usage, behavior, API, tokens, accessibility, tests, and governance.
- **AI speed with human ownership** — A risk-based workflow that uses AI to reach testable software earlier without lowering the production quality bar.

## Run locally

Prerequisite: Python 3.

```bash
python3 -m http.server 4173
```

Then open [http://localhost:4173](http://localhost:4173).

No build step, package installation, framework, or external asset host is required.

## Project structure

- `index.html` — Repository entry point; redirects to the portfolio index.
- `case-studies-index.html` — Portfolio overview.
- `case-study-accessible-invoice.html` — Responsive invoice case study.
- `case-study-design-system-docs.html` — Design-system documentation case study.
- `case-study-ai-workflow.html` — Human-reviewed AI workflow case study.
- `case-study.css` — Shared tokens, layout, responsive behavior, and focus styles.
- `indeed-invoice-email.html` — Sanitized responsive invoice reconstruction embedded in the case study.
- `indeed-invoice-preview.html` — Standalone desktop and mobile invoice preview.

## Sources and provenance

This sanitized reconstruction was assembled by Mirabelle using AI-assisted tooling. The underlying decisions and experience reflect her previous design-system work.

- Company names provide professional context only.
- Examples use reconstructed content and do not contain proprietary production data.
- The invoice demo is a purpose-built reconstruction of the responsive and accessibility constraints discussed in the case study.
- The site uses hand-authored HTML and CSS with no external libraries, fonts, images, analytics, or runtime dependencies.

## Technical architecture and repository scope

The original production architecture used a shared Web Component consumed by React and Angular product teams. The production Web Component, framework adapters, and TypeScript validation script are not included in this repository, so their exact APIs and validation assertions are not recreated or implied here.

This repository contains only the sanitized HTML/CSS reconstruction of the responsive email and accessibility contract. The invoice case study distinguishes that reconstruction from the original production architecture and calls out the implementation details that remain unavailable.

## Accessibility

The site uses semantic landmarks, one clear `h1` per page, labeled embedded previews, visible focus styles, reduced-motion support, responsive layouts, and native link semantics. Accessibility is presented as part of each system contract rather than a final review step.

## Authorship and tooling

This reconstruction was assembled by Mirabelle with AI-assisted coding support. Repository commits are attributed only to Mirabelle Doiron.
