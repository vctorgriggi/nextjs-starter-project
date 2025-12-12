# Next.js Project Setup ✨

Initial setup for Next.js projects with ESLint, Prettier, Tailwind CSS, and automatic import/class sorting.

[![Next.js](https://img.shields.io/badge/Next.js-15-black?style=flat-square&logo=next.js)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-4-38bdf8?style=flat-square&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![ESLint](https://img.shields.io/badge/ESLint-9-4B32C3?style=flat-square&logo=eslint&logoColor=white)](https://eslint.org/)
[![Prettier](https://img.shields.io/badge/Prettier-3-F7B93E?style=flat-square&logo=prettier&logoColor=black)](https://prettier.io/)

---

## ✨ Features

🎨 **Tailwind CSS 4** — Modern styling  
📝 **ESLint** — Linting with auto-sorted imports  
✨ **Prettier** — Consistent formatting with Tailwind plugin  
⚙️ **EditorConfig** — Standardized indentation  
🔄 **Auto-sorting** — Imports and classes organized automatically  
🚀 **Next.js 15** — App Router and Server Components

---

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/yourusername/next-project-setup.git
cd next-project-setup

# Install dependencies
npm install

# Run the project
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) 🎉

---

## 🏗️ Project Structure

```
├── app/                      # Next.js App Router
│   ├── layout.tsx           # Root layout
│   ├── page.tsx             # Home page
│   └── globals.css          # Global styles
├── public/                  # Static assets
├── .editorconfig            # Editor configuration
├── .prettierrc              # Prettier configuration
├── eslint.config.mjs        # ESLint configuration
└── package.json
```

---

## 🛠️ Tech Stack

**Framework** → [Next.js 16](https://nextjs.org/)  
**Styling** → [Tailwind CSS 4](https://tailwindcss.com/)  
**Linting** → [ESLint](https://eslint.org/) + [eslint-plugin-simple-import-sort](https://github.com/lydell/eslint-plugin-simple-import-sort)  
**Formatting** → [Prettier](https://prettier.io/) + [prettier-plugin-tailwindcss](https://github.com/tailwindlabs/prettier-plugin-tailwindcss)  
**Language** → [TypeScript](https://www.typescriptlang.org/)

---

## ⚙️ Configuration

### EditorConfig

```ini
root = true

[*]
indent_style = space
indent_size = 2
```

### Prettier

```json
{
  "tabWidth": 2,
  "semi": true,
  "singleQuote": true,
  "plugins": ["prettier-plugin-tailwindcss"]
}
```

Automatically sorts Tailwind classes for consistent styling.

### ESLint

Using `eslint-plugin-simple-import-sort` for automatic import ordering.

**Import order:**

1. External libraries (React, Next.js)
2. Internal aliases (`@/`)
3. Relative imports
4. CSS and assets

---

## 📜 Scripts

```bash
# Development
npm run dev

# Production build
npm run build

# Run production server
npm start

# Linting
npm run lint

# Formatting
npm run format
```

---

## 🎨 Auto-sorting

### Imports

Sorted automatically on save or when running `npm run lint`.

### Tailwind Classes

Sorted automatically when running `npm run format`.

---

## 🔧 Customization

### ESLint Rules

Edit `eslint.config.mjs` to add custom rules.

### Prettier Config

Edit `.prettierrc` to adjust formatting preferences.

---

## 🤝 Contributing

Contributions are welcome! Open an issue or submit a PR.

---

**[Issues](https://github.com/yourusername/next-project-setup/issues)**

Made with ❤️ by [vctorgriggi](https://github.com/vctorgriggi)
