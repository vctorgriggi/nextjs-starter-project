Initial setup for a Next.js project using ESLint, Prettier, Tailwind CSS, and automatic sorting for imports and classes.

## Stack

- Next.js
- ESLint with `eslint-plugin-simple-import-sort`
- Prettier with `prettier-plugin-tailwindcss`
- Tailwind CSS
- `.editorconfig` for consistent indentation

## Project Structure

```
.
├── .editorconfig
├── .gitignore
├── .prettierrc
├── package.json
├── package-lock.json
├── tsconfig.json
├── next.config.ts
├── postcss.config.mjs
├── eslint.config.mjs
├── README.md
├── app/
└── public/
```

## Configuration

### `.editorconfig`

```
root = true

[*]
indent_style = space
indent_size = 2
```

### `.prettierrc`

```json
{
  "tabWidth": 2,
  "semi": true,
  "singleQuote": true,
  "plugins": ["prettier-plugin-tailwindcss"]
}
```

### ESLint

The project uses `eslint-plugin-simple-import-sort` to automatically sort imports.

## Scripts

- `dev` starts the development server
- `build` builds the production bundle
- `start` runs the production server
- `lint` runs ESLint
- `format` runs Prettier

## Tailwind Class Sorting

`prettier-plugin-tailwindcss` automatically sorts Tailwind CSS classes on save or when running:

```
npm run format
```

## Getting Started

Install dependencies:

```
npm install
```

Run the development server:

```
npm run dev
```
