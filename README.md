<h1 align="center">AI Elements</h1>

<p align="center"><em>A modern, composable AI chat UI kit for Next.js, built with Radix, Tailwind, and shadcn/ui.</em></p>

<p align="center">
  <img src="https://img.shields.io/badge/Next.js-15.4.6-000000?style=flat&logo=next.js&logoColor=white" alt="Next.js 15.4.6" />
  <img src="https://img.shields.io/badge/React-19.1.0-61DAFB?style=flat&logo=react&logoColor=black" alt="React 19.1.0" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-4-06B6D4?style=flat&logo=tailwindcss&logoColor=white" alt="Tailwind CSS 4" />
</p>

AI Elements provides a set of accessible, production-ready React components for building conversational AI interfaces, with support for streaming, citations, reasoning, and more.

---

## Features

- ✨ **Composable chat UI**: Modular components for messages, prompts, sources, code, and more
- ⚡ **Streaming & reasoning**: Real-time AI responses with reasoning and source citation
- 🌐 **Web search integration**: Toggle web search for enhanced answers
- 🧩 **Radix + shadcn/ui**: Accessible, themeable, and easy to extend
- 🎨 **Tailwind CSS**: Fully customizable with utility classes
- 🦾 **TypeScript-first**: Strict types for safety and DX

## Quickstart

```bash
pnpm install
pnpm dev
# Visit http://localhost:3000
```

## Usage

The main chat UI is in [`components/ai-chat.tsx`](components/ai-chat.tsx). All atomic chat elements are in [`components/ai-elements/`](components/ai-elements/).

**Example:**

```tsx
import AIChat from '@/components/ai-chat';

export default function Home() {
	return <AIChat />;
}
```

> [!TIP]
> All components are headless and themeable. You can compose, extend, or style them as needed.

## Tech Stack

- [Next.js 15 (App Router)](https://nextjs.org/)
- [React 19](https://react.dev/)
- [Tailwind CSS 4](https://tailwindcss.com/)
- [shadcn/ui](https://ui.shadcn.com/)
- [Radix UI Primitives](https://www.radix-ui.com/)
- [ai-sdk](https://sdk.vercel.ai/docs)
- [TypeScript](https://www.typescriptlang.org/)

## Project Structure

```text
app/           # Next.js app directory (routing, layout)
components/    # UI and chat components
	ai-chat.tsx
	ai-elements/ # Atomic chat UI elements
lib/           # Utilities
public/        # Static assets (SVGs, icons)
```

## Credits

- Inspired by [shadcn/ui](https://ui.shadcn.com/) and [ai-sdk](https://sdk.vercel.ai/docs)
- Icons by [Lucide](https://lucide.dev/)
- Fonts: [Geist](https://vercel.com/font)

---

> [!NOTE]
> This project is under active development. Feedback and contributions are welcome!
