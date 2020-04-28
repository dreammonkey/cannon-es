This is a fork of https://github.com/schteppe/cannon.js made by Stefan Hedman [@schteppe](https://github.com/schteppe). It's a type-safe flatbundle (esm and cjs) for easier handling in module environments and tree shaking. Visit the original project for [full documentation](http://schteppe.github.io/cannon.js/docs/) and examples ([1](http://schteppe.github.io/cannon.js/), [2](http://github.com/schteppe/cannon.js/tree/master/examples), [3](http://github.com/schteppe/cannon.js/tree/master/demos)).

    yarn add cannon-es

```jsx
import { World } from 'cannon-es'

// ...
```

#### TO DO:

- Correct & standardize JSDoc comments
- Fix Octree `as any` assertions, and remove `as any` type assertions wherever possible
- Remove use of defined assertion (!) where possible (profile performance to ensure no degradation)
- Convert to static methods where possible? (memory savings)
- Convert to abstract classes where possible (Equation, Solver, etc.?)
- Test possible performance improvements by converting arrays and objects to Maps
- V-HACD support (https://github.com/react-spring/use-cannon/issues/35#issuecomment-600188994)
- Explore performance enhancements:
    - https://github.com/RandyGaul/qu3e
    - https://github.com/RandyGaul/cute_headers
    - https://github.com/TheRohans/dapao/issues?q=is%3Aissue
    - https://github.com/swift502/Sketchbook/commits/master/src/lib/cannon/cannon.js
    - https://github.com/schteppe/cannon.js/pulls