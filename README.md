# About

This repo contains a minimal reproduction of SvelteKit v2's SCSS preprocess dependency issue.

## How to reporduce

```bash
# install all dependencies
npm i

# run local dev server
npm run dev
```

The following message should show up in your terminal:
```bash
[vite-plugin-svelte] root_directory/src/routes/+page.svelte svelte.preprocess returned this file as a dependency of itself. This can be caused by an invalid configuration or importing generated code that depends on .svelte files (eg. tailwind base css)
```