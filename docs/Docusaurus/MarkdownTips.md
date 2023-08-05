---
title: Markdown Tips
description: A short description of this page
keywords: [apps, describing, the main topics]
---

# Markdown Tips

## Code blocks
### 1 highlight
```jsx title="/src/components/HelloCodeTitle.js" showLineNumbers{1-2,4}
function HelloCodeTitle(props) {
  let a = 1;
  let b = 1;
  let c = 1;
  return <h1>Hello, {props.name}</h1>;
}
```
### 2 highlight&error
you can use `//highlight--line` to highlight or
you can use `//error-line` to show error line
```js
//highlight-line
const name = null;
//error-line
console.log(name.toUpperCase());
// Uncaught TypeError: Cannot read properties of null (reading 'toUpperCase')
```


## Admontition

:::note

Some **content** with _Markdown_ `syntax`. Check [this `api`](#).

:::

:::tip

Some **content** with _Markdown_ `syntax`. Check [this `api`](#).

:::

:::info

Some **content** with _Markdown_ `syntax`. Check [this `api`](#).

:::

:::caution

Some **content** with _Markdown_ `syntax`. Check [this `api`](#).

:::

:::danger

Some **content** with _Markdown_ `syntax`. Check [this `api`](#).

:::




