# 🌟 MastUI — Build Beautiful Interfaces, Effortlessly

> A modern, **motion-first** UI component library built with **ShadCN UI**, **Magic UI (Framer Motion)**, and **Tailwind CSS**.
> MastUI empowers developers to craft elegant, fast, and accessible React applications — one component at a time.

![npm](https://img.shields.io/npm/v/mastui?style=flat-square)
![license](https://img.shields.io/github/license/yourgithub/mastui?style=flat-square)
![types](https://img.shields.io/npm/types/mastui?style=flat-square)
![build](https://img.shields.io/github/actions/workflow/status/yourgithub/mastui/ci.yml?style=flat-square)

---

## 📦 Monorepo Structure (If using monorepo)

```
root/
├── apps/
│   ├── docs/           # Nextra-powered documentation site
│   └── landing/        # MastUI landing page
├── packages/
│   ├── mastui/         # Component library (ShadCN + Magic UI)
│   ├── eslint-config/  # Shared ESLint config
│   └── tsconfig/       # Shared TypeScript config
```

---

## ✨ MastUI Highlights

* 🎨 **Variants & Sizes** powered by [`cva`](https://github.com/joe-bell/cva)
* 🎬 **Fluid Animations** with Magic UI (Framer Motion)
* ⚡ **Tree-shakable**: Import only what you need
* 💅 **Dark Mode & Theming** built on Tailwind CSS
* ✅ **Accessibility** ensured via Radix UI Primitives
* 🔧 **Composable & Extendable** components
* 🔥 **Modern DX** with TypeScript, Tailwind, and React

---

## 📦 Installation

Install MastUI components via npm:

```bash
npm install mastui
```

Also install peer dependencies:

```bash
npm install tailwindcss framer-motion class-variance-authority tailwind-merge
```

---

## 🛠 Quick Usage

```tsx
import { Button } from "mastui";

export default function App() {
  return (
    <div className="p-4">
      <Button variant="default" size="md" animate>
        Click Me
      </Button>
    </div>
  );
}
```

## 🧪 Local Development (For monorepo)

```bash
pnpm install
pnpm dev
```

Build all packages:

```bash
pnpm build
```

---

## 🌐 Docs & Playground

* Documentation powered by [Nextra](https://nextra.site) — typically under `/apps/docs`
* Landing page in Next.js — typically `/apps/landing`

---

## 🔧 Remote Caching with Turborepo + Vercel

Speed up builds with remote caching:

```bash
npx turbo login
npx turbo link
```

Learn more: [Turborepo Remote Caching](https://turborepo.com/docs/core-concepts/remote-caching)

---

## 📜 License

MIT License © Made with ❤️ by [Aditya Narayan](https://github.com/adityanarayan29)

---

## 🔗 Useful Links

* [Turborepo Documentation](https://turborepo.com/docs)
* [ShadCN UI](https://ui.shadcn.com)
* [Magic UI](https://magicui.design)
* [Framer Motion](https://www.framer.com/motion/)
* [Tailwind CSS](https://tailwindcss.com)
* [Radix UI Primitives](https://www.radix-ui.com/)

