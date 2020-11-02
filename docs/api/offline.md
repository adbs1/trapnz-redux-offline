## `offline(config)`

The principle entrypoint to Redux Offline: returns a store enhancer.

```js
import { createStore } from 'redux';
import { offline } from '@adbs1/trapnz-redux-offline';
import config from '@adbs1/trapnz-redux-offline/lib/defaults';

const store = createStore(myReducer, offline(config));
```

See [config documentation](./config.md) for information on customizing the returned store enhancer.
