# Foundations

In this project will have my official introduction to Astro, presentation, and then create my first hello world in astro and another important pieces.
These is the list of topics cover in this project:

-   Syntax
-   Astro components
-   Layouts
-   Styles
-   Navigation between pages
-   Structure
-   Props
-   404 page
-   View transitions introduction
-   Static site to production
-   Web deployment

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── fonts/
├── src/
│   └── components/
│       └── NavBar.astro
│   └── layouts/
│       └── MainLayout.astro
│   └── pages/
│       └── 404.astro
│       └── about.astro
│       └── index.astro
│   └── styles/
│       └── globals.css
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command             | Action                                           |
| :------------------ | :----------------------------------------------- |
| `npm install`       | Installs dependencies                            |
| `npm run dev`       | Starts local dev server at `localhost:4321`      |
| `npm run build`     | Build your production site to `./dist/`          |
| `npm run preview`   | Preview your build locally, before deploying     |
| `npm run astro ...` | Run CLI commands like `astro add`, `astro check` |
