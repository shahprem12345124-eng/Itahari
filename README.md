# Next.js client

This JavaScript App Router frontend belongs to the [Itahari Citizen Service Portal](../README.md).

Run `npm install` and `npm run dev` in this directory. The Express API defaults to `http://localhost:5000/api`; set `NEXT_PUBLIC_API_URL` in `.env.local` to override it.

The canonical site URL, metadata, and sitemap default to `https://itahari.vercel.app`. Set `NEXT_PUBLIC_SITE_URL` at build time if the production domain changes.

Citizens can track a submitted complaint using its reference number. Administrators can update complaint status and manage tourist places; managed places appear alongside the curated tourist listings.
