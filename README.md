# Fancy Hats Inc. — Agentic AI Demo

A demo project showing how an agentic AI advisor can be grounded in a specific company's context — its strategy, projects, and people — to produce recommendations that are actually useful instead of generically plausible.

The fictional company, **Fancy Hats, Inc.**, is a 100-year-old premium hat retailer based in Boston, working through a three-year roadmap to grow from a $42M Eastern-US business into a $90M coast-to-coast brand.

## What's Here

```
.
├── agent/       # Instructions for the agentic AI
├── company/     # Company strategy, projects, and background
└── employees/   # Employee resumes, job descriptions, and ambitions
```

### `agent/`
Markdown files that define how an AI advisor should behave when working with this company — what to read, how to reason, what tone to take, and where the boundaries are. Drop these into the system prompt, project instructions, or context window of an agentic AI provider.

### `company/`
Demo data describing the company itself: an overview and dossier, the three-year strategic roadmap, and the active project portfolio. This is the strategic context the agent reasons against.

### `employees/`
Demo data for a small set of employees. Each employee has three files: a resume, the job description for their current role, and a confidential "ambitions" file capturing their career goals in their own words. This is the people context the agent personalizes against.

## How to Use It

Point your agentic AI at the project and ask questions a head of people, a COO, or a CEO would actually ask:

- *"Suggest five training opportunities for my employees."*
- *"Who should I staff on the Denver pop-up?"*
- *"Build me a mentorship plan."*
- *"Who's at risk of leaving, and why?"*
- *"Recommend a hiring priority for next quarter."*

The agent will combine the roadmap, the active projects, and the individual employee context to produce specific, named, defensible recommendations — rather than generic advice.

## Notes

All company and employee data is fictional. Any resemblance to real hat retailers, real Bostonians, or real ambitions is coincidental.
