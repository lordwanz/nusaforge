# Installation Guide

This guide explains how to install NusaForge from npm.

## Prerequisites

Before installing NusaForge, make sure you have:

- Node.js installed.
- npm available in your terminal.
- An internet connection to access the npm registry.

Check your installation:

```bash
node --version
npm --version
```

## Install NusaForge

Install the package using npm:

```bash
npm install nusaforge
```

This installs NusaForge into the current project's dependencies.

## Verify the Package

Check the installed package version:

```bash
npm list nusaforge
```

You can also view the published package and its release information at:

https://www.npmjs.com/package/nusaforge

## Troubleshooting

### Installation fails

- Check your internet connection.
- Verify that npm can access the registry.
- Review the error message printed in your terminal.
- Confirm that the package name is spelled correctly.

### Package commands are unavailable

Installing a package does not automatically mean it provides a command-line interface. Check the package documentation and its `bin` configuration for supported commands.

## Next Steps

Continue to the [Usage Guide](usage.md) for instructions on using NusaForge.

---

NusaForge — Forge ideas into software.
