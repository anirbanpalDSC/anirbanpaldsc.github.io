# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is a resume document repository. The primary artifact is [raw.md](raw.md), a markdown-formatted resume for Anirban Pal — a Data Scientist / AI architect with 20+ years of experience.

## Document Structure

`raw.md` is structured as a flat markdown document with:
- **Header:** Name, contact, and a professional summary paragraph
- **Work Experience:** Reverse-chronological, each role with company, title, date range, and bullet points
- **Education & Research:** Degrees, selected publications, and professional service

## Conventions

- Bullet points use `*` and are indented with two spaces
- HTML comment tags (`<!-- end list -->`) appear as separators between bullet groups — these are artifacts and can be removed
- Escaped characters like `\<`, `\>`, `\&` appear in some inline HTML/markdown; prefer standard markdown equivalents
- Dates are formatted as `MM/DD/YYYY – MM/DD/YYYY` for roles

## UI Development

Always use [theme.md](theme.md) when building any UI. It defines the **Midnight Saffron** theme — a warm dark theme with saffron accents targeting Markdown, Streamlit, and Claude Code.

Key tokens:
- `primary`: `#E6A93D` (saffron accent)
- `background`: `#0F1117`, `surface`: `#1A1F2B`
- `text`: `#F5F7FA`, `muted`: `#A9B1BC`, `border`: `#2C3443`
- `success/warning/error/info`: `#4CAF50` / `#FFB020` / `#E57373` / `#64B5F6`

For Streamlit apps, copy the `[theme]` block from `theme.md` into `.streamlit/config.toml`.

## Content Context

- Current role: Data Scientist at Gallup, Inc (since Oct 2022)
- Key themes: Agentic AI, LLM orchestration, Transformer NLP, AWS pipelines, Power BI, predictive modeling
- Academic: PhD in CS (AI specialization) at University of Nebraska at Omaha; published in Nature Portfolio
