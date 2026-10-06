<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg" />
  <img src="assets/header-light.svg" alt="Mads Haerup, software engineer" width="100%" />
</picture>

<br />

I'm Mads, a software engineer in Copenhagen. I've spent five years building frontends for enterprise platforms: component libraries, data-heavy interfaces and AI-integrated search, in Vue, React, Angular and Next.js.

In my own time I build the layer underneath. A web framework, and the tooling that lets AI agents write code you can trust.

## Building

### [Avalon](https://useavalon.dev)

A full-stack islands framework. Pages ship as static HTML, and only the components you mark as islands load JavaScript.

- **Zero JS by default.** Nothing hydrates unless you ask for it.
- **Any framework, one route.** React, Vue, Svelte, Solid, Preact, Qwik and Lit islands side by side.
- **Hydration on your terms.** On load, when visible, on idle, on first interaction or behind a media query.
- **Deploys anywhere.** Built on Preact, Vite and Nitro, so it runs on Node, Bun, Deno, Cloudflare, Vercel, Netlify and AWS.

```tsx
// Ships as HTML. Loads JS only when someone clicks it.
<Counter island={{ condition: 'on:interaction' }} />
```

```bash
bunx create-avalon my-app
```

[Website](https://useavalon.dev) · [Docs](https://useavalon.dev/docs/introduction) · [Quick start](https://useavalon.dev/docs/quick-start)

### [Caelence agent](https://github.com/useAvalon/caelence-agent)

An open source coding-agent harness with a terminal UI and a desktop app. You bring an OpenRouter key, and chats stay on your machine.

- **Three modes.** Ask, plan and agent, with approval gates before anything runs.
- **Skills and evals.** Drop-in `SKILL.md` skills, plus eval suites to check the agent still does the job.
- **Integrations.** MCP servers, local tools and Langfuse tracing out of the box.
- **Built on** AWS Strands, Bun and Tauri.

```bash
bunx --bun @useavalon/caelence-agent desktop
```

[Repo](https://github.com/useAvalon/caelence-agent) · [npm](https://www.npmjs.com/package/@useavalon/caelence-agent) · MIT

## What I work on

- **Frontend architecture.** SPAs and SSR apps that stay maintainable as teams and features grow, typed end to end from OpenAPI.
- **Design systems.** Component libraries built with designers, from Figma to Storybook to production.
- **Accessibility.** WCAG-compliant components, ARIA patterns and automated checks with axe.
- **Data-heavy UIs.** Large grids, search and graph data (Solr, SPARQL) presented so people can actually work with it.
- **Agentic development.** Agent harnesses, MCP servers and evals on AWS Strands and Bedrock.

## Stack

<table>
  <tr>
    <td><b>Frontend</b></td>
    <td><img src="https://skillicons.dev/icons?i=ts,js,vue,react,angular,nextjs,pinia,tailwind,sass,vite" alt="TypeScript, JavaScript, Vue, React, Angular, Next.js, Pinia, Tailwind, Sass, Vite" height="40" /></td>
  </tr>
  <tr>
    <td><b>Backend</b></td>
    <td><img src="https://skillicons.dev/icons?i=nodejs,bun,express,fastapi,py,supabase,postgres,mongodb" alt="Node.js, Bun, Express, FastAPI, Python, Supabase, PostgreSQL, MongoDB" height="40" /></td>
  </tr>
  <tr>
    <td><b>Infra</b></td>
    <td><img src="https://skillicons.dev/icons?i=aws,cloudflare,vercel,netlify,docker,githubactions,jenkins,bitbucket" alt="AWS, Cloudflare, Vercel, Netlify, Docker, GitHub Actions, Jenkins, Bitbucket" height="40" /></td>
  </tr>
  <tr>
    <td><b>Testing</b></td>
    <td><img src="https://skillicons.dev/icons?i=vitest,jest,cypress" alt="Vitest, Jest, Cypress" height="40" /><br /><sub>Playwright, Testing Library</sub></td>
  </tr>
  <tr>
    <td><b>Tools</b></td>
    <td><img src="https://skillicons.dev/icons?i=figma,vscode,git" alt="Figma, VS Code, Git" height="40" /><br /><sub>Cursor, Kiro, Claude Code, Jira</sub></td>
  </tr>
  <tr>
    <td><b>AI</b></td>
    <td>AWS Strands, AWS Bedrock, LiteLLM, MCP</td>
  </tr>
</table>

<br />

<a href="https://useavalon.dev"><img src="https://img.shields.io/badge/useavalon.dev-1F2328?style=flat-square" alt="useavalon.dev" /></a>
<a href="https://github.com/useAvalon"><img src="https://img.shields.io/badge/useAvalon-1F2328?style=flat-square&logo=github&logoColor=white" alt="useAvalon on GitHub" /></a>