# Adraa Inbox documentation

Public docs for the Adraa Inbox REST API, built with [Mintlify](https://mintlify.com).

## Structure

- `index.mdx`, `quickstart.mdx`, `authentication.mdx` — getting-started guides
- `api-reference/openapi.json` — OpenAPI spec; endpoint pages are generated from it
- `api-reference/introduction.mdx` — base URL, errors, rate limits
- `docs.json` — site configuration and navigation

## Local development

```bash
npm i -g mint
mint dev
```

Open http://localhost:3000. Changes deploy automatically when pushed to `main`.
