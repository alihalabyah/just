## just-partial-it

Part of a [library](../../../../) of zero-dependency npm modules that do just do one thing.  
Guilt-free utilities for every occasion.

```js
import partial from 'just-partial-it';

const cubedRoot = partial(Math.pow, _, 1/3);
cubedRoot(10).toFixed(1); // 56.7
cubedRoot(35).toFixed(1); // 16.2
```  
