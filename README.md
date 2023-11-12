<div align="center">

<div align="center"><h1>external-shallow-equal</h1></div>

![NPM Version](https://badgen.net/npm/v/external-shallow-equal) ![Minizipped Size](https://badgen.net/bundlephobia/minzip/external-shallow-equal) ![Downloads](https://img.shields.io/npm/dm/external-shallow-equal.svg) ![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fidootop%2Fexternal-shallow-equal.svg?type=small)

<div align="center">Equivalent to React's internal shallowEqual, allowing external access to React's shallowEqual function.</div>

<br/>

</div>

## ⚡️ Installation

```bash
npm i external-shallow-equal
```

## 🔥 Usage

```typescript
import { shallowEqual } from "external-shallow-equal";

shallowEqual(0, -0); // false
shallowEqual(NaN, NaN); // true
shallowEqual([1, 2, 3], [1, 2, 3]); // true
```
