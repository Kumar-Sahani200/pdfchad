# PDFCHAD - A Modern Fullstack SaaS-Platform

Built with the Next.js 13.5 App Router, tRPC, TypeScript, Prisma & Tailwind

## Features

- 🛠️ Complete SaaS Built From Scratch
- 💻 Beautiful Landing Page & Pricing Page Included
- 💳 Free & Pro Plan Using Stripe
- 📄 A Beautiful And Highly Functional PDF Viewer
- 🔄 Streaming API Responses in Real-Time
- 🔒 Authentication Using Kinde
- 🎨 Clean, Modern UI Using 'shadcn-ui'
- 🚀 Optimistic UI Updates for a Great UX
- ⚡ Infinite Message Loading for Performance
- 📤 Intuitive Drag n’ Drop Uploads
- ✨ Instant Loading States
- 🔧 Modern Data Fetching Using tRPC & Zod
- 🧠 LangChain for Infinite AI Memory
- 🌲 Pinecone as our Vector Storage
- 📊 Prisma as our ORM
- 🔤 100% written in TypeScript
- 🎁 ...much more

## Getting started

To get started with this project, run

npm install

change 'pdfchad' to whatever project name created in pinecone, stripe, planetscale, kinde (keep same name for all the platform while creting keys for the .env)

Pinecone for long-term vector storage - https://www.pinecone.io/

I prefer this tool for the DB: https://console.aiven.io

Uploadthing for storing PDF files - https://uploadthing.com/dashboard

OpenAI for answering PDF questions - https://platform.openai.com/

Stripe for payment processing - https://stripe.com/

change environment value "gcp-starter" in src/lib/pinecone.ts to the environment value of your pinecone project

Do not forget to push the schema file into your database after you have created it!

When you are shifting from localhost to cloud, don't forget to change the locahost:3000 from envs as well as from Kinde

fill the .env out & and that's all you need to get started!

## Env File example:

KINDE_CLIENT_ID=
KINDE_CLIENT_SECRET=
KINDE_ISSUER_URL=
KINDE_SITE_URL=
KINDE_POST_LOGOUT_REDIRECT_URL=
KINDE_POST_LOGIN_REDIRECT_URL=

DATABASE_URL=

UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=

PINECONE_API_KEY=

OPENAI_API_KEY=

STRIPE_SECRET_KEY=
