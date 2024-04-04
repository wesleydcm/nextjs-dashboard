## Next.js Acme App

This is a fully functional demo site that uses all the latest Next.js features.

Among the technologies used to develop the website we have:

Next.js - TypeScript - TailwindCSS - PostgreSQL - clx - heroicons - bcrypt - use-debounce - zod and others;

#### To access the application dashboard, use the following credentials:

```
    Email: user@nextmail.com
    Password: 123456
```

> [Open Acme App](https://nextjs-dashboard-six-roan-85.vercel.app/dashboard)

## Features

### Search box

- The query is made directly by SQL, returning all invoices that contain the text entered, be it name, email, amount, date or status;
- To save resources, the `Debounced` technique was added to the search bar, just 300ms after the user stops typing the query is performed.

### Pagination

- Search and pagination using URL search parameters: `searchParams`, `usePathname` and `useRouter`.

### CRUD Invoices

- Revalidate client cache using `revalidatePath` API after database change.

### Error Handling

- Detect errors in your route segments and show a replacement UI to the user.
- `notFound` function and file not found to handle 404 errors (for resources that don't exist).

### Accessibility

- `eslint-plugin-jsx-a11y` with Next.js to implement accessibility best practices.
- Server-side form validation.
- Use of the React `useFormState` hook to handle form errors, and display them to the user.

### Authentication

- Authentication to app using NextAuth.js.
- Use of Middleware to redirect users and protect their routes.
- Use of React's `useFormStatus` and `useFormState` to handle pending states and form errors.

### Metadata

- Use of metadata to enhance web page indexing, using Open Graph Metadata, Description, Keywords and others.

---

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.
