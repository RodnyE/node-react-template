
# Node-React Template ✏️

This is a template for NodeJS projects with Express and React, using Webpack for the frontend. 🚀

## Setup 

1. Clone the repository:
   ```bash
   git clone https://github.com/RodnyE/node-react-template.git
   ```

2. Rename the `buildDependencies` property in `package.json` to `devDependencies`.

3. Install the dependencies:
   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm test
   ```

## Structure 📁

The project structure is as follows:

- `src/`: Contains the frontend React code.
- `serv/`: Contains the backend NodeJS code.
- `public/`: Contains the static files served by Express.
- `dist/`: Contains the bundled files generated by Webpack.

## Configuration ⚙️

- `webpack.config.js`: Webpack configuration file.
- `.babelrc`: Babel configuration file.
- `postcss.config.js`: PostCSS configuration file.

## Dependencies 📦

- NodeJS
- Express
- React
- Webpack and related plugins (listed in `buildDependencies` in `package.json`)

## Development 👨‍💻

To start the development server:

```bash
npm test
```

This command will run both the backend server and the frontend development build using Webpack. Any changes made in the code will automatically trigger a rebuild.

## Production 🚀

To build the project for production:

```bash
npm run build
```

This command will generate the optimized production build in the `dist/` directory.

To start the production server:

```bash
npm start
```

Make sure to set the appropriate environment variables in a `.env` file or in your hosting environment.

## Contributing 🤝

Feel free to contribute to this project by creating issues or submitting pull requests. Your contributions are highly appreciated.

---
♥️ Code by Rodny Estrada