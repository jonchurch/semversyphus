# semversyphus

A minimal test package designed for monitoring npm package update propagation and testing software that detects changes to npm packages.

## Purpose

This package serves as a test subject for:
- Monitoring npm registry update propagation
- Testing package version change detection systems
- Validating npm package update workflows
- Testing dependency update automation tools

## Installation

```bash
npm install semversyphus
```

## Usage

The package exports a single function that returns its current version:

```javascript
const getVersion = require('semversyphus');

console.log(getVersion()); // Returns the current package version
```

## API

### `getVersion()`

Returns the current version string from package.json.

**Returns:** `string` - The current package version (e.g., "1.0.0")
