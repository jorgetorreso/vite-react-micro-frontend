# vite-react-micro-frontend

Vite React Micro-Frontend

**Feature**
 ☀️ Micro FrontEnd using  vite-plugin-federation  🔥
 ☀️ Monorepo using pnpm 🔥
 ☀️ Develop & build using vite 🔥
 ☀️ Support React.js 🔥
 ☀️ Auto develop and build commands. 🔥

 ## Feature

-   [x] Micro Front End using [vite-plugin-federation](https://github.com/originjs/vite-plugin-federation) 🔥
-   [x] Monorepo using [pnpm](https://pnpm.io/) 🔥
-   [x] Develop & build using [vite](https://vitejs.dev/) 🔥
-   [x] Support [React.js](https://reactjs.org/) typescript frameworks
-   [x] Auto develop and build commands.

## Architecture

Application list:

-   **packages/main**: The main application
-   **packages/subapp1**: The child application
-   **packages/subapp2**: The child application using React.js

## Usage

1. Clone project:

```shell
git clone https://github.com/jorgetorreso/vite-react-micro-frontend.git
```

2. Install dependencies:

```shell
pnpm i
```

3. Start develop:

```shell
pnpm run dev
```

Now you can access by `http://localhost:5000`.

Develop for single application:

```shell
pnpm run dev --app main
```

1. Build:

```shell
pnpm run build

# or build for single application
pnpm run build --app main
```

## License

MIT License

Copyright (c) 2023 Jorge Torres
