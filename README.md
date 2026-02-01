# TypeScript LSP MCP Server

A Model Context Protocol (MCP) server that provides TypeScript/JavaScript code intelligence using the official **TypeScript Language Service**.

## Features

*   **Standard LSP Capabilities**:
    *   **Hover**: Documentation and type info.
    *   **Definition**: Jump to definition.
    *   **References**: Find usages.
    *   **Completions**: Intelligent code completion.
    *   **Signature Help**: Parameter hints.
    *   **Symbols**: Document symbol search.

*   **Inlay Hints**: Reveal inferred types and parameter names inline.
*   **Code Actions**: Quick fixes, Organize Imports, Refactorings.
*   **Cross-File Rename**: Semantic renaming.

## Installation

```bash
npm install -g @treedy/typescript-lsp-mcp
```

## Usage

Run via command line (stdio):

```bash
typescript-lsp-mcp
```

Or via npx:

```bash
npx @treedy/typescript-lsp-mcp
```

## Configuration

It uses the `tsconfig.json` found in the workspace root.