
Tech Stack

- Next.js
- MongoDB
- NextAuth
- TailwindCSS

Prerequisites

Make sure you have the following installed on your machine:

- Git
- Node.js(latest)
- npm(latest)

Cloning the Repository

git clone https://github.com/arnav2000agr/Next_prompt.git


Installation

Install the project dependencies using npm:


npm install


Set Up Environment Variables

Create a new file named .env in the root of your project and add the following content:


NEXTAUTH_URL=http://localhost:3000 \
NEXTAUTH_URL_INTERNAL=http://localhost:3000 \
NEXTAUTH_SECRET=\
GOOGLE_ID=\
GOOGLE_CLIENT_SECRET=\
MONGODB_URI=\

for nextauth secret [Cryptpool](https://www.cryptool.org/en/cto/openssl) can be used

for google_id and google_client_secret please configure google oauth 2.0.

Replace the placeholder values with your actual credentials.

Running the Project

npm run dev

Open [http://localhost:3000] to view the project.



