# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

MCP (Model Context Protocol) server for MulmoCast. Provides MCP tools for generating and managing MulmoCast content.

## Commands

```bash
yarn build      # Compile TypeScript (tsc)
yarn lint       # Run ESLint on src/
yarn format     # Format with Prettier
yarn test       # Run tests with coverage (tsx --test)
yarn cli        # Run CLI directly (npx tsx)
```

## Architecture

- `src/index.ts` - MCP server entry point
- `src/html_prompt.json` - HTML generation prompts
- `test/` - Test files (test_*.ts pattern)
- Uses tsx for TypeScript execution
