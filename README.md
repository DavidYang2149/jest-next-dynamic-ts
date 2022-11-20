# jest-next-dynamic-ts

Inspired by [jest-next-dynamic](https://github.com/FormidableLabs/jest-next-dynamic).

Added TypeScript based on jest-next-dynamic.

# Usage

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
