# HomeRent - Indian Home Rental Platform

A modern, full-stack home rental platform built specifically for the Indian market using Next.js, Supabase, and TailwindCSS.

## Features

- 🔍 Advanced property search with filters
- 📱 Responsive design for all devices
- 🔐 Secure authentication with OTP support
- 💬 Real-time chat between renters and owners
- 🗺️ Interactive maps for property locations
- 📸 Image and document upload support
- 👥 Multiple user roles (Owner, Renter, Agent)
- 🔒 Document verification system

## Tech Stack

- **Frontend:** Next.js 14, React, TailwindCSS
- **Backend:** Next.js API Routes
- **Database:** Supabase (PostgreSQL)
- **Authentication:** Supabase Auth
- **Storage:** Supabase Storage
- **Maps:** Mapbox GL
- **Real-time:** Supabase Realtime

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env.local` file in the root directory with the following variables:
   ```
   NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
   NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
   NEXT_PUBLIC_MAPBOX_TOKEN=your_mapbox_token
   ```

4. Run the development server:
   ```bash
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser

## Project Structure

```
src/
├── app/              # Next.js app router pages
├── components/       # Reusable React components
├── lib/             # Utility functions and configurations
├── types/           # TypeScript type definitions
├── hooks/           # Custom React hooks
├── utils/           # Helper functions
└── styles/          # Global styles and Tailwind config
```

## Database Schema

The project uses Supabase with the following main tables:

- `properties`: Property listings
- `users`: User profiles
- `messages`: Chat messages
- `verifications`: Document verification records

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

MIT License - feel free to use this project for your own purposes.
