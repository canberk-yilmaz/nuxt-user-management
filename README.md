# Nuxt 3 Supabase Exercises

## This example provides the steps to build a basic user management app. It includes:

- Supabase Database: a Postgres database for storing your user data.
- Supabase Auth: users can sign in with magic links (no passwords, only email).
- Supabase Storage: users can upload a photo.
- Row Level Security: data is protected so that individuals can only access their own data.
- Instant APIs: APIs will be automatically generated when you create your database tables.

## Setup

Make sure to install the dependencies:

```bash
# yarn
yarn install

# npm
npm install

# pnpm
pnpm install --shamefully-hoist
```

## Development Server

Start the development server on http://localhost:3000

```bash
npm run dev
```

## Production

Build the application for production:

```bash
npm run build
```

Locally preview production build:

```bash
npm run preview
```

Check out the [deployment documentation](https://nuxt.com/docs/getting-started/deployment) for more information.
