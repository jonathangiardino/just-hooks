# just-hooks

> React hooks collection for any &quot;use&quot;. 

[![NPM](https://img.shields.io/npm/v/just-hooks.svg)](https://www.npmjs.com/package/just-hooks) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Install

```bash
npm install --save just-hooks
```

## Usage

```tsx
import * as React from 'react'

import { useMyHook } from 'just-hooks'

const Example = () => {
  const example = useMyHook()
  return (
    <div>
      {example}
    </div>
  )
}
```

## License

MIT © [jonathangiardino](https://github.com/jonathangiardino)

---

This hook is created using [create-react-hook](https://github.com/hermanya/create-react-hook).
