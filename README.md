# Upload AI Web

## Description

This project is a web application for interacting with the Upload AI API. It is built using Vite as the bundler, React for the user interface, and TypeScript for type-checking.

## Installation

Before running the project, make sure you have Node.js and npm installed on your machine.

1. Clone the repository:

```bash
git clone <repository-url>
cd upload-ai-web
```

2. Install dependencies:

```bash
npm install
```

3. Create a .env file in the root directory if needed, and add any environment-specific configurations.

## Scripts

### Development

To run the project in development mode, execute the following command:

```bash
npm run dev
```

This will start the development server using Vite.

### Build

To build the project for production, execute the following command:

```bash
npm run build
```

This command compiles TypeScript files using tsc and then builds the project with Vite.

### Lint

To lint the project using ESLint, execute the following command:

```bash
npm run lint
```

This command uses ESLint to analyze and report any issues in the TypeScript code.

### Preview

To preview the production build locally, execute the following command:

```bash
npm run preview
```

This will serve the production build locally for testing purposes.

## Dependencies

- **@ffmpeg/ffmpeg:** FFmpeg library for handling multimedia data.
- **@ffmpeg/util:** FFmpeg utilities for Node.js.
- **@radix-ui/react-icons:** React components for Radix UI icons.
- **@radix-ui/react-label:** React components for Radix UI labels.
- **@radix-ui/react-select:** React components for Radix UI select menus.
- **@radix-ui/react-separator:** React components for Radix UI separators.
- **@radix-ui/react-slider:** React components for Radix UI sliders.
- **@radix-ui/react-slot:** React components for Radix UI slots.
- **ai:** AI library (version 2.2.33) - Provide the required API keys and configurations.
- **axios:** Promise-based HTTP client for the browser and Node.js.
- **class-variance-authority:** Class-based variance utilities for React.
- **clsx:** A tiny utility for constructing class names.
- **lucide-react:** A library of simply designed React SVG icons.
- **react:** JavaScript library for building user interfaces.
- **react-dom:** React package for working with the DOM.
- **tailwind-merge:** Utility for merging Tailwind CSS classes.
- **tailwindcss-animate:** Plugin for adding animation utilities to Tailwind CSS.

## Development Dependencies

- **@types/node:** TypeScript type definitions for Node.js.
- **@types/react:** TypeScript type definitions for React.
- **@types/react-dom:** TypeScript type definitions for React DOM.
- **@typescript-eslint/eslint-plugin:** ESLint plugin for TypeScript.
- **@typescript-eslint/parser:** TypeScript parser for ESLint.
- **@vitejs/plugin-react-swc:** Vite plugin for React with SWC.
- **autoprefixer:** PostCSS plugin to parse CSS and add vendor prefixes.
- **eslint:** Linting utility for identifying and fixing problems in JavaScript code.
- **eslint-plugin-react-hooks:** ESLint plugin for React hooks.
- **eslint-plugin-react-refresh:** ESLint plugin for React Refresh.
- **postcss:** Tool for transforming styles with JS plugins.
- **tailwindcss:** A utility-first CSS framework.
- **typescript:** TypeScript language and compiler (version 5.2.2).
- **vite:** Fast frontend development tool.
