# jest-next-dynamic-ts

Inspired by [jest-next-dynamic](https://github.com/FormidableLabs/jest-next-dynamic).

Added TypeScript based on jest-next-dynamic.

GitHub: [jest-next-dynamic-ts](https://github.com/DavidYang2149/jest-next-dynamic-ts)  
npm: [jest-next-dynamic-ts](https://www.npmjs.com/package/jest-next-dynamic-ts)  

## 📚 Install dependencies

```sh
npm install -D jest-next-dynamic-ts
```

## 🧪 Usage

```js
// This will mock `next/dynamic`, so make sure to import it before any of your
// components.
import preloadAll from "jest-next-dynamic-ts";
// This component can have dynamic imports anywhere in its rendered tree,
// including nested dynamic imports.
import SomeComponent from "./SomeComponent";
 
beforeAll(async () => {
  await preloadAll();
});
 
// Your tests here!
```
