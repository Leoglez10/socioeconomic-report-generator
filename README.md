# Socioeconomic Report Generator

> **Case study.** The source code is private (client project). This repository documents what the product does and the results it delivered.

A web platform built for an HR company that turns the intake of socioeconomic studies into branded, ready-to-deliver PDF reports.

## The problem

Each socioeconomic study was assembled by hand: collecting personal, family, academic and employment data, formatting it into a report, inserting photos and attaching supporting documents. The process was slow, error-prone and produced inconsistent results across clients.

## What it does

- **Guided intake form** with dynamic sections to register multiple entries (family members, jobs, education) without friction.
- **AI data extraction** to pre-fill fields from source documents.
- **Voice dictation** to capture information hands-free.
- **Automatic PDF generation** with a consistent corporate layout, headers, branding and watermark.
- **Photo integration** of the candidate and their home inside the final report.
- **PDF merging** of supporting documents into a single deliverable file.
- **Word or PDF export** for psychometric reports.
- **In-app release notes** that show users what changed since their last visit.

## Impact

- **80%+ faster** per client compared with the manual process.
- **10–30 clients per week** processed through the platform.
- Uniform, traceable reports with fewer capture errors.

## Tech stack

| Layer | Technologies |
| --- | --- |
| Frontend | React · Vite · Tailwind CSS |
| Backend | Node.js · Express · Firebase |
| AI | Gemini |
| Reports | EJS · Puppeteer · pdf-lib |
| Deployment | Docker |

## Author

Built by [Leoglez10](https://github.com/Leoglez10) as an independent full-stack developer.
