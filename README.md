# Taipei City Urban Renewal Review Auditor v2026 - document review web app 2026

> **Web app for reviewing Taipei City urban renewal documents: upload PDFs, run rule-based checks, and generate review reports in version 2026.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/leo-baker2003/document-review-auditor-taipei-city?style=flat-square)](https://github.com/leo-baker2003/document-review-auditor-taipei-city)

---

<p align="center">
  <a href="https://leo-baker2003.github.io/document-review-auditor-taipei-city/">
    <img src="https://img.shields.io/badge/Download-Taipei%20City%20Urban%20Renewal%20Review%20Auditor%20Latest-brightgreen?style=for-the-badge" alt="Download Taipei City Urban Renewal Review Auditor">
  </a>
</p>

> **[Direct Download - Taipei City Urban Renewal Review Auditor v2026](https://leo-baker2003.github.io/document-review-auditor-taipei-city/)**

---

[Download Latest Build](https://leo-baker2003.github.io/document-review-auditor-taipei-city/)

---

## Overview

Taipei City Urban Renewal Review Auditor is a browser-based application created for reviewing urban renewal project documents and rights transformation plans. It centers on PDF inspection and a rule-driven workflow, so reviewers can move from file upload to findings without having to sort everything by hand.

Built for Taipei City urban renewal review use cases, the tool calls out missing materials, form defects, calculation problems, and policy limit checks. It also produces HTML review reports that can be printed or saved as PDF, which makes sharing results and archiving each review pass straightforward.

---

## What it does

- Automates review of urban renewal project documents and rights transformation plans
- Handles PDF uploads through a review-oriented inspection flow
- Applies rule-based compliance checks with structured logic
- Flags missing documents and common form defects
- Performs calculation checks and policy limit validation for review items
- Generates HTML reports for findings and review results
- Supports printing or PDF export for offline retention
- Runs in a web interface that can be accessed from a browser

---

## Installation

Clone or download the repository, then open the project in your preferred environment.

1. Clone the repo:
   `git clone https://github.com/leo-baker2003/document-review-auditor-taipei-city.git
2. Enter the project folder:
   `cd webapp-city-reframe-audition`
3. Start the web app according to your local FastAPI setup or deployment method.

If you are using a prepared build, download it from the project page and launch the web interface from your hosting environment.

---

## How to use it

1. Open the web app in a browser.
2. Upload the PDF documents you want to review.
3. Run the review workflow to evaluate the files against the configured rules.
4. Inspect the output for missing items, form issues, and calculation or policy limit checks.
5. Review the generated HTML report and print or save it as PDF if needed.

Typical workflow:

- Prepare the urban renewal materials
- Upload the relevant PDFs
- Run automated inspection
- Review the findings
- Export or print the report

---

## Configuration

Review rules and workflow settings are handled in the application layer, with FastAPI and the rules engine supporting the review process. If your deployment includes local settings, keep configuration near the server startup or environment setup used for the app.

Example environment-style settings:

    APP_ENV=production
    REVIEW_MODE=urban_renewal
    REPORT_FORMAT=html
    ENABLE_PDF_EXPORT=true

Adjust values to match your deployment and review process.

---

## Requirements

- Web browser for accessing the interface
- A server environment compatible with FastAPI
- PDF files for document inspection
- Storage space for uploaded files and generated reports
- Runtime support for HTML report output and optional PDF export

---

## FAQ

**How do I change the review rules?**  
Modify the rules engine or related configuration used by the FastAPI application, then redeploy or reload the app as needed.

**Which file types can I use?**  
The workflow is focused on PDF upload and inspection.

**Can the report be saved?**  
Yes. Reports can be created as HTML and printed or saved as PDF.

**Where should I look if something breaks?**  
Check the upload path, browser console, server logs, and any rule configuration tied to the review flow.

**Who is it intended for?**  
It is meant for Taipei City urban renewal document review scenarios, especially when structured checks are needed for project materials.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
