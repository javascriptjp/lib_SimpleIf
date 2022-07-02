# SimpleIf

Author: [@javascriptjp](https://github.com/javascriptjp)

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/K3K1AQ3A3)

## How to use?

```javascript
const If=v=>a=>a?a(v?!0:!1):v?!0:!1
```

```javascript
console.log(If(1==1)())
//true

console.log(If(1==1)(console.log))
//true
//undefined

If(1==1)(console.log)
//true

If(1)(console.log)
//true

If()(console.log)
//false
```
