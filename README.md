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

Run the Development Server
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev


Open http://localhost:3000
 in your browser to see the app in action.

You can start editing the pages and components inside the app and components directories. The app will auto-update as you save changes.

Environment Variables

Create a .env file in the root directory and add the following variables:

DATABASE_URL=your_database_connection_string
NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_SECRET=your_nextauth_secret
STRIPE_SECRET_KEY=your_stripe_secret_key


Replace the placeholders with your own credentials.

Learn More

To learn more about the technologies used in this project:

Next.js Documentation
 - learn about Next.js features and API

React Documentation
 - for building UI components

Stripe API
 - for secure payment integration

Deploy on Vercel

The easiest way to deploy your Online Art Marketplace is using the Vercel platform, the creators of Next.js.

Fork or clone the repo.

Connect the repo to Vercel
.

Add your environment variables in the Vercel dashboard.

Deploy! Your app will be live at your-project-name.vercel.app.

Check out the Next.js deployment documentation
 for more details.
