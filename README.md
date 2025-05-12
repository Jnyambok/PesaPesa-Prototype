# PesaPesa - Online Banking Platform

PesaPesa is a fully functional online banking platform built with Next.js, providing users with a seamless and secure banking experience.

## Key Features

* **Multi-Bank Connectivity:** Connects to multiple banks for aggregated account information.
* **Real-time Transactions:** Displays transactions in real-time.
* **Peer-to-Peer Transfers:** Enables money transfers to other platform users.
* **Ultra-Secure Authentication:** Implements Server-Side Rendering (SSR) for enhanced security.
* **Admin Dashboard:** Provides a dedicated home page for administrative functions.

## Tech Stack

* **Frontend:**
    * Next.js (SSR, Group Routes, Nested Layouts)
    * React Hook Form
    * Zod (Form Validation)
    * Tailwind CSS
    * Shadcn UI
    * Chart.jd
* **Backend:** Appwrite (Backend-as-a-Service)
* **Financial Account Linking:** Plaid

* **Monitoring:** Sentry

## Project Description

To create a modern and responsive user interface, PesaPesa leverages Next.js for server-side rendering, group routes, and nested layouts.  Advanced and reusable form management is handled using TypeScript, React Hook Form, and Zod.  Appwrite is used as a Backend as a Service.  The platform incorporates Charts, Shadcn, and Tailwind CSS for a visually appealing and responsive UI. Sentry is used for monitoring. Plaid integration allows users to securely connect their financial accounts.

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

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
