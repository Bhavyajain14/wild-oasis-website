# The Wild Oasis: Guest Website

The guest-facing website for The Wild Oasis, a small cabin hotel. Guests browse cabins, filter them by size, and pick dates on a calendar where already booked dates are blocked. Built while learning Next.js and Supabase.

The staff dashboard for the same hotel is in [the-wild-oasis](https://github.com/Bhavyajain14/the-wild-oasis).

## What works

- Cabin list loaded from Supabase, with a filter by guest capacity (small, medium, large) kept in the URL
- Cabin detail pages, pre-built at build time with their own page titles
- Date range picker that disables dates that are already booked
- About page that refreshes its data once a day
- Loading, error and not found pages

## Not built yet

- Google sign-in (the button is there, the login flow is not)
- Saving a reservation, and the guest account pages (reservations list, profile)

## Tech

- Next.js (App Router, server components)
- Supabase (PostgreSQL database and image storage)
- Tailwind CSS, React Day Picker, Heroicons

## Run it

1. Install dependencies:

   ```bash
   npm install
   ```

2. Create a `.env.local` file with your Supabase project values:

   ```env
   SUPABASE_URL=your_supabase_url
   SUPABASE_KEY=your_supabase_anon_key
   ```

3. Start the dev server and open http://localhost:3000:

   ```bash
   npm run dev
   ```
