# BoardWex - Real-Time Miro Clone


Real-Time Miro Clone Built With Nextjs, React, Covex, Liveblocks, TypeScript, and Tailwind CSS.

Features:

- 🛠️ Whiteboard from scratch
- 🧰 Toolbar with Text, Shapes, Sticky Notes & Pencil
- 🪄 Layering functionality
- 🎨 Coloring system
- ↩️ Undo & Redo functionality
- ⌨️ Keyboard shortcuts
- 🤝 Real-time collaboration
- 💾 Real-time database
- 🔐 Auth, organisations and invites
- ⭐️ Favoriting functionality
- 🌐 Next.js 14 framework
- 💅 TailwindCSS & ShadcnUI styling

### Prerequisites

**Node version 14.x**

### Cloning the repository


### Install packages

```shell
npm i
```

### Setup .env file

```shell
CONVEX_DEPLOYMENT=dev:<convexProjectId>
NEXT_PUBLIC_CONVEX_URL=https://<convexProjectId>.convex.cloud
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=pk_test_XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
CLERK_SECRET_KEY=sk_test_XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
CLERK_JWT_ISSUER_DOMAIN=https://example-id-0.clerk.accounts.dev
LIVEBLOCKS_SECRET_KEY=sk_dev_XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
```

### Setup Convex

```shell
npx convex dev
```

### Start the app

```shell
npm run dev
```
