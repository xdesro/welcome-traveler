![](https://repository-images.githubusercontent.com/437614112/87dd2537-9082-4931-b84d-78bcfa5a7512)
# ⚔️ Welcome, Traveler

_This is a rather curious and a very respectable eleventy starter project._ It came into existence because I do exactly the same setup for like, 90% of my web projects these days. It has some opinions but hopefully very few, and there's reasoning behind them.

The template ships with the following features:

- **An `eleventy-plugin-vue` installation to allow for Vue templating.** This uses Vue server-side rendering functionality, so in true 11ty spirit, only compiled HTML and no run-time Vue will hit the client side. I just like Vue's template syntax. You can learn more about how to use the plugin on the [GitHub repo page](https://github.com/11ty/eleventy-plugin-vue/). Also if you like it, you can sponsor its development and the hard work that goes into the entire 11ty ecosystem by [sending Zach your money](https://github.com/sponsors/zachleat).

- **SCSS compiling for stylesheets.** I'm using the `sass` CLI here, it's the most minimalistic approach I've seen. I use Sass because it allows for very easy componentization and tokenization of style code — you can build your design system without any client-side increase in code.

That's like it actually lol, there's not a lot. There's an `.nvmrc` file if you use NVM, and there are some directories in `src` for fonts/meta/images/templates/data. There's a global `layout.html`, and `.vue` files added to `src` will be built as pages with that as a wrapper.

Godspeed and good luck, traveler.

## Getting Started

This guide assumes you have Node and NPM installed.

1. 📦 **Install dependencies**.

   ```sh
   npm i
   ```

2. 🚧 **Run for local development.** Kicks off a hot-reloading server at `localhost:8080`.

   ```sh
   npm run start
   ```

3. 🛳 **Build for deployment.** Serves from `dist/` directory.

   ```sh
   npm run build
   ```
