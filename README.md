# loop-server-errno

Loop server error numbers.

It can be installed using npm:

    $ npm install loop-server-errno

Then, use it like that:

```js

> var errors = require('loop-server-errno');
errors
> { INVALID_TOKEN: 105,
    BADJSON: 106,
    INVALID_PARAMETERS: 107,
    MISSING_PARAMETERS: 108,
    INVALID_AUTH_TOKEN: 110,
    EXPIRED: 111,
    REQUEST_TOO_LARGE: 113,
    INVALID_OAUTH_STATE: 114,
    CLIENT_REACHED_CAPACITY: 121,
    USER_UNAVAILABLE: 122,
    BACKEND: 201,
    ROOM_FULL: 202,
    UNDEFINED: 999 }
```
