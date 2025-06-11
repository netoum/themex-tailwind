# @netoum/themex-tailwind

[Corex](https://www.npmjs.com/package/@netoum/corex) Themex Tailwind template package providing global design tokens and component-level utility styles for scalable UI development.

---

## 📦 About

This package provides precompiled tailwind styles for the [Corex](https://netoum.com/corex) UI system. It includes:

- 🎨 Global design tokens (colors, spacing, typography, etc.)
- 🧩 Component-level utility styles
- 🔧 Built from design tokens compatible with Tokens Studio files 
- 🌗 Multiple themes (Neo, Revo, Uno) with light/dark modes
- 🚀 Ready-to-use tailwind for scalable design systems and modern UIs
---

## 📦 Installation

```bash
npm install @netoum/themex-tailwind
```

## 💡 Usage

### Import a full theme stylesheet:

```css
@import "@netoum/themex-tailwind";
```

### Import component-level styles:

```css
@import "@netoum/themex-tailwind/components/button.css";
```

### Import token-based styles directly:

```css
@import "@netoum/themex-tailwind/tokens/global/color.css";
@import "@netoum/themex-tailwind/tokens/semantic/color.css";
```

### Theme and Mode data attributes
You must then add of the theme and mode data attribute

- data-theme="neo" data-mode="light"
- data-theme="neo" data-mode="dark"
- data-theme="revo" data-mode="light"
- data-theme="revo" data-mode="dark"
- data-theme="uno" data-mode="light"
- data-theme="uno" data-mode="dark"


💡 You can explore all available paths in the exports section of package.json.

## 🛠️ Development

### 🔧 Full Build (from design tokens)

Build all themes and modes (light/dark) using token configurations:

```bash
npm run build
```

### ⚡ CSS Build Only (skip design tokens)

Skip token processing and rebuild only the final output tailwind:

```bash
npm run build:from:css
```

## 📜 License

MIT © Netoum

## 🤝 Built by Netoum

Corex is built by Netoum — a web agency specializing in modern applications using HTML, Vanilla JS, TypeScript, Elixir/Phoenix, and accessibility-first development.

Creating exceptional web experiences for clients worldwide.

**Get in touch:** info@netoum.com