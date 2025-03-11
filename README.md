# nano.

A minimalist web proxy built to be simple yet powerful.

Winner of the 2024 Proxathon.

## Features

-   Minimal design
-   Easy to use
-   Tabbed interface
-   Support for many popular sites

## Setup

> [!TIP]
> Run `pnpm install` to install the required dependencies.

**Start**

Run `pnpm start` to start the server. If no build folder is found, the app will build before starting.

**Build**

Run `pnpm run build` to build the app for production into the `dist` folder.

**Build Static**

Run `pnpm run build-static` to build the app for production into the `dist` folder. This is for static hosting on Github Pages etc. Make sure to change the Wisp server in `/index.html` to an external one.

