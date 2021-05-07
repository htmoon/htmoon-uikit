# 🥞 HTMoon UIkit

[![Version](https://img.shields.io/npm/v/@htmoon/htmoon-uikit)](https://www.npmjs.com/package/@htmoon/htmoon-uikit) [![Size](https://img.shields.io/bundlephobia/min/@htmoon/htmoon-uikit)](https://www.npmjs.com/package/@htmoon/htmoon-uikit)

HTMoon UIkit is a set of React components and hooks used to build pages on HTMoon's apps. It also contains a theme file for dark and light mode.

## Install

`yarn add @htmoon/htmoon-uikit`

## Setup

### Theme

Before using HTMoon UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from '@htmoon/htmoon-uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from '@htmoon/htmoon-uikit'
...
<ResetCSS />
```

### Types

This project is built with Typescript and export all the relevant types.

## How to use the UIkit

If you want to use components from the UIkit, check the [Storybook documentation](https://pancakeswap.github.io/pancake-uikit/)
