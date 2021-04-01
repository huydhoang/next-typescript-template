# Next.js TypeScript Template with Auto Code Formatting

## Getting Started

```bash
git clone https://github.com/huydhoang/next-typescript-template.git
cd next-typescript-template
pnpm dev
```

[pnpm](https://pnpm.js.org/) is a cool alternative to `yarn` or `npm` as it is faster and can reuse downloaded packages to reduce the size of `node_modules`.

If you use `yarn`

```bash
yarn dev
```

or `npm`

```bash
npm run dev
```

## Auto Code Formatting

Auto Code Formatting for TypeScript was setup using ESLint and Prettier in VSCode.
Simply turn on `Editor: Format On Save` feature within VSCode and let the magic happen.

`File > Preferences > Search 'Format On Save'`

## References:

https://dev.to/filippofonseca/how-to-set-up-a-next-js-project-with-typescript-and-react-576h

https://jaywolfe.dev/blog/automate-code-cleanliness-in-vscode-with-typescript-eslint-and-prettier/

https://stackoverflow.com/questions/53516594/why-do-i-keep-getting-delete-cr-prettier-prettier

https://qvault.io/clean-code/how-to-get-consistent-line-breaks-in-vs-code-lf-vs-crlf/

---

# Next's Original Readme

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
