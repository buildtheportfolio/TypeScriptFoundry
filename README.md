# TypeScript Foundry

A hub for small, self-contained TypeScript projects covering language fundamentals, algorithms, Node.js, browser APIs, tooling, architecture and practical web engineering.

> Every project is independently runnable and intentionally focused.

## Project structure

```text
TypeScriptFoundry/
├── index.html
├── style.css
├── script.js
├── Ideas.md
├── projects/
│   ├── _template/
│   │   ├── README.md
│   │   ├── package.json
│   │   ├── tsconfig.json
│   │   └── src/
│   │       └── index.ts
│   └── ...
└── README.md
```

The hub automatically discovers project folders under `projects/`. `Ideas.md` is the backlog and source of truth for the collection.

## Add a project

1. Copy `projects/_template/` to a new folder.
2. Rename the package and project metadata.
3. Implement the project from `Ideas.md`.
4. Run `npm install` and `npm run build` from the project directory.
5. Run the generated JavaScript with Node.js when appropriate, or use the project-specific browser entry point.
6. Push the folder to GitHub.

## Project rules

- One project = one folder.
- TypeScript is mandatory for application logic.
- Strict compiler settings are required.
- Keep dependencies minimal.
- Avoid frameworks unless the project genuinely requires one.
- Keep projects independently runnable.
- Keep source code free of comments.
- Deployment is manual.
- No GitHub Actions or workflows are required.
