# Next.js Chat and Image Generation App

This is a **Next.js** application that features a chatbot interface integrated with OpenAI, including the ability to upload and display images, as well as generate images using the DALL-E API.

## Features

- **Chatbot with OpenAI**: Users can chat with an AI, where the AI responds based on the GPT-4 model.
- **Image Upload**: Users can upload images during their chat sessions, and the images will be displayed in the chat interface.
- **DALL-E Image Generation**: Users can input a prompt to generate images using DALL-E directly from the app.
- **Shared Navbar**: Consistent navigation bar across all pages using a reusable component.

## Table of Contents

- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Available Scripts](#available-scripts)
- [API Routes](#api-routes)
- [Technologies Used](#technologies-used)
- [License](#license)

## Getting Started

### Prerequisites

- Node.js (version 18 or higher)
- npm or yarn

### Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repo.git
```

Create a .env.local file in the root directory and add your OpenAI API keys and other environment variables:

``` 
OPENAI_API_KEY=your-openai-api-key
```

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

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
