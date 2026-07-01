# VitTube

![Express](https://img.shields.io/badge/Express-000000.svg?style=flat-square&logo=Express&logoColor=white)  ![JSON](https://img.shields.io/badge/JSON-000000.svg?style=flat-square&logo=JSON&logoColor=white)  ![npm](https://img.shields.io/badge/npm-CB3837.svg?style=flat-square&logo=npm&logoColor=white)  ![Mongoose](https://img.shields.io/badge/Mongoose-F04D35.svg?style=flat-square&logo=Mongoose&logoColor=white)  ![Firebase](https://img.shields.io/badge/Firebase-DD2C00.svg?style=flat-square&logo=Firebase&logoColor=white)  ![.ENV](https://img.shields.io/badge/.ENV-ECD53F.svg?style=flat-square&logo=dotenv&logoColor=black)  ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=flat-square&logo=JavaScript&logoColor=black)  ![Nodemon](https://img.shields.io/badge/Nodemon-76D04B.svg?style=flat-square&logo=Nodemon&logoColor=white)  ![React](https://img.shields.io/badge/React-61DAFB.svg?style=flat-square&logo=React&logoColor=black)  ![Docker](https://img.shields.io/badge/Docker-2496ED.svg?style=flat-square&logo=Docker&logoColor=white)  ![Axios](https://img.shields.io/badge/Axios-5A29E4.svg?style=flat-square&logo=Axios&logoColor=white)  ![styledcomponents](https://img.shields.io/badge/styledcomponents-DB7093.svg?style=flat-square&logo=styled-components&logoColor=white)

## Overview

VitTube is a video hosting web application. The frontend is built with React, Redux Toolkit for state management, and Material UI for components. An API key stored in client-side environment variables connects the interface to backend media services.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [License](#license)

---

## Features

|      | Component         | Details                                                                                                                                                                                                                                                                      |
| :--- | :---------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ⚙️  | **Architecture**  | <ul><li>Full-stack **MERN** app (MongoDB, Express, React, Node.js)</li><li>Clear `client/` + `server/` monorepo split</li><li>REST API backend via `express`</li><li>Client-side SPA routing via `react-router-dom`</li><li>Global state managed with `@reduxjs/toolkit` + `redux-persist`</li></ul> |
| 🔩 | **Code Quality**  | <ul><li>Component-based React architecture using `.jsx` files</li><li>Styling via `styled-components` and `@mui/material` for consistent UI patterns</li><li>Environment configs isolated in `client/.env` and `server/.env`</li><li>`cross-env` used for cross-platform env variable handling</li></ul> |
| 📄 | **Documentation** | <ul><li>Environment variable setup documented via `client/.env` and `server/.env` templates</li><li>`package.json` scripts serve as implicit run/build documentation</li><li>No dedicated docs folder or wiki detected</li></ul> |
| 🔌 | **Integrations**  | <ul><li>**Firebase** — likely used for media storage or authentication</li><li>**MongoDB** via `mongoose` ODM for data persistence</li><li>**Axios** for HTTP client requests from React to Express API</li><li>`timeago.js` for human-readable timestamps (e.g., *"3 hours ago"*)</li></ul> |
| 🧩 | **Modularity**    | <ul><li>Decoupled frontend/backend — independently runnable via separate `package.json` files</li><li>Redux slices via `@reduxjs/toolkit` encourage modular state management</li><li>MUI + Emotion theming (`@emotion/react`, `@emotion/styled`) supports reusable UI components</li></ul> |

---

## Project Structure

```
└── VitTube/
    ├── client
    │   ├── .env
    ├── LICENSE
    ├── README.md
    └── server
        ├── .env
        ├── controllers
        ├── error.js
        ├── index.js
        ├── models
        ├── package-lock.json
        ├── package.json
        ├── routes
        └── verifyToken.js
```

---

## Getting Started

### Prerequisites

- Python 3.10+ / Node.js 18+ *(depending on the stack above)*

### Installation

```sh
git clone "https://github.com/IlluzyonistCode/VitTube
cd VitTube"
npm install
```

### Usage

```sh
npm start
```

---

## Contributing

- [Report Issues](https://github.com/IlluzyonistCode/VitTube/issues)
- [Submit Pull Requests](https://github.com/IlluzyonistCode/VitTube/pulls)
- [Discussions](https://github.com/IlluzyonistCode/VitTube/discussions)

---

## License

Distributed under the [AGPL-3.0](LICENSE) license.
