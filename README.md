# The Wild Oasis: Customer Booking Website

A full-stack web application for guests to browse, search, and book luxury resort cabins online.

## What This Project Does

- Guests can view cabin listings, filter by capacity, and check real-time availability.
- Secure user authentication powered by Google and Supabase.
- Guests can make cabin reservations, pick stay dates, and manage their profile details.
- Guests can view, update, or cancel their upcoming reservations directly from their user dashboard.
- Responsive design optimized for mobile devices, tablets, and desktop screens.

## Tech Stack

- **Framework**: Next.js 14 (App Router) and React 19
- **Backend & Database**: Supabase (Authentication, PostgreSQL Database, and Storage)
- **Styling**: Tailwind CSS
- **Icons & UI**: Heroicons and React Day Picker
- **Data Handling**: Next.js Server Actions and Server Components

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/Bhavyajain14/the-wild-oasis-website.git
   cd the-wild-oasis-website
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Configure environment variables in a `.env.local` file:
   ```env
   NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
   NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
   ```

4. Run the development server:
   ```bash
   npm run dev
   ```

5. Open `http://localhost:3000` in your browser.
