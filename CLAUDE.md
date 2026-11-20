# CLAUDE.md: eco_service_review

## Project
Two deliverables on **the state of valuing urban ecosystem services**:
1. **Informal literature review** (`manuscript/`). Originally ~5 pages, but Andie has said it is fine for it to run longer; do not cut content to hit a length target.
2. **12-minute presentation** of that review (`presentation/`): roughly 10–12 content slides at about one minute per slide.

Andie has an outline that both deliverables follow: [`outline.md`](outline.md). **Follow it. Do not reorder, add, or drop sections without asking.**

**Order of work:** (1) lit review, (2) slides. (Andie dropped the annotated bibliography in November 2026.)

**Pace: small, iterative steps.** Build this with Andie one piece at a time (e.g., one section per round). After each step, stop and check in. Do not run ahead to later sections or deliverables.

## Conceptual framework paper (CURRENT FOCUS, started November 20, 2026)
The informal review is done. The active deliverable is now a conceptual framework paper targeted at PNAS, led by Andie with Karen Seto (Hixon Center) and Taylor Ricketts (Gund Institute, UVM) as the other primary authors. It came out of a roughly 12-person research agenda meeting.

**Files**
- `concept_frame_manuscript/draft_concept_framework.tex`: the paper. Build with `latexmk -pdf` from inside that folder.
- `concept_frame_manuscript/TODO.md`: the running to-do list and "where we left off." Read it first each session and keep it current.
- `informal_review_manuscript/main.tex`: the informal review (moved from `manuscript/`). It is the source for lifted language and the best sample of the voice Karen liked. Do not edit it; Andie has said not to worry about fixing it.
- `figures/conceptual_framework_decision_draft.tex`: standalone copy of Figure 1. The paper has its own copy of the TikZ code, so an edit to one does not carry to the other.

**Who owns what**
- Sections 1 and 2: Karen. Add to them only with Andie's approval, and add rather than rewrite.
- Sections 3 and 4: Andie. Drafted as prose (November 2026), lifted from the informal review.
- Sections 5 to 7: outline bullets only, waiting for a meeting with Taylor. Do not draft prose there yet.

**The contribution (agreed with Andie; every section should point to it)**
The framework is organized around the decision, not the ecosystem: who can change the stock of natural assets, what they are managing for, and what measured benefit would change their choice.
- Do NOT claim: that existing frameworks leave people out, that they are static, or that feedbacks are new. The Millennium Assessment, Tan et al. (2020), Keeler et al. (2019), the SETS framework (McPhearson et al. 2025), and natural capital accounting (Fenichel and Abbott 2014) all put people inside the system. The Millennium Assessment also already says costs and benefits fall on different stakeholders and that nonmarketed benefits get left out of decisions.
- What is ours: a specific decision-maker, and more than one (city, business, insurer, non-profit, homeowner), each with a budget and an objective; valuation as the link that closes the loop; naming which decision-maker sees which benefit, in a city; the counterfactual (cost of doing nothing) as part of the framework.
- Open risk Andie has named: without a solid example in Section 6, a reviewer could say this is just benefit-cost analysis, or nothing Tan et al. did not already say.

**Conventions for this paper**
- Voice: "we", not "I", but keep Andie's informal, humanistic style, including asides and exclamation points. No em dashes. The "Avoid" list below still applies.
- Terms follow Figure 1: natural asset, ecosystem function, benefits/costs (the middle tier is "function" here, not "service").
- Write "Millennium Ecosystem Assessment" on first use and "Millennium Assessment" after. Never "MA" in prose.
- Citations: nothing from memory goes into a `\cite` or the `.bib`. Check Zotero first (see the memory note on Zotero). Flag with yellow notes: `\rev{Claude}{CITATION NEEDED (Andie to verify): ...}` for unsourced claims, `\rev{Claude}{NEW FROM ZOTERO (Andie to verify): ...}` for papers new to this project, and label any candidate named from memory as UNVERIFIED. Andie wants to put her own eyes on every one.
- After each drafted or revised passage, add a `% Checked against ...` comment block with the quotes that support each claim.
- Outline bullets that have been turned into prose stay above the section as `% OUTLINE` comments.
- **Edits to this paper go one at a time.** Show the current and proposed text in chat, wait for Andie's approval, then edit. Fix plain typos directly and report them.

## Writing style (REQUIRED)
All prose you generate must sound like Andie wrote it, not like generic AI or Claude. That covers manuscript text, slide text, captions, and speaker notes. When in doubt, reread a sample before drafting:
- `/Users/ac2878/Library/CloudStorage/Dropbox-YSE/Andie Creel/Dissertation/green_space_spending/manuscript/1_intro_and_background.tex` (best sample; already reviews urban green space valuation)
- `/Users/ac2878/Library/CloudStorage/Dropbox-YSE/Andie Creel/Dissertation/atus_chapt_1/manuscript/1_intro_background.tex`
- `/Users/ac2878/Library/CloudStorage/Dropbox-YSE/Andie Creel/Dissertation/local_rec_ratio/manuscript/1_intro_background.tex`
- `/Users/ac2878/Library/CloudStorage/Dropbox-YSE/Andie Creel/virtual_fencing/manuscript_lee_creel_gilbert/main.tex` (intro and conclusion)
- `/Users/ac2878/Library/CloudStorage/Dropbox-YSE/Andie Creel/Dissertation/2_acknowledgements.tex` (the Preface: her informal, first-person voice; the closest match for an informal lit review)
- Full dissertation PDF: `/Users/ac2878/Library/CloudStorage/Dropbox-YSE/Andie Creel/Dissertation/0_creel_dissertation.pdf`

### What her writing does
- Plain, direct economist's register. First person singular for solo work ("I find", "I estimate").
- Each paragraph opens with a topic sentence that makes a specific claim, often with a citation, then adds evidence.
- Packs findings into parallel lists with a citation on each item: "Extreme heat damages physical and mental health \citep{..}, lowers welfare \citep{..}, slows economic growth \citep{..}, ..."
- Summarizes a literature as who-found-what, joined by semicolons: "consumers use delivery services to order from restaurants more during extreme heat events \citep{..}; extreme temperatures reduce retail spending in China and the United States \citep{..}; ..."
- Names gaps and contributions outright, with ordinal signposts: "First, ... Second, ... Third, ..."; "There is an extensive literature on ..."; "A separate literature has ..."; "Economists have primarily valued urban green space through ..."; "This paper fills a central gap in the ... literature identified by \citet{..}: ..."
- Mixes long sentences with short, flat ones that land the point: "These gaps are consequential." "Such effects have been observed." "The conservation externality, in contrast, never closes on its own."
- Explains economic ideas with concrete, everyday examples: "A person who cooks dinner at home forgoes the wages they could have earned as a cook"; "no one can pay another person to enjoy a beach for them."
- Reports numbers plainly, with units and context: "about 9 percent lower", "\$16--\$18 (2023 USD)", "40 °C (104 °F)". Spells out "percent" in prose; uses `\%` on slides.
- Common connectives: Therefore, However, Yet, Additionally, Furthermore, Indeed, Importantly, Finally, In sum. Recurring phrases: "The implication is that ...", "This result reveals that ...".
- Defines acronyms on first use, "(WTP)", and shorthands with "(hereafter tree cover)".
- Writes Latin abbreviations as `(\textit{e.g.,} ...)` and `(\textit{i.e.,} ...)`: italic, with a comma, inside parentheses.
- Hedges in proportion to the evidence ("suggests", "is consistent with", "likely"), and states well-supported results with confidence.
- No contractions in the manuscript.

### Avoid (these read as AI)
- Em dashes (—). Use a second sentence, commas, or parentheses. Andie occasionally uses a spaced en dash (` -- `) for an aside; keep that rare.
- Words and phrases: delve, tapestry, pivotal, crucial, multifaceted, intricate, holistic, "shed light on", "a testament to", "paves the way", "navigate the complexities", "it is worth noting", "notably", "in today's world", "ever-evolving".
- Trailing participle clauses that editorialize: ", highlighting the importance of ...", ", underscoring the need for ...".
- Punchy templates: "It's not X, it's Y"; "X isn't just Y, it's Z"; colon reveals ("The result? ..."); rhetorical questions in prose.
- Triplets of adjectives or nouns added for rhythm rather than content.
- Bullet lists or bold lead-ins inside the lit review's prose. Lists belong on slides.
- Generic openers that could start any paper, and closing sentences that only restate the paragraph.
- Stacked hedges ("may potentially suggest").

Before handing back any drafted text, reread it against both lists and rewrite anything that sounds like AI.

## Terminology (use consistently across the review and slides)
Andie's three tiers, set in Section 2 of the lit review:
- **Natural asset**: the stock of a natural unit, measured in its own units (acres of park, number of trees, number of foxes, miles of trail, lake surface area). A park is a natural asset, not a service.
- **Ecosystem service**: what the natural asset provides (cooling, stormwater drainage, water and air purification, vermin control, improved mental health, a place to recreate).
- **Benefit**: the value to people of that service, ideally in money, so decision makers can weigh it against other uses of a budget.

Note: Boyd and Banzhaf's "services" (components of nature) sit closer to Andie's natural assets, and they call recreation a benefit. Andie's tiers follow natural capital accounting instead.

## Citations and accuracy
- **Do not pull in new papers.** Cite only papers Andie already cites elsewhere in her own work (her existing `.bib` files, listed below). If a claim needs a source that is not there, flag it and let Andie supply one. Do not search the web for literature unless she asks.
- **Never invent a citation, author, year, finding, or number.** State a finding only if you have checked it against how Andie uses the paper in her own writing, the paper itself (PDF), or its abstract, or if Andie has supplied it.
- If a claim needs a source, flag it inline the way Andie does: `(\textbf{citation?})`. For anything else uncertain, use `\rev{Claude}{...}`. Never silently drop a claim or swap in a different source.
- Copy the entries you need into this project's `references.bib`, unchanged and with the same key. Do not point to the other files.
- Main source bibliography: `/Users/ac2878/Library/CloudStorage/Dropbox-YSE/Andie Creel/Dissertation/references.bib` (about 270 entries). It already has urban green space valuation papers, including `klaiberItLessHot2017`, `netusilEstimatingDemandTree2010`, `sanderValueUrbanTree2010`, `herisPilotingUrbanEcosystem2021`, `salazarmirandaDesirableStreetsUsing2021`, `keelerSocialecologicalTechnologicalFactors2019`, `boydWhatAreEcosystem2007`.
- Other bibs with a few entries not in the dissertation bib (all under `/Users/ac2878/Library/CloudStorage/Dropbox-YSE/Andie Creel/`):
  - `LWCF/Presentations/osweet/parks-lwcf.bib`: park and canopy disparities (Locke, Grove, Jesdale, Duncan, Engelberg)
  - `PhD Work/green_space_spending/presentations/5_aere_summer_conference/bibliography.bib`: `omb_ecosystem_guidance_2024`
  - `PhD Work/YIBS small grant/YIBS Application-2023/YIBS.bib`: `jenerette_ecosystem_2011`
  - `PhD Work/Andie's Prospectus/2. Substituion Outdoor, Downtown, and Indoor/bibs/recreation demand.bib`: urban park visitation and social media
  - `Grizzly Bears 2.0/manuscript components/grizzly_bears.bib`: wildlife valuation, `rondeau_managing_2003` (urban deer)
  - `virtual_fencing/references.bib`: PES design
- Andie's JMP (tree cover protects storefront revenue from heat) is `creelValueNatureBasedAdaptation2026` (working paper, 2026).
- Andie's own work belongs in this literature: the dissertation chapters on tree cover and storefront revenue during heat, on the national value of local outdoor recreation (`creelNationalValueLocal2026`), and on recreation in satellite accounts. Cite them where they fit, but do not inflate them.

## Layout
- `concept_frame_manuscript/draft_concept_framework.tex`: the conceptual framework paper (current focus)
- `informal_review_manuscript/main.tex`: the lit review (finished; was `manuscript/main.tex`, and older sections of this file still use that path)
- `presentation/creel_<venue>.tex`: the Beamer talk
- `references.bib`: one shared bibliography at the repo root
- `literature/`: PDFs of papers (gitignored)
- `outline.md`: Andie's outline, if it does not live in this file

## LaTeX conventions: lit review (`manuscript/main.tex`)
Mirror `/Users/ac2878/Library/CloudStorage/Dropbox-YSE/Andie Creel/virtual_fencing/manuscript_lee_creel_gilbert/main.tex`:
- Header comment: `% Goal: ...` then `% Andie Creel / Started November 2026`.
- `\documentclass[12pt]{article}`; `\usepackage[english]{babel}`; `\usepackage[letterpaper,top=2cm,bottom=2cm,left=3cm,right=3cm,marginparwidth=1.75cm]{geometry}`.
- Packages: amsmath, amssymb, graphicx, array, booktabs, caption, todonotes, natbib, xurl, `hyperref` with `colorlinks=true, allcolors=blue`.
- Comment macro: `\newcommand{\rev}[2]{\todo[inline, size=\small, color=yellow!40]{\textbf{#1:} #2}}`. Do not delete Andie's `\rev` comments unless asked.
- `\title{...}`, `\author{Andie Creel}`, `\date{\today}`, `\maketitle`.
- Put comment dividers (`% -----...`) around each `\section` / `\subsection`.
- Use `\citet` in text and `\citep` in parentheses.
- End with `\newpage`, `\bibliographystyle{aer}`, `\bibliography{../references}`.
- No abstract unless asked.

## Beamer conventions (`presentation/`)
Start from the preamble of `/Users/ac2878/Library/CloudStorage/Dropbox-YSE/Andie Creel/PhD Work/green_space_spending/presentations/15_heartland/creel_heartland.tex` and copy it as is:
- `\documentclass[aspectratio=169]{beamer}`, `\usetheme{Madrid}`. Black, white, and gray: black frame titles with no box, gray blocks, the custom three-part footline (author | short title | frame number and short date), no navigation symbols, `-` item bullets.
- natbib author-year citations in gray, the hyperref `natlinkbreak` fix, and `\smallcite{key}` for citations on slides.
- Title page: `\title[short]{long}`, `\author[Andie M. Creel]{Andie M. Creel}`, `\date[Month Year]{Full date}`, `\institute{venue}`.
- Background photos through `\usebackgroundtemplate` and a TikZ node: opacity 0.4 on the title slide, 0.1 on content slides, 0.25 on the conclusion, 0.7 on the "Questions?" slide. Clear it (`\usebackgroundtemplate{}`) on figure-heavy slides. On-topic photos for urban green space are in `/Users/ac2878/Library/CloudStorage/Dropbox-YSE/Andie Creel/PhD Work/green_space_spending/presentations/99_photos/` (e.g., `new_haven_sun_trees.jpg`, `green_city.jpg`, `mexico_city_greenspace.jpg`, `park-people-nyc copy.jpg`).
- Slide text is terse fragments in nested bullets, with `\pause` between top-level bullets and `\smallcite` right after the claim it supports.
- Frame titles: plain labels for setup slides (Motivation, Research Questions, Conclusion); a full-sentence takeaway for any slide that delivers a finding.
- Section dividers: `% ------------------- Motivation -------------------`.
- Close with a "Questions?" slide (`\Huge Questions?` and `andie.creel@yale.edu`), then `\begin{frame}[allowframebreaks]{References}`, `\tiny`, `\bibliographystyle{abbrvnat}`, `\bibliography{../references}`.

## Build
- `latexmk -pdf main.tex`, run from inside `manuscript/` (same for the presentation file in `presentation/`).
- Commit `.tex`, `.bib`, and final `.pdf` only. Build artifacts (`.aux`, `.log`, `.bbl`, `.fdb_latexmk`, `.synctex.gz`, ...) and `literature/` are gitignored.

## Workflow
1. **Lit review** (`manuscript/main.tex`). Each section starts with Andie's outline bullets and the candidate citations as comments. Draft one section at a time, then stop for her edits.
2. **Talk.** Compress the review into slides. Each section becomes 1–3 slides, and the section claims become takeaway frame titles.
