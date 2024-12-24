This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Video Code Explaination
```bash
PART 1: https://www.loom.com/share/25de77a2fb41473c9ec50ebb815f62f5?sid=01d66419-fb00-4eb5-9606-5cf5fe9b25c8
PART 2: https://www.loom.com/share/2827caa4b6ba4649a45510524e5e9c61?sid=06bc1a39-0305-4b30-b2c8-1fc96c94d709
```

## Prompt Used
```bash
Prompt for claude:
For this we need to feed a prompt to the claude. Here is what we fed:

We are making a AI Text Styler for Social Media. Here’s my specifications features:
- A minimalist and clean design inspired by Pinterest's layout.
- The targeted user is social media user which are gen z or gen Alpha, for aesthetic captions.
- Converts input text from user into stylish fonts, symbols, and emojis.
- Options for bold, italics, and cursive.
- Categories like "Cute," "Cool," and "Funky."
- A copy button on each styled text output for quick copying

Example:
Input: "Hello World"
Output: "𝐇𝐞𝐥𝐥𝐨 𝗪𝗼𝗿𝗹𝗱 ✨🌏"

I'm not a programmer, so please explain everything thoroughly.
I need a step-by-step guidance.
Don't assume any prior knowledge; spell out even the most basic steps.
After this whatever claude suggests, we follow the given steps and finally use cursor to edit our codes and launch our application.
```
