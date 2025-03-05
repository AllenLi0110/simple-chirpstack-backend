# Simple ChirpStack Backend

A simple backend application for interacting with ChirpStack, a LoRaWAN Network Server. This project provides a clean and user-friendly interface for managing devices and networks.

## Folder Structure

```
// simple-chirpstack-backend
├── .github
|  └── workflows
├── .projen
├── src
|  ├── apps
|  ├── collections
|  ├── definitions
|  ├── exceptions
|  ├── helpers
|  ├── middlewares
|  ├── models
|  ├── repositories
|  ├── requests
|  ├── responses
|  ├── validators
|  |  └── resources
|  |  └── schemas
|  └── index.ts
├── .prettierrc
├── .projenrc.ts
├── esbuild.mjs
├── package.json
└── README.md
```

## Installation

1. Clone the repository:

```
git clone https://github.com/yourusername/simple-chirpstack-backend.git
```

2. Navigate into the project folder:

```
cd simple-chirpstack-backend
```

3. Install dependencies:

```
npm install
```

4. Run the development server:

```
npx projen
npm run dev
```

5. Open the app in your browser at http://localhost:8080.
