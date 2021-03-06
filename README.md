# Hapi + Angular + Typescript

This project is a pre-configured stack consists:

- **Hapi.js** (v16.1.x) + Typescript
- **Angular** (2.4.x) + Angular CLI
- **Ava** for Hapi API Testing

## Development server

```sh
$ npm web:run   # Angular app in development mode /w watch
$ npm api:run   # Hapi app in development mode /w watching
$ npm start     # Does all above
```
## Production build

```sh
$ npm web:build   # Angular app in production mode
$ npm api:build   # Hapi app without watching
$ npm run build   # Does all above
```

The build artifacts will be stored in the `dist/` directory.

## Running unit tests

```sh
$ npm web:test   # executes Karma
$ npm api:test   # executes Ava
$ npm test       # same as api:test
```

## Further help

Found a bug or have a question? Feel free to create new [issue](https://github.com/ahmed-taj/hapi-angular-typescript-starter/issues).

## Licence

MIT
