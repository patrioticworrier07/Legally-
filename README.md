# Bharat Law Guide — website prototype

## Run locally
Open `index.html` in a modern browser. No build tools or package installation are required.

## What is included
- Responsive landing page and navigation
- Searchable topic cards
- Constitution topic map for Fundamental Rights, Duties, Directive Principles and selected Parts
- BNS/BNSS/BSA vs IPC/CrPC orientation
- Bailable vs non-bailable explainer and lawyer-question checklist
- IT Act topic summaries
- Rule-based AI-helper demo with sample prompts
- Links to official Indian government legal resources

## Important limitations
This is a front-end prototype, not a complete legal database and not a live AI product. The AI helper uses a small set of hard-coded educational responses. It does not search every section, verify amendments automatically, or provide legal advice. Before public launch:
1. Connect the assistant to a secure server-side AI API (never expose API keys in browser JavaScript).
2. Ground responses in the current official statutes, amendments, commencement notifications, schedules and judgments; show citations and source dates.
3. Build a structured, searchable legal database for all Articles and sections, with versioning and transitional-law notes.
4. Have Indian legal professionals review the content, bail classification data, disclaimers and escalation flows.
5. Add privacy/security controls, rate limiting, abuse protection, monitoring and accessibility testing.
6. Check current official text and notifications before deployment. The criminal-law framework changed on 1 July 2024, subject to exceptions and transition/savings provisions.

## Sources linked in the site
- https://www.legislative.gov.in/constitutions-of-india
- https://www.indiacode.nic.in/
- https://www.mha.gov.in/en/commoncontent/judicial-division
- https://cybercrime.gov.in/
