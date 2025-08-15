# ts-starter

A simple TypeScript starter project.

## Getting Started

1. **Install dependencies:**
   ```sh
   pnpm install
   ```
2. **Start development mode (watch for changes):**
   ```sh
   pnpm run dev
   ```
3. **Build the project:**
   ```sh
   pnpm run build
   ```
4. **Start the project:**
   ```sh
   pnpm start
   ```

## Project Structure

- `src/` - Source code directory
- `index.ts` - Main entry point

## Scripts

- `pnpm run dev` - Start the project in development mode (watch for changes)
- `pnpm run build` - Build the project
- `pnpm start` - Run the built project

## Requirements
- Node.js
- pnpm

## Debugging in VS Code

You can debug this TypeScript project directly in Visual Studio Code:

1. Open the project folder in VS Code.
2. Go to the Run and Debug panel (or press `F5`).
3. If prompted, select "Node.js" as the environment.
4. Make sure you have a `launch.json` file in the `.vscode` folder. If not, VS Code can auto-generate one for you.
5. Set breakpoints in your TypeScript files (e.g., in `src/index.ts`).
6. Start debugging. VS Code will compile and run your code, stopping at breakpoints as expected.

> **Tip:** For best results, ensure your `tsconfig.json` includes source maps (`"sourceMap": true`).
