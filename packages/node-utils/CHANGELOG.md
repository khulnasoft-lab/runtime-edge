# @runtime-edge/node-utils

## 2.3.0

### Minor Changes

- Expose `context.waitUntil` for Node.js ([#805](https://github.com/khulnasoft/runtime-edge/pull/805))

## 2.2.4

### Patch Changes

- fix(buildToRequest): double slash path ([`6c683522a2e7f637ed55eaec5891794605235f54`](https://github.com/khulnasoft/runtime-edge/commit/6c683522a2e7f637ed55eaec5891794605235f54))

## 2.2.3

### Patch Changes

- build: upgrade tsup ([#773](https://github.com/khulnasoft/runtime-edge/pull/773))

- fix: expose `performance` constructor ([#772](https://github.com/khulnasoft/runtime-edge/pull/772))

## 2.2.2

### Patch Changes

- Simplify `set-cookie` handling ([#586](https://github.com/khulnasoft/runtime-edge/pull/586))

## 2.2.1

### Patch Changes

- Updated dependencies [[`fb34f31`](https://github.com/khulnasoft/runtime-edge/commit/fb34f3172cf5f32c8e70151c2dcfdc5913ac8b8c)]:
  - @runtime-edge/cookies@3.4.1

## 2.2.0

### Minor Changes

- drop node14 support ([`7cc92cc`](https://github.com/khulnasoft/runtime-edge/commit/7cc92ccd190c2d96483202d9f2e1a523778d1f48))

### Patch Changes

- Updated dependencies [[`7cc92cc`](https://github.com/khulnasoft/runtime-edge/commit/7cc92ccd190c2d96483202d9f2e1a523778d1f48), [`89039c3`](https://github.com/khulnasoft/runtime-edge/commit/89039c3680f9fbef9b83af4b56d94bd3d1cf4253)]:
  - @runtime-edge/cookies@3.4.0

## 2.1.3

### Patch Changes

- Updated dependencies [[`a4a7dc0`](https://github.com/khulnasoft/runtime-edge/commit/a4a7dc09e4ba2debc9d336ca5fca03fea0c60248), [`dc587c2`](https://github.com/khulnasoft/runtime-edge/commit/dc587c27e71cc9f717c9c58de85663156eab914b)]:
  - @runtime-edge/cookies@3.3.0

## 2.1.2

### Patch Changes

- Updated dependencies [[`586de6e`](https://github.com/khulnasoft/runtime-edge/commit/586de6e7bc7bb18121ed2853a4598077a46a21cf)]:
  - @runtime-edge/cookies@3.2.3

## 2.1.1

### Patch Changes

- chore(cookies): expose `.splitCookiesString` ([#473](https://github.com/khulnasoft/runtime-edge/pull/473))

- Updated dependencies [[`8d21ddc`](https://github.com/khulnasoft/runtime-edge/commit/8d21ddc0dd9d37abb02a902f69c3902469a22a68)]:
  - @runtime-edge/cookies@3.2.2

## 2.1.0

### Minor Changes

- Fix `instanceof` tests, upgrade undici and revamp how we import stuff into the VM ([#309](https://github.com/khulnasoft/runtime-edge/pull/309))

## 2.1.0-beta.0

### Minor Changes

- Fix `instanceof` tests, upgrade undici and revamp how we import stuff into the VM ([#309](https://github.com/khulnasoft/runtime-edge/pull/309))

## 2.0.3

### Patch Changes

- Use valid SPDX license expression ([#276](https://github.com/khulnasoft/runtime-edge/pull/276))

## 2.0.2

### Patch Changes

- We are already falling back in code, the types just need to reflect this correctly ([#262](https://github.com/khulnasoft/runtime-edge/pull/262))

## 2.0.1

### Patch Changes

- build: update dependencies ([`029c6af`](https://github.com/khulnasoft/runtime-edge/commit/029c6afe2b1a56a1c105663de6b0d6715a7b4f0a))

## 2.0.0

### Major Changes

- Provides mocked fetch event which throws when using `waitUntil`. `buildToNodeHandler()`'s dependencies now requires `FetchEvent` constructor. ([#244](https://github.com/khulnasoft/runtime-edge/pull/244))

- Uses host header as request origin when available. `buildToNodeHandler()`'s `origin` option has been renamed into `defaultOrigin`. ([#244](https://github.com/khulnasoft/runtime-edge/pull/244))

## 1.0.0

### Patch Changes

- Introducing @runtime-edge/node-utils to run edge-compliant code in Node.js environment ([#219](https://github.com/khulnasoft/runtime-edge/pull/219))
