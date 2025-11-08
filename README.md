# codexconfig

Configurations for the Codex CLI. To ensure the CLI has everything it needs, install the dependencies from this repo. The Open Codex CLI is provided as a project dependency so you can run it via `npm run open-codex` or `npx open-codex`.

## Installation

1. Ensure you are running **Node.js 22 or newer**. The bundled `open-codex` CLI depends on the latest Node runtime and will emit engine warnings or fail to execute on older versions.

2. Install the local dependencies:
   ```sh
   npm install
   ```
Afterwards you can configure or run the Codex CLI with the provided settings using:

```sh
npm run open-codex -- <args>
```

or

```sh
npx open-codex <args>
```
