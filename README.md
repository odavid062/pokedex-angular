# SpaPokedexRouting

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 19.1.6.

A Single Page Application (SPA) Pokédex built with Angular 19 that consumes the PokéAPI to search and display Pokémon information (types, dimensions, abilities, and sprites).

## Features

- Search Pokémon by name.
- Displays Pokémon sprite, types, height, weight, and abilities.
- Responsive design styled with Bootstrap 5 and custom CSS.

## Tech Stack

- **Framework**: Angular 19 (Standalone Components)
- **Language**: TypeScript 5.7
- **Styling**: Bootstrap 5.3.3 & CSS
- **API**: [PokéAPI](https://pokeapi.co/) (`https://pokeapi.co/api/v2/pokemon`)
- **Testing**: Karma & Jasmine

## Prerequisites & Installation

- Node.js and npm installed.

To install dependencies, run:

```bash
npm install
```

## Development server

To start a local development server, run:

```bash
ng serve
```
or:
```bash
npm start
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

## Code scaffolding

Angular CLI includes powerful code scaffolding tools. To generate a new component, run:

```bash
ng generate component component-name
```

For a complete list of available schematics (such as `components`, `directives`, or `pipes`), run:

```bash
ng generate --help
```

## Building

To build the project run:

```bash
ng build
```
or:
```bash
npm run build
```

This will compile your project and store the build artifacts in the `dist/` directory (`dist/spa-pokedex--routing`). By default, the production build optimizes your application for performance and speed.

To run build in watch mode for development:

```bash
npm run watch
```

## Running unit tests

To execute unit tests with the [Karma](https://karma-runner.github.io) test runner, use the following command:

```bash
ng test
```
or:
```bash
npm test
```

## Running end-to-end tests

For end-to-end (e2e) testing, run:

```bash
ng e2e
```

Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

## Available Scripts

In the project directory, you can run:

- `npm start` (or `ng serve`): Starts the local development server at `http://localhost:4200/`.
- `npm run build` (or `ng build`): Compiles the application into `dist/spa-pokedex--routing`.
- `npm run watch`: Builds and watches for file changes in development mode.
- `npm test` (or `ng test`): Executes unit tests using the Karma test runner.

## Project Structure

```text
src/
├── app/
│   ├── interceptors/
│   │   └── auth.interceptor.ts      # HTTP interceptor
│   ├── services/
│   │   └── spell.service.ts         # Spell service
│   ├── app.component.css            # Root component styling
│   ├── app.component.html           # Main template (search bar & Pokemon card)
│   ├── app.component.spec.ts        # Unit test specification for AppComponent
│   ├── app.component.ts             # Main standalone component logic
│   ├── app.config.ts                # Application configuration & providers
│   ├── app.routes.ts                # Application routing configuration
│   ├── pokemon.service.ts           # Service for querying the PokéAPI
│   └── pokemon.ts                   # TypeScript interfaces for PokéAPI data
├── public/                          # Static public assets
├── index.html                       # Base HTML file
├── main.ts                          # Application bootstrap entry point
└── styles.css                       # Global styles & Bootstrap import
```

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
