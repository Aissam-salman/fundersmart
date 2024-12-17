# FunderSmart

A full-stack application with Flutter mobile app, React TypeScript web client, and NestJS backend, powered by Supabase database.

## Project Structure

```

## Tech Stack

### Mobile App (Flutter)
- Flutter SDK
- Dart programming language
- State management (TBD)
- Native Android & iOS support

### Web Client (React)
- React
- TypeScript
- Modern tooling with Vite
- Type-safe development

### Backend (NestJS)
- NestJS framework
- TypeScript
- RESTful API
- JWT Authentication

### Database
- Supabase
- PostgreSQL
- Real-time capabilities
- Built-in authentication

## Getting Started

### Prerequisites
- Node.js (v16 or higher)
- Flutter SDK
- pnpm (for server dependencies)
- pnpm (for web client)
- Supabase account

### Server Setup
```bash
cd server
pnpm install
pnpm run start:dev
```

### Web Client Setup
```bash
cd client/web
npm install
npm run dev
```

### Mobile App Setup
```bash
cd client/mobile
flutter pub get
flutter run
```

## Environment Setup

### Server
Create a `.env` file in the server directory:
```
DATABASE_URL=your_supabase_url
SUPABASE_KEY=your_supabase_key
PORT=3000
```

### Web Client
Create a `.env` file in the client/web directory:
```
VITE_API_URL=http://localhost:3000
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

### Mobile Client
Create a `.env` file in the client/mobile directory:
```
API_URL=http://localhost:3000
SUPABASE_URL=your_supabase_url
SUPABASE_ANON_KEY=your_supabase_anon_key
```

## Development

### Running Tests
- Server: `cd server && pnpm test`
- Web: `cd client/web && npm test`
- Mobile: `cd client/mobile && flutter test`

### Code Style
- Server: Uses ESLint and Prettier
- Web: Uses ESLint and Prettier
- Mobile: Follows Flutter/Dart conventions

## Deployment

### Server
- Deploy to your preferred hosting service (AWS, DigitalOcean, Heroku, etc.)
- Set up environment variables
- Configure production database

### Web Client
- Build the production version: `pnpm run build`
- Deploy to hosting service (Vercel, Netlify, etc.)

### Mobile App
- Generate release builds for Android and iOS
- Deploy to respective app stores


## License
This project is licensed under the MIT License - see the LICENSE file for details

## Contact
Aissam Lamjadab - aissam.lamjadab@gmail.com
Project Link: [https://github.com/yourusername/fundersmart](https://github.com/yourusername/fundersmart)
