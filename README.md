# React-Netinfo

> A simple react hook to get network connectivity status

[![NPM](https://img.shields.io/npm/v/@ajay_g/react-netinfo.svg)](https://www.npmjs.com/package/@ajay_g/react-netinfo) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Install

```bash
npm install --save @ajay_g/react-netinfo
```

```bash
yarn add @ajay_g/react-netinfo
```

## Usage

```jsx
import React from "react";
import { useNetworkInfo } from "@ajay_g/react-netinfo";

const App = () => {
  const isOffline = useNetworkInfo();

  if (isOffline) {
    return <div>Sorry, you are offline :(</div>;
  }

  return <div>You are online :)</div>;
};
```

## License

MIT © [Ajay](LICENSE)

---

This hook is created using [create-react-hook](https://github.com/hermanya/create-react-hook).
