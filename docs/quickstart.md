# Quick start

Welcome to Cabal!

To start developing using Cabal you must install `cabal-js-sdk` using npm.

```bash
npm i cabal-js-sdk
```

# Basic Template

```js
import cabal from "cabal-js-sdk";

const address_Of_Type_Contract = "0x12345678";
const user_data = "hello@gmail.com";

cabal.put(address_Of_Type_Contract, user_data); //user puts data in
cabal.get(address_Of_Type_Contract); //user gets their own data
```
