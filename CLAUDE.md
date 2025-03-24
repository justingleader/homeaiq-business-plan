# CLAUDE.md for HomeAIQ Business Plan

## Project Overview
This repository contains business planning documents for HomeAIQ, a smart home integration company focusing on using open-source platforms like Home Assistant to provide premium installation and support services.

## Commands
- No build/lint/test commands (business planning repository)
- `pandoc -f markdown -t pdf document.md -o document.pdf` to convert markdown to PDF
- `csvlint data.csv` to validate CSV data consistency
- For financial tables, use `| Column | align syntax` with `:---:` for centered data

## Document Structure
- Use hierarchical headings (# for main, ## for sections, ### for subsections)
- Include executive summaries at the beginning (3-5 bullet points)
- Maintain 4-6 sentence paragraphs for readability
- Link related documents with relative paths `[text](./folder/document.md)`

## Content Guidelines
- Express financial figures consistently ($XXM or $XX,XXX)
- Market size in $B, customer counts in K, growth as XX% CAGR
- Reference competitors with [YYYY] citation format
- Use SWOT tables for strategic analysis
- Structure market segments consistently across all documents

## File Organization
- Use kebab-case for filenames (e.g., `market-analysis.md`)
- Group related documents in descriptive folders
- Include revision numbers in filenames when iterating
- Store reference materials in `/referencematerial`

## Data Visualization
- Use CSV format for data files
- For complex relationships, use Mermaid diagrams: ```mermaid
- Include graphical projection summaries with labeled axes