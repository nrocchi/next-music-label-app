# Next Music Label Application

Next application for music labels using React, Tailwind, Supabase, PostgreSQL & Stripe.

[Visit the demo here](https://next-music-label-app.vercel.app/)

use [Stripe Testing Cards](https://stripe.com/docs/testing)

## Features

- Tailwind design
- Tailwind animations and transition effects
- Full responsiveness for all devices
- Credential authentication with Supabase
- Github authentication integration
- File and image upload using Supabase storage
- Forms using react-hook-form
- Server error using react-toast
- Audio Player
- Playlists / Liked songs system
- Favorites system
- Song upload
- Stripe integration
- Stripe recurring payment integration
- Cancel Stripe subscriptions

## Installation

**Node version 14.x**

### Cloning the repository

```shell
git clone https://github.com/nrocchi/next-music-label-application.git
```

### Install packages

```shell
npm install
```

### Setup .env file


```js
NEXT_PUBLIC_SUPABASE_URL=
NEXT_PUBLIC_SUPABASE_ANON_KEY=
SUPABASE_SERVICE_ROLE_KEY=

NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
STRIPE_SECRET_KEY=
STRIPE_WEBHOOK_SECRET=
```

### Add SQL Tables
Use `database.sql` file

### Start the app

```shell
npm run dev
```

## Available commands

Running commands with npm `npm run [command]`

| command         | description                              |
| :-------------- | :--------------------------------------- |
| `dev`           | Starts a development instance of the app |

## Contributors

The original author is [Nicolas Rocchi](https://github.com/nrocchi).