---
name: hormozi-books
description: Reference library for Alex Hormozi's sales and business books ($100M Offers, $100M Leads, $100M Money Models) stored as PDFs. Extracts key frameworks for sales scripts, outreach scripts, and sales strategy.
category: sales
---

# Hormozi Books — Reference Library

## Location
- VPS (original): `/root/agency/hormozi-books/`
- Local (after migration): `~/your-repo/hormozi-books/` (i.e. `/home/username/your-repo/hormozi-books/`)
- Indus Brain breakdowns: `~/your-repo/indus-brain/books/` (chapter-level notes + synthesis)

## Available Books
| File | Book | Size |
|------|------|------|
| `100M_Leads.pdf` | $100M Leads | 20 MB |
| `100M_Money_Models.pdf` | $100M Money Models | 3.5 MB |
| `100M_Offers.pdf` | $100M Offers | 3.7 MB |

Total: ~28 MB. All three books confirmed present after VPS migration (2026-06-17).

Additionally, `indus-brain/books/` contains chapter-level breakdowns and synthesis notes for all three books.

## How to Read a PDF
PyMuPDF is installed. Use `execute_code` (not terminal) to extract text:
```python
import fitz
doc = fitz.open("/root/agency/hormozi-books/100M_Offers.pdf")
for i in range(doc.page_count):
 text = doc[i].get_text()
doc.close()
```

## When to Load This Skill
- User mentions Hormozi, $100M Offers/Leads/Money Models
- User wants to improve the sales scripts (`your sales workflow`)
- User asks for sales tactics, closing techniques, pricing strategy
- Need to validate or extract specific Hormozi frameworks

## Key Frameworks to Extract & Use
See `references/key-frameworks.md` for the extracted TOC and chapter summaries.

## How to Apply to Closer Prompts
1. Read the relevant PDF chapter
2. Extract the specific tactic/framework
3. Update `your sales workflow`'s `SYSTEM_PROMPT` to include the tactic with concrete language
4. Add matching rules that trigger the tactic based on lead's message patterns
