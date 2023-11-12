<div align="center">

<div align="center"><strong>react-shallowequal</strong></div>
<div align="center">Equivalent to React's internal shallowEqual, allowing external access to React's shallowEqual function.</div>
<br/>

![NPM Version](https://badgen.net/npm/v/react-shallowequal) ![Minizipped Size](https://badgen.net/bundlephobia/minzip/react-shallowequal) ![Downloads](https://img.shields.io/npm/dm/react-shallowequal.svg) ![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fidootop%2Freact-shallowequal.svg?type=small)

</div>


## ⚡️ Installation
```bash
npm i react-shallowequal
```

## 🔥 Usage

```typescript
import { shallowEqual } from "react-shallowequal";

shallowEqual(0, -0); // false
shallowEqual(NaN, NaN); // true
shallowEqual([1, 2, 3], [1, 2, 3]); // true
```
