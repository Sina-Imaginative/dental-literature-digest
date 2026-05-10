# Dental Literature Digest

An AI-powered tool that converts dense PubMed dental research abstracts into structured clinical breakdowns — instantly.

## What it does

Paste any dental research abstract and get back four things:

- **Key Finding** — the single most important result
- **Clinical Relevance** — why it matters to a practicing dentist
- **Limitations** — the main weaknesses of the study
- **One-liner Takeaway** — a memorable summary for dental students

## Live Demo

Try it here: https://sina-imaginative.github.io/dental-literature-digest/

## Example Outputs

Five real PubMed abstracts analyzed across different dental topics:

| Topic | Source |
|-------|--------|
| AI in dental caries detection | PubMed |
| Periodontal disease and systemic health | PubMed |
| Fluoride and caries prevention | PubMed |
| Oral cancer early detection | PubMed |
| Dental implant success rates | PubMed |

See the `/examples` folder for full structured outputs.

## How to run locally

1. Get a free Gemini API key at [aistudio.google.com](https://aistudio.google.com)
2. Clone this repository
3. Open `index.html` in VS Code
4. Replace `paste-your-gemini-key-here` with your API key
5. Open `index.html` in your browser

## Why I built this

Dental research is published faster than clinicians can read it. This tool bridges that gap — making evidence-based dentistry more accessible to students, clinicians, and researchers by extracting only what matters clinically from any abstract in seconds.

## Tech stack

- HTML, CSS, JavaScript
- Google Gemini API (gemini-2.0-flash)
- Hosted on GitHub Pages

## Author

Built by Sina · 2026
