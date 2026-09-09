# Ekta Sharma — Portfolio Website

A lightweight, responsive portfolio website for **Ekta Sharma**, focused on AI engineering, data intelligence, applied machine learning, and software projects.

## What this site is for

The homepage is intentionally built as a recruiter-facing entry point rather than a generic personal landing page. It highlights the kinds of systems represented across the portfolio:

- autonomous and multi-agent AI workflows
- research automation and evidence-grounded analysis
- financial and business intelligence
- resume/job intelligence and career tooling
- RAG, embeddings, document processing, and LLM applications
- SQL, analytics, and applied ML
- power-market and energy data analysis

## Featured projects

The current site links directly to selected repositories including:

- **ResearchPilot** — autonomous AI research analyst with search, evidence extraction, citation verification, contradiction detection, synthesis, charts, and follow-up analysis.
- **FinAgent AI** — multi-agent financial research and analysis platform.
- **CareerIQ** — resume/job intelligence, matching, ATS-gap analysis, interview evaluation, and career copilot.
- **QueryPilot AI** — AI-assisted database and analytics workflow.
- **AI Tutor Pro** — document/YouTube ingestion, retrieval, tutoring, adaptive quizzes, study plans, flashcards, and notes.
- **Power & Energy Analytics** — projects covering power-exchange data, generator availability, portfolio management, and thermal supply analysis.

## Technology

The portfolio itself is deliberately dependency-light:

- HTML5
- CSS3
- a small inline JavaScript smooth-scroll enhancement
- Google Fonts (Inter + DM Mono)
- GitHub Pages-compatible static hosting

The projects linked from the portfolio use a broader stack including React, TypeScript, Python, Node.js/Express, Gemini, LangChain, SQL, RAG, embeddings, and data-analysis tooling.

## Run locally

No build step is required. Open `index.html` directly in a browser, or serve the directory with any static HTTP server.

For example:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish with GitHub Pages

Enable **Settings → Pages → Deploy from a branch** and select the branch containing `index.html` (normally `main`) and the root folder.

For a personal GitHub Pages domain, the repository can be renamed to:

```text
EktaSharma-github.github.io
```

GitHub Pages will then use the repository as the account's user site.

## Customization before publishing

- Replace the placeholder email address in `index.html` with the preferred public contact address.
- Add a resume link when the final resume URL is ready.
- Add project demo URLs as individual applications are deployed.
- Keep repository links current as projects evolve.

## Design direction

The visual system uses a dark technical aesthetic, restrained typography, grid background, project cards, compact metadata, and a code-style hero panel. The goal is to make the portfolio feel like an engineering product while keeping the content easy to scan.
