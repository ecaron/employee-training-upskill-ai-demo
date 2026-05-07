# Project Background

For many employees, the primary frustration isn't just the paycheck — it is the **lack of career growth**. In fact, research shows that a staggering **94% of employees** would stay at a company longer if it invested in their learning and development (L&D). Unfortunately, a significant disconnect remains: roughly **59% of workers** claim they have received zero formal workplace training, leaving them to self-learn the skills required for an increasingly complex world.<sup>[1](https://tandemspace.com/blog/workforce-statistics-2026)</sup>

The friction often lies in the **complexity of execution**. While **90% of organizations** cite learning opportunities as their top retention strategy, HR departments are struggling with the logistical nightmare of identifying specific skill gaps and coordinating training<sup>[2](https://trainingorchestra.com/employee-training-trends/)</sup>. Organizations face a "perfect storm" of challenges, including:
* **Skill Identification Paralysis:** With **61% of companies** identifying AI and automation as their biggest skill gaps for 2026, many employees are simply "not sure what they should learn" to stay relevant.<sup>[3](https://www.gallup.com/workplace/692642/addressing-barriers-blocking-employee-development.aspx)</sup>
* **Operational Friction:** Between scheduling conflicts, budget constraints, and a culture that often views training as "time away from real work" (a sentiment shared by nearly **46% of employees**), development often gets pushed to the margins.
* **Fragmented Systems:** Roughly **75% of training managers** express dissatisfaction with their own L&D strategies, citing poor user experiences and a lack of human connection in digital-only learning platforms.<sup>[4](https://www.devlinpeck.com/content/employee-training-statistics)</sup>

Although there are many ways to address this, one idea that leverages AI combines your company information (dossier, current projects, roadmap) with your employee information (job description, resume, professional ambitions). This can be accomplished with most AI solutions, such as [OpenAI Codex](https://openai.com/codex/), [Claude Cowork](https://claude.com/product/cowork) or [OpenClaw](https://openclaw.ai/)

A [sample of the results is available here](SAMPLE.md), and a blog and video are coming soon.

## Fancy Hats Inc. — Agentic AI Demo

A demo project showing how an agentic AI advisor can be grounded in a specific company's context — its strategy, projects, and people — to produce recommendations that are actually useful instead of generically plausible.

The fictional company, **Fancy Hats, Inc.**, is a 100-year-old premium hat retailer based in Boston, working through a three-year roadmap to grow from a $42M Eastern-US business into a $90M coast-to-coast brand.

## What's Here

```
.
├── agent/       # Instructions for the agentic AI
├── company/     # Company strategy, projects, and background
└── employees/   # Employee resumes, job descriptions, and ambitions
```

### [`agent/`](agent/)
Markdown files that define how an AI advisor should behave when working with this company — what to read, how to reason, what tone to take, and where the boundaries are. Drop these into the system prompt, project instructions, or context window of an agentic AI provider.

### [`company/`](company/)
Demo data describing the company itself: an overview and dossier, the three-year strategic roadmap, and the active project portfolio. This is the strategic context the agent reasons against.

### [`employees/`](employees/)
Demo data for a small set of employees. Each employee has three files: a resume, the job description for their current role, and a confidential "ambitions" file capturing their career goals in their own words. This is the people context the agent personalizes against.

## How to Use It

Point your agentic AI at the project and ask questions a head of people, a COO, or a CEO would actually ask:

- *"Suggest five training opportunities for my employees."*
- *"Who should I staff on the Denver pop-up?"*
- *"Build me a mentorship plan."*
- *"Who's at risk of leaving, and why?"*
- *"Recommend a hiring priority for next quarter."*

The agent will combine the roadmap, the active projects, and the individual employee context to produce specific, named, defensible recommendations — rather than generic advice.

### Sample Prompt

```markdown
Based on what you know about my company and my employees, please suggest two training opportunities to offer my employees. Things to keep in mind:
* Focus on skills that will help my company in the near future.
* Prioritize skills where my employees can learn and grow together.
* Don't worry about all employees have to attend all trainings. I'd prefer each training be tremendously beneficial to 25% of my employees than being minimally beneficial to 100% of my employees.
 
For each training opportunity that you identify:
* Write the title and brief description of each opportunity, plus a couple sentences of why it helps the company
* Provide a bullet list of who should attend and a sentence about why this would benefit them
* If you identify an existing employee with existing skills in this area who could support or lead the training, mention that.
* Provide a rough budget and timeline, as well as a shortlist of specific external resources that some of the training opportunties will require
```

## Notes

All company and employee data is fictional. Any resemblance to real hat retailers, real Bostonians, or real ambitions is coincidental.

## Questions or Support

Please contact [Eric Caron](https://ericcaron.com/contact/) for questions or advice on setting this up for your company.
