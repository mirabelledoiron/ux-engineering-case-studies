# Mirabelle Doiron — Design Technologist Case Studies

I turn product intent into accessible, production-ready systems. My work sits between design and engineering: I define clear contracts, prototype in code, translate system decisions across frameworks, and use AI to reach testable behavior earlier.

**[View the live portfolio](https://ux-engineering-case-studies.vercel.app/case-studies-index.html)**

**[Start with the accessible invoice case study](https://ux-engineering-case-studies.vercel.app/case-study-accessible-invoice.html)**

## What I bring

- **Design-to-code fluency:** I carry interaction, content, accessibility, and visual intent into implementation.
- **Systems thinking:** I turn one-off solutions into explicit APIs, reusable patterns, and durable guidance.
- **Cross-framework collaboration:** I help shared components work across Web Components, React, and Angular environments.
- **Accessibility as architecture:** I define semantics, reading order, keyboard behavior, focus, and states before release.
- **AI-native delivery:** I use AI to accelerate exploration and scaffolding while retaining human review and accountability.

## Featured case studies

### 1. [Accessible invoice data, from Outlook to mobile](https://ux-engineering-case-studies.vercel.app/case-study-accessible-invoice.html)

I helped turn a brittle invoice pattern into a reusable contract across Outlook, mobile, and assistive technology.

- **Problem:** Mobile stacking broke the relationship between campaign, job, and price.
- **My role:** Accessibility guidance and responsive implementation. A product designer owned the visual design.
- **Technical focus:** Semantic relationships, Outlook-safe markup, responsive duplication, and cross-framework reuse.
- **Evidence:** React and Angular product teams consumed the shared Web Component.
- **Takeaway:** I translated client constraints into a component contract teams could reuse with confidence.

### 2. [Documentation as design-system infrastructure](https://ux-engineering-case-studies.vercel.app/case-study-design-system-docs.html)

I treated documentation as a product surface—not an archive. The content model connected intent, behavior, component APIs, tokens, accessibility, tests, and governance.

- **Problem:** Critical knowledge lived across people, code, and private conversations.
- **Approach:** Give every component the same decision-oriented contract.
- **AI-native value:** Structured guidance gives people and AI tools a safer source of truth.
- **Takeaway:** I made system decisions portable across teams, tools, and time.

### 3. [AI speed with human product ownership](https://ux-engineering-case-studies.vercel.app/case-study-ai-workflow.html)

I use AI to move from design intent to working software earlier, then apply explicit UX, accessibility, system, and risk gates before production.

- **AI accelerates:** Exploration, scaffolding, repetitive implementation, documentation, and test ideas.
- **I remain accountable for:** User needs, component contracts, semantics, states, failure behavior, and maintainability.
- **Takeaway:** AI changes delivery speed; it does not remove human responsibility for the shipped experience.

## My AI-assisted workflow

1. **Frame the contract** — Define the user need, constraints, acceptance criteria, component API, tokens, and required states.
2. **Generate working evidence** — Use AI to explore alternatives and reach an interactive draft quickly.
3. **Review the experience** — Check hierarchy, content, responsive behavior, semantics, keyboard support, and focus.
4. **Validate risk** — Test loading, empty, error, permission, and recovery paths with realistic content.
5. **Refine for production** — Refactor, test, document, observe, and remain accountable for the result.

I treat AI output as a proposal. A visual match is not approval, and a generated implementation is not complete until its behavior is understood and validated.

## Technical focus

- Semantic HTML and accessible interaction contracts
- Responsive CSS and token-driven design systems
- Web Components with React and Angular consumers
- Component APIs, state models, documentation, and governance
- Outlook and constrained email rendering
- AI-assisted prototyping with human quality gates

## Repository scope

This repository is a sanitized HTML/CSS reconstruction for interview discussion. It demonstrates the responsive email behavior and accessibility contract; it does not contain proprietary production code or customer data.

The original production Web Component, React and Angular adapters, and TypeScript validation script are not included. I do not recreate or imply their exact APIs or validation assertions here. The invoice case study identifies what is represented, what came from the production architecture, and what remains unavailable.

## Run locally

Prerequisite: Python 3. No package installation or build step is required.

```bash
python3 -m http.server 4173
```

Open [http://localhost:4173](http://localhost:4173).

If port 4173 is occupied, choose another port:

```bash
python3 -m http.server 4175
```

## Project map

- `case-studies-index.html` — Portfolio overview
- `case-study-accessible-invoice.html` — Responsive invoice and architecture case study
- `case-study-design-system-docs.html` — Documentation-system case study
- `case-study-ai-workflow.html` — Human-reviewed AI workflow case study
- `case-study.css` — Shared tokens, layout, responsive behavior, and focus styles
- `indeed-invoice-email.html` — Sanitized responsive invoice reconstruction
- `indeed-invoice-preview.html` — Standalone desktop and mobile preview

## Accessibility

I built the site with semantic landmarks, one clear `h1` per page, labeled embedded previews, visible focus styles, reduced-motion support, responsive layouts, and native link semantics. Each case study treats accessibility as part of the system contract rather than a final audit.

## Authorship and AI transparency

I wrote and approved the final portfolio narrative. I used AI-assisted tooling to help assemble and iterate on this sanitized reconstruction, and I reviewed every published claim. The decisions, constraints, and professional experience documented here are mine.

All repository commits are authored only by me, Mirabelle Doiron.
