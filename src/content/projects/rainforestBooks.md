---
title: 'Rainforest Books'
description: 'Full stack Amazon clone.'
pubDate: 'July 27 2023'
heroImage: '/rainforestBooks/rainforestBooks.png'
badge: 'Live Demo'
---

This is a mobile responsive Amazon web app clone that closely mimics its appearance and user experience.

Live demo: [https://books.vincentchuck.com](https://books.vincentchuck.com)

[Github repo](https://github.com/VincentChuck/amazon-clone)

### Desktop demo gif

![Desktop demo gif](/rainforestBooks/desktopDemo.gif)

## Highlights

- **Mobile responsive**

- **Checkout with Stripe**

  use credit card number "4242 4242 4242 4242" and any future expiry date and CVC to test the checkout
  ![stripe checkout screenshot](/rainforestBooks/stripeCheckout.png)

- Components that closely mimics the actual Amazon website:
  - **Multi-level category filter** ![category filter demo](/rainforestBooks/categoryFilterDemo.gif)
  - **Mobile search filter modal** ![Mobile search filter modal demo](/rainforestBooks/mobileModalDemo.gif)

## Technologies used:

- Language: [TypeScript](https://www.typescriptlang.org/)
- Frontend: [Next.js](https://nextjs.org/), [Tailwind CSS](https://tailwindcss.com/), [Redux Toolkit](https://redux-toolkit.js.org)
- Backend: [tRPC](https://trpc.io/), [Stripe](https://stripe.com/)
- Database: [PostgreSQL](PostgreSQL), [Prisma ORM](https://www.prisma.io/), hosted on [Supabase](https://supabase.com/)
- Deployed on [Vercel](https://vercel.com/)
