---
name: Midnight Saffron
description: A warm dark theme with saffron accents, readable contrast, and calm technical tone.
version: 1.0
portable: true
targets:
  - markdown
  - streamlit
  - claude-code
---

# Midnight Saffron Theme

A portable theme spec designed to work across:
- Markdown documentation
- Streamlit app theming
- Claude Code custom style samples

---

## 1) Theme Identity

**Theme name:** Midnight Saffron  
**Mood:** calm, intelligent, warm, modern  
**Use case:** dashboards, research tools, coding assistants, knowledge apps  

---

## 2) Design Tokens

### Core Colors
- **primary:** `#E6A93D`
- **background:** `#0F1117`
- **surface / secondary background:** `#1A1F2B`
- **text:** `#F5F7FA`
- **muted text:** `#A9B1BC`
- **border:** `#2C3443`
- **success:** `#4CAF50`
- **warning:** `#FFB020`
- **error:** `#E57373`
- **info:** `#64B5F6`

### Typography
- **font family:** sans serif
- **tone:** concise, polished, helpful
- **density:** medium
- **corner style:** slightly rounded
- **contrast:** high readability, low glare

### Spacing
- **compactness:** balanced
- **preferred rhythm:** 8px baseline feel

---

## 3) Markdown Usage Guidance

Use this visual style in Markdown documents:

- Prefer short headers and clean hierarchy
- Keep paragraphs compact
- Use code fences generously for copy/paste sections
- Avoid overly bright highlight colors
- Favor warm accent emphasis over neon tones

### Suggested Markdown conventions
- `#` for page title
- `##` for major sections
- `###` for implementation details
- Inline code for tokens, paths, commands, and variables

---

## 4) Streamlit Theme Config

Save this as:

`.streamlit/config.toml`

```toml
[theme]
primaryColor = "#E6A93D"
backgroundColor = "#0F1117"
secondaryBackgroundColor = "#1A1F2B"
textColor = "#F5F7FA"
font = "sans serif"
base = "dark"