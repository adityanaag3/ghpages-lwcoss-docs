# Host LWC OSS Apps along with Source Code on GitHub Pages

Sample LWC OSS app along with source code that has been hosted on GitHub pages. 

The build output is stored in the [`docs`](./docs) folder. GitHub pages has been configured to use the `docs` folder on the `main` branch as the source of the site content. This approach allows us to open-source the source code of our app, and also deploy the build output of our app to GitHub pages from a single repo.

## Steps Explained

[Watch this Quick Take](https://www.youtube.com/watch?v=LqPPDyTD67U) to learn about the tweaks you need to make to your code to host your apps along with their source code on GitHub pages.

## Changed files

- [`lwc-services.config.js`](./lwc-services.config.js) to update the build directory and resources
- [`scripts/server.js`](./scripts/server.js) to update the static content directory


## How to run the app locally?

Start simple by running `yarn watch` (or `npm run watch`, if you set up the project with `npm`). This will start the project with a local development server.

The source files are located in the [`src`](./src) folder. All web components are within the [`src/modules`](./src/modules) folder. The folder hierarchy also represents the naming structure of the web components.
