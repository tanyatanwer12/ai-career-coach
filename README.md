🚀 AI Career Coach
An AI-powered platform to help users choose and succeed in their ideal career paths.

🔧 Tech Stack
Next.js 14 with App Router

Tailwind CSS

Shadcn/ui

Clerk Authentication

Neon DB (PostgreSQL)

Google Gemini API

🛠️ Getting Started
Clone the repository:

bash
Copy
Edit
git clone https://github.com/tanyatanwer12/ai-career-coach.git
cd ai-career-coach
npm install
🔐 Create a .env file
ini
Copy
Edit
DATABASE_URL=your_postgresql_connection_url

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=your_gemini_api_key
📦 Run Locally
bash
Copy
Edit
npm run dev
Visit http://localhost:3000

✅ Features
Career path recommendation

Resume analyzer with AI feedback

Authentication and user onboarding

Modern, responsive UI

🙌 Author
Customized and maintained by tanyatanwer12

