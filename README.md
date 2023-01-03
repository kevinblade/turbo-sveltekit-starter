# Turborepo Svelte + Tailwind starter

This is an official starter Turborepo.

## What's inside?

This Turborepo includes the following packages/apps:

### Apps and Packages

- `dashboard`: a [svelte-kit](https://kit.svelte.dev/) app
- `ui`: a stub Svelte component library shared by `dashboard` application
- `eslint-config-custom`: `eslint` configurations (includes `eslint-plugin-svelte` and `eslint-config-prettier`)
- `tailwind-config`: `tailwindcss` configurations (includes `forms', 'typography` and `daisyui`)
- `tsconfig`: `tsconfig.json`s used throughout the monorepo

Each package/app is 100% [TypeScript](https://www.typescriptlang.org/).

### Utilities

This Turborepo has some additional tools already setup for you:

- [TypeScript](https://www.typescriptlang.org/) for static type checking
- [ESLint](https://eslint.org/) for code linting
- [Prettier](https://prettier.io) for code formatting

## Using this example

Run the following command:

```sh
npx degit kevinblade/call-center call=center
cd call-center
pnpm install
git init . && git add . && git commit -m "Init"
```
