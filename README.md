# Observatoire du réseau vélo Île-de-France

This project is the source code for processing and displaying as a website the regional cycle road network of the region Île-de-France.

## Data sources

### Communes

The communes are from https://github.com/gregoiredavid/france-geojson.

### Cycle routes

The routes are provided by the region Île-de-France and completed with [cocarto](https://cocarto.com/) by the team from the [Collectif Vélo Île-de-France](https://velo-iledefrance.fr).

### Map

The map data are from [OpenStreetMap contributors](https://openstreetmap.org/) through [MapTiler](https://www.maptiler.com/).

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
