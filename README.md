# e-plantShopping

Projekt: e-plantShopping

Krótki opis:
e-plantShopping to prosty sklep internetowy z roślinami stworzony jako aplikacja React z użyciem Vite i Redux Toolkit. Aplikacja umożliwia przeglądanie katalogu roślin, dodawanie produktów do koszyka, edycję ilości oraz usuwanie pozycji z koszyka.

Główne funkcje:

- Lista produktów (kategorie roślin) z opisami i cenami
- Dodawanie produktów do koszyka (`Add to Cart`)
- Wyświetlanie koszyka, zmiana ilości produktów i usuwanie produktów
- Obliczanie subtotali pozycji i całkowitej sumy koszyka
- Zarządzanie stanem aplikacji za pomocą Redux Toolkit

Technologie:

- React
  ﻿# e-plantShopping

Project: e-plantShopping

Short description:
e-plantShopping is a simple plant e-commerce demo built with React, Vite and Redux Toolkit. The app allows browsing a catalog of plants, adding products to a shopping cart, updating quantities, and removing items.

Key features:

- Product listing by category with images, descriptions and prices
- Add products to cart (`Add to Cart`)
- View and manage cart items (increment, decrement, remove)
- Calculate item subtotals and total cart amount
- State management with Redux Toolkit

Technologies:

- React
- Vite
- Redux Toolkit (@reduxjs/toolkit)
- JavaScript / JSX
- CSS

Important files:

- `src/CartSlice.jsx` - Redux slice for cart state (reducers & actions)
- `src/store.js` - Redux store configuration using `configureStore`
- `src/ProductList.jsx` - Product list and `Add to Cart` handling
- `src/CartItem.jsx` - Cart UI, quantity updates and removal
- `src/main.jsx` - App entry point and Redux `Provider` wrapper

Run locally:

1. Install dependencies:

```bash
npm install
```

2. Start development server:

```bash
npm run dev
```

Contributing:

- Open an issue describing the change you propose
- Create a branch named `feat/your-feature` or `fix/your-fix`
- Submit a pull request with a clear description of changes

Contact:
Project author: (add your name or contact information)
