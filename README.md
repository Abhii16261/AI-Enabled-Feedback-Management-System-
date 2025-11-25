AI-Enabled-Feedback management system - NBPDCL

This project uses a modern, high-performance frontend architecture built on React, Next.js, and TypeScript. Below is a breakdown of each key technology and how it fits into the system.

⚛️ Next.js 15 (App Router) + React 19 + TypeScript 5

Next.js powers routing, Server Components, SSR/SSG, and serverless API routes.

React 19 handles the UI layer through component-based rendering.

TypeScript adds static typing, improved tooling, and safer, faster development.

🎨 Tailwind CSS + PostCSS + Autoprefixer

Tailwind CSS provides utility-first styling for fast UI development.

PostCSS runs the Tailwind build pipeline behind the scenes.

Autoprefixer adds vendor prefixes for consistent cross-browser support.

🧩 shadcn/ui + Radix UI + Lucide Icons

shadcn/ui gives pre-built, Tailwind-styled components.

Radix UI supplies accessible, headless primitives.

Lucide Icons offers lightweight, customizable SVG icons.
Together, they enable a polished, accessible UI without reinventing core components.

📝 React Hook Form + Zod Validation + Form Components

React Hook Form provides performant, uncontrolled form handling.

Zod supplies schema-based validation with great TypeScript support.

Inputs like react-day-picker, input-otp, and others plug seamlessly into the same form/validation flow.

📊 Recharts

Used for charts and data visualizations.

Responsive, declarative components that fit naturally within the React UI.

✨ UI/UX Utilities

Next Themes → Light/dark mode toggling

Sonner → Toast notifications

cmdk → Command palette

Embla Carousel → Smooth, customizable carousels

react-resizable-panels → Adjustable panel layouts

All styled using Tailwind and integrated directly into the React component tree for a seamless experience.

⚙️ React Context, Hooks & Utility Libraries

Context + custom hooks manage shared state (auth, theme, preferences, etc.).

clsx and tailwind-merge safely combine Tailwind class strings.

date-fns handles date formatting and manipulation across the UI.

🤖 AI / Voice Integrations

Deepgram SDK → Speech-to-text

ElevenLabs → Text-to-speech

Google Gemini API → AI chat, reasoning, summarization
These are connected through Next.js API routes, then consumed as frontend hooks.

🗄️ Data Layer (db.json, MongoDB via Mongoose)

Some pages call API routes that interact with a local db.json or MongoDB using Mongoose.

Frontend components fetch data through these serverless endpoints.
