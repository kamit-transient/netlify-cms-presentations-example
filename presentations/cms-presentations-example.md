---
title: CMS Presentations Example
theme: night
---
# Slideshow Website

*A guide to extending Netlify CMS*

<!--s-->

## Setting up a project

- `npm`/`yarn`
- `webpack`
- `reveal-md`
- any build tool from `gulp` to a shell script

<!--s-->

## Setting up a project

```sh
# yarn
$ yarn add netlify-cms react

# npm
$ npm install --save netlify-cms react
```

<!--s-->

## Creating a new widget

```js
import React, { Component } from "react";

const SlideControl = props => { ... }
const SlidePreview = props => { ... }

export class SlidesControl extends Component { ... }
export const SlidesPreview = props => { ... }
```
