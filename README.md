# Hi, I'm Chris Roberts

**UiPath RPA developer and AI workflow builder in Philadelphia.**

I'm an automation accountant at Drexel University who builds bots. I've put 10+ production UiPath bots into service, running unattended so a whole finance department can use them. Together they save 5,000+ hours (~$200K) a year. The biggest, an ACH document-intake bot, saves 4,300+ hours (~$156K) a year across 20 staff accountants. I design every automation the way an accountant would: the robot or AI does the work, and code checks the numbers before anything reaches the books.

🎯 **Open to:** UiPath / RPA Developer and Agentic Automation roles.

## What I build

- **Unattended finance bots in UiPath:** journal-entry and GL posting bots that decide which transactions are ready, prepare and submit the entries, confirm they posted, prevent duplicates, and write status and errors back for staff to review.
- **Reconciliation workbook automation:** monthly bots that download source data, refresh Excel Power Query templates, keep staff notes when the data refreshes, manage support folders and hyperlinks, check the finished workbook, and publish a live copy plus dated snapshots.
- **Document automation:** bots that read bank statements and payment PDFs (OCR and PDF extraction), then split, rename, file, and post them.
- **AI document workflows:** an LLM pulls structured data out of invoices, deterministic rules check it, and anything that fails is sent to a person.
- **Tested, maintainable builds:** modular workflows, regression-test runners, global exception handlers, config-driven settings, and run logging.

## Tech stack

**Automation:** UiPath Studio · REFramework · UiPath Orchestrator · Unattended Robots · UiPath Test activities · OCR / PDF extraction · Excel & Power Query · n8n<br>
**AI:** Google Gemini · LangGraph · LLM structured extraction with JSON schemas · human-in-the-loop review<br>
**Code:** Python · JavaScript · Google Apps Script · React · Tailwind CSS · Flask · SQL (PostgreSQL / SQLite) · Git<br>
**Finance systems:** Banner Finance · BlackLine · OnBase · SAP ERP · QuickBooks · Google Workspace APIs

## Featured projects

| Project | What it does | Built with |
|---|---|---|
| [**uipath-reframework-invoice-posting**](https://github.com/Chris1112220/uipath-reframework-invoice-posting) | UiPath REFramework bot (Dispatcher + Performer) that validates vendor invoices with a 3-way match, posts balanced AP journal entries, and handles business vs. system exceptions with queue retries. Config.xlsx-driven, 9 Studio test cases, all data fictional. | UiPath Studio, REFramework, Orchestrator queues, Excel |
| [**uipath-ach-pdf-splitter**](https://github.com/Chris1112220/uipath-ach-pdf-splitter) | Unattended bot that splits combined bank ACH remittance PDFs into one file per payment (multi-page transactions kept together), names each by payer and amount, files it by fiscal period, and skips already-processed reports by SHA-256 hash. Sanitized rebuild of a production bot that saves **4,300+ hours (~$156K) a year** across 20 staff accountants; sample data is fictional. | UiPath Studio (C#), Orchestrator, PDF activities, Excel config |
| [**email-triage-agent**](https://github.com/Chris1112220/email-triage-agent) | LangGraph + Gemini agent that reads Gmail, classifies each email, and drafts a reply when one is needed. A keyword-rule fallback kicks in if the models fail, and it never sends anything without a human. Evals improved from 60% to 100% after the category definitions were tightened. FastAPI endpoint, pytest tests, and GitHub Actions CI on every push. | LangGraph, Google Gemini, Gmail API, FastAPI, pytest, GitHub Actions |
| [**invoice-extraction-n8n**](https://github.com/Chris1112220/invoice-extraction-n8n) | Accounts-payable intake for small firms. Drop a PDF invoice in Google Drive and an LLM extracts the fields, code reconciles the totals, a Google Sheet logs it, the file is renamed, and anything off is flagged *Needs Review* and emailed to a person. Fails over to backup models if one errors; passes 5/5 test invoices, including edge cases. | n8n, Google Gemini, Drive / Sheets / Gmail APIs, JavaScript, Python |
| [**ChrisDev-Portfolio**](https://github.com/Chris1112220/ChrisDev-Portfolio) | My portfolio site, with every project kept in one data file and filterable by type ([live site](https://chris-dev-portfolio-one.vercel.app)). | React, React Router, Tailwind CSS, Vercel |

## Impact (production UiPath bots)

- **5,000+ hours (~$200K)/year saved:** 10+ production UiPath bots combined
- **4,300+ hours (~$156K)/year saved:** ACH document-intake bot used by 20 staff accountants ([sanitized code](https://github.com/Chris1112220/uipath-ach-pdf-splitter))
- **72 hours/year saved:** bank-statement OCR posting bot

*My work bots run on private systems, so their code isn't public. The ACH splitter is published as a sanitized rebuild with fictional data.*

## Certifications

- **Microsoft Applied Skills:** Power Automate (October 2026)

## Education

- **Drexel University:** Graduate Certificate, Computer Science (2023–2024)
- **Temple University:** BBA, Finance (2007–2012)

## Currently learning

- **UiPath Agentic:** combining AI agents with RPA robots
- **ADP:** preparing for the UiPath Automation Developer Professional (ADPv1) certification

## Connect

🌐 [Portfolio](https://chris-dev-portfolio-one.vercel.app) · 💼 [LinkedIn](https://www.linkedin.com/in/christopher-roberts-philadelphia/) · 📧 [Christopher.roberts11220@gmail.com](mailto:Christopher.roberts11220@gmail.com)
