
 ##  👷🛠️ under construction  👷🏗️

# Evently - A Next.js MERN Events App 

_This project has copyright by JavaScript Mastery(https://github.com/adrianhajdin/event_platform). This repository is made for studying MERN._

**Evently** is a Next.js 14-based events app manages global events, allowing ticket purchases via Stripe and enabling users to create their own events.
## How to use

**Cloning the repository**
```
git clone https://github.com/talhacetin01/evently.git
cd evently
```
**Installation**
```
npm install
```
***You should replace the environment variables with your own in the .env.local***
```
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

MONGODB_URI=
WEBHOOK_SECRET=
UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=
```
**Then simply run ``npm run dev``**

Open ``http://localhost:3000`` to view the project.

**If you do not want to bother with downloading the project, you can view the demo by visiting this site:**

https://evently-wine-iota.vercel.app/
