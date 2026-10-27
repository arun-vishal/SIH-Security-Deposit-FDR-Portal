# Streamline of Security Deposit / FDR Portal

### Smart India Hackathon (SIH) — Project demo (NOT A PROTOTYPE)

> A proposed digital platform for simplifying the submission, tracking, verification, and administration of security deposits and Fixed Deposit Receipts (FDRs).

## Problem Statement

Managing security deposits and Fixed Deposit Receipts can involve fragmented records, manual document checks, repeated follow-ups, and limited visibility into application status. A unified digital workflow could reduce administrative effort, improve traceability, and make it easier for applicants and reviewers to coordinate.

**SIH Topic:** Streamline of Security Deposit / FDR Portal  
**Project status:** Frontend prototype / work in progress

## Proposed Solution

The goal is a centralized portal where applicants can submit security-deposit or FDR-related requests, attach supporting documents, follow review progress, and receive clear status updates. Administrators would be able to examine submissions, request corrections, track relevant dates, and maintain an auditable history.

## Current Prototype Features

The included `index.html` is an existing **AUREXA** document-verification dashboard that provides a foundation for this SIH topic. It currently includes:

- Responsive, animated dashboard with interactive 3D visuals
- Browser-only applicant and administrator demo login
- Application forms with document upload UI
- Local application records and status tracking
- Configurable, rule-based metadata checks and risk scoring
- Administrator review actions, notes, and audit timeline
- HTML verification report export and print option
- Theme and visual-effect preferences
- Browser `localStorage` for demo records and settings

**Important:** The current application remains branded AUREXA and uses institution/document verification fields. It does **not** yet implement an FDR-specific submission form, actual bank/FDR validation, security-deposit ledger, maturity tracking, refund processing, or secure server-backed authentication.

## Planned FDR Portal Features

- **Security deposit register:** Record deposit amounts, purposes, parties, and transaction references.
- **FDR lifecycle:** Track issuing bank, FDR reference number, amount, issue date, maturity date, and status.
- **Document workflows:** Upload and review FDR/deposit supporting documents.
- **Review and approval:** Applicant submission, administrator verification, correction requests, and decision history.
- **Expiry and maturity reminders:** Notify authorized users about upcoming deadlines.
- **Release/refund tracking:** Manage deposit release or refund requests and approval states.
- **Search and reporting:** Filter deposits, export summaries, and maintain auditable actions.
- **Secure deployment:** Implement real authentication, server-side authorization, encrypted storage, and appropriate audit logging.

These are **proposed enhancements**, not features already available in the uploaded HTML prototype.

## Technology Stack

**Currently implemented:**

- HTML5
- CSS3
- Vanilla JavaScript
- Canvas/CSS animations and interactive 3D effects
- Browser `localStorage`

**Potential production additions (not implemented):** a backend API, database, secure identity management, file storage, notifications, and authorized verification integrations.

## Run Locally

1. Download or clone this repository.
2. Open `index.html` in a modern web browser.
3. Select **Applicant / User** or **Administrator / Reviewer** on the demo login screen.
4. Explore application submission, local verification, review, and reports.

No installation, API key, or backend is required for this frontend demo.

### Demo Access

- **Applicant:** Enter any username of at least 2 characters and any demo password of at least 4 characters.
- **Administrator:** Username `admin`, password `admin123`.

These credentials are hard-coded for demonstration. **Do not use real passwords or upload sensitive financial or personal information.** The frontend roles do not constitute secure authentication or authorization.

## Deploy with GitHub Pages

1. Open the repository's **Settings → Pages**.
2. Under **Build and deployment**, select **Deploy from a branch**.
3. Select the `main` branch and `/ (root)`, then save.
4. Once GitHub completes deployment, use the Pages URL displayed in settings.

GitHub Pages serves this as a public static demo. It does not make financial records secure or provide backend capabilities.

## Suggested Project Structure

```text
SIH-Security-Deposit-FDR-Portal/
├── index.html     # Existing AUREXA frontend prototype
└── README.md      # Project description and development roadmap
```

## Development Roadmap

- [x] Browser-based dashboard foundation
- [x] Demo applicant/admin experience
- [x] Application submission and review UI
- [x] Local status, audit, and reporting features
- [ ] Replace institution fields with security deposit and FDR data models
- [ ] Build FDR issuance, maturity, renewal, and release workflows
- [ ] Add real database and secure authentication
- [ ] Implement notifications, validation, and audit controls
- [ ] Test workflows with representative non-sensitive sample data
- [ ] Complete SIH-specific documentation and demo

## Disclaimer

This is an educational SIH prototype and is **not** a banking, government, or official deposit verification service. Any displayed verification results are browser-side demo rule outcomes. Do not rely on the prototype for financial decisions or legal document authentication.

## Contributing

Contributions are welcome. Please open an issue describing a proposed enhancement or submit a pull request with a clear explanation of the changes.

---

**Smart India Hackathon | Streamline of Security Deposit / FDR Portal**
