# my-awesome-greeter

A practice project: the smallest possible TypeScript library, set up from start to finish so I could learn how to publish a package to npm. It builds with `tsc`, has Jest tests, and builds itself before every publish.

The library is one function. The useful part is everything around it, so you can copy the setup for your own package.

On npm: **[my-awesome-greeter-by-fayaz](https://www.npmjs.com/package/my-awesome-greeter-by-fayaz)**

## Use it

```bash
npm install my-awesome-greeter-by-fayaz
```

```ts
import { Greeter } from 'my-awesome-greeter-by-fayaz';

Greeter('Carl');   // "Hello Carl"
```

## What to copy for your own package

| File | Why |
|---|---|
| `package.json` | `main: lib/index.js`, and a `prepare` script so `npm publish` always builds first |
| `tsconfig.json` | Writes the type declarations into `lib/` |
| `jestconfig.json` | Jest with `ts-jest`, kept apart from `tsconfig` |
| `src/__tests__/test.ts` | One real test, so `npm test` checks something |

## Work on it

```bash
git clone https://github.com/p32929/my-awesome-greeter.git
cd my-awesome-greeter
npm install
npm test
npm run build
```

## Contributing

Contributions are very welcome. Please open an issue first to talk about what you'd like to add or change, so we can agree on it before you spend time on a pull request. Thank you!

## Share

<a href="https://p32929.github.io/share/?repo=my-awesome-greeter"><picture><source media="(prefers-color-scheme: dark)" srcset="https://p32929.github.io/readme/share-dark.svg"><img src="https://p32929.github.io/readme/share-light.svg" alt="Share this with your friends in just a click" width="420"></picture></a>

## Support

<a href="https://p32929.github.io/support/"><picture><source media="(prefers-color-scheme: dark)" srcset="https://p32929.github.io/readme/support-dark.svg"><img src="https://p32929.github.io/readme/support-light.svg" alt="If you like my works and want to support me, feel free to support" width="420"></picture></a>
