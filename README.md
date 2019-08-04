# A simple ts starter kit with Expressjs and Watchjs

Includes eslint, prettier, webpack, and jest also!

## Note

- [eslint version 6 doesn't seem to play nice with everyone else, so version 5 is used](https://github.com/typescript-eslint/typescript-eslint/issues/641).
- for using _winston logger_, `import { createLogger, format, transports } from 'winston'` doesn't seems to work, so `const winston = require('winston')` used instead.
- Hacks involved in the `webpack.config.js` to get this working.
- adds [io-ts](https://github.com/gcanti/io-ts), which requires [fp-ts](https://github.com/gcanti/fp-ts). It is a bit redundant since [Rambda](https://ramdajs.com/) is already here. Well, at least you have a choice.
- for ExpressJS, [Overnight](https://github.com/seanpmaxwell/overnight) is added. See [this](https://levelup.gitconnected.com/setup-express-with-typescript-in-3-easy-steps-484772062e01) for more info. Not too sure about the logger package that comes with it thou.

## Reference

- [Using ESLint and Prettier in a TypeScript Project](https://dev.to/robertcoopercode/using-eslint-and-prettier-in-a-typescript-project-53jb)
- [Webpack with Typescript](https://webpack.js.org/guides/typescript/)
- [Unit Testing with Typescript and Jest](https://dev.to/muhajirdev/unit-testing-with-typescript-and-jest-2gln)
- [Setup Express with TypeScript in 3 Easy Steps](https://levelup.gitconnected.com/setup-express-with-typescript-in-3-easy-steps-484772062e01)

## TODO

- fix the type `any` in `ExampleServer.ts`
