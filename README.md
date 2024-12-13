# TS Starter Config

This project provides a simple starter configuration for building applications in TypeScript. It includes scripts for development and production, a basic folder structure, and commonly used dependencies.

---

## Features

- TypeScript setup with strict mode enabled.
- Nodemon for live reload during development.
- Scripts for easy build and execution.
- Compatible with Node.js >= 16.
- Integration with lodash and TypeScript typings for lodash.

---

## Prerequisites

- Node.js >= 16
- npm or pnpm installed

---

## Installation

Clone the repository and install the dependencies:

```bash
# Using npm
npm install

# Or using pnpm
pnpm install
```

---

## Scripts

### Development Mode

Start the application in development mode with live reload:

```bash
npm run start:dev
```

### Production Mode

Compile TypeScript and run the generated JavaScript files:

```bash
npm run start:prod
```

### Build Only

Compile TypeScript files into JavaScript:

```bash
npm run build
```

---

## File Structure

```plaintext
.
├── src
│   └── index.ts       # Entry point of the application
├── dist               # Compiled JavaScript files (generated on build)
├── package.json       # Project metadata and scripts
├── tsconfig.json      # TypeScript configuration
├── nodemon.json       # Nodemon configuration for development
└── README.md          # Project documentation
```

---

## Configuration Details

### TypeScript Configuration (`tsconfig.json`)

- **Target**: `es2022` to use modern JavaScript features.
- **Output Directory**: Compiled files are placed in the `dist` folder.
- **Strict Mode**: Ensures robust and type-safe code.
- **Library Options**: Includes DOM and iterable libraries for frontend compatibility.

### Nodemon Configuration (`nodemon.json`)

- Watches the `src` folder for changes.
- Ignores the `dist` folder to avoid infinite loops.
- Automatically rebuilds and restarts the app on changes.

### Package Metadata (`package.json`)

- **Repository**: [GitHub Repository](https://github.com/Jszigeti/ts-starter-config)
- **License**: MIT

---

## Contributing

Feel free to submit issues or pull requests via the [GitHub repository](https://github.com/Jszigeti/ts-starter-config).

---

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
