# GitHub profile README design

**Status:** revised for user review

## Goal

Create a concise, trustworthy GitHub profile README for `vins-anity` with the
information density and terminal feel of neofetch.

## Layout

Render one static terminal-card image in `README.md`:

1. A dark rounded terminal frame with macOS window dots and the prompt
   `vins-anity@github: ~$ neofetch`.
2. Identity rows:
   - **Now:** Backend / Product Engineer
   - **Focus:** AI-assisted workflows and product automation
   - **Edu:** BS Information Technology, University of Cebu - Banilad
3. Four stack rows:
   - **Backend:** TypeScript, Bun, Node.js, REST APIs, PostgreSQL
   - **AI / ML:** AI-assisted workflows, OpenRouter, LLM architecture tools
   - **Infra:** Docker, GitHub Actions, testing and deployment workflows
   - **Tools / IT:** BigQuery, Power BI, Postman, Git
4. Three factual highlights:
   - Building product systems for lead qualification and operations
   - Developing AI-assisted workflows and decision support
   - Shipping TypeScript APIs, data workflows, and internal tools

The supplied portrait becomes a separate ASCII-style image asset below the
terminal card, not inside it. This preserves the reference's clean neofetch
layout while still using the personal image.

## Constraints

- Do not claim unverified titles, employer names, metrics, or technologies.
- Do not include contact details or the full resume.
- Use no dynamic badges, contribution widgets, animations, or third-party trackers.
- Keep the implementation to `README.md`, `assets/neofetch-profile.png`,
  and `assets/profile-ascii.png`.
