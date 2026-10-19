# HR — Lab Files

Lab materials for the Human Resources track: **BAT HR Copilot CIE — Hands-on Lab Guide**
(Copilot Apps + Agent Builder, for HR Managers).

> **Synthetic training material.** All policies, records, employee comments,
> contacts and scenarios in these files are fictional and are not official BAT
> information. Do not use real employee, customer, legal, health, payroll or
> performance data during the exercises.

## Start here

**[BAT_HR_Copilot_CIE_Lab_Guide.pdf](BAT_HR_Copilot_CIE_Lab_Guide.pdf)** — the full lab guide.

| Part | Activity | Time |
| --- | --- | --- |
| A | Choose two Copilot app exercises | 20 minutes |
| B | Build the BAT Manager People Guide agent | 25 minutes |
| C | Test and improve the agent | 5 minutes |

## Source files

All five live in [`Data/`](Data/):

| File | Used in |
| --- | --- |
| `BAT_Flexible_Working_Pulse_Survey_SYNTHETIC_CLEAN.xlsx` | Exercise A1 (Excel) |
| `BAT_Global_Flexible_Working_Framework_SYNTHETIC_CLEAN.docx` | Exercises A2, A3 + agent knowledge |
| `BAT_Manager_Onboarding_Guide_SYNTHETIC_CLEAN.docx` | Agent knowledge |
| `BAT_HR_Escalation_Guide_SYNTHETIC_CLEAN.docx` | Agent knowledge |
| `BAT_Manager_FAQ_SYNTHETIC_CLEAN.docx` | Agent knowledge |

The Excel pulse survey is employee feedback, not policy — do not add it as the
agent's knowledge source.

## Setup

1. Download the files (use **Code → Download ZIP** on the repository home page).
2. Save a working copy of each file in the training location your facilitator gives you.
3. Keep the four agent knowledge documents together in one OneDrive or SharePoint
   folder if your environment supports folder-based grounding.
