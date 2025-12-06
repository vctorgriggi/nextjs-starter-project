# Next.js Project Setup ✨

Initial setup for a Next.js project using **Next.js**, **ESLint**, **Prettier**, **Tailwind CSS**, and automatic sorting for imports and classes.

## 🚀 Stack

- Next.js
- ESLint (`eslint-plugin-simple-import-sort`)
- Prettier (`prettier-plugin-tailwindcss`)
- Tailwind CSS
- `.editorconfig` for consistent indentation

## 📁 Project Structure

- app/
- public/

## 🛠️ Configuration

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

Using `eslint-plugin-simple-import-sort` to automatically sort imports.

## 📜 Scripts

- `dev` — start the development server
- `build` — build the production bundle
- `start` — run the production server
- `lint` — run ESLint
- `format` — run Prettier

## 🎨 Tailwind Class Sorting

Sorting happens automatically on save or when running:

```
npm run format
```

## ▶️ Getting Started

Install dependencies:

```
npm install
```

Run the development server:

```
npm run dev
```
