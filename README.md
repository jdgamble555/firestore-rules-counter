# Firestore Rules Counter - Todo App Example

1. Add .env file with:
```
PUBLIC_FIREBASE_CONFIG={YOUR FIREBASE CONFIG}
```
Make sure the keys are in quotes!

You could also just use test config data if you just want to use the emulator:
```
PUBLIC_FIREBASE_CONFIG={"projectId":"test","appId":"test","apiKey":"test"}
```

2. Install Firebase Globally
```
npm i -g firebase-tools
```  

3. Install [Java SDK](https://www.oracle.com/java/technologies/downloads/)

4. Run firebase emulators:
```
firebase emulators:start
```

5. Run svelte in new terminal window.
```
npm i
```
```
npm run dev
```

___

Read more at Code.Build:  
[Firestore Secure Batch Increment](https://code.build/p/firestore-secure-batch-increment-IKO13Z)


___
# create-svelte

Everything you need to build a Svelte project, powered by [`create-svelte`](https://github.com/sveltejs/kit/tree/main/packages/create-svelte).

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

```bash
# create a new project in the current directory
npm create svelte@latest

# create a new project in my-app
npm create svelte@latest my-app
```

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.
