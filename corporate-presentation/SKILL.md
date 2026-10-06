---
name: corporate-presentation
description: Create PowerPoint decks that follow the corporate template: colors, fonts, layout, footer. Use when the user asks for a presentation, slides, or a deck for work.
---

# Corporate Presentation

Build every deck from `template.pptx` (in this folder). Never start from a blank presentation. Copy the template's slides and replace their text, so the brand frame stays identical.

## Important: the template has no real layouts
`template.pptx` contains 23 sample slides, but they are all built from plain text boxes on one empty layout. There are no placeholders, and the file's theme is the default Office theme. So the brand colors are NOT in the theme. Always set colors as exact hex values, and never use theme or accent colors.

## Slide size and font
- 16:9 widescreen, 13.333 in x 7.5 in.
- Font: Calibri (the theme font). Do not change the font family.

## Brand colors (only these)
| Role | Hex |
|---|---|
| Navy: slide titles, title-slide background | 0F4C81 |
| Cyan: accent rule under the title, highlights | 00A3E0 |
| Body text | 333333 |
| Footer text | 777777 |
| White: content-slide background, text on navy | FFFFFF |

## Frame used on every slide (positions in inches)
| Element | Position (x, y, w, h) | Style |
|---|---|---|
| Title | 0.6, 0.6, 11.0, 0.6 | 24 pt bold, navy, left aligned, vertically centered, no bullet |
| Accent rule | 0.6, 1.3, 12.0, 0.08 | Rectangle, fill and 1 pt line both 00A3E0 |
| Body | 0.8, 1.7, 11.5, 3.0 | 18 pt, 333333, no bullets, vertically centered |
| Footer | 0.5, 6.8, 4.0, 0.3 | 9 pt, 777777 |

- Content slides: white background (FFFFFF).
- Title slide (the first slide): navy background 0F4C81, title in white, subtitle in white 18 pt in the body position. Same accent rule and footer position. The subtitle line follows the pattern `Business Unit | Programme | Client Name`; fill in each part.
- Keep titles to one line (about 60 characters). Do not move or resize the title, rule, or footer.
- When content needs more room than the body box, you may extend the body area down to y = 6.5 in (never into the footer) and across x = 0.8 to 12.3 in.
- The template has no logo, images, slide numbers, or speaker notes. Do not add them unless the user asks.

## Standard storyline (from the template)
Use only the slides that fit the user's topic, in this order. Titles below are the template's own.

| # | Slide title | Typical content |
|---|---|---|
| 1 | Corporate Presentation Template (replace with the deck title) | Title slide |
| 2 | Presentation Objectives | Align on objectives, review current state, discuss recommendations, agree next steps |
| 3 | Agenda | Numbered list of sections |
| 4 | Executive Summary | Challenge, recommendation, benefits, decision required |
| 5 | Current State Assessment | What is working and pain points |
| 6 | Key Findings | Findings 1 to 4 |
| 7 | Strategic Drivers | Efficiency, growth, security, innovation |
| 8 | Current Challenges | People, process, technology, governance |
| 9 | Target Future State | Current state, transformation, future state |
| 10 | Recommended Solution | Technology, people, process, governance |
| 11 | Solution Architecture | Flow from users to data |
| 12 | Expected Benefits | Productivity, collaboration, security, user experience |
| 13 | Business Use Cases | By function (HR, Sales, IT, Finance) |
| 14 | Current Maturity | Level 1 to Level 5 |
| 15 | Transformation Roadmap | Assess, design, pilot, deploy, optimise |
| 16 | Implementation Timeline | Discovery, design, pilot, rollout |
| 17 | Risks and Mitigations | Risk register |
| 18 | Governance Model | Sponsor, steering committee, team |
| 19 | Success Measures | Adoption, satisfaction, productivity, ROI |
| 20 | Investment Overview | Licensing, implementation, change |
| 21 | Next Steps | Confirm scope, approve proposal, launch |
| 22 | Questions & Discussion | Closing questions |
| 23 | Thank You | Presenter name and role |

The template slides hold only short text. When a slide needs richer content, build it inside the frame above using the components below.

## Components (extensions, built only from brand colors)
These are not in the template. They exist so richer slides still look on-brand.
- Tables: header row navy 0F4C81 with white bold text; body rows white with 333333 text, 14 pt or larger; thin gray borders.
- Process steps and cards: rectangles filled navy with white text, or white with a cyan 00A3E0 outline; arrows and connectors in cyan.
- Charts: use native charts. Series colors in this order: navy, cyan, gray 777777, then lighter tints of navy and cyan. Add data labels and a short title.
- Keep text at 14 pt or larger. One main message per slide, at most 5 bullets.

## Rules
- Never invent numbers, names, dates, or client details. Use a clear placeholder such as [Client name] and tell the user.
- Presenter details on the closing slide: use what the user provides. If none is given, leave [Presenter name, role] as a placeholder. Never reuse names found in the template file.
- Footer: keep the template's footer text unless the user gives different wording (for example a company name or confidentiality notice).
- Replace all sample text. No leftover "Corporate Template", "Business Unit", or "Finding 1" wording unless it is intentional.

## Before delivering
1. Render the slides as images and check every one: no text overflowing its box, no overlaps, nothing in the footer area.
2. Confirm every color is one of the brand hex values above (or a tint for charts and tables).
3. Tell the user which placeholders still need their input.
