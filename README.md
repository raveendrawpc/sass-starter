# Sass Starter Project

A basic setup to start using Sass with modern @use syntax.

## Usage

1. Install dependencies: `npm install`
2. Watch for Sass changes: `npm run sass:watch`

## Structure
- Use `@use` to load partials in your main SCSS file
- Partial files should be prefixed with underscore (\_)
- Imported members are namespaced by default (use `as *` for global access)
