---
layout: docs
title: ES3 member expressions literals transform
description:
permalink: /docs/plugins/transform-es3-member-expression-literals/
---

Turn member expression reserved word properties into literals.

## Example

**In**

```javascript
foo.catch;
```

**Out**

```javascript
foo["catch"];
```

## Installation

```sh
$ npm install babel-plugin-transform-es3-member-expression-literals
```

## Usage

Add the following line to your `.babelrc` file:

```json
{
  "plugins": ["transform-es3-member-expression-literals"]
}
```
