# Sveltekit Typescript Tailwind Pug Starter

A starter for launching a Sveltekit / Pug project with Typescript and TailwindCSS and some other bells and whistles.

## About

This starter was developed for the [Lightning Jar ](https://lightningjar.com) team. It's designed to get one up and running quickly on a new project using:

- Sveltekit
- Svelte
- Typescript
- Pug.js
- TailwindCSS
- Prettier
- ESLint
- Vite
- Playwright

This starter follows many of the defaults of Sveltekit.

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

## Pug

This starter uses the [svelte-preprocess](https://github.com/sveltejs/svelte-preprocess). Special syntax is required to write Pug inside Svelte templates. You can learn more [here](https://github.com/sveltejs/svelte-preprocess/blob/HEAD/docs/preprocessing.md#preprocessors).

## Shortcuts

The following shortcuts and corresponding folders come pre-configured:

- $atoms: './src/lib/components/atoms'
- $components: './src/lib/components'
- $functions: path.resolve('./src/lib/functions'
- $lib: './src/lib'
- $molecules: './src/lib/components/molecules'
- $organisms: './src/lib/components/organisms'
- $settings: './src/lib/settings'
- $stores: './src/lib/stores'
- $types: './src/lib/types'
- $utils: './src/lib/utils'

## Strongly Recommended Editor & Extensions

If you are using VSCode, we recommend these extensions:

- [Svelte for VS Code](https://marketplace.visualstudio.com/items?itemName=svelte.svelte-vscode)
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [Prettier ESLint](https://marketplace.visualstudio.com/items?itemName=rvest.vs-code-prettier-eslint)
- [Tailwind CSS Intellisense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)
- [Playwright Test for VSCode](https://marketplace.visualstudio.com/items?itemName=ms-playwright.playwright)
