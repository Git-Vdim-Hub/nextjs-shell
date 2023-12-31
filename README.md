This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started
Pre-reqs:
-Make sure you have nodejs installed (Node)[https://nodejs.org/en]
-Make sure you have MongoDB installed: (MongoDB)[https://coding-boot-camp.github.io/full-stack/mongodb/how-to-install-mongodb]
-I recommend gitbash as well, but you can do without it. If interested, install (GitBash)[https://git-scm.com/downloads]



Then, to run the app, first, install dependencies:

```bash
npm install
# or
yarn install
# or
pnpm install
```

Then, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```
Since this framework is using Apollo/GraphQL, you will need to add a user in order to read the backend output. Open the graphQL server [http://localhost:3000/api/graphql](http://localhost:3000/api/graphql)

Follow apollo steps for a mutation and create a new user. You will need to add the user to the database manually.(GraphQL/Apollo How To)[https://coding-boot-camp.github.io/full-stack/apis/graphql-playground-guide]

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result. You should see Helloo !! as the very top, followed by an output of the user you created..

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
