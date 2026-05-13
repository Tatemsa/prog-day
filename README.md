# Prog-Day

A modern React application built with TypeScript, Vite, and Bun. This project features a clean setup with Biome for code formatting and linting, Tailwind CSS for styling, Shadcn UI components, and Cypress for end-to-end testing.

## Tech Stack

- **Frontend Framework**: React 19 with TypeScript
- **Build Tool**: Vite
- **Runtime/Package Manager**: Bun
- **Styling**: Tailwind CSS with Shadcn UI components
- **Code Quality**: Biome (formatting and linting)
- **Testing**: Cypress (E2E)
- **Development Tools**: ESLint, TypeScript

## Installation

Make sure you have [Bun](https://bun.sh/) installed on your system.

```bash
# Clone the repository
git clone <repository-url>
cd prog-day

# Install dependencies
bun install
```

## Scripts

The following scripts are available via `bun run <script>`:

- `dev` / `start`: Start the development server with Vite
- `build`: Build the project for production
- `format`: Format code with Biome
- `check`: Check code formatting and linting with Biome
- `lint`: Run ESLint for additional linting rules
- `preview`: Preview the production build locally

## Development

To start developing:

```bash
bun run dev
```

This will start the Vite development server with hot module replacement (HMR).

## Building

To build the project for production:

```bash
bun run build
```

The built files will be in the `dist` directory.

## Code Quality

This project uses Biome for fast code formatting and linting:

```bash
# Format code
bun run format

# Check formatting and linting
bun run check
```

## Testing

End-to-end tests are written with Cypress:

```bash
# Open Cypress test runner
bun x cypress open

# Run tests headlessly
bun x cypress run
```

## Project Structure

```
src/
├── components/
│   └── ui/          # Shadcn UI components
├── lib/
│   └── utils.ts     # Utility functions
├── assets/          # Static assets
├── App.tsx          # Main app component
├── main.tsx         # App entry point
└── index.css        # Global styles
```

## Contributing

1. Follow the code style enforced by Biome
2. Run `bun run check` before committing
3. Add tests for new features
4. Update this README if needed
