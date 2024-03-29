## Next.js Acme App

Dashboard application.

## Features

### Search box

- The query is made directly by SQL, returning all invoices that contain the text entered, be it name, email, amount, date or status;
- To save resources, the `Debounced` technique was added to the search bar, just 300ms after the user stops typing the query is performed.

### Pagination

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.
