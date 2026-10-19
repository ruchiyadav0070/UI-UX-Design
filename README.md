LeadZam UI/UX Redesign — Frontend Prototype
Project: LeadZam Lead Management Dashboard
Prepared by: Ruchi Yadav
Purpose: UI/UX & Frontend Intern Assignment
Overview
This project presents a proposed redesign of a lead-management workflow for a CRM-style dashboard. The goal is to make lead discovery, status tracking, and common actions easier to understand and use.

The prototype is a concept built with sample data. The audit observations are hypotheses to verify against the live LeadZam product; they should not be treated as confirmed defects without checking the current experience.
UX Goals
- Make key lead metrics easy to scan.
- Help users search, filter, and review leads efficiently.
- Make lead status and recent activity more visible.
- Provide a clear add-lead flow with form validation.
- Support responsive layouts for smaller screens.
Main Screens and Interactions
- Leads dashboard: KPI cards, lead table, search, filters, and status tabs.
- Add lead modal: Input fields, basic validation, Save and Cancel actions.
- Lead details drawer: Contact details, activity timeline, and status update.
- Export action: Demonstrates a CSV export workflow using sample records.
- Responsive layout: Adapts the dashboard for narrower screens.
Tech Stack
- React
- TypeScript
- Vite
- CSS
Run Locally
Requirements
- Node.js (current LTS recommended)
- npm
Setup
npm install
npm run dev
Open the local URL printed by Vite in your terminal.
Production Build
npm run build
Project Structure
LeadZam-UX-Assignment/
├── src/                 # React application and UI components
├── docs/
│   ├── UX-AUDIT.md      # UX audit findings and recommendations
│   ├── FIGMA-SPEC.md    # Design guidance for recreating screens in Figma
│   └── DEMO-SCRIPT.md   # Suggested 3–5 minute walkthrough
├── index.html
├── package.json
└── README.md
The exact structure may vary slightly depending on the final repository version.
UX Audit Summary
The audit is organized around usability areas such as navigation clarity, lead discovery, status visibility, and form feedback. Each finding should include:
1. The user goal
2. The observed issue (with screenshot/reference)
3. Potential business impact
4. Recommended improvement
5. Priority
Important: Verify each observation against the live website/app and add your own screenshots before submitting. Do not present an unverified hypothesis as a confirmed issue.
Design Link
- Canva design concept: https://canva.link/s1ncmuqpkvb6i6e
- Figma file: Add your actual Figma file link here if you recreate/import the concept in Figma.
The Canva link is a design concept, not a Figma link. If the assignment explicitly requires Figma, submit a real Figma file link.
Demo Walkthrough
Record a 3–5 minute video showing:
1. The design direction and the main UX problem you chose.
2. The dashboard and key information hierarchy.
3. Search/filter interaction.
4. Adding a lead and validation feedback.
5. Opening a lead, reviewing activity, and updating status.
6. Responsive behavior and known limitations.
Add your demo video link to the submission email or repository once recorded.
AI Usage Notes
AI assistance was used to help draft the initial UX direction, structure the README, and accelerate the prototype/design concept. Review and validate all outputs before submission.

Before submitting, be transparent about:
- Which parts were AI-assisted
- Which decisions and changes you made yourself
- What you tested manually
- Any limitations or incomplete functionality
Assumptions and Limitations
- All lead names, companies, metrics, and activity are fictional sample data.
- The prototype is not connected to a production backend or real LeadZam account.
- Authentication, permissions, persistence, and live integrations are not implemented unless explicitly added in the code.
- Audit findings require verification against the current live product.
- The Canva concept does not replace a required Figma file.
Submission Checklist
- [ ] Verify audit observations and add screenshots/references.
- [ ] Add the actual Figma link, if required.
- [ ] Push the code to a GitHub repository.
- [ ] Run npm install and npm run build locally.
- [ ] Record and link a 3–5 minute demo video.
- [ ] Review AI Usage Notes and assumptions.
- [ ] Email the PDF audit, design link, GitHub link, README/repo, and demo video to the recruiter.
