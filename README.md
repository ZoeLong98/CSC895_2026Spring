# 895MVP

Basic mobile + backend scaffold.

## Structure

- `mobile`: Expo app
- `server`: NestJS + Prisma + MongoDB

## Mobile

```
cd mobile
npm run start
```

## Server

1. Set `DATABASE_URL` in `server/.env`
2. Generate Prisma client:
   ```
   cd server
   npx prisma generate
   ```
3. Run the API:
   ```
   npm run start:dev
   ```
