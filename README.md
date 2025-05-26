# Webpack Configuration with TypeScript, SWC, SCSS, SVG, and PostCSS
- TypeScript: Uses TypeScript for static typing and to improve code quality.
- SWC (Speedy Web Compiler): Uses SWC for fast compilation of TypeScript and JavaScript.
- SCSS: Supports SCSS with modular styles (CSS Modules).
- SVG: Processes SVG files as React components using @svgr/webpack.
- Images: Processes images (PNG, JPG, JPEG, GIF, WebP) using asset/resource and saves them in the folder assets/images.
- Fonts: Handles fonts.
- Hot Module Replacement (HMR): Supports hot reloading to speed up development.
- Bundle Analysis: Uses webpack-bundle-analyzer to analyze the bundle size.
- Type Checking: Uses fork-ts-checker-webpack-plugin to perform TypeScript type checking in a separate process.
- Copying Resources: Uses copy-webpack-plugin to copy static assets.
- PostCSS: Uses PostCSS to process CSS with postcss-preset-env and cssnano.
- Browser Compatibility: Configures browserslist to ensure compatibility with various browsers.
- Automatic JSX Transform: Uses runtime: 'automatic' for automatic JSX transformation.

## Available Scripts
- yarn start: Launches the development server with hot reloading.
- yarn analyzer: Builds the project for production with bundle size analysis.
- yarn build:dev: Builds the project for development.
- yarn build:prod: Builds the project for production.

## Browser Compatibility Configuration
The browserslist setting in package.json ensures compatibility with the specified browsers.
