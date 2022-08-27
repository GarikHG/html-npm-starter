Create new Bootstrap-powered npm projects in no time.

## About
`html-npm-starter` is a GitHub template repository for creating new Bootstrap-powered npm projects. 
You can also use it as your own Bootstrap prototyping sandbox. It's built with Bootstrap v5.2 with plans to update.

## Repo template
Setup as a starter template, you can easily generate a new GitHub repository. From the repository homepage, 
click the `Use this template` button.

## What's included
* Single HTML page (`index.html`) to demonstrate how to include Bootstrap.
* Includes [Bootstrap](https://getbootstrap.com/) (currently using `v5.2`) source files via npm.
* Includes [Bootstrap Icons](https://icons.getbootstrap.com/) (`v1.9`), which includes over 1,600 icons available as SVGs and web fonts.
* npm scripts (see package.json) for compiling and autoprefixing Sass, watching for changes, and starting a basic local server.
* Example stylesheet (`scss/starter.scss`) highlighting two ways to include and customize Bootstrap.
* Example JavaScript file (`assets/js/starter.js`) showing how to import all of Bootstrap, or just the parts you need.

## Usage npm
Be sure to have [Node.js](https://nodejs.org/en/) installed before proceeding.

``` shell
# Clone the repo:
https://github.com/garikhg/html-npm-starter.git
cd html-npm-starter

# Install dependencies:
npm i

# Compile SASS:
npm run css-compile

# Watch Sass for changes (uses nodemon)
npm run watch

# Start local server (uses sirv-cli)
npm run server

# Watches Sass for changes and starts a local server
npm start
```

For the most straightforward development, open two Terminal tabs to execute npm run server and npm run watch at the same time.

Open http://localhost:3000 to see the page in action.

## Scripts
The following npm scripts are available to you in this starter repo. With the exception of npm start and npm test, the remaining scripts can be run from your command line with npm run script name, for ex. `npm run server`.

| Script name   | Description                                                                         |
|---------------|:------------------------------------------------------------------------------------|
| `server`      | Starts a local server (http://localhost:3000) for development                       |
| `watch`       | Automatically recompiles CSS as it watches the scss directory for changes           |
| `css`         | Runs css-compile and css-prefix                                                     |
| `css-compile` | Compiles source Sass into CSS                                                       |
| `css-lint`    | Runs [Stylelint](https://stylelint.io/) against source Sass for code quality        |
| `css-prefix`  | Runs [Autoprefixer](https://github.com/postcss/autoprefixer) on the compiled CSS    |
| `css-purge`   | Runs [PurgeCSS](https://purgecss.com/) to remove CSS that is unused by `index.html` |
| `test`        | Runs `css-lint` and `css`, in sequential order                                      |

## Copyright
© [@garikhg](https://github.com/garikhg) 2022 and licensed MIT.

