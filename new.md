```
├── public
│   ├── index.html
│   └── favicon.ico
├── src
│   ├── assets
│   │   ├── images
│   │   └── styles
│   ├── components
│   │   ├── auth
│   │   ├── cart
│   │   ├── common
│   │   ├── home
│   │   ├── product
│   │   └── user
│   ├── pages
│   │   ├── AuthPage
│   │   ├── CartPage
│   │   ├── HomePage
│   │   ├── ProductDetailPage
│   │   ├── ProductListPage
│   │   └── UserPage
│   ├── services
│   │   ├── authService
│   │   ├── cartService
│   │   ├── productService
│   │   └── userService
│   ├── utils
│   ├── App.tsx
│   ├── index.tsx
│   └── routes.tsx
├── package.json
├── tsconfig.json
├── eslint-config.js
├── jest.config.js
├── postcss.config.js
├── tailwind.config.js
├── .eslintrc.js
├── .eslintignore
└── .gitignore
```

-   `   react` and `react-dom`: required for building React applications
-   `react-router-dom`: for client-side routing
-   `axios`: for making HTTP requests to a server
-   `jsonwebtoken`: for generating and verifying JSON web tokens for authentication
-   `bcryptjs`: for hashing and salting passwords for secure storage
-   `prop-types`: for type-checking React props
-   `redux` and `react-redux`: for managing state in a large application
-   `redux-thunk`: for handling asynchronous actions in Redux
-   `styled-components`: for writing CSS-in-JS styles in React components
-   `classnames`: for conditionally applying class names to elements
-   `eslint` and `prettier`: for code formatting and linting
-   `husky` and `lint-staged`: for running code formatting and linting before committing changes
-   `dotenv`: for managing environment variables in development and production environments
-   `jest` and `react-testing-library`: for unit and integration testing React components and functions
****
-   `typescript`: required for building TypeScript applications
-   `@types/react` and `@types/react-dom`: for providing TypeScript types for React
-   `@types/react-router-dom`: for providing TypeScript types for `react-router-dom`
-   `@types/jest`: for providing TypeScript types for Jest and testing utilities
-   `ts-jest`: for running Jest tests with TypeScript
-   `eslint-plugin-import`, `eslint-plugin-react`, `eslint-plugin-react-hooks`, `@typescript-eslint/eslint-plugin`, and `@typescript-eslint/parser`: for configuring ESLint to work with TypeScript and React
