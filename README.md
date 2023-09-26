# Bravobnb (Airbnb Clone)

Full-stack Airbnb clone with full-fledged search, listing and booking functionality, and utilising new React server components.

Showcases my ability to build commercial-grade full-stack applications on par with one of the tech industry’s leading web platforms Airbnb.

Tech used: React, TypeScript, Next.js, NextAuth, Tailwind CSS, Prisma, MongoDB, Cloudinary.

## How to run

1. Install dependencies by running 

```bash
npm install
```

2. Set up an account with MongoDB, and Cloudinary. For each of these services, get relevant details required for env variables below.

3. Set up environment variables by creating .env file in root directory, and putting in the following variables

```bash
DATABASE_URL="mongodb+srv://your.mongodb.connection.url"
NEXTAUTH_SECRET="NEXTAUTH_SECRET"
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME="your.cloudinary.key"
```

4. Run in dev, by running the below command, and open [http://localhost:3000](http://localhost:3000) with your browser to see the result.


```bash
npm run dev
```

## Deploy on Vercel

The easiest way to deploy the app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme).

Check out the [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
