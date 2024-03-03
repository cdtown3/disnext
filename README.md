# DisNext
**DisNext** is a Discord-inspired chat application built with Next.js and Clerk (Clerk.Dev) for authentication. This project showcases a modern approach to building real-time chat applications using server-rendered React components and a secure, easy-to-integrate authentication solution. This project is initially based on: https://www.youtube.com/watch?v=ZbX4Ok9YX94&t=4573s

## Tech Stack:

**Frontend:** Next.js, shadcn-ui  
**Authentication:** Clerk.dev  
**Databases:** MySQL via PlanetScale, Prisma ORM

## Getting Started:
### Clone the repository:
**Bash:**  
`git clone https://github.com/your-username/disnext.git`

### Install dependencies:
**Bash:**  
`cd disnext`  
`npm install`

### Configure Clerk:
Create a Clerk account and project at https://clerk.com/.
Follow Clerk's setup guide to integrate with your Next.js application.
Place your Clerk API keys in the .env file

### Start the development server:
**Bash:**  
`npm run dev`

### Start Prisma studio:
**Bash:**
`npx prisma studio`