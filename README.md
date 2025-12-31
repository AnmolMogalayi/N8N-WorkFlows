![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&pause=1000&color=2F80ED&background=FFFFFF00&width=800&lines=Anny+%7C+N8N+Workflows;Automation+JSON+Exports)

![Workflows](https://img.shields.io/badge/Workflows-n8n-orange)
![Files](https://img.shields.io/badge/Files-4-blue)

## Project Overview

This repository contains n8n workflow exports and supporting setup guides used to automate tasks. It is a lightweight collection of JSON workflow definitions and PDFs intended to be imported into an n8n instance or reviewed as configuration artifacts.

**What's included:**
- `Crypto/` : n8n workflow(s) and a setup guide related to crypto market automation 📈
- `YT Shorts Generator/` : workflow(s) and a setup guide for generating YouTube Shorts 🎬
- `assets/` : placeholder for local assets (currently empty)

**Notes:** All workflow definitions are provided as JSON files. The PDF files are setup guides and likely document how to run or configure the workflows.

## Project Structure

```
N8N WF/
├─ assets/                      # local assets (currently empty)
├─ Crypto/
│  ├─ Crypto_Market_Agent.json  # n8n workflow (JSON export)
│  └─ BRODY'S SETUP GUIDE.pdf   # setup/installation guide (PDF)
└─ YT Shorts Generator/
   ├─ Shorts Generation.json    # n8n workflow (JSON export)
   └─ Brodyautomates Setup Guide.pdf # setup/installation guide (PDF)
```

## How It Works

- The `.json` files are exported workflow definitions (commonly from n8n). Import these files into an n8n instance to recreate the flows.
- The PDFs contain setup instructions, credentials guidance, or environment notes required to run these workflows — consult them before importing or executing.
- Typical import flow:
  1. Open your n8n instance (cloud or local).
 2. Go to the Workflow view and choose "Import".
 3. Upload the corresponding `.json` file (e.g., `Crypto_Market_Agent.json`).
 4. Review credentials and environment variables referenced by the workflow and configure them in your n8n settings.

## Usage Tips

- Keep credentials out of the JSON exports; prefer n8n's credential management.
- Review the PDF setup guides before running any workflow.
- Version-control the JSON exports when you update flows so you can track changes over time.

## Files of Interest

- `Crypto/Crypto_Market_Agent.json` — crypto market automation workflow (inspect before use).
- `YT Shorts Generator/Shorts Generation.json` — workflow for YouTube Shorts generation pipeline.
- PDFs — human-readable setup guides that accompany each workflow.

## Contributing

- If you have updated workflows, export the JSON and add it alongside the existing files.
- Keep PDF guides in PDF or source formats in `assets/` if you want to version documentation sources.

## License

No license file detected. Add a `LICENSE` if you intend to make this project open-source.

---

If you'd like, I can:
- add a simple `README` badge for the repo (GitHub-specific),
- create a `LICENSE` file template, or
- commit and open a PR with the new `README.md`.
