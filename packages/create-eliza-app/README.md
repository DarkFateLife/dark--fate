# create-darkfate-app

A minimal CLI tool to scaffold ELIZA applications with zero configuration. Get started building your own ELIZA-style chatbot in seconds.

<!-- automd:badges color="yellow" license name="create-darkfate-app" codecov bundlephobia packagephobia -->

[![npm version](https://img.shields.io/npm/v/create-darkfate-app?color=yellow)](https://npmjs.com/package/create-darkfate-app)
[![npm downloads](https://img.shields.io/npm/dm/create-darkfate-app?color=yellow)](https://npm.chart.dev/create-darkfate-app)
[![bundle size](https://img.shields.io/bundlephobia/minzip/create-darkfate-app?color=yellow)](https://bundlephobia.com/package/create-darkfate-app)

<!-- /automd -->

## Usage

You can create a new ELIZA app with your preferred package manager:

<!-- automd:pm-x version="latest" name="create-darkfate-app" args="path" <flags>" -->

```sh
# npm
npx create-darkfate-app@latest path

# pnpm
pnpm dlx create-darkfate-app@latest path

# bun
bunx create-darkfate-app@latest path

# deno
deno run -A npm:create-darkfate-app@latest path
```

<!-- /automd -->

## Command Line Arguments

-   `--name`: Name of the template to use (default: "darkfate")
-   `--dir`: Directory where the project will be created (default: current directory)
-   `--registry`: Custom registry URL for templates

## Getting Started

Once your project is created:

1. Navigate to the project directory:

    ```bash
    cd your-project-name
    ```

2. Copy the example environment file:

    ```bash
    cp .env.example .env
    ```

3. Install dependencies:

    ```bash
    pnpm install
    ```

4. Start the development server:
    ```bash
    pnpm start
    ```

<!-- automd:with-automd -->

---

_🤖 auto updated with [automd](https://automd.unjs.io)_

<!-- /automd -->
