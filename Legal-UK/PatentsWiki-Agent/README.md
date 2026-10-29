# PatentsWiki — IP Agent Lab Files

Files for the **PatentsWiki AI-Ready Knowledge Hub** exercise: build a SharePoint
knowledge hub for the Patents team, then ground a Copilot agent on it.

> **Fictional demo content.** Every page, process, policy, turnaround time, name
> and contact in these files is invented for the demo and is not real BAT
> guidance, policy or legal advice. Do not use real patent, matter or R&D data
> during the exercises.

## Start here

**[PatentsWiki_AI_Ready_Knowledge_Hub_Agent_and_Setup_Guide.pdf](PatentsWiki_AI_Ready_Knowledge_Hub_Agent_and_Setup_Guide.pdf)** — the full setup guide
(also available as [.docx](PatentsWiki_AI_Ready_Knowledge_Hub_Agent_and_Setup_Guide.docx)).

It covers the knowledge pattern (pages vs documents vs lists), the metadata
columns, the governance lifecycle, how to build the demo site, how to configure
the **PatentsWiki Assistant** agent, and the test plan.

## Demo wiki pages

All nine live in [`Data/`](Data/). Each one carries a page information block —
Wiki ID, content type, status, owner, last reviewed, next review — which is what
the agent reasons over.

| File | Wiki ID | Status |
| --- | --- | --- |
| `PW-HOME_PatentsWiki_Home.docx` | PW-HOME | Current |
| `PW-PROC-001_Invention_Disclosure_and_Filing_Process.docx` | PW-PROC-001 | Current |
| `PW-PROC-001-V2_Invention_Disclosure_Process_Superseded.docx` | PW-PROC-001-V2 | Superseded |
| `PW-POL-002_Public_Disclosure_and_Conference_Policy.docx` | PW-POL-002 | Current |
| `PW-PROC-003_Patent_Renewal_Decision_Process.docx` | PW-PROC-003 | Current |
| `PW-GUIDE-004_Requesting_RD_Data_for_Patent_Work.docx` | PW-GUIDE-004 | Current |
| `PW-PROC-005_Competitor_Patent_Watchlist_Process_Draft.docx` | PW-PROC-005 | Draft |
| `PW-REF-006_Patents_Glossary.docx` | PW-REF-006 | Current |
| `PW-REF-007_Whos_Who_and_Contacts.docx` | PW-REF-007 | Current |

The superseded and draft pages are deliberate — they are what the test plan uses
to check that the agent cites the right version and flags unapproved content.

## Setup

1. Download the files (use **Code → Download ZIP** on the repository home page).
2. Follow the setup guide to create the SharePoint site and upload the nine pages.
3. Keep the superseded page in an **Archive** area, and exclude that area from the
   agent's knowledge sources as the guide describes.
