# firebase-mcp

SpinSync, a spin-the-wheel app with AI-suggested sections. It was prototyped in Firebase Studio with Next.js and Firebase Genkit.

## Features

- Add your own sections to the wheel.
- Spin it with an animation and see the result clearly.
- Save several wheels locally.
- Ask AI to suggest new sections, or edits to the current ones, based on what's already on the wheel. This runs as a Genkit flow (`src/ai/flows/suggest-wheel-sections.ts`).

## Stack

Next.js, TypeScript, Tailwind CSS, shadcn/ui and Firebase Genkit with Gemini.

## Running it

```bash
cd 0-prototype
npm install
export GOOGLE_GENAI_API_KEY=<your key>
npm run dev          # app on http://localhost:9002
npm run genkit:dev   # Genkit developer UI, in a second terminal
```

Get an API key from [Google AI Studio](https://aistudio.google.com/apikey).
