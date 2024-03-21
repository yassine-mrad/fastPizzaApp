# Fast Pizza App

Welcome to Fast Pizza App, a small and fast pizza ordering application built with ReactJS!

# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: "latest",
    sourceType: "module",
    project: ["./tsconfig.json", "./tsconfig.node.json"],
    tsconfigRootDir: __dirname,
  },
};
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list

## Overview

Fast Pizza App is designed to provide a seamless and efficient experience for ordering delicious pizzas. With intuitive interfaces for browsing menus, customizing pizzas, and managing orders, it aims to make pizza ordering quick and enjoyable.

## Features

- **Menu Browsing**: Browse through a variety of pizza options.
- **Customization**: Customize your pizza with your favorite toppings and crust types.
- **Order Management**: Easily manage your orders, view order history, and track deliveries.
- **User Authentication**: Securely log in to your account to access personalized features.
- **Responsive Design**: Enjoy a seamless experience across devices of all sizes.

## Installation

1. Clone the repository: `git clone https://github.com/yassine-mrad/fastPizzaApp.git`
2. Navigate to the project directory: `cd fast-pizza-app`
3. Install dependencies: `npm install`
4. Start the development server: `npm start`
5. Visit `http://localhost:3000` in your browser to view the app.

## Contributing

We welcome contributions from the community! If you'd like to contribute to Fast Pizza App, please follow these steps:

1. Fork the repository.
2. Create your feature branch: `git checkout -b feature/your-feature-name`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- This project was inspired by the love for pizza and the desire to create a fast and enjoyable ordering experience.
- Special thanks to the ReactJS community for their amazing support and resources.

## Contact

Have any questions or suggestions? Feel free to contact us at [yassinemrad9898@gmail.com](mailto:yassinemrad9898@gmail.com.com).
