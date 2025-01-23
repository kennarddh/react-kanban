# React JS Boilerplate

## Guide

### Install Dependencies

```bash
npm install
```

### Environment Variables

All environment variables for react application must start with `APP_` prefix

To change env prefix change add or remove string from `envPrefix` variable in [`vite.config.json`](./vite.config.ts)

Environtment variables can be accesed using `env.<name>` or [`import.meta.env.<name>`](https://vitejs.dev/guide/env-and-mode.html). Prefix must be included.

Declare env types in `src/env.d.ts` in `ImportMetaEnv` interface

The environment variables can be found and modified in the `.env` file. See `.env` for default values.

In the project directory, you can run:

### Start

Start development build.

```bash
npm start
```

### Build

Type check and build for production.

```bash
npm run build
```

### Preview

Preview production build.

```bash
npm run preview
```

### Clean

Removes all the files generated by the build process.

```bash
npm run clean
```

### Lint Check

Finds linting errors.

```bash
npm run lint:check
```

### Lint Fix

Fix linting errors.

```bash
npm run lint:fix
```

### Prettier Check

Check the code formatting.

```bash
npm run prettier:check
```

### Prettier Fix

Fix the code formatting.

```bash
npm run prettier:fix
```

### Types Check

Check Typescript types.

```bash
npm run types:check
```

### Check

Check linting, code formatting, Typescript types.

```bash
npm run check
```

### Fix

Fix linting, code formatting, and check Typescript types.

```bash
npm run fix
```

## Notes

- If you want to disable check and fix workflow you need to remove [`.github/workflows/check-and-fix.yml`](./.github/workflows/check-and-fix.yml).
- If you want to disable dependabot you need to remove [`.github/dependabot.yml`](./.github/dependabot.yml).
- If you want to disable codeql analysis you need to remove [`.github/workflows/codeql-analysis.yml`](./.github/workflows/codeql-analysis.yml).