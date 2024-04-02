## Next.js Acme App

This is a fully functional demo site that uses all the latest Next.js features.

Among the technologies used to develop the website we have:
Next.js - TypeScript - TailwindCSS - PostgreSQL - clx
heroicons - bcrypt - use-debounce - zod and others;

## Features

### Search box

- The query is made directly by SQL, returning all invoices that contain the text entered, be it name, email, amount, date or status;
- To save resources, the `Debounced` technique was added to the search bar, just 300ms after the user stops typing the query is performed.

### Pagination

### CRUD Invoices

---

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.
