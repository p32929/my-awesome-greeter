# my-awesome-greeter

A practice package: the smallest possible TypeScript library, set up end-to-end so I could learn the publishing pipeline — `tsc` build, Jest tests, `prepare` hook, published to npm.

The library itself is one function. The point is everything around it.

On npm: **[my-awesome-greeter-by-fayaz](https://www.npmjs.com/package/my-awesome-greeter-by-fayaz)**

## Usage

```bash
npm install my-awesome-greeter-by-fayaz
```

```ts
import { Greeter } from 'my-awesome-greeter-by-fayaz';

Greeter('Carl');   // "Hello Carl"
```

## What's worth copying

If you're setting up your own TypeScript npm package, these are the bits:

| File | Why |
|---|---|
| `package.json` | `main: lib/index.js`, and a `prepare` script so `npm publish` always builds first |
| `tsconfig.json` | Emits declarations into `lib/` |
| `jestconfig.json` | Jest with `ts-jest`, kept out of `tsconfig` |
| `src/__tests__/test.ts` | One real test, so `npm test` means something |

## Develop

```bash
git clone https://github.com/p32929/my-awesome-greeter.git
cd my-awesome-greeter
npm install
npm test
npm run build
```

## Contributing

Contributions are warmly welcomed and greatly appreciated! Whether it's a bug fix, new feature, or improvement, your input helps make this project better for everyone.

Before submitting a pull request, please:

1. Create an issue describing the feature or bug fix you'd like to work on
2. Wait for discussion and approval to ensure alignment with project goals
3. Fork the repository and create your feature branch
4. Submit your pull request with a clear description of changes

This approach helps avoid duplicate efforts and ensures smooth collaboration. Thank you for considering contributing!

## Share

Sharing this repository with your friends is just one click away from here

[![facebook](https://user-images.githubusercontent.com/6418354/179013321-ac1d1452-0689-493f-9066-940cf2302b6e.png)](https://www.facebook.com/sharer/sharer.php?u=https://github.com/p32929/my-awesome-greeter/)
[![twitter](https://user-images.githubusercontent.com/6418354/179013351-7d8d6d1c-4ce2-46ab-bef8-4c4765a1b888.png)](https://twitter.com/intent/tweet?url=https://github.com/p32929/my-awesome-greeter/)
[![tumblr](https://user-images.githubusercontent.com/6418354/179013343-3111f55a-3b90-40c7-8487-9777348672b0.png)](https://www.tumblr.com/share?v=3&u=https://github.com/p32929/my-awesome-greeter/)
[![pocket](https://user-images.githubusercontent.com/6418354/179013334-b095c45f-becf-49f4-9ee1-5a731a9b1f85.png)](https://getpocket.com/save?url=https://github.com/p32929/my-awesome-greeter/)
[![pinterest](https://user-images.githubusercontent.com/6418354/179013331-44cd9206-11b1-4b65-becb-5863b61c828f.png)](https://pinterest.com/pin/create/button/?url=https://github.com/p32929/my-awesome-greeter/)
[![reddit](https://user-images.githubusercontent.com/6418354/179013338-7416ae3f-73ba-4522-86e1-1374d7082d22.png)](https://www.reddit.com/submit?url=https://github.com/p32929/my-awesome-greeter/)
[![linkedin](https://user-images.githubusercontent.com/6418354/179013327-ca7b7102-1da8-4b1c-858f-1a6e5f21bd70.png)](https://www.linkedin.com/shareArticle?mini=true&url=https://github.com/p32929/my-awesome-greeter/)
[![whatsapp](https://user-images.githubusercontent.com/6418354/179013353-f477fa0b-3e6f-4138-a357-c9991b23ff88.png)](https://api.whatsapp.com/send?text=https://github.com/p32929/my-awesome-greeter/)
