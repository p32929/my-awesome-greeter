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

## You might also like

<p><a href="https://openstore.pfay.workers.dev/cards/p32929/0?n=4&amp;repo=my-awesome-greeter"><picture><source media="(prefers-color-scheme: dark)" srcset="https://openstore.pfay.workers.dev/cards/p32929/0.svg?n=4&amp;repo=my-awesome-greeter&amp;theme=dark"><img src="https://openstore.pfay.workers.dev/cards/p32929/0.svg?n=4&amp;repo=my-awesome-greeter&amp;theme=light" width="50%" align="top" alt="More apps by p32929 on OpenStore (1)"></picture></a><a href="https://openstore.pfay.workers.dev/cards/p32929/1?n=4&amp;repo=my-awesome-greeter"><picture><source media="(prefers-color-scheme: dark)" srcset="https://openstore.pfay.workers.dev/cards/p32929/1.svg?n=4&amp;repo=my-awesome-greeter&amp;theme=dark"><img src="https://openstore.pfay.workers.dev/cards/p32929/1.svg?n=4&amp;repo=my-awesome-greeter&amp;theme=light" width="50%" align="top" alt="More apps by p32929 on OpenStore (2)"></picture></a><br><a href="https://openstore.pfay.workers.dev/cards/p32929/2?n=4&amp;repo=my-awesome-greeter"><picture><source media="(prefers-color-scheme: dark)" srcset="https://openstore.pfay.workers.dev/cards/p32929/2.svg?n=4&amp;repo=my-awesome-greeter&amp;theme=dark"><img src="https://openstore.pfay.workers.dev/cards/p32929/2.svg?n=4&amp;repo=my-awesome-greeter&amp;theme=light" width="50%" align="top" alt="More apps by p32929 on OpenStore (3)"></picture></a><a href="https://openstore.pfay.workers.dev/cards/p32929/3?n=4&amp;repo=my-awesome-greeter"><picture><source media="(prefers-color-scheme: dark)" srcset="https://openstore.pfay.workers.dev/cards/p32929/3.svg?n=4&amp;repo=my-awesome-greeter&amp;theme=dark"><img src="https://openstore.pfay.workers.dev/cards/p32929/3.svg?n=4&amp;repo=my-awesome-greeter&amp;theme=light" width="50%" align="top" alt="More apps by p32929 on OpenStore (4)"></picture></a></p>

<p><a href="https://p32929.github.io/share/?repo=my-awesome-greeter"><picture><source media="(prefers-color-scheme: dark)" srcset="https://p32929.github.io/readme/footer-share-dark.svg"><img src="https://p32929.github.io/readme/footer-share-light.svg" width="50%" align="top" alt="Share this project with your friends in one click"></picture></a><a href="https://p32929.github.io/support/"><picture><source media="(prefers-color-scheme: dark)" srcset="https://p32929.github.io/readme/footer-support-dark.svg"><img src="https://p32929.github.io/readme/footer-support-light.svg" width="50%" align="top" alt="If you like my work and want to support me, feel free to support"></picture></a><br><a href="https://openstore.pfay.workers.dev/add"><picture><source media="(prefers-color-scheme: dark)" srcset="https://p32929.github.io/readme/footer-join-dark.svg"><img src="https://p32929.github.io/readme/footer-join-light.svg" width="100%" align="top" alt="Put your own apps on OpenStore: free, your listing lives in your own repo"></picture></a></p>
