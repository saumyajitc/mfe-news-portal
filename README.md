# Micro Frontend with Vite

This repository is linked to this article [MFE](https://dev.to/mairouche/setup-a-micro-frontend-architecture-in-15min-with-vite-4pbg).
The `host/` folder contains the Micro Frontend Shell with Vite Vanilla.
The `apps/` folder contains the microfrotends modules (angular is not working at this stage but will be added in a later commit).

To start the application, follow the steps.

## Step 1 : Build the Vue Header micro frontend

```bash
cd apps/header
npm install
npm run build
```

## Step 2 : Build the React Trending micro frontend

```bash
cd apps/trending
npm install
npm run build
```

## Step 3 : Build and run the Shell

```bash
cd host
npm install
npm run dev
```

Finally, you'll be able to see our micro frontend overall application on http://localhost:3000/
