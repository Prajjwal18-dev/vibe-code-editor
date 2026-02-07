
## setup prisma and mongo db
npm i prisma --dev
npm i @prisma/client

define the schema in schema.prisma

run the following commands
npx prisma generate
npx prisma db push

## Authentication setup in nextjs
npm i next-auth
npm i @next-auth/mongodb-adapter
writing prisma schema
write config related to auth and middleware
implement google and github oauth
implement utilities for auth
