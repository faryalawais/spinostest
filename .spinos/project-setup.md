## Summary
This project aims to create a simple To Do application using NestJS, providing a clear structure for development and deployment.

## Proposed files (brief)
- `README.md`: Documentation for setup and usage.
- `src/main.ts`: Entry point for the application.
- `src/app.module.ts`: Main application module.
- `tests/app.e2e-spec.ts`: End-to-end tests for the application.
- `.gitignore`: Standard Git ignore file.
- `.github/workflows/ci.yml`: CI configuration for automated testing and linting.

## Commands
- `npm run lint`: Lint the codebase.
- `npm run typecheck`: Check TypeScript types.
- `npm run unit`: Run unit tests.
- `npm run build`: Build the application.

## CI / automation (optional)
The CI workflow is set up to run linting, type checking, and unit tests on every push and pull request.

## Follow-ups
- Implement user authentication.
- Add a database for persistent storage.