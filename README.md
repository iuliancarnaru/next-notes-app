Environment variables:

KINDE_CLIENT_ID=#
KINDE_CLIENT_SECRET=#
KINDE_ISSUER_URL=#
KINDE_SITE_URL=http://localhost:3000
KINDE_POST_LOGOUT_REDIRECT_URL=http://localhost:3000
KINDE_POST_LOGIN_REDIRECT_URL=http://localhost:3000/dashboard
DATABASE_URL="postgres://postgres.[host]:[password]@[db]:6543/postgres?pgbouncer=true&connection_limit=1"
DIRECT_URL="postgres://postgres.[host]:[password]@[db]:5432/postgres"
STRIPE_SECRET=#
STRIPE_API_ID=#
STRIPE_WEBHOOK_SECRET=#
PRODUCTION_URL=https://xxx.vercel.app

Prisma commands:

- npx prisma db push
- npx prisma studio

To test webhooks locally install stripe cli.
