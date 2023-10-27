# NoteDrop: ( Full stack Notion Clone | Next.js 13/React, TypeScript, Convex, Tailwind )

![NoteDrop Home Page](https://i.imgur.com/Z00lnwi.png)
![NoteDrop Note Editor](https://i.imgur.com/DVh5vqm.png)
---

Features:

- Notion-style editor 📝 
- Light and Dark mode 🌓
- Trash can & soft delete 🗑️
- Authentication using clerk 🔐 
- Real-time database using convex 🔗 
- Image upload/delete/update 🖼️
- Icons that changes in real-time 🌠
- Publishing note to the web 🌐

What's Next? 🚀

- 🤖 Implement AI-powered autocomplete (like Notion AI)
- 📅 Add a calendar and scheduling functionality to manage events and deadlines.
- 📚 Develop a collaborative real-time editing feature for team projects.
- 📤 Implement export options for sharing notes in various formats.
- 📁 Create a file attachment feature to enhance document handling.
- 🌐 Support multiple languages and regions.


---
### Cloning the repository

```shell
git clone https://github.com/dontdude/NoteDrop.git
```

### Install packages

```shell
npm i
```

### Setup .env file


```js
# Deployment used by `npx convex dev`
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

EDGE_STORE_ACCESS_KEY=
EDGE_STORE_SECRET_KEY=
```

### Setup Convex

```shell
npx convex dev

```

### Start the app

```shell
npm run dev
```
