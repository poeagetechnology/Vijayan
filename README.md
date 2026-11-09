# Vijayan Theatre — Booking & Management Website

A responsive single-theatre website starter built with React, Vite and Tailwind CSS.

## Included
- Public home page and movie catalogue
- Movie details, showtimes and ticket prices
- Interactive 6-row / 8-seat seat picker
- Customer booking form and confirmation ticket
- Management dashboard with booking list, revenue summary, cancellation, movie catalogue and showtime management
- Browser localStorage persistence for demo data
- Responsive layout for desktop and mobile

## Run locally
Requires Node.js 20.19+ or 22.12+.

```bash
npm install
npm run dev
```

Open the local URL printed by Vite.

## Production build

```bash
npm run build
npm run preview
```

Upload the generated `dist/` folder to a static host, or deploy the project to Vercel.

## Important demo limitations
- This starter uses browser localStorage. It is not a shared multi-device database.
- No payment gateway, SMS, WhatsApp, email delivery, authentication, or server-side seat locking is connected.
- The management page is a demo interface and has no administrator login. Add secure authentication before public production use.
- Movie posters are remote sample images. Replace them with licensed theatre/movie artwork.
- Update theatre address, contact details, real show dates, showtimes, prices and seat layout before launch.

## Suggested production architecture
For live customer bookings, connect a backend such as Node.js/Express or Supabase/Firebase with a database. Enforce seat availability and booking transactions on the server, add admin authentication and connect a payment provider before accepting real payments.
