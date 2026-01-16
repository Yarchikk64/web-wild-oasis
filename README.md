- Features
User authentication (NextAuth);
Browse cabins and view detailed information;
Book cabins with date selection;
Edit and delete bookings;
User profile page;
Country selection;
Server Actions and API routes;
Global state management with Context API;
Loading / error / not-found pages;


- Tech Stack
Next.js (App Router)
React
Supabase — database and backend
NextAuth — authentication
Tailwind CSS — styling
Server Actions
Context API

- Architecture
Built with Next.js App Router
Clear separation of concerns:
  app/_components — reusable UI components
  app/_lib — data fetching, auth, Supabase logic
  app/api — server routes
Focus on readability, scalability, and real-world workflow

- Project Goal
This project was created to:
  practice Next.js + React on a real-world use case
  understand full-stack application architecture
  work with authentication and databases
  prepare for real commercial development

⚙️ Installation & Setup

Clone the repository:
Install dependencies: npm install
Create a .env.local file and add your Supabase credentials: 

NEXT_PUBLIC_SUPABASE_URL=https://ttnyzofvjpreoetukrhm.supabase.co
NEXT_PUBLIC_SUPABASE_ANON_KEY=sb_publishable_7buwp7ipNyyd8ElVMUYL0A_w40BqjDv
NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_SECRET=AE9G1ZX+Ra7ow+QXWGjvdkNzat4loMDDakFwV4PomVA=
AUTH_GOOGLE_ID=181068537742-jqe0vqp6nds9jk8vbvmrmqrf2ko117sc.apps.googleusercontent.com
AUTH_GOOGLE_SECRET=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

Run the development server: npm run dev
