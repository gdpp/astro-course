# Pokemon Static

This is a very interesting section because we will learn to create pages by advanced for our static website, this includes functionalities as: 

-   Animations between screens
-   Generation of 151 pages at construction time
-   Reading dynamic arguments by URL
-   Name Transitions
-   Conditional style
-   TypeScript Path alias
-   Interfaces and typing
-   Basic metatags for SEO (title, description and image)
-   Tests when sharing links on social networks

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
├── src/
│   └── components/
│       └── PokemonCard.astro
│   └── layouts/
│       └── BaseLayout.astro
│   └── pages/
│       └── pokemons/
│           └── [name].astro
│           └── [page].astro        
│       └── index.astro
│   └── styles/
│       └── global.css
└── package.json
```

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command           | Action                                       |
| :---------------- | :------------------------------------------- |
| `pnpm dev`        | Starts local dev server at `localhost:4321`  |
| `pnpm build`      | Build your production site to `./dist/`      |
| `pnpm run preview` | Preview your build locally, before deploying |