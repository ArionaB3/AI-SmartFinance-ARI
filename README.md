AI-SmartFinance-ARI is a cutting-edge financial advisory tool built with the latest Next.js and TypeScript technologies. This platform empowers users to input their income, expenses, and budgets, offering tailored financial advice based on their individual financial data. Ideal for those eager to explore how AI-driven insights and financial management can be integrated into a Next.js app.

Technologies Used:

Next.js
TypeScript
OpenAI API
Tailwind CSS
Key Features:

Users can input their income and expenses.
Efficient budget management tools.
Personalized financial advice, powered by OpenAI's GPT-4, based on the user's financial data.
A smooth experience across all devices.
Steps to Set Up:

Ensure you have the following installed:
Git
Node.js
npm

Install the project dependencies:
npm install

Create a .env file at the root of your project with the following contents:
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=p
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/
NEXT_PUBLIC_OPENAI_API_KEY=

NEXT_PUBLIC_DATABASE_URL=

Replace placeholder values with your actual OpenAI credentials.
Open your browser and go to http://localhost:3000 to view the project.

