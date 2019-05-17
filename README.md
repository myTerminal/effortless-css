# effortless-css

[![npm version](https://badge.fury.io/js/effortless-css.svg)](https://badge.fury.io/js/effortless-css)
[![npm downloads](https://img.shields.io/npm/dt/effortless-css.svg)](https://www.npmjs.com/package/effortless-css)  
[![License](https://img.shields.io/github/license/myTerminal/effortless-css.svg)](https://opensource.org/licenses/MIT)  
[![NPM](https://nodei.co/npm/effortless-css.png?downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/effortless-css/)

A collection of frequently used {Less} CSS mixins

## How to Use

Install *effortless-css* from NPM

    npm install effortless-css --save-dev

Currently there's only one way to use *effortless-css*: reference the provided *Less* file into a stylesheet.

It could be as simple as

    @import '../../node_modules/effortless-css/less/all.less';

## Available mixins

### Colors

#### `.background-gradient-two-color-top`

Creates a vertical gradient from top to bottom.

Accepts: `@top` (defaulting to `#fff`) and `@bottom` (defaulting to `#000`) for gradient colors and optionally `@fallback` for browsers that do not support gradients. When not provided with `@fallback`, `@top` is used

#### `.background-gradient-two-color-left`

Creates a horizontal gradient from left to right.

Accepts: `@left` (defaulting to `#fff`) and `@right` (defaulting to `#000`) for gradient colors and optionally `@fallback` for browsers that do not support gradients. When not provided with `@fallback`, `@left` is used

#### `.opacity`

Makes an element transparent (as opposed to the name).

Accepts: `@alpha` (defaulting to `1`)

### Shape

#### `.box-sizing`

Sets the box-sizing of an element.

Accepts: `@sizing` (defaulting to `border-box`)

#### `.round-borders`

Makes the corners of an element rounded.

Accepts: `@radius` (defaulting to `50%`)

### Transforms

#### `.transform`

Sets a transform to an element.

Accepts: `@transform` (defaulting to `rotate(0deg)`)

#### `.transform-origin`

Sets the transform origin of an element.

Accepts: `@origin` (defaulting to `50% 50%`)

#### `.transform-style`

Sets the transform style of an element.

Accepts: `@style` (defaulting to `preserve-3d`)

#### `.perspective`

Sets the transform perspective.

Accepts: `@perspective` (defaulting to `500`)

### Misc

#### `.multiple-columns`

Makes an element host multiple columns.

Accepts: `@count` (defaulting to `2`)

#### `.transition`

Sets transition to properties of an element.

Accepts: Duration, a property or any number of properties

#### `.animation`

Sets animation to an element.

Accepts: `@props`

#### `.filter`

Sets a filter to an element.

Accepts: `@prop` (defaulting to `none`)

## To-do

* Include more mixins if possible
