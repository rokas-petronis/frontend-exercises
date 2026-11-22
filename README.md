# Fruit Pages & Calculator

A small collection of frontend exercises created while learning HTML, CSS, JavaScript, and TypeScript.

The repository started as a user interface design assignment focused on responsive, mobile-first layouts. It also includes a browser-based calculator with TypeScript logic and automated tests.

## What's included

### Fruit pages

- A homepage listing five fruits and their prices.
- Individual pages with images and descriptions for each fruit.
- CSS layouts with basic responsive styling and a desktop media query.

The original assignment instructions are in `extra-info/task-1.pdf`.

### Calculator

- A browser-based calculator with buttons for arithmetic operations.
- Addition, subtraction, multiplication, division, remainder, and exponentiation.
- Square, cube, and square-root actions.
- Calculation logic written in TypeScript, with tests using Vitest.

The calculator is a learning exercise, not a full-featured calculator or expression parser.

## Technologies

- HTML and CSS
- TypeScript
- Node.js and Express (local development server)
- Vitest (automated tests)

## Running locally

You'll need Node.js and npm. The repository includes an `.nvmrc` file specifying the Node.js version used for the project.

```bash
git clone https://github.com/rokas-petronis/html-css-task-one-nsk.git
cd html-css-task-one-nsk
npm ci
npm run build
node dist/index.js
```

Then open:

- Fruit pages: http://localhost:3000/
- Calculator: http://localhost:3000/calculator.html

The server uses port `3000` by default, or the `PORT` environment variable if set.

## Tests

Run the calculator's automated tests with:

```bash
npm run test:run
```

## Background

This repository documents some of my early frontend learning, starting with a user interface design assignment and continuing with TypeScript and testing practice.
