# UX Engineering Case Studies

Interview-ready case studies by Mirabelle Doiron about accessible implementation, design-system infrastructure, and human-owned AI workflows.

Each story follows the same decision-focused arc:

1. Problem
2. Constraints
3. API / Contract
4. Accessibility
5. Validation
6. Impact

## Case studies

- **Accessible invoice data** — A stable data contract that preserves campaign, job, and price relationships across Outlook, mobile, and assistive technology.
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

The portfolio content and project source are authored by Mirabelle Doiron. The case studies are sanitized reconstructions prepared for interview discussion from Mirabelle’s UX engineering and design-system work at Indeed and Osea.

- Company names provide professional context only.
- Examples use reconstructed content and do not contain proprietary production data.
- The invoice demo is a purpose-built reconstruction of the responsive and accessibility constraints discussed in the case study.
- The site uses hand-authored HTML and CSS with no external libraries, fonts, images, analytics, or runtime dependencies.

## Accessibility

The site uses semantic landmarks, one clear `h1` per page, labeled embedded previews, visible focus styles, reduced-motion support, responsive layouts, and native link semantics. Accessibility is presented as part of each system contract rather than a final review step.

## Authorship

Mirabelle Doiron is the sole project author and repository contributor.
