This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

![promptopia](https://github.com/arnaud-vanderschriek/promptAINextJS/assets/52375486/3fcd34ea-5160-467b-932b-22443ad641ef)

![promptopia-createPrompt](https://github.com/arnaud-vanderschriek/promptAINextJS/assets/52375486/a7d5722a-1081-4ce9-a591-0f453abb6770)

![promptopia-updatePrompt](https://github.com/arnaud-vanderschriek/promptAINextJS/assets/52375486/754bcebc-5360-44bd-91c2-d490cbf441c5)

![promptopia-userProfile](https://github.com/arnaud-vanderschriek/promptAINextJS/assets/52375486/19c7cebf-bafe-4cd0-99ea-ea5a570b505f)

## Presentation

This is a presentation web application which is used to show the use of NextJs, an authentication method with Next-Auth, a database with mongoDB. The css was made with Tailwind

The web application is hosted on vercel at the following address: https://prompt-ai-next-js.vercel.app/

## Installation

After cloning the repo, you will need to install the nodes modules with your package manager like npm, yarn or pnpm using the command 
```
npm install 
# or 
npm i
```

You are going to need an .env file oc. 
This file must contain the following variables 

* GOOGLE_CLIENT_ID 
* GOOGLE_CLIENT_SECRET ( given when setup your project on google cloud console )
* MONGODB_URI ( your personal mongoDB )
* NEXTAUTH_URL ( http://localhost:3000 )
* NEXTAUTH_URL_INTERNAL ( http://localhost:3000 )
* NEXTAUTH_SECRET https://next-auth.js.org/configuration/options#nextauth_secret

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
