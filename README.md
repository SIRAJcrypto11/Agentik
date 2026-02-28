# Agentik - AI Agent Platform

Agentik adalah platform AI Agent canggih yang dibangun dengan Next.js 14, TypeScript, dan OpenAI API.

## Fitur

- Chat AI real-time dengan GPT-4o-mini
- UI modern dengan Tailwind CSS
- Dark mode by default
- API Route dengan Edge Runtime
- Responsive design
- Bahasa Indonesia

## Tech Stack

- **Framework**: Next.js 14 (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **AI**: OpenAI GPT-4o-mini
- **Deployment**: Vercel

## Getting Started

### Prerequisites

- Node.js 18+
- OpenAI API Key

### Installation

```bash
npm install
```

### Environment Variables

Buat file `.env.local` dan tambahkan:

```env
OPENAI_API_KEY=your_openai_api_key_here
```

### Development

```bash
npm run dev
```

Buka [http://localhost:3000](http://localhost:3000) di browser.

### Build

```bash
npm run build
npm start
```

## Deploy ke Vercel

1. Push ke GitHub
2. Import repo di [vercel.com](https://vercel.com)
3. Tambahkan environment variable `OPENAI_API_KEY`
4. Deploy!

## Struktur Project

```
agentik/
├── app/
│   ├── api/
│   │   └── chat/
│   │       └── route.ts    # API endpoint
│   ├── globals.css          # Global styles
│   ├── layout.tsx           # Root layout
│   └── page.tsx             # Main page
├── package.json
├── tailwind.config.ts
├── tsconfig.json
└── next.config.js
```

## License

MIT
