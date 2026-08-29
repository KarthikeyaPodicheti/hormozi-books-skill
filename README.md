# Hormozi Books — Reference Library

Reference library for Alex Hormozi's sales and business books extracted into a reusable skill/framework format.

## Books

| File | Book | Focus |
|------|------|-------|
| `100M_Offers.pdf` | $100M Offers | Offer creation, value equation, guarantees, closes |
| `100M_Money_Models.pdf` | $100M Money Models | Business models, monetization, recurring revenue |
| `100M_Leads.pdf` | $100M Leads | Lead generation, outbound, inbound, paid ads |

## Extracted Frameworks

This repo includes high-level frameworks and full chapter breakdowns for agencies and service businesses.

## Installing Coding Agents and Skills

You can use these skill folders with multiple coding agents and assistants.

### Hermes Agent
1. Copy a skill folder, e.g. `hormozi-100m-offers/`, into your Hermes skills directory:
   - Windows: `C:\Users\<you>\AppData\Local\hermes\skills\sales\`
   - macOS/Linux: `~/.hermes/skills/sales/`
2. Restart Hermes or reload skills.
3. Ask Hermes to load the skill by name, for example:
   - "Use the `hormozi-100m-offers` skill"
   - "Apply `hormozi-100m-leads` frameworks to my outreach"

### Claude
1. Copy the desired skill folder into your Claude project or shared context folder.
2. In Claude, say:
   - "Load the `hormozi-100m-offers` skill"
   - "Use `hormozi-100m-leads` to rewrite my cold outreach"
3. Claude can read the `SKILL.md` and chapter files directly as reference context.

### OpenCode / Codex CLI
1. Place the skill folders inside your agent config directory or project-local `.skills/` folder.
2. Ask the agent:
   - "Use `hormozi-100m-money-models` to sequence my offers"
   - "Reference `hormozi-100m-leads` for my lead magnet plan"
3. Some CLIs auto-discover `.skills/` folders; otherwise, paste the path or drop files into the chat as needed.

### Generic coding agent
1. Keep each skill in its own folder with a `SKILL.md` at the root.
2. Load the folder by name or path when you want the agent to use it.
3. Use chapter files for deep dives; use `cheatsheet.md` and `patterns.md` for fast decisions.

## How to Use This Repo

This repo contains public-ready skill files for any agency or service business:
- `hormozi-100m-offers/` — offer creation and pricing frameworks
- `hormozi-100m-leads/` — lead generation, outreach, and content frameworks
- `hormozi-100m-money-models/` — upsells, downsells, continuity, and payment sequencing

### Usage
1. Read `SKILL.md` in each skill folder for when to apply it.
2. Use the chapter files as quick-reference during offer building, outreach, or sales conversations.
3. Use the `patterns.md` and `cheatsheet.md` files for decision rules and thresholds.

## Files
- `README.md` — this file
- `hormozi-100m-offers/` — full $100M Offers skill with chapters
- `hormozi-100m-leads/` — full $100M Leads skill with chapters
- `hormozi-100m-money-models/` — full $100M Money Models skill with chapters

## Note
This repo does not contain the full PDFs. The source PDFs can be stored locally and read with the included `SKILL.md` instructions.

## Contributing

Pull requests are welcome. Good first contributions:
- Add a `cheatsheet.md` summary if one is missing
- Fix a typo or unclear example in a chapter
- Add a `patterns.md` decision tree for a specific business type
- Translate a chapter note into another language

Please keep changes generic and agency-friendly. Avoid adding:
- personal data or private business details
- hard-coded local file paths or credentials
- niche-specific assumptions unless clearly labeled as examples
