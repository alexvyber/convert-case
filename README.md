# Case Convert

Package for converting string cases

## Install

```sh
npm install @alexvyber/convert-case
```

```sh
pnpm add @alexvyber/convert-case
```

```sh
yarn add @alexvyber/convert-case
```

## Example

```ts
import { camelToKebab, kebabToCamel } from "@alexvyber/convert-case"

console.log(camelToKebab("SomeString")) // => some-string
console.log(camelToKebab("otherString")) // => other-string

console.log(kebabToCamel("some-string")) // => SomeString
console.log(kebabToCamel("other-string")) // => OtherString
```

## API

<!-- Generated by documentation.js. Update this documentation by updating the source code. -->

#### Table of Contents

- [camelToKebab](#cameltokebab)
  - [Parameters](#parameters)
  - [Examples](#examples)
- [kebabToCamel](#kebabtocamel)
  - [Parameters](#parameters-1)
  - [Examples](#examples-1)

### camelToKebab

Converts a string from `CamelCase` to `kebab-case`.

#### Parameters

- `input` **T** The string in `CamelCase` to be converted

#### Examples

```javascript
camelToKebab("SomeString") // "some-string"
```

Returns **Kebabtize<T>** The `string` in `kebab-case`

### kebabToCamel

Converts a string from `kebab-case` to `CamelCase`.

#### Parameters

- `input` **T** The string in `kebab-case` to be converted

#### Examples

```javascript
kebabToCamel("some-string") // "SomeString"
```

Returns **Camelize<T>** The string in `CamelCase`
