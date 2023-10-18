# TurboDashClient

TurboDashClient is a cutting-edge web application client, optimized for speed and efficiency, harnessing the collective power of contemporary tools such as [Vite](https://vitejs.dev/), [React](https://reactjs.org/), and [TypeScript](https://www.typescriptlang.org/).

## Features

- **Vite**: Experience the next generation of frontend development with Vite, offering rapid serving and efficient bundling.
- **ESLint, TypeScript-ESLint, Prettier**: Achieve clean, error-free, and standardized code with integrated linting and formatting tools.
- **ViTest, JSDOM, Testing Library**: Robust testing environment using ViTest, with the familiarity and extended functionality of Jest through `@testing-library/jest-dom`, ensuring your components work as expected.
- **React Router v6**: Navigate with ease and confidence using the latest version of the comprehensive routing solution for React.

## Quick Start

1. Clone the repository.
2. Navigate to the project directory and run `npm install` to install dependencies.
3. Kickstart your development process with `npm run dev`, firing up a local development server.

## Available Scripts

- `dev`: Runs the development server, providing hot reloading and instant feedback.
- `build`: Compiles your application for production deployment.
- `preview`: Offers a local sneak-peek of your production build, before going live.
- `test`: Executes the test suite in a CI environment, ensuring reliability.
- `test:watch`: Continuously runs tests in the interactive watch mode during development.
- `lint`: Scans your codebase for linting errors, maintaining code quality.
- `lint:fix`: Resolves and reformats code issues automatically where possible.
- `typecheck`: Performs a TypeScript type verification without emitting code, ensuring type accuracy.

## Testing Strategy

While we use ViTest for testing functionalities, we embrace features of the Jest testing library via the `@testing-library/jest-dom` extension. This integration enriches our testing suite with custom Jest matchers, making assertions more descriptive and the tests more robust, directly reflecting DOM state and changes.

## References

Further enhance your testing approach and avoid common pitfalls by exploring these insightful resources:

- [Using Testing Library with ViTest](https://markus.oberlehner.net/blog/using-testing-library-jest-dom-with-vitest/)
- [Understanding Query Priority in Testing Library](https://testing-library.com/docs/queries/about#priority)
- [Avoiding Common Mistakes with React Testing Library](https://kentcdodds.com/blog/common-mistakes-with-react-testing-library)
