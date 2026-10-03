# This is my website

It was developed with Astro, hosted at GitHub and deployed by Vercel

### [Go To site](https://www.ferfalcon.com)

## Local development

The front-page redesign is developed on the `redesign` branch.

```sh
npm ci
npm run dev
```

Open `http://localhost:4321`. Run `npm run build` to validate the production build, and `npm run preview` to serve it locally.

The site is static and needs no environment variables. Fonts are self-hosted in `public/fonts` with their licenses. Portfolio images are extracted from the supplied Figma portfolio; their origins are recorded in `public/images/work/SOURCES.md`.

`PRODUCT.md` records the audience and content constraints. `DESIGN.md` records the implemented design system.

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```
