## Repro for ImmerJS issue

This is a repro for [Immer issue #<!-- -->718](https://github.com/immerjs/immer/issues/718):

1. Clone this repo
2. `npm install`
3. `npm run build`

The TypeScript compiler prints:

```
node_modules/immer/dist/core/proxy.d.ts:32:35 - error TS2304: Cannot find name 'ProxyHandler'.
```
