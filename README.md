# **mobile-or-tablet** • [**Documentation**](https://github.com/idimetrix/mobile-or-tablet/blob/main/docs/classes/ProDate.md)

Determines if the device is either a mobile phone or a tablet.

## Installation

You can install the package using **npm**, **yarn**, or **pnpm**.

```bash
pnpm add mobile-or-tablet

yarn install mobile-or-tablet

npm install mobile-or-tablet
```

## Usage

```tsx
import { isMobile, isMobileOrTablet, isTablet } from "mobile-or-tablet";

if (isMobile()) {
  /* is Mobile */
}
if (isMobileOrTablet()) {
  /* is Mobile Or Tablet */
}
if (isTablet()) {
  /* is Tablet */
}
```

## tsup

Bundle your TypeScript library with no config, powered by esbuild.

https://tsup.egoist.dev/

## How to use this

1. install dependencies

```
# pnpm
$ pnpm install

# yarn
$ yarn install

# npm
$ npm install
```

2. Add your code to `src`
3. Add export statement to `src/index.ts`
4. Test build command to build `src`.
   Once the command works properly, you will see `dist` folder.

```zsh
# pnpm
$ pnpm run build

# yarn
$ yarn run build

# npm
$ npm run build
```

5. Publish your package

```zsh
$ npm publish
```

## test package

https://www.npmjs.com/package/mobile-or-tablet
