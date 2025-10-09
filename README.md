# Mint Chip 🍃

## 🛠️ Tech Stack

- **React** 19.1.1
- **Vite** 7.1.7
- **Tailwind CSS** 4.1.14
- **ESLint** 9.36.0
- **Prettier** 3.6.2

## 🚀 Getting Started

* ### Installation

  ```bash
  npm install
  ```

* ### Available Scripts

  - #### Development
    ```bash
    npm run dev
    ```
    Starts the development server locally.

  - #### Build
    ```bash
    npm run build
    ```
    Creates an optimized production build.

  - #### Preview
    ```bash
    npm run preview
    ```
    Previews the production build locally.

  - #### Linting
    ```bash
    npm run lint
    ```
    Analyzes code with ESLint to find issues.

  - #### Formatting
    ```bash
    npm run format
    ```
    Formats all code with Prettier.

## ⚙️ Configuration

* ### Tailwind CSS
  Tailwind directives are imported in `src/index.css`:
  ```css
  @import "tailwindcss";
  ```

* ### ESLint
  Configured in `eslint.config.js` with support for React Hooks and React Refresh.

* ### Prettier
  Configured in `.prettierrc` with the following options:
  ```json
  {
    "semi": true,
    "singleQuote": true,
    "tabWidth": 2,
    "trailingComma": "es5"
  }
  ```
  - Semicolons: enabled
  - Single quotes
  - Tab width: 2
  - Trailing commas: ES5


## 📝 License

