# DevDays Workshop Repo

A small React + TypeScript storefront app built as a workshop project. The app demonstrates a product catalog, shopping cart, category filtering, wishlist controls, and checkout flow using a lightweight Vite setup.

## Overview

This repository contains a front-end e-commerce demo for browsing and purchasing products. It is designed to teach or exercise modern React patterns, TypeScript typing, and business-logic helpers in a simple, demo-friendly application.

## Features

- Product catalog with search and filtering
- Category, rating, and stock-based filtering
- Sort options for price and rating
- Add-to-cart and quantity management
- Wishlist toggling
- Cart drawer checkout flow
- Order validation and coupon support
- Unit tests for catalog, cart, and checkout logic

## Tech Stack

- React 18
- TypeScript
- Vite
- Vitest
- CSS for styling

## Project Structure

```text
.
├── index.html
├── package.json
├── package-lock.json
├── tsconfig.json
├── tsconfig.app.json
├── tsconfig.node.json
├── vite.config.ts
├── src/
│   ├── App.tsx
│   ├── main.tsx
│   ├── styles.css
│   ├── types.ts
│   ├── components/
│   │   ├── CartDrawer.tsx
│   │   ├── Header.tsx
│   │   ├── ProductCard.tsx
│   │   └── ProductGrid.tsx
│   ├── data/
│   │   └── products.ts
│   └── lib/
│       ├── cart.ts
│       ├── cart.test.ts
│       ├── catalog.ts
│       ├── catalog.test.ts
│       ├── checkout.ts
│       ├── checkout.test.ts
│       ├── format.ts
│       ├── wishlist.ts
│       └── wishlist.test.ts
└── README.md
```

## Getting Started

### Prerequisites

- Node.js 18+
- npm

### Install dependencies

```bash
npm install
```

### Run the app locally

```bash
npm run dev
```

This starts the Vite development server. Open the local URL shown in the terminal in your browser.

## Available Scripts

```bash
npm run dev
```
Runs the app in development mode.

```bash
npm run build
```
Builds the app for production.

```bash
npm test
```
Runs the Vitest test suite.

```bash
npm run test:watch
```
Runs tests in watch mode.

## Testing

This project includes library-level tests for core logic such as:

- cart behavior
- catalog filtering
- checkout flow
- wishlist behavior

Example:

```bash
npm test
```

## Notes

The repository is a workshop-style app intended for experimentation and learning. You can extend it by adding more products, new filter logic, styling updates, or checkout validation.

## License

This project is currently unlicensed unless otherwise specified.
