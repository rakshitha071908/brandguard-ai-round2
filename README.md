# BrandGuard AI - Team NEXORA

No-sign-in browser demo of the Nexora pre-publication review concept.

## Run
Open index.html in a modern browser. No build step, API key, account or server is required. Draft text and decision history are stored locally in the browser.

## Workflow and features
- Paste copy or upload a .txt/.md draft; edit title and content type.
- Get live word and character counts and automatic local draft saving.
- See matched claims, risk, explanations and the sample brand rule.
- Copy or apply the suggested rewrite and review the updated text.
- Export a plain-text review report.
- Approve or request changes; the decision persists in the browser review queue.
- Review the sample claims, voice and human-approval guidelines.

## Technology and scope
Vanilla HTML, CSS and JavaScript. The checks are deterministic phrase and pattern rules, not a generative AI model and do not verify claims against external evidence. Drafts and queue history stay in local browser storage. PDFs, presentations and images are not parsed in this demo.

## Round 1 continuity and Round 3
The Round 1 proposal remains the brief. This build delivers a complete first text-review journey. Future improvements: (1) evidence verification against approved facts with citations and stale-source warnings; (2) PDF, presentation and image analysis with located brand/accessibility findings; (3) authenticated roles, risk-based approvals, comments, versions and persistent audit history.
