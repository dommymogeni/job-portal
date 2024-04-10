This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## getting started

download the repository or clone the repository from github

```bash
git clone https://github.com/dommymogeni/job-portal.git
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Deployment on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

## database setup using prisma

```bash
npx prisma db push # creating the tales in the database
npx prisma generate #generating a prisma client
npx prisma migrate dev #generating a migration for the database
```

## Pusing the changes made to github account

```bash
git add .
git commit -m "updated"
git push
```
