# Structuring the Project

Once we already created our application on the Azure Portal, we can start to code our application. In this tutorial we will use Next.js. But you can use any other framework you want. Let's install the Next.js framework!

Open your terminal and run the following command:

```bash
npx create-next-app reminder-app --typescript 
```

Now we already have our application created, let's execute it to see if everything is working.

```bash
cd auth-app
```

```bash
npm run dev
```

Open the browser and go to the following address: `http://localhost:3000`.

Now we need to install some dependencies. And one of them is the **[Microsoft Graph Client](https://learn.microsoft.com/en-us/graph/sdks/create-client?tabs=Javascript)**. To install it, run the following command:

```bash
npm install @microsoft/microsoft-graph-client
```

If you want to know more about the Microsoft Graph Client, you can read the documentation **[HERE](https://docs.microsoft.com/en-us/graph/sdks/sdks-overview)**. And also, know about the NPM package **[HERE](https://www.npmjs.com/package/@microsoft/microsoft-graph-client)**.

Another package we will need to install is NextAuth. It is a library that helps us to integrate authentication login sessions with Next.js. To install it, run the following command:

```bash
npm install next-auth
```

Also, if you want to know more about NextAuth, you can read the documentation **[HERE](https://next-auth.js.org/)**. And also, know about the NPM package **[HERE](https://www.npmjs.com/package/next-auth)**.

Now we can finally start to create some components for our application. But we will do that in the next section.

**[⬅️ Back: Session 02](./02-session.md)**
| **[Next: Session 04 ➡️](./04-session.md)**
