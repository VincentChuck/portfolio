---
title: 'Todo App'
description: 'A simple todo app with email link and Google login, and optimistic updates.'
pubDate: 'March 16 2023'
heroImage: '/todoApp.jpeg'
badge: 'Demo'
---

This is a minimalistic todo app.

Live demo: [https://todo.vincentchuck.com](https://todo.vincentchuck.com/)

## Highlights

- **No password required**: supports Google login and email magic link login.
  ![Login page](/todoLogin.jpeg)

- **Mobile responsive** and uses the device's **dark / light mode**.
  ![Mobile view](/todoMobileCombined.jpeg)

- **Optimistic updates** for the creation, update, and deletion of todos for better user experience.
  ![Todo completed](/todoCompleted.jpeg)

## Technologies used:

- Language: [TypeScript](https://www.typescriptlang.org/)
- Frontend: [Next.js](https://nextjs.org/), [Tailwind CSS](https://tailwindcss.com/)
- Backend: [tRPC](https://trpc.io/)
- Database: [PostgreSQL](PostgreSQL), [Prisma ORM](https://www.prisma.io/), hosted on [Supabase](https://supabase.com/)
- Auth: [NextAuth.js](https://next-auth.js.org/) , [Mailtrap](https://mailtrap.io/) email delivery
- Deployed on [Vercel](https://vercel.com/)
