## Instant Vanilla

Template for getting a live Instant project running with vailla Typescript, HTML, and CSS.

![](https://i.imgur.com/6Uepoig.png)

## Quick Start
Walk through the deployment process below and you should see a live todo app up
and running!

**1. Deploy to Vercel**

Press the button below to clone this repository and deploy it to Vercel.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fnezaj%2Finstant-vanilla-template)

**2. Make a new app on Instant**

The first thing you'll notice in the live app is that we need to update the `APP_ID`. Let's go to the Instant dashboard
and create a new app. [Instant Dashboard](https://instantdb.com/dash)

**3. Update your repo with the new `APP_ID`**

Let's clone our repository to our local machine, install the dependencies
update the `APP_ID`, verify that the app is working locally, and then deploy it to Vercel!

```bash
git clone <YOUR_REPO_NAME> <YOUR_APP_NAME>
cd <YOUR_APP_NAME>
npm i
npm run dev
```

Update the `APP_ID` in `src/main.ts` and hit save. If all looks good let's deploy it to Vercel!

```bash
git add .
git commit -m "Update APP_ID"
git push origin main
```

Huzzah! You've got the app up and running. Now go forth and build something
people want :)

