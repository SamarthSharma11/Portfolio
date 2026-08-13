# Samarth Sharma Portfolio

A responsive personal portfolio for **Samarth Sharma**, a Full-Stack Developer and AI Engineer based in Delhi, India.

**Live site:** [samarthsharma11.github.io/Portfolio](https://samarthsharma11.github.io/Portfolio/)

## Highlights

- Responsive, terminal-inspired portfolio interface
- About, skills, project, education, leadership, and contact sections
- Project cards populated from browser local storage
- Lightweight demo admin dashboard for publishing project cards
- Demo contact form that records messages locally in the browser
- No build step or framework required - deploy directly with GitHub Pages

## Featured projects

| Project | Summary | Core stack |
| --- | --- | --- |
| ContextIQ | Multi-tenant SaaS for custom RAG chatbots with document/URL ingestion, grounded answers, analytics, and billing. | React, Node.js, OpenAI API, LangChain, Pinecone, Stripe |
| SnapDeploy | Browser IDE that turns plain-English prompts into functioning applications and patches follow-up requests as diffs. | React, Node.js, GPT-4 API, WebContainers, Socket.io |
| DevPilot | Autonomous pull-request review agent that analyzes diffs, runs sandboxed tests, and suggests focused fixes. | Python, FastAPI, LangChain, GitHub API, Docker, Redis |

## Run locally

This is a static website. Clone the repository and open `index.html` in a browser, or serve it locally:

```bash
npx serve .
```

Then visit the URL printed by the local server.

## Project structure

```text
.
├── index.html   # Page structure and portfolio content
├── styles.css   # Responsive visual system and layout
└── app.js       # Dynamic project cards, admin demo, and contact-form storage
```

## Admin demo

Select **Admin** in the site header and use this demo access code:

```text
demo
```

The dashboard can add project cards. Both project updates and submitted contact messages are stored only in the browser's `localStorage`; no server or external database is connected in this static demo.

To reset sample project content, choose **Reset demo content** from the dashboard.

## Deployment

The site is deployed with GitHub Pages from the `main` branch. Every commit to that branch triggers a new Pages build.

## Contact

- Email: [samarthsharma112006@gmail.com](mailto:samarthsharma112006@gmail.com)
- LinkedIn: [Samarth Sharma](https://www.linkedin.com/in/samarth-sharma-54a629378)
- GitHub: [@SamarthSharma11](https://github.com/SamarthSharma11)

---

Built with intent, not a template.
