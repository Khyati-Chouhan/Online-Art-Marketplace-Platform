# Online Art Marketplace Platform

A **full-stack marketplace** for artists to showcase and sell artworks. This platform supports **secure payments**, **user authentication**, **role-based access**, and a **responsive, mobile-first UI** capable of handling 500+ concurrent users.

Built with a modern stack to deliver a seamless experience for both artists and buyers.

---

## Features

- Artist and buyer user roles with role-based access control
- Secure authentication and authorization
- Artworks listing, search, and filtering
- Shopping cart and checkout with secure payment integration
- Responsive, mobile-first design
- Scalable backend to support high concurrency

---

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/Khyati-Chouhan/Online-Art-Marketplace-Platform.git
cd Online-Art-Marketplace-Platform
Install Dependencies
npm install
# or
yarn install
# or
pnpm install
```

### Run the Development Server
```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open http://localhost:3000
 in your browser to see the app in action.

You can start editing the pages and components inside the app and components directories. The app will auto-update as you save changes.

Environment Variables

Create a .env file in the root directory and add the following variables:
```.env
DATABASE_URL=your_database_connection_string
NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_SECRET=your_nextauth_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
```

Replace the placeholders with your own credentials.


## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com) from the creators of Next.js.
Deploy! Your app will be live at your-project-name.vercel.app.




